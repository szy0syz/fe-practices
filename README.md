# fe-practices

纯の前端练习

> 20190429: 补到今天又点感觉，简单特效，看了效果就能写~

## 20190504 回到顶部

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