# Circe · Copilot Studio desde VS Code

Material de la sesión de Javier Armesto en **Bizz Summit ES 2026**, celebrada el 3 de octubre de 2026.

Construimos un asistente de compras con instrucciones, conocimiento y una skill de reposición. Después cambiamos una regla de negocio y observamos su efecto sobre la misma propuesta. Todos los datos son ficticios; la demo no conecta con Business Central ni crea pedidos.

## Materiales

- [PowerPoint v4](slides/BizzSummit2026_Circe_Compras_v4.pptx): presentación y notas del ponente.
- [Guía HTML de la demo con Claude Code](docs/05-demo-en-escenario.html): órdenes `/demo-*`, explicación y botones para copiar.
- [Guía HTML de la mini demo con GitHub Copilot Chat](docs/08-mini-demo-copilot-chat.html): Init, Architect, Manage y Describer.
- [Guía de escenario en Markdown](docs/05-demo-en-escenario.md).
- [Guion de la sesión](docs/04-guion-ponente.md).
- [Fuentes y documentación](research/README.md).

Descarga los HTML y ábrelos en el navegador. GitHub muestra su código, no la interfaz. El índice de materiales puede abrirse desde `dist/index.html` sin conexión.

## ¿Dónde ejecuto la demo?

**El código operativo está en [circe-compras-copilot-studio](https://github.com/javiarmesto/circe-compras-copilot-studio).** Clona ese repositorio para utilizar el agente, las skills, los datos, los scripts y las órdenes de Claude Code.

Este repositorio contiene la charla y sus guías. Se han retirado las copias antiguas del código para evitar dos versiones distintas de la demo.

## Antes de copiar los comandos

Sustituye `TU_ORGANIZACION` por la URL de tu entorno y adapta las rutas `C:\Demos` a tu equipo. El agente de respaldo es opcional y debes prepararlo tú. No se incluyen accesos, agentes publicados ni configuración de ningún tenant.

La sesión se completó satisfactoriamente según su ponente. Eso no valida automáticamente otra instalación, versión del plugin o recorrido complementario. Consulta los requisitos en el repositorio de la demo.

## Editar estos materiales

El PowerPoint canónico es la v4. Su copia `Circe-Copilot-Studio-BizzSummit-2026.pptx` mantiene los enlaces anteriores. Consulta [slides/README.md](slides/README.md) para conocer los ajustes de privacidad.

Los nombres y marcas de productos pertenecen a sus titulares. El plugin de Microsoft se distribuye y mantiene en su propio repositorio; este material de comunidad no implica soporte oficial.
