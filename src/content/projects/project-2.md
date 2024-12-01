---
title: BearBotX - Project with an MBot
description: An application that lets you control an Mbot and displays its behaviour on a website
publishDate: 'Oct 2 2023'
seo:
  image:
    src: '/bearbot.png'
    alt: Project preview
---
 
![Project preview](/bearbot.png)
 
**Project Overview:**
The MBot project involves developing a robot system capable of performing various autonomous tasks. The primary functionality of the system includes line following, remote control, and obstacle avoidance. The application interacts with the MBot to control its behavior, enabling users to select different modes for controlling the robot’s actions. The project was designed to provide a practical and interactive way to control and manage the robot in real-time.
 
## Objectives
 
1. Enable the MBot to autonomously follow a black line on a white surface.
2. Develop a remote control mode allowing users to manually steer the MBot using a virtual interface.
3. Implement obstacle avoidance functionality to prevent the robot from colliding with walls.
 
## Features
 
1. **Line Following:**
   - The MBot follows a black line on a white surface.
   - Users can activate the “Line Following” mode, which uses the RGB sensor to detect the line and guide the robot along it.
   - The MBot stops when switched back to normal mode.
 
2. **Remote Control:**
   - The user selects the “Remote Control” mode and chooses a nearby MBot to control.
   - A virtual interface is provided with directional buttons to manually steer the robot.
   - The user can control the robot's movement in real-time and adjust speed as needed.
 
3. **Obstacle Avoidance:**
   - The MBot operates in “Safety Mode,” where it prevents collisions with obstacles.
   - If the MBot detects an obstacle (wall) in its path, it stops and reverses slightly to avoid it.
 
## Technology Stack
 
- **Frontend:** Developed using HTML, CSS, JavaScript with Angular for dynamic web interfaces.
- **Backend:** Integration with a Spring Boot server to handle communication between the application and the MBot.
- **Sensors & Actuators:** The MBot uses RGB sensors for line following, ultrasonic sensors for obstacle detection, and motors for movement control.
- **Mobile App:** The application can be accessed on various platforms, including iOS and Android.
 
## Project Planning
 
The project is being developed using Agile methodologies, and the team is divided into frontend and backend developers. Key milestones include user interface development, integration of sensor and motor controls, and testing phases. The project will use Scrum methodology for continuous development and refinement.
 
## Outcome
 
The MBot project successfully demonstrates how robots can be controlled via web applications, with various modes such as line following, remote control, and obstacle avoidance. The system is designed to be user-friendly, scalable, and secure, providing an engaging and interactive experience for robot enthusiasts and developers.
 
## GitHub Repository:
 
The project's code and development progress can be found on GitHub: [BearBotX Repo](https://github.com/BernhardPirchner/BearBotX)
 
**Note:** This case study outlines the goals and features of the MBot project, showcasing the integration of sensors and backend systems for robotic control.