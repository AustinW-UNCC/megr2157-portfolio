# A7 – [FEA on Bracket]

Objectives:

 - Use FEA analysis to improve a bracket design that I made earlier in the semester

 - Perform static stress analysis covering stress, strain, and stiffness of the bracket

- Interpret data by identifying max stress, displacement, and safety factors.

- Optimize the design by modifying geometry to enhance performance.

- Document the entire process with images, calculations, and insights.

- Reflect on key engineering lessons learned and time spent.

Description - 

Your task is simply to create a high stiff, high strength, and lightweight component. Use Finite Element analysis to drive your decision making process throughout your design. Each step of the analysis and before you make geometric changes make sure the component’s results (stress/displacement/Safety Factor) converge on a 7% difference. Achieve this by modifying the number of elements. If after three attempts to converge use the stiffness and stress from the finer mesh size use the finest mesh size and proceed through the process.

All of this will be done using my bracket from A6, the material on that bracket is A36 steel as shown below 

<img width="608" height="469" alt="image" src="https://github.com/user-attachments/assets/e9c4dd4d-dbf7-4313-b508-27c06621b164" />

Design 1 - 

the initial design will be my Design #1 for this project because I need to establish a baseline for how this bracket reacts before I make any changes to the design. 

The OG bracket: 

<img width="355" height="394" alt="image" src="https://github.com/user-attachments/assets/0946adfb-8225-4feb-8837-915ed4a06203" />

Adding Parameters - 

 The first parameter to add were the fixed geometry supports where the bracket would slide onto the channel or whatever it would be attached to for its' actual use. 

<img width="531" height="317" alt="image" src="https://github.com/user-attachments/assets/5ad45a1e-b8fc-4daf-aff3-8b43389f7220" />

Next, I added the loading forces on the bottom bar where the bracket would likely have some sort of linkage hanging from it 

<img width="517" height="281" alt="image" src="https://github.com/user-attachments/assets/566bd8f1-af53-42c5-9c8b-fcd0edf162e5" />

After that, I created a mesh to be able to run the simulations properly. I started with the most course mesh available for the initial test. 

<img width="131" height="183" alt="Screenshot 2026-10-21 150311" src="https://github.com/user-attachments/assets/af3e7c8f-57a0-46d8-a0ee-ab3bb4c21c73" />

<img width="416" height="380" alt="Screenshot 2026-10-21 150318" src="https://github.com/user-attachments/assets/2df42128-15d3-4cd8-9fb1-16619d2c4a0f" />

Work Flow - 

I started each design test with the coarsest mesh that SolidWorks allowed and then put it in the middle for the second test, and all the way to the right for the 3rd and final test of each design. Each run with a different mesh will have photos included below and it will be in order of Course to Fine mesh each time to ensure consistency within the reporting. 

Design 1 - 

  - D1-1

<img width="610" height="365" alt="image" src="https://github.com/user-attachments/assets/64bb9ba5-84da-4f8c-8864-75d1229298fb" />

<img width="611" height="426" alt="image" src="https://github.com/user-attachments/assets/b03f624d-a10c-4821-ae01-72c520200992" />

<img width="605" height="434" alt="image" src="https://github.com/user-attachments/assets/0e99c21e-c7ec-43f9-a8df-72711a28cb1e" />

  - D1-2

medium mesh - 

<img width="131" height="113" alt="image" src="https://github.com/user-attachments/assets/b29d7e92-9b8b-425c-bcbb-af30f974f79a" />

<img width="701" height="421" alt="image" src="https://github.com/user-attachments/assets/ba915c21-dbbc-4c6e-946b-aef151397c35" />

<img width="670" height="425" alt="image" src="https://github.com/user-attachments/assets/2975be17-f4e7-4893-8fb4-f6b6f5064af8" />

<img width="623" height="413" alt="image" src="https://github.com/user-attachments/assets/ef99c6b3-4ffe-4366-a083-194ec0363b0e" />

- D1-3

  Fine Mesh -

<img width="133" height="187" alt="image" src="https://github.com/user-attachments/assets/745b92ef-c2de-4947-8421-a621cf5ae88c" />

<img width="401" height="428" alt="image" src="https://github.com/user-attachments/assets/eac0a7d9-0942-4b59-a3d0-eb1ec2b74227" />

<img width="616" height="442" alt="image" src="https://github.com/user-attachments/assets/54a58bdf-c2da-4d49-9ff5-bfedd6b98aa5" />

<img width="655" height="443" alt="image" src="https://github.com/user-attachments/assets/143a9c30-8152-4056-a898-18b456bc73fc" />

Design 1 data - 

