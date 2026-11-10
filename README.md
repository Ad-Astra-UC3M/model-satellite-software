# Model Satellite (SiGMA) — Software

Firmware and ground software for the Ad Astra UC3M Model Satellite (SiGMA) project. Folders mirror the hardware repo (`model-satellite-hardware`): one folder per board.

| Folder | Contents |
|---|---|
| `flight-computer/` | STM32CubeIDE project for the flight computer firmware |
| `ground-station/` | Ground station software |

## Rules
- Build outputs and IDE workspace files are excluded via `.gitignore`. Keep the `.ioc`, `.project` and `.cproject` files: they define the project.
- Changes go into `main` through a pull request.
- Workflow guide: see the Ad Astra version control document.
