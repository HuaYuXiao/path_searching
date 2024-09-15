# path_searching

![HitCount](https://img.shields.io/endpoint?url=https%3A%2F%2Fhits.dwyl.com%2FHuaYuXiao%2Fpath_searching.json%3Fcolor%3Dpink)
![Static Badge](https://img.shields.io/badge/ROS-noetic-22314E?logo=ros)
![Static Badge](https://img.shields.io/badge/C%2B%2B-14-00599C?logo=cplusplus)
![Static Badge](https://img.shields.io/badge/Ubuntu-20.04.6-E95420?logo=ubuntu)

The path_searching package, `Fast-Planner` & `EGO-Planner` & `PE-Planner`

### AStar-Search

- [astar.cpp](src%2Fastar.cpp)

### Fast-Planner

- [kinodynamic_astar_fast.cpp](src%2Fkinodynamic_astar_fast.cpp)
- [topo_prm.cpp](src%2Ftopo_prm.cpp)

### EGO-Planner

- [dyn_a_star.cpp](src%2Fdyn_a_star.cpp)

### PE-Planner

- [kinodynamic_astar_pe.cpp](src%2Fkinodynamic_astar_pe.cpp)

## Installation

```bash
git clone https://gitee.com/hyx020222/path_searching.git ~/easondrone_ws/plan/path_searching
cd ~/easondrone_ws && catkin_make --source plan/path_searching --build plan/path_searching/build
```
