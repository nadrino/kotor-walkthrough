# Dantooine

[< Previous Page](../03_Telos/14_Telos.md) |
[Back to the Index](../index.md) |
[Next Page >](./02_Dantooine.md)

![823DFBB6-FE1B-48CC-94DA-DE76B71AED83.jpeg](img/823DFBB6-FE1B-48CC-94DA-DE76B71AED83.jpeg)

- Go out with Bao and T3! -> Kreia will intervine -> not much sense given the answer of Dillan
- Dillan
  - What are you talking about?
  - Hey, my ship is not banged up!
  - **I'm just visiting. I lived here once.**
    - // INTERESTING ALT WITH MIRA (not yet in the group)
    - {snorts}So you used to be a farmer? ...
  - Yes, but much has changed since I was last here. <- your answer
    - //I haven't been back since I left for the Mandalorian Wars. <- more coherent with reply
  - Where is Khoonda?
    - This is your center of government?
    - I'd be more impressed if there weren't so many holes.
  - Why do I need permission to enter the Enclave?
  - Who is Administrator Adare?
  - I'll be going now.
- Droid "Greetings and good day, traveler. On behalf of the Khoonda settlement I am programmed to welcome you to Dantooine."  + `BaoDur` baneter
  - That's very observant of you, T3! `a_influence_inc(8, 1)`
  - Droid, what happened to damage you?
  - Sith invasion?
  - **[Computer] Droid, run a self diagnostic and report.** `c_sc_com_gt(1)`
  - [Repair] Fix the droid's memory unit. `c_sc_rep_gt(5)`
  - No, you must be mistaken.
  - [Persuade] The droid is obviously malfunctioning. Do I look like a Jedi? `c_sc_per_gt(7)&&c_lightsaber_eq()`
  - Why do you hate the Jedi?
  - Can you be more specific?
- Reask the droid
  - Why did you call me a Jedi?
    - Tell me about the invasion.
    - What do you know of me specifically?
    - Is that all?
    - Tell me more.

![vlcsnap-2025-05-30-12h16m08s159.png](img/vlcsnap-2025-05-30-12h16m08s159.png)

  - What can you tell me about Dantooine?
    - **Salvage?**
    - So, you can just walk into the ruins and take anything you wish?
    - What do you know of the ruins?
    - Tell me about how the Enclave came to be ruined.
    - I want to talk about something else.
  - What are the local areas of interest?
    - Why is that?
    - Where is the Khoonda outpost?
  - Is there any work available here?
    - I want to talk about something else.
  - Why were you walking in a circle?
  - I'll be going now.
- Pato Ado
  - What are you doing on Dantooine?
  - **How did the planet lose its balance?**
  - What's so unusual about the kinrath's behavior?
  - Why are you anxious to leave Dantooine?
  - I'm not interested right now. Maybe later.
- Loot around
- Akkere
  - **Every trader says they're honest. Especially the dishonest ones.**
  - What do you sell?
  - Yes, T3. I'm sure he has upgrades you can use.
  - Why are you here?
  - Who is Zherron?
  - What can you tell me about Dantooine?
  - Have the mercenaries hurt anyone?
  - Why are the salvagers trouble?
  - I'll be going now. -> see inventory later
- Guard
  - try to open the door
- Dilan again
  - Tell me about the admin
  - Why are there so many mercenaries here?
  - Have the mercenaries caused any problems?
  - Who has disappeared?

Khoonda - SAVE

- Reception
  - Why does everyone think I'm a salvager?
  - What do you have in Khoonda?
    - Where can I find the weapon shop?
    - Why would I need to see Zherron?
    - Recent problems? Like what?
    - Could you go into more detail?
    - Where can I find Zherron?
    - What exactly is Khoonda?
    - It's not a very big building for a center of government.
    - I'd like to ask you about something else.
  - Where is the Administrator?
