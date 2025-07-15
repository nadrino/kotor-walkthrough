# Nar Shaddaa - Ambush

[< Previous Page](11_Onderon.md) |
[Back to the Index](../index.md) |
[Next Page >](../07_Korriban/01_Korriban.md)


- MAND
  - **That sounds altruistic. I didn't know you had it in you.**
- you can't use the shuttle again
- Equip back jal shey "for the jungle"
- Bralor
- Kelborn is taking his place
- Loot the remains of the siths
- you can go freely into mand bedroom
- Kex -> MAND -> get inventory
  - Kex here doesn't know why you'd let me roam free. He doesn't trust me.
  - Let me see...
- Before leaving the camp
- MAND `I want to have a word with you` -> Unifications of the clans
  - What is it?
    - How do you plan on doing that?
    - Is that a threat?
  - If you're leader of the Mandalorians, I would have thought you'd be tougher than you are.
  - Can you do anything to help out?
  - Do you know anything about this world?

Go to the Workbench
- T3 if needed
  - Refined Phobium Emitter (STUN)
  - Telgorn Jolt Cell M3 (Electrical, DEM>=27)
  - Pontite Lense (Emergy, AWA>=27)
- Make sure Visas LS is simple red


- HARD SAVE
- You can you the guide (our Mandalore is your guide!)



- EBON
  - cutscene: Disciple `I wish to show you something.`
    - What?
  - MAND `Nice ship you have here. Where did you get it?`
    - We requisitioned it from the clutches of a Sith warship.
    - What's your take on the Republic?
      - You seem awfully complimentary of Revan, considering he almost destroyed your people.
      - Perhaps the Jedi thought the Mandalorians a threat not worthy of their attention.
    - Can you tell me about the Mandalorians?
      - **Can you tell me of Mandalorian history?**
      - There's more to life than war and battle.
    - Are you certain the clans will follow you? `c_localn_eq(15, 1)&&!c_influence_bt(2, 41, 59)`
      - **I don't see any army with you yet.**
      - Why haven't the clans come together earlier?
      - **I don't want the Mandalorians to become that powerful again.**
  - G0T0
    - What was it like breaking away from the Republic? `if c_global_gt("000_Know_Goto", 0)`
      - So you started to enjoy crime?
      - Doesn't sound like you enjoyed working for the Republic.
      - I had other questions.
    - What capabilities do you possess?
  - Atton
    - Learn
  - T3
    - T3, did you know Mandalore? `[4]: 371 if z_t3mand_dlg("Mand")||c_global_eq("000_T3_Cand")`
    - Once?
    - What happened?
    - Of course I want to know.
    - He was left behind? By who?
    - His master?
    - And your Master. But why?
    - Why doesn't he recognize you?
    - Yeah, but not every droid is the same... well, maybe they are to a Mandalorian.
    - Can you tell me what happened to Canderous?
    - Yes, I want to see the holorecord. `!c_influence_bet(8, 21, 79) -> BUG Black screen?` `BUG DP_Canderous`
  - Bao
    - Learn Beast trick + Dominate mind
  - Same with Atton and Visas


[< Previous Page](11_Onderon.md) |
[Back to the Index](../index.md) |
[Next Page >](../07_Korriban/01_Korriban.md)

