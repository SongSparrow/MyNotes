# 目录
- [目录](#%e7%9b%ae%e5%bd%95)
- [随机测试](#%e9%9a%8f%e6%9c%ba%e6%b5%8b%e8%af%95)
- [多样性](#%e5%a4%9a%e6%a0%b7%e6%80%a7)
  - [自适应随机测试](#%e8%87%aa%e9%80%82%e5%ba%94%e9%9a%8f%e6%9c%ba%e6%b5%8b%e8%af%95)
# 随机测试

测试用例完全是随机产生的
- 输入域必须已知
- 选择输入域内部的节点
- 自动化

难点
- 定义输入域
- 随即机制
- 随机与集成服务

# 多样性
样本随机均匀分布

## 自适应随机测试
**算法**
```
randomly generate an input t, run t, add t to T
while (stop criteria not reached)
    randomly generate k candidate input c1, … ck
    for each candidate ci
        compute min distance di to T
    end for
    select one candidate t with min distance
    run t, add t to T
end while
```
**注意事项**
- 距离的计算方式
- 开销控制
- 维度问题

