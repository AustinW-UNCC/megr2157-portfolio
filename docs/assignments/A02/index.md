# A2 – Truss Stress Analysis

## Objective

I was asked to design a truss that could withstand a given force (P) while staying withing certain dimensions as given by the problem. 

The Requirements: 

1. A force P between 20-30 KN - I chose to go with 20KN to give myself the best chance at maintaining a higher safety factor

2. a = 0.4m and b = 0.3m

Image of the given constraints: 

<img width="275" height="184" alt="image" src="https://github.com/user-attachments/assets/7249811a-ad16-4eb7-9fbe-4de3670b7e5e" />

My Design Idea - 

I decided to go with this design because of the symmetry in the design, along with the simplicity of how this truss will react to vertical forces. Since there is symmetry in this design, I should be able to do my entire FBD and Stress analysis on only one side of the truss and still get accurate numbers for the entire design. 

<img width="281" height="201" alt="image" src="https://github.com/user-attachments/assets/32d2d3cc-43c4-4ae3-8e91-6ad7c28eb7d9" />


Final Design FBD - 

I chose to go with this design because I believe that it would handle the stresses being applied to it the best because the loads would be spread evenly across the entire truss, allowing for more force to be applied before failure. I also enjoy looking at a symmetrical truss like this and it worked out well for this project. 

<img width="308" height="248" alt="image" src="https://github.com/user-attachments/assets/fe7eed35-619b-42c5-b567-ed24ab564262" />

Length of each member in my truss - 

Each member was measures using basic trigonometry and the numbers for a and b respectively were given as part of the instructions for the assignment 4

<img width="446" height="616" alt="image" src="https://github.com/user-attachments/assets/72b62062-cc5f-4d1e-ad5b-e47a7c9399bf" />

Joint Method Analysis of my Truss

On this step, I analyzed every joint in my truss to determine where the forces would be the highest and to ensure that the truss would remain in equilibrium when the forces were actually applied. From these calculations I used the highest identified internal force to help aid me in the next step. 

<img width="425" height="584" alt="image" src="https://github.com/user-attachments/assets/af74882a-052e-4fc6-bca1-ba2cf75e48c1" />

<img width="514" height="452" alt="image" src="https://github.com/user-attachments/assets/e6410f47-ca52-4612-b6ab-61a6d37688e2" />

Cross-sectional area and weight calculations 

After finding that my maximum internal force was 16.025 KN, I used this number along with the requirement for a factor of safety of 3.5 to determine the minimum cross-sectional area that would work for my truss. That area helped me find the weight of the truss using volume and diameter formulas. 

<img width="470" height="238" alt="image" src="https://github.com/user-attachments/assets/d58b0268-2d5b-4113-a5f7-394bd6a1e417" />


<img width="545" height="544" alt="image" src="https://github.com/user-attachments/assets/fd2d050a-7e8c-4976-ae1c-8f7573cb2557" />


<img width="473" height="212" alt="image" src="https://github.com/user-attachments/assets/16baed7b-32ae-4e99-b617-66b61ef892db" />

Cross-sectional area and weight of the pins

To help me determine the minimum cross-sectional area of the pins, I used the point at which the largest amount of force was being applied (Pin D) to ensure that the pin size would be relevant to the highest amount of stress that the truss endures, while also maintaining a factory of safety of 4. I drew an FBD of the pin, along with all necessary calculations to ensure completion of the requirements. The density of the A500 steel was found using online resources and the ASTM. After that, I found the diameter of the pin that would be required to handle the same loads and stresses. 


<img width="490" height="274" alt="image" src="https://github.com/user-attachments/assets/a9b903cb-5fb2-4f6a-bdbb-0190c3acced8" />


<img width="485" height="445" alt="image" src="https://github.com/user-attachments/assets/8870d8ca-24fb-455e-b74c-12931093db37" />


<img width="497" height="506" alt="image" src="https://github.com/user-attachments/assets/cd69407a-3249-4f96-88c3-1049fdc14c43" />

SolidWorks Model and Simulation - 

