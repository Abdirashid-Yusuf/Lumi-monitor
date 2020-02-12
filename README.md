# Lumi-monitor

the goal is to create a system that mointors the baby while it is sleeping and also record the conditions of the room to ensure the baby gets comfortable sleep. 

### Build instruction for Lumi Monitor

### Table of contents
1) Parts 
These are the parts of the project. Make sure to have them before you can begin anything else 










[](Abdirashid-yusuf.github.io/lumiMonitor)
 
 the script to record 
#!/bin/bash
read -p "Please enter the file name: " filename
arecord -D plughw:1 -c1 -r 48000 -f S32_LE -t wav -V mono -v $filname
