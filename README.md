1.全局规划：使用 ROS 中的 Navigation Stack 进行全局规划，参数文件move_base.launch位于wpb_home
2.地图生成和保存，导航：wpr_simulation
3.使用 DWA 算法进行局部规划，配置参数文件dwa_local_planner_params.yaml,代码记录于dwaymal
4.编写 ROS 节点控制机器人按照规划路径行驶,代码位于control.py
