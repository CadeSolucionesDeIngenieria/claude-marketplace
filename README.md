# Catálogo de plugins de Claude Code de CADE

Este repositorio solo contiene el **catálogo** (`.claude-plugin/marketplace.json`) con la huella (sha256) de cada versión del plugin `cadelab`. El código del plugin lo sirve CADE Lab (`https://lab.cade.local/claude/plugins/…`) dentro de la red de CADE; Claude Code descarga el `.zip` y comprueba que su sha256 coincide con el de aquí. Si alguien cambiara el `.zip` en el servidor sin pasar por una PR aprobada en este repositorio, la instalación fallaría.

- Cómo se publica una versión y cómo se vuelve atrás: `docs/operacion/PLUGIN-CLAUDE.md` del repositorio `py_CadeLab`.
- No contiene código ni secretos. Toda modificación entra por PR con una aprobación.
