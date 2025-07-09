# Nar Shaddaa - Ambush

[< Previous Page](../13_NarShaddaa.md) |
[Back to the Index](../index.md) |
[Next Page >](../06_Onderon/01_Onderon.md)



- Ebon
  - GOTO HK
  - GOTO + sphere
  - Mira + Atton
  - Kreia + T3
  - Bao + GOTO
    - Don't worry, Goto's just jealous that you've got all that circuitry packed in such a small shell.
  - Bao + sphere x2
  - Bao + HK
  - Bao + GOTO
- Visas
  - Forms
- Bao
  - Same
- HK
  - I wanted to do some target practice.
  - Hold your fire - I don't need anyone killed. Yet.
  - You seem to have seen better days. I could repair you. `RESTORED++??`
  - Did you just call me 'unskilled meatbag'?
- T3
  - When I was captured by Goto, how were you able to find Goto's yacht? `c_global_eq("303NAR_Goto_Ware")+c_global_gt("303NAR_T3_Mission")`
  - You snuck into Vogga's droid warehouse to steal the codes?
  - So who was transmitting the codes to Goto's yacht?
  - The droids? Interesting.
- MIRA
  - Can I get some grenades from you?
    - Then you're fighting for your life, you use what's at hand. `Sonic on Bith!!`
    - Why not? `also Sullustan`
    - I was hoping for something more lethal. `HK banter`
    - [Persuade] Mira, we're being stalked by assassins. We need all the weapons you can make. `c_sc_per_gt(10)`
    - Just make me some grenades.
    - There were some questions I wanted to ask.
  - {On Ebon Hawk}You seem restless.
    - Too quiet?
    - Like Nar Shaddaa?
    - Used to Nar Shaddaa? Is that possible? `a_influence_inc(7, 1)`
    - Kreia showed me how to "listen" to Nar Shaddaa once... how all life there is connected, is bound to each other.
    - Maybe one day I'll be able to show you. `c_influence_bet(7, 10, 90)`
    - Come with me - and let me show you what Kreia showed me.
  - Leave the Ebon with MIRA
- Go near the entertainmnt
  - I wanted you to stand here - and listen.
  - No, there is - you can feel the Force here.
  - No, it's what you do. And I can prove it.
  - No, but it may help you put life, and all its hopes, in perspective. `a_givelight(1)`
  - I can train you, Mira. To become something greater - and to protect others. `a_givelight(1)`
  - I cannot promise that, Mira, I can only teach you what I know.


- Ebon
- GOTO / Bao +1 DEXT
  - What happens now that I know you're a droid?
    - Aren't you going to try and have me killed because of what I know?
    - Forget it. I had other questions.
  - You wanted me to save the Republic. How is that possible?
    - Is there anything you can do to help those systems and their people, either with information or resources? `a_global_set("000_Goto_Paid", 1) -> enables the payment`
    - I don't want a reward - helping the people of those systems is enough. `a_lightmed();a_influence_dec(3, 1)` + `a_global_set("000_Goto_Paid", 2) -> will prevent the payment in LS progression` 
    - Just tell me what needs to be done to help these systems.
      - Just tell me what needs to be done to help these systems.
      - What about the restoration efforts on Telos?
      - Yeah, yeah - it wasn't my fault.
      - That wasn't an option, either.
      - I'm getting tired of being blamed for Peragus.
      - What's the situation on Onderon?
      - I had other questions.
    - Where is your base of operations? `000_Know_Goto`
      - I had other questions.
    - What capabilities does your droid possess?
      - Not if I shut it down first.
      - What skills does it have?
      - So you're sneaky and confusing? `a_global_set("000_Goto_Skills", 1);a_influence_dec(3, 1)`
      - I had other questions.
    - Do you know anything about the HK droids sent after me?
      - Why are they hunting me?
      - Do you know where they are coming from?
      - You mean they're going to come after me?
      - What are they doing in the Republic fleet?
      - Why doesn't the Republic know?
      - Why haven't you acted on this information?
      - I had other questions.
    - On the yacht, you mentioned Revan. But Revan sought to destroy the Republic.
      - But why? Revan had limitless forces.
      - But why? Revan wouldn't need to conquer anything else once the Republic was beaten.
      - Do you know where Revan got his forces?
      - What about Malak?
      - Nothing, never mind.
