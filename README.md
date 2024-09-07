Report on a True Autonomous Vehicle Solution
WRO Season 2023 Future Engineering
Our team, Driver US, developed an innovative autonomous vehicle by integrating a modified racing car model with a custom-built upper structure crafted from LEGO parts. Central to our design is the use of a Raspberry Pi, which serves as the vehicle's AI processing unit. We wrote a program utilizing machine learning and image recognition to train the vehicle, allowing it to familiarize itself with the competition environment. Through simulated trials, our AI system learned the nuances of navigating the course, identifying paths, obstacles, and making real-time decisions that mirror human control. This end-to-end machine learning approach enabled our LEGO Car to autonomously navigate and respond accurately within the competition arena.
August 30, 2024
Driver US Team presentation
Team Members: William Wu, Jiarui Hu, Yangxuezhe Sun
Coach: Fei Guo
William Wu: Team captain, an ambitious 10th-grade student from Rancho Cucamonga, California.  Skilled in computer programming and familiar with structural design, William contributed significantly to the vehicle’s coding and overall assembly.
Jiarui Hu: A 12th-grade student from Rancho Cucamonga, California.  Passionate about AI and robotics with a talent for 3D modeling. Jiarui played a key role in designing the AI components and optimizing the robot's performance.
Yangxuezhe Sun: An 11th-grade student from Rancho Cucamonga, California.  He is a dedicated coding enthusiast who led the hardware part of the solution, is skilled in fixing potential arising issues, and is experienced in machine learning and AI algorithm design.
Summary of our Project: A combination of a remote-controlled RC car base and a self-built Lego structure that shelters a battery, Raspberry Pi, and camera. The entire system is controlled by an AI component and can run autonomously on the game field. 
Technical Solution Design: The vehicle's control logic integrates data from sensors and steering to be processed by tensorflow AI and be trained to run autonomously through the game mat. Our design includes both a training portion where a teammate inputs running data into the robot, and it would memorize how a human would drive and mimic it. This approach combines hands-on engineering with sophisticated software, resulting in a highly adaptive and intelligent autonomous vehicle.
Communication Design: The handle communicates with the Raspberry Pi, and the Raspberry Pi communicates with the Robot car.
Control Logic Design:  The remote control system captures images and data from the simulated arena that we created, which are then used to design and train an advanced neural network model. During the competition, this AI-driven network activates, executing actions that replicate human control and transmitting precise commands to the robot for seamless performance. The robot enhances these movements through secondary control, using gyro sensors and an AI camera to validate and refine its decisions in real time, optimizing starts, stops, and custom maneuvers for maximum impact.
AI Software code design: Capture photos and gather data using web-based remote monitoring, allowing our AI neural network to process and train on the collected information for enhanced precision. In real-time, the neural network analyzes video feeds to predict the robot's next moves. These predictions are then transmitted to our robot, which receives the data and executes the actions seamlessly, showcasing the AI's decision-making on the field.
Overall Technical Solution Design:  To solve the problem of our robot not knowing how to park, we developed a custom control code using TensorFlow that guides the vehicle into designated parking areas after completing both the free run and obstacle courses. This program ensures precise maneuvers, enabling the robot to park accurately, meeting the specific competition requirements.  Our autonomous vehicle features a modified RC car base with manually upgraded wheels for enhanced stability and performance, topped with a custom LEGO-built upper structure for flexibility and easy modifications. The system is driven by a Raspberry Pi, which handles AI processing and control tasks. Utilizing TensorFlow, we trained a Convolutional Neural Network (CNN) on images and data from the playing field, allowing the robot to learn navigation patterns and make real-time decisions autonomously.  We integrated a web-based remote monitoring system to capture and analyze data during runs, continuously improving the AI model’s performance. Gyro sensors and a PIXY2 AI camera provide secondary control, verifying AI predictions and ensuring precise actions. This combination of manual enhancements, sophisticated AI programming with TensorFlow, and real-time sensor feedback creates a highly adaptive and intelligent vehicle capable of overcoming complex challenges, including precise parking maneuvers.
Mobility Management:
The modified RC car base offers a stable platform, while the upgraded wheels provide improved maneuverability on varied surfaces. This setup ensures that the vehicle maintains control and stability during complex maneuvers, such as obstacle avoidance and parking.
AI Control and Neural Network Integration:
We utilized TensorFlow to develop a Convolutional Neural Network (CNN) that trains on images and data from the competition environment. This AI model allows the vehicle to recognize paths, obstacles, and designated areas, making autonomous decisions based on real-time data. The network learns from recorded control data and continuously refines its predictions, enabling the robot to mimic human driving behavior effectively.
Obstacle and Parking Management:
To tackle the challenge of autonomous parking, we programmed a custom code that guides the robot into designated areas after completing runs. The vehicle uses live data from sensors and the AI model to make precise adjustments, allowing it to park accurately. This solution is crucial for completing competition tasks that require specific end positioning.
Power and Sensor Management:
The Raspberry Pi powers the AI operations and communicates with the vehicle’s control systems. Gyro sensors and a PIXY2 AI camera validate the AI's decisions, providing additional data points that refine the vehicle’s movements. These sensors enhance the robot's accuracy in navigation and obstacle management, ensuring a reliable performance throughout the competition.
Web-Based Remote Monitoring and Continuous Learning:
A web-based remote monitoring system captures and analyzes data in real time, offering insights into the robot’s performance. This system plays a key role in refining the AI model, enabling continuous learning and adjustments to improve the vehicle’s accuracy and efficiency.
Conclusion:
Our technical design successfully integrates hardware enhancements, sophisticated AI programming with TensorFlow, and real-time sensor feedback to create an autonomous vehicle capable of complex navigation and precise control. The result is a highly responsive robot that meets the demanding challenges of autonomous driving competitions.






