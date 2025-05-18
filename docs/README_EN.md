# Muilt Game Launch
One-stop fast game launcher and updater
Built with wails + Vue + Go, providing low resource usage and high-performance game update and launch 
ZH(https://github.com/mogumc/MGL/blob/main/README.md)|EN

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
- Multi-threaded update   
- Custom themes  
- Game time records  
- Add custom games  

## Find the Game Configurations You Need
You can write your own game configurations or use our preset configurations.  
For more details, visit[MGL_Res](https://github.com/mogumc/MGL_Res)  
We also welcome contributions to that repository.

## License
[MGL](https://github.com/mogumc/MGL) GPL-3.0 license  
[wails](https://github.com/wailsapp/wails)  MIT License  
[Vue3](https://github.com/vuejs/core) MIT License  
[Element-Plus](https://github.com/element-plus/element-plus) MIT License 