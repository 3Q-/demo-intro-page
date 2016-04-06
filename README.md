#基于 api.openFrameGroup 实现的 App 引导页

绝大多数 App 都会有自己的引导页、广告页等。
引导页的实现创意可以说是千变万化，但实际实现却大同小异。

**使用 api.openFrameGroup 的 bgColor 参数来实现引导页相比于使用脚本使用有很多好处**
* 页面间的滑动效果是原生实现，用户体验好，无卡顿
* bgColor 设置的图片也是原生渲染，性能强于给 body 元素设置背景图的方式

##这个示例以脚本结合原生的方式为开发者实现了一个引导页
* 示例请使用 Apploader 查看。

* frameGroup 的使用可以参考文档([http://docs.apicloud.com/端API/api#28](http://docs.apicloud.com/端API/api#28))