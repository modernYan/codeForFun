# 趣味编程

## 计算24点
给出四个不大于10的自然数，找出所有可以计算得到24的四则运算表达式，只能用+-×/和括号。
代码参见[Calculation24.java](./src/main/java/com/github/codefan/codeforfun/Calculation24.java)。

**算法有三个点：**

* 对给出的4个数字进行排列组合，需要去掉相同数值重复的问题。
* 对每一个排列用逆波兰式插入3个运算符，运行符位置用枚举法，一共5种。
* 对符合结果的逆波兰式转换为带括号的四则元素，不同的逆波兰式转换为四则运算可能重复。
