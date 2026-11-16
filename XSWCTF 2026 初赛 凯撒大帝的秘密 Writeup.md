# [凯撒大帝的秘密] Writeup

## 📌 1. 题目基本信息
- **比赛/平台**：XSWCTF 2026
- **题目方向**：Crypto
- **考点**：bacon
- **最终 Flag**：`XSWCTF{w31com3_t0_crypt0}`

## 🎯 2. 解题思路与过程

1. **信息收集**：题目为`EZDJAM{d31jvt3_a0_jyfwa0}`
2. **尝试分析**：观察题目他的格式特别像flag的格式且花括号前为大写字母，结合题目凯撒大帝的秘密，大胆猜测这是由凯撒加密后的flag
3. **进一步分析**：现在我需要知道flag被后移了多少位，结合题目flag的格式为XSWCTF{}
4. **处理方法**：先尝试根据题目的第一为大写字母E和我们需要得到的字母X，推测该flag被后移了19位，于是将题目复制进在线工具cyberchef里的ROT13，选择后移19位，最终得到flag
![[Pasted image 20261115221726.png]]

## 💻 3. 核心工具

[ROT19](https://cyberchef.org/#recipe=ROT13(true,true,false,19)&input=RVpESkFNe2QzMWp2dDNfYTBfanlmd2EwfQ)



