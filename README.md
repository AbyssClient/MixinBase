# MixinBase
Mixins client base for 1.8.9

# How to setup
Clone the repository into whatever folder you want (Mine is in my coding folder), open the project in Intellij IDEA then go to the gradle tab on the right
and run setupDecompWorkspace in the buid/forgegradle, once that's done run genIntellijRuns, when that's completed a run configuration
should pop-up named "Minecraft Client", copy the settings from the image below

Now you can start Minecraft!

![mixinrunconfig](https://github.com/AbyssClient/MixinBase/assets/170053471/d8248117-0cfe-42b2-87b5-3b9c58022c31)

# How to build
Run the "build" command in the gradle tab, there should be a new file in Mixin-Base/build/lib, keep that folder open for now,
now press Windows + R and type in %appdata%, this will open a folder called "Roaming", you'll see the .minecraft folder,
open it, now navigate over to the "versions" folder and make a new folder inside of this folder called whatever you want,
for me this will be "exampleclient-1.8.9", now copy and paste the 1.8.9.jar file from the 1.8.9 folder in the versions folder into
your newly created folder (exampleclient-1.8.9), then do the same thing but with the exampleclient-1.8.9.json file I've left
in this repository, you can rename this file to the name of your folder (also rename the .jar you pasted), now open the .json
file with whatever text editor you want to use and edit the id to be the name of your file, now edit the "name" under "libraries"
to say "net:example:exampleclient-1.8.9", then change the --tweakClass property to the path of your Tweaker class in the project,

