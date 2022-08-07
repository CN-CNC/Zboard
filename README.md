
# Zboard 4轴CNC&3D打印主板

## 特点
1. 支持TMC2209驱动UART模式
1. 支持WIFI和Bluetooth远程控制
1. 内置WebUI上位机，可以不用安装上位机软件
1. 支持SD卡脱机，最大可支持32GB SD卡（TF卡）
1. 采用层叠技术，全模块化设计，可以很方便的替换损坏的模块
1. 硬件资源丰富，使用ESP32主控,主频高达240M，内存520KB，4M闪存，秒杀Arduino系列
1. 开源，方便按自己的需求修改源码
 
## 固件
- 3D打印固件：https://github.com/CN-CNC/Marlin.git

- CNC固件    ：https://github.com/CN-CNC/Grbl_Esp32


## 使用方法：

1. 用工程里面的PCB打板并购买电子元器件焊接好主板
1. 加@群#下载对应的固件源码
1. 编译并通过PCB上传到主板
1. 安装到机器上，调试运行即可