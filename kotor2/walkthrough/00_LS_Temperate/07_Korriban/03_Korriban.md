# Nar Shaddaa - Ambush

[< Previous Page](01_Korriban.md) |
[Back to the Index](../index.md) |
[Next Page >](02_Korriban.md)


- Academy
- On the right always
- Door!
- -> Sith has been automatised
- computer
  - [Computer] Access system commands. `c_sc_com_gt(5)`
  - Enter 'New Recruit.' `-> acount number to note!! or c_sc_com_gt(14)`
  - Enter 3401726-B853S5O0X001. `it's the second one`
  - Access Learning Material.
  - Log out.
- "Library" -> sith to kill
- THorium charges
- Computer -> Sith code `ERROR: PRIMARY BUFFER OVERFLOW. DATA CORRUPTED.`
  - [Computer] Connect to secondary buffer. `c_sc_com_gt(5)`
  - [Computer] Reset key buffer and then connect to secondary buffer. `c_sc_com_gt(10)`
    - History of the Sith. `DELETED`
    - Holocrons. `-> in the library?`
    - Flora and Fauna. `DELETED`
    - **The Sith Code.**
      - _Peace is a lie. There is only passion._
      - _Through passion, I gain strength._
      - _Through strength, I gain power._
      - _Through power, I gain victory._
      - _Through victory my chains are broken._
- Back to the computer in the dorms
  - [Computer] Enter 3401726-B853S5O0X001.
    - Access Training Room. `ERROR`
    - Take the Level one written test.
      - Freedon Nadd. `a_localn_inc(20) - it's on Dxun`
      - Twenty. `a_localn_inc(20) 9 on each sides`
      - Gizka. `a_localn_inc(20) c.f. KOTOR1...`
      - I always lie. `a_localn_inc(20), not a paradox`
      - passion - strength - power - victory. `a_localn_inc(20)`
    - Access Training Room.
- Sith spwan!
- Use thorium charges to blow the door
  - The holocron will work only if `!c_chkrevend(0) -> REVAN = SITH -> {Bastila hologram}`
- Leave -> right -> to the old city
- Sith ambush
- Right gas -> before LEFT -> LOOT 
- GAS -> breath control
- Sith
- Computer
  - [Computer] Access system commands.
  - Begin training sequence.
- kill the Tuk'atas
- Test will always fails but
- toture room opens
  - Vash was one of the members of the Jedi Council quickest to reject me.
- Loot
- Computer
  - Schedule disciplinary action.
  - Self.
- lol
  - [Computer] Access system commands.
  - Enter "Lonna Vash."
- You can now leave!
- Sion
  - What do you know of Kreia?
  - What does Kreia want with me?
  - What do you want with her?
  - **I will not let you harm her.**
- Kill the two siths behind him (600XP)
- try to kill Sion
- Kreia
  - Now you tell me. Anything else you want to share?
- Run towards the Ebon
  - T3!
    - A message from Kelborn? What is it?
    - He got a message from Kavar?
    - Yes, we should return to the Mandalorian Camp as soon as possible.
  - G0-T0 + Bao


- Dxun
  - Prepare
    - **Did Kavar say what he wanted?**
    - So I came all this way for nothing?
    - **[Awareness] I have to lead the group heading to the royal palace, don't I?** `c_sc_awa_gt(10)`
      - Bao-Dur has the skills
      - Mira.
      - Visas.
      - Yes, I'm certain.
      - I'm ready. They should head out now.
  - Take Bao as the leader
    - Mira + Visas (lines)
  - Mira take the mines
  - Mines
    - "{Someone has Stealth and Bao Dur's comment}We'll send one of us up ahead. They'll use Bao-Dur's code to bypass the sensor. `if c_local_set(35)&&c_xarga()` `a_baodur_code()`
  - Visas STEALTH between mines
    - Use Bao-Dur's corporate override code.
  - Turret power `NO DONT TOUCH`
    - Destroy turrents -> give the turret XP also! -> does it destroy also the others behind??
      - Only the 3 first give XP
  - Computer
    - [Computer] Slice the computer. (<CUSTOM35> spike(s)) `0`
      - Access security cameras.
        - CAM-410A Base Camp
        - CAM-410B Mine Field
      - Access officer logs.
        - Access officer logs.
          - Access Log 254-03 `a_holo_message(0, 40) need to press A twice?`
          - Access Log 255-13B `a_holo_message(0, 41)`
          - Access Log 255-33 `a_holo_message(0, 42)`
        - Return to root menu.
      - Access system commands.
        - [Computer] Run "Foothold" scenario. (<CUSTOM34> spike(s)) `2`
