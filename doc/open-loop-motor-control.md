\#B37VB Motor Speed Test (Jonathon and Zac)

\##Introduction

The aim of this experiment was to change the source code of an Arduino buggy to change the speeds of it and record the speed it actually travelled. The other aim was to demonstrate the ability to work with markdown files and git repositories, building the skills needed for the course.



\##Table of Results



|PWM (L) |PWM (R) |Speed (m/s)|

|--------|--------|-----------|

|215     |175     |0.21       |

|140     |100     |0.12       |

|112     |152     |0.14       |



\##Challenges

The robots right wheel was off axis so when completing a full rotation the robot would veer to the left, to circumvent this the left wheel was given more power to balance it out and make it travel in as straight of a line as possible. This took trial and error to work out.



\##Conclusion

This test proves that open loop control is not ideal in this use case as the real life conditions aren't ideal and so the buggy doesnt perform as theoretically expectected. It is alzso impractical to constantly have to manually adjust the buggy motor speeds each time and then test if it goes straight as opposed to having a system that takes feedback and adjusts motor speed automatically

