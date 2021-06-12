# Goal

Find an alternative for ASIO4ALL to use multiple soundcards on Windows with FruityLoops

## Tech Stack
- JACK Audio at https://jackaudio.org

## Installation
- Download JACK Audio at https://jackaudio.org/downloads ( Windows 64 Bit installer )
- Open Installer ( `jack2-win64-v1.9.18.exe` )
- Activate `JACK-Router ASIO Driver`
- Install Software

## Start JACK Server
- Open `C:\Program Files\JACK2\qjackctl\qjackctl.exe`
- Click `Start` Button

## Use JACK Router ASIO Driver in Ableton
- Open Ableton
- Open Preferences
- Open `Audio` Tab
- Set `Driver Type` to `ASIO`
- Set `Audio Device` to `Jack Router`

## Change Buffer Size
- Open JACK QT GUI Interface ( `C:\Program Files\JACK2\qjackctl\qjackctl.exe` )
- Click `Setup`
- On Page `Settings / Parameters` set `Frames/Period` to `128`
- Click `OK`
- Open Ableton
- Open Preferences
- Open `Audio` Tab
- Set `Audio Device` to `No Device`
- Set `Audio Device` to `Jack Router`