# Project Memory Assistant

> Herramienta de escritorio para organizar, documentar y mantener contexto persistente de proyectos de desarrollo. Funciona como memoria estructurada para asistentes de IA externos de programación.

![Version](https://img.shields.io/badge/version-0.1.0-blue)
![Platform](https://img.shields.io/badge/platform-Windows%2011-lightgrey)
![Status](https://img.shields.io/badge/status-en%20desarrollo-yellow)
![License](https://img.shields.io/badge/license-MIT-green)

---

## ¿Qué es?

Project Memory Assistant es una aplicación de escritorio construida con Electron + React que actúa como asistente de memoria estructurada para proyectos de desarrollo.

**No genera código.** Su función es organizar, clasificar, documentar y mantener el contexto de tus proyectos para que puedas trabajar de forma más efectiva con IAs externas de programación.

---

## Características principales

- 📁 **Importar proyectos** desde carpetas existentes o desde JSON generado por otra IA
- 🌳 **Vista de estructura** — árbol de archivos expandible con doble click para abrir en VS Code
- 🐛 **Gestión de bugs** — CRUD completo con severidad, prioridad y estado
- 💡 **Gestión de mejoras** — registro y seguimiento de ideas y mejoras pendientes
- 🖥️ **Vista de servidor** — gestión de infraestructura cloud con wizard guiado (AWS)
- 🗺️ **Mapa visual** de servicios con react-flow
- ⚡ **IaC determinista** — generación de comandos CloudShell por proveedor y fases
- 🔐 **Variables de entorno** encriptadas con AES-256-GCM
- 📝 **Documentación automática** — genera README (Markdown) y contexto para IA (JSON)
- 🤖 **Chat con IA** — Ollama local para contexto de proyecto, Gemini para infraestructura
- 💾 **Persistencia total** — todo se guarda en JSON local, sin base de datos externa

---

## Stack técnico

| Capa | Tecnología |
|---|---|
| Desktop | Electron |
| Frontend | React + TypeScript |
| Build | Vite v8 |
| Estilos | TailwindCSS v4 |
| Estado | Zustand |
| Validación | Zod |
| IA local | Ollama (`llama3.2`) |
| IA cloud | Gemini API (`gemini-2.0-flash`) |
| Mapa | @xyflow/react |
| Persistencia | JSON local + localStorage |

---

## Requisitos previos

### Node.js
```bash
# Versión recomendada: v24.x (gestionado con nvm)
nvm use 24
