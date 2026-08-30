# Freedom

# FREEDOM
**3lb Vertical Spinner Combat Robot**
<br>
**Villanova Combat Robotics | National Havoc Robotics League (NHRL)**
<br>
**Role: Frame and Armor Lead**

<!-- HERO IMAGE: final photo of the bot, or CAD render if photo isn't available -->
<img src="assets/CombatRobotCompImage.png" width="55%" />

## Overview

FREEDOM is a 3lb vertical spinner combat robot built for the National Havoc Robotics League (NHRL), one of the largest competitive combat robotics circuits in the country. FREEDOM was part of the first cohort of robots Villanova Combat Robotics ever brought to competition, and the club's first appearance at NHRL.

As The Frame and Armor Design Lead, I focused on the frame and supporting joint system: selecting parts, designing and iterating the CAD in SolidWorks, machining the components on a lathe and mill, and integrating the electronics (soldering, motor controller tuning, and receiver configuration) needed to get the system running reliably in competition. Beyond the weapon system, I also supported the build more broadly. I collaborated with teammates on integration across subsystems, weighed in on part selection for the platform, contributed to chassis design, and tracked the robot's weight against the 3lb limit using a shared weight budget spreadsheet. I also assisted with machining and electronics work outside my own scope. As this was Villanova Combat Robotics' first competition build, most of the process was worked out as a team in real time. That meant frequent coordination on design tradeoffs and build priorities across the group.

## Bill of Materials
| Component | Function | Part | Photo |
|---|---|---|---|
| Weapon Motor | Drives the weapon system | BadAss 2315-1480Kv Brushless Motor | <img src="assets/WheelMotor.jpg" width="80" /> |
| Drive Motor | Powers wheel drivetrain | Max Brushless 2006 Mk2 Beetleweight Planetary Gearmotor | <img src="assets/DriveMotor.webp" width="80" /> |
| Weapon ESC | Controls weapon motor speed | Vortex 80A ESC (Beetle Weapon / Big Bot Drive) | <img src="assets/WeaponsESC.webp" width="80" /> |
| Weapon Metal | Raw stock for weapon fabrication | 2" Alloy Steel Round Bar, 4140 Annealed, Cold Finish | <img src="assets/ESC.webp" width="80" /> |
| Dead Shaft Metal | Raw stock for dead shaft fabrication | 1/2" Alloy Steel Round Bar, 4140 Annealed, Cold Finish | <img src="assets/DeadShaft.jpg" width="80" /> |
| Chassis Material | Lightweight structural plate for chassis | Carbon Fiber Plate | <img src="assets/CarbonFiberPlate.jpg" width="80" /> |
| Ball Bearings | Support rotating shafts | TRITAN Radial Ball Bearing 6000, Dbl Sealed, 10 mm Bore, 26 mm OD, 8 mm Wd | <img src="assets/BearingCombat.jpg" width="80" /> |
| Timing Belt Pulley | Transfers rotational drive to belt | High-Strength GT Timing Belt Pulley, Press-Fit, 9 mm Max Belt Width, 3/16" Shaft, 16T | <img src="assets/TimingBeltPully.png" width="80" /> |
| Timing Belt | Transmits drive motor power | High-Strength Ultra-Quiet Timing Belt, Curved Teeth, 9 mm, 165-3P-09, Gates PowerGrip GT | <img src="assets/TimingBeltcrop.png" width="80" /> |
| Wheels | Provide traction/mobility | BaneBots Wheel, 2" x 0.8", Hub Mount, 50A, Blue | <img src="assets/Wheelscombatrobot.jpg" width="80" /> |
| Wheel Hubs | Mount wheels to drive shaft | T81 Hub, 6 mm Shaft | <img src="assets/T81H-RM61__49607.jpg" width="80" /> |
| Transmitter | Sends control inputs to robot | FlySky FS-i6 6CH Transmitter | <img src="assets/RecieverBOM.jpg" width="80" /> |
| Receiver | Receives transmitter signal, outputs to ESCs | FlySky FS-iA6B 6CH Receiver | <img src="assets/Screenshot 2026-08-14 005118.png" width="80" /> |

## Design & CAD
The frame system went through multiple design iterations in SolidWorks before being finalized for machining. As Frame Systems Design Lead, this design work, and the machining that followed, was my primary responsibility on the team. Design iterations were mainly focused on maneuverability, deflecting oponents weapons, handling weapon vibration, and weight. Throughout this process, I worked closely with the weapons team to make sure the weapon would mount correctly, function as intended within the chassis geometry, and stay within the robot's overall weight budget.

