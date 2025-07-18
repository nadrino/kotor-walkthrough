# XX

[< Previous Page](../08_JediConcil/06_Dantoine.md) |
[Back to the Index](../index.md) |
[Next Page >](02_TelosBattle.md)


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
  - After everything you've done, I'm not letting you off that easy.
    - What happened to you?
      - I think perhaps we have both been guilty of such things.
      - Everything that occurred at Malachor, everything that occurred in the war, was because there was no other choice.
    - Can you tell me where the Sith are striking from?
      - Is that where Kreia has gone?
      - What I started?
      - What does this have to do with Kreia?
      - Why would Kreia do that?
      - **Kreia is Sith - and she is strong in the Force. She would not forsake it, or threaten it.**
      - But why would I matter?
      - [Persuade] If you know, tell me. `!c_sc_per_lt(17)`
      - But if Kreia is Sith, why would she do such a thing?
      - Death of the Force?
      - That's impossible. How could I not tell she was Sith?
      - I have heard enough - this matter is finished.
      - **You will answer for your crimes before the Council, and then you shall return to your prison.** `CANON`

`interesting dialog 262tel/atrend4.dlg`

RCM

- HK-47
- right
  - Attempt to shut down reactor. `HK50 will prevent you from doing so`
- center
  - Query: There is information I wish to know.
  - Query: Why did you execute those droids in the lab? `if c_global_eq("298TEL_Droid_Cut", 1)`
    - Statement: If you are truly the pinnacle of droid schematics, it would seem testing weapons on each other would prove of greater value.
  - Statement: This unit would like to know how this place came to be.
    - Query: But why is this facility here?
    - Statement: This seems to be a remote location for a munitions plant.
    - Statement: Yes, an ignorance of one's origins and place in the galaxy is a sure sign of wisdom.
    - Statement: I wish to terminate this line of queries and start another.
  - Query: I wish a rundown of your capabilities.
    - Statement: It is important that my limited behavior core be educated in the differences between us.
    - Query: So you walking bombs are seeded all over the Republic fleet?
    - Statement: I wish to terminate this line of queries and start another.
  - Query: What is your purpose? `a_local_set("hk502cs", 50)`
    - Query: Why are you located here?
    - Query: But you recently became active again. Why?
    - Query: Where were your activities confined?
    - Statement: I wish to terminate this line of queries and start another.
  - Query: Who built you? `c_local_set("hk502cs", 50)` -> REVAN!
    - Statement: I was built by Revan. I do not understand the purpose in your construction.
    - Statement: I have no more questions. Signing off.
- left
  - kill droid with power conduit
  - computer -> disable comunications
- +250 XP
- Back to the reactor -> now you can
  - Attempt to shut down reactor.
  - Open all security doors.
- operate on self preservation program
- kill HKs
- capacitor armor -> -75% energy
- next


- left
  - [Enter reconnaissance pattern, observe the diagnostic training.]
- upload HK47
- let the hk-51 on
- right
- shutdown -> hk50 attack, 51 help you
- commission HK51


- Telos
- Grenn join
  - How did this happen?
  - Have you heard any word of reinforcements?
- Mand
  - Can't stand the heat?
- Chodo
- Rikeen
- Onderon soldier
  - Are you all right?
  - [Treat Injury] It looks bad, but you should be able to pull through. `c_sc_tre_gt(5)`
  - Stay here, after we secure that station, we'll get you to a medic.
  - All right then, let's go.



- Right
- Door locked -> DC 58 -> need more security skill

```
how security works?
DC of door vs security + roll. -> roll = 20 if not attacked
Unlock DC is set (maybe) if module as UnlockDC + Unlock difficulty*10 = 28 + 3*10 = 

maybe not...
Locker has 18 + difficulty 2 -> DC 21
```


- Always right
- Next corridor -> see enemy -> right, cul de sac
- then go in front
- always on the right first
- Visas cell
  - **Any weapons in there?**
  - Do whatever you feel you need to do.
- Don't go to the bridge yet
- Right until Tobin
  - **Tobin? What happened to you?**
  - Why did you ally yourself with the Sith?
  - And nothing you could do to stop him.
  - This ship... seems familiar.
  - Tobin, why did your Master come here?
  - But there's nothing here! Telos is a near-dead world.
  - Old woman?
  - But... there are no Force users here except us.
  - **If we're Force Sensitive, can he harm us?**
  - And if we deny him Telos?
  - [Wisdom] I think Kreia knows. She's been drawing him out - if she leaked Telos to your lord, maybe she wanted him to come here - and find nothing. `c_ac_wis_gt(13)`
  - Where can I find your Master?
  - Is he waiting for us?
  - What about his ship?
  - Letting you live on board this vessel seems punishment enough.
  - You made your choice, Tobin.
  - I'm here to kill your Master. Either help me or stand aside.
  - Tobin, we need your help.
  - [Persuade] If you would save Onderon, traitor, then listen to me. Once he destroys Telos, then Onderon will be among those he will destroy next. `c_sc_per_gt(17)`
  - If you are loyal to your homeworld, you will stop him here, now.
  - I need someone to set off the proton cores on this vessel when we give the signal.
- Visas reacts
  - It was a small act, nothing more.
  - No, speak your mind. I wish to hear it. `a_influence_inc(9, 3)`


- bridge
- Always on the right
- Visas
  - **Visas, you don't need to come with me.**
  - I am ready. Let's end this.
- SAVE
- Nihilus
  - Release me... or I'll blow your ship to hell.
  - Your arrogance has left you vulnerable to more conventional weapons.
  - **I have come... of my own choice - Visas is not... part of this.**
    - Her loyalty is to me now. And your battle is with me.
  - [Intelligence] Kreia has lied to you - there are no Jedi here. You have sensed it. `c_ac_int_gt(14)`
    - Then she has won... your victory against her has been for nothing.
    - Even now, the hunger is consuming you. Just as Kreia knew it would.
- First part of the battle
  - **{Kreia info}You're his link... to this place. Can you disrupt that link somehow?**
- Kill him
  - Visas... what are you doing?
  - **Look upon his face, then bring me the mask.** `a_give_item("nihilusmask", 1);a_addforcepoints(20)`
  - **What did you see when you looked at him?**
  - Then let this ship die, as it should have years ago.
- He stuns you
  - Canderous reveals how the Mand wars started
- +1000 XP
- Back


- Workbanch room
- Go to console
  - Activate the launch sequence.
  - Override the emergency sequence.
- Again
  - Seal the missile bay doors.
- Take the proton core
- Install it on the last platform
- Leave the Ravager



- Telos
  - **Is that a request, or an order?**
  - Very well. Lead on.
- Carth `who don't even bother look at you...`
  - Grenn said you wanted to speak to me about a mutual acquaintance.
  - //Why do you want to know? `only for revan woman`
  - Did you know him?
  - Do you know where Revan went?
  - **He might be dead.**
  - The Republic strong? Why?
  - Did you serve with Revan during the war?
  - Revan's ship?
  - Do you want me to tell you what I find?
- Ebon Hawk
  - cutscene with all your companions
- Malachor
  - Kreia arrives to the core
  - 




[< Previous Page](../08_JediConcil/06_Dantoine.md) |
[Back to the Index](../index.md) |
[Next Page >](02_TelosBattle.md)

