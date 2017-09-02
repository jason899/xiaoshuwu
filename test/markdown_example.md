

[TOC]

# 快速入门

## 支持6级标题

1. 有序列表1
1. 有序列表2


- 无序列表
* 无序列表


**这样可以加粗**
*这样可以斜体*
~~这样可以删除~~


>这样可以引用
>***这样加粗斜体引用***


**代码高亮** 
```
--  oracle下批量删除表操作
SELECT 'DROP TABLE '||TABLE_NAME||';' FROM ALL_TABLES
WHERE TABLE_NAME LIKE 'TMP_CCC%'
 
-- 清CCC建立的临时表，在命令窗口执行select出来的结果。执行之前确认下要drop的表对不对
SELECT 'drop table '||owner||'.'||table_name||';' 
  from all_tables WHERE table_name LIKE 'TMP_CCC%' ;
```

单反引号局部高亮，例如 `printf()`函数，
2反引号` \`` `单行高亮：
``只能一行哦\`` ``
3反引号` \``` `批量高亮：
4个连续空格自动解析为代码

</br>

-------------------------------------------------
# 进阶语法
## 链接
参考文档：http://blog.wiz.cn/feature-markdown.html 
这里：http://www.yangzhiping.com/tech/r-markdown-knitr.html
这里：http://lutaf.com/markdown-simple-usage.htm
这里：http://wowubuntu.com/markdown/
这里：http://www.jianshu.com/p/q81RER
这里：http://www.jianshu.com/p/0c630861b76f
这里：https://www.zybuluo.com/yinzhi6367/note/59158
在线测试：https://www.zybuluo.com/mdeditor
[点我试试](http://blog.wiz.cn/feature-markdown.html)

## 配图
![配图说明](http://upload-images.jianshu.io/upload_images/1495118-d83a4ccfc711dfe9.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![显示链接中带括号的图片][1]
## 表格

> 注意单元格对齐的写法

|工具|记录|时间|
|----|:----:|----:|
|WizNote|CJX|2016|

dog | bird | cat
----|----|---
foo | foo | foo
bar | bar | bar
baz | baz | baz

## 嵌套列表

- 我是第1级
 - 我是第2级
   - 我是第3级

## 嵌套引用
>数据结构
>>树
>>>二叉树

1. 有序第1级
 1.1. 有序第2级
3. 有序第1级
 2.1. 有序第2级
 2.2. 有序第2级

## 时序图
```sequence
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
```

```flow 
st=>start: Start 
io=>inputoutput: verification 
op=>operation: Your Operation 
cond=>condition: Yes or No? 
e=>end

st->io->op->cond 
cond(yes)->e 
cond(no)->io 
```

```seq 
Alice->Bob: Hello Bob, how are you? 
Note right of Bob: Bob thinks 
Bob-->Alice: I am good thanks! 
```

</br>

-------------------
# 高阶语法
> 与HTML的嵌套

（未完待续……）


# 简书暂不支持的内容列举
- TOC目录
- 时序图

# 图片
![enter description here][2]


  [1]: http://latex.codecogs.com/gif.latex?\prod%20\(n_{i}\)+1
  [2]: ./images/1504367418411.jpg