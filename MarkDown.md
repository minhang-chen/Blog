<p style="text-align: center">MarkDown学习记录<p>
------------------------------------------------

准备尝试着去写一些文章，在此记录一下MarkDown的相关语法，方便以后的学习回顾
####标题
```
"="（最高阶标题）和"-"（第二阶标题）显示标题
"#" <h1>一级标题
"##" <h2>二级标题
"###" <h3>三级标题
"####" <h4>四级标题
"#####" <h5>五级标题
"######" <h6>六级标题
```
给标题添加id或者class,在标题最后面添加{#id .class1 .class2}**（MPE扩展的特性）**
```
#这个标题有有个id{#id}
#这个标题有2个class{.class1 .class2}
```
####强调
\* *这是个斜体的文字* \*
\_ _这是个斜体的文字_ \_
\*\* **这是个粗体的文字** \*\*
\~\~ ~~文字会被横线删除~~ \~\~

####列表
#####无序列表
```
* item 1
* item 2
    * item 2a
    * item 2b
等同于
+ item 1
+ item 2
    + item 2a
    + item 2b
等同于
- item 1
- item 2
    - item 2a
    - item 2b
```

* item 1
* item 2
    * item 2a
    * item 2b


#####有序列表
```
1. item 1
2. item 2
3. item 3
    1. item3a
    2. item 3b

```
1. item1
1. item2
1. item3
    1. item3a
    1. item3b

####添加图片
```
![Alt Text](url)
标签引入图片
<src src="地址">
```
![美术宝 Logo](https://51nbimg.u51.com/1bf91478602a4f17816423c3832d9a27.png)
<img src="https://51nbimg.u51.com/1bf91478602a4f17816423c3832d9a27.png">

####链接
```
https://github.com/minhang-chen

[GitHub](https://github.com/minhang-chen)
```
https://github.com/minhang-chen

[GitHub](https://github.com/minhang-chen)

####引入
```
> 引入内容
```
>引入相关内容

####分割线
```
三个或以上

连词线
- - - 
星号
* * *
_ _ _
下划线
```

连词线
- - - 
星号
* * *
下划线
_ _ _

####行内代码
```
在文档内出现`<div></div>`的标签
```

在文档内出现`<div></div>`的标签

####代码块
在代码的开头和结尾加上 ` ``` `  来表示代码块
```
代码块显示区域
```

####语法高亮

```
    ```javascript(对应语法)
    let num = '', a = '', b = '';
    num = a + b;
    ```
```
```javascript
let num = '', a = '', b = '';
num = a + b;
```

####代码块class(MPE扩展特性)
给代码块设置class
```
    添加class1和class2
    ```javascript{.class1 .class2}
    let num = '', a = '', b = '';
    num = a + b;
    ```
```

####代码行数
```
    ```javascript{.line-numbers}
    let num = '', a = '', b = '';
    num = a + b;
    console.log(num)
    ```
```
```javascript{.line-numbers}
let num = '', a = '', b = '';
num = a + b;
console.log(num)
```
####任务列表
```
- [ ] 空格未选中
- [x] x选中 
```
- [ ] 未选中
- [x] 选中 

####表格
```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

###扩展语法
####上标
```
30^th^
```
30^th^

####下标
```
H~2~O
```
H~2~O

####缩略
```
*[缩略]: 看到了吗 我出现了
*[空格]:  字符之间要有空格
鼠标移到 缩略 就会有文字显示
字符之间要有 空格 才生效
没有空格就没有生效
```
*[缩略]: 看到了吗 我出现了
*[空格]:  字符之间要有空格
鼠标移到 缩略 就会有文字显示
字符之间要有 空格 才生效
没有空格就没有生效

####标记
```
==标记==
```
==标记==
{++ 啦啦啦 ++}
####脚注
```
Content [^1] 
[^1]: This is a footnote
```
Content [^1] 
[^1]: This is a footnote