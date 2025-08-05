# Robot Wrestling Project Journal

## Developer: Mina Romany Mina Habib  
**Duration**: 01/07/2025 – 12/07/2025  
**Total Time Spent**: 68 hours  
**Description**: An autonomous robot designed for competitive wrestling-style matches. Focus areas included high-torque movement, intelligent opponent detection, sensor integration, and adaptive behavior control through real-time decision-making algorithms.

---

### 01/07/2025  
I kicked off the combat robotics portion of my project by sketching the foundational frame and brainstorming potential arena layouts. It was important to visualize not just the physical structure, but how the robot would behave and maneuver within a confined space. I spent a good portion of the day studying torque and gear ratios, aiming to maximize pushing power while maintaining agility. During this process, I also gathered references on proven autonomous wrestling strategies, hoping to blend theoretical AI tactics with real-world physics. It was an exciting and motivating start to this subproject.

---

### 02/07/2025  
With my ideas taking clearer shape, I moved on to designing the full 3D chassis layout. I used CAD tools to simulate how weight distribution would affect balance and turning momentum. A lot of time went into testing various configurations that might hold up under pressure, both in terms of impact tolerance and fluid mobility. The challenge was balancing stability with responsiveness. By the end of the day, I had a working model that I felt confident could serve as the structural foundation for the robot.

---

### 03/07/2025  
Today was all about sensors. I finalized the design for sensor placement by researching the best combination of IR and ultrasonic modules. I paid close attention to their effective range, blind spots, and detection angles. This involved a lot of trial-and-error on paper before I committed to any hardware. The goal was clear: eliminate blind zones and ensure the robot could always "see" its opponent from any approach angle. It was a shorter session than others, but a deeply technical one.

---

### 04/07/2025  
I spent six focused hours simulating opponent detection logic. Using mock input from ultrasonic and IR sensors, I emulated how the robot would respond in real-time to a nearby competitor. I also began running physical motion tests, tweaking the motors to respond appropriately to distance fluctuations. Perhaps the most critical milestone today was integrating motor control with an edge detection failsafe — this would prevent the robot from driving itself out of bounds during a match. It was a challenging but rewarding debugging process.

---

### 05/07/2025  
My attention turned toward the power system today. I calculated the current draw for each motor when operating under full load, which helped me understand how much power the system would consume during a typical five-minute match. Using that data, I simulated battery drain rates to ensure the robot could function at peak performance from start to finish. I also took this opportunity to document all pin mappings and power distribution routes, ensuring consistency across both the hardware and codebase.

---

### 06/07/2025  
This was the first major assembly day. I began mounting all the internal components into the printed 3D frame. During this process, I tested sensor functionality under actual movement — checking for interference or erratic readings caused by vibration. As expected, the IR sensors were the most sensitive. I calibrated all modules for varying lighting conditions, ensuring reliability in both bright and dim environments. It was exhausting physical work, but seeing the robot take form was incredibly satisfying.

---

### 07/07/2025  
Today was about refinement. I optimized the ultrasonic sensor code by adding noise filtering algorithms to reduce false readings from ambient sound or reflections. I also implemented an edge-triggered stop/reset function to automatically pause the robot’s actions under certain failure conditions. Finally, I ran a series of three controlled fight simulations, observing how the robot behaved under combat-like pressure. Logging this behavior helped me identify small tweaks needed for future matches.

---

### 08/07/2025  
I focused on behavioral transitions today, developing routines for three key states: search, engage, and push. The robot needed to switch smoothly between locating an opponent, moving to intercept, and pushing with full torque. I fine-tuned the angles for sharp turns and added acceleration delays to avoid slipping during quick maneuvers. The most interesting part was testing how quickly the system could shift from aggressive mode to evasive mode when the opponent reversed or countered. It felt like programming a creature with instincts.

---

### 09/07/2025  
Aesthetics met functionality today as I implemented RGB LED logic to visualize the robot’s fight state. I programmed the LEDs to change color based on the current mode — for example, red when pushing, blue while searching, and yellow during evasive maneuvers. This was surprisingly helpful for both debugging and visual tracking during matches. I also documented all RGB behavior so I could later analyze how the robot reacted in real time during testing or presentations.

---

### 10/07/2025  
The documentation phase began in full. I wrote detailed notes about each submodule and created diagrams showing data flow, pin connections, and decision-making logic. I ran simulations using variable input environments, testing how the robot might behave under different arena conditions (e.g., reflective walls, ambient light, opponent size). I also adjusted the internal wiring layout to reduce cross-interference and improve safety in tight compartments.

---

### 11/07/2025  
As the finish line came into view, I gathered all media assets for the final presentation — pictures, short video clips, wiring diagrams, and 3D renders. I organized the Bill of Materials (BOM), double-checked all prices, and included vendor links in case the project needs replication or scaling. I spent time physically cleaning and polishing the robot body to make sure it looked presentable and professional. It was a rewarding and visual end to all the deep technical work.

---

### 12/07/2025  
On the final day, I focused entirely on verification and submission. I revisited each component's sourcing information to ensure everything was properly accounted for. Then, I did a final pass through this journal and the README file to catch typos or missing documentation. I made sure that all links worked, diagrams were clear, and everything was submitted in the proper format. It was a quiet but fulfilling end to a truly engaging and educational build process.

---


## Images
- ![alt text](imag/image.png)
- ![](imag/image2.png)
- ![](imag/piiic.jpg)
### Code
- ![alt text](imag/image3.png) 
- ![alt text](imag/image4.png) 
- ![alt text](imag/image5.png) 
- ![alt text](imag/image6.png) 
- ![alt text](imag/image7.png) 
- ![alt text](imag/image8.png) 
- ![alt text](imag/image9.png) 
- ![alt text](imag/image1.png) 
- ![alt text](imag/image10.png) 
- ![alt text](imag/image11.png) 
- ![alt text](imag/image12.png) 
- ![alt text](imag/image13.png) 
- ![alt text](imag/image14.png) 
- ![alt text](imag/image15.png) 
- ![alt text](imag/image16.png) 
- ![alt text](imag/image17.png) 
- ![alt text](imag/image18.png) 
- ![alt text](imag/image19.png) 
- ![alt text](imag/image20.png) 
- ![alt text](imag/image21.png)
### Circuits
- ![alt text](imag/circuits1.webp) 
- ![alt text](imag/circuits2.webp) 
- ![alt text](imag/circuits3.webp) 
- ![alt text](imag/circuits4.webp) 
- ![alt text](imag/circuits5.webp) 
- ![alt text](imag/circuits6.webp) 
- ![alt text](imag/circuits7.webp) 
- ![alt text](imag/circuits8.webp) 
- ![alt text](imag/circuits9.webp) 
- ![alt text](imag/circuits10.webp) 
- ![alt text](imag/circuits11.webp) 
- ![alt text](imag/circuits12.webp) 
- ![alt text](imag/circuits13.webp) 
- ![alt text](imag/circuits14.webp) 
- ![alt text](imag/circuits15.webp)


