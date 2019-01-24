---
title: markdown语法
---

>标题
# 一级标题
## 2
### 3

>字体
**加粗**
*斜体*
***斜体加粗***
~~删除线~~

>引用

>分割线
---------------------
***********************

>图片
![blockchain](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/
u=702257389,1274025419&fm=27&gp=0.jpg "区块链")

>超链接
[简书](http://jianshu.com)

>列表
- 列表内容
+ 类表内容
* 列表内容

1. 有序列表
2. 列表内容
3. 订单

>table

姓名|技能|排行
--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟

----------------------------------
>代码
`代码内容`

>代码块

    ```
        function fun(){
            echo "这是一句非常牛逼的代码";
        }
        fun();
    ```

--------------------------------
>流程图

```flow 
st=>start: Start:>http://www.google.com[blank]
e=>end:>http://www.google.com
op1=>operation: My Operation
sub1=>subroutine: My Subroutine
cond=>condition: Yes
or No?:>http://www.google.com
io=>inputoutput: catch something...

st->op1->cond
cond(yes)->io->e
cond(no)->sub1(right)->op1
```