### Frame
<img src="assets/Screenshot 2026-08-30 161739.png" width="60%" />

*Initial view of the side frame. Frame uses slotted connections as a redundancy to screw connections. Material was hollowed in locations seeing less fatigue from the motor.*

<img src="assets/Screenshot 2026-08-30 161957.png" width="60%" />

*Initial view of the front frame grille. Slotted front protects from debris from combat while staying mindful on weight*

<img src="assets/Screenshot 2026-08-30 161627.png" width="60%" />

*Initial assembly of the full frame with internals shown. Wheels were placed internal to the frame to protect from damage from the side, TPU was placed on the outside to absorb initial attack and prevent debris from hitting critical section*

### Chassis
<!-- CHASSIS CAD -->
<img src="assets/CADCombatRobot.png" width="60%" />
<!-- WEAPON CAD -->
<!-- <img src="assets/freedom-weapon-cad.png" width="49%" /> -->

*Chassis CAD, built around a low-profile carbon fiber plate to minimize weight while protecting the drivetrain and electronics.*

## Fabrication

<!-- PLA PROTOTYPE -->
<img src="assets/FREEDOMPLACROPPED.jpeg" width="56%" />

*Once the design was validated in PLA, the final frame system components were machined from 5052 Alloy aluminum on a cnc mill. Final post processing used a rasp to meet tolerances*

## Electronics

Electronics was another main area where I worked closely to with fellow teams to ensure the internal systems had the proper spacing. Electrical integration covered the full signal and power chain: soldering motor and battery connections, tuning the weapon and drive ESCs for consistent throttle response, configuring the receiver (mapping controller inputs to the correct channel outputs), and adjusting the throttle curve to fine-tune drive responsiveness for competition conditions.


<img src="assets/ElectronicsCrop.png" width="57%" />

*PLA prototype with electronics installed for driving test.*

<img src="assets/IMG_1314.jpeg" width="35%" />

*FlySky transmitter subtrim configuration, used to fine-tune channel centering and drive responsiveness ahead of competition.*

## Testing & Demo

<!-- DRIVING DEMO VIDEO -->
<video src="https://github.com/user-attachments/assets/a1d59dde-191d-4497-a97f-fc3ec471614c" controls width="200"></video>

*FREEDOM's drivetrain under remote control. The weapon system isn't shown here, as no safe testing environment was available prior to competition.*

## Status

FREEDOM competed at NHRL as part of Villanova Combat Robotics' first-ever competition cohort. The night before competition, the CNC machine's chuck shattered with no replacement available, forcing the team to manually machine key weapon features under significant time pressure. This left no window to test the weapon system before competition, and the resulting parts had tolerance and balance error that the manual process couldn't fully control. Under competition RPM, this caused the weapon to vibrate loose mid-match, and the bot was eliminated quickly as a result. The weapon system, from CAD through machining and electrical integration, was designed, built, and fielded as a complete, competition-ready system, and this experience directly shaped both the lessons below and my priorities heading into this year's build.

## Lessons Learned

- **Build in schedule margin.** With no buffer before competition, a single equipment failure eliminated the ability to test before fielding the robot. Future builds need machining and assembly finished with enough lead time to survive a setback like this.
- **Choose materials and manufacturing wisely** The internal wheel design increased the overall weight of the frame. This lead to future issues in the weight. Additionally high strength materials are only needed in critical areas. Most design used UHMW, a thermoplastic with high impact strength, and provided extra protection with TPU. 
## Future Work

This year, I'm stepping into a broader leadership role as co-lead for the entire robot, directing mechanical design and build scheduling across all subsystems, while continuing to lead weapon system development directly. I'm also developing my skills in FEA to provide the necessary structure in the most critical areas. Planned changes for the next build include:

- **Effective balance of material strength** Aluminum was spread across the design which made the design underachieve in critical areas and made reaching weight difficult 
- **Redesign Frame shape** Most competitive designs minimised connections by hardware besides replaceable parts. Ensuring frame is secure and can support assembly and quick repairs is a priority. 
- **Building schedule margin and equipment contingencies into the build timeline**, so a single point of failure can't eliminate the team's ability to test before competition
