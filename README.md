# Boot camp de Github actions.

## Sesion 1

### Github Actions

Herramienta que ayuda a automatizar tareas en el desarrollo de software.
- Uso para CD/CI

### Workflows

Se ejecuntan de acuerdo a eventos especificos
- push
- merge
- pull_request

### Casos de Uso

Automatizacion de:

- build
- testing
- Notificationes
- Escaneo de seguridad
- otros

### Conceptos Prueba

- Workflows
  - Conjunto de procesos automatizados definidos en un archivo YAML dentro de .github/workflows
- Triggers
  - Eventos que desencadenan la ejecución de un workflow
- Jobs
  - Conjunto de pasos que se ejecutan en un workflow, ej. subir a produccion y notificación ejecucion.
- Steps
  - Pasos individuales dentro de un job
- Runners
  - Máquinas que ejecutan los workflows
