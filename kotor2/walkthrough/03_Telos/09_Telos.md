# Telos - Compromising Czerka corp.

[< Previous Page](./08_Telos.md) |
[Back to the Index](../index.md) |
[Next Page >](./10_Telos.md)

- Go back to Chodo
  - The Exchange will trouble you no longer. `a_give_quest_ls()`
  - **I cannot accept this from you, Chodo. Consider it my investment in Telos.** (+1LSP)
  - **How did Czerka imbed itself in the first place?**
  - All right. I'll help you.
  - [Computer] So it can't be sliced?
  - How do you propose we obtain those files?
  - Have you tried bribing a Czerka employee?
  - [Persuade] I am not sure, but we should try. `c_sc_per_gt(6)` (+500c) -> other? -> NO? need 1000 later -> comeback -> maybe ok
  - I will see what I can do.
- Go to Cantina
- Corun Falt
  - What do you do at Czerka?
  - Tell me about Lorso.
  - How do you think she'll mess up?
  - Maybe I can help you.
  - There are some files I'd like to get my hands on. Files I imagine wouldn't make her look good if they went public.
  - Something like that, yes.
  - A closed system?
  - So how do I get in?
  - No, I'm serious. How do I get in?
  - So it's a gamble. How much to cover your risk?
  - I'll be back with it.
- Come back to Chodo
  - I need 1,000 credits to bribe a corrupt Czerka executive. (or 500c if already asked?)
  - Thanks. I'll return later.
- Corun Falt (500+1000-300 = +1200c benefits: "Smooth" as Atton says)
  - [Awareness] You're reaching. 300 would be enough. `c_sc_awagtcredlt(10, 300)` `c_sc_per_gt(6)`
  - You mean, B-4D4 could walk right in.
  - **Is that all? What a great help you are.**
  - All right. I'll be going now.
- Go to Opo Chano
  - I want your droid technician credentials.
  - **It's no concern of yours.**
  - I need to borrow Czerka's administrative droid.
  - Because I need him to get some files from Czerka's mainframe to expose Czerka's corruption to the Telosian authorities.
  - You can't? Why not?
  - Your contract? Why is that?
  - Credits? What for?
  - A loan? From whom?
  - **Hey, I answered all of your questions.**
  - Slusk and Luxa are dead and the Exchange is in disarray. They won't enforce your debt.
  - Just say your credentials were stolen.
  - Try it. It's easy.
  - That's not true. You're lying.
  - What if I repaid your loan?
  - I'll be back when I have the credits. [End Dialog]
- Chodo!
  - - I may have a solution to our problem.
  - Czerka's administrative assistant is a protocol droid. If we could steal that droid and reprogram it...
  - I need 2,500 credits to loan to a Czerka droid technician.
  - Thanks. I'll return later.
- Back to Opo Chano
  - Yes, here: 2500 credits.
  - Keep the money in return for the credentials. (not on switch??)
- Go to Czerka office
- reask
  - I need you to come with me.
  - I have my droid technician credentials right here.
  - Let's go now.
- TP to Ithorians office
  - Please reiterate the mission.
  - [Lie] I do not understand.
  - I was merely testing my ability to lie.
  - I will return when I have obtained the files.


- B4-D4 -> 203chano -> get 20 credits!

```txt
List of interaction on this map:

./204TEL_dlg.erf/204habat.dlg:        <resref label="Active">c_b4d4pc</resref>
./204TEL_dlg.erf/204habat.dlg:        <resref label="Active">c_b4d4pc</resref>
./204TEL_dlg.erf/204ithr.dlg:        <resref label="Active">c_b4d4pc</resref>
./204TEL_dlg.erf/204moza.dlg:        <resref label="Active">c_b4d4pc</resref>
./204TEL_dlg.erf/ithplant.dlg:            <resref label="Active2">c_b4d4pc</resref>
./204TEL_dlg.erf/ithplant.dlg:            <resref label="Active2">c_b4d4pc</resref>
```

