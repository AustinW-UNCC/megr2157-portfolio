# A6 – [Bracket Drawing]

This assignment started out by asking me to parametrically design the bracket that I made last week. I chose to make the bracket based on the dimensions and calculations from my stress analysis. 


Documentation and Parametric Design - 

I started by making my base shape from the side profile of the bracket. This was done because I believed that starting with the side view would allow me to 

<img width="638" height="331" alt="Screenshot 2026-09-30 151824" src="https://github.com/user-attachments/assets/42cfa230-45a0-4c3d-8ef6-d47a30e95273" />

The next pictures will be to show the process of designing this piece in CAD and showing that I used parametric design for each step as required in the assignment guidelines. 

This is the other part of the original base design, showing that parametric design was used 

<img width="512" height="263" alt="Screenshot 2026-09-30 151901" src="https://github.com/user-attachments/assets/aa6c4882-b074-48b3-9277-985a19864766" />

The next few images show the front facing view of the bracket and allow you to see how the slot was made for the bracket. All calculations were based on last week's numbers and are parametrically designed. 

<img width="500" height="205" alt="Screenshot 2026-09-30 151928" src="https://github.com/user-attachments/assets/3e8585b4-72ce-46c2-9618-ec4dd9dd24c2" />

<img width="659" height="347" alt="Screenshot 2026-09-30 152013" src="https://github.com/user-attachments/assets/cbc019f6-4259-44fb-9606-7e12d0cf2848" />

The next step here is the connecting bar between the bracket with the slot and the cylindrical pin. 

<img width="666" height="233" alt="Screenshot 2026-09-30 152138" src="https://github.com/user-attachments/assets/ec4ca1bc-5ccb-4785-9c14-e14483b02cda" />

<img width="461" height="245" alt="Screenshot 2026-09-30 152204" src="https://github.com/user-attachments/assets/4e674548-6310-405b-867f-2c31d7bd74b4" />

I also managed to merge the design from the connecting bar and the pin into one singular piece which is how the example piece from last week was designed. 

This next picture shows most of my parametric equations that were needed to identify any and all variables for this bracket. 

<img width="585" height="196" alt="Screenshot 2026-09-30 151743" src="https://github.com/user-attachments/assets/5abf97b3-def1-49e8-8049-3a921db97685" />

The overall picture of the design in SolidWorks

<img width="445" height="413" alt="image" src="https://github.com/user-attachments/assets/b2983fe2-b187-41c1-93ef-533f2d993703" />

This is the example piece that the brackets were made from 

<img width="485" height="645" alt="Screenshot 2026-09-30 140943" src="https://github.com/user-attachments/assets/f1b5e008-7899-428a-a1b7-f997d3ea1185" />

CAD Drawing - 

My CAD drawing is very in-depth and shows all angles of the assignment in order that anyone with the proper tools could re-create the bracket. This image is only of the start of the dimensions and not the entire thing. 

<img width="752" height="581" alt="image" src="https://github.com/user-attachments/assets/5197cd1d-a19f-49ef-8791-3c2a512031d9" />

Here is the final drawing showing all necessary dimensions so that someone could make this bracket. 

<img width="752" height="584" alt="image" src="https://github.com/user-attachments/assets/676eafd0-f5f5-4392-8522-d3bdd9c42cf7" />

Reflections - 

Part A: 

I used stress analysis to design my bracket because I felt like I had a better understanding on how stresses affect objects in the real world as opposed to stiffness.
The main dimension that this analysis controlled was the diameter of the cylindrical pin at the bottom of the bracket. 
I connected this dimension to the CAD design by inputting the values of the constants and then writing the equation to determine stress as part of my equations and tagged it to a global variable. The Global variable that I used in this section was "Pdia" and it can be seen very clearly in one of the pictures above. That being said, the equation to determine stress actually relates more to the radius of the pin, while the diameter is just double that radius (obviously). So, look at the equation for radius and you will see how the other parameters were used to determine the radius, which in turn, was used to find the necessary diameter. I did not have to change this dimension later on in the design phase as my calculations were correct from the beginning. 

Part B: 

