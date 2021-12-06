# Joystick

Joystick Logitech F710 configuration

![F710-Top](images/joystick/F710-top.jpg)
![F710-Top](images/joystick/F710-rear.jpg)

### Please Note: **F710** works on ROS in **Xinput** (Select letter X)

## Configuration

Buttons (Reference number with ros joy topic):

 - [0] **A**     - Enable drive
 - [1] **B**     - Enable **turbo** drive
 - [2] **X**     - 
 - [3] **Y**     - Emergency button (Stop roboteq board)
 
 - [4] **LB**    - Start/Stop song
 - [5] **RB**    - Next song
 
 - [6] **Back**  - Speech button
 - [7] **Start** - Enable/Disable Audio
 
 - [8] **LJ**    - 
 - [9] **RJ**    - 

All Configuration are in:
* [panther_control] [config/teleop.yaml](https://github.com/rpanther/panther/blob/master/panther_control/config/teleop.yaml)
* [panther_joystick] [config/joystick.yaml](https://github.com/rpanther/panther_hardware/blob/master/panther_joystick/config/joystick.yaml)

 
 [panther_control]: https://github.com/rpanther/panther/tree/master/panther_control
 [panther_joystick]: https://github.com/rpanther/panther_hardware/tree/master/panther_joystick
