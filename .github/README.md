# GoldHEN Cheat Database
_Cheat Menu allows you bring up a Menu while in-game for you to select cheats._

# Initial Cheats Credits
_Thanks to PS4Trainer For Initial Trainers Database and all Cheats Creators._

## Features
- `.json` support
- `.shn` support
- `.mc4` support
### Storage:
- Use `FTP` to upload cheat files to:
  - `/user/data/SploitHEN/cheats/json/`
  - `/user/data/SploitHEN/cheats/shn/`
  - `/user/data/SploitHEN/cheats/mc4/`
- Naming conversion for cheats that attach to eboot.bin process: `{titleid}_{version}.{format}`
  - e.g. `CUSA001234_01.01.json`
  - e.g. `CUSA001234_01.01.shn`
  - e.g. `CUSA001234_01.01.mc4`
- Naming conversion for cheats that attach to a non eboot.bin process (usually on collection games): `{titleid}_{version}_{process}.{format}`
  - e.g. `CUSA001234_01.01_example.elf.json`
  - e.g. `CUSA001234_01.01_example.elf.shn`
  - e.g. `CUSA001234_01.01_example.elf.mc4`
 - **Note:** Only one file format per `titleid` and `version` is currently supported.

### To Do:
- Add more cheat formats.
