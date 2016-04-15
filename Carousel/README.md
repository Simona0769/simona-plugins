#支持amd规范

#初始化

var carousel = Carousel("#selector", {});

#参数

a:长轴

b:短轴

slideClick:function(i, slide){} // slide点击事件 回调函数中:i 点击slide的下标，以0开始；当前点击的slide

onTouchStart: function(activeIndex,carousel) {} //点击开始事件  回调函数中:activeIndex 当前slide下标；carousel 当前插件对象

onTouchMove:function(activeIndex,carousel) {} //移动事件  回调函数中:activeIndex 当前slide下标；carousel 当前插件对象

onTransitionEnd:function(activeIndex,currentSlide,carousel) {} //变换结束事件  回调函数中:activeIndex 当前slide下标；currentSlide：当前slide； carousel 当前插件对象

#事件

next(); //跳到下一slide

prev(); //跳到上一slide

