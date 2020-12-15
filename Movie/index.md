---
title: 绅士必看
date: 2020-02-11 22:27:02
type: "av"
layout: "av"
---

# 影音资源共享

* <b>这里准备用来分享各类好玩的资源</b>

{% dplayer "url=https://moeplayer.b0.upaiyun.com/dplayer/hikarunara.mp4" "addition=https://dplayer.daoapp.io/bilibili?aid=4157142" "api=https://api.prprpr.me/dplayer/" "pic=https://i.loli.net/2020/02/21/3ue6TRaJoHnr7Ng.jpg" "id=9E2E3368B56CDBB4" "loop=yes" "theme=#FADFA3" "autoplay=false" "token=tokendemo" %}

```
{% dplayer "url=https://moeplayer.b0.upaiyun.com/dplayer/hikarunara.mp4" "addition=https://dplayer.daoapp.io/bilibili?aid=4157142" "api=https://api.prprpr.me/dplayer/" "pic=https://moeplayer.b0.upaiyun.com/dplayer/hikarunara.jpg" "id=9E2E3368B56CDBB4" "loop=yes" "theme=#FADFA3" "autoplay=false" "token=tokendemo" %}
{% dplayer 'url=some.mp4' "id=someid" "api=https://api.prprpr.me/dplayer/" "addition=/some.json" 'code=player.on("loadstart",function(){console.log("loadstart")})' "autoplay" %} 
```

{% dplayer “url=https://mail2gduteducn-my.sharepoint.com/personal/3119006870_mail2_gdut_edu_cn/Documents/%E5%AD%A6%E4%B9%A0%E6%95%99%E7%A8%8B/0%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E4%BB%8E%E5%9F%BA%E7%A1%80%E5%88%B0%E5%AE%9E%E6%88%98%E5%85%A8%E5%A5%97%E8%AF%BE%E7%A8%8B(%E9%87%8D%E8%A6%81%EF%BC%81%EF%BC%81%EF%BC%81%E4%BC%98%E5%85%88%E8%A7%82%E7%9C%8B)/%E7%AC%AC%E4%BA%8C%E8%AF%BE%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E6%95%B0%E5%AD%A6-%E4%BC%98%E5%85%88%E8%A7%82%E7%9C%8B.mp4” “pic=https://i.loli.net/2020/02/21/PanD94WSjcgyrV3.png” "api=https://api.prprpr.me/dplayer/" "loop=yes" "theme=#FADFA3" "autoplay=false" "token=tokendemo"%}



{% dplayer “url=blob:https://mail2gduteducn-my.sharepoint.com/43008528-32b7-41be-a17a-57b4ff42be58” “pic=https://i.loli.net/2020/02/21/PanD94WSjcgyrV3.png” "api=https://api.prprpr.me/dplayer/" "loop=yes" "theme=#FADFA3" "autoplay=false" "token=tokendemo" "id=9E2E3368B56CDBB4"%}



<video class="dplayer-video dplayer-video-current" webkit-playsinline="" playsinline="" poster="https://i.loli.net/2019/06/06/5cf8c5d9c57b510947.png" crossorigin="anonymous" preload="auto" src="https://api.dogecloud.com/player/get.mp4?vcode=5ac682e6f8231991&amp;userId=17&amp;ext=.mp4" __idm_id__="478951426" data-vscid="epuwcmxq2">
    <track kind="metadata" default="" src="https://cn-south-17-dplayer-49648867.oss.dogecdn.com/hikarunara.vtt">
</video>




<div id="player"></div>
<script type="text/javascript" src="https://player.dogecloud.com/js/loader"></script>
<script type="text/javascript">
var player = new DogePlayer({
    container: document.getElementById('player'),
    userId: 914,
    vcode: '9dbfeac71787bfbb',
    autoPlay: false
});
</script>





<iframe id="dogePlayerFrame" src="https://player.dogecloud.com/web/player.html?vcode=9dbfeac71787bfbb&userId=914&autoPlay=false&inFrame=true" allowfullscreen="true" msallowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" oallowfullscreen="true" allowtransparency="true" scrolling="no" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture; fullscreen" referrerPolicy="unsafe-url"></iframe>
------




<video class="dplayer-video dplayer-video-current" webkit-playsinline="" playsinline="" poster="https://i.loli.net/2019/06/06/5cf8c5d9c57b510947.png" crossorigin="anonymous" preload="auto" src="https://api.dogecloud.com/player/get.mp4?vcode=9dbfeac71787bfbb&amp;userId=914&amp;ext=.mp4" __idm_id__="478951426" data-vscid="epuwcmxq2">
    <track kind="metadata" default="" src="https://cn-south-17-dplayer-49648867.oss.dogecdn.com/hikarunara.vtt">
</video>

##### 声之形

<video class="dplayer-video dplayer-video-current" webkit-playsinline="" playsinline="" poster="https://i.loli.net/2019/06/06/5cf8c5d9c57b510947.png" crossorigin="anonymous" preload="auto" src="https://res.cloudinary.com/dnbpsjtyx/video/upload/v1579440834/%E6%88%91%E7%9A%84%E8%A7%86%E9%A2%91/%E5%A3%B0%E4%B9%8B%E5%BD%A2_wjg3sn.mp4" __idm_id__="478951426" data-vscid="epuwcmxq2">
    <track kind="metadata" default="" src="https://cn-south-17-dplayer-49648867.oss.dogecdn.com/hikarunara.vt">
</video>

























## [插件使用方法：](https://github.com/MoePlayer/hexo-tag-dplayer)

### 用法

```
{% dplayer key=value ... %}
```



```
dplayer options:
    'autoplay', 'loop', 'screenshot', 'hotkey', 'mutex', 'dmunlimited' : bool options, use "yes" "y" "true" "1" "on" or just without value to enable
    'preload', 'theme', 'lang', 'logo', 'url', 'pic', 'thumbnails', 'vidtype', 'suburl', 'subtype', 'subbottom', 'subcolor', 'subcolor', 'id', 'api', 'token', 'addition', 'dmuser' : string arguments
    'volume', 'maximum' : number arguments
container options:
    'width', 'height' : string, used in container element style
other:
    'code' : value of this key will be append to script tag
```

示例：

```
{% dplayer "url=https://moeplayer.b0.upaiyun.com/dplayer/hikarunara.mp4" "addition=https://dplayer.daoapp.io/bilibili?aid=4157142" "api=https://api.prprpr.me/dplayer/" "pic=https://moeplayer.b0.upaiyun.com/dplayer/hikarunara.jpg" "id=9E2E3368B56CDBB4" "loop=yes" "theme=#FADFA3" "autoplay=false" "token=tokendemo" %}
{% dplayer 'url=some.mp4' "id=someid" "api=https://api.prprpr.me/dplayer/" "addition=/some.json" 'code=player.on("loadstart",function(){console.log("loadstart")})' "autoplay" %} 
```