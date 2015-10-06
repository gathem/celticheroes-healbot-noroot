This is a simple script which uses android debug bridge to simulate physical taps on the phone

This is set to work on a nexus 5. If you have any other phone, you will need to adjust the coordinates of the tabs. You can use developer mode tool "show tap locations" option to quickly find the coordinates of all the commands.

Installation:
sudo cp heal /usr/bin
sudo chmod 755 /usr/bin/heal
You must install android developer tools because it is simply using "adb shell input tab <x> <y>"

Usage: 
heal <tank player slot (1-7)> true|false (use natures breath)

What it does:
Ensures you haven't died --v
Targets the tank you specified --v
Casts natures touch --v
waits a couple seconds --v
Casts meditate
waits a few more seconds --v
Casts natures touch again --v
waits a few seconds
Casts natures breath (if enabled) --v
Repeats endlessly

What if it doesn't work?
Learn to code in bash and figure it out...
