# 任务

1. 完成书单详情页面 (完成)

2. 完成Tag (完成了一大半，就是互相点击交互这方面没有想明白)

3. 排行榜的排行详情页面 （明天的任务）

## 主题书单的Tag的制作

Tag分为两部分一部分是筛选，另一部分是滑动框。两个的功能是结合在一起的。

1. 首先是设置筛选框，通过改造Adapter制作GroupAdapter。
2. 选择Group中的4个或者5个加入到ScrollTag中
3. 当使用GroupAdapter进行选择的时候，将选中的数据加入到ScrollTag的左侧。
4. 点击完成之后会切换颜色。


首先个人认为筛选框可以直接放在FrameLayout中，当点击筛选的时候使用动画展示。
其次就是如何制作GroupAdapter的问题了，原先是想用Adapter中嵌套Adapter的形式的，现在准备思考有没有更好的方法。(想不出来，准备使用最最原始的方法了)

## 遇到的问题

### 主题书单制作发生的问题

1. RecyclerView 采用LinearLayout.Horizontal的形式的时候，item的高度必须自己设定，不能设置成match_parent
2. 如何实现文字选中的效果
3. 如何实现ScrollTag点击之后让FilterTag一起选中的问题 （今天晚上思考一下）

## 明天的任务

1. 代码的重构
2. 排行榜的详情
3. 别人家的排行榜
4. 分类中的类别详情
5.