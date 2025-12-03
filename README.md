# Digital Twin Interoperability Through AI Agent Protocols

This repository contains the research proposal for the master's thesis **"Enabling Cross-Domain Collaboration in Digital Twin Ecosystems Through AI Agent-Mediated Semantic Interoperability"** conducted at the Institute of Informatics, Federal University of Rio Grande do Sul (UFRGS).

## Overview

This research investigates how AI Agent Protocols can enable semantic interoperability between heterogeneous Digital Twin (DT) systems while preserving their domain-specific optimizations and stakeholder autonomy. The work proposes a Digital Ecosystem architecture leveraging Model Context Protocol (MCP) and Agent-to-Agent (A2A) protocols to facilitate cross-domain collaboration without requiring unified ontologies or disruptive system changes.

## Research Question

**How can AI Agent Protocols improve Digital Twin systems interoperability while preserving existing system autonomy?**

## Overleaf Integration

This project is synchronized with Overleaf for review. To compare local changes with the Overleaf version:

### Setup Overleaf Remote

```bash
# Add Overleaf as a remote repository
git remote add overleaf https://git@git.overleaf.com/67eed6c5ea3465a8417292f3

# Fetch the Overleaf repository
git fetch overleaf --depth 1
```

### Compare with Overleaf

```bash
# Diff local article directory against Overleaf master branch
# Excludes Overleaf-specific configuration files
git diff main:article overleaf/master -- ':(exclude)texmf/' ':(exclude).gitignore' ':(exclude).latexmkrc'

# Save diff to file for review
git diff main:article overleaf/master -- ':(exclude)texmf/' ':(exclude).gitignore' ':(exclude).latexmkrc' > diff.txt
```

## Author

**Henrique Krausburg Correa**  
Master's Student, Institute of Informatics - UFRGS  
Advisor: Prof. Dr. Juliano Araújo Wickboldt

## License

This research is part of academic work at UFRGS. All code and documentation will be made available under appropriate open-source licenses upon completion.

## References

See `article.bib` for complete bibliography.

