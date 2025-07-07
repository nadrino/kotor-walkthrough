# Nar Shaddaa - Ambush

[< Previous Page](07_Onderon.md) |
[Back to the Index](../index.md) |
[Next Page >](09_Onderon.md)


- Cantina
- Gormo
  - Why do you ask?
  - Have you tried to explain your situation to the soldiers?
  - There seem to be a lot of people here that need one.
  - I only have mine and I'm using it.
  - Slicer?
  - Do you know what is going on here?
  - I'll be going now.
- Gelesi
  - You seem tired.
  - What's so tough about it?
  - Tell me about Sullio.
  - What do you know about the murder?
  - You sound nervous.
  - [Persuade] That sounds like a good idea. You need to think of your family first. `fail`
  - [Persuade] You're right to worry. I know people want to get rid of the captains. `c_sc_per_gt(16)`
- // with minimum XP abuse before leaving DXUN -> level 26
- Nikko
  - Let's play some pazaak.
- 250c x 4
- Qimtiq
  - Tell me about the cantina.
    - You seem to be in a good mood.
    - You want the war to come?
    - But if a war happened then wouldn't you be shut down?
    - I'll be going now.
- Talk M-sadaar `What are you looking at, smooth-skin?`
  - Are you a swoop racer?
  - Look, I just want some information.
  - Just a few questions.
  - Why are racers paid so well?
  - There. Was that so painful?
- Bahima `will comment about your skin if DS`
  - What do you know about Iziz?
  - How has it changed recently?
  - I'll be going now.
- Talk to Vix
  - Uh, hi.
  - Yes, swoop.
  - Yes, swoops fast. Is there something I can help you with?
  - That's great, Vix. I'm going to go stand over here now. 
- Qimtiq
  - I want to race.
    - Could you go over the basics of racing?
    - What do I get if I win?
    - **What are the rounds?** `Revan!`
    - What's the competition like here?
    - How is Jonra controversial?
    - Let's go back to my other questions.
    - I'm ready to race.
    - Here's 100 credits.
  - ...
  - Can I talk with you about Captain Sullio's murder?
  - I'll be going now.

```
ALERT: INFLUENCE WITH: EntryList, strref=91751, speaker=Disciple, execScript=a_influence_inc(11, 2), nextList=[[0]: 30]
ALERT: INFLUENCE WITH: EntryList, strref=91752, speaker=Handmaiden, execScript=a_influence_inc(4, 2), nextList=[[0]: 30]
ALERT: INFLUENCE WITH: EntryList, strref=91750, speaker=BaoDur, execScript=a_influence_inc(1, 2), nextList=[[0]: 30]

CHEAT -> c_global_eq("000_Cheat", 1)
```
- Xaar `+ Banter with Mand`
  - You look familiar, too.
  - I remember Dagary Minor...
  - Not directly any more, but I try and lend a hand when I'm able.
  - **Why is it so important if one world secedes from the Republic?**
  - Why not?
  - What was your mission?
  - You might want to travel to Telos, as well. There is a Republic representative there.
  - Couldn't you get a visa?
  - Actually, I'd like to talk to you about Captain Sullio's murder.
  - An acquaintance of mine, Dhagon Ghent, is being held by the authorities. I'm trying to get him free.
  - How can you be so sure?
  - Why don't you tell the authorities?
  - I don't suppose anybody else saw you?
- Sakarie `Crystal only for DS` `Kreia banter`
  - A lightsaber crystal? What does it do?
  - Actually, I was wanting to talk to you about Captain Sullio's murder?
  - What were they questioning you about?
  - I want to talk about the starport visa, instead.
  - What do you need the open starport visa for?
  - [Force Persuade] I have an honest face. You will answer my question. What do you need the visa for? `c_domin_mind()`
  - How do I know you'll live up to your end of the bargain?
  - How do you know I'm a Jedi?
  - I'll be going now.
