# DouYinComment
这个Demo主要功能:
## 1.模仿抖音播放小视频功能;(这个功能网上有很多Demo,所以大家可能大家需求不大,功能2可能会对您有所帮助)
### (1).支持边下边播
### (2).支持视频预加载
![image](https://github.com/tangtiancheng/DouYinComment/blob/master/gif/smallVideoImage.gif)

## 2.这个Demo有仿照抖音的小视频评论手势拖拽效果(直接将TCCommentsPopView这个类拖入您的项目即可使用,很简单)
可以说完全和抖音的效果一模一样,该功能我已经在"铃声多多"项目中使用,iOS端日活有70万左右,现在是没发现有什么问题.我在github,cocoachina,coco4app等Demo网址上找了很久,都没有一个demo是能完全和抖音的一致的.如果觉得好用希望给一个star

![image](https://github.com/tangtiancheng/DouYinComment/blob/master/gif/comment.gif)

## 3.和铃声多多一样,支持上传音频到库乐队(GarageBand)直接设置手机铃声
这个小众功能我看现在基本没有开发者把实现代码开源出来,鉴于之前有好几位iOS开发者通过简书找到我,都是公司需要做这个功能但是不知道怎么实现,所以今天把这个功能实现代码写出来,希望能帮到大家.如果确实解决了您的燃眉之急,希望能帮我点一个star,谢谢啦.

![image](https://github.com/tangtiancheng/DouYinComment/blob/master/gif/GarageBandImage.gif)


## 4.多列表嵌套分页滚动,header悬浮
### 该功能共有两个类:1.TCViewPager(用于处理列表分页)  2.TCNestScrollPageView(用于处理嵌套header滚动悬浮)
如果你已经有了自己的分页控件,但是想在其基础上再添加header悬浮滚动的功能,那么你就只需要使用TCNestScrollPageView即可,不需要用到TCViewPager.用法非常非常简单,直接参照demo
### (1).简单分页
![image](https://github.com/tangtiancheng/DouYinComment/blob/master/gif/分页效果.gif)
### (2).headerView随时变动
![image](https://github.com/tangtiancheng/DouYinComment/blob/master/gif/headerView随时变动.gif)
### (3).headerView吸顶
![image](https://github.com/tangtiancheng/DouYinComment/blob/master/gif/headerView吸顶.gif)
### (4).改变headerView高度
![image](https://github.com/tangtiancheng/DouYinComment/blob/master/gif/改变headerView高度.gif)
### (5).headerView不吸顶,下拉变大
![image](https://github.com/tangtiancheng/DouYinComment/blob/master/gif/headerView不吸顶,下拉变大.gif)

另外还有其他的效果自己去看demo,使用起来很简单,不会qing侵入你的代码,实现原理也不难,自己去看代码也肯定能看懂
