1. 什么是Python中的标识符？标识符有哪些命名规则？
标识符是Python程序中的命名工具，用于给程序中的各种元素命名。
- 基本规则
    - 由大小写字母、数字、下划线和汉字组成
    - 对大小写敏感（Python和python是不同的）
    - 不能以数字开头
    - 中间不能出现空格
    - 长度没有限制
- 编程建议
    - 命名要见名知意
    - 尽量避免使用汉字

> 类似于给事物起名字，好的命名可以提高代码可读性

2. 什么是Python中的保留字？保留字有什么特点？
保留字是Python语言预定义的特殊标识符。
- 基本特点
    - 共有35个保留字
    - 不能用作变量名、类名、模块名等
    - 用于Python语言自身的语法实现
- 学习建议
    - 无需死记硬背
    - 随着学习深入自然掌握

> 类似于皇帝的名字，平民不能使用

3. 什么是变量？如何在Python中使用变量？
变量是Python中存储数据的基本单元。
- 基本特征
    - 具有类型、名称和值三个属性
    - 通过赋值语句创建变量
    - 使用赋值运算符=赋值
    - 可以重复赋值，以最后一次为准

```python
# 变量使用示例
A = 10           # 整数赋值
name = "张三"    # 字符串赋值
π = 3.14        # 浮点数赋值
```

4. 什么是常量？Python中的常量有哪些类型？
常量是程序中固定不变的值。
- 常见类型
    - 整型常量：如 10
    - 字符串常量：如 "张三"
    - 浮点型常量：如 3.14
- 使用特点
    - 类似于数学中的常数
    - 通常作为变量的值使用

5. Python中的赋值符号(=)代表什么含义？如何正确理解？
赋值符号是Python中最基本的操作符之一。
- 使用规则
    - =是赋值号，不是等于号
    - 变量必须先赋值才能使用
    - 可以重复赋值
    - 以最后一次赋值为准

```python
# 赋值示例
A = 10
A = 15      # 重复赋值
print(A)    # 输出15
```

> 正确读法是"将10这个值赋值给A"，而不是"A等于10"

6. 什么是代码注释？Python中有哪些注释方式？
注释是提高代码可读性的重要工具。
- 单行注释
    - 使用#符号
    - #后面的内容会被忽略
    ```python
    # 这是一个单行注释
    x = 10  # 这也是注释
    ```
- 多行注释
    - 使用三个单引号或双引号
    - 可以跨越多行
    ```python
    '''
    这是多行注释
    可以包含多行内容
    '''
    ```
- 注释特点
    - 不会被编译和执行
    - 对程序运行没有影响
    - 提高代码可读性和可维护性

> 注意：好的注释应该解释代码"为什么这样做"，而不是"做了什么"