# Cosmic Calibre Documentation branch

Welcome to the documentation branch.

# Useful Links

1. [Facebook Group] (https://www.facebook.com/groups/677028359083110/)
2. [Preliminary Layout Design] (https://docs.google.com/presentation/d/1W6UJrwR1rXjfXRLpvvl_XMvAT6-qZtcInswgClTDw40/edit#slide=id.ga4bba3422_0_39)

# Minutes 4 (April 15)

### Coding Platform/IDE
  - FINAL: Android Studio
  - LANGUAGE: Java

### Final Theme
  - Human defending aliens alone, with the help of super gun weapons

### Think of Working Theme
  - Is the main character a…
    - Invasion lord?
    - Earth guardian?
    - Secret agent invading some secret lab?
    - Escaping criminal?
    - Half human-alien?
  - Basta Intergalactic chuchu (don’t care )
    - Tanggal si “Escaping Criminal” and “Secret Agent Invading some Secret Lab”

### Mechanics
  - Landscape orientation game
  - Platform  
    - Triple Platforms
    - Bottom – has no pitfalls
    - The middle and upper platform has
    - Gravity does its work
  - Properties of the Character
    - Life system = Heart style
      - Initial heart count = 3
      - Every time he gets hit, decrease heart count by one
      - Every time he picks up heart, increase heart count by one
      - Cap of 5 hearts
    - Firing system
      - Dual wielding
        - One hand for the auto-firing weapon (eg. Pistol, Rifle)
        - One hand for the triggered weapon (eg. Shotgun, Sniper)
        - Both works simultaneously
        - Default: Pistol for auto-firing, non for triggered
        - Getting a power-up for a weapon (triggered or auto-firing) will replace current weapon
        - Auto-firing power-up will be time based; If time limit finishes, the auto-firing will revert to Pistol
        - Triggered weapon will be ammo-based; If ammo depletes completely, the triggered weapon will be disabled until another triggered power-up is taken
  - Power-Ups (General)
    - Frequency/Rate of Spawn
      - Possibly counter-based
        - E.g. After killing the 20th enemy, a power-up will appear
      - Possibly distance-based
        - E.g. Every 2 sets of platform
      - Possibly time-based
        - E.g. Every 5 seconds
    - Gun-based
      - Spread shot
        - Applied to the auto-firing weapons
        - Time-based power-up
        - 10 seconds
        - first instance: 3-way spread shot;
        - second instance: 5-way spreadshot; 
        - third instance: time extend;
      - Railgun
        - Applied to the triggered weapon
        - Ammo-based power-up
        - 5 counts
        - Pierces through enemies
        - first instance: 5 ammos;
        - second instance: reset to 5 ammos;
      - Shotgun
        - Applied to the triggered weapon
        - Ammo-based power-up
        - 15 counts
        - Close AOE High Damage Shot
        - first instance: 15 ammos;
        - second instance: reset to 15 ammos;
      - Gatling Gun
        - Applied to auto-firing weapon
        - Time-based power-up
        - 15 seconds
        - High fire-rate
        - Resets time every additional instance
      - Sniper Rifle
        - Applied to triggered weapon
        - Ammo-based power-up
        - 10 ammo
        - High-Damage auto-aim (nearest enemy)
        - Resets ammo to 10 every additional instance
    - Stat-based
      - Shield – save character from first harming encounter
        - Flame Boost – invincibility for a short time, twice the running speed, auto-killing all encountered enemy, ends with a burst to auto-kill all near enemy once the speed boost stops
      - Heart Pick-Up – adds one more heart (life)
        - if life is already maxed out, it becomes an instantly used clear-screen nuke (to make the player feel AWESOME :D )
  - Enemies 
    - Endless Runner Mode
      - Walker Type – the basic dude you see everywhere
      - Pop-up Type – will randomly pop from ground
      - Laner Type – changes lane/row of operation
      - Flying Type – flies, drops walkers, one-hit
    - Bonus Round Mode
      - Walker Type (duh)
      - Pop-ups (haha)
      - Kamikaze Enemy – charges towards you quickly
      - Pinata Enemy – spawn smaller enemies once killed
      - Rare Game Enemy – one kill = higher than one kill count
      - “Frenzy Witch” Enemy – doesn’t harm you, but flashes on the screen quickly and thus hard to kill; once killed, gives “2x kill count” buff for 5 second
      - Boss Enemy –  only appears in the ‘Boss Stages’ and only sends out a specific kind of enemy