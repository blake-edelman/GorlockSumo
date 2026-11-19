# GorlockSumo

Sumobot firmware: ESP32 (Adafruit Feather ESP32), ESP-IDF framework, built with PlatformIO. Language is C.

## Commands
- Build: `pio run`
- Host tests (once a `native` env exists in platformio.ini): `pio test -e native`
- Never flash, open the serial monitor, or run the motors. The user does that.

## Workflow
Run `claude --agent orchestrator` for multi-step features (plan -> build -> review). Agents live in `.claude/agents/`. Specs go in `specs/` (HTML, see `.claude/skills/html-tech-doc`).
