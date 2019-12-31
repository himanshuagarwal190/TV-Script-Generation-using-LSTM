# TV Script Generator

The data consists of scripts from a TV show called Simpsons. The network was trained on this data to generate new scripts. An initial
seed sentence is required to build script on top of it.

Some scripts generated: (LSTM's takes a lot of time for training, but even when it was trained for few epochs the results were 
interesting, like it was able to figure out it was dialogue script and putting full stops and exclamations at the end of the sentences)

 Results

10 Epochs, temperature=0.2:

as the two-slit experiment has shown of my friends.
moe_szyslak: (sings) what's the bar to the beer.
moe_szyslak: (sobs) now i don't want to see many of a freety and i want to get the bar to be my friend.
moe_szyslak: (singing) oh, i don't be name is a man a for the beer.
moe_szyslak: (singing) oh, that's the bar.
moe_szyslak: (sings) i got a hand of the said to the beer.
moe_szyslak: (singing) oh yeah, i can't get the bar. (sighs) oh, that's the bar the bar the bar to me.
moe_szyslak: (singing) hey, hey, hey, hey, hey, hey, hey,

10 Epochs, temperature=0.7:

as the two-slit experiment has shown-tive in the pretty to hold you one didchind here exper in this gares.
homer_simpson: (chuckly) i wall me house a cootoue money little grank and for there to you of the too homer day homer.
lenny_leonard: homer, you do you to par booksely woo how 'cause you conver.
moe_szyslak: hey, homer, what's the strapers.
homer_simpson: ....
carl_carlson: she monnt it's pros of never with curenter the flow you and the flear and when you have been something here.
homer_simpson: (prounds regor canchar to sall

10 Epochs, temperature=1:

as the two-slit experiment has shownardly? it's joth.
moe_szyslak: yeah, i read too homer!
homer_simpson: ohthoh. be walaterseal.


prowds: yell, there's. we have alimerian rapally lenny you are say on the cland. we deep cliin of could kisial?
moe_szyslak: pelt?
moe_szyslak: patchine seech bute. i'd qraint alova?
ape_mak_joevebon: you dunger sexsarffally. we beer armies!
moe_szyslak: it's einatery two pieding chance.
corley: that possich differ you a wondlet (necvoused!
moe_szyslak: moe, there's gofthis hasply chanta (confestefive

20 Epochs, temperature=0.2

as the two-slit experiment has shown the best drink the bar that a thing a beer.
moe_szyslak: (singing) i want to say the bar that see a beer.
moe_szyslak: (singing) i don't want to see a man a back and the bartender secret of the too the bar love that see the poor and the bar that a minute.
moe_szyslak: (sighs) hey, hey, i want to tell you and the beer with me.
moe_szyslak: (confing and self) i can't be so beer to the bartender and the bar that to make a money to the bartender that in the wallan says a bar that a buy the secret a

20 Epochs, temperature=0.7

as the two-slit experiment has shown to the bar?
moe_szyslak: yeah, i love you to shouldn have to pen the car on the eity course i got tooked was a blumble.
stillwater: you got the pooz.
lenny_leonard: you kneeg a little god here chumes.
homer_simpson: (worrice) "bellon--po name. (beat) what am i gorna god!
moe_szyslak: (into homer) homer, we're alway / we got the once arvestane. (pleass girls) i let you stupid to could you think i'm not say right. these of sold the would never be a lothers help to two the jraces game with a speci

20 Epochs, temperature=0.2

as the two-slit experiment has shown.
bar_ra_bad any: i did the poot a bicks. too promocs of felmar little "cance after off end it!
homer_simpson: (napamly) food is sure the swell) you haven kermanthe he's file small kinds on the alwonch to the outss. i thank right till joy, you heard that for yaks the exp.
homer_simpson: this is donswes-hilg now look just laugh, here'se wartle pennable.
marge_simpson: (wishing up to my problemping that on a douph pen-tho festing like twan's boy? o'lloct with keep ofd never the tratent fan't did, 
