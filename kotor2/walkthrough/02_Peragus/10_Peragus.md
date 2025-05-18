# Peragus - Sith assault

[< Previous Page](../09_Peragus.md) |
[Back to the Index](../index.md) |
[Next Page >](../03_Telos/01_Telos.md)

- Ebon Hawk leave
    - Keep as much distance between them and us as you can.
    - Can we jump to hyperspace?
    - Just do your best to keep your distance - we'll get out of this yet.
    - **No - someone might still be alive in the facility.** (LSP)
- Ebon jumps hyperspace
- Atton & Kreia
    - The Harbinger was on its way to Telos?
    - How did you know I was on board the Harbinger?
    - How come I don't remember any of this?
    - That's an unusual set of coincidences.
    - How did we get to Peragus?
    - He says he repaired the ship and got us to Peragus.
    - So why are these Sith looking for me? -> KREIA LIES!
    - But I was exiled from the Jedi Order.
    - But... last of the Jedi? That can't be true.
    - What about the Jedi on Dantooine? And Coruscant?
    - **If any survivors still live, we need to warn them.** (LSP)
    - Then how do we stop the Sith?
    - So what do you think we should do?
    - What do you mean?
    - **This is self-defense, not war.** (LSP)
    - **If evil is not fought, then we sacrifice the galaxy.** (LSP)
    - **You're right, she may need help - can you handle things up here?** (LSP)
    - What makes you say that?
    - She didn't seem in pain to me.
    - That's a poor assumption to be making.
    - When did you get sensitive?
    - I'll go check on her, then.
- 1500 XP Level 9 -> push the awareness now
- Kreia
    - **Your hand - is there anything I can do?** (LSP)
        - // **I'm sorry for your loss.** (LSP) -> NO -> inf-- on Kreia
            - If we travel together, then we need to work together.
            - The pain I felt when you lost your hand - what if it had been more intense?
    - **If I felt the loss of your hand, what would have happened if you had died?**
    - More extreme? I felt like my hand was dipped in molten carbonite.
    - Quicker? Would it have killed me?
    - **What can we do? I don't want my actions to place you at risk.** (LSP)
    - I have never heard of a link like this before, in holocrons, or in the Jedi histories. -> doubt!
    - [You and Kreia possess the Force Chain special ability. When either of you uses a Force power on yourself, the other gains the benefit as well.]
    - So what do we do now?
      - Is there any place where we can retreat to?
      - **Enough for what?**
      - And if we find no trace of Jedi teachings on Telos to help us?
      - This is a lot to take in at once. I need time to reflect on this.
      - **The fool has a name. I'd like you to start using it.** (LSP)
- Atton (003EBO.mod\003atton.dlg)
    - **Cryptic as always.**
    - But to know the future, one must know yourself.
    - But to teach, one must be willing to learn.
    - I don't think Kreia is a Jedi.
    - "Good-looking?" Are you that desperate?
    - **Look, ease off the insults. She was wounded helping us escape, remember?** (LSP)
    - Getting empathy from you is like squeezing water from a stone.
    - Are we still on course for Telos?
    - **Can't we choose another destination?** my mod
        - Who voice-printed the astrogation system?
        - Why would someone lock the astrogation system?
        - Do you know anything about that assassin droid?
        - Since when do protocol droids collect bounties?
        - Let's focus on getting to Telos for the time being.
    - All right, I'll do that.
    - To what?
    - My lightsaber was... taken from me, by the Council.
        - **It was a single hilt.**
        - **Both the blade and crystal were unique.**
        - **It was a viridian blade, one the Jedi Order had never seen before.**
        - I think having it would just drive them to hunt me harder.
