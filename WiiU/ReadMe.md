## Homebrew Channel

The WiiU supports Homebrew on WiiU-Mode as well as in Wii-Mode.
Executables in elf (WiiU) and dol (Wii) are stored on the SD-Card.
The Wii apps reside in /apps whre the WiiU apps are in /WiiU/apps

## Injection

TeconMoon's WiiVC Injector allows to install Wii or even Gamecube titles directly to the home screen of the WiiU launcher.
The injector needs the executable (.dol), an icon (128x128px) and a banner (1280x720px) for each installation.
For title build process two keys are needed, the "Wii U Common Key" D7B0040... and a title key e.g. for "Rhythm Heaven Fever (USA)" 04EACEF...
The output of the injector has to be placed in /install/<TITLE>
The titles are installed with "WUP-Installer GX2" which is a homebrew application for the WiiU-Mode.

## Store Backups

With the Wii U USB Helper 0.6.1.616 store title downloads can be backuped. tbc 

## Nintendont

Nintendont enables the support of Gamecube games on the WiiU which is disabled by a feature flag by default.
While Nintendont is a Wii Homebrew app, it has to be launched from the Homebrew Channel in the vWii or can be injected as WiiVC titles to the startscreen.
Several operations like creating memorycard images can only be performed from the Wii-Mode.
Gamecube games are loaded from /Games folder.

## Coldboot Haxchi
