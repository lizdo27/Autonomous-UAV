# \# 🚁 Custom-Built Autonomous UAV: ROS2 \& Edge AI Integration

# 

# \## 📌 Project Overview

# This repository documents the mechanical fabrication, hardware assembly, and ongoing software integration of a custom-built autonomous Unmanned Aerial Vehicle (UAV). Unlike off-the-shelf drone kits, this quadcopter features a fully custom-designed frame using carbon fiber tubes and 3D-printed joints. The ultimate goal is to bridge traditional flight control systems with Edge AI computing by integrating an Nvidia Jetson Nano via ROS2 (Robot Operating System 2).

# 

# \## 📸 Hardware Showcase

# !\[Custom Drone](./Media/UAV.jpg)

# \*(Note: Displaying the custom 16mm carbon fiber frame and 3D-printed mechanical joints).\*

# 

# \## 🛠️ Detailed Bill of Materials (BOM)

# 

# \*\*Avionics \& Navigation:\*\*

# \- \*\*Flight Controller (FC):\*\* MicoAir H743 V2

# \- \*\*Companion Computer:\*\* Nvidia Jetson Nano (for Edge AI processing)

# \- \*\*GPS Module:\*\* BH-222Q

# \- \*\*Compass:\*\* HMC5883L

# 

# \*\*Propulsion \& Power:\*\*

# \- \*\*Motors:\*\* 3115 - 900KV Brushless Motors

# \- \*\*Propellers:\*\* 7-inch 3-blade props

# \- \*\*Battery:\*\* LiPo 4S 5500mAh (Optimized for extended flight time and payload capacity)

# 

# \*\*Communication:\*\*

# \- \*\*Transmitter:\*\* RadioMaster Pocket

# \- \*\*Receiver:\*\* ELRS 2.4GHz 

# 

# \*\*Mechanical \& Structural:\*\*

# \- \*\*Frame Arms \& Landing Gear:\*\* 16mm Carbon Fiber Tubes (Custom cut to 25cm arms).

# \- \*\*Joints \& Mounts:\*\* Fully custom 3D-printed structural parts (motor mounts, FC/ESC base, tube connectors, and propeller guards).

# 

# \## 👨‍💻 My Core Contributions (Hardware \& Mechanics)

# As the primary hardware/mechanical engineer for this system, my contributions include:

# \- \*\*Custom Frame Fabrication:\*\* Rejected standard pre-built frames in favor of designing a modular quadcopter frame. Sourced 16mm carbon fiber tubes and precisely cut them for the arms and landing gear.

# \- \*\*Advanced 3D Modeling:\*\* Utilized Autodesk Fusion to design all structural nodes. This includes the central electronics base for the FC/ESC, secure motor mounts, and custom joints that seamlessly clamp onto the carbon fiber tubes. 

# \- \*\*Assembly \& Integration:\*\* Executed the complete physical build, precision soldering for high-current propulsion systems, and organized cable management to minimize electromagnetic interference (EMI) with the compass and GPS.

# \- \*\*Next Steps:\*\* Currently researching serial communication (MAVLink/Micro-XRCE-DDS) to bridge the Nvidia Jetson Nano with the MicoAir FC for ROS2-based autonomous navigation.

# 

# \## 📁 Repository Structure

# \- `/3D\_Models`: Contains the custom .STL files for the joints, motor mounts, and central base.

# \- `/Media`: Images documenting the drone's structural assembly and testing.

