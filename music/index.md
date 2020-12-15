---
title: music
date: 2020-01-29 17:23:54
keywords: 
type: "music"
layout: "music"
---

一起来听音乐吧！


{% aplayer "战歌" "DAISHI DANCE,Cecile Corbel" "caffeine.mp3" "https://www.yremp.live/images/2019/08/18/182655-15467704159d8c95195.jpg" %}



{% aplayer "亡灵曲" "J.Fla" "https://www.yremp.live/images/2019/08/18/182938-1524911378cd79dc26e.jpg" "picture.jpg" %}

{% aplayer "你怎麼說" "Jay && 邓丽君" "http://fs.open.kugou.com/15ad66aa2470482df1919a5538a6c663/5c1eea95/G008/M04/0B/05/qIYBAFUGzV-ADtHPAExveQ6d2Rs873.mp3" "autoplay" %}


{% aplayerlrc "你怎麼說" "Jay && 邓丽君" "http://fs.open.kugou.com/15ad66aa2470482df1919a5538a6c663/5c1eea95/G008/M04/0B/05/qIYBAFUGzV-ADtHPAExveQ6d2Rs873.mp3" "autoplay" %}
[00:04.76]你怎么说[00:26.31]我没忘记你忘记我[00:32.53]连名字你都说错[00:50.51]你说过两天来看我[00:56.04]一走就是一年多[01:01.36]三百六十五个日子不好过[01:07.93]你心里根本没有我[01:14.37]把我的爱情还给我[01:43.60]我没忘记你忘记我[01:49.80]连名字你都说错[01:55.97]证明你一切都是在骗我[02:01.95]看今天你怎么说[02:07.16]你说过两天来看我[02:13.20]一等就是一年多[02:18.26]三百六十五个日子不好过[02:25.22]你心里根本没有我[02:31.43]把我的爱情还给我[02:36.75]红尘客栈[02:39.13]天涯的尽头是风沙[02:44.59]红尘的故事叫牵挂[02:50.01]封刀隐没在寻常人家东篱下[02:55.53]闲云野鹤古剎[03:03.19]快马在江湖里厮杀[03:08.92]无非是名跟利放不下[03:14.01]心中有江山的人岂能快意潇洒[03:19.91]我只求与你共华发[03:27.01]剑出鞘 恩怨了 谁笑[03:31.61]我只求今朝拥你入怀抱[03:37.02]红尘客栈风似刀[03:41.08]骤雨落宿命敲[03:46.26]任武林谁领风骚我却[03:49.76]只为你折腰[03:52.82]你回眸多娇我泪中带笑[03:58.36]酒招旗风中萧萧[04:02.41]剑出鞘恩怨了[04:08.58]千里之外[04:13.09]我送你离开千里之外[04:17.64]你无声黑白[04:21.62]沉默年代或许不该[04:25.62]太遥远的相爱[04:29.59]我送你离开天涯之外[04:33.79]你是否还在[04:37.85]琴声何来生死难猜[04:41.90]用一生去等待
{% endaplayerlrc %}




{% aplayerlist %}
{
    "mode": "random",                  
    "showlrc": 3,                             // （可选）歌词显示配置项，可选项有：1,2,3
    "mutex": true,                            
    "theme": "#e6d0b2",	                      // （可选）播放器风格色彩设置，默认：#b7daff
    "preload": "metadata",                    // （可选）音乐文件预载入模式，可选项： 'none' 'metadata' 'auto', 默认: 'auto'
    "listmaxheight": "513px",                 // (可选) 该播放列表的最大长度
    "music": [
        {
            "title": "CoCo",
            "author": "Jeff Williams",
            "url": "http://music.dream18.xyz/23849575_epic-cinematic-inspirational_by_artsound_preview.mp3",
            "pic": "https://i.loli.net/2020/02/21/94ZoQpfDRWiCVAM.jpg",
        },
        {
            "title": "アイロニ",
            "author": "鹿乃",
            "url": "http://music.dream18.xyz/LEVEL5-judgelight-%20-%20fripSide.mp3",
            "pic": "https://i.loli.net/2020/02/21/3tHiOpBVmfzKRuP.jpg"
        }
    ]
}
{% endaplayerlist %}