- 520 XP
- Kill all
- SAVE
- Xarga
  - Who was Freedon Nadd?
  - How could you have missed it?
  - Is that all you know about this tomb?
- Right
- Computer
  - `x, -, +, /`
- 500 XP
- Fully repair the droid
- Dark side area
  - Mira comment
    - But it may give us a clue about what's going on.
- Move forward
  - Control your emotions.
  - Bask in the power of the Dark Side. `-> learn slow`
- 1 DSP but not taken into account?

```
 INFO: [0] <NO TEXT>
 INFO:       >> ReplyList[3], isActive=c_global_eq("411DXN_Learn_Power", 45), nextList=[[0]: 15 if c_global_eq("411DXN_Learn_Power", 45), [1]: 14 if c_global_eq("411DXN_Learn_Power", 16), [2]: 13 if c_global_eq("411DXN_Learn_Power", 50), [3]: 12 if c_global_eq("411DXN_Learn_Power", 43), [4]: 11 if c_global_eq("411DXN_Learn_Power", 7), [5]: 10 if c_global_eq("411DXN_Learn_Power", 30), [6]: 9 if c_global_eq("411DXN_Learn_Power", 9), [7]: 8 if c_global_eq("411DXN_Learn_Power", 35), [8]: 7 if c_global_eq("411DXN_Learn_Power", 38), [9]: 6 if c_global_eq("411DXN_Learn_Power", 31), [10]: 5 if c_global_eq("411DXN_Learn_Power", 32), [11]: 4 if c_global_eq("411DXN_Learn_Power", 25), [12]: 3]
----------------------------
 WARN: [0] "[You have gained a new Dark Side power: Slow]"
 WARN: [1] "[You have gained a new Dark Side power: Fear]"
 WARN: [2] "[You have gained a new Dark Side power: Wound]"
 WARN: [3] "[You have gained a new Dark Side power: Shock]"
 WARN: [4] "[You have gained a new Dark Side power: Affliction]"
 WARN: [5] "[You have gained a new Dark Side power: Horror]"
 WARN: [6] "[You have gained a new Dark Side power: Choke]"
 WARN: [7] "[You have gained a new Dark Side power: Force Lightning]"
 WARN: [8] "[You have gained a new Dark Side power: Plague]"
 WARN: [9] "[You have gained a new Dark Side power: Insanity]"
 WARN: [10] "[You have gained a new Dark Side power: Kill]"
 WARN: [11] "[You have gained a new Dark Side power: Force Storm]"
 WARN: [12] "[You have gained Force Points]"
```

- Workbench -> Bao Armor against energy + regen
- Next follow the droid you just repaired
- Kill
- Droid repair
- Replace core C
- Then center
- Kill (or let the droid you repair do the job)
- Door -> Mira comments
- West coridor
  - Computer -> open the door
  - Dark energy
    - get "FEAR"
- Back to the central
  - **Untrained? What do you mean?**
  - **How is the Dark Side more powerful?**
  - But how do I use it?
  - I will not... be tempted. That path leads to the Dark Side. `a_lighthigh();a_temptation()`
- Xarga
  - I'm ready to go




