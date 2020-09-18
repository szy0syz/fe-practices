# fe-practices

纯の前端练习

> 20200118: 刷到第 50 号效果，想想原来自己大部分用 js 写，判断各种边界情况，感觉好弱鸡。
> 突然对 css 有种领悟：css 的美是自然雕琢的美，不像 js 那样需要人工抹粉涂口红！

> 20200104: 刷到 999 成神，刷到 9999 超神. (有生之年系列?)

> 20190429: 补到今天又点感觉，简单特效，看了效果就能写~

## 073_20200918_Creative-CSS-Loading

![072_20200918_Header](/073_20200918_Creative-CSS-Loading/preview.gif)

## 072_20200918_Header-Clip-path

![072_20200918_Header](/072_20200918_Header-Clip-path/preview.gif)

## 070_20200425_Custom-Checkbox

![20200425](/070_20200425_Custom-Checkbox/preview.gif)

> get 新的 css-tricks

```css
.option-input {
  -webkit-appearance: none;
  -o-appearance: none;
  -moz-appearance: none;
  -ms-appearance: none;
  appearance: none;
  position: relative;
  top: 13.33333px;
  right: 0;
  bottom: 0;
  left: 0;
  height: 40px;
  width: 40px;
  transition: all 0.15s ease-out 0s;
  background: deepskyblue;
  border: none;
  color: white;
  cursor: pointer;
  display: inline-block;
  margin-right: 0.5rem;
  outline: none;
  position: relative;
  z-index: 1000;
}

option-input:hover {
  background-color: white;
}

.option-input:checked::before {
  height: 40px;
  width: 40px;
  position: absolute;
  content: '✓';
  display: inline-block;
  font-size: 30.5559px;
  text-align: center;
  line-height: 40px;
}
```

## 068_20200406_Hover-Email-Input

![20200412](/068_20200406_Hover-Email-Input/preview.gif)

## 067_20200406_Glowing-Loading

![20200406](/067_20200406_Glowing-Loading/preview.gif)

## 066_20200324_Rubber_Band_Animation

![20200324](/066_20200324_Rubber_Band_Animation/preview.gif)

## 065_20200320_Profile-Card 个人展示卡

![20200320](/065_20200320_Profile-Card/preview.gif)

## 064_Product-Card 耐克鞋

## 062_20200305_Masonry-layouts

![20200305](/062_20200305_Masonry-layouts/preview.gif)

## 061_20200301_Responsive-Navbar 响应式导航

![20200301](/061_20200301_Responsive-Navbar/preview.gif)

## 060_20200228 创意注册表单

![202002282](/060_20200228_Interactive-Form/preview.gif)

## 059-20200228 3D 卡片展示

> 真是感慨 css-tricks 的精髓所在！
> 原来卡片叠飞的效果这样搞啊！

```html
<div class="imgBx">
  <img src="./1.jpeg" alt="1" />
  <img src="./1.jpeg" alt="1" />
  <img src="./1.jpeg" alt="1" />
</div>
```

```css
.container .imgBx:hover img:nth-child(3) {
  transform: translate(100px, -100px);
}
.container .imgBx:hover img:nth-child(2) {
  transform: translate(50px, -50px);
  opacity: 0.5;
}
.container .imgBx:hover img:nth-child(1) {
  transform: translate(0px, 0px);
  opacity: 0.1;
}
```

![20200228](/059_20200228_3D-Perspective-Post/preview.gif)

## 058-20200212 图片切换效果

![20200212](/058_20200212_Image-Distortion-Hover/preview.gif)

## 057-20200209 霓虹边框按钮

![20200209](/057_20200209_Neon-Light-Button/preview.gif)

> 此动画很能体现 css 的 **tricks** 精髓所在！

- css 倒映 `-webkit-box-reflect: below 1px linear-gradient(transparent, #003)`
- css 滤镜调色 `filter: hue-rotate(115deg);`
- 按钮左上和右下原来是两个小方块！
- 该动画精髓在延迟 `transition-delay`

## 056-20200206 GSAP 鼠标跟随效果

![20200206](/056_20200206_GSAP-Mousemove-Text/preview.gif)

## 055-20200205 全屏动画导航菜单

