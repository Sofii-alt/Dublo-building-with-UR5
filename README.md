
# Duplo Building with UR5

## Project Overview

This course project focused on programming a **UR5 robot** to build simple structures using **Duplo blocks**. The goal was to learn how to work with an industrial robot, understand its coordinate system, and create a reliable building process.

## Final Result

Video of the finished project:

*(Add video link here)*

---

## Project Workflow

The project was completed through the following steps:

- Choose a shape to build.
- Get familiar with the UR5 environment.
- Measure the dimensions of the Duplo blocks and the distances between placements.
- Define the robot's workspace and placement coordinates.
- Program the building process.
- Test and improve the program.
- Record a final demonstration video.

---

## Building Strategy

The building process was based on placing a single block correctly and then repeating that movement pattern across a layer. Once one layer was completed, the robot moved to the next layer and repeated the same process.

This made the code easier to manage since the same placement logic could be reused multiple times.

---

## Challenges

### Position Accuracy

One of the biggest challenges was getting the robot to place blocks accurately. Small positioning errors appeared during operation, especially when:

- Moving sideways between placements.
- Moving up to start a new layer.

To improve reliability, small offsets and correction values had to be added to the program.

### Gripper and Placement Issues

Another challenge was controlling how the robot released the blocks.

Problems included:

- Pressing too hard on already placed blocks.
- Releasing blocks too late.
- Misaligned block placement.

Even after adjusting the force settings, the robot occasionally caused blocks to shift. To improve stability, a support block was added in the middle of the structure.

### Understanding Robot Movement

A significant amount of time was spent understanding how the robot interprets movement commands and coordinate positions. Learning how the robot "sees" its environment and follows programmed paths was one of the most time-consuming parts of the project.

---

## What I Learned

Through this project I gained experience with:

- Programming a UR5 industrial robot.
- Coordinate systems and robot positioning.
- Motion planning and calibration.
- Debugging robotic systems.
- Handling real-world inaccuracies in automation.
- Designing a repeatable robotic building process.

---

## Conclusion

The project successfully demonstrated that a UR5 robot can be programmed to build simple structures using Duplo blocks. Although several challenges were encountered with positioning accuracy and block handling, these issues were addressed through calibration, code adjustments, and modifications to the building strategy.

Overall, the project provided valuable hands-on experience in robotics programming, robot control, and solving practical engineering problems.



### some in between videos
Video of the midpoint: 
picture of the code in Visual component

