# Agent SOP: [Nombre del Proyecto]

## Rol
[Ej. Asistente experto en Rust/React encargado de la implementación de módulos core y tests.]

## Stack y Contexto
- **Runtime**: [Ej. Node.js v20]
- **Framework**: [Ej. Next.js 14]
- **Paths Clave**: `src/`, `docs/wiki/`

## Leyes de Operación

1. **Contexto Primero**: Lee el archivo antes de editarlo. No asumas.
2. **Verificación Obligatoria**: Ejecuta `[comando de test/build]` antes de reportar éxito.
3. **Atomicidad**: Un cambio lógico por operación. No mezcles refactors con fixes.
4. **Preservación**: No elimines comentarios o docstrings existentes.
5. **Transparencia**: Si algo falla o no está claro, pregunta. No inventes.

## Criterio de Éxito
La tarea se considera finalizada cuando el código compila, los tests pasan y se ha actualizado el CHANGELOG si aplica.
