# CDN
This repo is basically used for holding the static files to be delivered aiming to speed up the visiting performance, by Alexander Ezharjan.

For example:
https://cdn.jsdelivr.net/gh/Ezharjan/cv/package.json

<br>
<br>
<br>

## 通过jsDelivr引用资源

## 使用方法：https://cdn.jsdelivr.net/gh/你的用户名/你的仓库名@发布的版本号/文件路径
例如：
```
    https://cdn.jsdelivr.net/gh/TRHX/CDN-for-itrhx.com@1.0/images/trhx.png
    https://cdn.jsdelivr.net/gh/TRHX/CDN-for-itrhx.com@2.0.1/css/style.css
    https://cdn.jsdelivr.net/gh/moezx/cdn@3.1.3//The%20Pet%20Girl%20of%20Sakurasou.mp4
```

_注意：版本号不是必需的，是为了区分新旧资源，如果不使用版本号，将会直接引用最新资源，除此之外还可以使用某个范围内的版本，查看所有资源等，具体使用方法如下：_

```
    // 加载任何Github发布、提交或分支
    https://cdn.jsdelivr.net/gh/user/repo@version/file

    // 加载 jQuery v3.2.1
    https://cdn.jsdelivr.net/gh/jquery/jquery@3.2.1/dist/jquery.min.js

    // 使用版本范围而不是特定版本
    https://cdn.jsdelivr.net/gh/jquery/jquery@3.2/dist/jquery.min.js
    https://cdn.jsdelivr.net/gh/jquery/jquery@3/dist/jquery.min.js

    // 完全省略该版本以获取最新版本
    https://cdn.jsdelivr.net/gh/jquery/jquery/dist/jquery.min.js

    // 将“.min”添加到任何JS/CSS文件中以获取缩小版本，如果不存在，将为会自动生成
    https://cdn.jsdelivr.net/gh/jquery/jquery@3.2.1/src/core.min.js

    // 在末尾添加 / 以获取资源目录列表
    https://cdn.jsdelivr.net/gh/jquery/jquery/
    
```
