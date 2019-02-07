> 翻页H5的背景图通常是要求全屏的，然而这存在一个问题，目前市面上的手机屏幕比例非常的不统一，这导致在背景图上的处理相当要注意。

### [demo-1](demo-1.html)

设置background-size:100% 100%对于过去的手机比例拉伸勉强可以接受

### [demo-2](demo-2.html)

设置background-size:100% 100%在iPhone X上拉伸明显，体验极差

### [demo-3](demo-3.html)

利用background-size:cover能保证图片正常比例的裁切

### [demo-4](demo-4.html)

利用background-size:cover和background-position:center完美解决背景图的显示和裁切

### [demo-5](demo-5.html)

图像的重点必须在蓝红交叉的位置