------

{% cplayer autoplay %}
- name: チルドレンレコード # 名字
  artist: 96猫,伊東歌詞太郎 # 艺术家
  poster: https://cplayer.js.org/801422833716a4f0f96ff6dff1f77dfe.jpg # 音乐海报
  src: https://cplayer.js.org/8af423669c27d265bb129d04a927044f.mp3 # 音乐资源链接
- 27955597 # 网易云音乐 ID
{% endcplayer %}



## [插件使用方法:](https://github.com/MoePlayer/hexo-tag-aplayer/blob/master/docs/README-zh_cn.md)



简单示例：

```
{% aplayer "Caffeine" "Jeff Williams" "caffeine.mp3" "picture.jpg" "lrc:caffeine.txt" %}
```



```
{% aplayer title author url [picture_url, narrow, autoplay, width:xxx, lrc:xxx] %}
```

### 标签参数

- `title` : 曲目标题
- `author`: 曲目作者
- `url`: 音乐文件 URL 地址
- `picture_url`: (可选) 音乐对应的图片地址
- `narrow`: （可选）播放器袖珍风格
- `autoplay`: (可选) 自动播放，移动端浏览器暂时不支持此功能
- `width:xxx`: (可选) 播放器宽度 (默认: 100%)
- `lrc:xxx`: （可选）歌词文件 URL 地址

