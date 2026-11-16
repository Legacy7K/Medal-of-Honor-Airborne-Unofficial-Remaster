# Medal of Honor Airborne Unofficial Remaster

My attempt at the remaster Airborne never got. It's a mod loader and 17 mods for the PC version that go through pretty much every part of the game: a new HUD, 1:1 damage, harder AI that you can tune per difficulty, lean, hold breath and stamina, suppression, ragdolls, a proper look for every map, longer view distance and reworked tanks. Plus a settings app so you can switch any of it off, and that keeps the pack up to date for you.

I built it around my own Expert playthroughs, so out of the box it's on the hard and realistic side. If that's not your thing, almost all of it can be turned down or off.

This is a fan project. It's not official and EA / DICE have nothing to do with it. There is a lot of new modifications and features. Most things have been changed so make sure to OVERWRITE your previous install. Please let me know if you encounter any bugs/issues. There is also a (TEST) category in the settings app which is OFF by default. If you would like to use it, give it a try and let me know.

**[Download the latest version](https://github.com/Legacy7K/Medal-of-Honor-Airborne-Unofficial-Remaster/releases/latest)**

---

## Difficulty

Everyone takes the same damage from the same gun. You, your squad, the Germans, the Italians. Your headshots and the enemy's kill a soldier outright, and a helmet won't save him (it still flies off). The difficulty then decides how much punishment you can take:

| | Casual | Normal | Expert |
|---|---|---|---|
| Enemy AI | a quarter of the harder AI | three quarters of the harder AI | the full harder AI |
| Your health | 2.5x | 1x | 0.5x |
| Healing | whole bar, 5 s after you're hurt | the quarter you're in, after 10 s | never |
| Enemy shots that miss on purpose | 50% | 10% | none |
| HUD | on | on | none |

Enemy numbers are the game's own on every difficulty. Double the enemies on Expert is still in the pack (the Enemy Population mod), switched off by default.

Enemies far away also take a few seconds to get their shots onto you (5 s on Casual, 2.5 s on Normal). Expert has none of that.

## The enemy

They engage from further out, use cover better, peek less and push harder. Now and then they move to new cover, firing as they go, and when they get close they stand and fight instead of running past you. No more stopping to do hand signals in the middle of a fight either. They only see the 75 degrees in front of them, so no more turning on the spot to shoot you in the back. They also split their fire between you and your squad instead of all piling onto you.

Enemies and your squad move at a steady 500 whether they're walking or sprinting (the game's own is 500 / 600).

The Nazi Storm Elite are an actual threat now. They take 20x the punishment of a normal soldier, and on Normal and Expert they jog instead of plodding along. Headshots won't drop them in one either.

## Your squad

With everyone doing full damage, your squad was clearing half the fights before you even got there. Now they're 50% worse shots, engage from half the distance, half their bullets miss and their hits do half damage. They keep the enemy busy, you do the killing.

## Tanks

- They spot you from up to 150 m and look for a new target every couple of seconds. On Expert they keep firing where they last saw you after you break line of sight.
- The crews watch all round, so sneaking up behind a tank won't save you. Get right up against it, below where they can look, and it can't see you.
- The main gun has a realistic reload and a slow 15 degree a second turret. It won't aim at you when you're right up close, but a moving tank will happily drive over you instead.
- Tanks that drive a route can stop to fight you, pull up now and then, drive on to get a better angle when their shot is blocked, and swing the turret back to the front once there's nobody left.
- Hit a tank and it stops, and if it can't see you the turret sweeps around looking for you. Wreck its tracks and the engine keeps running until you finish it off.
- Tanks are heard from much further away and never go quiet in a big fight.

## Weapons and movement

