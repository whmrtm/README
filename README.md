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
1. Layer 1
   1. Layer 2
      1. Layer 3
	    1. Layer 4

### Multiple  checkboxes
- [x] C
- [x] C++
- [x] Java
- [x] Qt
- [x] Android
- [ ] C#
- [ ] .NET

##<a name="blockquotes"/>Block quote

### Commonly used in quoted message
#### Cited 
　令人吃惊的是，在哪种字节顺序是合适的这个问题上，人们表现得非常情绪化。实际上术语“little endian”（小端）和“big endian”（大端）出自Jonathan Swift的《格利佛游记》一书，其中交战的两个派别无法就应该从哪一端打开一个半熟的鸡蛋达成一致。因此，争论沦为关于社会政治的争论。只要选择了一种规则并且始终如一的坚持，其实对于哪种字节排序的选择都是任意的。
>Stack Overflow is a question and answer site for professional and enthusiast programmers. It's 100% free. 

###Multiple layers of quoted message
>Data Structure
>>Tree
>>>Binary Tree
>>>>BST
>>>>>Complete Binary Tree

##<a name="code"/>Code highlight
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
##<a name="table"/>Table
Head1  | Head2
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

| Head1  | Head2|
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

| Name | Description          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |

You can also use italic, delete line in tables

| Name | Description          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |


| Left | Center  | Right |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

