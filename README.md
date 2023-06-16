# PFC Stream Package

This repository contains a stream package used primarily by the [Persona Fight Club (PFC) community](https://discord.gg/p4au) to stream events. This package is specialized to stream [Persona 4 Arena Ultimax](https://www.atlus.com/p4au/). 

This repository is a combination of stream assets used by the PFC community and an [overlay project developed by Jolteo_](https://github.com/barnesrd/p4pc-overlay-2.0).

## Quickstart guide

All overlays are contained within the `overlay/html-overlays` folder. 

- `prematch.html` : Overlay that displays player characters and names with a backdrop 
- `comms.html` : Overlay that displays commentator navis. Built to display along with `prematch.html`
- `scoreboard.html` : Overlay that displays player names, countries, and score. Meant for display during gameplay.

The information in these overlays can be edited using two programs:

### PFC MatchControl

This is the main control program for all of the overlays. Contains multiple tabs that allows a user to edit individual overlay information.

Developed by Jolteo_

### Fuuka Bot

This is a simple twitch chat bot that allows moderators and owners of the connected twitch account to update scoreboard information. (Currently does not allow editing of country information)

To connect the bot to a channel, edit the `CHANNEL_NAME` variable in the `.env` file using a text editor of your choice. (Planned to be changed in a future update)

Refer to the [usage doc](https://pastebin.com/8UTkTzF5) for a list of commands

Developed by Jolteo_

## Edit permissions

To request edit permissions, contact Jolteo_ in the PFC discord server. Permissions will be given based on need.
