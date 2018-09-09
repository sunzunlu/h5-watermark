# <font color="#F68736" face="微软雅黑">h5页面加水印</font>


##  为什么使用水印？
`版权问题！`防止他人滥用、转发、以及破坏个人或企业隐私。


## 实例展示

![](http://ydyfcs.epoint.com.cn:8066/doc/ydyf3z/assets/005/20180908-616b0095.png)  

- [h5页面加水印](http://ydyfcs.epoint.com.cn:8066/H5/Attaches/加水印/showcase_watermark/showcase_watermark.html) ` 注：按F12可在浏览器预览`

- 示例demo源代码(H5)：[点击此处进行下载](http://ydyfcs.epoint.com.cn:8066/H5/Attaches/加水印/showcase_watermark.zip)

## 典型项目应用案例

- 【大联动】 用户信息详情页面

## 依赖资源

- `js/watermark.js` 水印核心基类

## 配置和使用方法

__DOM结构__

`无`

__初始化__

以下代码是最简单的用法，更多复杂用法请参考`showcase_watermark`[源码下载](http://ydyfcs.epoint.com.cn:8066/H5/Attaches/加水印/showcase_watermark.zip)

```js
// 实例化
new WaterMark({
    watermark_txt: "姓名"
});
```

__参数说明__

| 参数 | 参数类型  | 说明  |
| :------------- |:-------------:|:-------------|
| watermark_txt | string | `可选` 水印字样 默认为`水印`字样 |
| watermark_x | string | `可选` 水印起始位置x轴坐标 默认为`20` |
| watermark_y | string | `可选` 水印起始位置Y轴坐标 默认为`20` |
| watermark_rows | string | `可选`   水印行数  默认为`480` |
| watermark_cols | string | `可选`   水印列数  默认为`8` |
| watermark_x_space | string | `可选` 水印x轴间隔  默认为`20` |
| watermark_y_space | string | `可选` 水印y轴间隔  默认为`10` |
| watermark_color | string | `可选`  水印字体颜色  默认为`#000000` |
| watermark_alpha | string | `可选`  水印透明度 默认为`0.2` |
| watermark_fontsize | string | `可选` 水印字体大小 默认为`14px` |
| watermark_font | string | `可选`  水印字体  默认为`fantasy` |
| watermark_width | string | `可选`  水印宽度 默认为`50` |
| watermark_height | string | `可选` 水印长度 默认为`40` |
| watermark_angle | string | `可选`  水印倾斜度数 默认为`20` |

