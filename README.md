# VTEC-slider

插件基于jQurey扩展而来,理论上**你用什么版本jQurey就能支持到什么版本的IE.**

所获取的data参数包含:

- title(鼠标悬停标题)  
- src(图片地址)   
- href(跳转地址)

```javascript
 $('#focus').vtec({				//#focus是你需要放置轮播图的大盒子
            data:data,			//data是所需要传到的数据
            showTime:200,		//动画时间
            isAuto:true			//是否自动轮播,默认是false
        });
```

