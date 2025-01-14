# EMATM0054/53 Robotic Systems
Teaching materials for unit EMATM0054/53

# Navigating the Labsheets
The Labsheets provide some icons to help you navigate quickly.  

<img width="40px" src="https://raw.githubusercontent.com/paulodowd/EMATM0054_53/main/Images/theory.png" align="left"> This is a section that provides background theory for what we are about to work on.  You can complete the exercises without the theory, but you will be able to make smarter choices if you gain a deeper understanding first.
<br><br>
<img width="40px" src="https://raw.githubusercontent.com/paulodowd/EMATM0054_53/main/Images/stop.png" align="left"> This is a section that contains important information you must respect to avoid damaging the robot, or to stay within the requirements for your Assessments.
<br><br>
<img width="40px" src="https://raw.githubusercontent.com/paulodowd/EMATM0054_53/main/Images/tick.png" align="left"> This is a section that provides advice on best practice, or confirms what we have achieved so far.
<br><br>
<img width="40px" src="https://raw.githubusercontent.com/paulodowd/EMATM0054_53/main/Images/info.png" align="left"> This is a section that contains information on **common problems** or **common solutions**.  These are designed to help you to avoid common pitfalls (time spent inefficiently).
<br><br>
<img width="40px" src="https://raw.githubusercontent.com/paulodowd/EMATM0054_53/main/Images/exercise.png" align="left"> This is a section that contains **exercises**: you are expected to find solutions, usually by writing code.  If you are in a hurry, you can scan the labsheets to find these yellow icons.
<br><br>
<img width="40px" src="https://raw.githubusercontent.com/paulodowd/EMATM0054_53/main/Images/validate.png" align="left"> This is a section that guides you to validate and confirm the operation of your work.  This is an important practice in robotics.  Make sure your solutions are working as you expect them to!    
<br><br>
<img width="40px" src="https://raw.githubusercontent.com/paulodowd/EMATM0054_53/main/Images/observation.png" align="left"> This is a section that encourages you to observe, reflect and think about broader implications for the exercises we are completing.  This is important to develop a high level of familiarity with the robotic system, from which we can make more intelligent choices.
<br><br>
<img width="40px" src="https://raw.githubusercontent.com/paulodowd/EMATM0054_53/main/Images/hypothesis.png" align="left"> This is a section that asks you to make a prediction or theory, drawing on your knowledge and experience so far.  You will also want to consider how you could then observe and measure the effects.
<br><br>

# Pololu 3Pi+ Code Stub

The below Labsheets make extensive use of some incomplete template code provided for you under the `3Pi_CodeStub` directory above.  Alternatively, visit <a href="https://github.com/paulodowd/EMATM0054_53/tree/main/3Pi_CodeStub">this link</a>.

# Trouble Shooting (FAQ)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0054_53/blob/main/Labsheets/Core/TroubleShooting_FAQ.ipynb) **TroubleShooting/FAQ**:  Help for common problems, like **"my robot won't connect"** 

# Assessment 1 Labsheets
|  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    | Labsheet Title | Description |
|---------------|----------------|----------------|
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0054_53/blob/main/Labsheets/Core/L0_GettingStarted.ipynb) | **Labsheet 0:** Getting Started | Instructions on how to get started, and exercises with millis() for non-blocking code. |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0054_53/blob/main/Labsheets/Core/L1_Motors.ipynb) | **Labsheet 1**: Motors |  Exercises to get your robot moving, steps to be confident that your code will behave predictably, building up a Class.  Advanced Exercises include PID Control |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0054_53/blob/main/Labsheets/Core/L2_LineSensors.ipynb) | **Labsheet 2**: Line Sensors | Incremental Exerices to get the Line Sensors working, and to get your robot to stay within the coursework map.  |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0054_53/blob/main/Labsheets/Core/L3_Magnetometer.ipynb) | **Labsheet 3**: Magnetometer | Exercises to install and use a software library, to enable your robot to detect a magnet.  |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0054_53/blob/main/Labsheets/Core/L4_SystemIntegration.ipynb) | **Labsheet 4**: System Integration |  Exercises improve the structure of your code, as well exercises to develop precise movement to complete Assessment 1.  |

# Supplementary Labsheets
The following Labsheets are supplementary, and therefore are not considered necessary to complete Assessment 1.  You may find them more useful for Assessment 2.
|  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    | Labsheet Title | Description |
|---------------|----------------|----------------|
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0054_53/blob/main/Labsheets/Supp/SL0_MeasuringBatteryVoltage.ipynb) | **S. Labsheet 0:** Battery Measurement | Guidance on measuring the battery level of the 3Pi robot. |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0054_53/blob/main/Labsheets/Supp/SL1_InterruptsAndTimers.ipynb) | **S. Labsheet 1**: Interrupts |  Advanced exercises to utilise a timer for precision execution of code.  |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0054_53/blob/main/Labsheets/Supp/SL2_BumpSensors.ipynb) | **S. Labsheet 2**:  Bump Sensors | Guidance on using the Bump Sensors for collision detection or ambient light measurement.  |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0054_53/blob/main/Labsheets/Supp/SL3_InertialSensors.ipynb) | **S. Labsheet 3**: Inertial Sensors | Guidance on using the Accelerometer and Gyroscope sensors.  |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0054_53/blob/main/Labsheets/Supp/SL4_3Pi_Display.ipynb) | **S. Labsheet 4**: Display Module |  Guidance and examples of using the LCD or OLED display for the 3Pi robot.  |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0054_53/blob/main/Labsheets/Supp/SL5_ResultsOverSerial.ipynb) | **S. Labsheet 5**: Results over Serial |  Guiding on collecting measurements for experiments and reporting them over Serial.  |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0054_53/blob/main/Labsheets/Supp/SL6_PlottingResults.ipynb) | **S. Labsheet 6**: Plotting Results |  Guidance and examples on plotting using Python and Google Colab.  |

# Assessment 2 Projects

Your team will have been randomly assigned one of the below projects.  You can change your randomised project allocation by editing the Team Allocation Spreadsheet (link on Blackboard).  If you would like to propose your own project, please change the project number to 'p' in the Team Allocation spreadsheet.

|  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    | Project | Description |
|---------------|----------------|----------------|
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0054_53/blob/main/Labsheets/Projects/Project_1_Box_Pushing.ipynb) | **Project 1:** Box Pushing | Investigating Collaborative Box Pushing behaviour with multiple robots. |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0054_53/blob/main/Labsheets/Projects/Project_2_Leader_Follower.ipynb) | **Project 2**: Leader-Follower |  Investigating Path Formation and Control with Multiple Robots |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0054_53/blob/main/Labsheets/Projects/Project_3_GradientBasedPositionControl.ipynb) | **Project 3**: Gradient Based Position Control | Investigating Sensor Processing and it's effect on a Localisation Task.  |


