# 类加载时执行顺序

1. 父类静态 变量加载
2. 父类 静态块初始化
3. 子类静态 变量加载
4. 子类 静态块初始化
5. 父类非静态 变量加载
6. 父类 非静态块初始化
7. 父类  构造器初始化
8. 子类非静态 变量加载
9. 子类 非静态块初始化
10. 子类构造器初始化