# SCORBOT-kinematics
Forward/inverse kinematics computation for a SCORBOT robot.

🇮🇹 _Files originali in **italiano** nella cartella ["it"](https://github.com/massimostanzione/SCORBOT-kinematics/it) - Original files, written in italian, are into  the ["it"](https://github.com/massimostanzione/SCORBOT-kinematics/it) subfolder._

### What is it
This repository consists of two simple *Mathematica* notebooks I wrote and used in practical activities while following the "Automazione e Robotica con Laboratorio" (12 CFU) course, held at Faculty of Engineering, University of Rome Tor Vergata.

These two files can be used to compute [forward](https://en.wikipedia.org/wiki/Forward_kinematics "Forward Kinematics - Wikipedia") and [inverse (backward)](https://en.wikipedia.org/wiki/Inverse_kinematics "Inverse (backward) Kinematics - Wikipedia") kinematics of a SCORBOT robot, as follows:
- `SCORBOT_forward.nb`: given the fixed physical parameters of the robot and its joint variables, compute the position of the end-effector (cartesian coordinates);
- `SCORBOT_inverse.nb`: given the fixed physical parameters of the robot, the desired cartesian coordinates for the end-effector, the roll angle and the pitch angle, compute the joint variables to obtain the desired coordinates/angles.

| File  | Input   | Output  |
| ------------ | ------------ | ------------ |
| `SCORBOT_forward.nb`  |<ul><li>Fixed Physical parameters</li><li>Joint variables</li></ul> |Position of the end-effector (cartesian coordinates)   |
| `SCORBOT_inverse.nb`  |<ul><li>Fixed Physical parameters</li><li>Desired cartesian coordinates for the end-effector</li><li>Desired Roll angle</li><li>Desired Pitch angle</li></ul> |Joint variables|

### How to use
Download the repository and open the files with Wolfram Mathematica. Further instruction on how to use them are written into the files themselves.

### Contribute!
Feel free to [open an Issue](https://github.com/massimostanzione/SCORBOT-kinematics/issues/new/choose "open an Issue") for any kind of fix/improvement/reporting/suggestion/etc.

### Platforms
Tested on:
- Wolfram Mathematica 12.0.0.0 for Linux x86 on Debian GNU/Linux 9 (stretch).
- ... add yours!

### Author
Massimo Stanzione</br>
http://github.com/massimostanzione

### Miscellaneous
Some fun with SCORBOT at University of Rome Tor Vergata:
- [SCORBOT making moka](https://www.youtube.com/watch?v=qyYn6U0nG7g)
- [Netturbot](https://www.youtube.com/watch?v=M9mwUqvYef4)
- [Hanoi tower](https://www.youtube.com/watch?v=0VCJ6IQ05f8)

