# Version support

## Versions

#### How often does Fabulously Forgified receive updates?

The goal is to push out a new version once per week or two weeks. This is not a guarantee and can change depending on the amount of mod updates, Mojang's schedules, real-life duties and others.

#### How do the modpack version numbers work?

##### Full Versioning:

- **X**.Y.Z. (up: B.C) stands for major versions which directly map to Minecraft's 1.**Y**.Z (1.16 was 1, 1.17 was 2 etc); this directly maps to upstream's major version
- X.**Y**.Z. (up: B.C) stands for minor versions which directly map to Minecraft's 1.Y.**Z** (1.21.1 was 1, 1.21.2 was 2)
- X.Y.**Z**. (up: B.C) stands for patch versions which refer to bigger changes like mod additions/removals
- X.Y.Z.**~** (up: B.C) stands for patch versions - no breaking changes, no mod additions/removals; this is hidden when 0
- X.Y.Z. (up: **B.C**) stands for the upstream version - the major version (A) is excluded as it matches **X**
_If Fabulously Optimized and upstream are in beta 1:_
- X.Y.Z.-**beta.1** (up: B.C-**beta.1**)
_If Fabulously Optimized is in beta 1, and upstream is stable:_
- X.Y.Z.-**beta.1** (up: B.C)

##### Shortened Versioning:

- **X**.Y.Z.+B.C stands for major versions which directly map to Minecraft's 1.**Y**.Z (1.16 was 1, 1.17 was 2 etc) - major version maps to upstream's major verison
- X.**Y**.Z.+B.C stands for minor versions which directly map to Minecraft's 1.Y.**Z** (1.21.1 was 1, 1.21.2 was 2)
- X.Y.**Z**.+B.C stands for patch versions which refers to bigger changes like added mods
- X.Y.Z.**~**.+B.C stands for patch versions - no breaking changes, no mod additions/removals; this is hidden when 0
- X.Y.Z.+**B.C** stands for the upstream version - the major version (A) is excluded as it matches **X**
_If Fabulously Optimized and upstream are in beta 1:_
- X.Y.Z-**b1**+B.C-**b1**
_If Fabulously Optimized is in beta 1, and upstream is stable:_
- X.Y.Z-**b1**+B.C

Here is how you should think about the version types in relation to Minecraft's:

| Minecraft term            | Modpack equivalent term |
| ----------------- | ------------------------- |
| snapshot                           | alpha                                              |
| pre-release                        | beta                                               |
| release candidate                  | -                                                  |
| release                            | stable                                             |

#### What versions do you support?

The latest stable version and if available, also latest beta and/or alpha versions. Older versions are listed for your convenience, but may not receive any more updates.

#### Why won't the installer show versions older than 5.10.3?

These versions are old and therefore no longer recommended for most users. Please [use manual install](install-instructions.md#minecraft-launcher-vanilla) if you'd like to use them.

#### Will you support Minecraft snapshots?

No, they are not supported on CurseForge App and are released too fast for the author and the modders to keep up with.

#### What does ⚠️ mean in a version's title?

Versions with a warning triangle ⚠️ contain vulnerabilities or bugs that are known on that vanilla Minecraft version. These are available for archival purposes only and may cause problems in multiplayer or your worlds. Please prefer versions that do not have warnings or see the version's notes before installing.

#### What if I want to play on an older Minecraft version?

[CurseForge listing](https://www.curseforge.com/minecraft/modpacks/fabulously-optimized/files?showAlphaFiles=show) contains all latest versions down to Minecraft 1.16.1.

If you need to play in a server that uses a version not supported by the modpack, your best bet is installing the latest version of the modpack and adding [ViaFabric](https://www.curseforge.com/minecraft/mc-mods/viafabric) to your modpack profile [(instructions are here)](adding-more-mods.md). It is recommended to keep the mod enabled only while playing the server where you need it.

#### Will you backport newer modpack changes to older versions?

Occasionally yes. Cases may include:

* a major breakage
* after introducing a new major stable release
* major updates to most important mods (e.g. Sodium, Lithium, Phosphor)

This is done to help you while you _transition_ to the new version, old Minecraft versions are still unsupported and will not receive full parity.

## Other platforms

#### Will you make a [Forge](https://files.minecraftforge.net) or [NeoForge](https://neoforged.net/) modpack?

No. Forge and NeoForge receive mod updates slower and do not have all the same performance and graphics-enhancing mods as Fabric.

#### Can I use (Neo)Forge mods in this modpack?

No, but [there are many equivalents anyway](https://gist.github.com/TrueCP6/4853f15015b210fd3b1e210e9e485f83). [Ask us on Discord](https://download.fo/discord) if you need an alternative for a specific mod!

#### Will you make a [Quilt](https://quiltmc.org) modpack?

Probably not, that depends on modders' general stances on that mod loader compared to Fabric. See [issue #257](https://github.com/Fabulously-Optimized/fabulously-optimized/issues/257).

#### Can I use Quilt mods in this modpack?

"Probably not. Quilt mods will eventually have their own metadata format which will likely not be compatible with Fabric." [Source](https://quiltmc.org/faq/)
