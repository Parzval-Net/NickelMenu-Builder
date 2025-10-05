# Guía de Contribución

¡Gracias por tu interés en NickelMenu Builder! Toda ayuda es bienvenida: reportes de bugs, ideas o código nuevo.

## Código de conducta

Este proyecto se rige por el [Código de Conducta](CODE_OF_CONDUCT.md). Al participar aceptas respetarlo.

## Cómo reportar un bug

1. Revisa que no exista ya un issue con el mismo problema.
2. Crea un issue con:
   - Pasos para reproducir.
   - Comportamiento esperado vs. real.
   - Capturas/pantallas si aplica.
   - Información del navegador/sistema.

## Proponer mejoras

- Puedes abrir un issue de tipo "feature request".
- Describe el caso de uso y por qué sería útil para la comunidad.

## Flujo de trabajo para pull requests

1. Haz un fork y crea una rama descriptiva (`feature/unicode-filters`).
2. Si editas el HTML monolítico:
   - Mantén la indentación de 2 espacios en `<style>` y `<script>`.
   - Evita incluir recursos externos innecesarios.
3. Ejecuta pruebas manuales: recorre los 4 pasos del asistente y revisa tema claro/oscuro.
4. Actualiza la documentación/release notes si agregas cambios relevantes.
5. Envía el PR y describe claramente qué resuelve.

## Estilo y calidad

- Prioriza la accesibilidad (focus states, aria-labels, etc.).
- Usa comentarios solo cuando el código no se explique por sí mismo.
- Los textos deben estar en español neutro.

## Lanzamientos

Los releases se documentan en [CHANGELOG.md](CHANGELOG.md). Añade una entrada bajo "Unreleased" y actualiza cuando se publique la versión.

## ¿Preguntas?

Abre un issue o contáctame mediante la sección de discusiones del repositorio.
