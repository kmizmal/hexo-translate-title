## hexo-translate-title

使用[libretranslate](https://github.com/LibreTranslate/LibreTranslate)将Hexo中的汉字标题转成英文标题，开箱即用，无需手工修改标题内容

### 安装
1. ***命令行安装***

在hexo项目目录执行
```bash
mkdir scripts
curl -O https://github.com/kmizmal/hexo-translate-title/releases/download/release/translate-title.js scripts/
```
2. ***手动安装***

在[Releases](https://github.com/kmizmal/hexo-translate-title/releases)下载translate-title.js之后手动扔到hexo项目目录下的scripts文件夹 ~~，如果没有就创建一个~~
### 配置（可选）

在`translate-title.js`的52行`translate_api_url`后填入你自己搭建的[libretranslate](https://github.com/LibreTranslate/LibreTranslate)接口

### 可能遇到的问题
# Front-Matter 误杀
在写这个脚本的时候*Front-Matter*多次抽风，~~气急败坏之下~~我直接引入了白名单，可以在脚本85行看到白名单列表

自己改看着 
~~或者提交issue~~



## DEMO
cloudflare page==> [zmalの折腾笔记](https://zmal.pages.dev/)

github pages==> [zmalの折腾笔记](https://kmizmal.github.io)
## License
MIT
