
	Space Invaders - recreated in java
	by Sean Godsell
	Date May 3, 2024
	License: GPL-2.0 license
	Please keep the authors name in all of this
	included source code.

	Have fun, and learn from this source code.  This
	game is compeletely written in java, which uses
	awt, swing, and JPanel, which is using double
	buffering graphics by default.

----------------------------------------------------------
To run the Space Invaders game, type in:
   jar -jar <path where jar is sitting/>Invaders.jar

The keys to control the game are the 'space bar', which
is the players fire laser key.  The cursor left, and 
cursor right keys, to move the player left and right.
There is a settings cog on the top, right of the screen.
You can control the number of alien rows, and columns,
which controls the # of aliens (space invaders) on the
screen.  You can also control the number of enemy shots
that are fired, as well as the number of player shots that
can be fired.  If you want to change something you have
all the code to this game as well, which is included
with in this jar file.

----------------------------------------------------------
To extract all of the sources, classes, images, and other
files, then extract this jar by using some kind of unzip
tool.  Find or create a blank directory or folder.  Then
extract all of the files in that directory or folder by
typing in the following command:
   unzip <path where jar is sitting/>Invaders.jar


----------------------------------------------------------
To build from the sources within this jar file, you will
need the JDK installed.  You also need to be in the src/ 
directory or folder.  The command(s) to build the 
Space Invaders game is:
   cd src
   javac -d ../ com/sgodsell/invaders/SpaceInvaders.java

This will build all of the class files in directory above
the src folder.  If there are no errors, then you can run
your build by using the folling command(s):
   cd ..
   java com.sgodsell.invaders.SpaceInvaders


----------------------------------------------------------
To re-build the Invaders.jar file, you must be in the 
directory/folder of where you extracted the Invaders.jar
files.  Next type in the following:
   jar --create --file Invaders-rb.jar \
       --main-class com.sgodsell.invaders.SpaceInvaders \
       README.txt com images src sounds

