# drone-sim

*No source code because this was for a semester-long project where I worked in a team of 4 to create this drone simulation.

As a team, we practiced agile development while using Jira to manage our tasks and sprints. We also designed project extensions that utilized some of the design patterns learned duirng the semester. Lastly, we used Docker to practice containerization with our finished simulation. Our overall result for this project was an A :) 

[Demo Video](https://youtu.be/4glJjDvvXKY) (might be dead link)

## Overview

This project simulates a delivery service within the UMN campus, orchestrated by a drone and scheduled by the user. On the scheduling page, the user can schedule a package's starting point and destination, while also choosing a path strategy (Astar, BFS, DFS, Beeline, or Dijkstra) that the drone will exclusively follow to reach its destination (the robot). The user can choose which entity (drone, package, robot, helicopter or human) to track at any given time, as well as speeding up or slowing down the simulation. The user also has the opportunity to subscribe and unsubscribe from delivery notifications, as well as add as many random pedestrians within the simulation. The project also tracks entity data from the simulation which is output to the SimulationData.csv file in the root folder.

## What the Simulation Does
- Handles user input for package scheduling
    - Implements different pathing strategies
- Creates and removes entities
    - Creates some default starting entities
    - User can add more of certain entities
- Updates entities
    - Moves entities
    - Change entity states
    - Designate entity paths
- Tracks and outputs entity data to a file
- Displays event notifications
    - Ability to subscribe/unsubscribe to notifications
- Provides interactive web simulation
    - View and follow specific entities
    - Handles simulation time/speed
