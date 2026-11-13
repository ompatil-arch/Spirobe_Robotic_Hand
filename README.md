# SPIROBE — Bio-Inspired Robotic Tentacle
### Continuum Kinematics, Additive Manufacturing & Embedded Actuation
**Makerspace, Sanjivani University**

---

## 📌 Project Overview
**SPIROBE** is an innovative cable-driven soft robotic continuum mechanism inspired by the muscular hydrostat architecture and variable-curvature grasping capabilities of an octopus tentacle. Unlike conventional rigid robotic grippers with discrete pin joints, SPIROBE employs an interlocking 3D-printed vertebrae chain governed by logarithmic spiral kinematics to achieve conformable, passive-adaptive grasping of delicate and irregular payloads.

---

## 🔬 Key Engineering Features
- **Continuum Spiral Kinematics**: Variable curvature profile ($\kappa(s) = \kappa_0 s + \alpha s^{2.2}$) delivering stable wraps (>200° enclosure) around fragile and unknown geometries.
- **Antagonistic Cable Transmission**: High-tensile Dyneema tendon cables guided through low-friction vertebral eyelets driven by precision spool winches.
- **Embedded Actuation**: Dual 12V N20 gearmotors paired with an L298N H-bridge driver controlled by an onboard ESP32 32-bit SoC.
- **Additive Manufacturing**: Precision 3D-printed continuum vertebrae fabricated on high-speed Bambu Lab 3D printers using engineered PLA/PETG.
- **Interactive 3D CAD Workstation**: Complete parametric SolidWorks assembly (Assem1.SLDASM / Parts 1–6) viewable in the interactive web workstation.

---

## 🗂️ Repository Structure
```
├── assets/                  # High-resolution CAD renders, motion test videos, and textures
├── Part1.SLDPRT             # SolidWorks CAD Part 1: Actuator Mount Bracket
├── Part2.SLDPRT             # SolidWorks CAD Part 2: Finger Tie Link & Nut Bar
├── Part3.SLDPRT             # SolidWorks CAD Part 3: Tendon Drive Spool & Pulley
├── Part4.SLDPRT             # SolidWorks CAD Part 4: Palm Enclosure Chassis
├── Part5.SLDPRT             # SolidWorks CAD Part 5: Tendon Clamp & Retainer Bar
├── Part6.SLDPRT             # SolidWorks CAD Part 6: Custom Structural Base & Mounting Plate
├── index.html               # Main interactive project website & engineering workstation
├── index3.html              # Mirror backup
├── .gitignore               # Git ignore rules
└── README.md                # Project documentation
```

---

## 🚀 Live Preview / Local Setup
To run the interactive engineering workstation locally:
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Spirobe_Robotic_Hand.git
   ```
2. Open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari).

### Enable GitHub Pages (Free Web Hosting)
1. In your GitHub repository, go to **Settings** > **Pages**.
2. Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
3. Select `main` branch and `/ (root)` folder, then click **Save**.
4. Your website will be live at `https://<your-username>.github.io/Spirobe_Robotic_Hand/`.

---

## 👥 Project Team & Affiliations
- **Lead Mechanical Design & CAD Modelling**: Makerspace, Sanjivani University
- **Project Guidance**: Dr. Kiran Wakchaure Sir, Sanjivani University
- **Institution**: Makerspace, Sanjivani University (ज्ञानं दीप्यति जीवनम्)

