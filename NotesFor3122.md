# Notes *for YC3122*
## 测试项
### ADC
- [ ] mode
- [x] 3.3v
### LPM
- [x] 高温测试
- [x] 低温测试
- [x] lpm 电压测试
  - [ ] 需要重新出一个表格
- [x] core 电压测试
- [x] tamper 功能测试
- [ ] tamper mesh
- [ ] temper 加电阻
- [ ] 测试所有功能的唤醒 clear key
- [x] chgrin 上电毛刺测试(测试是否丢会使lpm复位)
- [x] chgrin&charout  上电毛刺测试(测试是否丢会使lpm复位)
- [ ] sensor&temper 压力测上电重复是否会自己擦除秘钥
### VIO
- [x] VIO1
- [ ] VIO0
### RNG
- [x] 随机数单BIT翻转
- [x] 低功耗
  - [ ] 表格待补全
### 低重要性
- [ ] flash 读写

:mask:

----------------------------------------

## 工作和学习

----------------------------------------

### 2021-9-4

- [x] 学习markdown for vscode 如何记笔记,学习使用GIT
- [x] 测试FIB6 唤醒出现毛刺是否丢失秘钥
- [ ] 测试开关chgrpump 在高温临界值是否会对sensor报警产生影响
  - [x] 结论:有影响,但是需要debug
    - [ ] 单步出不去rom,需要看rom汇编分段然后进行测试
