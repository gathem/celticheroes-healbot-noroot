<h1>What it is:</h1>
TL;DR:This is a simple script which uses android debug bridge to simulate physical taps on the phone
<br/><br/>
This is set to work on a nexus 5. If you have any other phone, you will need to adjust the coordinates of the taps.<br/>
<b>You can use developer mode tool "show tap locations" option to quickly find the coordinates of all the commands.</b><br/><br/>
The script runs on a computer, and sends commands over usb using Android debugging bridge (dev tools provided by Google).<br/>
<b>It does NOT require root to use.</b>
<br/>
<h1>Installation:</h1>
sudo cp heal /usr/bin<br/>
sudo chmod 755 /usr/bin/heal<br/>
You must install android developer tools because it is simply using "adb shell input tap <x> <y>"<br/>
<h1>Usage:</h1>
1.) plug a usb cable into a mac or linux computer<br/>
2.) make sure usb debugging is enabled on your phone (developer settings)<br/>
3.) from commandline:\>$ heal \<tank player slot (1-7)\> true|false (use natures breath)<br/>
<h1>What it does:</h1>
Ensures you haven't died --v<br/>
Targets the tank you specified --v<br/>
Casts natures touch --v<br/>
waits a couple seconds --v<br/>
Casts meditate<br/>
waits a few more seconds --v<br/>
Casts natures touch again --v<br/>
waits a few seconds<br/>
Casts natures breath (if enabled) --v<br/>
Repeats endlessly...<br/>
<br/>
<h1>What if it doesn't work?</h1>
Learn to code in bash and figure it out...
