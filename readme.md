# A Quick Spinup WinGet Import File
Installs Firefox, Steam, some programming languages, .NET, Java, Paradox Launcher, and a few other things.

## How is this legal?
It uses the Microsoft Windows Package Installer.

## How do I use it?

Ensure you have `winget` installed. If you don't, (Like if you installed from an early version of Win10), get the [App Installer](https://apps.microsoft.com/store/detail/app-installer/9NBLGGH4NNS1?hl=en-us&gl=us) from the Microsoft Store.

Open up Powershell or Windows Terminal. 

`winget install -i spinup-install.json -e`

That'll do it. Just follow the prompts as the pop up.