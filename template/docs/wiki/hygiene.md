# Higiene y Flujo Git

Este proyecto sigue estrictamente la **Biblia de Desarrollo FMG**.

## Commits Atómicos

Se exige el uso de **Conventional Commits**:
`<type>(<scope>): <subject>`

### Tipos Permitidos
- `feat`: Nueva funcionalidad.
- `fix`: Corrección de bug.
- `docs`: Cambios en documentación.
- `style`: Cambios visuales (sin lógica).
- `refactor`: Cambio de código que no añade ni arregla nada.
- `chore`: Tareas de mantenimiento, dependencias.

## Flujo de Ramas

- `main`: Rama de producción (historial lineal).
- `feat/*`: Ramas para nuevas funcionalidades.
- `fix/*`: Ramas para correcciones.

**Prohibido:** `git push --force` a `main`.
