# Definir el schema `Task` en OpenAPI

## Objetivos

- Definir `Task` y `TaskInput` en `components/schemas` del documento OpenAPI.
- Incluir en `Task` los campos `id`, `title`, `description` y `completed`.
- Definir `TaskInput` con los campos de entrada, sin `id`, que genera el servidor.
- Declarar explícitamente los campos requeridos y asegurar que el archivo valida como OpenAPI 3.x.

## Notas

- `title` es un `string` requerido.
- `description` es un `string` opcional.
- `completed` es un `boolean` con valor por defecto `false`.
- Está pendiente decidir si `id` será `integer` o `string` con formato UUID.

## Histórico
