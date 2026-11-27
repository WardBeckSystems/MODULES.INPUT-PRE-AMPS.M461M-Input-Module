# M461M — Input Module: on the WBSps forum

What owners, technicians and Ward-Beck people said about the M461M on the WBSps.ca forum (Simple Machines), 2007|40 to 2013|46: 4 topics, oldest first. Quoted as posted (contact details taken out). Made by tools/forum_quotes.py from the forum's database backups.

## Price when new

_WBS INFO · May 24, 2007|40_

> Hey everyone,
>
> I was just going through the origional write-up sheet that came wth my console and it lists four extra pre's the tv station ordered for an older ward beck console, M461M's, as being $660 apiece. Anyone know what an M470 costs back in the day new?

— **Tommy P**, May 24, 2007|40

## M461M pin in/outs

_WBS TECHNICAL SUPPORT · Nov 18, 2007|40_

> Hey guys,
>
> Its been a while since i last got on the board--switched jobs and had a busy summer--and i'm trying to find the connection points for an M461M. Dr. Dave emailed me quite a while ago the "M461 impute module connector, rear view" schematic and my issue is that my module, although its an M461 series, there is no pan switch. After the mic pins at the top, there are four pins that say "FB 2, FB1, RS 2, RS 1" and next to them on the schematic it says "out". Are these the Front side busses, and if so, whats the RS stand for? Basically, i haven't a clue how to wire these--except that the mic is at the top--A to 1, shield on 2 (or b). Any assistance is greatly appreciated! I know the unit is getting power but i don't know what may need jumpered or not . . .

— **Tommy P**, Nov 18, 2007|40

> I should probably try and clear up what it is the pre looks like from the front:
>
> At the very top, just like the M461, is a small rotary knob that lets you select mic 1, mic 2, off, or line.
>
> Next down on the right side of the pre is the 'sen' knob, below that is Aux 2, then Aux 1, then a space and then a big red round 'ch on' button.
>
> Along the left side of the pre is, starting towards the top: Phase button, a push-in button marked '2', the a pre/post push-in button, then a push in button with the number '1' then a pre/post push in button, then pre fader listen button, followed lastly by a red solo button, which is equal level right next to the big red channel on button. So these are different from the usual M461's. I'm praying the second M portion of 'M461M' doesn't mean 'modified' as the tv station i got these from doesnt have any documentation on them anymore . . . !!

— **Tommy P**, Nov 18, 2007|40

> I guess what i could do is since i know where the "mic in" is, i'll wire that up and run some tone through it and plug the module into the green connector thingie so it gets power, then just go down the whole connections with my line out running to my protools active recording channel and see if i can get the tone to come through . . . of course this will be moot if i need to jumper something to get it to work . . .

— **Tommy P**, Nov 21, 2007|40

> Well, tried that method i described up above . . . didn't work so well. I'm still at square one . . .

— **Tommy P**, Dec 10, 2007|40

> well i called Ward Beck in Toronto today hoping they might have more info on the M461M module . . . the guy there knew of the device but couldn't help as WB has given all their old manuals and schematics to some guy from Polygon Production in Toronto named Waiman Funt . . . called the number and (its a cell phone) didn't get the guy, or a voicemail, so . . . guess i'll call his company and see if i can get a hold of the guy . . . anyone else gone this route?

— **Tommy P**, Jan 7, 2008|41

> maybe dave thomas has this. I'm in Sydney Australia right now so i dont have access to my archive.

— **kuzub**, Jan 8, 2008|41

> Hey Tony! Still in Australia eh? I've never been there but my wife has--she loved it. You'll have to post a review of your time there sometime! I did exchange emails with Dave about 6 months ago and sent you via email the schematic he sent me for the M461--unfortunately, i think my module is slightly different--plus i don;'t know if anything needs jumpered like my M470's did. I REALLY want to fire these guys up and hear their excellence!

— **Tommy P**, Jan 8, 2008|41

> could you post the schematic. I know almost for 100% certainty that the power configuration will be correct so that's a start. Post the schematic and some pictures of the modules inside, and front and I may be able to help. 
>
> Aus is freaking hot! being from Saskatchewan almost too hot. I've miss almost all of my winter, some would be great full but I will admit I'm missing it. I think I'm gonna go ice skating with some of my Aus family... I'll just lay on the ice for an hour and freak everyone out!