Here is the model of my truss in SolidWorks. I had to learn to use the weldments tool as that is something I had never done before and it took some time to get used to, but it was fun to discover new ways of making things in CAD. 


<img width="518" height="272" alt="Screenshot 2026-09-02 170332" src="https://github.com/user-attachments/assets/29bdc74c-ba88-4611-b910-6342b1f76d15" />

This image shows what that same truss looks like with the pins installed - 


<img width="568" height="263" alt="Screenshot 2026-09-02 172243" src="https://github.com/user-attachments/assets/df0f1b67-30b8-4fc4-bef9-dbd06b505555" />

In this image, you will see the truss set up for the simulation to confirm that the loads and fixtures were properly applied following the directions of the assignment. 


<img width="664" height="320" alt="Screenshot 2026-09-02 175900" src="https://github.com/user-attachments/assets/cbeab1db-39bf-4ad3-bcea-300859f76df4" />


Finally, here is the image of the truss after running the simulation - This image shows that the Factor of Safety of 3.5 was maintained properly and that the truss fits all necessary constraints of the project. 


<img width="833" height="363" alt="Screenshot 2026-09-02 180822" src="https://github.com/user-attachments/assets/66169b01-55f7-47ad-b0fc-9ee65aeb3a87" />

The Mass Properties tab in SolidWorks: shown here; estimates the total weight of the truss to be 14.24 lbs. Which is about 4 lbs heavier than my calculations proved. I am not quite sure exactly why that is the case.

<img width="79" height="19" alt="Screenshot 2026-09-02 180854" src="https://github.com/user-attachments/assets/b1c5b6c6-6494-4d65-a809-6810b2156d03" />

Engineering Lesson - 

The main lesson that I learned here is to always check everything ahead of time before completing too many steps. One of the biggest mistakes I made was running all calculations prior to checking if SolidWorks had A500 steel as an option. The other main lesson learned for me was how to use weldments in SW, and how to run a simulation better. I had only run one simulation in SW prior to this assignment, so that part took a lot of time watching YouTube videos to figure out. Aside from this, I would definitely manage my time better next time and give myself more time to fix mistakes. Being at a new university and still trying to do the small things like finding my way around campus makes all of this take longer than it will be once I feel settled in and ready to go. 

Likelihood of Failure Modes in Truss Components - 

Part 1 - Truss Members: 

After researching how truss members can fail under loads, especially when they are made of A500 steel, I decided that the most likely failure point on my truss would be the members in compression, (AE, BC, CE). Since A500 steel is very ductile, it is more prone to buckling under compressive loads rather than fracturing under tensile loads. The members that fracturing would apply to are AB, CD, AD, and DE. Since ductile materials will undergo a lot of stress-hardening in tension, these members will last much longer than the previously mentioned compressive members. 

However, since the simulation showed that the truss would hold the required load and still maintain a 3.5 FS, I do not feel like any major changes would be necessary to make to increase the strength of the truss. Although, if I were to make one suggestion, I would add a cross member that runs straight from member BC to member AD that also encompasses the two middle members (CE and DE) to help guard against the buckling forces that would apply to those members. 

Possibly Failure Point for Pin Connections - 

If the pins were to fail, I would expect them to fail due to shear stress. The reason for this is because when that slicing effect occurs, all of the weight provided by the 20KN force will be applied to a centralized location on that pin and all forces will travel through a single line. This would be the most likely case for failure in my opinion due. Much of the information that I learned from here actually came from my statics and solid mechanics classes and the notes that I took from them. I was very interested in how the materials responded and reacted to forces and I took very detailed notes on these subjects. 

The Fix - 

I would switch to a double-shear pin to resolve this issue and use a clevis to help spread that load out across multiple areas instead of it being focused in one centralized spot. The clevis would effectively double the shear stress required to snap the pin because it forces that same load to be slicing across two areas at the same time instead of just one. 

SolidWorks Link - 

[A2 - Truss Design.html](https://github.com/user-attachments/files/31760910/A2.-.Truss.Design.html)

