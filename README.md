<div align="center">

# Daniel Zuñiga

**Software & Infrastructure** · Autodidacta colombiano

[![Portfolio](https://img.shields.io/badge/portfolio-danzuniga.xyz-ff4d1c?style=flat-square)](https://danzuniga.xyz)
[![CV](https://img.shields.io/badge/CV-descargar-1c1b18?style=flat-square)](https://danzuniga.xyz/cv.html)
[![Email](https://img.shields.io/badge/email-danielzunigazb%40gmail.com-555?style=flat-square)](mailto:danielzunigazb@gmail.com)

</div>

---

### `$ whoami`

Construyo herramientas de infraestructura, automatización y apps nativas.
Aprendo trasteando con Linux hasta que termino con un pipeline, un framework
o un servicio systemd que resuelve un problema real — luego lo documento y
lo pruebo como si otra persona tuviera que mantenerlo mañana.

Terminales sobre GUIs. Protocolos sobre frameworks. Evidencia sobre claims.

### Proyectos

- **[player](https://github.com/danielzunigazb/player)** — reproductor de música nativo para Android (Kotlin, Compose, Media3). Letras sincronizadas, terminal integrada, monitor web con cifrado de punta a punta (con la cola reordenable desde el navegador) y releases automáticos firmados. Va en la v1.6.1. [player.danzuniga.xyz](https://player.danzuniga.xyz)
- **[gocraft](https://github.com/danielzunigazb/gocraft)** — reimplementación del cliente de Minecraft Java 1.8.9 (protocolo 47) en Go, con servidor compatible. OpenGL 3.3, mundos Anvil o servidores de terceros, sin recursos de Mojang (los lee del `client.jar` del usuario). Fidelidad con vanilla fijada con pruebas que reproducen paquetes contra el cliente.
- **[editor](https://github.com/danielzunigazb/editor)** — editor de video no lineal (MLT + FFmpeg) manejado por un LLM vía servidor MCP, con app web de chat en Docker. 42 herramientas, 15 plantillas y suites de pruebas con hashes de píxeles.
- **harness** — CLI que orquesta agentes de código (Claude Code headless) sobre repos reales: planea, ejecuta paso a paso y verifica cada paso con los tests, lint y build del propio repo. "El modelo dice que terminó" no cuenta como evidencia. TypeScript, TUI de tres paneles. Privado.
- **zwm** — gestor de ventanas en mosaico para X11 escrito en Zig: árbol BSP, barra, panel, lanzador, música por Spotify Connect y bloqueo de pantalla con PAM. Privado.
- **[galaxy-vitals-bridge](https://github.com/danielzunigazb/galaxy-vitals-bridge)** — app Android que lee métricas de Samsung Health (Galaxy Fit3) y las publica en [danzuniga.xyz/status](https://danzuniga.xyz/status/). Las coordenadas nunca salen del teléfono.

### Cómo trabajo

| | |
|---|---|
| **Reproducibilidad** | Sin binarios sin checksum. Todo pipeline se reconstruye desde cero con un comando. |
| **Documentación** | ADRs para decisiones, READMEs funcionales. Tan rigurosa como el código. |
| **Testing** | Si no tiene tests, no está terminado. Cobertura ≥85%, CI gates obligatorios. |
| **Estándares** | XDG Base Directory, systemd para servicios. Cero hardcodeo de rutas. |

### Stack

`Python` `Kotlin` `Go` `TypeScript` `Zig` `Bash` `SQL` · `FastAPI` `Typer` `Jetpack Compose` `MCP` `Pytest` `uv` `Ruff` · `Arch Linux` `systemd` `Docker` `Git` `GitHub Actions` `SSH`

---

<div align="center">
<sub>Córdoba, Colombia · <a href="https://danzuniga.xyz">danzuniga.xyz</a></sub>
</div>
