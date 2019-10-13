# 测试用例 0-2
#### 包含的指令
- [ ] ADDU
- [x] SUBU
- [x] LW
- [x] SW
- [ ] BEQ

#### 采分点
- [ ] RAW hazards
- [ ] BEQ

#### 汇编指令
```
LW    R1, R0, 0
LW    R2, R0, 4
ADDU  R0, R0, r0
ADDU  R0, R0, r0
SUBU  R3, R1, R2
ADDU  R0, R0, r0
ADDU  R0, R0, r0
SW    R3, R0, 8
HALT
```