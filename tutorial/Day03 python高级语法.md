# Day03 python高级语法
学习python高级变量类型，list，string，dict，set，过一遍就足够，知道是什么回事就行。
学习python的高级特性，函数，类与对象和方法，类型标注，理解为什么要出现函数，类（本质都是为了抽象）。理解Don't Repeat Yourself原则。

理解uv初始化的程序中
```python
def main():
    print("Hello from tests!")

if __name__ == "__main__":
    main()
```
是什么意思，以及为什么要这样写，而不是用简单的脚本的方式执行。

练习1，将之前的猜数字游戏改写成函数的形式
练习2，面向对象的练习题——图书馆系统

在代码里实现以下类
1. 图书类 (Book) — 属性的集合
• 属性（数据）： 书名 (title)、作者 (author)、ISBN号 (isbn)、是否被借阅 (is_borrowed)。
• 方法（行为）： 借出书 (borrow_book)、归还书 (return_book)。
2. 图书馆类 (Library) — 管理对象的容器
• 属性： 一个用来存放多本书的列表/数组 (books)。
• 方法： 添加新书 (add_book)、查看所有图书 (display_books)、根据书名查找图书 (search_book)。

在main()中实现下面步骤
1. 手动创建 3 本不同的 Book 对象。
2. 创建一个 Library 对象，把这 3 本书添加进去。
3. 调用 Library 的方法，打印出馆藏的所有图书信息。
4. 模拟借出一本书，改变它的 is_borrowed 状态。
