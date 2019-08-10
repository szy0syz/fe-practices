# fe-practices

纯の前端练习

> 20190429: 补到今天又点感觉，简单特效，看了效果就能写~

## 20190810 上下滑动文字效果

![201908101](/029_20190810_Sliding_Text/preview.gif)

## 20190810 闪光字效果

![201908102](/028_20190810_Glowing_Text/preview.gif)

## 20190729 3D卡片翻转效果

> 效果一般点

![20190729](/025_20190729_3D_Flip_Card/preview.gif)

## 20190719 首页圆形header效果

![20190719](/024_20190719_Curved-Header/preview.jpg)

* 🎉 实现原理：
  * 首先 “border-radius: 0 0 50% 50%“ 画半个圆的
  * 再将 “border-radius: 0 0 50% 50%/0 0 100% 100%;” 圆的垂直方向也设，成一个椭圆。
  * ”border-radius: 100px 25px 50px 50px / 50px 25px 50px 25px;“

![201907192](/024_20190719_Curved-Header/border.webp)

## 20190717 纯Css3预加载效果

![20190717](/023_20190717_Css3-Preloader/preview.gif)

* 🎉 实现原理：
  * 多个 "box-shadow" 的错位 + "border-radius" 实现小点阵效果；
  * "background-color: currentColor;" 可以实现每行第一个小圆点带色；
  * 使用 "animation-delay: -1s;" 让两个点阵有间隔；

## 20190523 波浪效果

![20190520](/022_20190523_Ripple-Animation/preview.gif)

## 20190520 卡片聚焦特效

![20190520](/021_20190520_CSS-Card-Hover/preview.gif)

* 🎉 实现原理：
  * .face 都设absolute，“后”覆盖“前”
  * 对别对卡片容器.face2和里面h2对transition
  * 改变高度和设置容器字体大小
  * 这里使用em，非常恰当，因为em就是根据上级父元素大小来定子元素大小
* ✅ 知识点：
  * grid布局
    * 在.container 中设宽度1200px，然后定义为grid布局，设置grid布局中每列的样式，最小350px的宽度，最大1fr(均分)，auto-fit表示一行能装几个装几个card;
    * grid-gap 设置每个轨道之间的间隙，不含最左和最右；
    * 使用margin让其水平居中
  * 对半视差折纸展示
    * 在容器内部加个before的伪类，然后占位50%和10%的透明
  * 关于卡片内部布局
    * 先设两个展示也都absolute，因html元素先后顺序，天生后面元素覆盖前面元素，则不需要设置z-index

## 20190516 回到顶部

* ✅ 知识点：`html { scroll-behavior: smooth; }`

## 20190504 导航特效

![201905042](/019_20190509_Responsive-Navigation-Hover-Menu/preview.gif)

## 20190504 按钮特效

![201905042](/018_20190504_Buttons-With-Hover/preview.gif)

## 20190504 卡片阴影特效

![201905041](/017_20190504_Card-Effects/preview.gif)

## 20190503 响应式产品介绍页

![201905031](/016_20190503_Responsive-Product-Card/preview.gif)

## 20190501 CSS分屏鼠标聚焦效果

![201905012](/20190502_CSS-Split-Screen-Hover/preview.gif)

* 🎉 实现原理：
  * 外层有个flex容器放N个图片，每个图片设flex-grow和transition
  * 让被聚焦时，再次设置flex-grow大小，这个大小得根据图片宽度来定
  * 图片容器再次flex，因为内部描述容器需要定位
  * 外层容器聚焦时给默认所有图片容器设置透明度较黑
  * 指定给具体内层获得聚焦的图片容器设置透明度为零
* ✅ 知识点：
  * `flex-grow` 最佳实现之一

## 20190501 纯CSS3实现动画弹窗

![201905011](/20190501_CSS3-Animated-Modal/preview.gif)

## 20190429 打字效果

![20190427](/20190429_Text-Typing/preview.gif)

* 🎉 实现原理：使用帧动画将承载文本的容器宽度(width)一点一点的放大，直到所有文字全部展现。
* ✅ 知识点：
  * `ch` 数字0️⃣的宽度，好比理解为一个等宽字体的短度，这里使用ch精确控制容器宽度(到底要显示几个字母)
  * `white-space: nowrap;` 规定段落中的文本是否换行，因为容器刚开始宽度很小，必须设置nowarp不换行，记得超出部分隐藏
  * `steps` 在css3-animation中，该属性表示动画分为几段。怎么理解？简单理解显示器刷新频率。

## 20190429 图片聚焦效果

![20190427](/20190429_Image-Hover/preview.gif)

## 20190427 首页双视觉

![20190427](/011_20190427_Dual-Parallax-Effect/preview.gif)

## 20190427 首屏css3轮播

![20190427](/010_20190427_Full-Landing-Carousel/preview.gif)

## 20190427 首屏背景图放大

![20190427](/009_20190427_Animated-Full-Landing/preview.gif)

## 20190427 透明登录界面

![20190427](/008_20190427_Transparent-Login-Form/preview.jpg)

## 20190427 响应式动效相册

![20190427](/007_20190427_responsive-gallery/gallery.gif)

## 20190427 图片自上而下效果

![20190427](http://cdn.jerryshi.com/picgo/img-effect.gif)

## 20190426 coming soon

![20190425](http://cdn.jerryshi.com/picgo/1556209300084.jpg)

## 20190421 按钮特效

![201904211](http://cdn.jerryshi.com/picgo/hover-effect-button.gif)

## 20190420 仿抖音文字效果

![201904201](http://cdn.jerryshi.com/picgo/dy.gif)

## 20190420 企业站响应式服务介绍栏

![201904202](http://cdn.jerryshi.com/picgo/services-section.gif)
