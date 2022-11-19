# A Quick Spinup WinGet Import File
Installs Firefox, Steam, some programming languages, .NET, Java, Paradox Launcher, and a few other things.

## How is this legal?
It uses the Microsoft Windows Package Installer.

## How do I use it?

Ensure you have `winget` installed. If you don't, (Like if you installed from an early version of Win10), get the [App Installer](https://apps.microsoft.com/store/detail/app-installer/9NBLGGH4NNS1?hl=en-us&gl=us) from the Microsoft Store.

1. Download the Zip file
2. Unzip the Zip file
3. Open up Powershell or Windows Terminal. 
4. `cd ~\Downloads\winget-spinup-main`
5. `winget install -i spinup-install.json -e`

If you want to just use the Gaming Edition file, just double click it to run it. (But please, for the love of your own security, read it before you run it. You never know if I'm a nasty person.)

That'll do it. Just follow the prompts as the pop up.

## What's it got?
There are two versions - "Gaming Edition" and the spinup json file.
The spinup json is how I provision a Windows Computer - 
### Runtime Environments
- .NET Framework 4.8, Runtime 6, and Runtime 7 (And 6 & 7 Desktop Runtimes)
- Java RE 8

### Games
#### Storefronts/Launchers
- Steam
- Epic Games Launcher
- GOG Galaxy
- Paradox Launcher
- EA Desktop
- Ubisoft Connect
#### Indie/Open Source Games
- Sonic Robo Blast 2
- Sonic Robo Blast 2 Kart
- OpenRA
#### Utilities
- Steam Rom Manager
- Nyrna (Suspends Apps, supposedly like a modern console does)
- Borderless Gaming (Faux Borderless for those that can't Borderless)

### Multimedia
- VCV Rack
- MPC-HC
- foobar2000
- Sonixd
- PureCodec
- The GIMP

### Development
#### IDEs
- GNU Emacs
- TeXStudio
#### Languages
- MiKTeX
- SBCL
- Erlang
- Racket
- Python 3.10
- Rustup
- Golang
#### Version Control
- Github Desktop
- Git LFS

### Internet Things
- Firefox
- Discord
- Parsec

### Office
- Obsidian
- ShareX
- Sumatra PDF
- Pandoc
- Calibre

The Gaming Edition contains just the gaming things, the .NET stuff, and Java 8

## Okay, but how do I update?
1. Open Windows Terminal
2. `winget update --all --include-unknown`

The last flag tells WinGet to get anything that doesn't have a verison number, in case you installed something outside of WinGet.


