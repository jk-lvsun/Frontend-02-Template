#### css 总体规则

- @charset
- @import
- rules
    - @media
    - @page
    - rule

##### css 规则
- 选择器
- 声明
    - key
    - value

##### css 选择器

###### 简单选择器
- type(div svgla)
- *
- .class
- #id
- [atr=value]
:hover
::before

###### 复合选择器
（同时match 几个简单选择器）
- <简单选择器><简单选择器>
- * 或者div 必须写在前面

###### 复杂选择器
（复合选择器中间用连接符连接变成复杂选择器）
复杂选择器针对一个元素的结构进行选择
- <复合选择器> <sp> <复合选择器>(子孙选择器)
- <复合选择器> ">" <复合选择器>(父子选择器)
- <复合选择器> "~" <复合选择器>(兄弟选择器 所有兄弟元素)
- <复合选择器> "+" <复合选择器>(兄弟选择器 相邻兄弟元素)
- <复合选择器> "||" <复合选择器>(select level4 tabel选中列)
 逗号构成选择器列表 或的关系


 ###### 伪类
 链接/行为
 -  :any-link
 -  :link : visited
 -  :hover
 -  :active
 -  :focus
 -  :target

树形结构
- :empty (是否有子元素)
- :nth-child() odd even 
- :nth-last-child() 从后往前
- :first-child :last-child :only-child

逻辑型
- not 伪类 （支持复合型选择器）

##### 伪元素
- ::before 
- ::after
- ::first-line
- ::first-letter


为什么first-letter可以设置float之类的，而first-line不行呢？
first-letter是在布局完成之后，确定了一段文字中的第一个文字，可以对其操作布局时性能开销小；
而first-line选中的是第一行文字，不同的宽度选中的文字内容不一样，要对其重新布局排版消耗性能大,所以first-letter 可以设置 float 之类的，而 first-line 不行。

