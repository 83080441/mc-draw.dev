# mc-draw.dev

**Idiomas:** [English](README.md) | Español

Tracker público de bugs, ideas y feedback para **[MC Draw](https://mc-draw.dev)** — un editor de modelos de items de Minecraft en el navegador.

> **Este repositorio no contiene el código fuente.**  
> El desarrollo de MC Draw se hace en un proyecto privado de edición de items ([`itemeditor`](https://github.com/83080441/itemeditor)). Aquí solo se gestionan issues y conversación con la comunidad.

## Qué es MC Draw

[MC Draw](https://mc-draw.dev) te permite diseñar modelos 3D de items a partir de texturas 16×16: arrastra un PNG, edita polígonos y previsualiza el resultado en 3D (GUI, mano, tercera persona, etc.).

> **Aviso:** MC Draw **no está afiliado** a Mojang Studios, Microsoft, Minecraft ni al proyecto Forge. No es un producto oficial de ninguno de ellos.

## Propósito

MC Draw **no es una aplicación comercial**: no incluye publicidad, no busca ganancias personales para el creador y no está orientada a fines de lucro. Su único objetivo es la distribución libre de la herramienta para aportar a las comunidades de modders.

## Cómo funciona

La app se sirve desde un servidor para que puedas abrirla en el navegador, pero **no guarda ni respalda tu trabajo en la red**. No hay cuentas, ni almacenamiento en la nube, ni sincronización remota: todo lo que editás queda en tu dispositivo y es tuyo. Exportás PNG o JSON cuando lo necesitás; nada se retiene del lado del servicio.

## Cómo contribuir

Usa las [Issues](https://github.com/83080441/mc-draw.dev/issues) de este repo para:

- Reportar bugs
- Proponer ideas o mejoras
- Dar feedback sobre la herramienta

Antes de abrir una issue, revisá si ya existe una similar.

### Etiquetas

Las etiquetas del repo se definen en [`.github/labels.yml`](.github/labels.yml) y se sincronizan solas al pushear a `main`.

| Label | Uso |
| --- | --- |
| `bug` | Algo no funciona |
| `enhancement` | Idea o mejora |
| `feedback` | Comentario general |
| `needs info` | Falta información del reporter |
| `export` | PNG / JSON (export o import) |
| `desktop` | Pedidos de versión desktop / Electron |
| `documentation` | Docs / README |
| `question` | Pregunta |
| `duplicate` | Ya existe otra issue |
| `invalid` | No aplica |
| `wontfix` | No se va a implementar |
| `good first issue` | Fácil para empezar |
| `help wanted` | Se busca ayuda |

Las plantillas de issue ya aplican `bug` o `enhancement` al crear la issue.

## FAQ

**¿Cómo nace MC Draw?**  
Por la necesidad de entender y tener una forma visual de crear items complejos sin tener que hacer run cada 3 minutos.

**¿Dónde está el código fuente?**  
En un repositorio privado ([`itemeditor`](https://github.com/83080441/itemeditor)). Este repo (`mc-draw.dev`) es solo el tracker público de issues.

**¿Es gratis? ¿Hay anuncios o suscripciones?**  
Sí, es gratis. No hay publicidad, cuentas de pago ni monetización. El proyecto no tiene fines de lucro.

**¿Mis modelos se guardan en algún servidor?**  
No. No hay respaldos en la red: lo que editás vive en tu navegador/dispositivo. Si querés conservarlo, exportá el PNG o el JSON desde la app.

**¿Necesito una cuenta?**  
No. Abres [mc-draw.dev](https://mc-draw.dev) y listo.

**¿Para qué sirve este repositorio de GitHub?**  
Para reportar bugs, pedir features y dar feedback con la comunidad. No es el código de la app.

**¿Puedo usarlo en mi pack / mod / servidor?**  
Sí: está pensado para aportar a las comunidades de modders. Exportá tus assets y usalos en tu propio proyecto; es opcional mencionar al autor o la herramienta.

**¿Cómo reporto un bug de forma útil?**  
Abrí una [issue](https://github.com/83080441/mc-draw.dev/issues) con la plantilla **Bug report**. Si podés, adjuntá screenshot, PNG o JSON exportado desde el editor.

**¿Existe una versión desktop?**  
Por el momento no: MC Draw es solo web. Si hay demanda pública real (issues), evaluaré crear un proyecto en Electron.

## Enlaces

| Recurso | URL |
| --- | --- |
| App | [https://mc-draw.dev](https://mc-draw.dev) |
| Issues | [github.com/83080441/mc-draw.dev/issues](https://github.com/83080441/mc-draw.dev/issues) |
| Código fuente (privado) | [`itemeditor`](https://github.com/83080441/itemeditor) |

## Licencia

MC Draw se licencia bajo la **[PolyForm Noncommercial License 1.0.0](LICENSE)** (`PolyForm-Noncommercial-1.0.0`).

Podés usarla con fines **personales y no comerciales** (por ejemplo mods, proyectos hobby, aprendizaje). El **uso comercial no está permitido** bajo esta licencia.

- Los PNG / JSON que exportés con la app son **tuyos**.
- Este tracker público es para issues y feedback; el código de la app está en un repo privado, pero el uso de la app distribuida en [mc-draw.dev](https://mc-draw.dev) se ofrece bajo los mismos términos permitidos.
