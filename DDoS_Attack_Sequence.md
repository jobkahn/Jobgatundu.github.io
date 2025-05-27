---mermaid
sequenceDiagram
config:
  Look: handDrawn
  theme: neutral
---
flowchart LR
A[Attacker]{Hacker Launch attack} --> B[controller server]{The server is compromissed}
B --> [Bots] --> C[Firewall] 
C --> D[Target Server]{The affected server receives thousands of requst and is unable to respond to request}
