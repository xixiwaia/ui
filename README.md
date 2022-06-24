# ui
### 分别实现了tab选项卡和collapse手风琴的效果

### message与tab和collapse不同的是： 
1.我们不知道会创建多少个新的dom节点（消息弹窗），因此没有在一开始就罗列出来，而是在用户创建对象的时候，我们再创建dom <br>
2.message中constructor设置了初始值，简化了写法 <br>
3.setTimeout中需要this代表当前的对象，如果使用的function创建函数this会改变，因此我们使用箭头函数<br>
