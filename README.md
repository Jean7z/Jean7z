<div align="center">

# Jean7z

### C++ / Android developer · GTA San Andreas modding

<br>

![C++](https://img.shields.io/badge/-C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Android](https://img.shields.io/badge/-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![ARM](https://img.shields.io/badge/-ARM-0091BD?style=for-the-badge&logo=arm&logoColor=white)
![Reverse Engineering](https://img.shields.io/badge/-Reverse%20Engineering-000000?style=for-the-badge&logo=terminal&logoColor=white)
![NDK](https://img.shields.io/badge/-NDK-3DDC84?style=for-the-badge&logo=android&logoColor=white)

</div>

---

## About

I build C++ plugins for **GTA San Andreas on Android** with the
[Android Mod Loader](https://github.com/AndroidModLoader) SDK. My workflow
starts at the binary: symbols verified against the released `libGTASA.so`
before a single byte is patched, and everything ships as a single-tree
plugin targeting **arm64-v8a** and **armeabi-v7a** alike.

- **Gameplay mods** — clothing/wardrobe unlocks, gym reworks, weapons
  and targeting behavior.
- **Reverse engineering** — SCM script decoding, symbol verification,
  relocation-table-level hook placement.
- **SDK work** — extending `aml-psdk` to expose more of the game engine's
  classes to the whole modding community.

## Projects

### GTA San Andreas mods

| Mod | What it does |
|---|---|
| [gta-sa-freeclothes](https://github.com/Jean7z/gta-sa-freeclothes) | Unlock all clothing — every outfit owned, free prices, all 7 shops in any safehouse wardrobe |
| [gta-sa-headshot-nospread](https://github.com/Jean7z/gta-sa-headshot-nospread) | Headshot accuracy optimization + weapon spread removal |
| [gta-sa-unlimited-gym](https://github.com/Jean7z/gta-sa-unlimited-gym) | Train without limits |

### Tools

- [img-to-svg](https://github.com/Jean7z/img-to-svg)
- [aml-psdk](https://github.com/Jean7z/aml-psdk) — plugin SDK for easier mod creation ([upstream](https://github.com/AndroidModLoader/aml-psdk))

---

<div align="center">
  <sub>GTA San Andreas is a trademark of Rockstar Games. Not affiliated.</sub>
</div>