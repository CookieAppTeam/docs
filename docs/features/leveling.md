# Level System
Cookie provides a **customizable** level system for both **text** and **voice** activity.

- Members can use `/rank` to view their current level and XP.
- The server leaderboard can be accessed with `/leaderboard server`. 

!!! tip
    Members can disable their level-up ping using `/notifications`.

## ⚙️ Setup
1. Configure all settings with `/level settings`. By default, level-up messages will be sent
in the channel where the user leveled up.
2. You can customize level-up messages using the `/messages` command.

## ✏️ Text Levels
With **text levels**, users can collect XP when they write messages on your server.

- The XP reward and cooldown can be customized using `/level settings`.

## 🔊 Voice Levels
For **voice levels**, the minutes that you have been active in a voice channel are counted.

!!! note
    
    By default, voice minutes will not be counted in the following cases:
    
    - You are in the AFK channel.
    - You are alone in a voice channel.
    - You are headset-muted.
    - You are in a blacklisted channel.
