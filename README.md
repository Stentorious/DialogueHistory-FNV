# Dialogue History
<p align="left">
    <img height="350px" src="https://staticdelivery.nexusmods.com/mods/130/images/93405/93405-1755481429-1918344638.png">
</p>

## Overview
- View, search, and listen to your previous conversations via a new interface accessible through the Pause Menu.
- Additionally view the transcript of your current conversation in the Dialogue Menu.
- Full controller support included.

### Conversation Transcript
Accessed with H or Left Stick while in the Dialogue Menu.
- Replay: Select an NPC dialogue line to play its audio..

### Dialogue History
- Accessed with H or Left Stick while in the Pause Menu.
- Navigate menu with the Mouse or D-Pad.
- View: Select a date/location in the left window to expand its conversations list.
- Open: Select a conversation from the list to view it on the right.
- Replay: Select an NPC dialogue line to play its audio.
- Find: Use the search bar to filter by NPC name.
- Sort: Use the button next to the search bar to switch sorting mode.

### How It Works
- Logs all conversations that occur in the Dialogue Menu.
- Conversations are stored in save specific JSON files found in the Data\DialogueHistory directory.
- Oldest conversation entries are deleted automatically on save when a configurable limit is reached.
- These files can be deleted at any time, no data is baked into the save.

### Special Thanks
- Wadelz for the SetOnNPCResponse event.
- WallSoGB for the helping me add the SoundFromPath functions.
- Audley and BillieBobWell for helping me test.

## Configuration
- Configurable via [MCM Extender](https://www.nexusmods.com/newvegas/mods/93642)

### General
- Toggle saving conversations to JSON entirely.
- Set maximum number of conversation entries saved to JSON.
- Prevent conversations with non-persistent NPCs being save to JSON.
- Prevent consecutive duplicate topics from being added to the conversation history.
- Remove skill tags from saved dialogue lines.

### Interface
- Set Player and NPC name color schemes.

## Requirements
- [xNVSE](https://www.nexusmods.com/newvegas/mods/67883)
- [JIP LN NVSE](https://www.nexusmods.com/newvegas/mods/58277)
- [JohnnyGuitar NVSE](https://www.nexusmods.com/newvegas/mods/66927)
- [ShowOff xNVSE](https://www.nexusmods.com/newvegas/mods/72541)
- [User Interface Organizer](https://www.nexusmods.com/newvegas/mods/57174)
- [MCM Extender](https://www.nexusmods.com/newvegas/mods/93642)

## Installation
Installs like any other mod, manually or using a mod manager.