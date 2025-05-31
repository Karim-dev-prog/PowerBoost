# Error Handling & Recovery Guide

If you encounter problems after using PowerBoost—such as system instability, performance issues, or errors—follow the steps below to recover your system safely.

---

## 1. General Troubleshooting

- **Restart your computer**: Some changes only take effect after a reboot.
- **Revert tweaks manually**: If you know which registry or system changes caused the issue, you can undo them through the Registry Editor or PowerShell.
- **Check for backups**: If you exported your registry or created a System Restore Point before running PowerBoost (highly recommended), you can use these to restore your system.

---

## 2. Using System Restore from Windows Recovery Environment (WinRE)

If Windows does not start correctly or you experience serious issues, you can use System Restore from WinRE to return your PC to a previous state.

### How to Access WinRE

1. **If Windows Fails to Boot Automatically**:  
   WinRE should appear after several failed startup attempts.

2. **Manual Method**:  
   - Restart your computer.
   - As soon as Windows begins to load, repeatedly press `F8`, `F11`, or `Esc` (key varies by manufacturer).
   - Or, hold `Shift` while clicking Restart from the sign-in screen or Start menu.

### Steps to Use System Restore in WinRE

1. In the blue WinRE screen, select **Troubleshoot**.
2. Choose **Advanced options**.
3. Select **System Restore**.
4. Follow the prompts to select a restore point (preferably the one you created before running PowerBoost).
5. Let Windows restore your system. This may take several minutes.

---

## 3. Additional Help

- **If you backed up your registry**:  
  Double-click your `.reg` backup file to restore the previous settings, or use `regedit.exe` and the Import feature.

- **If issues persist**:  
  - Search online for the specific error message, or visit Microsoft’s support site.
  - Consider reaching out via Issues on our [GitHub repository](https://github.com/Karim-dev-prog/PowerBoost/issues).

---

## 4. Preventing Issues in the Future

- Always create a System Restore Point before making system changes.
- Backup your registry before running optimization scripts.
- Read the documentation to understand the tweaks being applied.

---

## Disclaimer

System tweaks can have unintended effects. PowerBoost is provided as-is without warranty. Always back up your system and data before using optimization tools.
