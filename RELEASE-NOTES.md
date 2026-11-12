# Rogue Agents: release notes

## The fourth release (November 2026): one crescent, four new names

- **Health and armour are one crescent across the foot of the view,** not a pair: thick at its middle and drawn
  out to a point at either end; health is its teeth, cream going to red, and armour a row of steel plates riding
  outside them. (The pair, health on one side and armour on
  the other, was too like one classic's gauges; an independent review of the game's originality said so.)
- **Four guns have new names,** for the same reason (their old ones turned out to be other games' guns, or a real
  one): the pistol is the Wren No. 3, the shotgun the Lurcher 12, the automatic shotgun the Airedale, and the heavy
  submachine gun the Corncrake. Nothing about how they shoot has changed.
- It plays with the third release: nothing about how games talk to each other has changed.

## The third release (November 2026): first fixes from play

Everything the second release had, with what its first long play-through found wrong put right. **It cannot join
games of the second release, nor the other way round** (the two say so): everyone playing together needs this one.

- **Fixed: Esc did not hold the pause menu open.** On a keyboard the menu opened and shut on the same press.
- **The alarm is no longer the loudest thing in the game.** A fault made every looping sound play at full whatever
  its volume said. The alarm now sits a little above the music and background of a fight, and well under the guns.
- **Guns are a touch louder beside everything else:** a sharper crack, and the music and background step back for
  a moment under your own fire.
- **Water is in the way.** Nobody wades any more: the Jungle's stream is crossed by its two bridges and the stones
  of its ford, and the Cave's island by its boardwalk. Bullets and sight still cross water, which now moves, and
  a round that lands in it throws up a splash.
- **The first difficulty is kinder.** A round to the head puts down any guard, the heavy included. Fewer guards
  are on duty, and those who would stand nearest to where you arrive are the first given the day off. The alarm
  brings two, later, where it brought four, sooner.
- **A hit staggers a guard for half as long again,** on every difficulty; and a guard a long way off runs straight
  at you much less often.
- **Being hit pushes you** a little way from where the shot came (forward, if you are shot in the back), with a
  grunt; team-mates hear it from where you stand. A blast pushes further. Never over an edge.
- **Health and armour are two curved gauges** in the lower corners of the view, a segment for each point: health
  from amber to red as it goes, armour in teal, what was just lost shown white for a moment. A wedge on a ring
  outside them flares towards whoever hit you.
- **Fixed: a gun of the newer kinds lying on the ground looked like the plain kind** to anyone who had joined
  somebody else's game.

Getting it going, playing with friends, the known limits and what nobody has yet tried are as for the second
release, below.

## The second release (November 2026)

The first release that anyone can download. One to four agents fight through a run of four stages, chosen along
the way from fourteen, taking a powerup with them from each to the next; or play against each other. Everything
in it (names, places, pictures, sounds, music) is the game's own.

**Read this first:** this is an early version. Every picture and sound is a stand-in made by a program. It has
been played at length by one person on one Windows PC, who enjoyed it, and by automatic players by the thousand;
what has not been tried by anyone is listed under "Not yet tried", and the list is long and honest.

### Getting it going
| System | Download | Then |
|---|---|---|
| Windows 10 or 11 | `RogueAgents-win-x64-...zip` | Unzip anywhere, open `RogueAgents.exe`. Windows may warn that it does not know the program: "More info", then "Run anyway". |
| Linux (64-bit) | `RogueAgents-linux-x64-...tar.gz` | Unpack, run `./RogueAgents`. Needs a graphics driver with Vulkan. |
| Mac, Apple chip (M1 or later) | `RogueAgents-osx-arm64-...tar.gz` | Unpack and follow `READ ME FIRST.txt` beside the app: the Mac will object the first time. Needs macOS 14 or later. |
| Mac, Intel | `RogueAgents-osx-x64-...tar.gz` | The same. |

Nothing else needs installing. **Everyone playing together needs this same release:** it cannot join games of
the first release, nor the other way round (the two say so when they try).

### Playing with friends
- **In the same house (same network):** one player chooses Play with friends, Host on this network. Their pause
  menu (Esc) shows the address the others type under Join on this network. The host's PC may ask to let the game
  through its firewall (it uses UDP port 27817).