- Panar `could ask about Dagon, but same info provided by Kiph`
  - You're a swoop racer, aren't you?
  - // I'd like to talk to you about Captain Sullio's murder.
    - Do you know Dhagon Ghent?
    - Who is Bakkel?
    - Do you know any reason why Dhagon Ghent would kill Sullio?
    - I'll be going now.
- Kiph `alibi -> 1`
  - What do you know of the city?
    - What do you think of the General and the Queen?
  - What do you do?
    - Could you be a little more vague?
  - I want to talk to you about Captain Sullio's murder.
    - Soldiers have a habit of doing that. `a_local_set(50)`
    - Do you know Dhagon Ghent?
    - Do you know any reason why Dhagon Ghent would kill Sullio? `a_alibi_motive()`
    - I'll be going now.
- +250 XP
- Waitress
- Nikko `alibi -> 2`
  - Can I talk with you about Captain Sullio's murder?
  - Do you know Dhagon Ghent?
  - **Someone was saying that Sullio deeply humiliated Dhagon the night she was murdered. That's a very good motive.** `alibi check`
  - What happened on the night of the murder?
  - Where did you find the body?
  - I'll be going.
- + 500 XP
- 2nd round -> if persuade > 18 -?> you won't pay AND he will give you 500c more -> 1000c 
  - [Persuade] With the money I've made you, I'm not going to pay the fee. I want a cut of the profits. `c_sc_per_gt(18)`
- Jonra Far `after 1st race at least`
  - I'll take that drink. I'm <FullName>.
  - Fun.
  - Social activism via swoop racing, sounds far-fetched to me.
  - Struggle?
  - Free yourselves? I didn't know Onderon was a conquered planet.
  - Sounds like the Republic has been bad for Onderon.
  - What can I do?
- Bahima
  - Can I talk with you about Captain Sullio's murder?
    - An acquaintance of mine, Dhagon Ghent is being questioned by the military about this. I'd like to get him free.
    - Do you know Dhagon Ghent?
    - //Do you know any reason why Dhagon Ghent would kill Sullio?
    - //`Someone was saying that Sullio deeply humiliated Dhagon the night was murdered. That's a very good motive.` -> already done with Nikko
    - I'd like to ask about something else.
  - I have an extra starport visa, but it isn't open. Know anybody who can do something about it? `Won't appear if we chose "Would you know where I could find an extra starport visa?" first"`
  - Would you know where I could find an extra starport visa?
  - You've got several rough characters in here.
    - They seem little more than thugs.
    - Anything I can do to help?
  - I'll be going now.
- Kiph
  - A friend of a friend told me that you're the guy I should talk to about... adjusting... starport visas.
  - How do I know that the visa will work?
  - Here's 500 credits.
- Xaart
  - I managed to get an open starport visa.
  - Here you go.
- Outside


- Have a chat with Mand `no influence directly on him`
  - Go ahead.
    - They were the only Jedi who realized that the Republic would fall without the support of the Jedi.
    - **The Mandalorians were a menace that had to be stopped.**
    - Of course. The Mandalorians couldn't run the Republic.
  - Can you do anything to help out? `first`
  - What's your take on the Republic?
    - You seem awfully complimentary of Revan, considering he almost destroyed your people.
    - Perhaps the Jedi thought the Mandalorians a threat not worthy of their attention.
  - Can you tell me about the Mandalorians?
    - **Can you tell me of Mandalorian history?**
    - There's more to life than war and battle.
  - Are you certain the clans will follow you?
    - **I don't see any army with you yet.**
    - Why haven't the clans come together earlier?
    - **I don't want the Mandalorians to become that powerful again.**
  - How did you become Mandalore?
    - **So all of this is over a helmet?**
    - **How did you find the helmet?** `I was there with him when he defeated Darth Malak and traveled with him afterwards.`
  - Do you know anything about this world?
  - If you're leader of the Mandalorians, I would have thought you'd be tougher than you are.
  - I was wondering if you could give me some stimulants.
    - I'll take any advantage I can get.
