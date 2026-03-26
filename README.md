# F8620 Quadcopter Drone Kit – Assembly & Operation Manual

Welcome to the official repository for the **F8620 Quadcopter Drone Kit** manual. This repository contains the complete assembly guide, technical reference, and operating instructions for building and flying the F8620 micro drone. Whether you are a hobbyist, student, or educator, this manual provides everything you need to understand the components, assemble the drone, and operate it safely.

---

## 📖 About This Repository

This repository hosts the **F8620 Quadcopter Drone Kit Installation Manual** in PDF format, along with supplementary documentation, assembly tips, and safety guidelines. The manual is designed for beginners and intermediate builders, explaining each step with detailed diagrams and explanations of key concepts such as coreless motors, electronic speed controllers (ESCs), flight controllers, lithium battery management, and remote control pairing.

**Key Files:**
- `F8620_Installation_Manual.pdf` – The full assembly and operation guide.
- `assembly_images/` – High-resolution images of each step (extracted from the manual).
- `quick_start.md` – A condensed step‑by‑step checklist for first‑time builders.

---

## 🚁 Drone Overview

The F8620 is a compact quadcopter designed for education and recreational flying. It features:

- **145 mm wheelbase** (motor‑to‑motor diagonal distance)
- **66 mm propellers** (one‑piece design)
- **Coreless brushed DC motors** – lightweight, rapid response, high torque‑to‑weight ratio
- **Integrated flight controller + ESC** – reduces wiring complexity
- **2.4 GHz remote control** with 4‑channel operation and 360° flip capability
- **600 mAh Li‑Po battery** with built‑in protection circuitry

---

## 📦 Components List

| Component | Quantity | Description |
|-----------|----------|-------------|
| Fuselage (3D printed PLA) | 1 | Main body with pre‑drilled mounting points |
| Carbon fiber rods | 4 | Arms for motor mounts |
| Motor mounts (3D printed) | 8 | Secures motors to arms |
| Coreless motors (CW/CCW) | 4 | 1–3A operating current, hollow‑cup design |
| Propellers (A & B) | 4 pairs | Marked "A" (clockwise) and "B" (counter‑clockwise) |
| Flight control board | 1 | Integrated ESC, gyroscope, receiver |
| Battery (600 mAh Li‑Po) | 1 | 3.7V nominal, with protection board |
| Remote control | 1 | 4‑channel 2.4 GHz transmitter |
| Accessories | – | Screws, tool for propeller removal, button labels |

---

## 🛠️ Assembly Overview

The manual guides you through six main assembly stages:

1. **Frame Assembly** – Attach carbon fiber rods to the fuselage and motor mounts.
2. **Motor Bracket & Motor Installation** – Secure motors to mounts, route cables.
3. **Propeller Installation** – Match marked propellers to correct motor rotation direction.
4. **Flight Control Module** – Connect motors to the integrated ESC/FC board.
5. **Battery Mounting** – Secure the battery and connect the power leads.
6. **Remote Control Setup** – Insert batteries, install joysticks, and bind with the drone.

> **⚠️ Important:** Always verify the orientation of the flight controller (front marked by power cable) and check propeller rotation direction before applying power.

---

## 🔧 Key Technical Concepts

### Coreless Motors (Hollow Cup)
- **Rotor:** Cup‑shaped coil without an iron core → low inertia, fast response.
- **Stator:** Permanent magnets.
- **Advantages:** High power density, low EMI, low cost.
- **Lifespan:** 200–500 hours due to brush/commutator wear.

### Propellers
- **Diameter:** 66 mm (inches: 2.6").
- **Pitch:** 45 mm (affects thrust and speed).
- **Markings:** "A" = clockwise rotation, "B" = counter‑clockwise rotation.  
  *Incorrect installation will cause the drone to flip on takeoff.*

### Flight Control & ESC
- The flight controller receives commands from the remote, processes gyroscope data, and sends PWM signals to the integrated ESCs to adjust motor speeds.
- ESC is integrated onto the same board, simplifying wiring.

### Lithium Battery Safety
- **Capacity:** 600 mAh.
- **Discharge rate:** 25C (max continuous current 15A).
- **Charging:** Use a dedicated Li‑Po balance charger; never leave charging unattended.
- **Storage:** Store at ~3.85V per cell if not used for extended periods.
- **Warning:** Do not puncture, crush, or overheat. Swollen batteries must be discarded properly.

### Flight Time Estimation
- Hover current per motor ≈ 1.5 A → total current ≈ 6 A.
- With 600 mAh battery:  
  **Flight time ≈ 600 mAh × 60 min / (6000 mA) ≈ 6 minutes** (hovering).  
  Aggressive flight reduces this time.

---

## 🎮 Operating Instructions (Summary)

1. **Pre‑flight Preparation**
   - Charge battery fully.
   - Place drone on a level, obstacle‑free surface.
   - Insert battery and press the power button on the flight controller.

2. **Binding & Calibration**
   - Power on remote control (LED solid).
   - Automatic frequency matching occurs – drone LED becomes solid when bound.
   - Press gyro calibration button; LED flashes then turns solid when complete.

3. **Arming & Takeoff**
   - Push left throttle stick up once → propellers spin (pre‑flight state).
   - Push again → throttle increases; drone lifts off.

4. **Flight Controls**
   - **Left stick:** throttle (up/down) and yaw (left/right rotation).
   - **Right stick:** pitch (forward/back) and roll (left/right movement).

5. **360° Flip**
   - Press the flip button, then flick right stick in any direction → drone performs a roll.

> **⚠️ Never attempt flips near people or obstacles. Perform only in open spaces.**

---

## 📚 Additional Resources

- **PDF Manual:** [F8620_Installation_Manual.pdf](F8620_Installation_Manual.pdf)
- **Troubleshooting Guide:** See pages 23‑24 of the manual for common issues (e.g., motor not spinning, LED flashing codes).
- **Safety Guidelines:** Always fly in accordance with local regulations. Keep drone within line of sight.
- **3D Print Files:** The fuselage and motor mounts are 3D printed. You can find the STL files in the `3d_models/` folder for replacement or customization.

---

## 🤝 Contributing

If you have improvements to the manual, additional tips, or want to contribute translations, please open an issue or submit a pull request. All contributions are welcome.

---

## 📄 License

The content of this repository (including the manual) is shared under the **Creative Commons Attribution‑NonCommercial‑ShareAlike 4.0 International (CC BY‑NC‑SA 4.0)** license. You are free to share and adapt the material for non‑commercial purposes, provided you give appropriate credit and license your adaptations under the same terms.

---

## 🙏 Acknowledgements

This manual was created based on the original F8620 drone kit documentation. Special thanks to the designers and testers who made this educational drone possible.

---

**Happy flying!** 🚀  
*For questions or support, please open an issue in this repository.*
