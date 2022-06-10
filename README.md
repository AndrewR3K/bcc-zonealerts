
# BCC - zonealerts (THIS CODEBASE HAS BEEN DEPRECATED!! ANY AND ALL FUTURE DEVELOPMENT WILL BE CONTINUED ON [VORPCORE/vorp_zonenotify](https://github.com/VORPCORE/vorp_zonenotify)

> A RedM zone notification system for [Vorp Core](http://docs.vorpcore.com:3000/)

Join the [VORP Community Discord](https://discord.gg/23MPbQ6)

## Features

1. Displays a top notification when you enter towns, districts, states, and others.
2. Displays the time within the notification
3. Displays the temperature within the notification
4. 233+ Zones!
5. Config based native notificaton or a custom Vue.js notification
    
    -- Custom
    ![image](https://user-images.githubusercontent.com/10902965/170663856-e6b11c13-df2e-49e7-957a-10bc4bec9774.png)

    -- Native
    ![image](https://user-images.githubusercontent.com/10902965/170857584-2bca2214-e671-4c7d-87f8-acd5022f02c3.png)



## Installation
1. Download this repo/codebase
2. Extract and place `bcc-zonealerts` into your `resources` folder
3. Add `ensure bcc-zonealerts` to your `server.cfg` file
4. Restart your server (unless you have nightly restarts)

## How-to-configure
All configurations available in `config.lua`

- NativeZones = True/False (If you want to use the native notification of the custom one)
- Notification.TimeShowing = How long the notification will display.

## TODO
- [Trello](https://trello.com/b/CYsF6PuX/bcc-zonealerts)

 ## Dependency
 - Vorp Core
