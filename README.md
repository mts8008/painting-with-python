![Alt text](RandomWebPaint.jpg?raw=true)
Playing around with the SystemHotkey package and pyautogui in preparation for my full conversion of my Project-JARVIS project to python. Ended up making some interesting recursive drawing functions while getting familiar with pyautogui and SystemHotkey.

Usage:

1. Open MS Paint (if you have multiple monitors, open it on your main one).
2. I like to fill the background with a black color before I get started, but that's my personal preference.
3. Run pag_plus_syshk.py from IDLE 3.6.0.
4. Let go of the mouse, sit back and watch some colorful and random things get created!
5. I usually clear the canvas after each run, but again that's up to you!

Notes: 
* If it starts going berserk, press Ctrl+X to abort (That's what systemhotkey is for!)
* If your monitor is not 1920 x 1080, or if you have customized your paint toolbar this most likely will not work well. I've included another function that uses systemhotkey to help you locate things on-screen. Move the mouse over what you want (with the script running), and press Ctrl+F to print the x,y coordinates of your mouse. This should be helpful if you need to make nay changes.
* You'll need the .png files in the same location as pag_plus_syshk.py, pyautogui uses those images to locate the brush and select menu on screen.
* You'll need to abort (Ctrl+X) before re-running each time. This is because systemhotkey continues to run in the background and listen for hotkeys.

Try toying around with some of the values, particularly in the functions like 
drawModified that incorporate an element of randomness.

Enjoy!
