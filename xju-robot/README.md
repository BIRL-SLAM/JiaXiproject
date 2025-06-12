# XJU ROBOT
XJU-ROBOT is an open-source project based on ROS (Robot Operating System), providing a **simulation** environment for various heterogeneous robots. It integrates various algorithms such as **pnc**, **slam**, **perception**, etc., and can be used for relevant practitioners to study and develop.

**Table of Contents**
- [Getting Started](#getting-started)
- [License](#license)
- [Citation](#citation)

---

```bash
# Download code
git clone https://github.com/Mr-Tony921/xju-robot.git
git submodule init && git submodule update
# Install dependencies
bash install_dependencies.sh
```

## Getting Started

```bash
# Basic example of how to build and run
# Open one terminal
cd xju-robot && source devel/setup.bash
roslaunch xju_simu simple_world.launch
# Open another terminal
roslaunch xju_pnc move_base_flex.launch
```

## License

All resources in XJU-ROBOT are licensed under fully permissive licenses (e.g., Apache-2.0).

## Citation

If you use XJU-ROBOT, consider citing the following publication:

```
@inproceedings{tony2024xju-robot,
  title={xju-robot: A Robot Simulation Framework},
  author={Tony},
  url={https://github.com/Mr-Tony921/xju-robot.git},
  year={2024}
}
```
