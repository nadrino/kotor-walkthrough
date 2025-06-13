# Dantooine - Sublevel of the enclave

[< Previous Page](./02_Dantooine.md) |
[Back to the Index](../index.md) |
[Next Page >](./04_Dantooine.md)


- Kaevee -> the thef! (lips not working)
  - Are you the thief that Suulru is complaining about?
  - What are you doing down here?
  - Who are you?
  - [Awareness] I sense you have a connection to the Force.
  - Why be a Jedi? They're a lost cause.
  - You can forge your own path. Free of rules.
  - Where is your master?
  - Someone named Vrook came here not too long ago.
  - About stealing...
  - I'm a Jedi and could use any artifacts you've found.
  - What did it say?
  - Was it a Sith holocron? Holocron can be dangerous.
  - Listen to your master's lessons. Not the holocron.
  - Where is the holocron now?
  - What are you going to do now?
  - May the Force be with you.
- All the parts for a light saber! Wait for workbench + crystals cave
- Jorran
  - Could you open the door?
  - Are you Jorran?
  - There are still some laigreks around.
- Kill the closest laigrek
- Jorran
  - The laigreks in this area are dead.
    - Before you go - what were you doing down here?
    - Why were you down here if it's so dangerous?
      - Almost nobody...? Who's the almost?
      - How did they die?
      - How can dead people cause problems?
      - Daraala had me looking for their bodies. To lay them to rest.
      - Her deceit won't gain her anything.
      - I want to talk about something else.
    - Did you find anything down here?
      - I know you found something. Taepalae told me.
      - Any chance you could give me what you found as a reward?
      - Could I buy them off of you?
      - Can I see what it is first?
      - I'm afraid I don't have that kind of money. -> 1000c later instead of 1300c
- Next rooms start with open doors -> dead salvager
- Get mine unlock doors then SAVE -> Guerevik spawn
- Droid room -> repair all with T3 -> kill the laigrek! -> T3 warns you! `Modules/610dan/prot_drd.dlg`
  - Reactivate the droid. (1 repair part)
  - [Repair] Diagnose speech system
  - ... `Modules/610dan/610t3greet.dlg`
  - I don't care about this droid's design flaw. I'm sure we can use it to our advantage.
  - I didn't realize the power core was unstable. Good thing you noticed that. Thanks T3. `a_influence_inc(8, 0)` -> BUG should be +1 not 0 within `Modules/610dan/610t3greet.dlg`
  - Engage droid in "Meet and Greet" mode. (<CUSTOM45> repair part(s))
- Leave some space between droids -> will explode in contact with enemy
- 280 XP per droid repaired + 200 XP is they explode
- Loot on the right
- Computer solo mode
  - Overload terminal (<CUSTOM35> spike(s)).

- Historian
  - Thanks for the polite bow. You must be a gentleman.
  - What are you doing here?
    - [Awareness] That's not the only reason. `c_sc_awa_gt(11)`
    - Left?
    - What others?
    - You mentioned holocrons? `Atris took them...`
    - Why is that?
  - Do you know what happened to the Jedi?
    - Why do you think people hate the Jedi?
    - But Jedi have protected the galaxy for centuries - they seek peace, often through sacrifice.
    - Do you hate the Jedi?
    - What do you mean?
    - I was one of those Jedi. I must accept part of that responsibility.
    - Revan and Malak would have received the same training as I did.
    - Go on.
    - **Do you know who trained Revan?** `Kae -> Kreia!`
    - I want to talk about something else.
  - Why do you work for the Republic?
    - Why Telos and Onderon?
    - And Onderon?
    - **Why is Dantooine important?**
      - alt: Why are the Jedi Order important?
  - Tell me about the Republic.
    - What happened?
    - What do you mean?
  - You look familiar to me. `they met before..!`
  - I'll be going now.
  - The Sith are awake in the galaxy, and I'm going to need their help to stop them.
  - Trust me, the Sith are out there. They've been hounding me since Peragus.
  - We would welcome your company. `a_influence_inc(11) only if Atton in the group` 
- Keep T3 and him
- Loot mercenaries -> ordered to find Vrook
- Will->
  - Don't change the will
- Before leaving
  - I don't suppose you'd like to negotiate a peaceful resolution to this situation?

Back to the camp
- Jorran -- not very interesting already everything you need -> LS part with theif -> not much sense
  - How much do you want for the Jedi artifacts? -> now it's only 1000c!
  - Can I see them?
  - I'm afraid I don't have that kind of money. -> not buying. Just a crystal that is interesting
- Darala
  - I'd like to talk to you about the dead salvagers.
  - I found their bodies.
  - Here you go. +1000c
- back to Khounda
- Suulru `disciple banter`
  - I found your thrief.
  - Your thief wasn't Jorran or a salvager
  - The salvagers have been hit by this thief, too.
  - **A former padawan was stealing to survive.**
  - She's just a young woman going through tough times.
  - Your world wasn't the only one damaged by Darth Malak.
  - The Jedi were responsible for saving us.
  - **These are the Jedi's darkest days. Thousands of years of service and peace shouldn't be so casually cast aside and spurned.**
- Zherron
  - I gave Dopak your message.
- Before entering the Ebon
- Disciple
    - Well, I hope our enemies think so.
      - I thank you for your kind words, but they are not necessary. `a_givelight(1)`
    - What do you know about Force bonding?
      - I have a connection with another that could be lethal to us both.
      - I have a bond with another that transmits pain across distances - if she suffers, I suffer. If she dies, there's a chance I'll die, too.
      - What?
      - Where would the holocrons be?
      - What do you remember about the bonds?
      - Is such a bond ever lethal?
      - You said feel each other across distances - what about each other's thoughts?
      - I had other questions.
    - **Nothing, never mind.**
      - And why do you want to discuss it?
      - I left to protect the innocents on the Outer Rim. `a_givelight(1)`
      - That was my belief, but recent discoveries seem to indicate there may have been other causes.
      - T3-M4 has a copy of it.
      - I trust you - go ahead. `a_influence_inc(11, 1)`
    - INTERESTING: if T3 in the group, he should ask directly


[< Previous Page](./02_Dantooine.md) |
[Back to the Index](../index.md) |
[Next Page >](./04_Dantooine.md)