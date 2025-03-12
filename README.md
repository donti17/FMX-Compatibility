# FreeMyXe Compatibility Database

This is a community-driven compatibility database for games running on [**FreeMyXe**](https://github.com/InvoxiPlayGames/FreeMyXe)**-patched Xbox 360 consoles**. The goal is to document which games work, which have issues, and any possible fixes.

## How to Use
- **Check compatibility**: Browse the game lists ([Retail Games](/Retail.md) or [Homebrew](/Homebrew.md)) to see if a title works.
- **Contribute**: If you've tested a game, report your findings (see below).
  
> [!NOTE]
> This repo is made for **legally dumped games** and homebrew. This does **not** serve for piracy.
> While pirated games *will usually* run the same, this repo is made for people to see which legally dumped games and homebrew will run and therefore does not support or endorse piracy in any way.

## Game Compatibility List
Compatibility reports are categorized as follows:

| Status | Meaning |
|--------|---------|
| ✅ Works | Fully functional with no issues. |
| ⚠️ Partially | Works, but has glitches or requires fixes. |
| ❌ Borked | Does not work or crashes. |

### Categories
- [Retail Games](/Retail.md)
- [Homebrew](/Homebrew.md)

## Assumptions
- All games and homebrew listed in this database are assumed to have been patched using **XePatcher/XexTool** (Tools.zip found from [BadUpdate](https://github.com/grimdoomer/Xbox360BadUpdate/releases/download/latest/Tools.zip)) before testing. If a title does not work, please ensure it has been properly patched before reporting compatibility issues.
- **Arcade games should work out of the box** and generally run perfectly fine as a GoD or patched XEX. If an arcade game does not work, feel free to let me know via the issues tab and I can get an arcade file.

## How to Contribute
We rely on the community to expand and maintain this database (though I will be posting a lot here too with my findings!). To submit a compatibility report:

1. **Fork this repo**
2. **Edit the relevant markdown file**
3. **Use this format** when adding a new game:
   ```md
   | Game Title     | Region   | Works?     | Notes (Crashes, Fixes, Patches)      |
   |----------------|----------|------------|--------------------------------------|
   | Example Game   | NTSC-U   | ⚠️ Partially | Crashes after loading world 2       |
   | Another Game   | PAL      | ✅ Works   | No issues found                     |
   | Yet Another    | NTSC-J   | ❌ Borked  | Doesn't launch at all               |
   ```
   So that it'll look like this:

   | Game Title     | Region   | Works?     | Notes (Crashes, Fixes, Patches)      |
   |----------------|----------|------------|--------------------------------------|
   | Example Game   | NTSC-U   | ⚠️ Partially | Crashes after loading world 2       |
   | Another Game   | PAL      | ✅ Works   | No issues found                     |
   | Yet Another    | NTSC-J   | ❌ Borked  | Doesn't launch at all               |


4. **Submit a pull request** with your changes.

Alternatively, you can report compatibility using **GitHub Issues**:
- Open an [**Issue**](https://github.com/Brubhubedits/FMX-Compatibility/issues/new?template=compatibility_report.yml) and follow the provided template.

> [!NOTE]
> Make sure you're using the latest version of both [BadUpdate](https://github.com/grimdoomer/Xbox360BadUpdate/releases/latest) and [FreeMyXe](https://github.com/InvoxiPlayGames/FreeMyXe/releases/latest).

## Credits
This project is maintained by the Xbox 360 community! Special thanks to:
- [**InvoxiPlayGames**](https://github.com/InvoxiPlayGames) for creating [**FreeMyXe**](https://github.com/InvoxiPlayGames/FreeMyXe) and discovering the Rock Band Blitz save file exploit.
- [**grimdoomer**](https://github.com/grimdoomer) for developing [**Xbox360BadUpdate**](https://github.com/grimdoomer/Xbox360BadUpdate).

