## 表达式

### 4.3 逻辑和关系运算符

1、短路求值
当且仅当左侧运算符对象无法确定表达式的结果时才会计算右侧运算对象的值。

### 4.5 递增和递减运算符

1、前置和后置

    int i = 0, j;
    j = ++i; // 前置版本，先++再赋值 i=1 j=1
    j = i++; // 后置版本，返回对象改变之前的副本 i=2 j=1

前置返回对象本身，后置返回对象原始值的副本

    cout << *p++ << endl;