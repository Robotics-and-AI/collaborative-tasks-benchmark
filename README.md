# Building Benchmark (BB)
<img src="https://github.com/Collaborative-Robotics-and-AI/BuildingBenchmark/blob/main/AssembledBenchmark.png" width="800">

## Introduction
Benchmarks are crucial to help robotics research advance in an efficient and standardized manner, however, the collaborative assembly field lacks a benchmark with multiple tasks of varying task complexity. As such, we propose the Building Benchmark (BB). It contains 7 distinct tasks ranging from easy to difficult assembly scenarios, each with 1 to 3 parts, providing a rich environment for studying collaborative assembly systems. Its design was grounded on the following criteria:

- Contain independent sequential assembly tasks 
- Tasks have a wide variety of sturdy and graspable 3D printable pieces
- Each piece has its own distinguishable features. 

The benchmark mainly focuses on assisting in the development of collaborative systems, though it is also applicable towards
any combination of its inherent sub-systems: task sequencing allocation, fully-robotic assembly, robot pick-and-place operations and visual perception.

## Task description
The proposed benchmark is representative of a city landscape and contains a total of 7 unique tasks. The main assembly operations are wide tolerance insertion (WTI), tight tolerance insertion (TTI), screw fastening, snap fitting and two-handed actions.

| Building | Color                                                                                           | # of parts | WTI   | TTI   | SCREW | Snap-fit | Two-handed |
| :------: | :---------------------------------------------------------------------------------------------: | :--------: | :---: | :---: | :---: | :------: | :--------: |
| Museum   | <img valign='middle' alt='green' src='https://readme-swatches.vercel.app/089b00?style=round'/>  | 1          | X     |       |       |          |            |
| Snap     | <img valign='middle' alt='yellow' src='https://readme-swatches.vercel.app/d9d92e?style=round'/> | 3          | X     | X     |       | X        |            |
| Bridge   | <img valign='middle' alt='orange' src='https://readme-swatches.vercel.app/ff7700?style=round'/> | 3          | X     | X     |       |          |            |
| Triangle | <img valign='middle' alt='red' src='https://readme-swatches.vercel.app/bb0000?style=round'/>    | 1          | X     |       |       |          |            |
| Wheel    | <img valign='middle' alt='blue' src='https://readme-swatches.vercel.app/363e8e?style=round'/>   | 2          | X     |       | X     |          | X          |
| Dovetail | <img valign='middle' alt='black' src='https://readme-swatches.vercel.app/000000?style=round'/>  | 2          | X     | X     |       |          |            |
| Hospital | <img valign='middle' alt='white' src='https://readme-swatches.vercel.app/ffffff?style=round'/>  | 3          | X     |       | X     |          |            |

## Benchmark deployment
**Essential benchmark elements:**
  - 3d print tasks and base:
      - 520g of PLA
      - 25 hours

**Screw fastening operations:**
  - 4 M5x30 screws
  - 4 DIN 940 M5 nuts

**Fix base to an extrusion table plate:**
  - 3d print corner pieces:
    - 20g of PLA
    - 1 hour
  - 4 M4 x 20 screws
  - 4 adequately sized M4 T-nuts
