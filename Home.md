
# Lab 8 - There’s an App for That: App Development

# By: Lily Schlaug and Noah Lane  
# Summary
The goal of this lab was to serve as an introduction to block coding and use it to communicate with the Arduino. A robot was built by using materials in the Sparkfun Inventor's kit. Some code from a previous lab was reused to program movements of the motors. Our app was developed using MIT App Inventor program. Once the app was designed, desired instructions were sent to the robot through the app. 

# Materials  
1 x Computer running Arduino IDE  
1 x Computer with MIT App Inventor installed  
1 x Bluetooth HC-05 module 
   
***SparkFun Inventor’s kit:***   
1 x RedBoard  
1 x Ultrasonic sensor  
2 x Motors  
1 x Motor Driver  
2 x wheels  
1 x AA battery pack  
1 x paper clip  
1 x command strip    
# Assembly Procedures
**Part 1**
1. Begin with the circuit from Lab 6
2. Attach the provided wheels to the motors
3. Mount the motors using command strips underneath the Arduino
4. Mount the battery back using command strips under the Arduino
5. Attach paper clip to the back of the plate to prevent the battery from dragging on the ground   
![image](https://github.com/npla225/BAE305-SP24-Lab8/assets/156371043/b7e2982f-91c6-4f99-9d8d-bba99cd70b05)
_Figure 1: Circuit diagram for 5C-Autonomous Robot, Sparkfun inventors kit_  

**Part 2**
1. Download and install the MIT App Inventor software following the prelab instructions
2. Integrate the HC-05 module into the circuit from part 1 as shown in Figure 2  
![image](https://github.com/npla225/BAE305-SP24-Lab8/assets/156371043/e854272a-f8eb-46db-9e41-d8038055443d)
_Figure 2: Circuit diagram for Bluetooth HC-05 module_

# Test Equipment
Carlos' Android Phone
# Test Procedures  
**Part 1**  
1. In the MIT App Inventor Designer add the following components shown in Figure 3
2. Switch to the Block viewer and build the block code shown in Figure 4
3. Export the code to Carlos' phone

![Screenshot 2024-03-05 121151](https://github.com/npla225/BAE305-SP24-Lab8/assets/156371043/37b9fa8f-ceab-4cee-87c1-b3fa0babbd90)
_Figure 3: App designer layout for Part 1_

![blocks](https://github.com/npla225/BAE305-SP24-Lab8/assets/156371043/eecc9c7f-635e-4ee4-81de-25efd3fb487d)  
_Figure 4: Block code for Part 1_  
**Part 2**

1. In the MIT App Inventor Designer add the following components shown in Figure 5
2. Switch to the Block viewer and build the block code shown in Figure 6
3. Export the code to Carlos' phone  
![image](https://github.com/npla225/BAE305-SP24-Lab8/assets/156371043/7281bd92-46b1-49d5-ab23-3326599977c4)
_Figure 5: App designer layout for Part 2_  
![blocks (1)](https://github.com/npla225/BAE305-SP24-Lab8/assets/156371043/54337340-5f79-41f1-9b1f-03371d2520da)  
_Figure 6: Block code for Part 2_  

# Test Results    
**Part 1 - Assemble and test your robot**    
The result of part 1 is the built robot. We use the code from lab 6 to ensure that robot is able to move forward, backward, left and right at various speeds.    
![image](https://github.com/npla225/BAE305-SP24-Lab8/assets/156371115/cf0a69de-1d84-49e4-ba41-19b466ec758f)

**Part 2 - Develop the App** 
The result of part 2 is to be able to control the robot via the created app. The app should have commands to connect serial communications, move desired direction, and stop the robot's movement. 

**Part 3 - Wireless remote** 
Part 3 takes the app from part 2 and develops it for wireless bluetooth communication. It also requires editing the ardunio IDE code to receive the communication from the correct ports. The final result should move the robot through bluetooth communication from the app.    

# Discussion    
Part 1 - Assemble and test your robot    
Discussion Questions: In Lab 6 we found out what was the minimum speed that will move the motors. What is the minimum speed that will move the complete car?    
- The minimum speed to move the robot in this lab was 50. This is higher than in lab 6 because of the increased weight that the motors are required to move.    

# Conclusion
To conclude, this lab's purpose was to understand how we can create a simple app to communicate instructions to a robot. For this lab, we built a robot and aimed to provide it with instructions for movement through a few different methods. First, we verified that the robot moved based on the Arduino IDE code from lab 6. Next, we created an app through MIT App Inventor. This allowed us to build a simple app using block commands and upload it to a phone. This app provided the desired direction of movement and a stop command. Finally, we made changes to the circuitry and app to allow for bluetooth communication through commands in the app. Commands for the robot remained the same, but the means of communication to the robot was wireless. 

# Refrences 
**Figure 1**   
JOEL_E_B. “Sparkfun Inventor’s Kit Experiment Guide - v4.0.” SparkFun Inventor’s Kit Experiment Guide - v4.0 - SparkFun Learn, learn.sparkfun.com/tutorials/sparkfun-inventors-kit-experiment-guide---v40/circuit-5c-autonomous-robot. Accessed 5 Mar. 2024.  
**Figure 2**  
“Setting up Bluetooth HC-05 with Arduino - Tutorials.” Explore Embedded, exploreembedded.com/wiki/Setting_up_Bluetooth_HC-05_with_Arduino. Accessed 5 Mar. 2024. 