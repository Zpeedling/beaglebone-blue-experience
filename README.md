# My BeagleBone Blue Experience
Content that helped me on my experience with the BeagleBone Blue (BBBL)

Since my experience learning to use the BeagleBone Blue (will be referred as BBBL from now on) wasn't that smooth, and quite difficult. It's my objective to create here a tutorial-like guide on the usage of this powerful board, perfect for robotics applications by the way.
This will also be my first experience with github, so I'm open to suggestions for improving this repository and I may take a little while to finish this project.
Cheers!

## Introduction - What is BeagleBone?
The beagles are "tiny open-hardware, open-software computers at low-cost, community-supported development platform for developers and hobbyists" ([Reference]( https://beagleboard.org/)). But I think you already knew this since you search for this and end up here.
There are different board types according to their porpuse. For example, the BeagleBone Black (BBB) is the base of all beagles, this one is for general porpuse. The BeagleBone Green (BBG) is based on the BBB and developed for SeedStudio making it easier to connect to the large family of Grove sensors (don't really know much about it).
The BeagleBone Blue (BBBL) is designed as the BBB with the robotics cape all in a single board, and of course, is meant for robotics applications.
Refer to this [site](https://beagleboard.org/blue) for official information on the BBBL. There's also a good video for setting it up that you can check [here](https://youtu.be/pTpUMajQS_U).

On practice you can just grab an SD card and load an OS image onto it and plug it on the beagle, conect via USB with it and start programming like in the video above.
But I was a little lost facing the interactions with my BBBL, so I'll go step by step and explaining things a little more deeply so everyone can understand what's going on.
Let's begin.

## BeagleBone Blue Specifications
...
### This is a test
This is a test `this is a test` this is a test
```
this is also a test
```

## How to setup ROS with python 3
[Reference](https://medium.com/@beta_b0t/how-to-setup-ros-with-python-3-44a69ca36674)
Open bash and run the following commands
```
sudo apt-get install python3-pip python3-yaml
sudo pip3 install rospkg catkin_pkg
```
And that's it.
