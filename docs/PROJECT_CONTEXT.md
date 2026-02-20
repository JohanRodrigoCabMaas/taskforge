# 🚀 PROJECT_CONTEXT.md
# Proyecto: TaskForge

---

## 📌 1. Objetivo del Proyecto

TaskForge es un proyecto personal creado con el objetivo de:

- Mejorar lógica de programación
- Aprender arquitectura full-stack moderna
- Aplicar buenas prácticas profesionales
- Usar herramientas reales de equipo (Jira, GitHub, commits con issue keys)
- Implementar backend en Go
- Implementar frontend con React + Vite
- Usar MongoDB inicialmente
- Dockerizar la aplicación
- Posteriormente migrar a Supabase
- Integrar validaciones automáticas con Husky

El enfoque principal es aprendizaje progresivo y estructurado.

---

# 🧱 2. Stack Tecnológico

## Backend
- Go
- Estructura modular limpia
- Servidor HTTP propio (luego framework como Gin o Fiber)
- MongoDB (fase inicial)

## Frontend
- React + Vite
- ESLint
- Husky para pre-commit hooks

## Base de Datos
- MongoDB (fase actual de aprendizaje)
- Futuro: Migración a Supabase

## DevOps
- Docker
- Docker Compose
- Variables de entorno
- GitHub + Jira integration

---

# 📂 3. Estado Actual del Proyecto

## ✅ Infraestructura inicial

- Repositorio GitHub creado: `taskforge`
- Estructura base creada:
  - backend/
  - frontend/
  - docs/
- Archivos `.gitkeep` creados
- Primer commit realizado
- GitHub conectado correctamente con Jira
- Commits usando issue keys (ej: TF-1)

## ✅ Backend inicializado

Dentro de `/backend`:

- `go mod init` ejecutado
- Carpeta `cmd/`
- Archivo `cmd/main.go`
- Ejecuta correctamente:

go run ./cmd:
- Imprime: "TaskForge Backend iniciado 🚀"

---

# 🗂 4. Flujo Profesional Definido

## Jira Workflow

Columnas:
- Por hacer
- En curso
- Listo

Reglas:
- Toda tarea se crea primero en Jira
- Cada commit debe incluir issue key (ej: TF-2)
- El commit debe describir claramente el cambio

Ejemplo:

TF-2 inicializar backend en Go

---

## Git Workflow

Convención de commits:
- feat: nueva funcionalidad
- fix: corrección
- chore: tareas técnicas
- refactor: mejora interna

Ejemplo:

TF-3 feat: crear endpoint health

---

# 🛠 5. Plan General del Proyecto

---

## 🔹 FASE 1 — Setup (COMPLETADA)

- Crear proyecto Jira
- Crear repositorio GitHub
- Conectar GitHub con Jira
- Crear estructura base
- Inicializar backend en Go

---

## 🔹 FASE 2 — Backend Base (ACTUAL)

Objetivo: Convertir backend en API real

Pendiente:

- Crear servidor HTTP
- Crear endpoint `/health`
- Estructura limpia:
  - internal/
  - handlers/
  - services/
  - repositories/
- Manejo de errores
- Configuración de variables de entorno
- Logging básico

---

## 🔹 FASE 3 — MongoDB

- Instalar driver oficial
- Conectar base de datos
- Crear modelo simple (Task)
- CRUD completo:
  - Crear tarea
  - Listar tareas
  - Actualizar tarea
  - Eliminar tarea

---

## 🔹 FASE 4 — Frontend (React + Vite)

- Crear proyecto Vite
- Conectar frontend con backend
- Crear UI básica
- Crear CRUD visual
- Manejo de estados

---

## 🔹 FASE 5 — Husky + Calidad de Código

- Instalar Husky en frontend
- Crear hook `pre-commit`
- Validar:
  - ESLint
  - Formato
  - Presencia de issue key

---

## 🔹 FASE 6 — Docker

- Dockerfile backend
- Dockerfile frontend
- docker-compose.yml
- Contenedor MongoDB
- Variables de entorno
- Red interna

---

## 🔹 FASE 7 — Autenticación

- JWT
- Middleware
- Protección de rutas

---

## 🔹 FASE 8 — Migración a Supabase

- Crear proyecto Supabase
- Migrar estructura
- Reemplazar MongoDB
- Ajustar repositorios

---

## 🔹 FASE 9 — Mejoras Avanzadas

Opcionales:

- Tests unitarios
- Clean Architecture formal
- CI/CD en GitHub Actions
- Versionado semántico
- Deploy en nube

---

# 🧠 6. Filosofía del Proyecto

Este proyecto no busca rapidez.
Busca:

- Entender lo que se hace
- Construir base sólida
- Pensar como ingeniero
- Aprender arquitectura real

---

# 📈 Estado Actual de Avance

Fase actual: 🔹 Backend Base  
Próximo paso inmediato: Crear servidor HTTP y endpoint `/health`

---

# 📌 Notas Importantes

- Siempre crear issue antes de trabajar
- Siempre incluir issue key en commit
- No avanzar a frontend sin backend estable
- No usar herramientas avanzadas sin entender la base

---

# 🏁 Meta Final

Tener una aplicación completa:

Frontend (React)  
Backend (Go)  
Base de datos  
Dockerizada  
Con flujo profesional  
Lista para migrar a Supabase  
Con prácticas de ingeniería reales

---

END OF CONTEXT