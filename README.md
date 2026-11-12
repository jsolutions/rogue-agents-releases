# Rogue Agents

A first-person shooter for one to four players, with the look and feel of the spy shooters of the late 1990s:
low-poly rooms, chunky guns, and missions made of things to do rather than only people to shoot. Every run is put
together afresh: four stages chosen along the way from fourteen, each with different rooms, objectives, guards and
supplies every time. Play it alone, with friends as a team, or against each other.

It is free, it is an early version, and everything in it (names, places, pictures, sounds, music) is its own.

## Get it

**[Download the latest release](../../releases/latest)** and pick the file for your computer:

| Your computer | The file | Then |
|---|---|---|
| Windows 10 or 11 | `RogueAgents-win-x64-...zip` | Unzip it anywhere and open `RogueAgents.exe`. Windows may say it does not know the program: choose "More info", then "Run anyway". |
| Linux (64-bit) | `RogueAgents-linux-x64-...tar.gz` | Unpack it and run `./RogueAgents`. Needs a graphics driver with Vulkan. |
| Mac with an Apple chip (M1 or later) | `RogueAgents-osx-arm64-...tar.gz` | Unpack it and follow `READ ME FIRST.txt` beside the app: the Mac objects the first time. Needs macOS 14 or later. |
| Mac with an Intel chip | `RogueAgents-osx-x64-...tar.gz` | The same. |

Nothing else needs installing. To remove it, delete the folder.

The warnings on Windows and Mac are because the programs are not signed with a paid certificate yet, not because
anything is wrong with them.

## Play

The game opens on its menu. **Play alone** starts a run. The keys are shown as each mission begins, and every one
can be changed under Settings, Controls: W A S D to move, the mouse to look, left button to fire, right to aim,
R to reload, E to use, Tab for the objectives, Esc for the menu. A controller works too.

**With friends in the same house:** one of you chooses Play with friends, Host on this network. Their pause menu
(Esc) shows the address the others type under Join on this network. The host's computer may ask whether to let the
game through its firewall: say yes.

**With friends over the internet:** you need the address of a lobby server, the small go-between that hands out
room codes. There is no public one: whoever invited you to play will give you theirs. Type it in once, under
Settings, Game, Lobby address. Then one of you chooses Play with friends, Make a room, and tells the others the
six-letter code.

Everyone playing together needs the same release.

## If it goes wrong

If the game stops unexpectedly it writes a report, and says where. It also notes down, as you play, the main
things that happen (a stage beginning, a player joining), so that a report can say what led up to the fault; if
the game is taken down too suddenly to write anything, it writes the report the next time you start it. The
reports are small text files in a folder called `crashes`, here:

| | |
|---|---|
| Windows | `%APPDATA%\RogueAgents\crashes` (paste that into the address bar of a folder window) |
| Linux | `~/.config/RogueAgents/crashes` |
| Mac | `~/Library/Application Support/RogueAgents/crashes` |

**Please send it:** [open an issue here](../../issues/new) and attach the newest `crash-...txt` file, with a line
about what you were doing. A report holds what went wrong, what the game was doing and what kind of computer it
is. It does not hold your name, your friends' names, or any internet address, and you can read it before you send
it. The game itself sends nothing anywhere.

Anything else that seems wrong, or simply not fun, is worth an issue too.

## What to expect

This is an early version. The whole game is there to be played from the menu to the end of a run, but:

- every picture and sound is a stand-in made by a program, waiting for an artist: boxes for tents, drums for radios;
- it has been played far more by its own automatic players than by people, so how hard it is and how the guns
  feel are first guesses;
- it has not yet been tried on a Mac, on a slow computer, or between two houses.

The [release notes](RELEASE-NOTES.md) list what each release holds and what is known not to work.

## Licence

Free to download, play and pass on unchanged: see [LICENSE.txt](LICENSE.txt). The libraries it is built on, and
their licences, are in [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).
