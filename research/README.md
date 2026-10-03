# Investigación para la sesión

Consulta: 9 de septiembre de 2026. Alcance: preparar una demo enseñable y mantenible. Las afirmaciones de producto se apoyan en Microsoft Learn y repositorios del equipo; los artículos de expertos aportan experiencias y criterios. No se usa contenido de marketing como una medición propia.

## Decisiones que cambian el contenido

- La extensión VS Code está GA, pero la página actual delimita su explicación al standard harness. Por eso se presenta como ruta específica, sin generalizar al nuevo runtime.
- La referencia actual de PAC incorpora autoría `cli-copilot`. El bootstrap se basa en ese scaffold y evita un YAML inventado.
- El plugin vigente `copilot-studio-plugin` sucede a `skills-for-copilot-studio`. Su README lo califica de experimental y pide PAC posterior a 2.9.3. Ensayamos la versión instalada, no damos por hecho estabilidad del esquema.
- Una skill de ejecución y las skills del asistente de autoría tienen destinatarios distintos. El sandbox del agente tampoco es el equipo del desarrollador.
- Los resultados de este repositorio solo acreditan cálculo local hasta que se complete el ensayo del tenant.
- Actualización 24-sep-2026: el GitHub Copilot harness es GA desde el 2-sep-2026 (S14); en él el consumo empieza al construir. `pac copilot publish` permite publicar desde terminal (S02). No hay confirmación documental de que `cli-copilot` equivalga a ese harness: se comprueba en el ensayo.

## Fuentes prioritarias

| ID | Fuente y autoría | Qué usamos | Límite |
|---|---|---|---|
| S01 | [Harnesses in Copilot Studio](https://learn.microsoft.com/microsoft-copilot-studio/harnesses-overview), Microsoft Learn | Distinguir runtime y capacidades | Verificar disponibilidad en el tenant |
| S02 | [PAC copilot](https://learn.microsoft.com/power-platform/developer/cli/reference/copilot), Microsoft Learn | Parámetros de scaffold y sincronización | La versión instalada debe ofrecerlos |
| S03 | [VS Code extension overview](https://learn.microsoft.com/microsoft-copilot-studio/visual-studio-code-extension-overview), Microsoft Learn | Edición local, Git y estado GA | Página delimitada al standard harness |
| S04 | [Clone agent](https://learn.microsoft.com/microsoft-copilot-studio/visual-studio-code-extension-clone-agent), Microsoft Learn | Ruta standard en VS Code | Clonar Git no clona el agente |
| S05 | [Skills overview](https://learn.microsoft.com/microsoft-copilot-studio/agents-experience/skills-overview), Microsoft Learn | Formato de skill y alcance del harness | No garantiza activación en cada conversación |
| S06 | [Copilot Studio Plugin](https://github.com/microsoft/copilot-studio-plugin), Microsoft CAT | Plugin de autoría y requisitos | Experimental; no apto para afirmar soporte productivo |
| S07 | [New Harness, New Rules?](https://microsoft.github.io/mcscatblog/posts/new-orchestrator-resources/), Giorgio Ughini y equipo CAT; actualizado 2-ago-2026 | Modelo de componentes y recursos actuales | Muestras como referencia, no copiar toda la arquitectura |
| S08 | [The New Copilot Studio Agent Sandbox](https://microsoft.github.io/mcscatblog/posts/copilot-studio-agent-sandbox/), Chris Garty; actualizado 11-ago-2026 | Script revisado, salida en archivos y límites de red/persistencia | Inventario de paquetes puede cambiar |
| S09 | [Live Demo: Claude Code Plugin](https://microsoft.github.io/mcscatblog/posts/claude-copilot-skills-copilot-studio-plugin-demo/), Giorgio Ughini; marzo 2026 | Referencia de un proceso de autoría observado por su autor | Grabado con plugin anterior y standard harness |
| S10 | [Skills for Copilot Studio](https://microsoft.github.io/mcscatblog/posts/skills-for-copilot-studio/), Giorgio Ughini; marzo 2026 | Contexto de la evolución de la autoría | El “20x” del título no es resultado de nuestra demo |
| S11 | [Copilot Studio para administradores](https://practical365.com/copilot-studio-beginner-guide/), Lewis Baybutt; 25-jun-2025 | Criterio práctico sobre entorno, permisos y políticas | No usar como tarifa o inventario de capacidades de 2026 |
| S12 | [Power CAT Copilot Agent Kit](https://github.com/microsoft/Power-CAT-Copilot-Studio-Kit), Microsoft Power CAT | Posible ampliación de pruebas y diagnóstico | No es dependencia del caso básico |
| S14 | [New and improved: GitHub Copilot harness, agent skills, and richer context](https://www.microsoft.com/en-us/microsoft-copilot/blog/copilot-studio/new-and-improved-github-copilot-harness-agent-skills-and-richer-context/), blog de Copilot Studio; 2-sep-2026 | GA del harness y qué sigue en preview | Anuncio de producto; confirmar en el tenant |
| S13 | [Agenda Bizz Summit](https://sessionize.com/api/v2/cg1hr0bv/view/GridSmart), organización | Título, duración y horario publicados | Confirmar cambios cerca del evento |

## Lectura recomendada

Primero S01, S02, S05 y S06 para ejecutar el laboratorio. S07 y S08 ayudan a explicar las decisiones. S09 ofrece una demostración del propio autor; su procedimiento debe actualizarse al plugin vigente. S11 sirve para conversar con administración. S12 tiene sentido después del primer ensayo.

## Lo que no afirmamos

No tenemos una medición propia de velocidad de desarrollo. No se ha creado Circe en un tenant en esta preparación. El esquema de inventario es docente y no reemplaza planificación, reservas, fechas de recepción ni compras de Business Central. Un resultado local correcto no prueba que el agente haya elegido y ejecutado la skill correctamente.