- Murder scene
- droid!
- Back to the Cantina
  - Bahima
    - Can I talk with you about Captain Sullio's murder?
    - I found a broken serving droid by the murder scene.
    - What keeps happening to your serving droids?
    - Why didn't you mention this before? `-> to Nikko`
    - I'll be going.
  - Niko
    - Can I talk with you about Captain Sullio's murder?
    - I found a broken serving droid by the murder scene.
    - What happened to it?
    - Do you remember who scavenged the droid?
    - I'll be going.
  - Kiph
    - I want to talk to you about Captain Sullio's murder.
    - I found a broken serving droid by the murder scene.
    - Is it possible that the droid saw something? Something that we could recover?
    - No, it was missing.
    - I'll be going now.
  - Panar
    - I'd like to talk to you about Captain Sullio's murder.
    - I found a broken serving droid by the murder scene.
    - Any idea which scavenger got to his droid?
    - You know that? Where?
    - I'll be going now. `-> 1B-8D`
- 1B-8D
  - B-8D, I need to know if you have any parts from one of Bahima's serving droids.
  - I want to buy those parts.
  - Here's 25 credits.
- Back
  - // Nikko -> you have the head
  - Kiph -> head
  - Nikko
    - I want to show
- Captain
  - Dhagon Ghent couldn't have killed Captain Sullio.
  - Nikko can explain it.

```
missing line: "...And so S-0D3's transmission clearly shows that the murderer was firing from the marketplace. But Dhagon came running from his office. It couldn't have been him."
```
- ...
  - **They weren't really fighting. The regulars of the cantina can vouch for that.** `a_alibi_gen()`
  - **They were friends. Sometimes friends tease each other. They just took it to an extreme.** `a_alibi_gen()`
  - **That's true. Nikko saw him come from his office.** `a_alibi_gen()`
  - **He came from his office, but a recording of the murder shows the shot came from the opposite direction.** `a_alibi_gen()`
    - c_alibi_gen(0, 4) -> `{Nikko's thanks is an after thought}You handled that just right, off-worlder. Dhagon owes you a great deal. And you, too, Nikko.`
    - c_alibi_gen(0, 2) -> `You're quite a team. Together you got the major to back down. That's no small feat.`
    - "thanks for the leg work..." -> `Great job, Nikko. Without you, I'm pretty sure that the doctor would still be behind bars. And thanks for your leg work, off-worlder.`
  - [Awareness] The major seemed particularly unwilling to believe Dhagon was innocent. `c_sc_awa_gt(2)`
  - **What do you mean?**
- Daghon
  - Why were you locked up in the first place?
  - You have any idea who killed her?
  - You don't care?
  - Mandalore said you might be able to help me out. I need to get in touch with someone from the Palace.
  - **Who is trying to kill the Queen?**
  - I'm trying to get in touch with a Jedi Master who is inside the Palace.
  - **Who do you think it is?**
  - Can you get in touch with someone inside the Palace?
  - Who has them?
- -> he needs disk
- Cantina!
- Bakel
  - **Are you a beast-rider?**
  - You have something that belongs to Dhagon Ghent. I want to get it back.
  - I was hoping I might be able to buy any holodisks you get from his office.
- Open visas!
- Capitain -> move away -> 2500c by aida + 250 XP
- Last races
  - Jonra Far
    - Can you tell me about the swoop track?
    - What do you mean?
    - What do you think of the other racers?
  - 3rd round -> vs M-sadaar -> 2000c + 500c // LATER
  - 4th round -> vs Jonra Far -> 5000c +500c
    - M-sadaar -> don't want to talk anymore
    - Jonra Far
    - Vix
- Leave the Cantina
- Dhagon
  - I got the holodisks from Bakkel.
  - **I have something I have to do first.**
- Last peaceful time on Onderon!
- Talk to the people -> you are the swoop champion!
- Back to Anda
  - +2500c +550XP
- Riiken will talk to you
- News terminal
  - _Crime rates have been soaring in recent months. Even in the Merchant Quarter, the Western Square has seen a dramatic increase in violent crimes._
  - _In the Merchant Square today a full scale riot broke out. During a public speaker's address, vocal supporters of Queen Talia were provoked to violence._
  - // UNREACHABLE _In local news, a citizen in the Merchant Quarter was mistakenly arrested by Queen Talia's soldiers. The soldier's report claimed that the speaker was "attempting to incite a riot."_ 