![202002051](/055_20200205_Full-screen-Overlay-Navigation/preview.gif)

## 054-20200205 CSS3 翻转相册

![20200205](/054_20200205_3D-Transform-Gallery/preview.gif)

## 053-20200126 CSS3 移动光条导航

![20200121](/053_20200126_CSS3-Menu-Hover-Effect/preview.gif)

- 🎉 实现原理：
  - 一个大容器定下宽和高
  - 一个光标 div 在大容器下根据 index 算 transformY 移动即可

## 052-20200118 SVG 波浪倒映 DIV

![20200121](/052_20200121_Wavy-Div-Animation/preview.gif)

## 051-20200118 H5 底部导航栏

![202001181](/051_20200119_H5_Bottom-Bar-Nav/preview.gif)

## 050-20200118 左右滑动导航栏特效

![202001181](/050_20200118_Skewed-Tab-Interactions/preview.gif)

## 049-20200118 鼠标聚焦导航栏特效

![20200118](/049_20200118_CSS-Creative-Menu-Hover/preview.gif)

## 048-20200117 左侧导航汉堡菜单效果

![20200117](/048_20200117_Hamburger-Menu/preview.gif)

## 047-20200115 个人资料展示页

![20200115](/047_20200115_Profile-Card-Page/preview.gif)

## 046-20200114 登录页

![202001142](/046_20200114_Ladning-Page/preview.gif)

## 045-20200114 图标视频背景鼠标特效

![202001141](/045_20200114_Icon-Hover-Effects/preview.gif)

## 044-20200113 搜索框特效

![20200113](/044_20200113_Tranforming-Search-Bar/preview.gif)

## 043-20200108 服装商品展示特效

![202001082](/043_20200108_Produc-Grid-Hover/preview.gif)

## 042-20200108 霓虹灯爱心

![202001081](/042_20200108_Neon-Light-CSS3/preview.gif)

## 041-20200107 卡片点击特效

- `text-rendering: optimizeLegibility;` 浏览器在绘制文本时将着重考虑易读性，而不是渲染速度和几何精度.它会使字间距和连字有效。 (Chrome 上没效果)

![202001071](/041_20200107_Blur-Focus-CSS3-Hover/lig.png)

![202001071](/041_20200107_Blur-Focus-CSS3-Hover/preview.gif)

## 040-20200107 CSS 飞翔卡片

![202001070](/040_20200107_CSS3-Flying-Tab-Menu/preview.gif)

## 20200106 水波浪字体效果

![20200106](/039_20190426_Water-Animation-Text/preview.gif)

## 20200106 个人资料卡特效

![20200106](/038_20200106_Creative-Profile-Card-Hover/preview.gif)

> get 到 css 书写规整新技能

## 20200104-3 文字和背景轮滚视觉差

![202001043](/037_20200104_Text-Clip-Mask-Parallax-Scrolling/preview.gif)

## 20200104-2 按钮背景刷笔效果

> 原理是张背景图 😂

![202001042](/036_20200104_Creative-Button-Hover/preview.gif)

## 20200104-1 思维框子

![202001041](/035_20200104_Creative-Div-Box-Design/preview.gif)

## 20200103-2 自定义滚动条

![202001032](/034_20200103_Custom-Scrollbar/preview.gif)

## 20200103-1 网页暗黑模式切换

![20200103](/033_20200103_Pure-CSS3-Dark-Mode/preview.gif)

## 20191210 电视机雪花噪点

![20191210](/032_20191210_TV_Noise/preview.gif)

## 20191109 线条变色爬动

![20191109](/031_20191109_Elastic_Line/preview.gif)

## 20190820 loader 特效

![201908101](/030_20190820_Glowing-Gradient-Loader-Ring/preview.gif)

## 20190810 上下滑动文字效果

![201908101](/029_20190810_Sliding_Text/preview.gif)

## 20190810 闪光字效果

![201908102](/028_20190810_Glowing_Text/preview.gif)

## 20190729 3D 卡片翻转效果

> 效果一般点

![20190729](/025_20190729_3D_Flip_Card/preview.gif)

## 20190719 首页圆形 header 效果

![20190719](/024_20190719_Curved-Header/preview.jpg)

