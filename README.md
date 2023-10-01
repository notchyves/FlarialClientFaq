# [![flarial_small](https://github.com/notchyves/FlarialClientFaq/assets/82107846/8248ee47-3126-4420-8cd5-a3a38ae49b41)](https://discord.gg/flarial-community-1049946152092586054) Flarial Client FAQ

Flarial Client is the newest and greatest legit injector modification for Minecraft Bedrock Edition. If you have any issues setting up your Flarial experience, this is what this FAQ is for! If you find any issues, or would just like to add something here; feel free to fork this repository, edit it, and the make a pull request and we will decide on a case-by-case basis whether to merge or not. **If you have any other questions not covered here go to our Discord Server linked [here](https://discord.gg/flarial-community-1049946152092586054).**

## 📁 How do I download Flarial Client?

To download Flarial Client go to this the [#download](https://discord.com/channels/1049946152092586054/1050115297253793882) channel. After this you have a few choices:

### Launcher Installer (Recommended)
If you use this, you will get the Flarial Minimal and the Flarial Launcher. Here are the differences:
#### Flarial Launcher
- A nice beautiful launcher to help manage Flarial and the client in general.
- Discord integrations.
- Extra Minecraft Managment.

#### Flarial Minimal
- Extremely lightweight.
- Easy to use.
- No login needed.

### Standalone DLL
If you use this, you will need an injector. You can choose to use many injectors but here are some you can use:

- **[Chyves Injector](https://github.com/notchyves/ChyvesInjector/releases/download/publish/Chyjector.zip)** (extremely small, discord integration)
- **[MCBE DLL Injector](https://github.com/ambiennt/MCBE-DLL-Injector)** (forked debloated fate injector)

You will need to setup the injector with the Flarial DLL, so it knows what to inject.

## ❓ Troubleshooting

### VCRUNTIME140_1.dll not found:
- Go to https://support.microsoft.com/en-us/help/2977003
- Scroll down and download the x64: vc_redist.x64.exe
- Run the exe and install it
- It should work now!

### How do I remove the red arrow from Minecraft?
This is not a Flarial bug though there is a fix. Download this pack [here](http://www.mediafire.com/file/kqyjo9s9ld39nkn/No+Red+Arrow+by+Mhavin.mcpack/file) and apply it. This bug happens as the pack creator/porter did not update your hud_screen.json. **This is being [actively investigated](https://bugs.mojang.com/browse/MCPE-105882) by Mojang.**

## 🐞 Known Bugs

### Launcher
| Issue                           | Solution                                     |
| ------------------------------- | -------------------------------------------- |
| ERROR_NO_PATH                   | Disable "Custom DLL" in settings                           |
| "Download failed" popup         | Connection issues with flarial.net, refer to [Cannot Access Website](https://discord.com/channels/1049946152092586054/1136329055596183783)  | 

### Client
| Issue                           | Solution                                     |
| ------------------------------- | -------------------------------------------- |
| Failed to find address of _____ | Update/Downgrade to supported version.       |
