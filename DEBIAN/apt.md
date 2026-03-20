# Advanced Package Tool
## Ini berisi syntax yang tersedia dalam `apt`
| Command | Function |
|---------|----------|
| sudo apt update | Update daftar package dari repo |
| sudo apt upgrade -y | Upgrade package new version without deleting another package |
| sudo apt install `package` | Install `package` |
| sudo apt autoremove | Delete dependency yang tidak dibutuhkan system |
| sudo apt purge `package` | Delete `package` + config | 
| sudo apt autoclean | Delete cache |
