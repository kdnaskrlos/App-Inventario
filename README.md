# App-Inventario · Comic Shop

Dos apps web que comparten el inventario a través de este repositorio.

| App | Enlace | Para qué |
| --- | --- | --- |
| Carga masiva | https://kdnaskrlos.github.io/App-Inventario/ | Genera variantes, SKU y códigos de barras en la computadora. |
| Stock móvil | https://kdnaskrlos.github.io/App-Inventario/movil/ | Consulta el stock y escanea códigos de barras desde el teléfono. |

## Cómo se sincronizan

1. En la carga masiva, toca **Sincronizar → Subir inventario**. Se guarda `data/inventario.json` en este repositorio.
2. La app móvil descarga ese archivo al abrirse y cada vez que vuelves a ella. También hay un botón de actualizar.

El repositorio es público: cualquiera con el enlace puede ver `data/inventario.json`, incluidos costos y precios.

## Versiones

- Carga masiva: v24 (instalable en la PC)
- Stock móvil: v5
