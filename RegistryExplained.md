# Windows Registry Guide

## What is the Windows Registry?

The Windows Registry is a hierarchical database that stores low-level settings for the Windows operating system and installed applications. It contains information, settings, options, and other values for hardware and software.

## Why is the Registry important?

- It controls how Windows behaves.
- It affects system performance and stability.
- Tweaking registry keys can optimize Windows for better speed or functionality.

## Structure of the Registry

The registry consists of **keys** and **values** organized in a tree-like structure:

- **Hives:** The top-level containers (e.g., `HKEY_LOCAL_MACHINE`, `HKEY_CURRENT_USER`).
- **Keys:** Like folders, they hold subkeys or values.
- **Values:** Store the actual data (settings), which can be strings, numbers, or binary data.

## Common Registry Hives

- `HKEY_LOCAL_MACHINE (HKLM)`: Settings for the entire computer.
- `HKEY_CURRENT_USER (HKCU)`: Settings for the logged-in user.
- `HKEY_CLASSES_ROOT (HKCR)`: File associations.
- `HKEY_USERS (HKU)`: All users' profiles.
- `HKEY_CURRENT_CONFIG (HKCC)`: Hardware configuration.

## Editing the Registry Safely

- Always **backup** the registry or create a System Restore Point before making changes.
- Use tools like **regedit.exe** carefully.
- Incorrect changes can cause system instability or crashes.

## How PowerBoost Uses the Registry

PowerBoost tweaks registry keys to improve system performance by:

- Optimizing memory usage.
- Adjusting network settings.
- Enhancing system responsiveness.

## Disclaimer

These tweaks may not work on all systems and might cause unexpected behavior. Use with caution.
