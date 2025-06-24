# Nar Shaddaa - Reclaiming the Ebon

[< Previous Page](../04_NarShaddaa.md) |
[Back to the Index](../index.md) |
[Next Page >](./06_NarShaddaa.md)

- SAVE
- Cutscenes
- Ebon
  - I do not ask for your blood, I ask for your obedience.
  - I could kill you all in a heartbeat. Your lives are mine, whether you wish it or not.
  - Give up the slave trade - or else.
  - Then prepare to die.
- Kill
  - Get off my ship before I throw you out.
- +500 XP
- Atton and Kreia cutscene
- T3 `level 20? Need cutscene with Kreia?`
  - [Intelligence] How did you get here, T3? `c_t3_message_0(14)+c_area("003EBO")`
  - Were you on the Ebon Hawk with Kreia?
  - But where did the Ebon Hawk come from?
  - Yes, but where did the Ebon Hawk come from?
  - T3?
  - If you don't know, then just say so.
  - If you didn't know, then say so, but don't start seizing up on me.
  - [Computer] You're deliberately avoiding answering - why? `c_sc_com_gt(10)`
  - [Computer] Let me check your core. I'll be careful, I promise. `a_givelight(1);a_influence_inc(8, 1)` `c_sc_com_gt(10)`
  - I want to make sure you're all right. Just let me check, all right? `a_givelight(1);a_influence_inc(8, 1)` `!c_sc_com_lt(15)`
  - I'm finished. Are you all right?
  - Then play the message. `BUG: can't play the message`
  - ...
  - Friend of yours?
  - I don't understand why you were concealing that from me.
  - I understand. I didn't think you kept messages like that.
  - That person in the hologram a friend of yours?
  - So this help you came in search of - you came in search of me.
  - So you found me in my weakened state and placed me in danger. You could have gotten me killed.
  - **You needed someone strong enough to fight the danger that was coming. Someone who knew war - and battle, and could make the hard choices that had to be made.**
  - I'm honored, T3. I will do what I can to stop this threat. `a_influence_inc(8, 3);a_lightsml()`
  - Never mind.
- Kreia (level >= 20) end of Kreia back story!
  - Before, when I heard the thoughts of my companions, I heard something, like an echo. `!c_pc_level(20)`
  - **But that sound, that echo - it was more than beyond the ship, it was the people in it.**
  - Never mind. I'll be going now.
- Atton
  - Learn everything he can
- Leave the Ebon


- Cantina `Atton -> will play pazaak for you and Visas` / `T3 could have a line as well`
  - And if I am?
  - Why don't you just go in and see him?
  - Can I pass along a message for you?
  - That sounds like it might be worth some compensation.
- Pazaak den
  - Are you speaking to me?
- Kaalah-nah `306nar/kaalanah.dlg`
  - What could you possibly have to sell me?
  - How do I know it's worth it?
  - I'm here to see the Exchange.
  - What makes you say that?
  - The Exchange and I have business, and I'm looking to sign on.
  - We'll see about that.
- Bar `306nar/hitman.dlg BUG, alien vioces not replaced`
  - Why don't you leave the girl alone?
  - If you think you're tough, prove it.
- Bartender
  - Know anything interesting about the area?
  - **How do you mean?**
  - Pazaak den?
  - The Champ?
  - Swoop races? `-> this could happen before we dp the quests there`
  - Jekk'Jekk Tarr?
- Dancers `Visa Banter`
  - What's going on here?
  - Tell me about Vogga.
  - What's in it for me?
  - What would you need of me?
  - What about me?
  - I have some preparations to make first.
- Kaalah-nah -> LATER
  - What can you tell me about this area?
  - Then you must know the password to the pazaak den.
  - You will give it to me.
- Give password and enter
- Droid `306nar/drdplay.dlg`
  - What are you talking about?
  - Why do you waste your time then?
  - [Intelligence] Wait... you said come here and play pazaak. Why here?
  - Uh, maybe in a moment. Why would you want to come here specifically?
  - [Computer] ...
  - no play!
  - // NOO -> byg with quest? [Awareness] [Check the droid for oddities.] `c_sc_awa_gt(5)` `a_global_inc("300NAR_Exchange_Gap", 1);a_global_dec("300NAR_Exchange_Favor", 1)`
  - [Computer] [Hook the module up to your datapad.]
- Twilek -> Atton will play for you
- Duros
  - DSP if not playing
  - play 2 times (or 3)
- Champion spawns -> play with him! 500c
  - I have won a few matches, yes.
  - ...  -> play with him! 500c x3 + golden card
  - Who are you again?
  - So if you win every time. Why do you play?
  - 


[< Previous Page](../04_NarShaddaa.md) |
[Back to the Index](../index.md) |
[Next Page >](./06_NarShaddaa.md)
