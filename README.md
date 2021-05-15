PC微信机器人之彻底搞懂hook原理及手动实现
QQ：2645542961
其实hook分很多种，我们最说的hook就是 Inline Hook，是用的最广泛的也是自由度最大的，相交于其他Hook ，比如有：apihook ，消息hook 等等hook，他们都有局限性，apihook只能hook windows 的api 消息，他们局限性太大了，所以应用的相对来说，不是那么自由。

下图是hook的原理图，

![image](https://user-images.githubusercontent.com/73727649/118352657-2165b400-b595-11eb-90e5-1eef05ceb524.png)
先找到基址，下断点，找到call，然后修改里面的内容，在原封的返回。
![image](https://user-images.githubusercontent.com/73727649/118352668-2dea0c80-b595-11eb-8785-597d016ae0e9.png)
现在已实现很多有趣的功能，比如群管，发各种消息，加好友等等，可提供接口二次开发，欢迎技术交流。
QQ：2645542961
![image](https://user-images.githubusercontent.com/73727649/118352692-4b1edb00-b595-11eb-97b4-0caaa0940712.png)

