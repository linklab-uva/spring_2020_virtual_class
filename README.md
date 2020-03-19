## Common Grounds Sim v1

For official use on CS servers only  

**Currently deployed on gpusrv05.cs.virginia.edu**  

First, set Gazebo to run headless using `xvfb-run`, default screen 0 at `1920x1080` using 16 bit color

```
user@remote-server: Xvfb --shmem --screen 0 1920x1080x16 &
```

Master launch command:

```
user@remote-server: roslaunch spring_2020_virtual_class simulator.launch
```
