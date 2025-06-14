# Dantooine - Before leaving

[< Previous Page](./07_Dantooine.md) |
[Back to the Index](../index.md) |
[Next Page >](./09_Dantooine.md)



- Ebon
  - Disciple with Kreia cutscene
  - **Bao becomes a Jedi**
    - Maybe it's because I stopped wearing that boring Republic uniform.
    - What about me, for giving the order?
    - **If Ulic Qel-Droma could be forgiven for waging war against the Republic, you can be forgiven for saving it.**
    - You did it to save us, to protect us from death.
    - You have dwelled in the past for too long. You cannot undo history, but you can change the future.
    - If you will let me teach you, the Force can become your shield. I believe you could learn to become a Jedi.
    - Then we have no time to waste.
    - `bug, head of Vrook instead of PC -> reload the game`
  - HK
    - [Repair] Install the droid's processor.
  - HK `But until you do, you answer to me.`
    - Any idea what happened to you?
    - Are you okay?
    - Why were you in our storage hold?
    - You look a lot like a series of droids that have attacked me. // -> later -> no necessary
    - You're an assassin droid?
    - What, "meatbag?"
    - Well, get used to it.
    - **I'm not sure I like the idea of having an assassin droid on board.**
    - Are you ready to serve me, droid?
    - +1000 XP
  - Kreia `leveled up after the battle of Khoonda`
    - I want you to teach me more about the Force.
      - I wish to ask about the lesson related to my skills.
      - [Treat Injury] I have devoted myself to healing others.
      - [You have gained a bonus to your weakest and strongest skills, and you have also recovered some of your connection to the Force.] `a_addforcepoints(6);a_global_set("000_Kreia_Skill", 2)`
      - +1000 XP
  - T3-M4 `Computer >= 21`
    - [Computer] I'd like to upgrade your core again.
    - [Computer] This might take a while, so you might want to lock your systems down. `!c_sc_com_lt(21)`
    - All done. How do you feel? `+1 Wisdom +1 Intelligence`
    - [Due to your computer skills, T3 has gained an additional +1 Intelligence and +1 Wisdom.]
    - I... don't know. While I was working on you, I felt strange, detached.
    - +750 XP
  - HK
    - Vulnerabilities?
    - **Mercy and charity are not weaknesses.** `a_influence_dec(5, 1);a_givelight(1)`
      - // **If you decide to attack me, I will crush you into scrap without a second thought.** `a_givedark(1);a_influence_inc(5, 1)`
    - Why are you studying me for vulnerabilities?
    - What, to protect me?
    - You don't have to call me master.
    - There is no "illusion" of control. You answer to me.
    - What do you mean, "the end?"
    - I had some questions.
      - Interrogation?
      - It's not an interrogation, I just want to ask you some questions.
      - Enough with the interrogation already. When I ask you questions, I mean I will ask questions without torturing you.
    - You look a lot like a series of droids that have attacked me.
      - Well, there's at least four other now defunct versions of you in the galaxy.
      - Actually, there's a series of HK-50 units sharing your model and function that we have encountered on multiple occasions.
      - Are you all right?
      - I wanted to talk about the other HK units.
        - Do you know where these clones are being created?
          - But how did this happen?
          - What was that? It sounded like a malfunction.
          - Are you sure you don't know where they are striking from?
          - And how would this information come out if it was locked in your memory core?
          - I need to know more about these clones of yours.
        - Why do you need me?
          - What are you talking about?
          - That doesn't explain why you need me.
          - I need to know more about these clones of yours.
        - Do you know why they are hunting me? `Atris leaked the info of you being a Jedi`
          - What do you mean?
          - Why would someone do that?
          - Who?
          - I need to know more about these clones of yours.
        - Why are they masquerading as protocol droids?
          - [Computer] So a good portion of your programming was adapted from protocol subroutines? `c_sc_com_gt(9)`
          - What do you mean?
          - [Awareness] Do any of these "incidents" have any wider repercussions? `c_sc_awa_gt(18)+c_ac_int_lt(17)` -> same line as intelligence
          - **Why did you say that just now?**
          - The echo - why did you say that? `Revan has discussed of "echo" before`
          - What repercussions did Praven Prime have?
          - And that's a good thing?
          - But why are the HKs masquerading as protocol droids?
          - **So? That's how droids should be treated.** `a_influence_dec(8, 1)` BUT ALSO T3...
            - //**Those are typical droid duties, but it doesn't mean they should be treated as furniture.** `a_influence_inc(8, 1) if T3 is around -> could also decrease with the other answer`
          - Actually, I'd like to know.
          - Why did the Sith go to war with the Republic?
          - **I need to know more about these clones of yours.**
        - Why did they start revealing themselves now?
          - I need to know more about these clones of yours.
        - You sound pretty disgusted by these duplicates.
          - I get it, already.
          - They really don't seem that different from you, actually.
          - From the voice? But you all sound exactly the same.
          - Okay, so that explains your anger.
          - I need to know more about these clones of yours.
      - Do you know anything about the Sith hunting us?
        - Any idea where they might be striking from?
        - You can say that again.
        - **I picked up a sonic imprint sensor on Peragus - it doubles as a translator.** `HERE IS WHY!`
        - Why?
        - Here you go.
        - I'm not sure I'm going to like what you're about to tell me.
        - Can you use it to track them?
        - What should we do with it?
        - Then we should destroy it.
        - I'm not for standing around here, waiting for them to hit us again.
        - So we just wait?
        - I had some other questions.
      - For a sophisticated assassin droid, you don't seem as advanced as you should be.
        - I had some other questions.
      - How did you get scattered all over the galaxy?
        - It was something of a pain, yes.
      - +1000 XP
    - Visas
      - I wanted to teach you some of the forms I have learned. `Vrook - Shen...`
      - I only taught you to make you stronger, not to serve me.
    - Bao
      - 3 things to learn
  - Bao
    - I wanted to teach you some of the techniques I've learned in my travels. `a_bao_teach(176)`
  

LATERRR

- HK
  - And how is that?
  - I am not proud of what I did during the Wars - and I do not wish to discuss it. `a_influence_dec(5, 1);a_givelight(1)`
  - What do you mean?
  - Are you trying to provoke me?
  - Why did you ask me about the Mandalorian Wars?
  - What do you mean?
  - **That's a very human perspective.**
  - How is that?
  - Don't attempt to justify my actions - or yours. `a_lightsml(1);a_global_set("000_HK47_Good_Retort", 1)`
  - 
- Reask `!c_pc_level(20)`!!
  - I want you to teach me more about the Force.
    - Before, when I heard the thoughts of my companions, I heard something, like an echo. `!c_pc_level(20)`

[< Previous Page](./07_Dantooine.md) |
[Back to the Index](../index.md) |
[Next Page >](./09_Dantooine.md)