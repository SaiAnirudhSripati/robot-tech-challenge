Problem Description

- The application is a simulation of a toy robot moving on a square table with a dimension of 5x5
- No obstructions on the surface of the table
- The robot must be prevented from falling down.

Functional requirements:
The application will take the following commands

- PLACE X,Y,F
- MOVE
- LEFT
- RIGHT
- REPORT

->PLACE will put the robot at the X,Y postion with F facing EAST,WEST,NORTH or SOUTH
->The origin 0,0 shall be considered as the South West
->The first command that the application will take is the PLACE  ,only after that any other valid command can be issued,if any command is issued before the PLACE command then they shall be discarded
-> MOVE will move the robot by one unit in the direction that it is currently facing
->Left and right will the robot in the specific direction by 90 degrees without changing the position of the robot.
->Report will announce the X,Y and F of the robot in any form ,but standard form should be sufficient.
->The robot that is not on the table can ignore the MOVE,LEFT,RIGHT and report commands
->Input can be from a FILE or a Standard input
->Provide test data to exercise the application
Technical requirements:

- Rails,React,Postgres
- Should be hosted on AWS

Judgement based on

- Design
- Coding style
- Automated unit/ui testing

Deliverables
The code source files,test data and any test data all under a local GIT Repo
