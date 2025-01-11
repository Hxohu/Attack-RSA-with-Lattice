# 格理论在RSA分析中的应用

本项目是对2024年密码数学挑战赛赛题1:RSA密码系统的特定密钥泄露攻击(第一部分)的总结。在pdf文档Attack_RSA_with_Lattice中介绍了格理论在RSA分析中的基础理论知识，其余html文档中为具体攻击代码，T1(其中记录了所有已解出赛题的答案)使用python内核即可运行，其余内核均为sagemath 9.5，T4与T12通过遍历一部分值求出结果，其中T4使用了[flatter](https://github.com/keeganryan/flatter)库加快LLL算法的运行速度(约5~6倍)使其能够在大约4小时内运行出结果。

在该赛题的第一部分中，仅有T3未解出结果。

本文的代码在软件平台AMD Ryzen 7 5700U处理器，16GB内存，Windows 11 64位操作系统上完成攻击。