- **Over the internet:** this needs a lobby server, the small program that hands out room codes and introduces
  the players' computers to each other. **There is no public lobby.** Whoever looks after your group's games runs
  one and gives you its address, which goes in Settings, Game, Lobby address, once. Then: Play with friends, Make
  a room; tell the others the six-letter code; they choose Join a room.

### What is new since the first release
- **Eleven more stages, and a run that is four stages long.** A run begins in the Jungle, the Forest (a railway
  through a pine wood at dusk, a relay station behind a fence) or the Snow (a weather station round a frozen
  lake); which, the run decides. Then the team votes between three ways on, from the Bunker, the Cave, the Yacht
  (three decks of a ship at anchor), the Village (a street, a square, a walled yard on a hill) and the Mansion (a
  country house of two storeys round a great hall); then again, from the Gallery (picture rooms round a sculpture
  court, a vault), the Prison (two yards, a cell block of two tiers), the Office (in by the roof, down two floors)
  and the Docks (a container yard, a warehouse, a freighter); and last between the Lighthouse (a rock in the sea
  in a gale, and a tower climbed room by room to the lamp) and the Observatory (a track up a mountain at first
  light to a great dish), where a run ends. The last two are provisional and may change.
- **Twelve guns.** Each of the four weapon slots now has three kinds of gun: the one everybody starts with, and two
  to find. A revolver and a machine pistol; a silenced submachine gun and a heavy one; a marksman's rifle and a
  light machine gun; an automatic shotgun and a grenade launcher. A gun of a kind you are not carrying is changed
  for by pressing Use beside it, and yours is left in its place. Which kind lies where is different every run.
  (The eight new guns borrow the sounds and shapes of the first four for now.)
- **Small rounds lose their force with distance.** The silenced pistol does half its damage by 28 metres.
- **Six more powerups** (fourteen in all), two of them with a price: the Lone Wolf, who is hurt less and cannot be
  revived, and the Hair Trigger, which fires faster from smaller magazines.
- **Two more kinds of objective.** *Bring someone out:* talk to them and they follow you, opening doors as they
  come, and the mission ends only when they are at the way out with the team. (If they are killed it becomes
  "search the body", and the alarm rings.) *Plant something:* hold Use for four seconds at a place marked with four
  gold corners; what was planted stays there, blinking. Every stage has one of each among the eight things it can
  ask for.
- **Playing against each other.** Whoever hosts (on one network, or by making a room) can choose "Against each
  other" instead of a run: everyone for themselves, two teams, or One Shot, where any hit kills. It is played on
  one of eight places (the Hall, the Bunker, the Yacht, the Gallery, the Mansion, the Prison, the Office, the
  Lighthouse) with nobody home: no guards, nothing asked for. Everyone starts with the pistol; guns, armour and
  medical kits lie where they lie in the stage and come back twenty seconds after they are taken. Three seconds
  after falling you are back, somewhere far from the others. First to the kills wins, or whoever is ahead when the
  time is up. Every number in it is a first guess.
- **Losing the host no longer loses the stage.** Over the internet, if the player whose computer is running the
  game drops out in the middle of a stage, one of the others takes over and the stage carries on from where it
  was: the same guards down, the same objectives done, everyone where they stood with what they had. The game
  stops for six to eight seconds while everyone finds the new host, and up to three seconds of play are lost.
  (Before, the stage began again.)
- **Music.** A piece behind the menus; in a stage, a calm piece with a tense layer that comes in over it when the
  guards are after you and goes again a few seconds after they lose you; a short piece when a mission is won or
  lost. Its loudness is its own (Settings, Sound). Like every other sound in the game it is a stand-in made by a
  program.
- **For whoever makes the real sounds:** a pack of your own can be chosen in Settings, Sound; the game makes an
  empty one for you with a list of every sound it asks for, and checks a pack for mistakes.
- **Something carries over between runs.** The game keeps a record of what you have done over all your runs, and
  ten feats (finish a stage, win a run, a hundred guards down...). Five of them each unlock a **kit**: a different
  way to begin a run (a padded jacket, a revolver or a machine pistol in place of the pistol, or one powerup
  already taken). Choose it under **Kit and records** on the main menu; what a run earned is said on the screen at
  its end. The record is yours alone, kept on your computer.
- **A run gets a little harder as it goes:** more of a stage's guards are on duty for every stage already come
  through.
