# COOKING
This vault contains all my recipies

To set up the obsidian vault on you device, follow the following steps
## Windows 10 / 11
#### Requirements:
- Any recent [git](https://git-scm.com/) version
- Obsidian (Download & Install [Here](https://obsidian.md/help/install))
#### Steps

1) Clone the repo to a directory of your choosing

2) Open obsidian and go to manage vaults (This screen is the default if you have just installed obsidian)

3) Click on "Open vault as folder"

4) Select the directory where the repo is (NOTE: By this point, the git plugin should be working, if it does not, continue with the following steps, else: you're done)

5) Install the community plugin "Git" by Vinzent from the community plugins tab in settings

6) Run the command `git config credential.helper` on cmd prompt, this should return "manager", if it doesn't, try `git config set credential.helper manager`and try again

7) Open the git source control from your left taskbar

8) Pull to check if everything works

9) On the bottom left, change mode to "Reading" from "Live Preview"

## Mobile
#### Requirements

- GitSync App on Sync Mode
- Obsidian App
#### Steps

1) Open GitSync and clone the repo to your phone, make sure it is in "Download and Overwrite" mode

2) Open Obsidian and go to Open folder as vault and select the directory you chose

3) Go to Community plugins and disable the git plugin (That plugin is only for desktop and may cause problems)

4) Go back to GitSync and set up how often you want the repo to be updated