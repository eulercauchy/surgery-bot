# surgery-bot
A method for training, programming, and testing a surgery robot for use on human anatomy.
______________________________________

The purpose of this repository is to make a training simulator to design a robot to perform surgery on human anatomy.  We will start with a good enough approach, just get something working.  Then refine, test, refine.
______________________________________
The current approach is as follows:
Create virtual environment for testing and creation of training data for a ML algorithm to identify organs positions and poses.

It is expected to use Unreal Engine 5 as the visualization engine.

Behavior trees and ROS2 for the control of the Robot.

This seems like the easiest by far place to start, they even have a unity project.
https://github.com/Z-Anatomy/Models-of-human-anatomy

and unity has a great ML data package
https://github.com/Unity-Technologies/ml-agents
to train agents
and 
https://docs.unity3d.com/Packages/com.unity.perception@1.0/manual/index.html
to create labelled ML data
also possible of using
https://github.com/pyushkevich/itksnap
for a segmentation algorithm.
