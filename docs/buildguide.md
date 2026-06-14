---
icon: lucide/hammer
---

# BUILD GUIDE

## Overview
The system is composed of 4 stackable, removable modules:

-  **Battery Module** – power system and charging
-  **Sensing Module** – main calculation + air quality sensors
-  **Mechanical Module** – 'breathing' mechanism actuator
-  **Diffuser Module** – scent diffusion actuator



!!! note
    Each module can be built independently, but the recommended build order is:

    ==**Sensing → Battery → Mechanical → Diffuser**==


Each module consists of 2 main elements: the **shell/casing**, and a **wiring harness**, with the 
pogo-pin connecting elements attaching to both.

---

## Before You Start
asdfasdfasdfasdf

---

## SENSING MODULE
Short description of what this module does:
- Handles sensor readings
- Runs firmware
- Communicates with other modules
!!! note

    The sensing module should be built first, as no other module will function without being connected to this layer.

---

### Sensing Module Components

#### Electronics
- [ ] MCU / SBC: [name]
- [ ] Sensor 1: [name]
- [ ] Sensor 2: [name]
- [ ] PCB: [link or version]
- [ ] Connectors: [type]




#### Hardware
- [ ] Screws: [type/length]
- [ ] Standoffs: [type]
- [ ] Heat-set inserts: [spec]

> More info in [hardware](../hardware.md)


---

### Wiring Harness


> 📷 INSERT IMAGE HERE: `sensing_wiring_diagram.png`

#### Notes
- [ ] Power routing notes
- [ ] Signal lines
- [ ] Connector mapping

---

### Assembly – Electronics

Step-by-step:
1. [Step placeholder]
2. [Step placeholder]
3. [Step placeholder]

---

### Assembly – Enclosure

> 📷 INSERT IMAGE HERE: `sensing_shell_render.png`

- Link to printable files: [STL / STEP / repo link]
- Print settings: [material, layer height, infill]

Steps:
1. [Step placeholder]
2. [Step placeholder]

---

### Testing

- [ ] Power on check
- [ ] Sensor detection
- [ ] Serial output check
- [ ] Communication test with other modules

---

## BATTERY MODULE

> Power system and charging management.

- Battery storage
- Voltage regulation
- Charging circuit

---

### Battery Module components

#### Electronics
- [ ] Battery: [spec]
- [ ] Charging IC: [name]
- [ ] Voltage regulator: [name]
- [ ] Protection circuit: [if applicable]

#### Hardware
- [ ] Heat-set inserts: [spec]
- [ ] Screws: [spec]

---

### Wiring Harness

> 📷 INSERT IMAGE HERE: `battery_wiring_diagram.png`

Notes:
- [Power input/output paths]
- [Safety notes]

---

### Assembly – Electronics

1. [Step placeholder]
2. [Step placeholder]

---

### Assembly – Enclosure

> 📷 INSERT IMAGE HERE: `battery_shell_render.png`

- Print files: [link]

Steps:
1. [Step placeholder]

---

### Testing

- [ ] Charging test
- [ ] Output voltage check
- [ ] Load test

---

## MECHANICAL MODULE

> Structural layer – mounts everything together.

- Structural alignment
- Module stacking system
- Mounting system for airflow alignment

!!! warning

    Mechanical module should not be attached without first attaching a battery module. As the system will not be able to provide enough current through only the sensing layer.



---

### Mechanical Module Components

- [ ] Frame parts (3D printed / machined)
- [ ] Screws
- [ ] Inserts
- [ ] Gaskets (if used)

---

### Assembly

> 📷 INSERT IMAGE HERE: `mechanical_exploded_view.png`

Steps:
1. [Step placeholder]
2. [Step placeholder]

---

### Notes

- Alignment tolerances: [value]
- Tension points: [notes]

---

## DIFFUSER MODULE

> Controls airflow across sensors.

- Airflow shaping
- Dust / particle diffusion control
- Sensor exposure consistency

---

### Diffuser Module Components

- [ ] Diffuser body
- [ ] Mesh / filter material (if used)
- [ ] Fasteners

---

### Assembly

> 📷 INSERT IMAGE HERE: `diffuser_airflow_diagram.png`

Steps:
1. [Step placeholder]
2. [Step placeholder]

---

### Notes on Airflow Design

- Intended airflow path: [describe]
- Avoided turbulence zones: [describe]
- Calibration notes: [if relevant]

---

## FINAL ASSEMBLY

---

### Stack Order

Bottom → Top:

1. Battery Module  
2. Sensing Module  
3. Mechanical Module  
4. Diffuser Module  

---

### Final Wiring Check

- [ ] Power continuity across stack
- [ ] Signal continuity
- [ ] No shorts between modules

---

### Power-On Procedure

1. [Step placeholder]
2. [Step placeholder]
3. [Step placeholder]

---

### Calibration

- Sensor baseline calibration: [instructions]
- Environmental calibration: [instructions]

---

### Troubleshooting

#### Device does not power on
- Check: [placeholder]

#### Sensors not detected
- Check: [placeholder]

#### Erratic readings
- Check airflow / diffuser alignment

---

### Notes

[Any design philosophy, warnings, or quirks]

---

### Files & Resources

- CAD files: [link]
- PCB files: [link]
- Firmware: [link]
- Wiring diagrams: [link]