# Telos - Escaping citadel station

[< Previous Page](./11_Telos.md) |
[Back to the Index](../index.md) |
[Next Page >](./13_Telos.md)

Excavation site
- Kill droid -> level 12
- Careful to mines -> stationary + solo mode at end of combat
- Merc
  - Mercenaries? How about I pay you 500 credits and you stay out of my way?
  - Who are you?
  - But why? What's down here?
- Kreia lvl 11
- Kill near the entrance first
- Remove mines
- Bao access the console
  - What is it?
  - How are we going to get to the polar region?
  - So we don't know that the shuttle will still be there, or working?
  - What are we waiting for, then?
  - Let's go.

SAVE

Facility
- Gas -> will be disabled later
- Bao-Dur can break repulsor shields
- Solo mode -> try stealth but hard
- Kill the turrets
- MOD REQUIRED TO OPEN THE FIELD DOOR 
- Next room 3 droids
- Coridor on the left -> back pack -> administrative ID Card
  - Only useful to disable the turrets
- Last coridor before ship -> 6 droids + lab and workbench
- Open the last door with Bao
  - Why is that?
- Send solo Bao to deactivate the gas (room on the left)
  - Turn off the security gas vents. `a_destroy_traps()`
- Other room - bay control -> inactive -> reactor off
- Twilek -> alien voices bug -> dlg edit not working? EXCLUDED `# Length of 'a_special_influence' (19 characters) exceeds the maximum allowed length (16)` -> `a_special_influence` where??
  - Who are you?
  - Find your own way out. -> will stay...
  - **Follow me out.** -> CAREFUL -3 infl on Kreia
    - Go toward the entrance with him following
    - He leaves `a_givelight(2)`
    - ALT -> REMOVE KREIA FROM THE GROUP
    - Kreia is angry! `a_global_set("000_R_Good_Kreia", 1)`
      - What do you mean?
      - **You're overreacting - it was a small kindness only.**
      - Is it wrong to help others in need?
      - If it meant your life, there is nothing I would not do... for you, or any of my allies. `a_influence_inc(1, 1)` BAO
      - Perhaps you are right. I will consider this. `a_influence_dec(6, 3)`
    - Otherwise Bao +4 infl!
      - It was a minor thing, nothing more. `a_influence_inc(1, 1)` + `a_influence_inc(1, 3)
    - Back
- 1 droid in the coridor
- 2 droid next room
- unlock
- 3 droids
- Can't unlock the door with other droids -> will open later
- HK-50
  - Repair it -> follow -> explose
- Door -> HK factory! Open with KSE? 
- Before the reactor -> deactivated droids
- Start the reactor
- Oooops
- Droid on the side stays OFF
- Kill turrets -> level 13
- Kill 5 droids
- Loot room on the left with security -> datapad
- Kill big droid near the ship
- Loot
- Unlock the hangar door
- Now go improve things
- Unequip Bao-Dur for later
- Let's have a chat
  - What are you talking about?
    - I was inspired by your arm.
    - Now whose claws are out? (TSLRCM?)
    - **Don't know what you're talking about.**
  - What's your opinion about the Telos situation?
  - How'd you lose your arm, anyway?
    - **I was being serious.**
  - Never mind.
- Kreia
  - I want you to teach me more about the Force.
    - This bond we share. I would know more about it.
    - What about when we fight on our journey?
    - Does this bond have any advantages?
    - I want you to teach me more about the Force.
  - I want to build a lightsaber.
    - Because I feel naked without it. `a_givelight(1)` `a_global_set("000_Kreia_Lightsaber", 1)`
    - But how do I make one?
    - I want you to teach me more about the Force.
  - Can you teach me any lightsaber forms?
    - Can you tell me of the Shii-Cho style?
    - Tell me of Soresu. -> learned with level up
    - I want you to teach me more about the Force.
  - I wished to know more about the Force forms.
    - The one that allows me to focus the Force.
    - I had other questions.
  - **Do you know anything about the Sith who pursue us?** `!c_influence_bet(6, 30, 70)`
    - The one who bathes in pain - Sion.
    - Who is the betrayer? -> `speaks of herself` "She", could be Atris tho
    - And the one consumed by hunger?
  - Never mind. I'll be going now.
- Replace Kreia with Atton
- Level him up
- Talk with him -> DS/Male later -> `c_ismale()&&c_global_gt("000_Women_Trouble")`
  - **What do you mean?**
  - I feel as if I'm more in touch with the Force than I ever have been. -> `the other have noticed it too!` -> Bao previously
  - Nevermind
- Bao
  - **Really, you don't have to call me "General."**
  - I was just wondering what you've been doing since the war ended. `a_local_set(34)`
  - **During my exile, I did the same thing.**
  - Only too well.
  - **I think taking on Czerka single-handedly might be a little out of your league.**
  - Never mind.
- Reask
  - **Oh, now you want to talk about it?**
  - **Obviously it is.**
  - What is it?
  - **The Jedi served no one with inaction.**
  - **So you wanted revenge?**
  - **I detached myself from the frenzy of battle. It was impersonal.**
  - Never mind.
- Get ready for the shuttle

- **Awareness >= 15 && Persuade >= 4**

- SAVE

- HK-50 looking for you
- Turning on the reactor will make them come everywhere



[< Previous Page](./11_Telos.md) |
[Back to the Index](../index.md) |
[Next Page >](./13_Telos.md)
