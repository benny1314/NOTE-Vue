关于标题


## 大标题

规范的README文件开头都写上一个标题，这被称为大标题 。

```
大标题
====

```

> 大标题下面加 `=`

## 中标题

比大标题低一级的是中标题，也就是显示出来比大标题小点。


```
中标题
----

```

> 中标题下面加 `-`


实际上，前文所述的大标题和中标题是分别和一级标题和二级标题对应的。即大标题大小和一级标题相同，中标题大小和二级标题相同。 


## 小标题

小标题的格式如下 `###` 小标题，注意`#`和标题字符中间要有空格


    # 一级标题
    ## 二级标题
    ### 三级标题
    #### 四级标题
    ##### 五级标题
    ###### 六级标题
    
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题



## 单行文本

使用**两个Tab符**实现单行文本。

    Hello,大家好，我是果冻虾仁。

 
多行文本

多行文本和单行文本异曲同工，**只要在每行行首加两个Tab**

    欢迎到访
    很高兴见到您
    祝您，早上好，中午好，下午好，晚安

## 部分文字的高亮

如果你想使一段话中部分文字高亮显示，来起到突出强调的作用，那么可以把它用 \` \` 包围起来。注意这不是单引号，而是Tab上方，数字1左边的按键（注意使用英文输入法）。

    Thank `You` . Please `Call` Me `Coder`
    

Thank `You` . Please `Call` Me `Coder`

## 文字超链接

给一段文字加入超链接的格式是这样的 `[ 要显示的文字 ]( 链接的地址 )`。比如：

[我的博客](http://blog.csdn.net/guodongxiaren)

### 你还可以给他加上一个鼠标悬停显示的文本。

    [我的博客](http://blog.csdn.net/benny1314 "悬停显示")
    
[鼠标放上面会有显示呢](http://blog.csdn.net/benny1314 "悬停显示")

## 引用


    > 数据结构
    >> 树
    >>> 二叉树
    >>>> 平衡二叉树
    >>>>> 满二叉树
    
>数据结构
>>树
>>>二叉树
>>>>平衡二叉树
>>>>>满二叉树

## 下划线

    ++benny++

++benny++

## 高亮

    ==benny==

==benny==


    ^aa^
    
^aa^

    ~aa~
    
~aa~

## 插入图片

这个方括号里的baidu并不会对图像显示造成任何改动，如果你想达到 鼠标悬停 显示提示信息，那么可以仿照前面介绍的文本中的方法，就是这样：

    ![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")

在URL后面，加一个双引号包围的字符串，显示效果如图： 

![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")

## 超链接

    [benny](www.okjava.cn)
    
[benny](www.okjava.cn)


## 给图片加上超链接

**如果你想使图片带有超链接的功能，即点击一个图片进入一个指定的网页**

    [![BENNY]](www.okjava.cn)
    
    [BENNY]:http://www.baidu.com/img/bdlogo.gif "百度Logo"


[![BENNY]](http://www.okjava.cn)

[BENNY]:http://www.baidu.com/img/bdlogo.gif "百度Logo"

只需注意上下文中的 baidu 是你自己起的标识的名称，可以随意，但是一定要保证上下两行的 标识 是一致的。

## 插入代码片段

我们需要在代码的上一行和下一行用 \`\`\` 标记 (Tab键上面的键)

\`\`\`

public static void main (String[] args){}

\`\`\`

```
public static void main (String[] args){}
    
```

## 与上文分隔


    ---
    
---



## 字体加粗

    _斜体_

_斜体_


    **加粗**

**加粗**

    *斜体*

*斜体*



## 分割线

可以在一行用3个以上的 `*` `-` `_`来建立一条分割线，行内除了空格不能有其他东西，

当然三条线效果是不同的，按顺序是**很明显**，**不明显**，**一般**。第二种不仔细看真看不到有线，我是换了暗色主题才看清。


## 删除线

文本两端加上两个`~~`即可

    ~~删除我~~

~~删除我~~



## 代码

要标记一小段行内代码，用反引号包起来 \`

Use the `printf()` function.

``There is a literal backtick () here.``

## 表格

```

表头1  | 表头2
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

| 表头1  | 表头2|
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

| 名字 | 描述          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |

表格中也可以使用普通文本的删除线，斜体等效果

| 名字 | 描述          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |
| Close     | **Closes** a window     |

表格可以指定对齐方式

| 左对齐 | 居中  | 右对齐 |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

```


|表头1  | 表头2
|------------- | -------------
|Content Cell  | Content Cell
|Content Cell  | Content Cell

| 表头1  | 表头2|
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

| 名字 | 描述          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |

表格中也可以使用普通文本的删除线，斜体,粗体等效果

| 名字 | 描述          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |
| Close     | **Closes** a window     |

表格可以指定对齐方式

| 左对齐 | 居中  | 右对齐 |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |



