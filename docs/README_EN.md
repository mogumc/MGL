<div align="center">
    <img src="../docs/icon.png" width="200">
    <h1>Muilt Game Launcher</h1>
</div>

<div align="center">
  <a href="https://dotnet.microsoft.com/zh-cn/download/dotnet/latest/runtime"><img alt="Windows" src="https://img.shields.io/badge/platform-Windows-blue?logo=windowsxp&style=flat-square&color=1E9BFA" /></a>
  <a href="https://github.com/mogumc/MGL/releases"><img alt="Release" src="https://img.shields.io/github/v/release/mogumc/MGL?logo=visualstudio&style=flat-square&color=1E9BFA"></a>
      <a href="../LICENSE">
        <img alt="GitHub" src="https://img.shields.io/github/license/mogumc/MGL"/>
    </a>
    <img src="https://komarev.com/ghpvc/?username=mogumc&label=Views&color=orange&style=flat" alt="Visitor statistics" />
    <h3>One-stop game launcher</h3>
    <h3>Built with wails2 + Vue3 + Go, a low resource usage and high-performance game launcher</h3>
    
<strong>
<samp>

[English](README_EN.md) · [简体中文](../README.md)

</samp>
</strong>
</div>

<br/>

## Getting Started  
### A) Compile it yourself

#### Dependencies  
- [Go (required for compiling)](https://golang.google.cn/dl/)  
- [npm (required for compiling)](https://nodejs.org/en/download)  
- [wails (required for compiling)](https://wails.io/docs/gettingstarted/installation/)  
- [WebView2 (required for running the app)](https://developer.microsoft.com/microsoft-edge/webview2)  

If your Windows version is below Windows 10, you need to install WebView2 manually.

```bash
git clone https://github.com/mogumc/MGL.git
cd ./MGL/src
go env .
wails build
```

### B) Use Precompiled Version

#### Dependencies
- [WebView2 (required for running the app)](https://developer.microsoft.com/microsoft-edge/webview2) 

If your Windows version is below Windows 10, you need to install WebView2 manually.

Visit our [releases](https://github.com/mogumc/MGL/releases) page and download the latest version suitable for your system.  
You can choose either the packaged installer or the portable version. Run ``MuiltGameLaunch.exe`` in the installation directory to start the program.

## Features
- Custom themes  
- Game time records  
- Add custom games  

## License
[MGL](https://github.com/mogumc/MGL) GPL-3.0 license  
[wails](https://github.com/wailsapp/wails)  MIT License  
[Vue3](https://github.com/vuejs/core) MIT License  
[Element-Plus](https://github.com/element-plus/element-plus) MIT License 
