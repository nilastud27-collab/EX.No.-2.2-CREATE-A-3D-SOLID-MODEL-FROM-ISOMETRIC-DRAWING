# EX.No.-2.2 CREATE A 3D SOLID MODEL FROM ISOMETRIC DRAWING
## Date :15.10.2026

## AIM: 

To create a 3Dmodel from the given isometric drawing using fusion 360 tool. 

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload

##Procedure:

## STEP-1: Create the Base Plate 
1. Open Autodesk Fusion 360 and ensure the units are set to 
Millimeters (mm). 
2. Select Create Sketch and choose the XY (Top) Plane. 
3. Create two circles with a center-to-center distance of 56 mm. 
4. Draw the outer profiles of the base using the Center Diameter 
Circle tool or arc tool with a radius of R18 (Diameter = 36 mm). 
5. Draw the two inner through-holes with a diameter of 16 mm 
at the same center points. 
6. Use the Line tool to connect the outer circles tangentially to 
complete the enclosed base boundary. 
7. Click Finish Sketch.

<img width="752" height="433" alt="Screenshot 2026-11-19 233010" src="https://github.com/user-attachments/assets/ea13458f-41a1-4310-a7b6-8a142112a50a" />

## STEP-2:  Extrude Rectangle 
Select the Extrude tool (E), choose the base profile, and extrude it upward by a thickness of 8 mm.

## STEP-3: Create the Vertical Support Block 
1. Select Create Sketch and click on the top face of the extruded base plate. 
2. Draw a rectangle of 40 mm and 10 mm positioned 
symmetrically between the two holes. 
3. Draw another rectangle perpendicular to the previous with 36mm and 12mm  
4. Click Finish Sketch.

<img width="742" height="480" alt="Screenshot 2026-11-19 233135" src="https://github.com/user-attachments/assets/f3dad3f2-fec0-4a56-af56-581456627536" />

## STEP-4: Extrude vertical support blocks 
Select the Extrude tool (E), select the rectangular profile, and 
extrude it upward by 32 mm. Ensure the operation is set to Join.

## STEP-5:   Create the Triangular Rib (Web) 
1. Select Create Sketch on the central vertical plane (XZ Plane). 
2. Use the Line tool to draw a triangle connecting the back face 
of the vertical block to the top surface of the base plate. 
3. Click Finish Sketch.

## STEP-6: Chamfer the triangular rib 
1.Select the modify tool and select chamfer type two direction. 
2.Set the thickness of the rib to 12 mm and ensure the operation 
is set to Join.

<img width="422" height="345" alt="Screenshot 2026-11-19 233251" src="https://github.com/user-attachments/assets/11982359-8464-4c8d-8177-10cff8f5e0ca" />
<img width="318" height="277" alt="Screenshot 2026-11-19 233258" src="https://github.com/user-attachments/assets/bcd882a6-b602-48ea-9233-17f50459e955" />

## STEP-7: Model the Upper Arm and Cylindrical Boss 
1.Select Create Sketch on the top face of the vertical block. 
2.Draw a line extending outward by 32 mm from the front face 
to define the center point of the upper cylinder. 
3.At this center point, draw two concentric circles: an outer 
circle of 30 mm and an inner hole of 20 mm. 
4.Use the Line tool to draw the connecting arm from the sides of the vertical block to the outer circle tangentially. 
5.Click Finish Sketch.

<img width="681" height="646" alt="image" src="https://github.com/user-attachments/assets/94173d9a-237e-4d00-9888-b27ded002fff" />

## STEP-8:  Extruding: 
1.Select the connecting arm profile and Extrude it downward by 
10 mm (Join operation). 
2.Select the outer ring profile of the cylinder and Extrude it 
upward by 10 mm to form the boss

<img width="646" height="542" alt="Screenshot 2026-10-15 110309" src="https://github.com/user-attachments/assets/98eaf332-59ef-4294-81b2-b7c8ea631559" />
<img width="400" height="297" alt="Screenshot 2026-10-16 010522" src="https://github.com/user-attachments/assets/395e1eda-c582-4473-b226-19d435397931" />

## STEP-9: : Final Inspection and Saving 
1. Go to File > Save and name the project. 
2. Select new file and draft the drawing of this model, show 3 
view of projections.

<img width="760" height="612" alt="Exercise 2 2 sketch" src="https://github.com/user-attachments/assets/c087049a-12a9-4ea2-a471-977fc565a39f" />

## INPUT:
![image](https://user-images.githubusercontent.com/113594316/198523331-05ace360-502b-4569-b9b4-31c60e3cd554.png)

## Output:
<img width="760" height="612" alt="Exercise 2 2 sketch" src="https://github.com/user-attachments/assets/1eb3e7aa-4ea1-4358-811a-2a09b5f96c2b" />
<img width="983" height="693" alt="Exercise 2 2 Drawing" src="https://github.com/user-attachments/assets/06c7b1f9-7c3d-4738-b762-e057643a529b" />

## RESULT: 
Thus, the 3D model is created from given isometric drawing.

ILANILA VINNARASI.K.V
26017175
15.10.2026


