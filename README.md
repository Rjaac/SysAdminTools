# SysAdminTools

**SysAdminTools** is a modular suite of offline system administration tools for Windows.  
Designed to audit, clean, monitor, and secure systems using open-source, agent-based logic.

## 🧩 Structure

Each agent lives in its own folder (e.g. `01_mirror`, `02_janitor-boy`) and handles a specific function.

```
SysAdminTools/
├── scripts/         → Main .ps1 logic scripts (01_mirror.ps1, etc)
├── etc/             → Configuration files (YAML, JSON)
├── logs/            → System logs (ignored by Git)
├── tmp/             → Temporary runtime data (ignored)
├── 01_mirror/       → Snapshot data
├── 02_janitor-boy/  → Cleanup profiles and reports
├── ...
```

## ⚙️ Agents Overview

- **01_mirror** – System snapshot and inventory
- **02_janitor-boy** – Cleaning and uninstall suggestions
- **03_warden** – Port/security monitor
- **04_kit-builder** – Setup environments by profile
- *(full list in progress...)*

## 📜 License

This project is licensed under the [MIT License](LICENSE).