- Onderon assault
- Zuka
  - I get to fly a Basilisk?
  - **What kinds of 'unimportant' support systems?**
- Mand + Kreia (mandatory)
  - **The Mandalorian exploits have left a profound impact in more places than Iziz.**
- Dress with Jedi ROBE!
- Kill -> Ramp
- Kill
- Left first
- Workbench -> robe underlay against environment (only possible)
- Console
  - [Computer] Enter Bostuco's access code.
    - Access Turret Control.
    - ...
    - [Computer] Access other systems.
    - Deactivate forceshield barrier.
- near the power conduit
- Force field opened
  - Reinforcements won't arrive in time. Surrender now.
- Kill
  - Finally, somebody has the right idea. Go ahead, run.
- Pass by the electrical conduit
- Kill the two sith after
- Royalist officer (who is actually Bostuco?)
  - Let's go then!



- Palace
  - Any door can be opened, Tobin. This isn't over.
- North first
- As the cutscene suggests -> don't loot the museum yet
- Computer near the door `the hacker is trying to overload your terminal`
  - [Computer] Access defense systems.
  - [Computer] Abort console overload sequence. `c_sc_com_gt(8)`
  - [Computer] Disable remote access. `c_sc_com_gt(10)`
  - [Computer] Access system commands.
  - Log out.
- coridor
- second door on the right -> Kavar
  - What's he need me for?
- Kadron
  - **Who are you?**
  - How do we do that?
  - Where exactly is the other security console?
  - Do you have anything that can help me out?
  - I'll take care of it right now. `talk to the corporal`
- +250 XP
- Corporal
  - No
- Computer
  - [Computer] Access security cameras.
    - [Computer] CAM-506B Museum
    - [Computer] Activate museum security system.
    - [Computer] CAM-506C Primary Security Terminal `the hacker say hello! It's the guy from the cantina!`
  - Log out.
- Next room in the coridor -> bedroom
  - [Computer] Access system commands.
  - [Computer] Open the storage door.
  - [Computer] Repair corrupted key sequence.
    - 66 (66*2 - 66/2 = 99)
    - 45 (54 -> 54/45 = 1 + 1/5)
    - 39 (93 -> 93 - 39 = 54 = 2 * 9 * 3)
- Loot + security tuneler
- Back to the tresure room
- Kill all -> GAS!!
- Console
  - [Computer] Access poison gas defenses.
  - [Computer] Grant security clearance. `CLEARANCE REVOKED`
  - _Nice try, Jedi_
- Treasure
  - Ossus Keeper Robe
  - Crystal, Viridian
  - Jal Shey Perception Gloves
  - Crystal, Pontite
- South part
- Careful with the mines
- Last door
- Riiken -> torture
- Droid in next door explode once killed!
- Hacker
  - **Give me a reason I shouldn't kill you.**
  - Why would you work with General Vaklu?
  - [Awareness] I don't believe a word you've said. `c_sc_awa_gt(5)`
  - [Awareness] I can tell you aren't lying about that.
  - But you helped me clear Dhagon Ghent.
  - I need access to the console.
  - Stay here. Soldiers will come to deal with you soon.
- Computer -> open camera and leave
  - [Computer] Access security cameras
  - Log out.
- Kiph
  - What about the "Epicenter Six" program?
  - Stay here. Soldiers will come to deal with you soon.
- Riiken
  - **I've been in my share of them. Those energy fields can sting.**
- Computer
  - [Computer] Access system commands.
  - [Computer] Open force cage.
  - [Computer] Open all security doors.
  - [Computer] Transfer all primary functions to secondary terminal then shutdown.
- +250 XP
- Riiken
  - I already transferred control to Kadron's secondary security console.
  - Let's go.

- Tobin
  - I told you that the door wouldn't stop me.
- Kill the beast
  - [Battle Meditation] Use battle meditation to rally the Royalists.
