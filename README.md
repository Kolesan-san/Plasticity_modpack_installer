# Plasticity modpack Installer

📖 [Read this documentation in Russian](https://github.com/Kolesan-san/Plasticity_modpack_installer/blob/main/README_RU.md)

---

## 🟢 Base Mode

Recommended for most users.

- **Update & Install**: Automatically checks for updates, downloads, and installs the latest version in one click.
- **Auto-detect path**: Automatically finds the Plasticity installation folder.
- **Config**: Select configuration variant (`Don't install`, `Theme`, `Theme and shortcuts`).
- **Uninstall**: Completely removes the mod and restores original files (including configs).

---

## ⚙️ Advanced Mode

For full control and manual installation.

- **Manual Update & Install**: Install from a selected local archive (cleans up old files first).
- **Mod URL / Download**: Download archive via direct link.
- **Browse Archive**: Manually select a ZIP or RAR archive.

---

## ⚠️ Administrator Rights Notice

In some cases, the installer may require **elevated administrator rights** if Plasticity is installed inside the default **`Program Files`** directory.

- **Why this happens:** Windows protects the `Program Files` folder with stricter permissions to prevent unauthorized changes. Any installer that needs to update or replace files there must request elevated rights.
- **Is it safe?** Yes — the installer only modifies Plasticity’s mod files and restores originals when uninstalling. It does not perform any hidden or unsafe operations.
- **Why EXE instead of MSI?** MSI packages are more limited in flexibility: they don’t allow the same auto‑detect logic, custom configuration options, or seamless update/uninstall features without complex workarounds. The EXE installer was chosen to preserve full functionality and user experience.

---

## 🔒 VirusTotal Scan

- **SHA-256**: `4350BF888D4F3FF342A5E3B192CAC1EE366AB74F117542FAF0EB8023DFD52273`  
- **Detection ratio**: `0/72`  
- **Scan date**: November 28, 2025  
- [View full report on VirusTotal](https://www.virustotal.com/gui/file/4350bf888d4f3ff342a5e3b192cac1ee366ab74f117542faf0eb8023dfd52273/detection)

---

## 🙏 Credits

Special thanks to [Vadim Danilkov](https://t.me/Dead_wall) for testing, advice, and developing the PLS3DCH mod itself.
