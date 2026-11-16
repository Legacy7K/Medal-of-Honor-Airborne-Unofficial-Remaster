# Medal of Honor Airborne Unofficial Remaster

My attempt at the remaster Airborne never got. It's a mod loader and 17 mods for the PC version that go through pretty much every part of the game: a new HUD, 1:1 damage, harder AI that you can tune per difficulty, lean, hold breath and stamina, suppression, ragdolls, a proper look for every map, longer view distance and reworked tanks. Plus a settings app so you can switch any of it off, and that keeps the pack up to date for you.

I built it around my own Expert playthroughs, so out of the box it's on the hard and realistic side. If that's not your thing, almost all of it can be turned down or off.

This is a fan project. It's not official and EA / DICE have nothing to do with it.

**[Download the latest version](https://github.com/Legacy7K/Medal-of-Honor-Airborne-Unofficial-Remaster/releases/latest)**

---

## Difficulty

Everyone takes the same damage from the same gun. You, your squad, the Germans, the Italians. Your headshots and the enemy's kill a soldier outright, and a helmet won't save him (it still flies off). The difficulty then decides how much punishment you can take:

| | Casual | Normal | Expert |
|---|---|---|---|
| Enemy AI | the game's own | halfway to the harder AI | the full harder AI |
| Enemies | the game's numbers | the game's numbers | double |
| Your health | 3x | 2x | 1x |
| Healing | whole bar, 5 s after you're hurt | the quarter you're in, after 15 s | never |
| Enemy shots that miss on purpose | 50% | 25% | none |
| HUD | on | on | none |

Enemies far away also miss more often on Casual and Normal, and on Casual they take a couple of seconds to get their shots onto you. Expert has none of that.

## The enemy

They engage from further out, use cover better, peek less and push harder. Now and then they move to new cover, firing as they go, and when they get close they stand and fight instead of running past you. No more stopping to do hand signals in the middle of a fight either. They only see the 90 degrees in front of them, so no more turning on the spot to shoot you in the back. They also split their fire between you and your squad instead of all piling onto you.

Everyone moves faster than in the original. Enemies and your squad walk at 600 and sprint at 900 (the game's own is 500 / 600).

The Nazi Storm Elite are an actual threat now. They take 20x the punishment of a normal soldier and jog instead of plodding along. Headshots won't drop them in one either. Kill one and he can drop his MG42 for you to pick up (still being tested).

## Your squad

With everyone doing full damage, your squad was clearing half the fights before you even got there. Now they're 25% worse shots, engage from closer in, a quarter of their bullets miss and their hits do three quarters of the damage. They keep the enemy busy, you do the killing.

## Tanks

- They spot you from up to 300 m, keep firing where they last saw you after you break line of sight, and are always looking for a new target.
- The turret crew and the hull crew watch different directions. Get behind both, or right up against the tank below where they can look, and you're invisible to it.
- The main gun has a realistic reload and a 30 degree a second turret. It won't aim at you when you're right up close, but a moving tank will happily drive over you instead.
- Tanks that drive a route can stop to fight you, pull up now and then, drive on to get a better angle when their shot is blocked, and swing the turret back to the front once there's nobody left.
- Hit a tank and it stops, and if it can't see you the turret sweeps around looking for you. Wreck its tracks and the engine keeps running until you finish it off.
- Tanks are heard from much further away and never go quiet in a big fight.

## Weapons and movement

- Lean on Q / E, from the hip or down the sights, and you can walk while leaning.
- Hold breath on Left Alt, on iron sights and scopes. On a scope it slows the game down for a moment, like the upgrade slow-mo.
- Stamina, shared between sprinting and holding your breath. Sprint it dry and you're walking until you get it back.
- Light breathing sway when you aim, worse when you move or after a sprint, better crouched.
- Hip fire actually scatters now and every gun kicks harder.
- MG nests are a handful. They spray 2.5x wider and kick 2.5x harder, and the enemy gunners on them spray twice as wide.
- Reload a Thompson, MP40, BAR or StG 44 early and the rounds left in the magazine go with it. Barrels smoke after a few rifle shots or a long burst.
- Every gun kicks half as much while you're crouched.
- Suppression. Rounds cracking past you blur and darken the edges of the screen and jolt the camera, and when it gets really heavy your hearing goes and your ears ring.
- Ragdolls that fall depending on where they were hit, with the game's own death animation about one time in four. Bodies are heavy, they never hang in the air or fly off, and they stick around instead of vanishing when you look away.
- Badly hurt, you hear slow, heavy breathing and your heartbeat.
- Movement with some weight to it (still being tested): you build up to speed, the gun trails a little behind your movements, the camera catches up a moment later and moves with your steps. Each part can be switched off.
- Weapon upgrades no longer slow everything down or blur the screen.
- German scopes for the Gewehr 43 and the StG44.

## HUD

A new HUD in the style of a 1940s newsreel. Thin lines, spaced out capitals, italic serif type, no boxes anywhere.

- A compass along the top with your current objectives and how far away they are.
- Health as one thin line with how you're doing written above it: Fit for duty, Lightly wounded, Wounded, Seriously wounded.
- Your weapon, its upgrade stars, the ammo and your grenades.
- A small crosshair that shows where your shots will actually land, traced from the gun, not the middle of the screen.
- A stamina bar, grenade warnings, objective notices, and stars for how well you landed after a jump.
- New scopes with a sharp eyepiece, and a blurred world around them instead of a black screen.

## Graphics and sound

Every map has its own look, each with its own page in the settings app. Husky is a warm night with a light haze, Avalanche cold with fog, Neptune and Der Flakturm grey and stormy with thunder and lightning, Market Garden dusty and Varsity has ash falling from the burning factory. On top of that there's ambient occlusion, sharpening, a film-style colour grade, better bloom and lens flare, light shafts, film grain, motion blur only on fast turns, and clouds and wind streaks rushing past on parachute jumps. There's also tone mapping, depth of field on iron sights, shell shock, barrel heat haze, lens dirt, fog glow, breath frost on Avalanche, wet ground reflections and contact shadows, plus SMAA anti-aliasing. The game can run on Vulkan through DXVK, and the 60 frames a second cap can be lifted.

View distance is 5x further and the field of view is wider (120, 105 aiming, 135 sprinting). All adjustable.

You'll also hear a battle going on around you: distant artillery, machine guns, rifle fire and planes overhead, all using the game's own sounds. It goes quiet indoors and fades in on the way down from a jump. Every gunshot echoes a little off the buildings and hills around it, and gunshots carry five times further.

## Settings app

Everything in the pack is in one window. Every option has a short explanation of what it does, there's a Reset button for each page, and Launch Game starts the game for you. It also has the game's own launcher settings and full key bindings, with two keys per action, so you can put weapon switching and scope zoom on the mouse wheel together.

## Extras

- Discord status that shows whether you're in the menu, choosing your class or in a mission, and which map.
- An in-game reader on ~ that shows what every mod is doing, handy if something goes wrong.
- The fix for not being able to get back into the game after alt-tabbing.
- The old debug keys are turned off (no more accidental free weapon upgrades on F11).
- Skip the EA intro and the logo screen when the game starts.
- Class selection extras, off by default while they're being tested: rocket launchers and the Storm Elite's MG42 in the class selection, slot rules and coloured gun pictures.

## Controls that change

| Key | Does |
|---|---|
| Left Shift | sprint |
| Q / E | lean left / right |
| Left Alt | hold breath |
| F | use |
| Middle mouse | melee |
| B | alt fire |

Every one of these can be changed in the settings app.

---

## Installing

1. Back up `UnrealEngine3\MOHAGame\Config` and `MOHAGame\Splash\Splash.bmp` in your game folder.
2. Copy `Binaries` and `MOHAGame` from the zip's `Game Folder` into `UnrealEngine3` and say yes to replace. `dinput8.dll` has to end up next to `MOHA.exe`.
3. Move the six `MOHA*.ini` files out of `Documents\EA Games\Medal of Honor Airborne(tm)\Config` so the game makes fresh ones. You'll have to set your resolution and keys again.
4. Start the game. You'll see REMASTERED on the splash screen and a badge on the main menu.
5. Optional but strongly recommended with the longer view distance: download the 4GB patch from the same page and run it once.

The full guide, uninstall steps and troubleshooting are in the README inside the zip. To turn the whole thing off quickly, just delete `Binaries\dinput8.dll`.

## Updating

Close the game, open the settings app and press **Check for Updates**. If there's a newer version it downloads it with a progress bar, then installs it and opens the app again.

Updating replaces your settings with the new version's defaults. Backing up your old settings isn't recommended, because new versions can add or change settings and an old backup can bring back outdated values.

## Requirements

- Medal of Honor: Airborne for PC. Made and tested on the Steam version.
- Single player only.
- Use a clean install, not one with another overhaul on it.
- Old saves are fine, just start missions from the beginning instead of loading mid-level.

## Antivirus warnings

Your browser or antivirus might flag the download. It's a false positive. The mod loader is a `dinput8.dll` that loads itself into the game when it starts, which is the same trick a lot of game mods and fixes use. If it gets blocked, allow it, or check it on VirusTotal yourself first.

## Problems?

Open an issue here and attach `Binaries\MOHAModLoader\loader.log` and `problems.log`, plus the log from the mod that's acting up (each mod has its own in `Binaries\Mods\<mod name>`). Say which mission and roughly where it happened.

## Credits

Made by Kev-O. Medal of Honor: Airborne belongs to EA. The textures, sounds and icons all come from the game itself, apart from a few extra sounds I made for the pack.

Please don't reupload this anywhere without asking me first. If you want to use part of it in your own mod, just ask.
