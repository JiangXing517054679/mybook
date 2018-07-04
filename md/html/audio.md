#audio音频标签
audio标签定义声音，比如音乐或其他音频流。

|属性|说明|
|:-  |:-  |
|src|设置音频的地址|
|autoplay|加载完后自动播放|
|contorls|音频的控制台|
|loop|视频播放完后再次播放|
|preload|如果出现该属性，则音频在页面加载时进行加载，并预备播放。如果使用 "autoplay"，则忽略该属性。|
|muted|规定视频的音频输出应该被静音。|

#文件格式
|属性|说明|
|:-  |:-  |
|.mp3|主流平台都支持播放|
|.ogg|只有谷歌和火狐支持播放|
|.wav|除了IE11以下不支持，其余都支持播放|

#注意
    1.在苹果系列的浏览器和安卓移动端的浏览器会禁止自动播放，需要用户点击操作才能播放。
    2.如果要转变格式，尽可能使用AE，格式工厂等软件进行格式转换。
    3.可以在开始标签和结束标签之间放置文本内容，这样老的浏览器就可以显示出不支持该标签的信息。

```
<audio src="media/music.mp3" autoplay controls></audio>
```

#例子
<audio src="../../media/music.mp3"  controls></audio>
#心得
1.它是一个存放音频的一个元素
2.给你的网页插入一段音频，让你的网页瞬间B格满满的