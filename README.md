# 网易云音乐 2
和旧版本相比，本插件不再是单纯的歌单插件，支持在博客文章中添加音乐。

## 插件介绍

音乐mp3文件和图片文件都调用网易的资源，不会占用网站流量。

插件静态文件均做了按需加载，不会影响网站加载速度。

## 使用方法

### 在文章中插入音乐

直接在文章中插入歌曲、歌单、专辑地址即可。地址要单独一行，否则不会被解析。

#### 单曲

```
http://music.163.com/#/song?id=28605055
```

#### 专辑
```
http://music.163.com/#/album?id=2440003
```
#### 歌单
```
http://music.163.com/#/playlist?id=135451308
```
#### 电台
```
http://music.163.com/#/program?id=16299155
```

### 调用私人歌单页面

+ 新建页面，使用`[nm]`短代码
+ 插件设置页面直接选择页面
+ 在你想调用的地方直接调用函数`neteasemusic()`

## 更新日志

### 2.0.0

+ beta 版本发布