# Dantooine - Preparing for the battle of Khoonda

[< Previous Page](./05_Dantooine.md) |
[Back to the Index](../index.md) |
[Next Page >](./07_Dantooine.md)

Back to Khoonda
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
- Suulru
  - Would you be interested in joining the Khoonda militia? `Bug, recrut quest never ends -> add a script to check the status`
- Talk to Berun
- Adum Larp
  - Would you be interested in joining the Khoonda militia? `no`
- Turrent Control Station `T3`
  - [Computer] Slice the computer. (<CUSTOM35> spike(s)) `0`
  - Turret status `programmed to attack everything`
  - Change turret target priority
  - Reprogram turrets to attack only Hostiles (<CUSTOM34> spike(s)) `3 spikes with T3 with comp improvement` 
- +590 XP
- Leave Khoonda by the garage door
- Place 4 mines next to the others in the East
- Akkere -- get the thorium charges!
  - Would you be interested in joining the Khoonda militia? `Bug, recrut quest never ends`
  - This isn't a permanent job. Very short term, but dangerous.
  - You can store your wares on my ship.
  - I'll take them. `-1000c + Thorium Charges`
- Lock the back door with Bao
  - [Repair] Lock down the security door. (<CUSTOM42> Part(s)) `1 with bao`
  - +355 XP
- Dillan HATES JEDI, notice your lightsaber
  - [Persuade] Could you please answer some of my questions, first?
  - Would you be interested in joining the Khoonda militia?
- Place 3 mines in front `FIX THE QUEST "Khoonda: Traps" -> Modules/601dan/mine_chk.dlg -> script -> quest set 20/30 -> the should be set to 91 (otherwise ends at 90)`
- Go to the salvager camp
- Recrute Jorran
  - Would you be interested in joining the Khoonda militia? `Bug, recrut quest never ends`
- Back to Khoonda
- Everybody notices you LS!
- Medical room 
  - 4 injured people
    - [Treat Injury] I'll treat your wounds. `c_sc_tre_gt(11)`
  - Medical droid -> T3 or Bao
- Droid room
  - Droids with Bao/T3 + get Akere key
  - Reprogram droids NO!
- Let's see Akkere!
- Akkere `infl+ Bao`
  - I found this hydrospanner. It has your name on it.
  - Don't toy with me! I know you have been stripping these droids for parts and selling them.
  - Tell me.
    - **I believe you. I won't turn you in.** `a_lightsml()`
- Bao comments
  - It was a minor thing, nothing more. `a_influence_inc(1, 1)` + `a_influence_inc(1, 3)`
- Kill merc
  - I've already finished some of the tasks you asked me to do.
  - I want payment for helping you.
  - **[Force Persuade] You will pay me now.**
- Kill them all (force push++, nothing to loot)
- Ebon to improve items for battle (against energy)
  - Disciple and Kreia cutscene
  - -> Bao Jedi? NO just need 2800 XP for level 16, after the battle?
  - Kreia
    - I want you to teach me more about the Force.
      - You taught me of sight - is there anything else you can teach me?
      - What do you mean?
      - [Repair] Repairing machines.
      - [Treat Injury] Healing others.
      - **Very well. I shall take this lesson to heart.** `a_influence_inc(6, 1)`
      - I'll think on this, and return when my weakest skill is stronger.
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

- Take Bao and Disciple
- Go back to Khoonda


[< Previous Page](./05_Dantooine.md) |
[Back to the Index](../index.md) |
[Next Page >](./07_Dantooine.md)