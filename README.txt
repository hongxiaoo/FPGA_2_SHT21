﻿FPGA2SHT21_1.1.1.190423_alpha
将根据MSP430的函数与文件结构，构建一个属于FPGA的，且具有较强兼容性的IIC通信代码,基于FPGA2SHT21_1.1.1.190412_base的状态机版本进行修改。

于2019年4月26号正式实现IIC通信大部分功能，但在示波器中stt和stp时的scl信号还有拖尾信号出现，将在下一个版本中进行优化，stop模块和scl模块中还存在部分问题使得有时候程序不能正常运行。