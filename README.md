# Minscape3-WRO-FutureENG-2025#
 Engineering Materials
This repository contains all the engineering materials for our
**Spike-based self-driving robot**, developed to compete in
the **WRO Future Engineers Competition – Season 2025**.
Designed with precision, creativity, and adaptability in mind,
this robot represents our team's vision for intelligent
navigation using sensor fusion and modular programming.
From conception to deployment, every part ofthis project is
a product of collaborative effort, critical thinking, and
engineering discipline.
## Content
- `Team_Photos`: Includes **2 team photos** - one official
(formal, high-resolution) photo used for submissions, and a
fun, candid team picture capturing our spirit and joy while
building the robot.
- `Vehicle_photos`: Contains **6 detailed images** of the
vehicle taken from every key angle: top, bottom, front, back,
left, and right. These images are useful for replication,
documentation, and visual inspections.
`video`: Contains the mp4 files showcasing both missions
along with a link to our demo video in the folder README file.
This video demonstrates the robot navigating a mock
environment, completing both mission objectives using
sensor feedback and precise movement logic.
`schemes`: Includes **connection diagrams and system
layouts** in JPG/PNG formats. These diagrams show where
and how all components (motors, sensors, and wires) are
connected on the Spike hub and structure.
-`src': Contains the full software stack used for both
**Mission 1** and **Mission 2**:
- **Spike Prime Code Files** (`.llsp3')
- **Block-based code screenshots**
- **Block Inline documentation** with clear module separation
- `models`: Includes files forthe predesigned robot versions
on the Studio 2.0 Software which gave us a look at both the
complete vision of the final product and the steps to build it.
## Introduction
Our robot is built using the **LEGO Spike Prime** robotics
platform and customized for autonomous navigation tasks
using advanced sensor strategies. It integrates both
mechanical engineering and software architecture in a
simple yet powerful design.
### Hardware Overview
**2x Ultrasonic Sensors** (left and right): Used for wallfollowing, corner detection, and path correction.
- **2x Color Sensors** (front): Help the robot detect colored
lines, nodes, and colored objects for mission guidance.
- **1x Motor** (rear): Controls forward and backward
propulsion.
**1x Motor** (front): Used for accurate front-wheel steering
similar to real vehicle dynamics.
- Robust chassis built using LEGO Technic elements to
ensure stability during turns and sudden stops.
## Code Architecture
Our robot's logic is divided into mission-specific modules
with reusable functions and clearly defined sensor-motor
mappings.
### Mission 1 —
This code has for objective to complete three full laps around the map without any obstacles. It uses the built in gyroscope to move straight and turns when one of the ultrasonic sensors detects a far larger distance than normal.
### Mission 2 -
This code has for objective to complete three full laps around the map with obstacles to avoid. Our code detects the objects while moving in the middle lain using the color sensors at the front of the vehicle.
## Uploading & Running the Code
1. Launch the **LEGO Spike Prime** software on your
preferred device.
2. Connect your robot via USB or Bluetooth.
3. Open the appropriate `.llsp3` code file depending on your
mission.
4. Verify sensor connections and motor ports (A, B, C...).
5. Deploy the code and press run. Mission execution should
begin automatically.
## Team Credits
We are a team of enthusiastic builders, programmers, and
future engineers who collaborated closely to bring this
project to life. We each brought our unique strengths in
design, coding, and testing.
- **Project Lead & Programmer**: Charbel
- **Mechanical Lead**: Charbel
- **Sensor Integration Specialist**: Jean-Paul
- **Tester & Calibrator**: Lama
- **Documentation & Media**: Charbel/Lama/Jean-Paul
See `Team_photos` for visuals of our awesome crew!
## Troubleshooting Tips
Here are common issues you might face and how to solve
them:
- **Color Sensor Not Detecting Properly**
- Ensure ambient light isn't interfering.
Clean the sensor lenses.
- Recalibrate using a white reference tile.
- **Robot Drifts or Turns Sharply**
- Recheck motor cables and steering motor alignment.
- Reduce speed if navigating tight curves.
**Code Not Uploading**
- Restart both the Spike app and the hub.
- Check Bluetooth/USB connection status.
- Refer to `other/upload_guide.md`.
**Ultrasonic Sensors Giving Zero Reading**
- Ensure sensors aren't too close to walls.
- Verify their field of view is not obstructed.
## Acknowledgments
-
We would like to thank:
Our coach for endless patience and guidance
- Our academy **Mindscape** for providing a well-suited
environment for us to participate in this competition.
- The WRO team for organizing this opportunity
- Each other, for the teamwork and the fun
Together, we turned curiosity into creation. Let's drive the
future, one mission at a time.