- Atton
  - Did you know Mira, Atton?
  - Nothing, never mind.
- MIRA
  - It was not my doing, Mira. I merely showed you what you could do.
  - Grenades?
  - I was hoping we could talk.
- KREIA
  - Crystal -> disassemble crystal
  - LS styles
- reassemble LS


- Telos
- GOTO + HK
- HK50!
  - Can't shoot HK47
- Grenn
  - That's it? Aren't you going to put me under arrest?
  - Why would the Republic change their minds like that?
  - You should really improve your security arrangements.
  - I'd like to talk to you about the bounties.
    - I killed the escaped criminals.
    - I followed them to the restoration zones, where they were on duty as Czerka security, and killed them.
- Grenn
  - I've found a solution to Citadel Station's fuel problem.
    - First, let's talk about my fee.
    - Vogga has a lot of fuel from Sleheyron, and he needs to sell it.
- Workbench
  - Ultimate Diatium Energy Cell (T3)
  - Osus lens x3 (Kreia)
- Ebon
  - HK-47-HK-50
  - MIRA
    - Teach
  - G0-T0
    - I wanted to talk to you about your operations on Nar Shaddaa.
      - I wanted to ask about Vogga.
    - A lot of your operations on Nar Shaddaa were carried out by droids.
      - Vogga's freighters were being hijacked by droids. `a_global_set("000_Goto_Ware", 1);a_global_inc("000_Goto_Confront", 1)`
      - The droid in the pazaak den - was built to play, to lose - and to watch the other players. `a_global_set("000_Goto_Ware", 1);a_global_inc("000_Goto_Confront", 1)`
      - The swoop racing on Nar Shaddaa was being dominated by a droid. `a_global_set("000_Goto_Pazaak", 1);a_global_inc("000_Goto_Confront", 1)`
      - That Bith off the docks who was murdered by his droid after he had found that frequency was being used all over the moon to relay information. `a_global_set("000_Goto_Bith", 1);a_global_inc("000_Goto_Confront", 1)`
      - The reason you couldn't tell what Visquis was up to was because droids don't function properly in the Jekk'Jekk Tarr. `a_global_set("000_Goto_Jekk", 1);a_global_inc("000_Goto_Confront", 1)`
      - **I think you used droids in your operations because you are a droid.**
      - Something about Visquis and the Jekk'Jekk Tarr is what made me think of it. When you said "organic."
      - Is it? The identifier wasn't necessary, but yet you felt the need to use it.
      - Normally, I would attribute such a slip to... human... memory, but one of your annoying traits is that you seem to remember everything.
      - I suspect you are a droid, an extremely advanced model. What I don't get is how you are able to commit crimes.
      - But what is curious is that you still want to help the Republic. That's where things don't fit.
      - You sound - defensive.
      - Well, I've got some of the pieces - but not all of them. And when I do, I'm going to figure you out.
      - [Awareness] The first Republic droid intelligence intended for Citadel station was lost. Or was it?
      - And what did this "droid," do?
      - **So you are the droid that was intended for Citadel station.** 
      - So all the crime... everything you've done for the Exchange is actually because you want to help the Republic.
      - That is my goal as well - to help the Republic, help its people. `a_lightmed()`
      - But why the hologram? `NEED TO BE ON THIS EBON -> LATER`
      - What happens now that I know you're a droid?
      - Aren't you going to try and have me killed because of what I know?
      - Forget it...
- +3250 XP + LSP
- Atton teach

- BUG/IMPROVEMENT: Airspeeder broker
  - `!c_glob_bool_set("300NAR_Visquis_Call")`
- BUG: Duros alien voice replacement: `Has there been any news from the scout?`, should be: `I do not understand why they would do that. I had th`....

`Modules/351nar/console02.dlg ['!c_have_item("k_computer_spike", 1)', 'c_sc_com_lt(6)', 'c_sc_com_bet(6, 25)', 'c_sc_com_gt(24)'] 96203 activeList[3]`
c_sc_com_gt(24) ???? -> T3 SOLVED



- LATER cause I enter/leave Ebon:
  - HK + Bao > finally improve it! +1 const


[< Previous Page](../13_NarShaddaa.md) |
[Back to the Index](../index.md) |
[Next Page >](../06_Onderon/01_Onderon.md)
