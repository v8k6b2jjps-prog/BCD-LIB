# 🔧 PS1 Library Collection

A collection of PowerShell scripts and tools to manage Windows system components.

---

## 📂 Modules

- **BCD LIB (PowerShell cmdlets)**  
  Manage Boot Configuration Data (BCD) entries.  

  **Supported Functions:**
  - `Get_Boot_info` — Display current boot configuration and entries.
  - `Get-VHD-Path` — Retrieve the path of a VHD/VHDX file.
  - `Is-VHD-System` — Check if the current system is running from a VHD.
  - `Add_VHDX_BOOT` — Add a boot entry for a VHDX-based system.
  - `Add_PARTITION_BOOT` — Add a boot entry for a Windows installation on a physical partition.
  - `Add_RAM_DRIVE_BOOT` — Add a boot entry for running Windows from a RAM drive.
