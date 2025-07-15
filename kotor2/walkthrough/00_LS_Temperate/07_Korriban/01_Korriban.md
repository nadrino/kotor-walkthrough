# Nar Shaddaa - Ambush

[< Previous Page](../06_Onderon/12_Onderon.md) |
[Back to the Index](../index.md) |
[Next Page >](03_Korriban.md)


KOR
- Additional lines with mod
- ...
  - What happened here?
  - Do you think there are any living Sith here?
  - Can you sense any Sith here?
  - Let's head out, then.
  - Why won't you come with me?
  - Korriban doesn't look that bad. I'm not afraid.
  - Very well. Stay here and keep the engines primed in case we need to leave quickly.
- Go see Kreia first -> LS training
  - Kreia (need 3 lightsabers) `TSLRCM`
    - I wish to learn about lightsaber combat. `c_area("003EBO")||c_global_eq("000_Before_Visas_Trn")` + `c_visasfightav()`
    - **I don't want to fight her.**
    - Why the single hand?
    - Are you ready, Visas?
    - Very well. Let us begin.
  - ...
    - _[Success] You have defeated her - now do it with two weapons, one in each hand. Again, no items, no Force powers._
  - ...
    - _[Success] Excellent. Now - divest yourself of your weapons. You - blinded one - you will keep yours._
  - ...
    - _It is enough. There is nothing more for me to teach you. You know as much of battle as I._
    - Very well.
  - +1000 XP + Finesse
  - Workbench -> short LS for left hand
    - Improvements against DS
  - ...
  - Kreia
    - Yes, and I need some answers.
      - [Awareness] I wanted to ask you about the duels with Visas. `c_sc_awa_gt(9)&&c_global_eq("000_Before_Visas_Trn", 1)`
      - You're aren't just training me. You're testing her.
      - Have you found any weaknesses in the Miraluka?
        - // [Awareness] Wait... is that why you tolerate the Handmaiden's presence? Because she is a doorway to Atris? `c_sc_awa_gt(10)&&c_npc_avail(4)`
        - // no handmaiden here
      - She may betray us.
      - You want to use her? `a_global_set("000_Before_Visas_Trn", 2)`
      - Then we shall keep her on board, as you suggest. `a_influence_inc(6, 1)`
      - Never mind. I'll be going now.
- Visas + Mandalore
  - Visas make sense
  - Mandalore, since you know it was Canderous and he's (might) known the place with Revan
- Ask Mand about this planet
- right of the ship Naga Sadow (successor of Marka Ragnos)
  - Tell me more.
- left
  - _This was the tomb of Tulak Hord, known as the greatest lightsaber duelist of the Sith Lords._
    - Tell me more.
    - Are you saying modern Jedi are poorly skilled with the lightsaber?
    - What made him so good?
- Corpse
- Loot them anyway
  - What are these guardians?
- Right - Marka Ragnos
  - It sounds like civil wars are common among the Sith.
  - So what happened between Sadow and Kressh?
- Left
  - _This way leads to the Tomb of Ajunta Pall, a fierce Sith Lord. According to legend, the blade proved more fearsome than the Master, leading to his demise._
    - [Awareness] You sound like you disapprove. ` c_sc_awa_gt(11)`
    - No one is beneath redemption, Kreia. No one. `a_lightsml();a_influence_inc(6)`
    - What became of the blade?
- Sith findins
  - Tell me more.
- Cave -> kill
- Kill all the mobs till the academy
- Back to the cave


[< Previous Page](../06_Onderon/12_Onderon.md) |
[Back to the Index](../index.md) |
[Next Page >](03_Korriban.md)

