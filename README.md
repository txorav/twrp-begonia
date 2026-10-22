# TWRP Recovery for Redmi Note 8 Pro (`begonia`)

Automated **GitHub Actions** CI builder and complete device tree for **Team Win Recovery Project (TWRP)** on **Xiaomi Redmi Note 8 Pro** (`begonia` / `begoniain`).

## Features
- Supports both **TWRP 14** (Android 14 minimal manifest) and **TWRP 12.1** (LTS).
- **Unified Partition Support**: Mounts both legacy physical partitions and retrofitted dynamic partitions (`super`) with EROFS and EXT4.
- **Decryption**: Keymaster 4.0 beanpod crypto support.

## Build via GitHub Actions
```bash
gh workflow run "TWRP Recovery Build (begonia)"
```
Or trigger manually from the **Actions** tab on GitHub.