— **kuzub**, Jan 10, 2008|41

> HAHA! Dude, you should totally do that! Yeah, winter up there is the real deal! I lived in Brazil from when i was 8 until i was 12 and when i came back to michigan, oooh, winter seem WAY colder, and it has ever since . . . guess i got warm blooded or something! 
>
> I'm at work right now and will try to post some form of schematic asap. yes, power rails appear the same . . . i'm just not sure what to take off of what for signal ect.

— **Tommy P**, Jan 10, 2008|41

> i dont know much about the M461, but if the module shape is similar, either the input of the output will line up, so use that as a starting ground. I did have a 461 at one time but i sold it dave! small world. 
>
> Base on the M461 I can tell a few things
> it has 
> (1) Mic in 
> (1) Line in
> (2) FB
> (2) Reverb Sends
> (2) Master outputs (these would feed routing modules fitted above the eq's)
> (1) Solo Output
> (1) Solo DC Output
>
> so you can almost guess at what the output would be and almost get it right. Do a trace from the pot of the FB out and you'll find the ouput. then do a trace from the transformer and you'll find the mic input. touch the Transformer and you'll trace the ground for the microphone. 
>
> this is all based on the M461 picture i have... so if you take more pics I can help a little more.

— **kuzub**, Jan 10, 2008|41

> Tony, I sent you a PM . . .

— **Tommy P**, Jan 13, 2008|41

> Hi Guys, the M461 is basically a M460 without the EQ section. I have a manual for one in my shop but will not be there until Sunday. Like all Ward Beck M46xxxx series modules the Pin 22 is chassis, Pin 21 is +25 volts, Pin 20 is common, pin 19 is -25 volts. Pin 18 should be strapped to the common (p20) to have the LED's light. Pin 21 must be strapped to Y and Z to W in order to get the channel on light to come on. I usually put an 82 ohm resistor between Z and W and pin 20 should be strapped to pin X. The resistor drops the 25 volts down to about 23 volts and the incandescent lamp will last much longer.
>
> The balanced inserts pins must be strapped together and the balanced faders pins must be strapped together before any audio will get through to the final output stage. 
>
> Once I find the manual I can give you better wiring notes.
>
> Best regards, Dave Thomas www.aamicrophones.com

— **drtaudio**, Jan 18, 2008|41

> Thanks dave, Tom and I got this (I think you made it up) 
>
> I said hook it up according to this

— **kuzub**, Jan 19, 2008|41

![WBSM461pinouts.JPG](PHOTOS/FORUM/2008%20-%20forum%20125%20-%20WBSM461pinouts.JPG)

<details><summary>Text in the picture (OCR)</summary>

```
; 9 L 2 1 11 1 8 I 1 2 1 2 " 4 Eez
MiC IN
A /1
Mic IN
B /2
MiC SHIELD
3
F B 2
0 /4
F B 2
F B 1
E |5
F B 1
Out
OUt
R $ 2
F |6
R $ 2
R $ 1
HZ
R $ 1
SOLO/ CUE
J 8
SOLO/ CUE
K|9
LINE IN
L /10
LINE IN
BOOSTER AMP
Mi1
BOOSTER AMP
CH ON
N /12
CH ON
PHASE SwiTch
P /13
PHASE Sw TCH
OUTPut AMP
R/14
OUTPUT AMP
LEFT OUT
S /15
LEFT OUT
RIGHT OUT
T/16
RIGHT OUT
LINE MUTE CONTROL
U/17
MIC MUTE CONTROL
6
0
SOLO CONTROL
V 18
CONTROL COMMON
CH ON CONTROL
W 19
-25 VOLT
3 g
CONTROL COMMON
X12o
COMMON GROUND
+24 VOLT
Y721
+25 VOLT
CH ON LAMP
22
CHASSIS GROUND
8 1
Test CNNecioNs IN ReD
```

</details>

> Gentlemen,
>
> Thank you so much for your expertise. Dave, a write up by you would be very valued on my end. Can't wait to hear these things! Dave, when you say 'strapped' together, you mean jumpered, right? Tony, I hope Australia was awsome--I digg the accents on the weemin!
>
> Tom

— **Tommy P**, Jan 21, 2008|41

> Hi, Does the M461M have a black input transformer the same size as the one in the M460? I have a M461S manual which is a Stereo line amp that fits into the M461 slot the M461M might be a mono line level return only. The were used a lot in broadcast consoles where the only need a few microphones inputs for the announcer and one or two guest radio personalities the rest of the inputs were line level coming back from tape machines, CD players, Record player preamps and other line level sources. It has the same two Aux sends, Channel on lite but no input transformer or input preamp gain.
>
> Cheers, Dave Thomas www.aamicrophones.com

— **drtaudio**, Mar 4, 2008|41

> Hi Guys! My apolpgies! I have been away and haven't checked on this threat in a while! Dave, thank you for the info on the M461M. It looks just like the pic of the M461 on this site, except, like you said, it has two aux sends instead of the built-in filters. Yes, the M461M DOES have a black 'Hammond' labeled transformer nessled into its design. I agree the 'M' on it probably stands for 'mono' because i have NO pan switch. I do have a selector at the top that lets me select Mic 1, Mic 2 and Line. Do I understand your post correctly when you say it was mainly used for line level sources? It DID come from a broadcast console. All the documentation and the console frame itself was thrown out many years ago (quite disapointed about that). What can i do from here to get these pieces of audio history running?

— **Tommy P**, Apr 1, 2008|41

> http://wbsps.ca/forum/index.php?topic=667.0

— **kuzub**, Feb 16, 2013|46

## WBS M461M Hookup Diagram

_WBS RACKMOUNTING · Jan 15, 2010|43_

> Here is a wiring diagram for an M461M for a rack mount project.
>
> If anyone wants to comment on it make suggestions let me know.

— **kuzub**, Jan 15, 2010|43

![layout.png](PHOTOS/FORUM/2010%20-%20forum%20289%20-%20layout.png)

<details><summary>Text in the picture (OCR)</summary>

```
RZ
SWITCH
[ 0
M46IM For Dan
Ezoo 6200
Mic Ing
Mic In
Mic Shld
FBI Out
Line out
Line InG
Line
PE
-15 Fader Replacement
R5
220
0 8
Power Supply Comm
```

</details>

> Hi Tony,
> Except for reversing the 25+ and 25- it looks great. I hope so, as I just racked a pair of 461Ms and am sending this fellow your diagram. I wired them up with output off of 15 and 16 and there's just way too much signal. Even with the sens pot all the way down his protools was redlining.
> Thanks.
> Best,
> Tom

— **DrTom**, Feb 2, 2010|43

> ahhh yes, you're right about the swap

— **kuzub**, Feb 2, 2010|43

> http://wbsps.ca/forum/index.php?topic=667.0

— **kuzub**, Feb 16, 2013|46

## M461M schematic

_WBS TECHNICAL SUPPORT · Feb 15, 2013|46_

> You asked, I had, Warren scanned
>
> Please show support, donate.

— **kuzub**, Feb 15, 2013|46

_461-02-004.jpg_
_not kept: the file is not in the forum backups_

> Does NOT remotely look like me!!

— **warrenbeck**, Feb 17, 2013|46

> ? what do you mean

— **kuzub**, Feb 17, 2013|46

> My units just say M461. I ended looking at other schematics around these numbers and they all look somewhat similar. Is there a standard M461 schematic? I can't seem to find much info on it.

— **Santiago**, Feb 19, 2013|46

> it's exact same with different outputs and a different HP/LP filter
>
> oh so similar
>
> this should answer so many questions, if you have others please ask.

— **kuzub**, Feb 19, 2013|46

> The M461 is standard across all M461 modules - regardless of the suffix. The suffix typically denotes the option of a customer special routing. Largely they are all interchangeable, hot swappable, etc... just have to wire your console for the auxes/summing/RS/FB/PA etc...
>
> The ONLY exception to this is the M460M - it was designed after some whyning by the engineering department, and not by Dad. They did silly things to the switch, and routing. It can all be re-configured to be a normal M460 (straight through to and including LA for pin-outs not necessarily function). But after that headache all modules conformed to 1 consistent specification for its series.

— **warrenbeck**, Feb 20, 2013|46

> Thanks Anthony and Warren. I'm having to learn this board through basically trial and error. I've already started using it to cut drums and guitar tracks. I'm having a blast with it. I'd love any more history, pics or schematics on anything related to 1204 consoles. Heck, I'd love to find out who originally had this one!

— **Santiago**, Feb 20, 2013|46
