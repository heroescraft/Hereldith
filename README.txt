 | |  | |                      | |     | | (_) | |   | |    
 | |__| |   ___   _ __    ___  | |   __| |  _  | |_  | |__  
 |  __  |  / _ \ | '__|  / _ \ | |  / _` | | | | __| | '_ \ 
 | |  | | |  __/ | |    |  __/ | | | (_| | | | | |_  | | | |
 |_|  |_|  \___| |_|     \___| |_|  \__,_| |_|  \__| |_| |_|

Hello and welcome to Hereldith, I have some important notes for you on
how to play, and WHY you might see your anti-virus screaming that is this
a virus. So please read ALL of this because it is very important.

This program is safe:
	Ok, so why does Windows think this is malware? Because Hereldith's code
	frequently uses a os (Python library) method called "system". This method 
	exists in other programming languages, and all it does is run cmd prompt/terminal
	commands. I ONLY use system to clear (cls) the cmd prompt's (In this case, it's
	Hereldith's) screen .
	Why do anti-virus softwares not like system? Because giving exe files access
	to the cmd prompt allows them to pretty much do anything on a device. They could
	edit the registry (Which doing that can totally ruin one's system), and do other
	malicious things. This is why you should NEVER run random exe files.

	If right now you don't trust my credibility, you can either review Hereldith's 
	source code and run that ()
	or just begone with Hereldith.

On with the game:
	Hereldith currently doesn't have much player help with the "controls". That is
	the second perpose of this file. First of all, if you ever want to quit quickly
	just use to keybind: CTRL+c. (NOTE: If you have text highlighted it will instead
	of quitting, copy the highlighted text to your clipboard.)

	Main Menu:
		new: Creates a new character.
		load: Loads a current character, if you don't have any it will bring you
	back to main menu.
		quit: quits the program
	In Game:
		travel <place>: Travels to the specified town. Note: you may only go
	to towns that have a road leading to them. In the GUI there is a list of
	roads you may travel on. Also just "travel" works as a command.
		use <item>: Uses the specified item.
		shop <shop>: Goes to the specified shop. The list of shops in your current
	location will tell you
		quit: quits the program.