Installation process:  
Step 1: Copy the contents of 'userscript.js' into your clipboard  
Step 2: If you haven't already, download Tampermonkey (https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo//Open)  
Step 3: Press the Extensions icon on the toolbar at the top of your browser and click on the icon that looks like a rounded square with two eyes at the bottom, and press "Dashboard"  
Step 4: Press the little "+" tab, delete everything in the big text box, paste your clipboard contents into that text box, and press Ctrl/Cmd + S to save it.  
Step 5: Open GeoFS, and it should work!  

Note: When installing Tampermonkey, you may need to enable Developer Mode inside of the browser's settings, and click "Allow User Scripts" in Tampermonkey's browser settings.  
  
Alternatively, instead of following the installation process, bookmark the userscript.js file and each time you refresh or visit GeoFS, open the bookmark, copy the code, go to the GeoFS tab, press f12, Ctrl+Shift+I, or Cmd+Shift+I, and paste the code into the console.  
  
A couple of things to note:  
For the minimums to work, you need to type in the **BAROMETRIC (MSL)** minimum altitude/desision height (without the -½) as defined at the bottom of the IFR approach plate.  
For the Glideslope alarm to work, **you must be tuned into an ILS**.  
For some of the callouts to work, you must be descending.  
  
Here is a list of all of the current callouts and their links, pasted directly from some lines of 'userscript.js':  
    window.a2500 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/2500.wav');  
    window.a2000 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/2000.wav');  
    window.a1000 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/1000.wav');  
    window.a500 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/500.wav');  
    window.a400 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/400.wav');  
    window.a300 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/300.wav');  
    window.a200 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/200.wav');  
    window.a100 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/100.wav');  
    window.a50 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/50.wav');  
    window.a40 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/40.wav');  
    window.a30 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/30.wav');  
    window.a20 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/20.wav');  
    window.a10 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/10.wav');  
    window.aRetard = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/retard.wav');  
    window.a5 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/5.wav');  
    window.stall = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/stall.wav');  
    window.glideSlope = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/glideslope.wav');  
    window.tooLowFlaps = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/too-low_flaps.wav');  
    window.tooLowGear = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/too-low_gear.wav');  
    window.apDisconnect = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/ap-disconnect.wav');  
    window.minimumBaro = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/minimum.wav');  
    window.dontSink = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/dont-sink.wav');  
    window.masterA = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/masterAlarm.wav');  
    window.bankAngle = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/bank-angle.wav');  
