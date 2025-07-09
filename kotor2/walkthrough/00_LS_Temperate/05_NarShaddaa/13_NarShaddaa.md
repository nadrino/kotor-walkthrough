# Nar Shaddaa - Ambush

[< Previous Page](../12_NarShaddaa.md) |
[Back to the Index](../index.md) |
[Next Page >](14_NarShaddaa.md)


- TODO: END THE QUEST WITH PILOT -> THEY DISAPPEARED... -> END AFTER MIRA ENTER JEKK JEKK
- 3 HK
- Fassa
  - Do you need pilot
  - The refugee Odis, will work for you for sponsorship.
- +1500 XP
- Vogga
  - I do not have Goto here, but rest assured, he will trouble you no longer.
- + 500 c + 1050 XP
- Leave
- 3 HK
  - Take **Mira & Kreia** for the AirSpeeder with mod + conv with MIRA! + no HK50 anynmore `Kreia for Aaida` `HK USELESS in MIRA TALK`
- Refugee
- A quest message will appear
- Aaida
  - Lootra lives - he's actually came to Nar Shaddaa looking for you.
  - The path is clear, the Exchange thugs have been dealt with.
  - This galaxy could go a long way to healing itself if everyone was able to help each other in such a way.
  - You'd better go - he's waiting for you.
  - +1000 XP
- Airspeeder
  - [Repair] Install maneuvering flaps. `c_sc_rep_gt(15)`
  - [Demolitions] Install cryogenic power cells. `MIRA!`
  - I'd love your help, Mira. `a_influence_inc(7, 1)`
- +600XP
- Airspeeder
  - Attempt to use the airspeeder.
  - Go to Refugee Landing pad
- Mira -> NOT WITH ATTON, doesn't make sense -> equip her with standard clothes
  - Why are you looking at me like that?
    - **When one is in touch with the Force, others can feel it.**
    - Me and Atton what?
    - What are you talking about?
    - I care about him, but I can't allow myself to form attachments now.
    - I was hoping we could talk.
      - Do you understand men?
      - That could work. I guess.
      - That sounds more like hunting.
      - There were some questions I wanted to ask.
    - Where did you get that rocket launcher?
      - [With Mira in your party, you can make rockets at workbenches, provided your Demolitions skill is high enough.]
    - Why don't you kill your targets?
      - [Awareness] Because all life is connected, and Malachor proved it - you know what the loss of family means, even to your targets. `c_sc_awa_gt(10) + a_givelight(1)`
      - We did what had to be done, and I carry that decision still.
- Entertainment 
- Juma -> force persuade -> atton comments
- Twilek
  - If you think I will be to Vogga's liking, I will dance for him.
  - I'll do it.
  - Wait - did you say put something on?
  - All right, if I have to.
- ...
  - Poor Juma
- Open containers -> Dooble bladed LS
- Aaida & Lootra `KREIA BANTER`
  - I hope so, too - may the Force be with you both. `a_give_quest_ls()`
  - I think you already knew the answer, which was why you didn't give in to the Exchange.
  - That's a little harsh.
  - **If you were lost to me, Kreia, I would not turn away a stranger's help to rescue you.**
  - If it meant your life, there is nothing I would not do... for you, or any of my allies. `free infl on Atton, Bao, Handmaiden or Disciple if needed`
- Lightsaber!! green viridian -> exchange -> Kreia will color gree green

- Back to Ebon with speeder
- Borna Lys -> profit
- Mira
  - I wanted to apologize.
    - Still, I'm sorry you lost your family at Malachor. `a_givelight(1);a_influence_inc(7, 1)`
    - What do you mean?
    - All things are connected through the Force. From such acts of kindness, great things may come. `a_givelight(1);a_influence_inc(7, 2)`
    - Fair enough. I had some questions for you.
  - Tell me a little about Hanharr. 
    - What happened between you and Hanharr? 
    - What do you mean? `c_influence_bet(7, 30, 70)`
      - Yes, I'd like to know what happened.
      - Do you know the name of his homeworld?
      - Do you know what species he is?
      - So he was a slave?
      - [Awareness] Why was he wearing those cuffs? `c_sc_awa_gt(10)`
      - It's good he broke free. Nothing deserves to be caged. `a_givelight(1)`
      - [Intelligence] Weren't they destroyed? `c_ac_int_gt(12)`
      - Who did he work with?
      - So how do you factor in?
      - That seems strange.
      - A foolish code. His species would die from such debts.
      - What do you mean?
      - That life debt makes no sense.
      - He didn't seem much of a problem to me.
      - Any regrets that he's gone?
    - So how did you save his life? `c_influence_bet(7, 20, 80)`
      - And you proved him wrong?
      - So he was trying to hem you in with a minefield?
      - [Demolitions] Sending out a jamming signal for proximity mines isn't a simple trick. `c_sc_dem_gt(6)`
      - What happened with Hanharr and the mines?
      - Barely?
      - Sometimes it is stronger to spare a life than take it. `a_lightsml();a_influence_inc(7, 2)`
      - There were some questions I wanted to ask.
    - Were you raised on Nar Shaddaa? `c_influence_bet(7, 40, 60)`
      - What happened to your family?
      - They died in the final battle?
      - How could you have lost family at Malachor V? There were no colonies - it was a taboo world to the Mandalorians.
      - You're a Mandalorian?
      - You were a slave?
      - I regret the loss of life at Malachor. But there was no choice left. `a_global_set("000_Mira_Malachor_XP", 1);a_givelight(1)` 500 XP
      - You don't sound too happy about it.
      - They had to be stopped.
      - Forget it. I had some questions for you.
    - Why did you become a bounty hunter? `c_global_gt("000_Mira_Family", 1)&&c_global_eq("000_Mira_Angry") -> NO already`
      - Finding people on Nar Shaddaa seems difficult.
      - Walking?
      - No, I understand.
      - Forget it. I had some questions for you.
    - I was hoping we could talk.
      - Just wanted to get to know you a little better, is all.



[< Previous Page](../12_NarShaddaa.md) |
[Back to the Index](../index.md) |
[Next Page >](14_NarShaddaa.md)
