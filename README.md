# Team Assignments

The following is a list of teams and the members of each. To find which teams you are included, simply use CTRL+F and search for your nickname within this document. Highlighted in bold are the team heads.

Project Head: **Jino Basilio**

Team | Members | Description
-----|---------|------------
Game Design | **Jino**, Rico, Andre, Ivan,  Aemiel, Chi, Kryzl, EJ, Dan | This team is in charge of brainstorming for game ideas, including the game mechanics and theme.
Game Logic | **Nina**, **Aemiel**, Rico, Ivan, Jino, EJ, Dan | This team is in charge of developing the inner framework of the game, including the classes and their methods.
GUI and Animation | **Ivan**, Andre, Nina, Aemiel, Chi, EJ | This team is in charge of coding the outer aesthetics, including the GUI layout and game animations.
Graphics | **Aemiel**, Chi | This team is in charge of creating key graphics/images that will may used for the GUI, promotions, etc.
Music | **Andre**, Rico | This team is in charge of composing the music and sound of the game, including the background music and the sound effects.
Documentation | **EJ**, Rico, Andre, Jino, Aemiel, Kryzl | This team is in charge of documenting the progress of the game development, taking notes of during the meetings, and logging version changes in a changelog.

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

### Deadline/Assignment
  - Game Logic – finish the framework in one month
  - GUI – finish the framework in one month, cooperate with Game Logic
  - Documentation – At least right after the basic frame work finishes
  - Graphics – generate ideas, make rough drafts or prototype graphics
  - Music – start generating ideas, think of good music (raises intensity and concentration) with a good looping capability
