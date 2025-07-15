# Nar Shaddaa - Ambush

[< Previous Page](09_Onderon.md) |
[Back to the Index](../index.md) |
[Next Page >](11_Onderon.md)


- Have a chat with Mand `no influence directly on him` 
  - Go ahead. `!c_influence_bt(2, 29, 69)&&!c_local_set(44)`
    - They were the only Jedi who realized that the Republic would fall without the support of the Jedi.
    - **The Mandalorians were a menace that had to be stopped.**
    - Of course. The Mandalorians couldn't run the Republic.
  - I was wondering if you could give me some stimulants.
    - I'll take any advantage I can get.
  - Do you know anything about this world?
  - Never mind.
- Murder scene
- droid!
- Back to the Cantina
  - Bahima
    - Can I talk with you about Captain Sullio's murder?
      - An acquaintance of mine, Dhagon Ghent is being questioned by the military about this. I'd like to get him free.
      - Do you know Dhagon Ghent?
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
- Out
- 1B-8D
  - B-8D, I need to know if you have any parts from one of Bahima's serving droids.
  - I want to buy those parts.
  - Here's 25 credits.
- Back
  - // Nikko -> you have the head
  - Kiph -> head
  - Nikko
    - I want to show
- ...
- Captain
  - Dhagon Ghent couldn't have killed Captain Sullio.
  - Nikko can explain it.
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
  - Last race
    - 4th round -> vs Jonra Far -> 5000c +500c
      - Jonra Far
      - M'sadaar
      - Vix
  - Bakel
    - **Are you a beast-rider?**
    - You have something that belongs to Dhagon Ghent. I want to get it back.
    - I was hoping I might be able to buy any holodisks you get from his office.
  - Open visas!
  - Leave the Cantina
- Dhagon
  - I got the holodisks from Bakkel.
  - **I have something I have to do first.**
- Last peaceful time on Onderon!
- Talk to the people -> you are the swoop champion!
- Riiken will talk to you
- News terminal
  - _Crime rates have been soaring in recent months. Even in the Merchant Quarter, the Western Square has seen a dramatic increase in violent crimes._
  - _In the Merchant Square today a full scale riot broke out. During a public speaker's address, vocal supporters of Queen Talia were provoked to violence._
  - // UNREACHABLE _In local news, a citizen in the Merchant Quarter was mistakenly arrested by Queen Talia's soldiers. The soldier's report claimed that the speaker was "attempting to incite a riot."_ 
- Terlin `Handmaiden, Disciple, Visas infl+`
  - I have found a visa for you. Here.


[< Previous Page](09_Onderon.md) |
[Back to the Index](../index.md) |
[Next Page >](11_Onderon.md)

