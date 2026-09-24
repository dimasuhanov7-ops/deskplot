# Installer checksums · Контрольные суммы установщика

SHA-256 for every published `Deskplot-Setup-<version>.exe`.
SHA-256 для каждого опубликованного `Deskplot-Setup-<версия>.exe`.

| Version · Версия | File · Файл | SHA-256 |
|---|---|---|
| [2.0.2](https://github.com/dimasuhanov7-ops/deskplot/releases/tag/v2.0.2) | Deskplot-Setup-2.0.2.exe | `13bb50acc71420e7a1073ed70ea9abf9b65808dc4a1b12b1e6ee7a90d9a006c8` |
| [2.0.1](https://github.com/dimasuhanov7-ops/deskplot/releases/tag/v2.0.1) | Deskplot-Setup-2.0.1.exe | `4e69c57451dccd5c6e334dabb1c106bcbcf813f079b34b3a87d28ec045c2cdef` |
| [2.0.0](https://github.com/dimasuhanov7-ops/deskplot/releases/tag/v2.0.0) | Deskplot-Setup-2.0.0.exe | `98a39c6d3f2267ded61d479323eb24769d1ad355e8c08e6c02eba4a7dd015343` |

**How to check · Как проверить**

```powershell
Get-FileHash Deskplot-Setup-<version>.exe -Algorithm SHA256
```

Compare the output to the value above for that version — it should match exactly.
Сравните результат со значением из таблицы для этой версии — оно должно совпадать полностью.
