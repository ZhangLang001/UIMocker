# UIMocker
封装了对Android的UI模拟操作的库

UIMocker是基于xposed框架实现的一个用来操作被注入app的ui的一个model

UImocker实现了如下功能:<br/>
1.实现了点击，长按操作，对任意一个view发起点击或者长按操作。<br/>
2.实现了对listview，或者scrollerview的滚动操作，可以和很轻松实现翻页操作(水平，垂直)。<br/>
3.实现了滑动相关的api，可以很轻松的模拟一些常用的手势操作。<br/>
4.实现了对ui界面的某个文本进行定位，结合clicker相关的api可以实现对任意view的点击<br/>
5.实现了对任意activity生命周期的拦截，可以在调用onCreate(),onResume(),onPause(),onDestroy()之前或之后插入我们自己的代码(非hook实现)<br/>
6.实现了对webview的js注入，模拟点击webview的某个元素<br/>
