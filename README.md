<div align="center">

# Daniel Zuñiga

**Software & Infrastructure** · Autodidacta colombiano

[![Portfolio](https://img.shields.io/badge/portfolio-danzuniga.xyz-ff4d1c?style=flat-square)](https://danzuniga.xyz)
[![CV](https://img.shields.io/badge/CV-descargar-1c1b18?style=flat-square)](https://danzuniga.xyz/cv.html)
[![Email](https://img.shields.io/badge/email-danielzunigazb%40gmail.com-555?style=flat-square)](mailto:danielzunigazb@gmail.com)

</div>

---

### `$ whoami`

Construyo herramientas de infraestructura, automatización y bioinformática.
Aprendo trasteando con Linux hasta que termino con un pipeline, un framework
o un servicio systemd que resuelve un problema real — luego lo documento y
lo pruebo como si otra persona tuviera que mantenerlo mañana.

Terminales sobre GUIs. Protocolos sobre frameworks. Evidencia sobre claims.

### Ahora mismo

- **[player](https://github.com/danielzunigazb/player)** — reproductor de música nativo para Android (Kotlin, Compose, Media3). Letras sincronizadas, terminal integrada, monitor web con cifrado de punta a punta y releases automáticos firmados. [player.danzuniga.xyz](https://player.danzuniga.xyz)
- **[editor](https://github.com/danielzunigazb/editor)** — editor de video no lineal (MLT + FFmpeg) manejado por un LLM vía servidor MCP, con app web de chat en Docker. 42 herramientas, 15 plantillas y suites de pruebas con hashes de píxeles.
- **[galaxy-vitals-bridge](https://github.com/danielzunigazb/galaxy-vitals-bridge)** — app Android que lee métricas de Samsung Health (Galaxy Fit3) y las publica en [danzuniga.xyz/status](https://danzuniga.xyz/status/). Las coordenadas nunca salen del teléfono.
- **[fungi-discovery](https://github.com/danielzunigazb/fungi-discovery)** — pipeline reproducible de identificación taxonómica (ITS) para hongos. Typer + BioPython + BLAST/VSEARCH, cobertura ≥85%, CI en GitHub Actions.
- **[systemd-hooks](https://github.com/danielzunigazb/systemd-hooks)** — framework mínimo (stdlib puro) para correr scripts Python como servicios systemd user, con logging JSONL y paths XDG-compliant.
- **cognitive-core (blini)** — 7 servicios systemd orquestando automatización personal: monitoreo, captura de contexto, sugerencias. Privado.

### Cómo trabajo

| | |
|---|---|
| **Reproducibilidad** | Sin binarios sin checksum. Todo pipeline se reconstruye desde cero con un comando. |
| **Documentación** | ADRs para decisiones, READMEs funcionales. Tan rigurosa como el código. |
| **Testing** | Si no tiene tests, no está terminado. Cobertura ≥85%, CI gates obligatorios. |
| **Estándares** | XDG Base Directory, systemd para servicios. Cero hardcodeo de rutas. |

### Stack

`Python` `Kotlin` `Bash` `SQL` · `FastAPI` `Typer` `Jetpack Compose` `MCP` `Pytest` `uv` `Ruff` · `Arch Linux` `systemd` `Docker` `Git` `GitHub Actions` `SSH`

---

<div align="center">
<sub>Córdoba, Colombia · <a href="https://danzuniga.xyz">danzuniga.xyz</a></sub>
</div>
