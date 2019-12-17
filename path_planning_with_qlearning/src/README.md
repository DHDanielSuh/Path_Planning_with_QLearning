# Path Finding using A star, Wavefront, and Reinforcement Learning

The project aims to let the robot find the route to its destination using three algorithms: `A star`, `Wavefront`, and `Reinforcement Learning`.
All learning progress is done in Gazebo Simulator. 
The Scripts folder contains the `A_star_Wavefront.py` and `Q_Learning.py` files. 
In the case of the `A_star_Wavefront.py` file, you can specify the starting point and the ending point in the code. 
In the case of `Q_Learning.py`, hyperparameters can be adjusted in the code. 
When entering hyperparameters such as `[x, y, z]`, each of the three cycles is performed using `x`, `y`, and `z` as hyperparameters.
After reinforcement learning is completed, they will be saved for each session in the `dqnmodels` folder, and you can compare the results with a plot of the scores in each `Session` folder.


0. Launch Gazebo environment by running
```console
    $ roslaunch path_planning_with_qlearning brick_world.launch
```
1.  
    - Run A Star and WaveFront script with 
```console
    $ rosrun path_planning_with_qlearning A_star_Wavefront.py
```

   - Run Reinforcement Learning script with 
    
```console
    $ rosrun path_planning_with_qlearning Q_Learning.py
```