当开启 Hexo 的 [文章资源文件夹](https://hexo.io/zh-cn/docs/asset-folders.html#文章资源文件夹) 功能时，可以将图片、音乐文件、歌词文件放入与文章对应的资源文件夹中，然后直接引用：

### 播放列表

```
{% aplayerlist %}
{
    "narrow": false,                          // （可选）播放器袖珍风格
    "autoplay": true,                         // （可选) 自动播放，移动端浏览器暂时不支持此功能
    "mode": "random",                         // （可选）曲目循环类型，有 'random'（随机播放）, 'single' (单曲播放), 'circulation' (循环播放), 'order' (列表播放)， 默认：'circulation' 
    "showlrc": 3,                             // （可选）歌词显示配置项，可选项有：1,2,3
    "mutex": true,                            // （可选）该选项开启时，如果同页面有其他 aplayer 播放，该播放器会暂停
    "theme": "#e6d0b2",	                      // （可选）播放器风格色彩设置，默认：#b7daff
    "preload": "metadata",                    // （可选）音乐文件预载入模式，可选项： 'none' 'metadata' 'auto', 默认: 'auto'
    "listmaxheight": "513px",                 // (可选) 该播放列表的最大长度
    "music": [
        {
            "title": "CoCo",
            "author": "Jeff Williams",
            "url": "caffeine.mp3",
            "pic": "caffeine.jpeg",
            "lrc": "caffeine.txt"
        },
        {
            "title": "アイロニ",
            "author": "鹿乃",
            "url": "irony.mp3",
            "pic": "irony.jpg"
        }
    ]
}
{% endaplayerlist %}
```

### 外接播放器：

```
<!-- 简单示例 (id, server, type)  -->
{% meting "60198" "netease" "playlist" %}

<!-- 进阶示例 -->
{% meting "60198" "netease" "playlist" "autoplay" "mutex:false" "listmaxheight:340px" "preload:none" "theme:#ad7a86"%}
```



`{% meting %}` 的选项列表如下:

| 选项          | 默认值     | 描述                                                        |
| ------------- | ---------- | ----------------------------------------------------------- |
| id            | **必须值** | 歌曲 id / 播放列表 id / 相册 id / 搜索关键字                |
| server        | **必须值** | 音乐平台: `netease`, `tencent`, `kugou`, `xiami`, `baidu`   |
| type          | **必须值** | `song`, `playlist`, `album`, `search`, `artist`             |
| fixed         | `false`    | 开启固定模式                                                |
| mini          | `false`    | 开启迷你模式                                                |
| loop          | `all`      | 列表循环模式：`all`, `one`,`none`                           |
| order         | `list`     | 列表播放模式： `list`, `random`                             |
| volume        | 0.7        | 播放器音量                                                  |
| lrctype       | 0          | 歌词格式类型                                                |
| listfolded    | `false`    | 指定音乐播放列表是否折叠                                    |
| storagename   | `metingjs` | LocalStorage 中存储播放器设定的键名                         |
| autoplay      | `true`     | 自动播放，移动端浏览器暂时不支持此功能                      |
| mutex         | `true`     | 该选项开启时，如果同页面有其他 aplayer 播放，该播放器会暂停 |
| listmaxheight | `340px`    | 播放列表的最大长度                                          |
| preload       | `auto`     | 音乐文件预载入模式，可选项： `none`, `metadata`, `auto`     |
| theme         | `#ad7a86`  | 播放器风格色彩设置                                          |



## 自定义配置（3.0 新功能）

现在你可以在 Hexo 配置文件 `_config.yml` 中配置本插件：

```
aplayer:
  script_dir: some/place                        # Public 目录下脚本目录路径，默认: 'assets/js'
  style_dir: some/place                         # Public 目录下样式目录路径，默认: 'assets/css'
  cdn: http://xxx/aplayer.min.js                # 引用 APlayer.js 外部 CDN 地址 (默认不开启)
  style_cdn: http://xxx/aplayer.min.css         # 引用 APlayer.css 外部 CDN 地址 (默认不开启)
  meting: true                                  # MetingJS 支持
  meting_api: http://xxx/api.php                # 自定义 Meting API 地址
  meting_cdn: http://xxx/Meing.min.js           # 引用 Meting.js 外部 CDN 地址 (默认不开启)
  asset_inject: true                            # 自动插入 Aplayer.js 与 Meting.js 资源脚本, 默认开启
  externalLink: http://xxx/aplayer.min.js       # 老版本参数，功能与参数 cdn 相同
```

## [另一个插件的使用：](https://github.com/EYHN/hexo-tag-cplayer/blob/master/readme-zh-CN.md)

```
{% cplayer [autoplay] [yaml|cson|json] %}
# type your config here
{% endcplayer %}
```

### 示例：

[YAML](https://github.com/yaml/yaml):

```
{% cplayer autoplay %}
- name: チルドレンレコード # 名字
  artist: 96猫,伊東歌詞太郎 # 艺术家
  poster: https://cplayer.js.org/801422833716a4f0f96ff6dff1f77dfe.jpg # 音乐海报
  src: https://cplayer.js.org/8af423669c27d265bb129d04a927044f.mp3 # 音乐资源链接
- 27955597 # 网易云音乐 ID
{% endcplayer %}
```

[CSON](https://github.com/bevry/cson):

```
{% cplayer autoplay cson %}
[
  {
    name: "チルドレンレコード"
    artist: "96猫,伊東歌詞太郎"
    poster:"https://cplayer.js.org/801422833716a4f0f96ff6dff1f77dfe.jpg"
    src:"https://cplayer.js.org/8af423669c27d265bb129d04a927044f.mp3"
  }
  27955597
]
{% endcplayer %}
```



[JSON](http://www.json.org/):

```
{% cplayer autoplay json %}
[
  {
    "name": "チルドレンレコード",
    "artist": "96猫,伊東歌詞太郎",
    "poster":"https://cplayer.js.org/801422833716a4f0f96ff6dff1f77dfe.jpg",
    "src":"https://cplayer.js.org/8af423669c27d265bb129d04a927044f.mp3"
  },
  27955597
]
{% endcplayer %}
```



## 参考链接：

1. [APlayer](https://github.com/MoePlayer/hexo-tag-aplayer/blob/master/docs/README-zh_cn.md)
2. [metingJS](https://github.com/MoePlayer/hexo-tag-aplayer/blob/master/docs/README-zh_cn.md#meingjs-支持-30-新功能)
3. [音乐直链服务](https://music.liuzhijin.cn/)



