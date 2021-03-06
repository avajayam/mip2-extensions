# mip-stats-tianrun 天润统计

天润统计组件

标题|内容
----|----
类型|通用，定制
支持布局|responsive, fixed-height, fill, container, fixed
所需脚本|https://c.mipcdn.com/static/v2/mip-stats-tianrun/mip-stats-tianrun.js

## 示例

MIP 提供天润的插件，便于站长更好的接入 MIP，`<noscript>` 标签中是的代码是当访客手机不支持 JS 时直接 URL 回传统计数据，内容由第三方站长自己实现参数填充，代码示例：

```html
<!-- 人民网CMS自己实现参数填充 noscript 示例：-->
<mip-stats-tianrun sub="cli2" z="26">
  <noscript>
    <img src="//cl2.webterren.com/11.gif?z=26&amp;_wdxid=000000000000000000000000000000000000000000&amp;_wdt=011&amp;_wdc=w_2930&amp;_wdci=7678771&amp;_wda=254&amp;_wdp=2016-10-08&amp;_wdori=%u4e2d%u56fd%u53f0%u6e7e%u7f51%u7efc%u5408&amp;_wdti=%u6e56%u5317%u8b66%u6821%u6821%u82b1%u6652%u82f1%u6b66%u5236%u670d%u7167%u0030%u7ec6%u6570%u8b66%u5bdf%u754c%u7684%u4eba%u6c14%u201c%u7f51%u7ea2%u201d&amp;_wdurl=http://m2.people.cn/mip/r/MV80Xzc2Nzg3NzFfMjkzMF8xNDc1ODgzNjcz?s=baidu-mip&amp;_wdqd=m2_baidu&amp;_wdvs=wap&amp;_wda2=254&amp;_wdot=0" width="0" height="0" alt=""/>
  </noscript>
</mip-stats-tianrun>
```

## 属性

### sub

说明：要发送到的广告的子域

必填：否

格式：字符串

单位：无

默认值：cl2

### z

说明：天润广告z参数值

必填：否

格式：字符串

单位：无

默认值：26

## 注意事项

`img` 的 `src` 不能写协议
