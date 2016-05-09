# Installation_Will
Agenda of Will test.

Preparation: Ubuntu Backup USB and Wireless Mouse & Keyboard, J-link,  one Laptop with keil installation. 

1.  Ubuntu 14.01 USB steak installation.

2.  Modification of COMPUTER(Linux)'s IP. Default: 192.168.0.7 (randomly)  

3.  Lidar IP modification:  Firstly, "urg_setting_tool_ip", IP:192.168.0.10  
                            Secondly, "/bringup/launch urg_node.launch" ip_address: 192.168.0.10  

4.  dwa_local_planner_params.yaml -> #Goal Tolerance Parameters -> SET: yaw_goal_tolerance: 0.2.

4.  stm32 burn via latest greenrobot. J-link Driver is in the Ubuntu USB (/Keil/Jlink驱动). 

5.  Router implementatin. Router IP 192.168.0.1 ; NAME: hitrobot_test(randomly); code: hitrobot; Tryout: cmd -> ping 192.168.0.1

6.  Remote desktop. In the WINDOWS: Open mstsc.exe -> 192.168.0.1 -> vnc-any -> 192.168.0.1 (No password).

7.  Learning via aqmdbls_demo-c0.90.exe. Drivers(CP210x) -> aqmdbls_demo-c0.90.exe （通讯中断制动时间1.0秒   堵转停机时间2.0秒， others as usual）

8.  ..  
  
