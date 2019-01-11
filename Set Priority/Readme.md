# This folder contains the changes done to set the priority on diffrent type of packets.

In our case we are using multiple type of diffrent messages to be transferred such as Text File , Image File , Audio File
and Video File 

All these file having diffrent properties such as diffrent size and diffrent preferences . so we want to make the transferring
of messages in some order so that we can increase the packet delivery stats. 
In a network their may be a case that only video file are transferring and image and text messages are just starving. To solve
this problem we have implement a priority base implementation in our system.

So that first text files will be transferred then image -> audio -> video .

To implement this changes we have to make some changes in these two file 

# Requirements:
    1.One Simulator.
    2.Basic Knowledge of JAVA.

# Steps to Install this system in existing One Simulator
    1. Replace these two files with old files in existing One simulator.
    2. Run One.bat file
