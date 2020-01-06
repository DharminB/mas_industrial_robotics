# New planning pipeline

- Launch main launch file
  ```
  roslaunch mir_task_planning tutorial_01.launch
  ```

- To generate problem
  ```
  rosservice call /rosplan_problem_interface/problem_generation_server "{}" 
  ```

- To plan
  ```
  rosservice call /rosplan_planner_interface/planning_server
  ```

