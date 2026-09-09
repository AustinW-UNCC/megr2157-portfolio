# A3 – [Parametric and FEA]

Part 1 
------

The First step of this assignment was to design a bar with a round cross-sectional area with a load somewhere between 300-500 lbf of force. It also had to have a maximum of 0.009 inches of axial deflection. Next, I had to choose a type of aluminum with a young's modulus between 8.5-10.0 x 10^6 psi. I chose to go with Aluminum 6061 Alloy because it's young's modulus was very close to the middle of the range, sitting around 10.0 X 10^6 psi. I first started by making a drawing of what my design would look like and then doing the calculations necessary to find what the minimum length of the bar should be. All of that is listed in the picture below. 

<img width="602" height="547" alt="image" src="https://github.com/user-attachments/assets/d39aeecb-e9b6-4a29-bb22-2576a14fdea8" />

CAD Design - 
------------

I started by creating a circle using my global variable "d" for the diameter of the circle 

<img width="491" height="410" alt="Screenshot 2026-09-09 125202" src="https://github.com/user-attachments/assets/0f4c5396-71f3-4164-b68a-0348e0ceca3e" />

Next, I extruded the bar based on the calculations that I did for the length 

<img width="389" height="288" alt="Screenshot 2026-09-09 130844" src="https://github.com/user-attachments/assets/b0daa31b-4425-4d25-8b0e-69c85e799df4" />

<img width="638" height="108" alt="Screenshot 2026-09-09 125153" src="https://github.com/user-attachments/assets/33f23703-6dff-4db1-b464-d9519febe5be" />

Next, I input all my data into the SolidWorks equation, and it confirmed that my calculations were exact 

<img width="524" height="161" alt="image" src="https://github.com/user-attachments/assets/f6efb32a-7ce4-4f29-a260-c1026352473f" />

I then decided to go with Aluminum 6061 Alloy as it had a very similar modulus of elasticity to the one I chose to do the calculations with. 

<img width="347" height="189" alt="Screenshot 2026-09-09 130910" src="https://github.com/user-attachments/assets/01145645-1c74-4a35-8d5d-56591fead6fa" />

FEA Simulation - 
----------------

For the FEA simulations, I started with choosing a fixed geometry on the one end of the bar as the problem requested, as shown here   

<img width="167" height="146" alt="Screenshot 2026-09-09 131005" src="https://github.com/user-attachments/assets/9cb6d2c0-29f2-42f6-8e5b-b38182908a86" />

After that, I applied the forces to the end of the bar as the problems picture indicated to do and here is how that looked 

<img width="342" height="499" alt="Screenshot 2026-09-09 131117" src="https://github.com/user-attachments/assets/5e760bca-ab8e-43ac-afba-d63f4791f54a" />

Step 2 - FEA of the bar 
--------

This step asked me to start by showing a deflection map from the simulation that I ran. The deflection map here shows that I had calculated the length of the bar perfectly to achieve the allowed axial deflection of 0.009 inches 

<img width="885" height="332" alt="Screenshot 2026-09-09 131353" src="https://github.com/user-attachments/assets/b6e49580-bac3-4e3a-bce8-c5aa31e05d0b" />

Next, the assignment asked me to show a von mises stress map. This was generated using the same simulation as before and shows that the forces did come anywhere near the maximum allowed stress of the 6061 Aluminum Alloy. 

<img width="939" height="395" alt="Screenshot 2026-09-09 131305" src="https://github.com/user-attachments/assets/29f6ae88-711d-49cd-9d85-4403074f7242" />

Note: The maximum stress on the bar was only 2,224 PSI and the maximum allowable for 6061 Aluminum is 7,998 PSI. This gives a factory of safety of 3.595

Step 3 - Design Reflection
--------

The axial deflection from my hand calculation and the axial deflection from the CAD simulation turned out to be the exact same #. Therefore, the percent error here is 0.00%. 

I believe the reason for these values being the same is due to the modulus of elasticity that I used for the calculations being basically identical to the modulus listed in Solid Works for 6061 Aluminum. Since this problem is very basic and only takes into account the forces being evenly distributed and the fixed geometry to be perfectly symmetrical as well, I am not surprised that the two numbers were the same. In a real-life scenario, the likelihood of everything being this perfect would be slim so I would expect there to be slight changes in how it works in a genuine situation. 

However, I would still trust the CAD modeling software to be more accurate in the overall scheme of things since the computer software and modeling simulations that Solid Works can provide is much more well-rounded than my current knowledge of how all of this works. This software is widely used for its accuracy and ability to do things that we humans cannot easily replicate without using much more expensive methods. That is why I would trust the Solid Works simulations to be more accurate in the long run compared to my personal calculations. 

Part B - Design Reflection

After running calculations regarding the newly added pinhole in the side of the bar, my factory of safety went from 3.595 to a much smaller 1.432. Since there was no exact dimension of the size of the pinhole, I used 0.1 inches as the estimated size. The calculation was actually very simple since the (Kt) found in the machinery's handbook was listed as 2.51 for a pinhole ratio of 20%. the 20% came from the 0.1-inch hole being 20% of the total diameter of 0.5 inches. Therefore, all I had to do was divide 3.595/2.51 and out came a new safety factor of 1.432. 

4. lessons learned and mistakes made -

  - I learned firstly how to make global variables and equations during this assignment since I have never had to use them before. I also now understand why they are important and why inputting variables instead of numbers into the parts can make things go so much faster when you have an entire system of parts and one small change could require you to re-configure an entire design. With global variables, the design, along with all extrusions and cuts can be fixed by simply re-evaluating the variable instead of having to input all new numbers under each step of the design.

  - I did not have any major or substantial mistakes during this process as I took my time and carefully went over each step, using the provided videos and online resources to help me along.

  - I spent about 4 hours on this project in total, from the start of my hand drawing to the end of my portfolio updates


Final Step - 2157 Only

For the last step in this assignment, I was tasked with re-evaluating each step done in part 2. Including, changing the numbers for the load, thickness, height, and width of the bar. 

The new values that I went with were: 

F = 500 lbf

D = 0.75 inches

Since my bar is a round object, the height and width are calculated into the diameter and therefore was not required to be changed 

I believe that the length of the bar will have to be longer in order to achieve the same deflection of 0.009 inches. I believe this to be the case because based on the equation for length, a small change in diameter is exponentially more effective than a small change in force. 

After doing the calculations, I was right, the new length of the bar will need to be 79.52 inches in order to achieve the same amount of the deflection

Solid Works part here - 

https://github.com/AustinW-UNCC/megr2157-portfolio/releases/download/SolidWorksA03/A03.SolidWorks.Part.SLDPRT

