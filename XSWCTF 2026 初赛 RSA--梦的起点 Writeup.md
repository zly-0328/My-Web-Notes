# [RSA--梦的起点] Writeup

## 📌 1. 题目基本信息
- **比赛/平台**：XSWCTF 2026
- **题目方向**：crypto
- **考点**：RSA
- **最终 Flag**：`XSWCTF{The_First_Flag_Yor_You}`

## 🎯 2. 解题思路与过程

1. **信息收集**：拿到题目是一个main.py文件，我先用 VS code打开是一段有关于RSA的代码，同时给出了其n，c，e，p的值
2. **尝试分析**：由于已知了其中的4个关键值n，c，e，p，所以可以尝试直接带入解密
3. **处理方法**：我使用在线dcode里的RSA解密工具，直接输入数据，得到flag
![[Pasted image 20261115215129.png]]

## 💻 3. 核心 工具

[RSA密码计算器](https://www.dcode.fr/rsa-cipher)