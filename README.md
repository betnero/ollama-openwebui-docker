# ollama-openwebui-docker
 A Dockerized local LLM stack featuring Ollama and Open WebUI for efficient, private AI model interaction.


# Ollama + Open WebUI Docker Setup

This repository contains a Docker Compose setup to run:

- [Ollama](https://ollama.com/)
- [Open WebUI](https://github.com/open-webui/open-webui)

## 📦 Getting Started

```bash
git clone https://github.com/betnero/ollama-openwebui-docker.git
docker-compose up -d


🔌 Ports
Ollama runs on host port: 11434
Open WebUI runs on host port: 1234

📂 Volumes
Ollama data: ./data/ollama
Open WebUI data: ./data/openwebui

Launch
OpenWebUI available at:
http://localhost:1234/
