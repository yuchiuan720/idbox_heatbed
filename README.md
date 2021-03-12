# idbox_heatbed
customer for id-box  3d print  head bed part 

總電阻:6.5R 1-3:3.7R 1-2:3.2R

PID 自動校準功能 須開啟 #define PIDTEMPBED

使用 M303 E-1 S90 C8 進行PID校正

再寫入KP KI KD 


Hi. I have problém with heating bed
If i set some temp heating stop 10 degree leds for example set 60*c hotbed stop heating 50 *c
But If i try calibrate PID heating is ok
Please help
Marlin firmware 2.0.4
Skr 1.3
