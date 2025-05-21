<div align="center">
    <img src="./docs/icon.png" width="200">
    <h1>Muilt Game Launcher</h1>
</div>

<div align="center">
    <a href="https://dotnet.microsoft.com/zh-cn/download/dotnet/latest/runtime"><img alt="Windows" src="https://img.shields.io/badge/platform-Windows-blue?logo=windowsxp&style=flat-square&color=1E9BFA" /></a>
    <a href="https://github.com/mogumc/MGL/releases"><img alt="Release" src="https://img.shields.io/github/v/release/mogumc/MGL?logo=visualstudio&style=flat-square&color=1E9BFA"></a>
    <a href="./LICENSE">
        <img alt="GitHub" src="https://img.shields.io/github/license/mogumc/MGL"/>
    </a>
    <img src="https://komarev.com/ghpvc/?username=mogumc&label=Views&color=orange&style=flat" alt="访问量统计" />
    <h3>一站式游戏启动器</h3>
    <h3>使用wails+Vue+Go构建,提供低占用高性能游戏启动体验  </h3>
    
<strong>
<samp>

[English](./docs/README_EN.md) · [简体中文](README.md)

</samp>
</strong>
</div>

<br/>

## 开始
### A)自行编译

#### 依赖
- [Go(编译需要)](https://golang.google.cn/dl/)
- [npm(编译需要)](https://nodejs.org/zh-cn/download)
- [wails(编译需要)](https://wails.io/zh-Hans/docs/gettingstarted/installation/)
- [WebView2(程序需要)](https://developer.microsoft.com/microsoft-edge/webview2)

如果Windows版本低于Windows10 需要自行安装WebView2  

```
git clone https://github.com/mogumc/MGL.git
cd .\MGL\src
go env .
wails build
```

### B) 使用预编译版本

#### 依赖
- [WebView2(程序需要)](https://developer.microsoft.com/microsoft-edge/webview2)

如果Windows版本低于Windows10 需要自行安装WebView2  


访问我们的 [发布页](https://github.com/mogumc/MGL/releases) 页面并下载符合您系统的最新版本.  
您可以选择已经打包的安装程序或便携版本,启动安装目录下``MuiltGameLaunch.exe``运行程序.  

## 功能
- 自定义主题  
- 游戏时长记录
- 添加自定义游戏

## License
[MGL](https://github.com/mogumc/MGL) GPL-3.0 license  
[wails](https://github.com/wailsapp/wails)  MIT License  
[Vue3](https://github.com/vuejs/core) MIT License  
[Element-Plus](https://github.com/element-plus/element-plus) MIT License 




  
