# Dantooine - Lightsaber

[< Previous Page](./04_Dantooine.md) |
[Back to the Index](../index.md) |
[Next Page >](./06_Dantooine.md)


- BEFORE ENTERING -> Levelup Disciple!! -> lvl 15 -> will become a Jedi
  - Cutscene
    - Disciple getting bullied
  - **Disciple becomes a jedi** -> CAREFUL! NEED TO LEVEL UP BEFORE FOR A FREE LEVEL
    - What are you doing?
      - Can you teach me to meditate? `a_addforcepoints(10);a_influence_inc(11, 1)`
    - I had other questions.
      - **I could train you to feel the Force again.**
      - Do not bow to me - that will be your first lesson as a Jedi.
      - Then let us meditate - and open ourselves to the Force.
      - Imagine the initial teachings of the Jedi, your first steps within the Enclave.
      - Remember the wind among the plains of Dantooine, the feel of life around you.
      - Think of what you felt when our paths crossed again.
      - And at last... see the galaxy through the Force.
      - [The Disciple has taken his first steps on the path of a Jedi Consular. He will grow in ability as he travels with you and learns what you know of the Force.]
  - Bao lightsaber! `still need some infl for jedi`
    - What are you talking about?
      - So, why are you here?
      - We could let you off wherever we stop next.
      - Even if you knew what was wrong with it, how would you know where to start?
      - It's all wires and switches to you, huh?
      - **I told you, I'm not a Jedi.**
    - Do I have all the lightsaber parts I'll need?
      - One-handed lightsaber.
      - Violet (or whatever found in the cave)
  - Improve LS with what you have -> Don't equip yet, we need to talk to the old man without a ls
  - Kreia - complaining about the number of people gathered
    - As many as want to come with us and help us.
      - What makes you think they obey me?
      - Does the fact they obey me upset you?
      - **I've noticed their behavior is changing - Atton, especially.** `!c_influence_bet(6, 40, 60)`
      - **And what about you?**
      - They are my friends, not tools.
      - What do you mean? `!c_influence_bet(6, 35, 65)`
      - He was a powerful presence - there was little one did not believe when he spoke it with conviction.
      - I thought teachings of the Sith came from Korriban.
      - Do you have any ideas?
      - I had other questions.
    - Can you tell me about the <FullName> Crystal?
    - `CANCELED -> same above` I had questions about how Revan amassed such a huge force against the Republic. `!c_influence_bet(6, 35, 65)` 
    - Did you know Revan? `> +3 infl !`
      - Where did Revan come from?
      - What else do you know of Revan?
      - What caused Revan to fall, to turn on the Republic?
      - Then what made him turn to the Dark Side, become a Sith Lord?
      - **You trained him?** `!c_influence_bet(6, 10, 90)` `a_global_set("000_Kreia_Revan_XP", 1);a_influence_inc(6, 3)`
      - What was Revan like as a student?
      - What do you see when you look at me?
      - What do you know more of Revan?
    - Never mind. I'll be going now.
 - Visas
    - I wanted to teach you some of the techniques I have learned in my travels.
      - Affect Minds
```
 INFO:       >> strref=None, isActive=c_pc_spell(270)&&c_visas_spell(270), nextList=[[0]: 241 if c_pc_spell(270)+c_visas_spell(270), [1]: 254 if c_pc_spell(182)+c_visas_spell(182), [2]: 255 if c_pc_spell(6)+c_visas_spell(6), [3]: 256 if c_pc_spell(14)+c_visas_spell(14), [4]: 253]
----------------------------
 WARN:       >> strref=None, execScript=a_visas_teach(270), nextList=[[0]: 232]
 WARN:       >> strref=None, execScript=a_visas_teach(182), nextList=[[0]: 244]
 WARN:       >> strref=None, execScript=a_visas_teach(6), nextList=[[0]: 245]
 WARN:       >> strref=None, execScript=a_visas_teach(14), nextList=[[0]: 246]
```
- Leave the Ebon
- Kreia and Atton for `infl+`

- Back in Khoonda
- Adare
  - Who knows about the attack?
  - What can I do to help?
  - Can you give me anything to help?
  - I'll check out Khoonda's defenses then.
- Speak to Vrook
- Speak to Zehron
  - Cave... -> +2000c
  - How much time do I have?
  - Any idea...
  - What kind of things need fixing?
  - What's involved with finalizing the defenses?
  - I'm going to see what I can do.



- Akkere -- get the thorium charges!
  - Would you be interested in joining the Khoonda militia? `Bug, recrut quest never ends`
  - This isn't a permanent job. Very short term, but dangerous.
  - You can store your wares on my ship.
  - I'll take them.
- Close the door
- Recrut -> not yet. We need to find out about the droid screwdriver...
  - Dillan
    - Would you be interested in joining the Khoonda militia? `Bug, recrut quest never ends`
  - Recrute Jorran
    - Would you be interested in joining the Khoonda militia? `Bug, recrut quest never ends`
