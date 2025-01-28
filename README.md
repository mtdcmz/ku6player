# ku6player

## 项目简介

一款HTML5开源的仿酷6网视频播放器，界面简洁，支持MP4和M3U8格式视频播放（使用[HLS.js](https://github.com/video-dev/hls.js/)）。

**在线演示**: [Live Demo](https://mtdcmz.github.io/ku6player/play.html?url=)

## 调用方法

### 直接调用

在URL后添加视频地址：
```
https://mtdcmz.github.io/ku6player/play.html?url=视频地址
```

### iframe嵌入

使用iframe将播放器嵌入网页：
```html
<iframe src="https://mtdcmz.github.io/ku6player/play.html?url=视频地址" width="640" height="360" frameborder="0" allowfullscreen></iframe>
```

**注意**: 替换`视频地址`为实际视频链接。
