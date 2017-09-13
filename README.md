前端优化：1：静态资源，制作雪碧图，减少请求返回的数据量，压缩HTML，CSS，JS文件，小图标用iconfont代替。
  2页面渲染速度优化：css放在顶端，优先渲染，js放在底部避免阻塞，服务端如果用node的话，使用compress可开启压缩，
var express = require('express');
var compress = require('compression');
var app = express();
app.use(compress());
 vue框架特点：1：mvvm:双向数据绑定，2：组件化：在vue中所有的都是组件化，3模块化：。
 应用：可以用在webapp，spa(单页面应用)
 

