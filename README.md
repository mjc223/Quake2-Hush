# Hush

## What is Hush

Hush is a mod of Quake 2 styled after popular games of the survival horror genre, namely *Resident Evil* and *Silent Hill*, taking inspiration from their game flow, weaponry, enemy attacking and aggro behavior, movement, camera angles, and item descriptions.


## What has been (will be) changed

### Static Camera Angles and Player Movement
Survival horror is known for limiting player information and movement, therefore Hush mimics this by augmenting player movement (heavily slowing it, removing jumps)
and moving the camera to a closer/claustrophobic third person view. //Not implemented

### Object Interaction/Item Descriptions
Many survival horror games are heavily character focused, and one way characterization of the main character is performed is through the comments of the protagonist on
various in game objects, events, and items. Hush allows the main character to remark on picked up items in order to have characterization.

### Weaponry
Weaponry has been augmented in Hush. Survival Horror games like *Resident Evil* and *Silent Hill* have a small variety of weapons, with clear niches depending on ammo availability, range, damage, etc. Additionally, melee weapons are a common weapon type in survival horror due to the extremely limited range and inherent risk in using melee over ranged options.

Primaries: 

 - Pump Shotgun (High damage at close, moderate ammo efficiency, bad range, low rof) (Over super shotgun)
 - Pistol (Moderate damage, High ammo capacity, moderate rof) (Over blaster)
 - Hunting Rifle (Extreme damage, extreme range, low ammo efficiency, low ROF) (Over railgun)

Melee: 

 - Knife: The default option, fast swing speed for stun locking, but pitiful range and weak damage. (Over machinegun)
 - Aluminum Bat: The all rounder melee weapon, sizable range, respectable damage, but still only hits one target. (Over shotgun)
 - Fire Axe: The crowd killer, it can hit multiple targets at once, has good knockback, but painful windup. (Over grenade launcher)
 - Taser: Instantly incapacitates any enemy, but single use. (Over Hyper Blaster)


### Enemy Behavior
In *Silent Hill*, enemies generally only have melee attacks. In Hush, enemy behavior has been modified to reflect this fact, the following enemy behaviors have been converted:

- Enemy 1
    Didn't have time
- Enemy 2
    Sorry about that
- Enemy 3
    No one's reading this
- Enemy 4
    Play Dwarf Fortress
- Enemy 5
    Merry Christmas


### Monster Aggression and the Radio/Flashlight
In many survival horror games, namely *Silent Hill*, you are given tools to make the detection and dispatching of enemies easier, but they come at a cost. in *Silent Hill*, these tools are the Radio and the Flashlight. In Hush, both of these tools cause enemies to be alerted more easily, making navigation and the evasion of enemies more difficult.

## How To Test

Most of Hush's functionality can be tested by loading up the test map, but with debug functionality, more specific things can be tested.

### Static Camera Angles and Player Movement:
Traditional fps controls, minus the ability to jump. TPP was not implemented.

### Object Interaction/Item Descriptions:
Type desc in console to view the currently held weapon's description

### Weaponry:
Type give all in console, and they all behave differently. Refer to the breakdown above to see which q2base weapons have been converted in Hush.


### Enemy Behavior:
Nope.

### Monster Aggression and the Radio/Flashlight
The BFG10k is your flashlight, it has infinite ammo, but alerts enemies to your position. It lights up an area around you. The radio
can be enabled by typing 'radio' into the console. It alerts enemies to your position so that you may draw them out.