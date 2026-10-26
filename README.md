# Mechatronics Projects Pack
**Closed-Loop Control · Sensors · Actuators · Practical Robotics**

A structured collection of four foundational mechatronics projects designed to build real competence in closed-loop control and robotic systems.  
Each project is intentionally scoped so that a dedicated student can complete it, measure performance, and discuss engineering trade-offs in interviews.

---

## Projects Overview

| # | Project | Core Skills Developed | Difficulty | Est. Time |
|---|---------|-----------------------|------------|-----------|
| 01 | **Closed-Loop DC Motor Position Control + PID** | Encoder feedback, discrete PID, rise time / overshoot / steady-state error | Intermediate | 1–2 weeks |
| 02 | **Differential-Drive Robot** | Dual-motor speed control, sensor integration, basic mobile robotics | Intermediate | 2–3 weeks |
| 03 | **Self-Balancing Robot (Inverted Pendulum)** | Unstable plant control, IMU fusion concepts, aggressive PID / state feedback thinking | Advanced | 3–5 weeks |
| 04 | **2–3 DOF Servo Arm + Gripper** | Joint control, basic kinematics intuition, pick-and-place logic | Beginner–Intermediate | 1–2 weeks |

### Recommended Build Order
1. **01 – DC Motor PID** → Learn clean closed-loop fundamentals first  
2. **04 – Servo Arm** → Quick mechanical win + CAD practice  
3. **02 – Differential Drive** → Combine multiple actuators + sensors  
4. **03 – Self-Balancing** → Hardest control problem (do last)

---

## Repository Structure

```
arduino-mechatronics-projects/
├── 01-dc-motor-pid/
│   ├── README.md          # Full build + tuning guide
│   ├── BOM.md             # Parts list with alternatives
│   ├── motor_pid_position.ino
│   └── cad/
├── 02-differential-drive-robot/
├── 03-self-balancing/
├── 04-servo-arm/
├── shared/
│   ├── analysis/          # Python plotting helpers
│   └── cad-templates/
└── README.md
```

Each project folder contains:
- Detailed README (wiring, theory notes, tuning procedure, expected results)
- Bill of Materials
- Well-commented firmware
- CAD notes / templates where applicable

---

## Engineering Focus

These projects emphasize **measurable control performance**, not just “it works”:

- Rise time
- Overshoot percentage
- Settling time
- Steady-state error
- Disturbance rejection (where applicable)

Students are expected to log data, plot results, and document what failed and how it was fixed. This transforms hobby builds into credible engineering evidence.

---

## Hardware Notes

- Primary platform: Arduino Uno / Nano (ESP32 recommended for later projects)
- Access to a 3D printer is highly useful but not mandatory for first versions
- Multimeter and basic hand tools required

---

## Portfolio Advice

For maximum impact:
1. Record a short (30–60s) video of each system working under load/disturbance.
2. Capture and plot key performance metrics.
3. Write a short “Lessons Learned” section covering failures and iterations.
4. Keep the GitHub README as the single source of truth.

---

## License

Open for educational use. Modify and extend freely.

---

## Author

**Aboderin Logo** (`oluwadec`)  
Mechatronics Engineering Student  
Building practical competence in control systems and robotics software.

---

**Start here →** [`01-dc-motor-pid/README.md`](01-dc-motor-pid/README.md)
