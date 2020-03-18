# 目录
- [目录](#%e7%9b%ae%e5%bd%95)
- [缺省值测试/Default Options in Testing](#%e7%bc%ba%e7%9c%81%e5%80%bc%e6%b5%8b%e8%af%95default-options-in-testing)
- [决策表 Decision Table](#%e5%86%b3%e7%ad%96%e8%a1%a8-decision-table)
  - [决策表的组成](#%e5%86%b3%e7%ad%96%e8%a1%a8%e7%9a%84%e7%bb%84%e6%88%90)
  - [构造决策表的步骤](#%e6%9e%84%e9%80%a0%e5%86%b3%e7%ad%96%e8%a1%a8%e7%9a%84%e6%ad%a5%e9%aa%a4)
  - [练习](#%e7%bb%83%e4%b9%a0)

# 缺省值测试/Default Options in Testing
测试用例必须覆盖到全部缺省值  

- Base Choice  
- Multiple Base Choice  
- Merge Input Variables  
- Refine Input Domain  
- Modify Test Case

# 决策表 Decision Table

能够将复杂的问题按照各种可能的情况全部列举出来，简明并避免遗漏。因此可以利用决策表设计出完整的测试用例集合。  

## 决策表的组成
- **条件桩**：列出问题所有的条件
- **条件项**：针对条件桩列出的所有可能取值
- **动作桩**：列出问题规定的可能采取的操作
- **动作项**：指出条件项各取值情况下采取的动作

<table>
    <tr>
        <th>条件桩</th><th>条件项</th>
    </tr>
    <tr>
        <th>动作桩</th><th>动作项</th>
    </tr>
</table>

## 构造决策表的步骤

1. 确定规则个数
2. 填写条件桩与动作桩
3. 填入条件项
4. 填入动作项
5. 合并相似规则，简化决策表

合并后的条件项用$-$表示，执行动作与该条件的取值无关，称该条件为无关条件

## 练习

前一日函数，返回当前日期的前一天







