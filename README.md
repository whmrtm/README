README
===========================
This file is used to display how to write markdown grammer, inspired by Jelly (87923)
****

Author: Heming Wang (Owen)

===========================



##<a name="index"/>Index
* [Line](#line)
* [Title](#title)
* [Text](#text)
    * Regular text
* [Link](#link) 
    * Text
        *  URL
        *  Other URL
* [Emoji](#emoji)
<a name="line"/>
##***、---、___ Display different lines
***
---
___



<a name="title"/>
#First level title
##Second level title
###Third level title
####Fourth level title
#####Fifth level title



##<a name="text"/>Display text
###Regular text
This is some regular text
####About newline
You cannot just use enter<br>
actually you can use HTML tags\<br>
But then what is the point of using markdown?  
Add two spaces after last line  
Then we are down

Or simply just add a blank line between two lines

###Single line text
    Hello World
###Block
    Welcome  
    Nice to meet you!
###Highlight
Thank `You` . Please `Call` Me `Coder`
####Highlight can be used as a tag
For instance:<br>
`java` `C++` `Socket` `Scheme`
####Strikethrough
This is a  ~~Strikethrough~~
####Italic
*Italic 1*

_Italic 2_
####Bold
**Bold 1**

__Bold 2__

##<a name="link"/>Link
###Linked to outside URLs
[Google](http://Google.ca) 

###Another way to write url
[MyBlog][1]  

[1]:http://blog.csdn.net/guodongxiaren 
```
[MyBlog][1]  

[1]:http://blog.csdn.net/guodongxiaren 
```


###Link URL in this Respotory
[Book](./Book)
grammer as follows：
```
[Book](./Book)
```
###Hashtag
[Index](#index)  
[Top](#TEST)

##<a name="pic"/>Show pics
###Pics from Internet
![baidu](http://www.baidu.com/img/bdlogo.gif "BAIDU logo")

###Pics from GitHub
![](https://github.com/guodongxiaren/ImageCache/raw/master/Logo/foryou.gif)
###<a name="piclink">Add link
[![head]](http://blog.csdn.net/guodongxiaren/article/details/23690801)
[head]:https://github.com/guodongxiaren/ImageCache/raw/master/Logo/jianxin.jpg "BLOG"

##<a name="dot"/>List
###Dots list
* Nickname：WTD
* English name：Owen

###More dots
* Code
    * Script
        * Python

###Num lists
####General

1. A
2. B
3. C

####Automatically ranked
Choose at the first line `1. `，Use asterik for the rest `*` 

1. One
* Two
* Three
* Four
* Five
* Six

####Multiple layer of list
Multiple layers
1. 这是一级的数字列表，数字1还是1
   1. 这是二级的数字列表，阿拉伯数字在显示的时候变成了罗马数字
      1. 这是三级的数字列表，数字在显示的时候变成了英文字母
	    1. 四级的数字列表显示效果，就不再变化了，依旧是英文字母

### 复选框列表
- [x] C
- [x] C++
- [x] Java
- [x] Qt
- [x] Android
- [ ] C#
- [ ] .NET

您可以使用这个功能来标注某个项目各项任务的完成情况。
##<a name="blockquotes"/>块引用

###常用于引用文本
####文本摘自《深入理解计算机系统》P27
　令人吃惊的是，在哪种字节顺序是合适的这个问题上，人们表现得非常情绪化。实际上术语“little endian”（小端）和“big endian”（大端）出自Jonathan Swift的《格利佛游记》一书，其中交战的两个派别无法就应该从哪一端打开一个半熟的鸡蛋达成一致。因此，争论沦为关于社会政治的争论。只要选择了一种规则并且始终如一的坚持，其实对于哪种字节排序的选择都是任意的。
><b>“端”（endian）的起源</b><br>
以下是Jonathan Swift在1726年关于大小端之争历史的描述：<br>
“……下面我要告诉你的是，Lilliput和Blefuscu这两大强国在过去36个月里一直在苦战。战争开始是由于以下的原因：我们大家都认为，吃鸡蛋前，原始的方法是打破鸡蛋较大的一端，可是当今的皇帝的祖父小时候吃鸡蛋，一次按古法打鸡蛋时碰巧将一个手指弄破了，因此他的父亲，当时的皇帝，就下了一道敕令，命令全体臣民吃鸡蛋时打破较小的一端，违令者重罚。”

###块引用有多级结构
>数据结构
>>树
>>>二叉树
>>>>平衡二叉树
>>>>>满二叉树

##<a name="code"/>代码高亮
```Java
public static void main(String[]args){} //Java
```
```c
int main(int argc, char *argv[]) //C
```
```Bash
echo "hello GitHub"#Bash
```
```javascript
document.getElementById("myH1").innerHTML="Welcome to my Homepage"; //javascipt
```
```cpp
string &operator+(const string& A,const string& B) //cpp
```
##<a name="table"/>显示表格
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

表格可以指定对齐方式

| 左对齐 | 居中  | 右对齐 |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

##<a name="emoji"/>添加表情
Github的Markdown语法支持添加emoji表情，输入不同的符号码（两个冒号包围的字符）可以显示出不同的表情。

比如`:blush:`，可以显示:blush:。

具体每一个表情的符号码，可以查询GitHub的官方网页[http://www.emoji-cheat-sheet.com](http://www.emoji-cheat-sheet.com)。

但是这个网页每次都打开**奇慢**。。所以我整理到了本repo中，大家可以直接在此查看[emoji](./emoji.md)。
