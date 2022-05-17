## 最近更新
最近一次的更新需要修改main.js，不方便在集市上直接更新，请查看链滴社区中的帖子：
[https://ld246.com/article/1651156033109](https://ld246.com/article/1651156033109)

帖子里当前关于main.js的修改，对应于windows平台V2.0.9的版本，愿意折腾的可以试一下（尝试前先备份好main.js文件）。

## SiYuan_mindMap
基于jsMind的思维导图挂件，适用于思源笔记（开放笔记API后的版本）



## 开始使用
* 基本使用：

  * Tab 键是新建子元素并进入编辑状态
  * Enter 键是新建兄弟元素并进入编辑状态
  * Delete 键是删除元素
  * 如果上面三个键没生效，大概是焦点问题，可以用鼠标点一下那个元素再按
  * 按 Esc 或者元素失去焦点时结束编辑状态；
* 如何插入超链接？

  * 复制笔记中的块超链接或者外部的链接地址；
  * 双击元素进入编辑模式，输入需要展示的文本（如果使用元素已有的文本，这一步可以省略），然后按 Ctrl+k，就会结合刚刚复制的链接地址和当前元素的文本生成超链接；点击文字后能跳转到指定位置；
  * 注意：删除设置了超链接的元素时，鼠标要点边框后按 Delete，不然直接跳转了。
* 检索关键字

  * 点击【检索】按钮弹出搜索界面
  * 输入框中输入内容后按【Enter】或者点击【提交】即开始检索，匹配到的关键字黄色高亮；
  * 点击搜索到的结果，下方会出现对应的结果预览，如果是超链接，点击后能进行跳转。
  * 点击某个搜索结果后搜索界面上方显示的该结果在导图中的路径；点击该路径或【检索】按钮，能关闭搜索界面；
* 如何缩放导图？

  * 鼠标悬浮在导图上方后按住Ctrl，使用鼠标滚轮来缩放导图。缩放比例：0.4~2


## 备注
1、思维导图初始化的时候，如果发现底部有相邻的代码块，会读取代码块中的数据来绘制导图，如果没有，就在底部插入代码块，并使用内置的导图模板；

2、导图被修改后默认会自动将最新的数据写入到代码块中，尽管如此，左上角还是保留了手动保存的按钮，不放心的话可以编辑完手动点一下。

3、挂件底部绑定的那个代码块，除了用来保存数据（页面刷新或者重新打开时导图状态保持一致），还可以用于全局搜索时检索导图包含的关键字。（代码块中的数据包含了导图各个节点的文本信息，而代码块的内容是可以被全局检索到的）。
