# Scene Controller
The idea for this device is to provide the brains behind listening to sensor data and making decisions on what should happen to a scene.  There really isn't any specifications for this device as it is really about tying the devices together into a workflow.   

## Motion Play Next
This is a pretty simple scene controller.  It basically listens for motion sensor data and when motion is detected it will command a media player to play the next media item in a sequence.
* [Motion Play Next Media Item on a Raspberry Pi using Python](MotionPlayNext/RaspberryPi/)
* [Motion Play Next Media Item on a Raspberry Pi using Node-Red](MotionPlayNext/RaspberryPi/NodeRed.md)    

## Motion Play Video & Fogger
This is a more complex scene controller that involves a motion sensor, media player for videos and a fog machine.  
* [Motion Play Next & Fogger using Node-Red](MotionVideoAndFogger/NodeRed/)    

## Motion Skull Look Left or Right
This is a scene controller that involves motion sensors and a skeleton head that reacts to the motion.  
* [Motion Skull Look Left or Right using Node-Red](MotionSkull/NodeRed/)    

## Laugh Play Audio
This is a scene controller that involves monitoring the laugh message and playing audio clips.  
* [Laugh Play Audio using Node-Red](LaughPlayAudio/NodeRed/)