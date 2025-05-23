# Disabling mods

Don't like a feature or having a mod conflict? Easiest way to resolve it is to disable the mod. For resource pack-related issues, [see this page](resource-pack-issues.md).

Notes:

* You can also delete the mod(s), but that will make it harder to [use them later](adding-more-mods.md), unless you remember the mod's name exactly.
* Don't disable anything that says "API", other mods need it to work.

### Mod Menu

1. With the game open, click `Mods`
2. Scroll down to the specific mod you want to disable, note the third row with the ⚒️ (tools) or ✏️ (pencil) icon 
   * If the icon is **blue** and the text mentions **"Toggle mod"**, click the config button ![config](https://i.ibb.co/j35cBtn/image.png) and find the setting that disables the mod
   * If the icon is **blue and the text says something else**, click the config button ![config](https://i.ibb.co/j35cBtn/image.png) and see if you can disable the specific feature you need
   * If the icon is **gray** and there is no config button, or you know you added the mod yourself, follow your launcher-specific instructions below
   * If you **don't see any icons** and you didn't add the mod yourself, you don't have the Mod Menu Helper resource pack enabled for some reason.
     1. For the latter, click `Done` → `Options...` → `Resource Packs...` → `⏵` on "Mod Menu Helper.zip" → `Done` → go to point 1 of this tutorial

### CurseForge App

1. Open CurseForge App
2. Go to `My Modpacks`, click on Fabulously Forgified
3. Click on the three dots, select `Profile Options`
4. Check "Allow content management for this profile", click `Done`
5. Find the mod you need, toggle the knob.

### Modrinth App

1. Open Modrinth App
2. Open `|||\` "Library"
3. Click on Fabulously Forgified
4. Find the mod you need, toggle the knob.

### Prism Launcher

1. Open Prism Launcher
2. Click on Fabulously Forgified, then `Edit`
3. Go to `Mods`
4. Find the mod you need, uncheck the checkbox.

### MultiMC

1. Open MultiMC
2. Click on Fabulously Forgified, then `Edit Instance`
3. Go to `Loader mods`
4. Find the mod you need, uncheck the checkbox.

### MultiMC (auto-update)

There is currently no _easy_ way because the tool downloads missing mods back on launch. There are script workarounds though, [tutorials written here](multimc-auto-update.md#can-i-ignore-some-of-the-mods).

Consider [switching to Prism Launcher instead,](install-instructions.md#prism-launcher) which also has a seamless modpack updater.

### Minecraft Launcher (vanilla)

1. Open Minecraft Launcher, click on `Installations`
2. Hover on the Fabric installation, click 📂
3. Click `mods`
4. Rename the specific mod from "modname.jar" to "modname.jar.disabled"
   * Don't see ".jar" at the end of the name? [See this page for help.](https://www.thewindowsclub.com/show-file-extensions-in-windows)
   * Rename ".jar.disabled" back to ".jar" to use the mod again.

### GDLauncher

No longer supported. [Please migrate to Prism Launcher.](install-instructions.md#gdlauncher)
