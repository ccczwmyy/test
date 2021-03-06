### Appium
---
> - **跨平台**，android，iOS接入无侵入性。

#### 安装
参考官网[说明文档](https://github.com/appium/appium/blob/master/docs/en/about-appium/getting-started.md)，要有耐心，中间可能出现各种错误，推荐使用**Appium Desktop**。
#### 使用
1. 启动**Appium Desktop**。
2. 点击**Start Server**。
```bash
[Appium] Welcome to Appium v1.7.2
[Appium] Appium REST http interface listener started on 0.0.0.0:4723
```
3. 测试用例编写
参考[官方DEMO](https://github.com/appium/appium/blob/master/docs/en/about-appium/appium-clients.md)，本项目使用JAVA Client。

4. 生成测试报告 **TODO**

5. 视频(Android&Ios)
[执行测试用例](https://youtu.be/XQRgkCn6c8c)

6. 问题
- Toast识别问题：必须使用LENGTH_LONG（3500ms）才能识别，如果是LENGTH_SHORT（2000ms）大部分都识别不出来。（Appium-1.3.1）

#### 参考文档
> - [美团-基于 Appium 的 Android UI 自动化测试](https://tech.meituan.com/appium-mock-test.html)
> - [官方文档](https://github.com/appium/appium)
> - [官方示例代码](https://github.com/appium/sample-code)
> - [饿了么物流技术-自动化之旅--Appium](http://lrd.ele.me/2017/02/17/%E8%87%AA%E5%8A%A8%E5%8C%96%E4%B9%8B%E6%97%85--Appium/)
> - [Appium 元素定位方式大揭秘](https://juejin.im/post/5997dff7f265da24921b170d)
