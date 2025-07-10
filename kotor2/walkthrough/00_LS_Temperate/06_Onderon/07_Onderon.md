# Nar Shaddaa - Ambush

[< Previous Page](06_Onderon.md) |
[Back to the Index](../index.md) |
[Next Page >](08_Onderon.md)


- western square
- Kill bounty hunters
- Go to the cantina first
- Cantina
- Gormo
  - Why do you ask?
  - Have you tried to explain your situation to the soldiers?
  - There seem to be a lot of people here that need one.
  - I only have mine and I'm using it.
  - Slicer?
  - Do you know what is going on here?
  - I'll be going now.
- Funny twilek
- Gelesi
  - You seem tired.
  - What's so tough about it?
  - Tell me about Sullio.
  - What do you know about the murder?
  - You sound nervous.
  - [Persuade] That sounds like a good idea. You need to think of your family first. `fail`
  - [Persuade] You're right to worry. I know people want to get rid of the captains. `c_sc_per_gt(16)`
- SAVE
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
  - Buy you a drink?
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
- Jonra Far
  - I'll take that drink. I'm <FullName>.
  - Struggle?
  - Free yourselves? I didn't know Onderon was a conquered planet.
  - Sounds like the Republic has been bad for Onderon.
  - What can I do?
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
  - He proposes to race again -> Panar wants his revenge
    - [Persuade] With the money I've made you, I'm not going to pay the fee. I want a cut of the profits. `c_sc_per_gt(18)`

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
  - I'll see what I can do.
- Sakarie `Crystal only for DS` `Kreia banter`
  - A lightsaber crystal? What does it do?
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
- Kiph
  - What do you know of the city?
    - What do you think of the General and the Queen?
  - What do you do?
    - Could you be a little more vague?
- Waitress
- Leave the Cantina


- 1B-8D `infl GOTO(3) if needed`
  - What do you sell?
  - Can you answer questions?
    - Who do you work for?
    - Can you tell me about Iziz?
    - Do you know how I could get to the Palace?
    - Can you tell me anything about the Palace?
    - I get the idea. Can I ask about something else?
    - [Repair] Let me just see if I can rewire you to be a little more "helpful. `c_sc_rep_gt(4)`
    - Who do you work for?
    - 1B-8D please give me components for free.
    - 1B-8D, request access market conditions. Change all, multiply by 0.
    - Let me see what you have for sale.
- SAVE -> spawn bounty hunters
- Dagon Gent place
  - Where is he?
  - Do you think Dhagon did it
  - Mandalore, could Dhagon have done this?
  - What tower?
  - Thanks for the information.
- Loot the messy lab
- Back to the turret
- bounty hunters
  - And what if I am?


- cutscene vaclu
- Anda +2500c
- Back Riiken
  - Do you have a man named Dhagon Ghent in custody?
    - Who got murdered?
    - How long is Dhagon going to be questioned?
    - Can I see him?
    - How can I eliminate him as a suspect?
    - Can I ask about something else
  - You were telling me about the troubles in Iziz. `last time we can peacefully`
    - What do you mean by that?
    - Why don't you tell me what you really think?
    - [Persuade] How will it get better if people are afraid to speak out? It's just a form of cowardice. `always fails`
    - **[Persuade] You hide behind your shaky rationales build of fear and weakness. You don't have the strength to live by your beliefs.** `c_sc_per_gt(12)`
- Ponlar `infl with Mand`
  - [Persuade] Everyone join Ponlar. The Queen's reign must end!
  - If we want to work with Vaklu we need to give him some sort of sign. This is as good as any. `a_influence_inc(2, 2)`
- kill everyone
- lvl 26?
- Andar +550 XP
- Go to the cantina


[< Previous Page](06_Onderon.md) |
[Back to the Index](../index.md) |
[Next Page >](08_Onderon.md)

