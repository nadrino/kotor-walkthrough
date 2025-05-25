# Telos - Czerka excavation site

[< Previous Page](./13_Telos.md) |
[Back to the Index](../index.md) |
[Next Page >](../04_Dantooine/01_Dantooine.md)

- Party
  - What's with T3?
  - You did what while you were connected?
  - You downloaded Atris' archives?
  - He said there was a holo record of my trial in Atris' records.
  - I came because I chose to, not because you summoned me.
  - If you seek to punish me, then get on with it.
  - Those last few moments after my trial... I had no idea.
  - I know it could take a while, but keep analyzing her archives.
  - In a second - what else was in the archive?
  - What about artifacts? Lightsabers?
  - She was obsessed with records. Why wouldn't she have a list?
  - That was a rhetorical question, sorry.
  - All right then. Play the missing Jedi.
  - MOD
    - **What happened to the other member of the concil?**
    - **So they're dead. But five of the Jedi who were on the Council that exiled me are still alive.**
      - KREIA: And we are walking into it. This is too convenient **to be anything but a trap.**
    - Be that as it may, we need their help against the Sith.

{[Gameplay Programmer: If the player is male, the Handmaiden walks on board.]}
{[Warp to 003EBO]}

Lightsaber!
- Bao-Dur
  - Atris and the Jedi Council took it from me.
  - Do you think I can't build one?
  - With the Jedi enclaves all destroyed, I don't know where to get the parts.
  - **Since when did you become an expert on lightsabers?**
- Atton & T3 then Bao
  - Utility droids tend to have a habit towards developing personality quirks.
  - That sounds like a good idea to me.
  - [T3-M4 has received a permanent +2 bonus to his Constitution.]
- SAVE

- Start with discussing with Bao
  - What are you talking about?
    - So, why are you here?
    - I mean, why are you still here?
    - Even if you knew what was wrong with it, how would you know where to start?
    - It's all wires and switches to you, huh?
    - I told you, I'm not a Jedi.
  - Where did you pick up that remote, anyways?
    - What does it do, other than follow you around?
  - Do I have all the lightsaber parts I'll need? `-> emitting matrix and lens`
  - Do you have shields?
  - What are you doing?
- Talk to the droid
  - It's been a long time since the war. I'm surprised you're still functioning.
  - Never mind.
- HK-> repair
- T3
  - How's the Ebon Hawk?
  - Good job - glad to hear it. `a_givelight(1)&&a_influence_inc(8, 1)`
  - What about the astrogation system?
  - You locked it? Why did you do that?
  - Protect? Protect who? Under whose orders?
  - Why didn't they want anyone to know where the ship had been?
  - So the astrogation system was crippled to prevent learning where the Ebon Hawk had been?
  - But how did the Ebon Hawk come back from there if it was so dangerous? And why?
  - ... BASTILA!
  - Friend of yours?
  - I don't understand why you were concealing that from me.
  - I understand. I didn't think you kept messages like that.
  - **Who was the person the hologram was talking about?**
  - Another missing friend? `-> Revan!`
  - What happened to your old friend? Why aren't you with him?
  - Because he could not take anyone with him. Even the woman in the hologram.
  - ...and he left you. I'm sorry, T3.
  - But you did help - you found us, T3. If we can stop the Sith... then there is hope after all.
  - Is that message what you were trying to hide?
  - So this help you came in search of - you came in search of me.
  - That message doesn't tell me where the Ebon Hawk came from.
  - But why don't you have that information?
  - Deleted? By who?
  - You deleted it? Why?
  - This is impossible. You deleted it, you don't know why, and all you can show me is this old hologram as an "explanation?"
  - Don't be sorry - maybe you had a good reason, or were trying to protect someone.
  - Never mind. I'll be going now.
- Nothing else to do with T3 -> Repair >= 21 and Computer >= 21 still too low
- Kreia
  - Yes, and I need some answers.
    - Kreia, what are you - are you a Jedi, a Sith?
      - [Intelligence] Then what were you? `c_ac_int_gt(13)`
      - If the past is as important as you claim, then I would hear yours. `a_global_set("000_Kreia_Movie", 2)&&a_playkremov01()`
      - I need more than that, Kreia.
      - I had other questions.
      - +1000 XP
    - Did you know Atris at all?
      - What do you mean?
      - You walked her path?
      - **You trained Revan?**
      - Never mind. I'll be going now. +500 XP
- Atton
  - I had some questions for you.
    - Care to explain where you got your Echani training?
    - When we entered the Telos Academy, you dropped into an Echani combat stance.
    - I was just asking - no harm meant. I just thought it could be an asset. `a_givelight(1) + a_influence_inc(1)`
    - Never mind.



- LATER
  - I wish to learn about lightsaber combat.
    - Not yet -> need LS + proper sparring partner
  - Did you know Revan? `!c_influence_bet(6, 10, 90)`
    - [Influence: Fail]
  - What's wrong with your eyes? -> LATER -> Need Visas `c_npc_avail(9)`
    - There might be a way to heal your sight.
    - But how do you get around?
    - What?
    - All right. `a_influence_inc(6, 2)`
    - [Computer Use] Hey, T3 has a stuck motivator. `c_sc_com_gt(0)`
    - [Repair] Hey, I can hear a catch in it. It's not fully fixed. `c_sc_rep_gt(0)`
    - [Awareness] I heard her thoughts. `c_sc_awa_gt(10)`
    - Was I always able to do that?
    - [You have gained +1 Awareness and recovered some of your connection to the Force.] `a_addforcepoints(6)&&a_adjust_skill(3, 1)`

Bao becomes Jedi -> not yet!! Free level
- Reask -> `{Light Side}Having you here has an effect on me, General. I never noticed it years ago. I think my mind was too occupied then.`
  - Maybe it's because I stopped wearing that boring Republic uniform.
  - What about me, for giving the order?
  - **If Ulic Qel-Droma could be forgiven for waging war against the Republic, you can be forgiven for saving it.**
  - You did it to save us, to protect us from death.
  - You have dwelled in the past for too long. You cannot undo history, but you can change the future.

[< Previous Page](./13_Telos.md) |
[Back to the Index](../index.md) |
[Next Page >](../04_Dantooine/01_Dantooine.md)
