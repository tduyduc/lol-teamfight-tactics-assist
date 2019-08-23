# LOL Teamfight Tactics Assist

_Automation for League of Legends' Teamfight Tactics game mode_

_© 2019 T.D. Stoneheart. Some rights reserved. Source code available under GPLv3 license._

-----

## Disclaimer

The author **does not** assume any responsibility when you use this automation script, as it is not related to, endorsed by, or affiliated with Riot Games by any way.

While this automation script affects only the account it is run on, it might slightly affect other players' competitive gameplay experience negatively.

-----

## Introduction & How to use

This automation script is a companion of the (somewhat unethical) _LOL Vs. Bots Assist_ project, from which this project takes the codebase. It focuses on simplicity in order not to clutter the source code; no configuration GUIs are created, and number of games are not tracked. Also, the script is designed to work with any game client size without having to adjust to a fixed size.

The script is created to assist in completing as many games as possible by quitting and finding a new match as soon as you are eliminated. Keep in mind that the script cannot play for you, so do not expect ending up in high places with this automation.

Before launching the script, create a Teamfight Tactics lobby first. The _Find Match_ button should be visible on the game client.

Prior to automation, you will be able to choose to enable _Fast Finish_ mode or not to. When _Fast Finish_ is enabled, the script attempts to forfeit _(or surrender, or finish fast)_ games as soon as possible. Surrendering is available when the game has elapsed for at least 10 minutes, typically from round 3-1 onward.

At any time during automation, press <kbd>Shift</kbd>+<kbd>Esc</kbd> to pause automation. Switching to another window during the game is required to use this hotkey. You will be prompted to either resume or quit automation.

The script attempts to quit the game as soon as possible when you are eliminated from the game, and then finds a new match when you are back to the client. If you wish to find a new match when the winner is found and all other players are eliminated, use _LOL Vs. Bots Assist_. Uncheck the _moving only_ option and start automation from a Teamfight Tactics lobby; all other settings _(even the number of games limit setting!)_ have no effect.

You can also re-start automation during a Teamfight Tactics game in progress.

-----

## Known issues

* The `/FF` chat message _(for forfeiting)_ is not really reliable, often leaving an empty chat box without recognizing any keystrokes as message text. To deal with this issue, <kbd>Shift</kbd>+<kbd>F</kbd> is used instead of <kbd>F</kbd> to avoid unexpectedly buying experience points.
* Networking issues might soft-lock the automation, leaving the game stuck in _"Attempting to connect"_.

-----
