# Hybrid调试指南
>
开发接口过程中如何自测接口?

## Dependency
>
- Chrome
- Android SDK Level >=19

## Usage

>
- Android设备连接电脑，并打开USB调试
<<<<<<< HEAD
- 通过Hybrid打开任意页面
- 使用Chrome浏览器打开，[chrome://inspect](chrome://inspect),  调用JSBridge对应的接口

## Picture
> - 以下是 “隐藏TitleBar”为例，通过JSBridge来隐藏Native的标题栏

- 打开Console控制台

![inspect1](images/inspect1.png)

- 注入JSBridge.call("hideTitlebar");

![inspect2](images/inspect2.png)

- App端隐藏掉Titlebar
- 
![hideTitle](images/hideTitlebar.png)
=======
- 通过Hybrid打开任意页面，测试页面-Slideplus素材中心页
- 使用Chrome浏览器打开，[chrome://inspect](chrome://inspect)

>>>>>>> 68c9959aabdedfc07c70a0e0316c0ba5345be043
## Sample
>
- JSBridge.call("hideTitlebar")  ---Hide Title bar

<<<<<<< HEAD
<iframe height=350 width=550 src="http://192.168.1.33:9090/machao/worktilefiles/raw/master/inspect.mov"  frameborder=0>
=======
<iframe height=350 width=550 src="inspect.mov"  frameborder=0>
>>>>>>> 68c9959aabdedfc07c70a0e0316c0ba5345be043