- 🎉 实现原理：
  - 首先 “border-radius: 0 0 50% 50%“ 画半个圆的
  - 再将 “border-radius: 0 0 50% 50%/0 0 100% 100%;” 圆的垂直方向也设，成一个椭圆。
  - ”border-radius: 100px 25px 50px 50px / 50px 25px 50px 25px;“

![201907192](/024_20190719_Curved-Header/border.webp)

## 20190717 纯 Css3 预加载效果

![20190717](/023_20190717_Css3-Preloader/preview.gif)

- 🎉 实现原理：
  - 多个 "box-shadow" 的错位 + "border-radius" 实现小点阵效果；
  - "background-color: currentColor;" 可以实现每行第一个小圆点带色；
  - 使用 "animation-delay: -1s;" 让两个点阵有间隔；

## 20190523 波浪效果

![20190520](/022_20190523_Ripple-Animation/preview.gif)

## 20190520 卡片聚焦特效

![20190520](/021_20190520_CSS-Card-Hover/preview.gif)

- 🎉 实现原理：
  - .face 都设 absolute，“后”覆盖“前”
  - 对别对卡片容器.face2 和里面 h2 对 transition
  - 改变高度和设置容器字体大小
  - 这里使用 em，非常恰当，因为 em 就是根据上级父元素大小来定子元素大小
- ✅ 知识点：
  - grid 布局
    - 在.container 中设宽度 1200px，然后定义为 grid 布局，设置 grid 布局中每列的样式，最小 350px 的宽度，最大 1fr(均分)，auto-fit 表示一行能装几个装几个 card;
    - grid-gap 设置每个轨道之间的间隙，不含最左和最右；
    - 使用 margin 让其水平居中
  - 对半视差折纸展示
    - 在容器内部加个 before 的伪类，然后占位 50%和 10%的透明
  - 关于卡片内部布局
    - 先设两个展示也都 absolute，因 html 元素先后顺序，天生后面元素覆盖前面元素，则不需要设置 z-index

## 20190516 回到顶部

- ✅ 知识点：`html { scroll-behavior: smooth; }`

## 20190504 导航特效

![201905042](/019_20190509_Responsive-Navigation-Hover-Menu/preview.gif)

## 20190504 按钮特效

![201905042](/018_20190504_Buttons-With-Hover/preview.gif)

## 20190504 卡片阴影特效

![201905041](/017_20190504_Card-Effects/preview.gif)

## 20190503 响应式产品介绍页

![201905031](/016_20190503_Responsive-Product-Card/preview.gif)

## 20190501 CSS 分屏鼠标聚焦效果

![201905012](/015_20190502_CSS-Split-Screen-Hover/preview.gif)

- 🎉 实现原理：
  - 外层有个 flex 容器放 N 个图片，每个图片设 flex-grow 和 transition
  - 让被聚焦时，再次设置 flex-grow 大小，这个大小得根据图片宽度来定
  - 图片容器再次 flex，因为内部描述容器需要定位
  - 外层容器聚焦时给默认所有图片容器设置透明度较黑
  - 指定给具体内层获得聚焦的图片容器设置透明度为零
- ✅ 知识点：
  - `flex-grow` 最佳实现之一

## 20190501 纯 CSS3 实现动画弹窗

![201905011](/014_20190501_CSS3-Animated-Modal/preview.gif)

## 20190429 图片聚焦效果

![20190427](/013_20190429_Image-Hover/preview.gif)

## 20190427 首页双视觉

## 20190429 打字效果

![20190427](/012_20190429_Text-Typing/preview.gif)

- 🎉 实现原理：使用帧动画将承载文本的容器宽度(width)一点一点的放大，直到所有文字全部展现。
- ✅ 知识点：
  - `ch` 数字 0️⃣ 的宽度，好比理解为一个等宽字体的短度，这里使用 ch 精确控制容器宽度(到底要显示几个字母)
  - `white-space: nowrap;` 规定段落中的文本是否换行，因为容器刚开始宽度很小，必须设置 nowarp 不换行，记得超出部分隐藏
  - `steps` 在 css3-animation 中，该属性表示动画分为几段。怎么理解？简单理解显示器刷新频率。

![20190427](/011_20190427_Dual-Parallax-Effect/preview.gif)

## 20190427 首屏 css3 轮播

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
