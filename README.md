# codeLockNew 
## 北京邮电大学2019级信通院数字电路设计课程第四周实验题目
## 说明
是使用Verilog语言，配合小脚丫STEP-MAX10实现的可更改密码的四位密码箱（标题里的“New”是因为并非完全原创）。  
板载主控：10M02SCM153

## 开发工具
IDE：Quartus Prime Lite Edition 18.1

## 来源
https://github.com/Clouds42/FPGA_Verilog_MySafe 是主要功能来源，密码更改功能由笔者自行编写。

## 功能特色
1.简明的状态提醒：使用LED灯表示解锁状态和密码校验正误。  
2.友好的交互：使用四位拨码开关输入密码，按键解锁。  
3.丰富的功能：可以通过板载按键自定义密码。  
