<div align="center">

# Engram

### Your Personal Knowledge Engine

*Don't organize your knowledge. Let Engram understand it.*

---

[Overview](docs/01_Project/01_Project_Overview.md) •
[Documentation](docs/) •
[Architecture](docs/03_Architecture/) •
[Roadmap](docs/09_Roadmap/) •
[Contributing](CONTRIBUTING.md)

</div>

---

# What is Engram?

Engram is an AI-powered Personal Knowledge Management (PKM) platform designed to automatically understand, organize, and connect knowledge from multiple sources.

Instead of manually creating folders, tags, and notebooks, Engram analyzes your content and builds a structured knowledge base that grows as you learn.

Supported content includes:

- 📷 Screenshots
- 📄 PDF files
- 📝 Notes
- 🖼 Images
- 📚 Documents
- 🔗 Links *(Future)*
- 🎥 Videos *(Future)*
- 🎙 Audio *(Future)*

---

# ❓ The Problem

Modern learners collect information everywhere:

- ChatGPT conversations
- PDFs
- Books
- Screenshots
- YouTube
- GitHub
- Google Drive
- Notes

After a few weeks, finding a specific piece of information becomes difficult.

Current note-taking applications still require users to manually organize everything.

Knowledge becomes fragmented.

---

# 💡 Our Solution

Engram automatically:

- Extracts text from documents and images
- Understands the meaning of the content
- Detects important concepts
- Groups similar information
- Builds a Knowledge Graph
- Creates a searchable personal knowledge base
- Provides AI-powered retrieval

No manual folders.

No manual tagging.

No manual organization.

---

# Core Features

- AI Knowledge Extraction
- OCR for Images
- PDF Parsing
- Semantic Search
- Automatic Categorization
- Knowledge Graph
- AI Study Assistant
- Offline AI Support (Ollama)
- Local-first Architecture
- Reference Builder
- Personal Knowledge Memory

---

# Core Idea

Traditional storage:

```
Folders

└── AI
    └── Deep Learning
        └── Transformer.pdf
```

Engram:

```
Transformer

├── Screenshot
├── PDF
├── Notes
├── Chat History
├── Related Concepts
├── Projects
└── References
```

Knowledge comes first.

Files become evidence.

---

# Architecture

```
                User

                  │

          Frontend (Next.js)

                  │

         FastAPI Backend

                  │

      Knowledge Processing Layer

      ├── OCR
      ├── Parsing
      ├── Embeddings
      ├── LLM
      └── Knowledge Extraction

                  │

      ├── PostgreSQL
      ├── pgvector
      ├── Neo4j
      └── MinIO
```

More details are available in:

docs/03_Architecture/

---

# Technology Stack

To be added later

Complete stack:

requirements/Tech_Stack.md

---



# Project Goals

- Build a true second brain
- Organize knowledge automatically
- Eliminate manual folders
- Improve knowledge retrieval
- Enhance learning efficiency
- Keep user data private

---

# Roadmap

MVP

- File Upload
- OCR
- AI Categorization
- Semantic Search

---

Version 1

- Knowledge Graph
- AI Chat
- Reference Builder

---

Future

- Browser Extension
- Mobile App
- Video Understanding
- Audio Understanding
- Team Workspace
- Plugin System

---

# Contributing

We welcome contributions from developers, designers, researchers, and AI enthusiasts.

Please read:

CONTRIBUTING.md

---

# License

This project will be released under the MIT License.

---

<div align="center">

## Engram

*"Knowledge should organize itself."*

</div>