- Kill every solider
- Kavar arrives
- Get next to Talia
  - Did I miss anything? So you must be General Vaklu.
  - You'll find that I'm full of surprises.
- Go behind Valku now (push him)
- Loot while you can the soliders
  - You're right. If left free, he will bring nothing but suffering. `a_influence_inc(6, 3)`
  - But you won't live to see that day. Goodbye. `a_influence_inc(2, 3)`
- Kreia heals Tobin `-> making a diversion -> tell his master to go to Telos while the Jedi concil will happen on Dantoine`
- **THIS IS THE LAST TIME YOU CAN UPGRADE YOUR CRYSTAL WITH KREIA -> HARD SAVE**
- Kavar
  - **You were looking for me?** `is he lying??`
  - Why did you choose these places to hide?
  - Why not Telos?
  - Atris intends to rebuild the Jedi Order on Telos.
  - What happened on Katarr?
  - The Sith have revealed themselves.
    - **I thought the Sith were defeated at the end of the Jedi Civil War.**
    - Do you know anything about this threat?
    - Did you have any success in tracing the Sith?
      - I thought the Sith were defeated at the end of the Jedi Civil War.
    - Why did the Sith come here?
    - I want to talk about something else.
  - Where are all the Jedi?
    - I didn't get that impression from Vrook.
    - I want to talk about something else.
  - I need to know why you cast me out of the Order.
    - What do you mean?
    - I want to talk about something else.
  - Why did you cut me off from the Force?
    - I want to talk about something else.
  - I have reestablished my connection to the Force.
    - I want to talk about something else.
  - I saw a holo-recording of the Jedi Council meeting where you cast me out.
    - Why is this hard for you?
    - I want to talk about something else.
  - I have developed a Force bond with another. If either one of us feels pain, so does the other. If either one of us dies...
  - You've answered all my questions.
- Dxun!



- You're back with Kreia and Bao
- Talk to Bao
  - Did something happen to you on Dxun? You seem a little calmer than normal. `c_global_eq("411DXN_Tempt_NPC", 1)&&c_global_eq("411DXN_Tempt", 1)`
  - What do you mean?
- Talk to Kreia -> Journal entry
- Ebon
  - G0-T0 and Bao's sphere
- Bao
  - I wanted to teach you some of the forms I have learned.
- Kreia


- Head to Nar Shaddaa
- Leave with G0T0 and Mandalore
- Greeda
  - I wanted to talk to you about establishing trade routes.
  - Onderon is in chaos, but you might trade with Mandalorians on Dxun.
- Buy the Droid pacificator and Nomi-s armband
- Docks -> Mandalorians
  - You prefer being an out of work mercenary to returning to the glory of the Mandalorians? `a_influence_inc(2, 2)`
- MAND
  - How did you become Mandalore? `c_localn_eq(15, 2)&&!c_influence_bt(2, 21, 79)`
    - So all of this is over a helmet?
    - **Did you make a new helmet?**
  - Do you know anything about this world?
- Vogga
- G0-T0 -> stays outside!
- Vogga is still asleep
  - Please wake him for me.
- If you try to enter the room -> he gets hangry
- Take the dancer outfit to make him asleep again
- Mira -> take Elite blaster (Vaklu) + improve at the workbench of the workshop of Tienn
- Back to the Ebon



- Dantoine
- Leave with HK and T3
- HK
  - I found a new upgrade part for you.
  - [Install HK Protocol Pacifist Package.]
  - Do a diagnostic, then report.
  - Well, as long as you're not going to start shooting wildly at anyone we meet, then fine.
  - **I think I flipped the wrong switch. Or the right one.**
  - Hold still. I need to operate.
  - [HK-47 has gained a bonus to his Wisdom and Awareness. The event has also given you an experience bonus.]
- +500 XP
- Take Kreia and Mandalore
- Head east -> to the mercenary camp
- Mandalorians
  - Kill the madalorian with him