- Terlin `Handmaiden, Disciple, Visas infl+`
  - I have found a visa for you. Here.


- Kavar `could gain infl with Mand if alone`
  - Master Kavar? I didn't know you were still alive.
  - I want to know why I was cast out of the Jedi Order.
  - Yes, of course. That goes without saying. `a_lightsml();a_influence_inc(6, 1)`
- Kill all you can -> only 2
- Interupt by Tobin `CAREFUL IN LS -> ONE DIALOG TO RETURN TO THE RIGHT SIDE WITH THID PLAYTHROYGH`
  - What's going on here?
  - Why does the General want an alliance with me?
  - **You expect me to believe that's all you know?**
  - **What assistance do you want?**
  - What could you offer me?
  - How does this work then? `lol -> will attack you`
  - If you vouch for him, that would make the decision easier.
  - [Awareness] I sense no duplicity in this offer, as well.
  - **I will not work with you.**
  - **I don't want Kavar dead.**
- Talk around
  - Nikko
  - Qimtiq
  - Kiph in is the swoop room
  - Bahima say they will be closing
  - Vix as dumb as before
- Outside
- Head to Djagon room -> back Vaklu men running toward the cantina
- Kill 5 Vaklu men
- Back to central square
  - Why aren't you shooting at me? All the other soldiers have been.
  - It's broad daylight. They were wearing uniforms.
- Ambush by civilians
- Gegorran don't want to sell anymore
- Turrets against you
- Leave



- Back spacioport
- MAND
- Beast -> why attacked
- News
  - _Two new alerts of escaped Republic spies have been circulated to all media centers. If you see either of them, please report it to the authorities immediately._
  - _In the latest news today, the Onderon Space Force has confirmed that a Republic military craft initiated the space battle over our planet._
- HARD SAVE
- Back to Dhagon Gent
  - Contact the Jedi Master now.
- HK waiting
- Return on DXUN


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
- Guide
- MAND `I want to have a word with you` -> Unifications of the clans
  - What is it?
  - How do you plan on doing that?
  - Is that a threat?
- Make sur Visas has a simple single blade LS
- HARD SAVE

- EBON
  - Disciple `I wish to show you something.`
    - What?
  - MAND `Nice ship you have here. Where did you get it?`
    - We requisitioned it from the clutches of a Sith warship.
    - Simulants
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
  - Bao
    - Learn Beast trick + Dominate mind
  - Same with Atton and Visas
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


- head to nar shaddaa
- Greeda -> not yet
  - I wanted to talk to you about establishing trade routes.
- Docks -> Mandalorians
  - You prefer being an out of work mercenary to returning to the glory of the Mandalorians? `a_influence_inc(2, 2)`
- MAND
  - Do you know anything about this world?
- Ebon `during the night (nice on Nar Shaddaa)`
  - Bao `c_influence_gt(1, 85)`
    - _{Malachor V}{Somewhat haunted, sleepless/restless}{Bao-Dur is in one of the rooms, staring at a panel, not doing repairs as usual, the Remote is missing, no one else is nearby, the ship is asleep}_
    - Don't you ever sleep?
    - My decision haunts me, too.
      - _Blame lies with me, for creating it. The situation forced your hand, anger forced mine._ `-> creating the Mass Shadow Generator -> will be introduced on malachor in a bonus mission`
    - If you are to blame for its creation, then I am equally to blame for commanding its use.
  - Bao and Cand
    - Settle down, you two. This isn't the time or place for this.
    - I don't think this needs to be discussed any further.

- Dantooine
- Essok Mand
  - You control Canderous to fight against him
  - {After Mandalore wins the fight}Any other takers? `a_influence_inc(2, 2)`
- MAND
  - Do you know anything about this world?



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
- 




[< Previous Page](07_Onderon.md) |
[Back to the Index](../index.md) |
[Next Page >](09_Onderon.md)

