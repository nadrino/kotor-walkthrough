# Dantooine - Building your lightsaber

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
  - Improve LS with what you have
  - Visas
     - I wanted to teach you some of the techniques I have learned in my travels.
       - Affect Minds
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
    - `CANCELED -> same above` I had questions about how Revan amassed such a huge force against the Republic. `!c_influence_bet(6, 35, 65)` 
    - Did you know Revan? `> +3 infl !`
      - Where did Revan come from?
      - What else do you know of Revan?
      - What caused Revan to fall, to turn on the Republic?
      - Then what made him turn to the Dark Side, become a Sith Lord?
      - **You trained him?** `!c_influence_bet(6, 10, 90)` `a_global_set("000_Kreia_Revan_XP", 1);a_influence_inc(6, 3)`
      - What was Revan like as a student?
      - What do you see when you look at me?
      - I had other questions.
    - Can you tell me about the <FullName> Crystal?
    - Never mind. I'll be going now.
  - +1500XP
```
 INFO:       >> strref=None, isActive=c_pc_spell(270)&&c_visas_spell(270), nextList=[[0]: 241 if c_pc_spell(270)+c_visas_spell(270), [1]: 254 if c_pc_spell(182)+c_visas_spell(182), [2]: 255 if c_pc_spell(6)+c_visas_spell(6), [3]: 256 if c_pc_spell(14)+c_visas_spell(14), [4]: 253]
----------------------------
 WARN:       >> strref=None, execScript=a_visas_teach(270), nextList=[[0]: 232]
 WARN:       >> strref=None, execScript=a_visas_teach(182), nextList=[[0]: 244]
 WARN:       >> strref=None, execScript=a_visas_teach(6), nextList=[[0]: 245]
 WARN:       >> strref=None, execScript=a_visas_teach(14), nextList=[[0]: 246]
```
- Leave the Ebon with T3 and Bao


[< Previous Page](./04_Dantooine.md) |
[Back to the Index](../index.md) |
[Next Page >](./06_Dantooine.md)