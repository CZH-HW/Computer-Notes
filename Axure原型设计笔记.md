[TOC]

# Axure 

能帮助网站需求设计者，快捷而简便的创建基于网站构架图的带注释页面示意图、操作流程图、以及交互设计，并可自动生成用于演示的网页文件和规格文件，以提供演示与开发

## 1. Axure RP 9 基础

### 1.1 界面基本功能介绍

![](https://github.com/CZH-HW/CloudImg/raw/master/Comp/axure_1.png)

- 复制、剪切及粘贴区域
- 选择模式
- 插入形状
- 点（编辑控点）
- 置顶和置底
- 组合和取消组合
- 调整大小
- 对齐
- 预览和共享
- 文本设置
- 元件样式
- 左侧面板的页面（pages）、大纲（outline）、元件库、母版
- 右侧面板的样式、交互和说明

### 1.2 元件基础

元件是组成我们原型的零件，也有人翻译成组件。

Axure RP 9 默认给我们提供了三套元件库，默认元件库、流程图元件库、图标元件库。也可以自己导入第三方的元件库使用。

- 默认元件库：基本元件、表单元件、菜单|表格、标记元件
![](https://github.com/CZH-HW/CloudImg/raw/master/Comp/axure_9.png)


- 流程图元件库：
![](https://github.com/CZH-HW/CloudImg/raw/master/Comp/axure_10.png)


元件基本操作如下：

1. 使用元件（从元件库中把元件拖拽到画布上、插入选择对应图形项目）
2. 选中元件（单击、框选、概要里选择相应元件）
3. 删除元件（delete）
4. 复制元件（Ctrl+C、Ctrl+V）
5. 改变元件位置（直接拖动、设置坐标值） 
6. 改变元件大小（选中元件拖动四周方形手柄、按住shift拖动手柄可锁定宽高比例、调整W、H值）
7. 调整元件角度（按住Ctrl键+旋转元件节点）
8. 锁定元件（对应元件右键——>锁定——>锁定位置和尺寸）   
9. 隐藏功能（右键——>隐藏、样式菜单栏的眼睛图标）：只是视觉上不可见，仍可被选中、被修改尺寸和位置
10. 元件命名（样式/交互/说明选项卡顶部输入名称即可）  
11. 组合元件（Group/Ungroup）
12. 元件层次顺序（概要窗口元件的上下位置代表其层级关系，Front/Back）
13. 元件的对齐和分布（至少选中两个元件进行对齐操作、至少选中三个元件进行分布操作，分布用来拍间距）
14. 元件样式（透明度、文字排版、填充、边线、阴影、圆角、内边距）
15. 修改文本框属性类型（拖拽左侧元件库中文本框（Text Field）到画布上——>点击交互（INTERACTIONS）右边的三个小点后选择类型） 
注：选择属性类型为文件即可在浏览器（预览）中变成打开选择本地文件的按钮。
![](https://github.com/CZH-HW/CloudImg/raw/master/Comp/axure_2.png)
16. 限制文本框输入字符位数（交互（INTERACTIONS）右边的三个小点后——>在MAX LENGTH中输入指定长度的数字）
17. 设置文本框提示文字（交互（INTERACTIONS）右边的三个小点后——>在HINT TEXT中输入提示文字，HIDE AFTER选择提示文字消失的触发条件）
18. 设置鼠标移入元件时的提示（交互（INTERACTIONS）右边的三个小点后——>在TOOLTIP中输入提示内容）
19. 设置列表框的内容（拖拽左侧元件库中下拉框（Droplist）/列表框（List Box）到画布上——>双击此元件设置）
20. 导出html文件（在顶上工具栏，选择“发布”项，找到“生成HTML文件”项）
21. 嵌入多媒体文件、页面（内联框架（Inline Frame）——>双击元件或在属性中选择“链接到url或文件”，填写超链接地址）
22. 设置树控件样式（右键单击编辑树属性、右键单击编辑图标）
![](https://github.com/CZH-HW/CloudImg/raw/master/Comp/axure_3.png)    
23.自适应视图
- 可以快速生成多尺寸设计稿，调整方便，时时可预览；
- 可分享，效果堪比视觉并开发的版本，可以用来收集意见，降低开发风险；
- 响应式，可以让我们的设计提案更加生动。
---

## 2. 交互

### 2.1 页面交互
选中页面后——>点击右侧面板的交互——>选择触发事件——>添加动作及动作目标——>选择动画及显示效果
![](https://github.com/CZH-HW/CloudImg/raw/master/Comp/axure_4.png)   
![](https://github.com/CZH-HW/CloudImg/raw/master/Comp/axure_5.png)   
![](https://github.com/CZH-HW/CloudImg/raw/master/Comp/axure_6.png)   

### 2.2 控件交互
交互样式：鼠标悬停、鼠标按下、选中、禁用、获取焦点——>静态样式的设置（非动态）

控件交互：选中元件——>添加交互或交互样式——>添加动作及动作目标（事件结果）——>选择动画及显示效果
 
条件判断：如果、否则
![](https://github.com/CZH-HW/CloudImg/raw/master/Comp/axure_7.png)   

---

## 3. Axure 进阶

### 3.1 全局变量与局部变量

- 全局变量：项目（P）——>点击全局变量（V）——>设置多个全局变量，加号添加，双击重命名，双击默认值设置默认值。
  创建全局变量**用于浏览器页面切换时存储数据**。
![](https://github.com/CZH-HW/CloudImg/raw/master/Comp/axure_11.png)


- 局部变量(在一个动作中有效)：在交互动作中只要有设置文本为值的情况就有`fx`，有`fx`的地方就有局部变量，局部变量也可以赋值给全局变量
![](https://github.com/CZH-HW/CloudImg/raw/master/Comp/axure_8.png)  


局部变量实际应用举例：

商品总价 = 商品价格（局部变量）* 商品数量（局部变量）

![](https://github.com/CZH-HW/CloudImg/raw/master/Comp/axure_12.png)
![](https://github.com/CZH-HW/CloudImg/raw/master/Comp/axure_13.png)




局部变量和全局变量的应用：
在验证过程中的应用：
利用全局变量可以存储用户名和密码信息，格式
`(name：password)(name1:password1)…`

通过局部变量可以进行验证，用户名是否正确
只需要建立一个局部变量`n`提取出`name`的值，和全局变量进行比较。

比如用户名正确，再对密码进行判断，但是要建立两个局部变量得到`name`和`password`的值，并且符合`(name：password)`的格式，用`[[]]`实现。





