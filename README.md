# iconfont-saw 抗锯齿
部分浏览器下阿里图标库的字体图标在20*20px下的显示有锯齿
```
-webkit-font-smoothing: antialiased;
-webkit-text-stroke-width: 0.18px;
-moz-osx-font-smoothing: grayscale;
```
 
新建 一个标签加上这三条属性 放到原来的标签里面 -webkit-text-stroke-width: 0.18px可调试 0.2左右最好
