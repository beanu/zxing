<img align="right" src="https://raw.github.com/wiki/zxing/zxing/zxing-logo.png"/>

## 二维码源码优化实现
手机上实现扫一扫功能，大部分的业务只是识别QR二维码。zxing提供了大而全的东西，因此我们需要一款定制版的zxing

扫一扫的第三方库，大部分都是基于zxing做的上层开发。大厂也不公开他们优化的源码。因此，这次通过收集大厂的优化方案，自己实现一套


基于[zxing 3.4.0 Latest commit 24a5f9c on 16 Feb](https://github.com/zxing/zxing)

[下载地址：扫描器](https://github.com/beanu/zxing/releases/download/v0.01/android-release.apk)


## 扫描性能优化
- 去除zxing额外支持的格式
- 删除zxing冗余代码
- TODO 将处理相机帧从串行改为并行

## 交互体验优化
- 自动放大
- 竖屏扫码
- TODO 双击放大
- TODO 重力传感器聚焦
- TODO 手势调整焦距



### 参考文章
* [字节跳动技术方案](https://zhuanlan.zhihu.com/p/44845942)
* [爱奇艺二维码优化](https://mp.weixin.qq.com/s/tB7htYzrmP0wGUFCkCvBUw)
* [二维码放大摄像头](https://www.jianshu.com/p/710e3d29dfaf)
