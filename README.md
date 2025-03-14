This repo is looking for **collaborators**!
These are people that can approve/decline issues/pull requests and directly edit the md files without the need for a pull request. Feel free to apply via the issues tab :)

# FreeMyXe Compatibility Database

This is a community-driven compatibility database for games running on [**FreeMyXe**](https://github.com/InvoxiPlayGames/FreeMyXe)**-patched Xbox 360 consoles**. The goal is to document which games work, which have issues, and any possible fixes.

### How to Use:
1. **Check Compatibility**:  
   Browse the [Retail Games](/Retail.md) or [Homebrew](/Homebrew.md) lists to see if a title works with FreeMyXe.

2. [**Contribute**](#how-to-contribute):  
   If you've tested a game, contribute your findings by creating a pull request or using the Issues tab to report compatibility.

3. **Additional Information**:  
   Visit the [**Wiki**](https://github.com/XDanfr/FMX-Compatibility/wiki) for more detailed guides on testing and patching methods.
  
> [!NOTE]
> This repo is made for **legally dumped games** and homebrew. This does **not** serve for piracy.
> While pirated games *will usually* run the same, this repo is made for people to see which legally dumped games and homebrew will run and therefore does not support or endorse piracy in any way.

## Game Compatibility List
Compatibility reports are categorised as follows:

| Status | Meaning |
|--------|---------|
| ✅ Works | Fully functional with no issues. |
| ⚠️ Partially | Works, but has glitches or requires fixes. |
| ❌ Borked | Does not work or crashes. |
| 👤 Offline | Only use an offline account (not Xbox Live) |

### Categories
- [Retail Games](/Retail.md)
- [Homebrew](/Homebrew.md)

## Assumptions
- All games and homebrew listed in this database are assumed to have been patched using one of the methods in the [**Wiki**](https://github.com/XDanfr/FMX-Compatibility/wiki) before testing. If a title does not work, please ensure it has been properly patched before reporting compatibility issues.
- **Arcade games should work out of the box** and generally run perfectly fine in GoD format. If an arcade game does not work, feel free to let me know via the issues tab just like any other game.

> [!NOTE]
> If a game doesn't work via XexTool, it's very likely that it'll work via [this method](https://www.youtube.com/watch?v=tUajcJjVaPY). This is the recommended method.

## How to Contribute
We rely on the community to expand and maintain this database (though I will be posting a lot here too with my findings!). To submit a compatibility report:

1. **Fork this repo**
2. **Edit the relevant markdown file**
3. **Use this format** when adding a new game:
   ```md
   | Game/Homebrew Title        | Works? | Notes (Crashes, Fixes, Patches)      |
   |----------------------------|:------:|--------------------------------------|
   | Example Game               |   ⚠️   | Crashes after loading world 2        |
   | Another Game               |  ✅ 👤 | No issues found, use offline account |
   | Yet Another                |   ❌   | Doesn't launch at all                |
   ```
   So that it'll look like this:

   | Game/Homebrew Title        | Works? | Notes (Crashes, Fixes, Patches)      |
   |----------------------------|:------:|--------------------------------------|
   | Example Game               |   ⚠️   | Crashes after loading world 2        |
   | Another Game               |  ✅ 👤 | No issues found, use offline account |
   | Yet Another                |   ❌   | Doesn't launch at all                |


4. **Submit a pull request** with your changes.

Alternatively, you can report compatibility using **GitHub Issues**:
- Open an [**Issue**](https://github.com/Brubhubedits/FMX-Compatibility/issues/new?template=compatibility_report.yml) and follow the provided template.

> [!NOTE]
> Make sure you're using the latest version of both [BadUpdate](https://github.com/grimdoomer/Xbox360BadUpdate/releases/latest) and [FreeMyXe](https://github.com/InvoxiPlayGames/FreeMyXe/releases/latest).

## Roadmap
- [ ] Revise the issue reporting experience to be more helpful for owners and contributors.

## Credits
This project is maintained by the Xbox 360 community! Special thanks to:
- [**InvoxiPlayGames**](https://github.com/InvoxiPlayGames) for creating [**FreeMyXe**](https://github.com/InvoxiPlayGames/FreeMyXe) and discovering the Rock Band Blitz save file exploit.
- [**grimdoomer**](https://github.com/grimdoomer) for developing [**Xbox360BadUpdate**](https://github.com/grimdoomer/Xbox360BadUpdate).
- evangeloush ([u/3v4ng310u5](https://reddit.com/u/3v4ng310u5)) for helping out with a couple of questions and making an awesome [tutorial](https://www.reddit.com/r/360hacks/comments/1j7kaz8/running_actual_games_on_the_badupdate_exploit/)!
- [CabooseSayzWTF](https://github.com/CabooseSayzWTF) for discovering the [manual patching method](https://github.com/XDanfr/FMX-Compatibility/wiki/Recommended-method:-How-to-patch-Title-Updates) - many games would not work or have TUs working without your work.
