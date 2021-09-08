# Space-Invador-Emulator
A take on the classic arcade game using MIPS Assembly language</br>

Difficulty Scaling</br>
	   -Every 5 enemies defeated, enemy move speed increases</br>
	   -Every 5 enemies defeated, enemy shot frequency increases</br>
	
Game Over Screens</br>
	   -Game over screens for each specific game over instance: no lives, no shots, no enemies</br>
	
	

Graphical glitch note:</br>
	It appears that on some occasions (generally when holding down b to fire),
	after an enemy is hit and destroyed, when the next bullet is fired from the 
	player a bullet appears on the left side of the screen and flies up until it
	is re-dealloc'd at the top of the screen. I did attempt to find the source of
	this many times, but was ultimately unable to. This has NO bearing or affect
	on gameplay whatsoever and is ultimately a harmless graphical glitch in regards
	to it changing anything about gameplay, but it does exist and I found it pertinent
	to note this in case of confusion.</br>
  
  Used MARS to run and play.