- Lean on Q / E, from the hip or down the sights, and you can walk while leaning. Numpad lean keys work with Num Lock on or off.
- Hold breath on Left Alt, on iron sights and scopes. On a scope it slows the game down for a moment, like the upgrade slow-mo.
- Stamina, shared between sprinting and holding your breath. Sprint it dry and you're walking until you get it back.
- Light breathing sway when you aim, worse when you move or after a sprint, better crouched.
- Hip fire actually scatters now and every gun kicks harder.
- MG nests are a handful. They spray 5x wider and kick twice as hard, and the enemy gunners on them spray twice as wide.
- Reload a Thompson, MP40, BAR or StG 44 early and the rounds left in the magazine go with it. Barrels smoke after a few rifle shots or a long burst.
- Every gun kicks half as much while you're crouched.
- Suppression. Rounds cracking past you blur and darken the edges of the screen and jolt the camera, and when it gets really heavy your hearing goes and your ears ring.
- Ragdolls that fall depending on where they were hit, with the game's own death animation about one time in four. Bodies are heavy, they never hang in the air or fly off, and they stick around instead of vanishing when you look away.
- Badly hurt, you hear slow, heavy breathing and your heartbeat.
- Movement with some weight to it: you build up to speed, the gun trails a little behind your movements, the camera catches up a moment later and moves with your steps, the lean eases in and out, and the view eases to a stop after you move the mouse. Each part can be turned down or off.
- Weapon upgrades no longer slow everything down or blur the screen.
- German scopes for the Gewehr 43 and the StG44.

## HUD

A new HUD that keeps the game's own look, its brackets, the red cross and a steel-blue health bar, with spaced out capitals and italic serif type.

- A compass along the top with your current objectives and how far away they are.
- Health as four segments with how you're doing written above it: Fit for duty, Lightly wounded, Wounded, Seriously wounded. It goes red and pulses when you're nearly dead.
- Your weapon, its upgrade stars, the ammo and your grenades. Handguns show their unlimited reserve as an infinity sign.
- An optional small crosshair that shows where your shots will actually land, traced from the gun, not the middle of the screen (off by default).
- A stamina bar, grenade warnings, objective notices, and stars for how well you landed after a jump.
- New scopes with a sharp eyepiece, and a blurred world around them instead of a black screen.

## Graphics and sound

Every map has its own look, each with its own page in the settings app. Husky is a warm night with a light haze, Avalanche cold with fog, Neptune and Der Flakturm grey and stormy with thunder and lightning, Market Garden dusty and Varsity has ash falling from the burning factory. On top of that there's ambient occlusion, sharpening, a film-style colour grade, better bloom and lens flare, light shafts, film grain, motion blur only on fast turns, and clouds and wind streaks rushing past on parachute jumps. There's also tone mapping, depth of field on iron sights, shell shock, barrel heat haze, lens dirt, fog glow, breath frost on Avalanche, wet ground reflections and contact shadows, plus SMAA anti-aliasing. The game runs on Vulkan through DXVK (you can switch it back to Direct3D 9), and the 60 frames a second cap is lifted.

View distance is 10x further for buildings, scenery and detail, and the field of view is wider (120, 105 aiming, 135 sprinting). All adjustable.

You'll also hear a battle going on around you: distant artillery, machine guns, rifle fire and planes overhead, all using the game's own sounds. It goes quiet indoors and fades in on the way down from a jump. Every gunshot echoes a little off the buildings and hills around it, and gunshots carry five times further. On High Sound Quality the game can play 150 sounds at once instead of 91, and tank sounds are never the ones it drops.

## Settings app

Everything in the pack is in one window. Every option has a short explanation of what it does, there's a Reset button for each page, and Launch Game starts the game for you. It also has the game's own launcher settings and full key bindings, with two keys per action, so you can put weapon switching and scope zoom on the mouse wheel together. Tanks that stay put and tanks that drive a route each have their own copy of every tank setting. And it plays music while it's open, with a volume control in the top left.

## Extras

- Discord status that shows whether you're in the menu, choosing your class or in a mission, and which map.
- An in-game reader on ~ that shows what every mod is doing, handy if something goes wrong.
- The fix for not being able to get back into the game after alt-tabbing.
- The old debug keys are turned off (no more accidental free weapon upgrades on F11).
- Skip the EA intro and the logo screen when the game starts.
- Class Selection (TEST) in the settings app, off by default while it's being tested: the Storm Elite dropping his MG42 for you to pick up, rocket launchers and the MG42 in the class selection, slot rules, coloured gun pictures and every gun loaded in ready from the start.
- A crash guard: a surface missing the lighting it needs is drawn plainly instead of crashing the game.

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
