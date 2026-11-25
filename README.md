# RumboEdu — MVP

Plataforma web para el seguimiento y acompañamiento académico de estudiantes de educación media (10.º a 12.º grado) en Panamá.

## Objetivo del MVP

Integrar en un solo perfil académico los indicadores clave de cada estudiante —**calificaciones, asistencia, entrega de tareas y participación**— junto con el seguimiento del registro oportuno de calificaciones, para identificar cambios significativos entre periodos y generar alertas de apoyo para docentes y orientadores.

> **Nota ética y legal:** RumboEdu cumple con los lineamientos de la Ley N.º 81 de 2019 (Protección de Datos Personales de Panamá), utiliza acceso restringido por rol y no realiza diagnósticos psicológicos ni predicciones definitivas de deserción escolar.

## Stack Tecnológico

- **Frontend:** React (Web SPA)
- **Backend:** Node.js LTS (REST API)
- **Base de datos:** PostgreSQL 16
- **Control de versiones:** Git & GitHub

## Estructura del Repositorio

```text
.
├── docs/        # Documentación de gestión y planificación del proyecto
├── frontend/    # Aplicación web en React (SPA)
├── backend/     # API REST en Node.js
├── database/    # Esquemas SQL, migraciones y datos de prueba anonimizados
├── .gitignore
├── .gitattributes
└── README.md
```

## Módulos Principales del MVP

1. Autenticación y roles diferenciados (`docente`, `orientador`, `padre/representante`, `estudiante`).
2. Gestión de estudiantes, asignaturas y periodos académicos.
3. Registro de calificaciones, asistencia, entrega de tareas y participación.
4. Control y recordatorios de registro oportuno de calificaciones.
5. Visualización de trayectoria académica y comparación entre periodos.
6. Generación de alertas académicas e historial básico de seguimiento.
7. Reportes académicos básicos.

## Flujo de Trabajo en Git (Equipo)

- **`main`**: rama estable lista para demos y validación.
- **`develop`**: rama de integración para el desarrollo continuo (opcional).
- **`feature/<modulo>`**: ramas por funcionalidad (ej. `feature/auth`, `feature/asistencia`, `feature/alertas`).

```bash
# Crear una nueva rama de funcionalidad
git checkout -b feature/nombre-modulo

# Guardar cambios
git add .
git commit -m "feat: descripción breve del cambio"

# Subir cambios al remoto
git push -u origin feature/nombre-modulo
```

## Equipo del Proyecto

- **Natalia Bernal** — Gestora de Proyecto
- **Erick Tenorio** — Desarrollador de Software
