# Rubik's Cube Solver

Fully 3-d printed rubik's cube solver that can solve a 3x3 rubik's cube in under 5 seconds.

## Design Rationale

The motor and cube connectors were the first pieces to be designed and fabricated. These pieces had to be tolerenced perfectly as if they were too loose, it would slip and too tight 
then it would be really hard to remove it. After a lot of testing and printing, I arrived at the perfect dimensions that ensure a smooth fit with minimal sliding. Moreover, in order
screw holes were implemented on the side in the offchance that these piece rub on each other and get loose after a lot of testing.

The main design constraint was coming up with a solution to securely harness each stepper motor to each face of the cube. Each motor weighs ~1 lb so 
so the column pieces had to be strong enough to support it while vibrating at max speed. The dimensions were measured using vernier calipers and a tolerance range of 8-10% was used.
I had also implemented a honeycomb design on the side for extra ventiliation. Finally, screw tabs were added so that motor can be screwed into the column. 

One goal I had with the base plate and the arch was to keep the filament usage down to a minimum. I have employed the use of pattern to hollow out these pieces so that less material would be used.
For the arch, I had initially envisioned to use neodynium magnets for easy removal of the cube. However, this proved not to be strong enough upon further testing, therefore I went with the good old 
screws and nuts on the side of the arch. For the base plate, similar design changes were made and each of the four columns, along with the bottom motor can be screwed directly onto the base plate.

<table align="center">
  <tr>
    <td style="padding-right: 30px;">
      <img src="https://github.com/user-attachments/assets/39f6f25a-be3d-4f7f-8062-5a38d182007d" width="300" height="325" alt="Caption for Image 1">
      <br>
      <span>Caption for Image 1</span>
    </td>
    <td style="padding-right: 30px;">
      <img src="https://github.com/user-attachments/assets/587ea7bb-412a-4587-a774-4b750834dfb9" width="300" height="325" alt="Motor screwed into the arch">
      <br>
      <span>Motor screwed into the arch</span>
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/33d7a88a-f11e-475a-b96d-aa0618fbc637" width="300" height="325" alt="Assmebly rendered in SolidWorks">
      <br>
      <span>Assmebly rendered in SolidWorks</span>
    </td>
  </tr>
</table>



## Fabrication
The enclosure, connectors and motor holders were fully 3d printed on my Elegoo Neptune 3-pro printer using PLA and sliced using Cura. The trickiest part to print by far was the base plate since it took up whole build volume of my printer. The first time I printed it, I ended up with a mess since I forgot to properly configure the bed adhesion setting in Cura.
### Print Settings:
  - Nozzle temp : 210° C, Heatbed : 50° C
  - 10% infill on base plate with 3 walls
  - 15% infill and 2 walls on other parts
  - Tree supports for the base plate

<table align="center">
  <tr>
    <td style="padding-right: 20px;">
      <img src="https://github.com/user-attachments/assets/a1777398-3f4c-4e38-b37d-64ee500cf129" width="300" height="400" alt="Caption for Image 1">
      <br>
      <span>Base Plate Print ~24 hours <span>
    </td>
    <td style="padding-left: 20px;">
      <img src="https://github.com/user-attachments/assets/d2b14d99-aa1b-4cbd-bc4d-afd8e5e15eba" width="300" height="400" alt="Caption for Image 2">
      <br>
      <span>Failed due to poor adhesion :(</span>
    </td>
  </tr>
</table>







