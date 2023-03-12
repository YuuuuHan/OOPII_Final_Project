# OOPII_Final_Project
Using **Java language** to build GUI interface, and determine the movement strategy of the object through **different command** and **various algorithms**, including **DFS, BFS and UCS**, and the object can not collide with any obstacles in the process of movement.
## Illustrate
- **Map_id**:  Depending on the map_id, the displayed map style will be different.
- **JfScaler**: Use to set the map zoom size.
- **Milliseconds**: Use to set the speed of object movement.
- **Algorithm**:
  - If it is a **DFS algorithm**, the value is set to **0**.
  - If it is a **BFS algorithm**, the value is set to **1**.
## Run the project
Use **X2go** and run the project according to the following instructions:
```
1. javac A1073317_checkpoint7_DemoGame.java
2. java A1073317_checkpoint7_DemoGame map_id jfScaler milliseconds algorithm 
   (e.g. java A1073317_checkpoint7_DemoGame 0 4 20 1)
```
## Outcome
- This is the main object in the project - **Player**

![messageImage_1678591263471](https://user-images.githubusercontent.com/119481696/224555287-212e8ef0-0386-4059-b060-f5534b75d45e.jpg)
- When you want to move Player, you must **click** Player, and a **square border** will appear

![messageImage_1678591331604](https://user-images.githubusercontent.com/119481696/224555309-5ada361b-dba2-44b5-ab27-0cf55e8f252e.jpg)
- When Player **collides with an obstacle** while moving, it will **stop moving**

![messageImage_1678591313331](https://user-images.githubusercontent.com/119481696/224555337-e72d402f-e527-4822-b24a-7a46a2e20078.jpg)
- The following is the **correct** movement process:

![messageImage_1678591347743](https://user-images.githubusercontent.com/119481696/224555379-71bd5ce4-dfb2-4f95-974c-a6945c4f3beb.jpg)
- The following is the **wrong** movement process:

  - Because Player is beyond the boundary of the map
  
![messageImage_1678635595806](https://user-images.githubusercontent.com/119481696/224555539-b8016517-670c-4e62-9012-400ae8462e5a.jpg)
  
  - Because Player collided with the obstacle
  
  ![messageImage_1678591370225](https://user-images.githubusercontent.com/119481696/224555408-1d7732b4-5ae8-42e8-80a6-28dcafc30bf9.jpg)
