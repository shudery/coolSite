

做好切图准备用不同尺寸的图片适应浏览器时
发现媒体查询无法正确覆盖，做实验调试
首先无论什么元素，若设置了style属性，则外部css文件包括其中的媒体查询，在调整浏览器窗口时都是无法覆盖style属性的
img这个元素本身就有src属性引用图片，如果用background-image属性设置看不到图片
会被src覆盖，除非src引用的图片透明，img的图片和background的可以配合做动画。。

img和Background-image的区别

一直没能解决切换图img的图片问题，PS也是渣渣得很，设计不过关。。

自适应边距也应该用%，max-width有时候非常有用