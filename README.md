# 写在前面
为了更好的记录学习过程中的点点滴滴和学习写技术笔记，故搜集了一些资料进行学习，这里就算是我学习整理的一些内容，正所谓“好记性不如烂笔头”，所以即时的记录才是学习的基石。

# 内容
`话不多说，我们开始吧`
### 标题
文章的开头总是从标题开始，所以突出重点的标题和重要性分明的层次标题样式往往十分重要！

形式：
```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

效果：
> # 一级标题
>> ## 二级标题
>>> ### 三级标题
>>>> #### 四级标题
>>>>> ##### 五级标题
>>>>>> ###### 六级标题

#### 其他的方式：

#### 1.第一种特殊的情况，但使用的不多，也不必硬记，做个了解就行。
形式：

```
> 一级标题
> ===
*注意*：这里的`=`的个数最少是1个，最多不做限制

> 二级标题
> ---
```

效果：

一级标题
=

二级标题
-

#### 2.第二种是与HTML的标题兼容的，也就是HTML的标题语法这里一样适用。

形式：
```
<h1>一级标题</h1>
<h2>二级标题</h2>
<h1>三级标题</h3>
<h1>四级标题</h4>
<h1>五级标题</h5>
<h1>六级标题</h6>
```
效果：
> <h1>一级标题</h1>
> <h2>二级标题</h2>
> <h3>三级标题</h3>
> <h4>四级标题</h4>
> <h5>五级标题</h5>
> <h6>六级标题</h6>

### 文本
文本内容是一篇笔记，文章或者博客的精华，也是作者内容输出的地方，所以markdown也提供了丰富的文本标识方法
#### 普通文本
形式：
我是一个普通文本，看不出来吧！

效果：
我是一个普通文本，看不出来吧！

#### 代码块或者文本块
形式：


#### 反斜杠

> 相当于反转义作用。使符号成为普通符号

#### 代码强调

语法简述:

> 用\`将内容包围即可


形式:

```
`java`
```

效果:

`java`


#### 折叠

折叠有着特殊的表达形式，如下面所示

形式1:

```
<details>
<summary>WEB开发</summary>

##### 服务器
xxxx

##### 中间件
xxxx

##### 数据库
xxxx

</details>
```

效果；

<details>
<summary>WEB开发</summary>

##### 服务器
xxxx

##### 中间件
xxxx

##### 数据库
xxxx

</details>


形式2:

```
<details>
<summary>WEB开发</summary>

##### 服务器
xxxx

##### 中间件
xxxx

<details>
<summary>数据库</summary>

##### mmysql

##### mongodb

##### redis

</details>
```

效果:

<details>
<summary>WEB开发</summary>

##### 服务器
xxxx

##### 中间件
xxxx

<details>
<summary>数据库</summary>

##### mmysql

##### mongodb

##### redis

</details>


#### diff语法
语法简述：
```
> 输入` ```diff `之后，再输入内容即可
> `+` 表示增加
> `-` 表示删除
```

效果1；

```diff
+ 日拱一卒无有尽，
- 功不唐捐终入海。
! 功不唐捐，
# 玉汝于成。
```

效果2；

```diff
function addTwoNumbers (num1, num2) {
-  return 1 + 2
+  return num1 + num2
}
```

效果3：

```diff
fun main(){
+ say("")  
return ""
}

fun main(){
- say("")  
return ""
}
```
  
#### 表情

形式:
```
:smile:
```

效果：

😄

拓展1：emoji表情的适当合理的使用能很好的增加可阅读性和阅读的趣味性，所以emoji表情的使用也越来越普遍，这里我简单列举几个emoji表情的网站以供参考

> https://emojixd.com/
> 
> https://www.emojiall.com/zh-hans
> 
> https://openmoji.org/
>
> https://www.webfx.com/tools/emoji-cheat-sheet/

拓展2：除了使用emoji表情之外，还有很多趣味的表情包的恰当使用同样能增加可读性和趣味性，所以这里我也简单列举几个表情包的网站

> https://www.dbbqb.com/
>
> https://www.fabiaoqing.com/
>
> https://www.doutupk.com/
>
> https://www.doutub.com/









