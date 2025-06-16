<h1>SafeBeat Infant Monitor Project Demo</h1>

![IMG_6599](https://github.com/user-attachments/assets/92e2d65f-38a3-49ac-b8c4-8109ac2d33a9)

![IMG_6600](https://github.com/user-attachments/assets/5f265e5f-b9a4-4ade-b045-66f7205e2f82)

<h2>Description</h2>
<p>
This project was undertaken by me and four other team members and served as our capstone project for Texas A&M University.  
I want to emphasize the fact that this project was a collaborative effort, with all work shared by my team members: Aaradanaa Sabitha Mohan, Venkata Sai Kotrike, Jonathan Zheng, and Anthony Dinh.  
Our technical advisor is Dr. Lee Hudson, and our project sponsor is Dr. Logan Porter.  
<br>
<br>
With that said, the project is an embedded project primarily centered around a biomedical engineering application and embedded software development.  
The goal of the project is to measure Electrocardiogram (ECG/EKG) and Respiratory Rate for the purpose of monitoring sleep apnea in infants.  
These measurements are used in a monitoring system that displays real-time data of recorded biometrics and alerts parents if a sleep apnea event occurs.  
The project structure is divided into two discrete components: the monitoring belt and the control box.  
<br>
<br>
The belt will measure data and transmit it to the control box, while the control box will store and display the data, handle user input, and monitor the alarm system.  
Currently, real measurements on a human subject are not planned and are considered outside the project scope; this project serves as a prototype and working concept.  
Even though the final product will not be tested on a person, we will simulate the device's functionality through simulated input ECG and Respiratory Rate.  
<br>
<br>
NOTE: The project was completed in May of 2025, and we won the second place prize in competition with over 30 other teams in our major. The "code" in this repo will contain some project contents to look at if interested. Keep in mind that all work was shared between the team members stated above. 
</p>

<h2>Lessons Learned</h2>
<p>
  This team project lasted over the course of about 8 months, and posed significant challenges with timeline and resource management. 
  At the start of this project we had high hopes but were limited in development time for the project.
  Despite this, we were able to meet all deliverables besides one for the project. 
  The deliverables included: full software development for both components, a working display to function as a user interface, and custom PCB design.
  The only deliverable for the project that we fell short on was the custom PCB design. 
  This was due to a few different challenges, but as a team decision we switched from a custom PCB to a launchpad focused protoboard design for the hardware components.
  The design choice to use the TI launchpad allowed us to complete the project, with just a larger physicsl footprint.
  Through this project I further developed team skills, leadership, RTOS & Embedded development skills in C, and other fundamental eningeering project skills.
  This project was a wonderful experience and truly was the culmination of many years of work at university.
</p>

<h2>Project Structure</h2>
<p align="center">
Conceptual Block Diagram <br/>
<img src=https://i.imgur.com/H2JbNeu.png height="80%" width="80%" alt="Login Screen"/>

<h2>Link to code repository</h2>  
https://github.com/byork6/SafeBeat-Infant-Monitor  

<h2>Languages and Utilities Used</h2>  
<ul>
  <li><b>Software written in C</b> (For both separate MCU's)</li>
  <li><b>SIMPLELINK Low Power Software Development Kit (SDK)</b> - Used for embedded software development on both MCU's</li>
</ul>

<h2>Development Environments Used</h2>  
<ul>
  <li><b>Code Composer Studio Theia</b></li>
</ul>

<h2>Hardware Components</h2>  
<ul>
  <li><b>Microcontrollers</b> - Texas Instruments CC2651P3 Bluetooth Low Energy MCU (Monitoring Belt & Control Box)</li>
  <li><b>Analog Front End Integrated Circuit (IC)</b> - Analog Devices ADAS1000-4, used for 3-lead ECG/RR measurements and signal processing (Monitoring Belt Only)</li>
  <li><b>BLE Antenna</b> - Will be a PCB Trace antenna (Monitoring Belt & Control Box)</li>
  <li><b>Low frequency filters</b> - Discrete component filters on PCB for ECG leads (Monitoring Belt Only)</li>
  <li><b>Serial memory component</b> - TBD (Control Box Only)</li>
  <li><b>Power path management IC</b> - Enables battery power and AC adapter power (Control Box Only)</li>
  <li><b>Display</b> - TBD (Control Box Only)</li>
  <li><b>Speaker</b> - Used for the event alarm (Control Box Only)</li>
  <li><b>Button Interface</b> - Used for user input control (Control Box Only)</li>
</ul>