- Back to Khoonda
  - Suulru
    - Would you be interested in joining the Khoonda militia? `Bug, recrut quest never ends`
- Medical room
  - [Treat Injury] I'll treat your wounds. `c_sc_tre_gt(11)`
- Medical droid -> T3 or Bao
- Droids with Bao/T3 + get Akere key
- Reprogram droids NO!
- Reprogram turrets
- Leave
- Akkere `infl+ Bao`
  - I found this hydrospanner. It has your name on it.
  - Don't toy with me! I know you have been stripping these droids for parts and selling them.
  - Tell me.
  - **I believe you. Please take 500 credits to help you.**
- Bao comments
  - It was a minor thing, nothing more. `a_influence_inc(1, 1)` + `a_influence_inc(1, 3)`
- Mines -> don't remove mines -> prevent message from happening
  - Add 3 mines in front
  - Add 4 mines in the east
- Kill merc
- Ebon -> Bao Jedi


Assault
- Grenn
  - **There isn't anyone else that can rally the settlers?**
  - Could you tell me about the squads?
  - Main entrance.
  - The back - by the garage.
  - Inside by the administrator's door.
  - I'll take the front.
  - Do I have time to do anything else?
  - Have you talked with the men?
  - [Persuade] I think they could use some encouragement. Maybe I could speak to them.
  - [Persuade] Tell them this is their chance to make history. `c_sc_per_gt(15)`
    - Dantooine's short history has been a constant tale of rugged people surmounting difficult odds. Never have the odds been so great, or the future so uncertain...
    - ... But today is your chapter, your tale. Generations yet born will look upon the upcoming battle with pride and wonder...
    - ... I will not lie, the risks are great. The threat real, but I would stand beside any one of you proudly as we face our destiny on this field of battle...
    - ... This is our day, our valiant chance to free Dantooine. Who will fight beside me?

- // Kreia -> LATER!!
- Reask `-> could be done later`
    - I want you to teach me more about the Force.
      - Before, when you taught me to listen - I wish to continue that lesson.
        - :: That sound in the background - what is it? ::
        - :: I hear you. This... this is incredible. :: `a_addforcepoints(6);a_krepcup()`
        - What about T3?
        - But I did hear something from Bao-Dur.
        - Maybe it is because I know him better; I served with him.
        - **There was also something wrong with Atton's thoughts.**
        - Perhaps. Maybe I will go see him - and see how his pazaak game is coming.
  - Atton
    - Atton, why do you play pazaak in your head?
      - [Repair] There are no ticks in the power coupling - it's fixed. `c_sc_rep_gt(3)`
      - You're not making any sense.
      - I don't want to play pazaak.
      - This better not be using Nar Shaddaa rules.
      - If it's a friendly game, sure.
      - ...
      - I was trying to compute the totals to twenty.
      - **Atton, before, I felt your mind. With Kreia's help. I'm sorry.** `a_influence_inc(1);a_global_set("000_Atton_Pazaak", 90)`
      - What do you have to hide?
      - Is that something you can train me to do?
      - No - I want to learn to shield my mind.
      - Then I want to learn to play pazaak.
      - [Atton has taught you to play pazaak in your head as a way of resisting mental domination. You have gained a permanent +1 to your Willpower saves.]
- I want you to teach me more about the Force.
  - You taught me of sight - is there anything else you can teach me?
  - What do you mean?
  - [Repair]
  - [Treat Injury]
  - Very well. I shall take this lesson to heart. `a_influence_inc(6, 1)`
  - I'll think on this, and return when my weakest skill is stronger.
- Reask `!c_pc_level(20)`!!
  - I want you to teach me more about the Force.
    - Before, when I heard the thoughts of my companions, I heard something, like an echo. `!c_pc_level(20)`
    - 


- Ebon?
  - Bao
    - I wanted to teach you some of the techniques I've learned in my travels. `a_bao_teach(176)`
  - Kreia
    - Skill
    - Very well. I shall take this lesson to heart.
- Old man -> with Kreia and Atton?
  

LATERRR

- **Bao becomes a Jedi** >> LATER
  - Maybe it's because I stopped wearing that boring Republic uniform.
  - What about me, for giving the order?
  - **If Ulic Qel-Droma could be forgiven for waging war against the Republic, you can be forgiven for saving it.**
  - You did it to save us, to protect us from death.
  - You have dwelled in the past for too long. You cannot undo history, but you can change the future.
  - If you will let me teach you, the Force can become your shield. I believe you could learn to become a Jedi.
  - Then we have no time to waste.


[< Previous Page](./04_Dantooine.md) |
[Back to the Index](../index.md) |
[Next Page >](./06_Dantooine.md)