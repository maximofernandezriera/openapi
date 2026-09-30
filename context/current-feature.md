# Respuestas de error y códigos de estado

## Objetivos

- Estandarizar el manejo de errores en toda la especificación OpenAPI.
- Definir el schema `Error` en `components/schemas`, con campos como `code` y `message`.
- Definir respuestas reutilizables `400`, `404` y `500` en `components/responses`.
- Aplicar `400` a cuerpos de petición inválidos y `404` donde corresponda.
- Asegurar que todas las respuestas de error usan el schema `Error` y que no haya respuestas de error duplicadas entre endpoints.

## Notas

- Issue de referencia: [#4 — Respuestas de error y códigos de estado](https://github.com/maximofernandezriera/openapi/issues/4).

## Histórico

- 2026-09-30: Estandarizadas las respuestas de error en `openapi.yaml` con el schema `Error` y respuestas reutilizables `400`, `404` y `500` aplicadas a los endpoints.
- 2026-09-30: Documentados `GET /tasks` y `GET /tasks/{id}` en `openapi.yaml`, con referencias a `Task`, ejemplos de respuesta, parámetro `id` y respuesta `404`.