<img width="476" height="212" alt="image" src="https://github.com/user-attachments/assets/e3fb82cd-90a0-477e-84fb-41e750dd2d84" />

Thoughts about my design - 

For design 1, the high amount of stress worried me because it implies that I must've calculated something wrong, which means that this may be a harder process than I originally imagined. However, once I changed the mesh, the stress severely lowered which tells me that it is likely a sharp edge or corner that is creating a severe stress concentration. That is what I expect to address first in my next design. The stress was concentrated right where the vertical bar meets with the round pole. That is where my main focus will be going for the next iteration. 

Design 2 - 

For this design, I chose to focus on smoothing out the transition from the long bar to the round bar of the bracket. I also decided to add a brace further down the bar to help with deflection of the bracket. 

<img width="486" height="473" alt="image" src="https://github.com/user-attachments/assets/9a734b4e-1cff-4dfe-af98-7ed270b6f920" />

The Fixtures and loads were added again properly to ensure simulation was equal to the simulation on the first design. 

<img width="463" height="476" alt="image" src="https://github.com/user-attachments/assets/e6bca482-c435-4209-9367-1d9400c35a69" />

D2-1 

Coarse mesh - 

<img width="669" height="515" alt="image" src="https://github.com/user-attachments/assets/a663d08f-86d0-42d2-b693-ed56c09a188d" />

<img width="650" height="469" alt="image" src="https://github.com/user-attachments/assets/af1fc268-088b-4c84-8d38-ecb568a29971" />

<img width="658" height="482" alt="image" src="https://github.com/user-attachments/assets/725f589f-ca43-4857-b4c6-506d62e46c5b" />
D2-2 

medium mesh - 

<img width="702" height="482" alt="image" src="https://github.com/user-attachments/assets/f181eff0-0db1-441b-866d-18cf8925e97c" />

<img width="731" height="478" alt="image" src="https://github.com/user-attachments/assets/59d9cbab-210f-40ea-8b79-98667674cbec" />

<img width="725" height="498" alt="image" src="https://github.com/user-attachments/assets/2428edd4-b351-4444-8372-c9e0ca7e04de" />

D2-3

Fine Mesh - 

<img width="689" height="470" alt="image" src="https://github.com/user-attachments/assets/2c02f13c-597f-42a4-82f7-520d17cf036b" />

<img width="708" height="454" alt="image" src="https://github.com/user-attachments/assets/e8e11ca1-c65d-48c4-a1ce-748b852197c6" />

<img width="675" height="459" alt="image" src="https://github.com/user-attachments/assets/b79e797f-51b7-405c-a9f7-01948c0f0845" />

D2 - Resulting Data 

<img width="514" height="254" alt="image" src="https://github.com/user-attachments/assets/0e23fcac-f0c6-40fb-bbd5-7bd830b5a5a2" />

Thoughts on my design - 

This design helped create a major change in the maximum stress felt by the original bracket. I believe that by making the transition between parts smoother, it got rid of the stress concentration that was causing such a huge issue before. This bracket stayed relatively consistent throughout the 3 meshes and I am very happy with the results. 

Design 3 - 

For the third design, I decided to focus on weight loss for the bracket since the stress and displacement are no longer an issue. I decided to make cut outs in each section of the bracket to maintain the symmetry while also taking away unecessary material. 

<img width="482" height="478" alt="image" src="https://github.com/user-attachments/assets/7c21bd05-9d5d-43d4-aaa1-4a603cd28a59" />

D3-1 

Course mesh - 

<img width="641" height="452" alt="image" src="https://github.com/user-attachments/assets/ff3b384c-f129-4f23-97b7-f7e995fe2a4d" />

<img width="614" height="475" alt="image" src="https://github.com/user-attachments/assets/d27a363f-0d44-4dc8-894e-ce70a7266c1d" />

<img width="721" height="479" alt="image" src="https://github.com/user-attachments/assets/768fc9d5-3cef-4cfd-828c-2585d4f01e73" />

D3-2

Medium Mesh - 

<img width="671" height="463" alt="image" src="https://github.com/user-attachments/assets/9d761c55-7423-4d6c-be32-271a5704b254" />

<img width="680" height="456" alt="image" src="https://github.com/user-attachments/assets/b274a0c4-ac9f-448b-b3f8-24dc48e84589" />

<img width="638" height="455" alt="image" src="https://github.com/user-attachments/assets/baaad4ba-af2a-47a5-b046-c557b939f686" />

D3-3 

Fine mesh - 

<img width="653" height="468" alt="image" src="https://github.com/user-attachments/assets/88de5506-44e5-4e44-ac7c-cc2d8b632658" />

