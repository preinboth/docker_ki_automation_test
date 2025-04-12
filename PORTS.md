# Ports Übersicht

Diese Datei dokumentiert die Ports, die von den Docker-Containern auf dem Host-System verwendet werden.

## Port Mapping Tabelle

| Service | Host Port | Container Port | Beschreibung |
|---------|-----------|----------------|--------------|
| n8n | 5678 | 5678 | Hauptport für den n8n Workflow-Service |
| Ollama | 11434 | 11434 | Port für den Ollama LLM-Service |
| Qdrant | 6333 | 6333 | Port für den Qdrant Vektordatenbank-Service |

## Hinweise

- Alle Ports sind standardmäßig auf dem Host-System verfügbar
- Die Ports sollten nicht von anderen Anwendungen verwendet werden
- Die Konfiguration der Ports erfolgt in der `stack.env` Datei
- Die Port-Mappings sind in der `docker-compose.yml` definiert 