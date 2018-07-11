# Pendulum
倒立摆

倒立摆一直是研究控制算法很好的典型结构。
在学习了《经典控制理论》和《现代控制理论》之后，一直没有实际的接触过真正的控制算法。
所以利用空闲时间搭建了一个简易环形倒立摆。

模块：
大扭矩自带编码器无差电机。
大功率mos管驱动芯片BTN7971搭建的全桥驱动电路。
STM32C8T6主控芯片。
欧姆龙500线高精度编码器


利用串级PID算法，让摆杆和旋臂保持在一个特定的位置。