- Go to residential module east

```txt
List of interaction on this map:

./203TEL_dlg.erf/203bed.dlg:        <resref label="Active">c_b4d4pc</resref>
./203TEL_dlg.erf/203chano.dlg:        <resref label="Active">c_b4d4pc</resref>
./203TEL_dlg.erf/203thgd1.dlg:        <resref label="Active">c_b4d4pc</resref>
./203TEL_dlg.erf/203thgd2.dlg:        <resref label="Active">c_b4d4pc</resref>
./203TEL_dlg.erf/203thgd3.dlg:        <resref label="Active">c_b4d4pc</resref>
./203TEL_dlg.erf/203thgd4.dlg:        <resref label="Active">c_b4d4pc</resref>
./203TEL_dlg.erf/batono.dlg:        <resref label="Active">c_b4d4pc</resref>
./203TEL_dlg.erf/harra.dlg:        <resref label="Active">c_b4d4pc</resref>
```

- Entertainment

```txt
List of interaction on this map:

./202TEL_dlg.erf/202drdt.dlg:        <resref label="Active">c_b4d4pc</resref>
./202TEL_dlg.erf/202grenn.dlg:        <resref label="Active">c_b4d4pc</resref>
./202TEL_dlg.erf/dendis.dlg:        <resref label="Active">c_b4d4pc</resref>
./202TEL_dlg.erf/samhan.dlg:        <resref label="Active">c_b4d4pc</resref>
```

- Cantina

```txt
List of interaction on this map:

./207TEL_dlg.erf/207falt.dlg:        <resref label="Active">c_b4d4pc</resref>
./207TEL_dlg.erf/207luxa.dlg:        <resref label="Active">c_b4d4pc</resref>
./207TEL_dlg.erf/207swpmc.dlg:        <resref label="Active">c_b4d4pc</resref>
./207TEL_dlg.erf/dotonhet.dlg:        <resref label="Active">c_b4d4pc</resref>
./207TEL_dlg.erf/mebla.dlg:        <resref label="Active">c_b4d4pc</resref>
./207TEL_dlg.erf/ramana.dlg:        <resref label="Active">c_b4d4pc</resref>
```

- Docks

```txt
List of interaction on this map:

./201TEL_dlg.erf/201ithd.dlg:        <resref label="Active">c_b4d4pc</resref>
./201TEL_dlg.erf/202drdp.dlg:        <resref label="Active">c_b4d4pc</resref>
./201TEL_dlg.erf/202drdp.dlg:        <resref label="Active">c_b4d4pc</resref>
./201TEL_dlg.erf/202drdp.dlg:        <resref label="Active">c_b4d4pc</resref>
./201TEL_dlg.erf/czerdock.dlg:        <resref label="Active">c_b4d4pc</resref>
./201TEL_dlg.erf/durosdock.dlg:        <resref label="Active">c_b4d4pc</resref>
```

- Exchange

```txt
List of interaction on this map:

./208TEL_dlg.erf/203slusk.dlg:        <resref label="Active">c_b4d4pc</resref>
./208TEL_dlg.erf/203vula.dlg:        <resref label="Active">c_b4d4pc</resref>
```

- Czerka

```txt
List of interaction on this map:

./209TEL_dlg.erf/203lorso.dlg:        <resref label="Active">c_b4d4pc</resref>
./209TEL_dlg.erf/203lorso.dlg:        <resref label="Active">c_b4d4pc</resref>
./209TEL_dlg.erf/czerkag.dlg:        <resref label="Active">c_b4d4pc</resref>
./209TEL_dlg.erf/czerkag2.dlg:        <resref label="Active">c_b4d4pc</resref>
```


[< Previous Page](./08_Telos.md) |
[Back to the Index](../index.md) |
[Next Page >](./10_Telos.md)
