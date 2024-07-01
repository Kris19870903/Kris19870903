. **GitHub/GitLab**: Umieść kod bezpośrednio w pliku `README.md` lub innym pliku Markdown w repozytorium. GitHub i GitLab automatycznie renderują diagramy Mermaid w podglądzie plików Markdown.
   
   ```markdown
   # Proces przyjęcia towarów

   ```mermaid
   graph TD
       A[Odbiór towarów] --> B[Kontrola jakości]
       B --> C[Identyfikacja i etykietowanie]
       C --> D[Wprowadzenie towarów do systemu magazynowego]
       D --> E[Przypisanie towarów do lokalizacji składowania]

       A --> |Technologie wspierające| A1[Skanery kodów kreskowych]
       A1 --> A
       B --> |Technologie wspierające| B1[RFID]
       B1 --> B
       C --> |Technologie wspierające| C1[AIDC]
       C1 --> C
       D --> |Technologie wspierające| D1[WMS]
       D1 --> D
javascript
Skopiuj kod

2. **MkDocs z rozszerzeniem Mermaid**: Jeśli używasz MkDocs do generowania dokumentacji, upewnij się, że masz zainstalowane rozszerzenie Mermaid. W pliku konfiguracyjnym `mkdocs.yml` dodaj rozszerzenie Mermaid:

```yaml
markdown_extensions:
  - pymdownx.superfences
  - pymdownx.mark
  - pymdownx.highlight
  - pymdownx.inlinehilite
  - pymdownx.magiclink
  - pymdownx.smartsymbols
  - pymdownx.tasklist
  - pymdownx.tilde
  - pymdownx.details
  - pymdownx.critic
  - pymdownx.snippets
  - pymdownx.keys
  - pymdownx.emoji
  - pymdownx.betterem
  - pymdownx.striphtml
  - pymdownx.progressbar
  - pymdownx.arithmatex
  - pymdownx.saneheaders
  - pymdownx.b64
  - pymdownx.smartsymbols
  - pymdownx.tilde
  - pymdownx.snippets
  - pymdownx.keys
  - pymdownx.emoji
  - pymdownx.details
  - pymdownx.critic
  - pymdownx.snippets
  - pymdownx.mark
  - pymdownx.superfences
  - pymdownx.tabbed
  - pymdownx.inlinehilite
  - pymdownx.magiclink
  - pymdownx.tasklist
  - pymdownx.arithmatex
  - pymdownx.striphtml
  - pymdownx.progressbar
  - pymdownx.keys
  - pymdownx.details
  - pymdownx.tilde
  - pymdownx.snippets
  - pymdownx.keys
  - pymdownx.emoji
  - pymdownx.betterem
  - pymdownx.smartsymbols
  - pymdownx.tilde
  - pymdownx.snippets
  - pymdownx.keys
  - pymdownx.emoji
  - pymdownx.details
  - pymdownx.critic
  - pymdownx.snippets
  - pymdownx.mark
  - pymdownx.superfences
  - pymdownx.tabbed
  - pymdownx.inlinehilite
  - pymdownx.magiclink
  - pymdownx.tasklist
  - pymdownx.arithmatex
  - pymdownx.striphtml
  - pymdownx.progressbar
  - pymdownx.keys
  - pymdownx.details
  - pymdownx.tilde
  - pymdownx.snippets
  - pymdownx.keys
  - pymdownx.emoji
  - pymdownx.betterem
  - pymdownx.smartsymbols
  - pymdownx.tilde
  - pymdownx.snippets
  - pymdownx.keys
  - pymdownx.emoji
  - pymdownx.details
  - pymdownx.critic
  - pymdownx.snippets
  - pymdownx.mark
  - pymdownx.superfences
  - pymdownx.tabbed
  - pymdownx.inlinehilite
  - pymdownx.magiclink
  - pymdownx.tasklist
  - pymdownx.arithmatex
  - pymdownx.striphtml
  - pymdownx.progressbar
  - pymdownx.keys
  - pymdownx.details
  - pymdownx.tilde
  - pymdownx.snippets
  - pymdownx.keys
  - pymdownx.emoji
  - pymdownx.betterem
  - pymdownx.smartsymbols
  - pymdownx.tilde
  - pymdownx.snippets
  - pymdownx.keys
  - pymdownx.emoji
  - pymdownx.details
  - pymdownx.critic
  - pymdownx.snippets
  - pymdownx.mark
  - pymdownx.superfences
  - pymdownx.tabbed
  - pymdownx.inlinehilite
  - pymdownx.magiclink
  - pymdownx.tasklist
  - pymdownx.arithmatex
  - pymdownx.striphtml
  - pymdownx.progressbar
  - pymdownx.keys
  - pymdownx.details
  - pymdownx.tilde
  - pymdownx.snippets
  - pymdownx.keys
  - pymdownx.emoji
  - pymdownx.betterem
  - pymdownx.smartsymbols
  - pymdownx.tilde
  - pymdownx.snippets
  - pymdownx.keys
  - pymdownx.emoji
  - pymdownx.details
  - pymdownx.critic
  - pymdownx.snippets
  - pymdownx.mark
  - pymdownx.superfences
  - pymdownx.tabbed
  - pymdownx.inlinehilite
  - pymdownx.magiclink
  - pymdownx.tasklist
  - pymdownx.arithmatex
  - pymdownx.striphtml
  - pymdownx.progressbar
  - pymdownx.keys
  - pymdownx.details
  - pymdownx.tilde
  - pymdownx.snippets
  - pymdownx.keys
  - pymdownx.emoji
  - pymdownx.betterem
  - pymdownx.smartsymbols
  - pymdownx.tilde
  - pymdownx.snippets
  - pymdownx.keys
  - pymdownx.emoji
  - pymdownx.details
  - pymdownx.critic
  - pymdownx.snippets
  - pymdownx.mark
  - pymdownx.superfences
  - pymdownx.tabbed
  - pymdownx.inlinehilite
  - pymdownx.magiclink
  - pymdownx.tasklist
  - pymdownx.arithmatex
  - pymdownx.striphtml
  - pymdownx.progressbar
  - pymdownx.keys
  - pymdownx.details
  - pymdownx.tilde
  - pymdownx.snippets
  - pymdownx.keys
  - pymdownx.emoji
  - pymdownx.betterem
  - pymdownx.smartsymbols
  - pymdownx.tilde
  - pymdownx.snippets
  - pymdownx.keys
  - pymdownx.emoji
  - pymdownx.details
  - pymdownx.critic
  - pymdownx.snippets
  - pymdownx.mark
  - pymdownx.superfences
  - pymdownx.tabbed
  - pymdownx.inlinehilite
  - pymdownx.magiclink
  - pymdownx.tasklist
  - pymdownx.arithmatex







Kontynuuj generowanie


