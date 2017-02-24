Playing around with the SystemHotkey package and pyautogui in preparation for
my total conversion of my PROJECT-JARVIS repo to python. Made some interesting 
drawing functions while getting familiar with pyautogui and SystemHotkey.

Usage:

1. Open MS Paint (if you have multiple monitors, open it on your main one).
2. I like to fill the background with a black color before I get started, but that's my personal preference.
3. Run pag_plus_syshk.py from IDLE 3.6.0.
4. Let go of the mouse, sit back and watch some colorful and random things get created!
5. I usually clear the canvas after each run, but again that's up to you!

Notes: 
* If it starts going berserk, press Ctrl+X to abort (That's what systemhotkey is for!)
* You'll need the .png files in the same location as pag_plus_syshk.py, pyautogui uses those images to locate the brush and select menu on screen.
* You'll need to abort (Ctrl+X) before re-running each time. This is because systemhotkey continues to run in the background and listen for hotkeys.

Try toying around with some of the values, particularly in the functions like 
drawModified that incorporate an element of randomness.

Enjoy!
