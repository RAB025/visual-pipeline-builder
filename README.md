# Visual Pipeline Builder

A frontend-heavy visual workflow editor built with React Flow, featuring reusable node abstractions, dynamic text-based variables, and DAG validation via a FastAPI backend.

## Features
- Drag-and-drop node-based pipeline editor
- Reusable BaseNode abstraction for rapid node creation
- Auto-resizing Text nodes with dynamic variable handles
- Deterministic edge creation using explicit name matching
- Backend DAG validation and pipeline analysis

## Tech Stack
- Frontend: React, React Flow, Zustand, CSS
- Backend: FastAPI, Python

## Getting Started

### Frontend
```bash
cd frontend
npm install
npm start