- T3-M4 -> IF UNREACHABLE DISCUSSION WAS PATCHED (c_chkastrogation(1))
  - **T3, what's wrong with the astrogation system?** -> Failed -> `inf > 75 or inf < 25`
    - I know it's damaged.
    - Can you try to work on it when you get the chance?
    - I know you can do the calculations, but we may get separated.
    - **No, I'm not planning to leave you behind, but it happens.** (`inf++`, `LSP`)
    - Forget it. I had some other questions.
  - You look like you've suffered a lot of damage over the years.
    - How much damage?
    - So you lost a lot of programs in your behavior core - in addition to the damage to your frame?
    - **Well, I'm sure you'll gain that skill back. I'm glad to have you along.** `inf++`
  - **[Computer] I might be able to upgrade your memory core.** `!c_influence_bet(8, 40, 60)`
    - [Computer] All right. Let me take a look. `!c_sc_com_lt(9)`
    - All done. How do you feel? `Intelligence++`
    - What do you mean, I faded out there for a second? You were shut down.
    - I had other questions for you.
  - **[Repair] You look like you're in need of some routine maintenance.** `!c_influence_bet(8, 40, 60)`
    - [Repair] Just sit still. This won't take long. `!c_sc_rep_lt(9)`
    - That should do it. You doing all right? `Constitution++`
    - Glazed look? What are you talking about?
    - I had other questions for you.
  - **[Computer] Mind if I try to upgrade your memory core again?** `!c_influence_bet(8, 30, 70)`
    - [Computer] All right. Let me take a look. `!c_sc_com_lt(15)`
    - That should up your processor speed. `Intelligence++`
    - Blank look? What, me? I was working on you this whole time.
    - I had other questions for you.
  - **[Repair] Ready for some more routine maintenance?** `!c_influence_bet(8, 30, 70)`
    - [Repair] I'll try and make this quick. `!c_sc_rep_lt(15)`
    - All done with the response package. Give it a spin.
    - [Due to your repair skills, T3's response systems have improved, giving him +1 Dexterity.]
    - No, I'm fine. I guess I just caught up in my work.

Next upgrade need `computer >= 21` or `repair >= 21`

- Open HK door
  - [Repair] Diagnose the droid.
  - [Repair] Take the vocabulator and insert it in the core. `execScript=a_destroy("hkpart04")`

- Kreia (starts by claiming you should keep an eye on Atton -> don't reply)
  - I had other questions for you.
  - Can you tell me what has happened since the Mandalorian Wars?
  - Tell me about the Mandalorian Wars.
    - **But only some Jedi Knights answered the call... like I did.**
    - And Revan and Malak refused to wait.
    - Until we destroyed them... at Malachor V. (Kreia's empathy for once!!)
    - Many Jedi died at Malachor V... and the conflict split the Jedi Order.
    - But some battles must be fought. It was not Revan's failing. (any answer is interesting, let's take this one)
    - Didn't the Jedi Order try to stop them?
    - How were Malak and the Sith defeated?
    - But what happened to Revan?
    - So Revan saved the Republic?
    - **Then we must do what we can until it has a chance to recover from the war.** (LSP)
    - **Can anything be done to help the Republic?** (LSP)
    - This threat is directed against me? -> KREIA LIES!
    - There were other questions I wished to ask you.
  - When we were on Peragus, I could feel the Force again.
    - It was like a whisper, at the edge of hearing. -> other lie of Kreia -> Cut from the force
    - I don't believe the Jedi would do such a thing.
    - It's not possible to cut one off from the Force. It's like deafening someone... or blinding them.
    - **I don't believe the Jedi would inflict such a punishment on someone. It seems... too cruel.** `a_givelight(1)`
    - I thought I had lost it by my actions, by forgetting my training and the teaching of the Jedi.
    - Can my connection to the Force be healed?
    - But the Force... I can feel it again, if only slightly. -> lie -> "Link" -> propose to be her padawan
    - But there are no more Jedi.
    - **I would welcome whatever aid you offer.** (`a_givelight(1)` + `a_influence_inc(6, 1)`)
    - I had other questions for you.
  - I need to know more about the Sith hunting us.
    - There was another Jedi Civil War?
    - Are they following Malak's path?
    - The Sith on Peragus knew some Force techniques, but they were extremely weak.
    - This is a lot to take in at once. I need time to reflect on this.
  - Will do...

You explored all the possibilities with Kreia!

- See T3
  - Do you know where that HK droid in the cargo bay came from? (!c_influence_bet(8,25,75)) -> FAILED
    - That didn't sound very convincing. Are you sure you don't know?
    - I had other questions for you.
  - I need a programming spike. `a_item_gen()`
    - Can you make any more? `x4`
    - I'll put this to good use. For now, there was something else I needed.

- SECRET CACHE?? -> should only be available after 
- Head to Telos


[< Previous Page](../09_Peragus.md) |
[Back to the Index](../index.md) |
[Next Page >](../03_Telos/01_Telos.md)
