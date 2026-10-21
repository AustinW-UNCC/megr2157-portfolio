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

This design helped create a major change in the maximum stress felt by the original bracket. I believe that by making the transition between parts smoother, it got rid of the stress concentration that was causing such a huge issue before. This bracket stayed relatively consistent throughout the 3 meshes and I am very happy with the results. 




















