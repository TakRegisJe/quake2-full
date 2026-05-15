
Witcher Quake Mod
=================

A Quake 2 game modification that replaces the standard arsenal with Witcher-themed
melee weapons, signs, and movement abilities.

Launch Parameters
-----------------
  +set game WitcherQuake +set cheats 1


================================================================
SWORD WEAPONS
================================================================

All melee weapons use a short-range box trace to detect hits.
Monsters retain their original ranged attacks.

  Dagger
    Replaces: Machinegun / all bullet weapons
    A fast, lightweight strike. Low damage but quick to swing.

  Silver Sword
    Replaces: Shotgun / Super Shotgun
    A wider arc swing capable of hitting multiple targets in a cone.

  Steel Sword
    Replaces: Blaster / Hyperblaster
    A balanced mid-weight sword strike. Reliable damage at close range.

  Broadsword
    Replaces: Railgun
    A heavy two-handed sword. Longer reach and higher damage per swing.

  Poleaxe
    Replaces: BFG
    A sweeping area strike centered on the player.
    Deals 100 damage to all enemies within 100 units.


================================================================
WITCHER SIGNS
================================================================

Signs target the enemy directly in your crosshair (up to 1024 units).
Each sign has a 5-second cooldown shown on the HUD.

  Quen  [Key: Q]
    Shield sign. Instantly restores your armor.
    If you have no armor, equips Jacket Armor.

  Axii  [Key: R]
    Charm sign. Enchants a targeted enemy, turning it against nearby foes.
    If no other enemies are in range, the charmed enemy stands idle.

  Igni  [Key: T]
    Fire sign. Sets a targeted enemy ablaze.
    The enemy takes burn damage every server tick for 5 seconds.

  Yrden  [Key: Y]
    Trap sign. Freezes a targeted enemy in place for 5 seconds.
    Velocity is cleared and AI is paused until the effect expires.

  Aard  [Key: U]
    Force sign. Blasts a targeted enemy with a telekinetic shockwave.
    Knocks the enemy back based on its mass. Lighter enemies travel farther.


================================================================
MOVEMENT ABILITIES
================================================================

Dashes grant a burst of directional speed. Forward and side dashes
also grant brief invincibility frames. All dashes share one cooldown.

  Forward Dash  [Key: /]     Cooldown: 5 seconds
    Burst forward at high speed.

  Left Dash     [Key: ,]     Cooldown: 5 seconds
    Sidestep burst to the left.

  Right Dash    [Key: .]     Cooldown: 5 seconds
    Sidestep burst to the right.

  Long Dash     [Key: E]     Cooldown: 7 seconds
    Extended forward dash at double the normal dash speed.

  Speed Boost   [Key: I]     Duration: 5 seconds
    Increases horizontal movement speed by 50% for a short time.

  Jump Boost    [Key: O]     Duration: 10 seconds
    Amplifies jump height by 50% for a short time.


================================================================
CONTROLS SUMMARY
================================================================

  Signs
    Q         Quen   (restore armor)
    R         Axii   (charm enemy)
    T         Igni   (burn enemy)
    Y         Yrden  (freeze enemy)
    U         Aard   (knockback)

  Movement
    /         Forward Dash
    ,         Left Dash
    .         Right Dash
    E         Long Dash
    I         Speed Boost
    O         Jump Boost

  HUD
    P         Toggle controls screen in-game


================================================================
HUD
================================================================

Cooldown timers for all signs and the dash are displayed in the
top-right corner of the screen during play.

Press P in-game to open the controls reference screen.

