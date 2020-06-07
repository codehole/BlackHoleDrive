# goIndex-theme-nexmoe

基于 [盘ta](https://github.com/Hidove/goindex) 的js,参考OneIndex的主题nexmoe,魔改美化.

apps.js 是基于[yanzai](https://github.com/yanzai/goindex)的js美化的，支持多盘、搜索、分页加载和调用外部播放器等功能，另外添加了DPlayer播放。

app.js 的模板为GoIndex.js


# 使用

1.打开 https://install.kenci.workers.dev/ 网站,验证并获取代码

2.使用对应app.js的模板代码，将获取到的id和授权填入

3.将代码部署到 [Cloudflare Workers](https://www.cloudflare.com/)

4.使用 https://cdn.jsdelivr.net/gh/codehole/BlackHoleDrive/app.js 替换获取代码中的js
> var html = `
> 
> ......
> <script src="替换"></script>
> 
> ......
> 
> `;

5.其中app.js有部分链接为外链，app.js的所有链接均连接仓库中的文件

6.apps.js地址：https://cdn.jsdelivr.net/gh/codehole/BlackHoleDrive/apps.js

# 预览
[apps.js](https://pan.nuocom.cn/) 
