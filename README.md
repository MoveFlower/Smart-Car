# Smart-Car
这是我在2015年暑假凭兴趣制作的一款智能小车。  
该小车具有以下特点：  
* 利用车头的超声波传感器检测与障碍物的距离，以进行避障。  
* 利用舵机控制超声波传感器的转动，使检测障碍物更为灵活。

##效果演示
![car](https://github.com/Jason-Flash/Smart-Car/blob/master/image/SmartCar.gif)
##小车制作
###材料准备
* 51单片机开发板1个（注：也可使用其他开发板或自制板进行控制，接线方法和程序需要进行相应修改）  
* L298N电机驱动模块1个  
* HC-SR04超声波传感器1个  
* P0090舵机1个  
* 4轮驱动智能小车底盘1个  
* 双节18650锂电池盒1个
* 18650充电锂电池2节  
* 杜邦线若干根

###接线方法
* 单片机P34口接L298N的in1（注：可调整，但须对程序进行相应修改）  
* 单片机P35口接L298N的in2（注：可调整，但须对程序进行相应修改）  
* 单片机P36口接L298N的in3（注：可调整，但须对程序进行相应修改）  
* 单片机P37口接L298N的in4（注：可调整，但须对程序进行相应修改）  
* 单片机P32口接超声波模块ECH0  
* 单片机P33口接超声波模块TRIG  
* 单片机P03口输出PWM信号，控制舵机（注：可调整，但须对程序进行相应修改）

##程序编写
