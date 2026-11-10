# IntroductionToRobotics
UPTP 1151 Group **B2**, introduction to robotics (monday)
## Final proyect: Tic Tac Toe on EPSON robot
The proyect is composed of a 3D printed grid as the board, the pieces will be both tokens (as circles) and blocks (as crosses), the robotic hand will move each piece from the tray to the board.   
The first idea is to control the robot using the HMI, which will simulate the board and the players takes turns to move their respective pieces into a desired position within the grid, and the robotic hand will move on the physical board. 
There were difficulties working with the HMI before, so the alternative is to use the I/O Box to control the positioning.   
The system will include a start/stop button, and when a match is finished the robot will rearrange the pieces back to the tray, into the original position. It will also show a prompt in the HMI to start a new game or end the program.
### Things to do:
- [ ] 3D design of the board. Decide whether the grid will have the shape of the token and block or a blank space 
- [ ] Print the 3D design
- [ ] Select of positions on the workspace, calibration
- [ ] Program the motion of the hand. Includes the motion from tray to any position in the grid and back to the tray. 
- [ ] HMI (or I/O box) connection to the main program. Make the program respond to the actions of the HMI (or I/O box): selection of pieces, selection of cell, reset/accept buttons, restart/end. 
