FROM registry.gitlab.com/islandoftex/images/texlive:latest

ARG TEMPLATE_URL
ARG USER_NAME=texlive

USER $USER_NAME

# Get TEXMFHOME value and create the directory
RUN if [ -n "$TEMPLATE_URL" ]; then \
      TEXMFHOME=$(kpsewhich -var-value TEXMFHOME) && \
      mkdir -p "$TEXMFHOME" && \
      curl -L "$TEMPLATE_URL" | tar -xz -C "$TEXMFHOME" && \
      texhash "$TEXMFHOME"; \
    fi