For the slot at the top of the bracket, I applied a tighter tolerance than was probably necessary because I believe that since the majority of the material and strength of the bracket comes from that top section, that it should be held on much better and should have more of the forces being applied there. This is a sliding fit surface that in my opinion, would not want to be used as such in many cases. Most of these types of brackets are made this way for install and are then clamped down by bolts or some other sort of fastener that will keep them from sliding. 

For the pin at the bottom, I allowed for a slightly larger than necessary tolerance because I believe that requiring everything that may be hanging onto this bracket to also be manufactured to the thousandth would create unnecessary cost in the long run. As long as the attached part will fit onto the pin at the bottom and is tight enough that it will not slide off simply due to the frictions between the materials, then it should be good to go for the purposes of my bracket. 

This project took about 6 hours to complete

MEGR 2157 Only: 

Parametric Design - 

For the parametric design, I kept it very simple and designed a link like you would see on a bike or some sort of similar style chain. the reason for doing this is because this part of the design is more to get practice with the accounts of fits and tolerances than it is to come up with new and crazy style links. So why make it harder on myself than it needs to be. 

I started by choosing the slot tool on SolidWorks because that is the best and quickest way to get a link style chain piece made in the CAD software. This part is shown below. 

<img width="221" height="484" alt="Screenshot 2026-09-30 175835" src="https://github.com/user-attachments/assets/0d6558df-1f6e-4323-a46f-169e9a8ae1ce" />

Since SolidWorks allows you to make multiple shapes on one sketch, I was able to create the holes that would slide onto the shaft at the same time. These are dimensioned using parametric modeling and you can see that they are slightly larger than the diameter of the pin and are at the upper range of the tolerance limit because this is the part that I chose above to be on the looser side of the tolerance limits. 

<img width="281" height="194" alt="Screenshot 2026-09-30 175918" src="https://github.com/user-attachments/assets/8b33170a-1972-4071-8855-76f564caf4a5" />

The final step in this process was to decide how wide to make the link, and I chose to go with a wider than normal size because I have looser tolerance limits and the extra width will help to counteract a lot of sliding due to the increased amount of surface friction between the link and the pin. 

<img width="724" height="470" alt="Screenshot 2026-09-30 175944" src="https://github.com/user-attachments/assets/9478c415-96d7-433a-aee5-b10cd9abe133" />

Final overall view of the pin after dimensioning and extruding - 

<img width="215" height="383" alt="image" src="https://github.com/user-attachments/assets/7c461604-2bf8-406e-8969-48971ab4a050" />

Drawing - 

Any and all necessary dimensions are posted on this drawing so that someone could re-create this object with access to the proper tools for tolerancing. 

<img width="794" height="610" alt="image" src="https://github.com/user-attachments/assets/36cd9ee4-cfdd-463e-bcf2-6392e9d1156e" />

Reflections - 

I learned that when dealing with tolerancing, the allowable difference between pieces and parts is much smaller than I ever thought it would be for objects that may not be used in extremely important scenarios. Due to the technology and ability of machines today, we are able to get within a couple thousandths of an inch using machines that were never originally designed to be capable of such small measurements. 

By dimensioning and tolerancing a drawing, you are telling the manufacturer how important the part and or item is to you and to its purpose in the real world. Me being a little bit older college student, I have seen these drawings firsthand in the field and I have had to make parts using provided tolerances from engineers. I have made tens of thousands of tubing bends that had to be under 0.5 degrees of tolerance, and I have seen with my own eyes how such inherently small differences can cause major issues and delays in real life projects. This can also lead to major cost increases when parts become delayed or have to be remade because sometimes a small part can hold up an entire assembly line. 

Link to CAD drawings and designs - 

https://github.com/AustinW-UNCC/megr2157-portfolio/blob/main/Part%202%20A6.SLDPRT

https://github.com/AustinW-UNCC/megr2157-portfolio/blob/main/A6%20Bracket.SLDDRW

https://github.com/AustinW-UNCC/megr2157-portfolio/blob/main/Part%202%20A6.SLDDRW

https://github.com/AustinW-UNCC/megr2157-portfolio/blob/main/A6%20Bracket.SLDPRT
