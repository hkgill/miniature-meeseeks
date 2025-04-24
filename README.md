# Verba: The Golden RAGtriever

Welcome to **Verba: The Golden RAGtriever**, an open-source modular framework for Retrieval-Augmented Generation (RAG) applications. Verba provides a streamlined, user-friendly interface for working with your data, supporting both Python backend and a modern Next.js frontend.

---

## 🏗️ Project Structure

- `goldenverba/` — Core Python backend and RAG logic
- `frontend/` — Next.js web frontend (TailwindCSS + DaisyUI)
- `data/` — Example and test data
- `img/` — Images and diagrams
- `Dockerfile`, `docker-compose.yml` — Containerization support

---

## 🚀 Quick Start

### Backend (Python)

1. **Python Version:** Requires Python `>=3.10.0`.
2. **Install dependencies:**
   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -e .
   ```
3. **Run the backend:**
   ```bash
   verba
   # or
   uvicorn goldenverba.server:app --reload
   ```

### Frontend (Next.js)

1. **Node.js Version:** Requires Node.js `>=21.3.0`.
2. **Install dependencies:**
   ```bash
   cd frontend
   npm install
   ```
3. **Run the frontend:**
   ```bash
   npm run dev
   # Visit http://localhost:3000
   ```

---

## 🧩 Key Features

- Modular RAG pipeline: Reader, Chunkers, Embedder, Retriever, Generator
- Pluggable component managers
- Responsive, themeable frontend (Default, Dark, Weaviate themes)
- Markdown/code formatting, document viewer, chat interface
- Docker and Compose support
- Extensible for custom data sources and models

---

## 📦 Building & Deployment

- **Build frontend static files:**
  ```bash
  cd frontend
  npm run build
  ```
- **Docker Compose:**
  ```bash
  docker-compose up
  ```

---

## 📚 Documentation

- [Technical Documentation](TECHNICAL.md) — System architecture and internals
- [Frontend Guide](FRONTEND.md) — Next.js setup and usage
- [Python Tutorial](PYTHON_TUTORIAL.md) — Python/venv setup
- [Contribution Guide](CONTRIBUTING.md)
- [Changelog](CHANGELOG.md)

---

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 📝 License

BSD License. See [LICENSE](LICENSE) for details.

---

## 🌐 Links

- [GitHub Repository](https://github.com/weaviate/Verba)

---

## 🙏 Acknowledgements

Created and maintained by the Weaviate team and community.

---

For more details, see the documentation files in this repository.
