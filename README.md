# XYYX-DAPLINK
STM32离线仿真器，下载器，支持VCOM，内置锂电池，电平支持5V/3V3程控切换，1.3寸LCD显示，输入输出过流保护，避免烧写供电过流导致烧写器复位。
# 硬件设计
1）STM32F103RET6主控MCU。  
2）USB TYPEC接口，支持在线仿真和离线烧写，支持在线串口。  
3）锂电池和USB供电。  
4）1.3寸LCD，6按键，上、下、左、右、确认、开关机，其中开关机可做取消按键。  
5）内置TI BQ21040DBVT锂电池充放电管理，为了安全锂电池采用高温型聚合物锂电池。  
6）输出电压可配置选择，5V/3V3,选择电平后相应输出同时改变。  
7）使用TI TPS2553DBVR 供电输出限流控制，避免输出过流导致仿真器复位。  
8）内置升压模块，保证电池供电电源稳定性，以及在电池供电情况下5V输出。  
     **硬件测试完成后会在 [玩客科技](https://siasevan.taobao.com) 开放购买链接。**
# 软件设计
1）软件参考[MBronsomOfflineSWD](https://github.com/MBronsom/OfflineSWD.git) 还有[志明电子](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.64bc2e8dq3TpiC&id=560296602843&_u=kaos6gq014c) 开源仿真器设计。  
2）LCD修改为1.3寸 240*240彩色LCD显示。 

# 项目进度
  1）2023-02-20 原理图设计完成，PCB开始打样。     



