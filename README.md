# img-zoom图片放大器
### 介绍
很多电商网站（淘宝、京东...）在商品详情页中，鼠标悬停在商品图片上，便会出现对应的放大区域。

这里是该功能的简易版实现插件。

### 思路
1. 采用ES6语法，面向对象编程。
2. 鼠标移入图片框，创建移动遮罩框，以及对应大图显示区。
3. 根据移动遮罩框的移动位置，动态改变大图片的绝对定位位置。

### 引入

``` javascript
new ImgZoom('.zoomWrapper', {
	zoomW: 420,  //放大框宽高，默认就是420
	zoomH:420
});
```


### 效果

![enter description here][1]


  [1]: ./img/zoom.gif "zoom.gif"