# KeliangFSACcode   
## HRT 23D电控程序
  这是2023FSAC使用的VCU程序，包括整车驱动、逻辑交互以及控制策略。无人车第一代下层控制策略尚不成熟，欢迎广大FSAC/FSEC以及汽车界各位前辈、同学以及学弟学妹们指正、补充。同时本代码开源在HRT电无人自主搭建的开源网站上，随后将发布。开源网站将发布所有上层感知与部分电气系统代码，欢迎同行们和我们一起助力FSAC/FSEC技术的发展。本程序基于matlab-simulink开发。包括设计了：无人意图转译、TCS限滑、差速横摆力矩控制、状态估计、无人转向、无人制动、自动标定以及整车驱动程序、整车逻辑控制程序等。    
我的邮箱是3594612631@qq.com。   
程序基于RapidECU-U4B开发。主控芯片MPC5744P。交互的硬件平台有：AMK控制器、MAXON EPOS4转向控制器、自研ESC（无人制动）、自研VCU（逻辑控制大头、ami）、INS570D（惯导＋rtk）、上层工控机（无需类型匹配，我们使用的是惠普）、自研EBS、转角编码器等 
我们的高速循迹视频：【2023 FSAC  HRT 高速循迹】 https://www.bilibili.com/video/BV1PN41137YF/?share_source=copy_web&vd_source=d1475b813d1042bf2cac3b302119b1d9
## HRT 23D electronic control program  
  This is the VCU program used by the 2023FSAC, including vehicle drive, logical interaction, and control strategy. The first generation of unmanned vehicle control strategy is not mature, welcome FSAC/FSEC and the automotive industry predecessors, students and younger students to correct and supplement. At the same time, this code is open source on the open source website independently built by HRT, and will be released later. The open source website will publish all the upper sensing and part of the electrical system code, welcome peers and us to help the development of FSAC/FSEC technology. This program is based on matlab-simulink. The design includes: unmanned intention translation, TCS limit slip, differential yaw moment control, state estimation, unmanned steering, unmanned braking, automatic calibration, vehicle driver program, vehicle logic control program and so on.  
My email address is 3594612631@qq.com.  
The program was developed based on RapidECU-U4B. Main control chip MPC5744P. Interactive hardware platforms are: AMK controller, MAXON EPOS4 steering controller, self-developed ESC (unmanned braking), self-developed VCU (logic control, ami), INS570D (inertial navigation +rtk), upper layer industrial computer (do not need type matching, we use HP), self-developed EBS, corner encoder and so on.   
Our high-speed tracking video:【2023 FSAC  HRT 高速循迹】 https://www.bilibili.com/video/BV1PN41137YF/?share_source=copy_web&vd_source=d1475b813d1042bf2cac3b302119b1d9   