- Suulru `Possible banters: ['Mand', 'Handmaiden', 'Kreia', 'Disciple']`
  - Why not?
  - What exactly is your problem?
  - The salvagers stole your equipment?
  - Are you sure it's a salvager?
  - What did they steal?
  - Why doesn't the Administrator help?
  - Is there anything I can do to help?
  - **If you want my help, you'll have to cough up more than a couple of dusty old war trophies.**
  - I'll see what I can do.
- Turn right
- Mordrul
  - Gerevick?
    - Who is Gerevick?
    - I've had no problems the militia needs to worry about.
    - Isn't being hands-on a good thing?
    - Can't anyone do something about it?
    - What makes you suspicious?
    - Seems like Dantooine has had a lot of trouble.
    - I might cause some trouble of my own, actually.
    - I've got a few questions about the other people here in the settlement.
  - I've heard rumors there's a Jedi around here.
    - Do you know if the rumor is true?
    - If no one says anything on their behalf, the rumor can feed on itself.
    - [Persuade] If good men say nothing then the Dark Side triumphs. -> nothing more to say
    - I'd like to talk about something else.
  - I wondered if you knew anything about Suulru's problem.
- Got back to the Admin room
- Adum
  - **Selling arms, right?**
  - I would like to ask you some questions.
  - How long have you been here?
  - What do you know about the mercenaries?
  - Why are there so many kinrath and kath hounds around?
  - Nice banter - you try the same line on everyone?
- Zherron
  - I've had a spot of trouble, yes.
  - Just exploring and getting to know people.
    - What sort of work do you have? **CHECK THIS -> INFINITE XP BUG IF NOT ASKING**
    - Why is this place so overrun with kinrath?
    - How dangerous is it?
    - How much is the reward?
    - [Persuade] With so few settlers, lives are much more important than credits. -> always fail
    - What do you know about the cave?
    - I'll see what I can do.
  - What's Gerevick's connection to the militia?
  - Can I ask you some general questions?
    - How is the militia doing?
    - What do you know about the Administrator?
    - Could you tell me about Khoonda?
    - How do you feel about the mercenaries?
- Admin
  - It's a pleasure to meet you. I'm <FirstName>.
    - **Why do you want to know?**
    - I'd prefer if you keep that quiet, Jedi don't seem to be liked here. Or practically anywhere these days.
    - What do you mean by that?
    - [Persuade/Lie]: He sent for me. He said you'd fill me in on the situation when I arrived.
    - Go on.
    - I actually came here to search the Enclave ruins, anyway.
  - **What are the dangers of the sublevel?**
  - **What was Master Vrook doing for you?**
    - Could you tell me anything more?
  - Is there any work I can do here?
  - Do the people of Dantooine really hate the Jedi?
    - Can anything be done about it?
  - What can you tell me about the people of Dantooine?
    - I'd like to know about the settlers.
      - [Awareness] You don't seem convinced by that. `c_sc_awa_gt(5)`
    - What are salvagers doing on Dantooine?
      - And you coexist happily with them?
      - What are you going to do when the ruins are empty?
    - What about the mercenaries?
- Gerevik
  - My ship isn't battered. -> miso soup
- Will not talk to you
- Leave
- Loot behind building
- Kill just enough kinrath to level up Bao (2 in my case)
- Old man
  - What are you doing out here?
  - **Do you suspect foul play?**
  - Why do you really want those sensors?
  - I'll see what I can do.

![CCFA6D6E-5ABB-4CAC-8FC7-1770A2C205F1.jpeg](img/CCFA6D6E-5ABB-4CAC-8FC7-1770A2C205F1.jpeg)

- To the ship. Don't enter
- Remove party -> to play pazaak!
- Pato Ado
  - Ask for 750c play until he's broke (tested 4x!)
  - the armor
- Back to the ship SAVE


[< Previous Page](../03_Telos/14_Telos.md) |
[Back to the Index](../index.md) |
[Next Page >](./02_Dantooine.md)