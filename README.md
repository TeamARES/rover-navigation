# Full Autonomous Stack 

### Process

1. Run the simulation
2. Build a map through SLAM
- To do 
  - Quality of the map is not good!
  - maybe need to use RTABMAP ros

3. Then launch the amcl node and give robot the initial pose

- amcl is working fine

4. Then launch the move-base node and move the robot from one point to another

- this is not working fine , see in para-meters what is the problem!
## To do:

1. use the maps of the turtlebot and try to run the amcl and move_base node on it

- Will have to launch my robot in the turtlebot world
- Use it's map and make the navigation work completely
- If it works fine!

2. Improve the maps by doing some modification to slam gampping or RTABMAP

