# Fast Swimmer

Fish vs Worms, underwater, 2 to 10 players online.

One player is the **Fish** and hunts everyone else. The **Worms** hide in kelp forests, rock nooks and behind spires,
grab glowing orbs to heal, and three orbs turn a Worm into a **MiniFish** that can bite back.
Worms win if the timer runs out or the Fish dies.

## Download (Windows, 64-bit)

Go to **[Releases](../../releases/latest)** and download `FastSwimmer-Windows.zip`.

1. Unzip the whole folder anywhere (keep the files together).
2. Run `FastSwimmer\FastSwimmer.exe`. Windows may warn about an unknown app the first time: **More info > Run anyway**.
3. Click **Play**, type your name, then **Quick Play** (joins an open game or starts one), or **Create Lobby >
   Private** and send your friends the join code (press Esc in game to see and copy it).

You need an internet connection. Full instructions and controls are in `README.txt` inside the zip.

## Controls

| Key | Action |
|---|---|
| W / S | swim forward / back |
| W (Worm) | crawl very slowly along the ground (only a slow wriggle in open water) |
| Mouse | steer and look around |
| Space (hold, release) | charge, then lunge (Fish) or dash (Worm: it arches up, then springs off) |
| E (Fish) | Reveal: Worms and MiniFish glow red through walls for 5 s (every 30 s) |
| Alt (hold) | look around while swimming straight |
| Caps Lock | free the mouse cursor / back to mouse-look |
| Tab | player list |
| Esc | menu: join code + Copy, Resume, Leave Game |
| V (hold) | talk (voice chat: off until you turn it on in Settings > Volume; 13+) |
| Q / E, F, wheel | spectating: switch player, free camera, zoom |

## Voice chat and privacy

Voice chat is **off** until you turn it on in Settings > Volume and agree to a short notice; it's for players
**13 and older**. Push-to-talk (hold V) is the default, and `/mute NAME` in chat mutes a player for you. Your voice goes
live through Unity's voice service (Vivox) to players near you in your game; Fast Swimmer does not record or store it.

To play online the game uses Unity's online services (anonymous sign-in, Lobby, Relay, and Vivox only if voice is
on). There are no ads, no purchases and no analytics of our own, and nothing is sold. The full notice is `PRIVACY.txt`
in the zip; Unity's own policy: https://unity.com/legal/game-player-and-app-user-privacy-policy.
Questions or a deletion request: open an issue here (it's public: don't post anything private).

Open-source licence notices for the parts inside the Unity packages are in `THIRD_PARTY_NOTICES.txt` in the zip.
Made with Unity.

This repository only hosts the game downloads; the source code is private.
