# FreeMyXe Compatibility Database

This is a community-driven compatibility database for games running on [**FreeMyXe**](https://github.com/InvoxiPlayGames/FreeMyXe)**-patched Xbox 360 consoles**. The goal is to document which games work, which have issues, and any possible fixes.

## How to Use
- **Check compatibility**: Browse the game lists ([Retail Games](/Retail.md) or [Homebrew](/Homebrew.md)) to see if a title works.
- **Contribute**: If you've tested a game, report your findings (see below).

## Game Compatibility List
Compatibility reports are categorized as follows:

| Status | Meaning |
|--------|---------|
| ✅ Yes | Fully functional with no issues. |
| ⚠️ Partial | Works, but has glitches or requires fixes. |
| ❌ No | Does not work or crashes. |

### Categories
- [Retail Games](/Retail.md)
- [Homebrew](/Homebrew.md)

## Assumptions
- All games and homebrew listed in this database are assumed to have been patched using **XePatcher/XexTool** before testing. If a title does not work, please ensure it has been properly patched before reporting compatibility issues.
- **Arcade games should work out of the box** and generally do not require patching. If an arcade game does not work, feel free to let me know via the issues tab and I can get an arcade file.

## How to Contribute
We rely on the community to expand and maintain this database (though I will be posting a lot here too with my findings!). To submit a compatibility report:

1. **Fork this repo**
2. **Edit the relevant markdown file** in the `games/` folder
3. **Use this format** when adding a new game:
   ```md
   | Game Title     | Region   | Works?     | Notes (Crashes, Fixes, Patches)      |
   |----------------|----------|------------|--------------------------------------|
   | Example Game   | NTSC-U   | ⚠️ Partial | Crashes after loading world 2       |
   | Another Game   | PAL      | ✅ Works   | No issues found                     |
   | Yet Another    | NTSC-J   | ❌ Broken  | Doesn't launch at all               |
   ```
   So that it'll look like this:

   | Game Title     | Region   | Works?     | Notes (Crashes, Fixes, Patches)      |
   |----------------|----------|------------|--------------------------------------|
   | Example Game   | NTSC-U   | ⚠️ Partial | Crashes after loading world 2       |
   | Another Game   | PAL      | ✅ Works   | No issues found                     |
   | Yet Another    | NTSC-J   | ❌ Broken  | Doesn't launch at all               |


4. **Submit a pull request (PR)** with your changes.

Alternatively, you can report compatibility using **GitHub Issues**:
- Open an **Issue** and follow the provided template.

Note: Make sure you're using the latest version of both [BadUpdate](https://github.com/grimdoomer/Xbox360BadUpdate/releases/latest) and [FreeMyXe](https://github.com/InvoxiPlayGames/FreeMyXe/releases/latest).

## License
This project is licensed under **CC0 1.0 Universal (Public Domain Dedication)**. This means:
- No restrictions on use, modification, or redistribution.
- No attribution required.

## Credits
This project is maintained by the Xbox 360 community! Special thanks to:
- [**InvoxiPlayGames**](https://github.com/InvoxiPlayGames) for creating [**FreeMyXe**](https://github.com/InvoxiPlayGames/FreeMyXe).
- [**grimdoomer**](https://github.com/grimdoomer) for developing [**Xbox360BadUpdate**](https://github.com/grimdoomer/Xbox360BadUpdate).

