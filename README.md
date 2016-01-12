Candle Closing Time Remaining - (CCTR) [v3]
===========================================

Candle Closing Time Remaining (CCTR) is an indicator which displays the remaining time for an open candle to be closed.

Features
========

- Changeable color and size
- Changeable location (Corners)
- Display server time (on OR off) [v2]
- Play an alert sound when the candle is going to close [v3]
- Clean code


Installation
============

- Copy the `.mq4` file to indicators directory.
- Open the file in MetaEditor and compile it.
- Now you can see it on MetaTrader indicators list panel.

Usability Tips
==============

- You can change the location of display time, by setting the "location" Input field as follows:

- set location 'Top-Left' : To be displayed in comment in the top-left part of the chart. 
- set location 'Top-Right' : To be displayed in the top-right part of the chart.
- set location 'Bottom-Left' : To be displayed in the bottom-left part of the chart.
- set location 'Bottom-Right' : To be displayed in the bottom-right part of the chart.

- You can on or off server time displaying by setting "displayServerTime" as follows: [v2]

- set 'On' : display server time. 
- set 'Off' : don't display server time.

You can on or off alert sound playing by setting "playAlert" as follows: [v3]

- set 'On' : play a sound when candle is going to close in less than 5 seconds.
- set 'Off' : don't play sound.

Also you can set your favorite sound as alert by enter it's name on "customAlertSound": [v3]

- note that, the file must be located in terminal_directory\Sounds or its sub-directory. Only WAV files are played.  
- if you leave the field empty, the default sound will be played. 

Change log
==========

- display candle closing time remaining. [v1]
- adding an input field to display server time. [v2] 
- play an alert sound when the candle is going to close. [v3]
- change input types to readable strings. [v3]
- shorten the name of the indicator in comments area. [v3] 



Good luck with your trading ;)
