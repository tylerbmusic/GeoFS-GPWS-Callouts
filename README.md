Installation process:\n
Step 1: Copy the contents of 'userscript.js' into your clipboard\n
Step 2: If you haven't already, download tapermonkey (https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo//Open)\n
Step 3: Press the Extensions icon on the toolbar at the top of your browser and click on the icon that looks like a rounded square with two eyes at the bottom, and press "Dashboard"\n
Step 4: Press the little "+" tab, and paste your clipboard contents into the big text box, and click "install".\n
Step 5: Open GeoFS, and it should work!\n
\n
If you _want_ to make your life _harder_, instead of following the installation process, bookmark the userscript.js file and each time you refresh or visit GeoFS, open the bookmark, copy the code, go to the GeoFS tab, press f12, Ctrl+Shift+I, or Cmd+Shift+I, and paste the code into the console.\n
\n
A couple of things to note:\n
For the minimums to work, you need to type in the **BAROMETRIC (MSL)** minimum altitude/desision height (without the -½) as defined at the bottom of the IFR approach plate.\n
For the Glideslope alarm to work, **you must be tuned into an ILS**.\n
For some of the callouts to work, you must be descending.\n
\n
Here is a list of all of the current callouts and their links, pasted directly from some lines of 'userscript.js':\n
    window.a2500 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/2500.wav');\n
    window.a2000 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/2000.wav');\n
    window.a1000 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/1000.wav');\n
    window.a500 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/500.wav');\n
    window.a400 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/400.wav');\n
    window.a300 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/300.wav');\n
    window.a200 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/200.wav');\n
    window.a100 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/100.wav');\n
    window.a50 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/50.wav');\n
    window.a40 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/40.wav');\n
    window.a30 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/30.wav');\n
    window.a20 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/20.wav');\n
    window.a10 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/10.wav');\n
    window.aRetard = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/retard.wav');\n
    window.a5 = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/5.wav');\n
    window.stall = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/stall.wav');\n
    window.glideSlope = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/glideslope.wav');\n
    window.tooLowFlaps = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/too-low_flaps.wav');\n
    window.tooLowGear = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/too-low_gear.wav');\n
    window.apDisconnect = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/ap-disconnect.wav');\n
    window.minimumBaro = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/minimum.wav');\n
    window.dontSink = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/dont-sink.wav');\n
    window.masterA = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/masterAlarm.wav');\n
    window.bankAngle = new Audio('https://tylerbmusic.github.io/GPWS-files_geofs/bank-angle.wav');
