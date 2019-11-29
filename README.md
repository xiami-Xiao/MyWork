# MyWork
   城市预约挂号平台项目总结：城市预约挂号平台这个网页我运用了很多电商网站都用的网页的框架，用html搭建框架，用css做整个页面的装饰，用js做页面的动态渲染，例如下拉菜单，轮播图，二级菜单等应用普遍的动态效果。
  
  城市预约挂号平台项目中遇到的问题：
  
  1.网页时一定一定要先进行整体规划，看有哪些是可以通用的。   
  解决方法：用了一个.wrap的div包裹相同宽度的部分，设置统一宽度。
  
  2.在用ul，li写网页上图片下文字的时候会发现图片有时不居中。
    解决方法：首先要让li变成块级元素，给他display：block，加了之后会发现，这个li部分的高度不再是一点点了，而是被内部元素撑开。然后在给img加个margin：auto；
    
  3.设计CSS时，把容器属性设置成了浮动，很容易造成页面错位，网页由此变得十分混乱。
    解决方法：不要慌嘻嘻加上这段代码就可以啦。
    
    
    .clearfix:after{content:”.”; display:block; height:0; clear:both; visibility:hidden; text-align:center}.clearfix{display:inline-block;}* html .clearfix{height:1%}.clearfix{display:block;}

　　.clearfix:after{content:”.”; display:block; height:0; clear:both; visibility:hidden; text-align:center}

　　.clearfix{display:inline-block;}

　　* html .clearfix{height:1%}.clearfix{display:block; }
  
  
  经验总结：
  小白建议在做各个模块的时候加上明显的边框有利于布局调试。像 div {border： solid 1px 吉县f00;} 之类的全局规则可以暂时为你查出布局问题。为特定的元素加上边框可帮您找到难以发觉的交错或空白问题。
  
  
  
  
   
  
