TrackIR for Some source games.
===================



I never said it is supposed to work, it's just a WIP project.
To make it work, you'll need a dev license (dev.dat).


##Disclamer
The patch are here, but for some reasons the build is not meant to support it, i don't really know...
I'll keep working on it soon.


##How to patch the game yourself


####Requirements :
-IDA Pro (With decompiler if you can't ASM)
-A brain


Open the client.dll of the source game you want.
Wait for it to disassemble.
Then search for text : "HL2-Track"

Is no result, you will not be able to patch it.

If you got a result, you should have this :


![Screenshot](http://puu.sh/kdalb/a9ae25bee3.png)


The first function call is the one we want to patch.

So go to it and patch it;

Here is how it looks when it's patched:

![Screenshot](http://puu.sh/kdahd/c61894431b.png)








##File name structure


game_filename_status.extentions


You'll just have to remplace the originale filename by the one you can find on the repo.

Portal 2
differ: char 3607633, line 8609 is 260 M-0  62 2



##More infos

Few years ago (4-5-6?), even before VR with Oculus Rift, Valve used NaturalPoint products (TrackIR and the one which work with the eye movement) for experiments of alternative control in Portal 2.

Then the updated engine with TrackIR code parts was released with AlienSwarm.


Games without TrackIR code :

CSGO
TF2