- **A crash report now says what led up to the crash.** As you play, the game notes the main things that happen
  (a menu opened, a stage begun and what it was made from, a player joining, the host changing). A report ends
  with the last of them, after the error and where in the program it was. And if the game is taken down too
  suddenly to write anything (a graphics driver's fault, a freeze ended from Task Manager), the report is written
  the next time the game starts, from the log the last session left. See "If something goes wrong".
- **Fixed: some doors could not be walked through.** In the first release a player could not walk into the store
  or the barracks in the Jungle's yard: the body stopped at the doorstep. Fixed for every door.
- **Fixed: the floor of the Mansion's garage flickered** between concrete and the yard's gravel.
- Footsteps on snow have their own sound.
- Each download now carries the licences of the software it is built on (the folder `licenses`).

### Known limits
- All pictures and sounds are stand-ins made by the project's own tools: boxes for tents, drums for radios.
- Guards walk through players (they do not collide with them), and characters are not lit by the level's lights.
- The difficulties change numbers (objectives, guards, supplies), not how guards behave.
- If the host's computer is lost during the pause between stages, the team plays the finished stage again.
- No names over team-mates' heads.
- Music and sounds are read from WAV files only.
- The Windows and Mac programs are not signed with a paid certificate, so both systems warn the first time.
- On Windows a console window may flash for a moment when the game is opened with a double-click.

### Not yet tried
One person has played it, on one Windows PC. Nobody has yet reported on:
- **How hard it is, for people.** The automatic players win almost every run on the first difficulty, so it may
  be too easy; the second and third are harder.
- **The sound and the music.** They were checked by measurement, not by ear.
- **Playing against each other, a change of host in mid-stage, and the kits,** with people rather than automatic
  players.
- **A controller.** Its support is written and tested in code; none has been plugged in.
- **A Mac.** The Mac downloads are made and checked for shape only.
- **A slow PC.** The target is 60 pictures a second on a 2017 laptop with built-in graphics; the figures say it
  should manage easily, but none has run it.
- **Real home networks.** Internet play is tested with real programs on one PC, with the connection made poor on
  purpose, and Linux with Windows through a container; not between two houses.
- **A Linux PC with a graphics card.** The Linux build is checked in a container that draws in software.

### If something goes wrong
If the game stops unexpectedly it saves a report and says where: a file named `crash-...txt`, in a folder
`crashes` beside its settings (`%APPDATA%\RogueAgents` on Windows, `~/.config/RogueAgents` on Linux,
`~/Library/Application Support/RogueAgents` on a Mac). If it was taken down too suddenly to say anything, it
writes the report, and tells you so, the next time it starts. Sending that file to whoever gave you the game is
the most useful thing you can do.

A report holds what went wrong and where in the program, the last things that happened before it, what the game
was doing and what kind of computer it is. It does not hold your name or anyone else's, no internet addresses and
no room codes, and it is plain text: read it before you send it if you like. The folder `logs` beside it holds
the notes of the last five times the game was played, of the same kind. Nothing is sent anywhere by the game
itself.

## The first release (November 2026)

The first version that was a whole game from the main menu to the end of a run, given to nobody but its makers.
One to four agents fought through the Jungle, then the team's choice of the Bunker or the Cave, taking one powerup
with them between the two.

- **A run of two stages:** the Jungle, then the Bunker or the Cave (the team votes). Each stage is put together
  afresh every run: which rooms are in its swap slots, which objectives are asked for, where the key lies, how
  many guards are on duty, what supplies there are.
- **Three kinds of objective:** find the key and open the door; destroy the containers; talk to someone (and
  search them if a stray shot got there first). Then reach the way out.
- **Three difficulties:** two, three or five objectives a stage, with more guards and fewer supplies.
- **Four guns:** the Wren No. 3 pistol (silenced; it can always be reloaded), the Kestrel submachine gun, the Harrier
  rifle and the Lurcher 12 shotgun. Guards drop what they carried.
- **Eight powerups,** two of which cost something. One is chosen after the first stage.
- **Guards** that hear and see, raise the alarm, call for more, take cover, and flinch by where they are hit; and a
  heavier kind.
- **Co-op for up to four:** on one network, or over the internet by room code. A team-mate who goes down can be
  got up again; the run is lost when everyone is down.
- **Menus:** play alone, play with friends, settings (every key can be changed; picture; sound; your name).
  Keyboard and mouse, or a controller.
- **Downloads** for Windows, Linux, and Mac (Apple chips and Intel).
