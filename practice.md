
<font size="50" color="red">兼容 HTML</font>
<h1>这是一个h1标签</h1>
<p>下面是一个table</p>
<table>
    <tr>
        <td style="font-size:25px">Title1</td>
        <td style="font-size:25px">Title2</td>
    </tr>
    <tr>
        <td>Content1</td>
        <td>Content2</td>
    </tr>
</table>

<p>这是另一个段落</p>
<img src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1522648151172&di=8565cbbedd82189fba18e0eae41c8235&imgtype=0&src=http%3A%2F%2Fimgsrc.baidu.com%2Fimage%2Fc0%253Dshijue1%252C0%252C0%252C294%252C40%2Fsign%3Db6ac6f0a753e6709aa0d4dbc53aef548%2Fc83d70cf3bc79f3de9f6771db0a1cd11728b2983.jpg" style="width:100px">

<font size="50" color="red">标题</font>

# 这是h1
## 这是h2
### 这是h3
#### 这是h4
##### 这是h5  ##
###### 这是h6 #
####### 没有h7，就到h6

This is an H1
=
This is an H2
-

<font size="50" color="red">引用</font> 
>  This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

> ## 这是一个标题。
> 
> 1. 这是第一行列表项。
> 2. 这是第二行列表项。
> 
> 给出一些例子代码：
> 
> return shell_exec("echo $input | $markdown_script");

> 一级引用
>> 二级引用
>>> 三级引用
>>>> 四级引用


* 不以结婚为目的的恋爱都叫耍流氓
  > 这是毛主席说的

<font size="50" color="red">表格</font> 

|Tables|Are|Cool|
|:-|:-:|-:|	
|col 3 is |right-aligned|$1600|	
|col 2 is|centered|$12|	
|zebra stripes| are neat|$1|


<font size="50" color="red">列表</font>   
无序列表

* Red
* Green
* Blue
+ Red
+ Green
+ Blue
- Red
- Green
- hello word   
helloword  
helloword                                      



有序列表  
支持有序列表的 start 属性  

3.    Bird
1. McHale
8. Parish


<font size="50" color="red">代码块</font>  

通常编辑器根据代码片段适配合适的高亮方法，但你也可以用 ``` 包裹一段代码，并指定一种语言


```javascript
var num = 0;
for (var i = 0; i < 5; i++) {
    num+=i;
}
console.log(num);
```
如你不需要代码高亮，可以用下面的方法禁用：
```nohighlight
var num = 0;
for (var i = 0; i < 5; i++) {
    num+=i;
}
console.log(num);
```
也可以使用 4 空格缩进，再贴上代码，实现相同的的效果   

    def g(x):
        pass
    a = 1
    g(a)



<font size="50" color="red">插入链接</font>   
1. 内链式：    
[百度1](http://www.baidu.com/" "Title")  
下面是一个图片
![图片](https://www.baidu.com/img/bd_logo1.png?where=super)

2. 引用式：  
[2]   
[2]: http://www.baidu.com

<http://www.cnnic.cn>  
<jidongdong@cnnic.cn>

<font size="50" color="red">任务列表</font>   
这是文字……

- [x] 选项一
- [ ] 选项二  
- [ ]  [选项3]


<font size="50" color="red">强调</font>   
*字体倾斜*  _字体倾斜_  
**字体加粗**  __字体加粗__

~~删除线~~

<font size="50" color="red">分割线</font>  
分割线可以由* - _（星号，减号，下划线）这3个符号其中一个的至少3个表示，注意至少要3个，且不需要连续，有空格也可以  
***
1
*** * 
2
- - -
3
___



<font size="50" color="red">换行</font>  
如果另起一行，只需在当前行结尾加 2 个空格

如果是要起一个新段落，只需要空出一行即可。  


<font size="50" color="red">公式</font>   
$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a}. $$

$$
x \href{why-equal.html}{=} y^2 + 1
$$


github表情  
:smile: :bowtie: :+1: :clap: :octocat:

```sequence
    起床->吃饭: 稀饭油条
    吃饭->上班: 不要迟到了
    上班->午餐: 吃撑了
    上班->下班:
    Note right of 下班: 下班了
    下班->回家:
    Note right of 回家: 到家了
    回家-->>起床:
    Note left of 起床: 新的一天
```