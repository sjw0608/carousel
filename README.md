# 旋转木马插件

## 使用

```默认模板
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">

    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style></style>
    <script src="./js/jquery.js"></script>
    <script src="./js/carousel.js"></script>
</head>

<body>
<div class="J_Poster poster-main" data-setting='{
            " width ": 1000,
            "height ": 270,
            "posterWidth ": 640,
            "posterHeight ": 270,
            "scale ": 0.9,
            "speed ": 500,
            "verticalAlign ": " middle ",
            "autoPlay": true,
            "delay": 2000
    }'>
        <div class="poster-btn poster-prev-btn"></div>
        <ul class="poster-list">
            <li class="poster-item"></li>
        </ul>
        <div class="poster-btn poster-next-btn"></div>
    </div>
</body>
<script>
$(function () {

        Carousel.init($(".J_Poster"));
});
</script>
</html>
```

## 配置参数

```默认配置参数
data-setting = {
      width: 1000, //幻灯片的宽度
      height: 270, //幻灯片的高度
      posterWidth: 640, //幻灯片第一帧的宽度
      posterHeight: 270, //幻灯片第一帧的高度
      scale: 0.9, //记录显示比例关系
      speed: 500, //幻灯片切换的速度
      autoPlay: false, //是否自动播放 默认为false
      delay: 5000,  //自动播放速度 默认为 5000ms
      verticalAlign: 'middle' //图片对其方式 默认为middle（居中对齐） 其他参数：top（顶部对齐） bottom（底部对齐）
    }
```