- Talk to Mandalore
  - **Why did you leave Revan?**
  - **He didn't need you along, huh?**
  - Ready for what?
- To the Enclave!
- SAVE
- Cutscene with Tobin
- Kreia
  - **[Awareness] You're afraid.** `c_sc_awa_gt(12)`
  - **Is there anything wrong?**
- ...
  - **Why were you all in hiding?**
    - What happened on Katarr?
      - So it is me?
    - Why didn't you track down this threat?
  - We must ally if we are to stop the Sith.
    - What? But the Sith are attacking the Republic!
    - Then we must act.
  - **Why did you cast me out of the Order?** `last chance to ask!`
  - **I need to know what you spoke of when you cast me out of the Order many years ago.**
    - _You already know  the answer - you've noticed it in those who travel with you._
  - What do you mean?
    - What are you talking about?
    - Are you saying I'm controlling them?
    - I don't believe any of this.
    - Are you telling me you weren't responsible for my loss?
    - But... that makes no sense. I can feel the Force again.
    - But I can feel the Force, strongly.
    - This makes no sense!
    - I won't give up the Force - stop this.
- cutscene with Kreia
- cutscene on the Ebon
- cutscene with Sion
- you revive!
- loot
- leave -> tp to Ebon
- Atton
  - What happened here?
  - How did the know she was here? `mod!`
  - But why would he do that? `mod`
  - And you didn't stop them? `mod`
  - Where are they taking her? `mod`
  - A Sith?
  - Atris will execute her.
  - But Kreia and I are linked. If she dies...
  - Then we're going to Telos. We have no choice.
- ...
  - I fear I have been influencing you all, without realizing it.
  - Do you understand why you attack who I attack, kill who I kill?
  - But what if the Force is just controlling all this?
  - I learned that I form connections through the Force - and that is why others follow me to their death.
- Telos academy
- cutscene with Kreia
- You landed!
- Got to Atris
  - **Atris, you have fallen to the Dark Side. Surely you see that.**
  - What happened to you?
    - There is no reason for us to fight.
    - Where did she go?
  - Did she say where the Sith were striking from?
    - You have placed everyone on Citadel Station in jeopardy, Atris.
    - What plans are you talking about? `leaked info from your past`
  - What is this place?
    - And when the Sith are defeated, what then?
    - Atris... you will make the Jedi into the Sith.
    - Weakness - like when you fled Katarr? And Dantooine?
    - And you left the Jedi to die on Katarr.
    - You are responsible for the murder of an entire planet. `a_local_set(37)`
    - What were the Jedi doing on Katarr? `a_local_set(39)`
    - Me?
    - But that makes no sense. Why me?
    - That makes no sense - I am not allied with these Sith.
    - What was this pronouncement on Katarr?
    - If it showed the future, then that is only one such possibility.
    - What is the echo?
    - But what is the echo?
    - But I did nothing!
    - That vision on Katarr - was it the future or the past?
    - Why did you not warn the Jedi what would happen?
    - If you murdered them out of revenge, then admit it.
  - Atris, we don't have time for this - we need to unite to stop the Sith.
  - I will not fight you - surrender, and I will spare you.
- ... battle
- Last conversation -> let her live -> will be judge by the jedi consil


- Mandalore
  - How did you become Mandalore? `c_localn_eq(15, 2)&&c_influence_bt(2, 21, 79)`
    - **So all of this is over a helmet?**
    - **How did you find the helmet?** `I was there with him when he defeated Darth Malak and traveled with him afterwards.`


- Atton
  - //What do you know of the GenoHaradan? `CUT CONTENT`




- /// head to nar shaddaa


- Dantooine
- Essok Mand
  - You control Canderous to fight against him
  - {After Mandalore wins the fight}Any other takers? `a_influence_inc(2, 2)`
- MAND
  - Do you know anything about this world?



[< Previous Page](01_Korriban.md) |
[Back to the Index](../index.md) |
[Next Page >](02_Korriban.md)

