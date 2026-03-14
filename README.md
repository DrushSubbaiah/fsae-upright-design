# FSAE Upright Design

Structural design and analysis of a Formula Student upright developed for the Velocita Racing car.  
This project focuses on designing a lightweight yet structurally robust upright capable of handling worst-case loads encountered during racing conditions.

---

## Project Overview

The upright connects the suspension, wheel hub, and braking system.  
It must withstand loads generated from braking, cornering, and vertical impacts while maintaining precise suspension geometry.

### Objectives
- Minimize component weight
- Maintain structural integrity under peak loads
- Ensure safety factor above acceptable limits
- Integrate with suspension and hub assembly

---

## Vehicle Suspension Setup

| Parameter | Value |
|-----------|------|
| Front Static Camber | -1° |
| Rear Static Camber | 0° |
| Toe | 0° |
| Application | Formula Student Race Car |

---

## Load Case Calculations

Worst-case loads were calculated based on vehicle dynamics and maximum expected racing conditions.

### Considered Load Cases

1. **Braking Load**
2. **Cornering Load**
3. **Vertical Bump Load**
4. **Combined Load Case**

The loads were applied to simulate the worst-case stresses experienced by the upright.

---

## Design Process

1. Determine suspension geometry constraints
2. Calculate worst-case loads
3. Create CAD model
4. Perform Finite Element Analysis
5. Optimize geometry to reduce weight

---

## CAD Model

Below is the CAD model of the upright.

![Upright CAD](https://github.com/DrushSubbaiah/fsae-upright-design/blob/main/rear%20explode.png?raw=true)
![Upright CAD](https://github.com/DrushSubbaiah/fsae-upright-design/blob/main/rear%20iso.png?raw=true)
![Upright CAD](https://github.com/DrushSubbaiah/fsae-upright-design/blob/main/rear%20iso2.png?raw=true)

---

## Load Application

For structural validation, the calculated loads were applied at the mounting points representing real suspension and hub connections.

![Load Case Diagram](images/load_case.png)

---

## Finite Element Analysis

FEA was conducted to evaluate stress distribution and deformation under worst-case loading conditions.

### Factor of Safety Distribution

![FOS Plot](https://github.com/DrushSubbaiah/fsae-upright-design/blob/main/rear%20up%20FOS.png?raw=true)

### Stress distribution

![Stress](https://github.com/DrushSubbaiah/fsae-upright-design/blob/main/rear%20up%20stress.png?raw=true)

---

## Results

| Parameter | Value |
|-----------|------|
| Material | Aluminium 7075-T6 |
| Maximum Stress | (347.75MPa) |
| Safety Factor | (1.42) |
| Weight | (720g) |

The design satisfies the required structural criteria while maintaining minimal weight.

---

## Tools Used

- CAD: SolidWorks
- Simulation: ANSYS
- Calculations: MS Excel

---

## Key Learnings

- Structural design under multi-directional loading
- Suspension component integration
- FEA-driven design optimization
- Load estimation for motorsport applications

---

## Team

Velocita Racing – Formula Student Team

Role: **Lead Suspension Engineer**

---

## Future Improvements

- Topology optimization for weight reduction
- Integration with hub assembly analysis
- Fatigue analysis for endurance conditions

---

## Author

Drush Subbaiah  
Mechanical Engineering Student  
Formula Student Suspension Lead  
Velocita Racing
