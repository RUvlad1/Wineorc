<div align="center" class="tip" markdown="1" style>

![wineorc logo](https://raw.githubusercontent.com/DarDarDoor/Wineorc/main/photos/Wineorclogo.png)
![wine ver](https://img.shields.io/badge/wine-7.20-red) ![repo ver](https://img.shields.io/badge/Current%20version-2.7-success) ![lol](https://img.shields.io/badge/Pretty-cool-informational)
</div>

uhh hi
i'll try to do something with this i guess
dar is kidna gone now so  idk

# 🍷 A simple Shell script to setup ORC revivals automatically on Linux

This script is not supported in any way, shape or form by the official devs of these revivals.

## ⚡ What this does
This script will download dependencies, register URI and install the revival of choice (Currently Crapblox, Tadah, Placeholder and ItteBlox). It can also install DXVK, and uninstall the revival of choice.

## ⚠️ Requirements
The needed packages are:
- `sudo`
- The latest WINE (obv, preferably wine-staging)
- `wget`
- `curl` (for ItteBlox and Placeholder only)

The script can install WINE for you. However, only some distros are supported, so if it fails then you should install WINE and the other dependencies manually.

## 💻 How to use it

1. Download the latest release from the Releases page (or just clone this repo via git)
2. Open a terminal and cd into where the script is downloaded.
3. Run `chmod +x wineorc.sh`
4. Run `./wineorc.sh` and follow the prompts.
5. Once installed, play a game and it should work!

See `./wineorc.sh --help` for all available options.

## ⬆️ How to update the revival
You should do these steps if the revival has recently been updated:

1. Download the latest Wineorc version (get it from the Releases tab)

2. Run `./wineorc.sh uninstall`, then select your revival. Enter your password if prompted.

3. Run the script normally.

If the script has an out of date launcher, ping me on Discord and I'll update it. You can also open a pull request with the latest link, and I'll accept it.

## ❗ Troubleshooting
If the revival crashes/doesn't launch, try to:

1. Make sure all necessary optional wine dependencies are installed. You can install them on Arch Linux by running these commands:

`sudo pacman -S expac &&
sudo pacman -S $(expac '%n %o' | grep ^wine)`

If you're not on arch, see [here](https://wiki.winehq.org/Building_Wine#Satisfying_Build_Dependencies) for all the dependencies.

2. Uninstalling the revival (use `./wineorc.sh uninstall` and then select the revival) and then reinstalling it again. (this really can help)

If those don't work, DM me on Discord: DarDarDar#3429.

## Credits

[doitsujin/dxvk](https://github.com/doitsujin/dxvk), licensed under zlib

vl1 for making the Polygon guide

calones for helping me, and putting up with me being dumb

thexkey for helping me alot making the Placeholder helper

itteh, genosmrpg, jackd900, pizzaboxer, kinery and thexkey for making great revivals


<div align="center" class="tip" markdown="1" style>

![itteblox working](https://raw.githubusercontent.com/DarDarDoor/Wineorc/main/photos/ittebloxlinux.png)

ItteBlox 2016 working on Arch Linux

</div>
