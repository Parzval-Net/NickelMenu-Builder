# NickelMenu Builder

NickelMenu Builder es una webapp de una sola página que te ayuda a crear configuraciones personalizadas para [NickelMenu](https://github.com/pgaskin/NickelMenu), una herramienta imprescindible para ampliar las funciones de los eReaders Kobo.

> **Abierto y libre.** Este proyecto se distribuye bajo la licencia MIT y está pensado para la comunidad hispanohablante que quiere configurar su Kobo sin complicaciones.

## Características

- Asistente paso a paso para definir contextos, acciones y personalizaciones.
- Biblioteca de acciones populares y búsqueda con filtros por contexto.
- Personalización de iconos Unicode y previsualización estilo Kobo.
- Editor rápido para los datos del propietario (`owner.sh`).
- Soporte para icono personalizado (PNG ≤ 64×64 px y ≤ 10 KB).
- Validación integrada y exportación en un clic (`config`).
- Tema claro/oscuro persistente y diseño responsive.

## Demo rápida

1. Clona o descarga este repositorio.
2. Abre `index.html` en tu navegador preferido (no requiere servidor).
3. Sigue los 4 pasos del asistente.
4. Exporta tu configuración y cópiala a `KOBOeReader/.adds/nm/config`.

## Requisitos

- Navegador moderno (Chromium, Firefox, Safari). No se necesitan dependencias.
- NickelMenu instalado en tu lector Kobo.

## Estructura del proyecto

```
├── index.html              # Webapp autosuficiente (HTML + CSS + JS)
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── CHANGELOG.md
```


## Uso

- **Crear configuración:** sigue el flujo del asistente y usa la validación antes de exportar.
- **Unicode personalizado:** selecciona una acción y elige un símbolo; la vista previa se actualiza al instante.
- **Icono personalizado:** sube un PNG y el asistente lo vinculá automáticamente en la sección experimental.

## Desarrollo

El proyecto está pensado para mantenerse como un único HTML.

### Comandos sugeridos

No hay scripts, pero puedes usar [http-server](https://www.npmjs.com/package/http-server) u otro servidor estático si necesitas pruebas con HTTPS/localStorage cruzado:

```bash
npx http-server -o index.html
```

## Contribuir

Las contribuciones son bienvenidas. Consulta [CONTRIBUTING.md](CONTRIBUTING.md) para conocer el flujo de trabajo y [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) para mantener un ambiente respetuoso.

## Licencia

Este proyecto se distribuye bajo la licencia [MIT](LICENSE).

## Créditos

- Inspirado en el ecosistema generado por la comunidad de NickelMenu.
- Iconografía Unicode recopilada a partir de la documentación oficial.

¡Disfruta creando menús personalizados para tu Kobo!