<img width="725" height="479" alt="image" src="https://github.com/user-attachments/assets/80c9d746-20a6-4c0c-9697-61cd14653747" />

<img width="680" height="460" alt="image" src="https://github.com/user-attachments/assets/64066b6b-1a73-4bef-96e7-57f34a396f9d" />

Resulting Data - 

<img width="518" height="257" alt="image" src="https://github.com/user-attachments/assets/b39a8315-08b7-4792-b0f9-d637c65827e6" />

Thoughts on my design - 

This rendition was very intriguing due to the extra weight loss in the bracket; however, I notice that the stress is starting to creep back up towards a negative direction, which would imply that I should find another way to save weight if I were to continue this design process. Since I still have a massive factory of safety, I believe that there is no need to keep going with the design process and I will end it here with a successfully made bracket. 

lessons learned - 

Reflecting on this assignment, I feel like I have a better understanding on why engineers make certain choices in the design process. I have always looked at it like "why don't engineers think about x, y, and z when making parts", but the truth behind it is, they do. Sometimes it is just not feasible to make the parts via the manufacturing process or due to cost and time restraints. An example of this I learned making my bracket. I could spend weeks continuously making the bracket better but in a real world scenario, this would be extremely cost effective for a part that likely doesn't need this much overengineering. Sometimes engineers have to make decisions for the betterment of the company rather than for the people who install and work with the parts. What I mean by that is this, if it takes 10 extra minutes to install, but saves 2 days and thousands of dollars in time and manufacturing, then the tradeoff is worth it to spend the extra few minutes on the install. 

2157 Students Only - 

objective - complete the process above for the link that we made as well. 

Initial Design - 

<img width="206" height="421" alt="image" src="https://github.com/user-attachments/assets/bb2a3944-81b4-4515-8aff-60ca3ede74d2" />

here are the applied loads on the link

<img width="296" height="218" alt="image" src="https://github.com/user-attachments/assets/0e26fc1c-bb30-4c5c-aa46-7ca46422e200" />

L1-1 

Coarse mesh - 

<img width="382" height="478" alt="image" src="https://github.com/user-attachments/assets/5471476b-8b8b-4add-81b8-8e1e462fe0f8" />

<img width="374" height="458" alt="Screenshot 2026-10-21 185905" src="https://github.com/user-attachments/assets/06cba11f-25c3-4403-aade-dcdb8fef2e46" />

<img width="380" height="460" alt="image" src="https://github.com/user-attachments/assets/38ce0199-6211-46c1-9f8e-b85c0a048c54" />

Medium Mesh - 

<img width="411" height="469" alt="image" src="https://github.com/user-attachments/assets/5d7c61d5-cf29-4a8b-a5d7-11ed4fc34a8a" />

<img width="380" height="449" alt="Screenshot 2026-10-21 190236" src="https://github.com/user-attachments/assets/6f0d65b1-3254-4a63-a036-3adc17f5b943" />


<img width="365" height="454" alt="image" src="https://github.com/user-attachments/assets/1c7df8bc-4886-4423-a510-2ea708a4b050" />

Fine Mesh - 


<img width="418" height="459" alt="image" src="https://github.com/user-attachments/assets/22513fc8-65ef-437c-b0b2-713c6ffc180f" />


<img width="388" height="452" alt="image" src="https://github.com/user-attachments/assets/df7bfa8b-6ab9-445c-8be8-c207a6ab9d96" />


<img width="379" height="482" alt="image" src="https://github.com/user-attachments/assets/5d15b584-d318-40a0-ba49-b092a4797b97" />

Thoughts on the design - 

Based on the result of this FEA, I would have to say that there is no engineering need or reason to adjust this linkage as it comes no where near the limit of stress, strain, displacement, or the factor of safety. Along with it being very easy and simple to manufacture, there is no reason to continue making new designs for this result as they all converge as required by the assignment at this point. 

I spent about 8 hours on this project and I wish I had chosen to start working on it sooner, not because I didn't have enough time, but rather, there are questions that I wish I could ask about whether I did certain things correctly or not. I genuinely believe that I did this to the best of my ability in the time given, but next time I will try to meet with Dr. Fagan to ask since I am unsure if the way that I applied my loads and fixed geometries was even correct. 

CAD Files - 

[Bracket Revision 2](https://github.com/AustinW-UNCC/megr2157-portfolio/blob/main/A6%20Bracket%20D2.SLDPRT)

[Bracket Revision 3](https://github.com/AustinW-UNCC/megr2157-portfolio/blob/main/A6%20Bracket%20D3.SLDPRT)








