# Valkyrie

A free dashboard for RGH and JTAG Xbox 360 consoles, made by SafeLight.Dev. Open beta, and it updates itself.

## Get it

Two ways in. Both check every file against [a signed list](https://downloads.safelight.dev/valkyrie/fleet/stable.json) and save the console's start-up settings first, so an install can be undone. Start the console in Valkyrie, or keep your own dashboard and hold Start at power-on to open Valkyrie.

### From a USB stick: Valkyrie Setup

No computer app needed. You need an RGH or JTAG Xbox 360 with DashLaunch and a hard drive, and a USB stick of 1 GB or more.

1. Download [Valkyrie Setup](https://downloads.safelight.dev/valkyrie/setup/ValkyrieSetup-offline.zip) (240 MB). Valkyrie is inside, so the console needs no internet.
2. Format the USB stick as FAT32.
3. Unzip the download and copy everything in it to the top of the stick: launch.ini, README.txt and the ValkyrieSetup folder.
4. With the console off, plug the stick in and turn the console on. Setup starts by itself.
5. Press A to install. When it says Valkyrie is installed, take the stick out and press A again.

- If the power goes during the install, put the stick back in and turn the console on. Setup carries on where it stopped.
- To remove Valkyrie, start Setup again and choose Remove.
- Console online? The [small download](https://downloads.safelight.dev/valkyrie/setup/ValkyrieSetup-online.zip) (210 KB) fetches Valkyrie from safelight.dev instead.
- README.txt in the zip has the full steps.

### With Valhalla

- You need a Mac (Apple silicon, macOS 14 or later) or a 64-bit Windows 10 or 11 PC, and the console on your home network with its cable plugged in.
- Install it with [Valhalla](https://github.com/SafeLightDev/valhalla/releases/latest): open Valkyrie, choose Install and pick your console.
- No xbdm on your console? Valhalla makes a starter USB stick.

## What it does

- Games: your library as tiles, with cover art, banners and screenshots downloaded for you.
- Themes: Series X (the default), OG Xbox, Blades, NXE and Metro, plus SafeLight.Dev's own Bifrost, Darkroom and Den.
- Trainers: SafeLight.Dev's trainers, run from Valhalla while you play.
- Title updates: the newest update for your copy downloads when a game starts. Settings, then Network turns it off.
- DLC: a game's packs, with the installed ones marked.
- Achievements: each game's full list, with your profile's unlocks marked.
- Saves: your saves by profile and game, read only.
- Apotheosis: turns a game disc into Games on Demand on the hard drive.

## Updates

- Valkyrie checks for a new build about once a day and shows a toast when one is ready.
- Every update is signed, and a new build runs on trial: if it fails to start, the console goes back to the build before it.
- Hold B as the console turns on to start the backup copy yourself, or LB for the safe copy.

## Help

- Answers to common questions, setup steps and fixes: [safelight.dev/x360help](https://safelight.dev/x360help#valkyrie).
- [Report a bug](../../issues/new/choose) or talk to us on [Discord](https://discord.gg/7SH9zg6DuX).
- Every build's notes are on the [Releases](../../releases) page.
- Valkyrie works with your own consoles and your own games. It does not modify a console for you and comes with no games.

## Thanks

- FlipBit, contributor to Valhalla and Valkyrie. We could not have done it without him.
