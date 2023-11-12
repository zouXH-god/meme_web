# meme-web
## 本项目基于 MeetWq/meme-generator 的web端实现，原仓库地址：https://github.com/MeetWq/meme-generator

## 安装
克隆当前仓库：

```bash
git clone https://github.com/zouXH-god/meme_web.git
```

通过 `python -m meme_generator.app` 运行 web 服务器


### 字体安装

为确保表情包中的文字生成正常，需要自行安装字体

> **Note**
>
> 字体安装后若文字仍显示不正常，可删掉 `matplotlib` 字体缓存文件重新运行程序
>
> 缓存文件位置：
> - Windows: `C:\Users\<username>\.matplotlib\fontlist-xxx.json`
> - Linux: `~/.cache/matplotlib/fontlist-xxx.json`
> - Mac: `~/Library/Caches/matplotlib/fontlist-xxx.json`
