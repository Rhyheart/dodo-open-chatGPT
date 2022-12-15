
<p align="center">
  <a href="https://open.imdodo.com">
    <img src="https://avatars.githubusercontent.com/u/96616694" width="200" height="200" alt="dodo-open">
  </a>
</p>

<div align="center">

  # dodo-open-chatGPT

  _✨ 基于最新 C# .NET 6 开发，支持Windows、MacOS、Linux、Docker，完美跨平台。 ✨_

  <a href="https://github.com/Rhyheart/dodo-open-chatGPT/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/Rhyheart/dodo-open-chatGPT" alt="license">
  </a>
  <a href="https://github.com/Rhyheart/dodo-open-chatGPT/releases">
    <img src="https://img.shields.io/github/v/release/Rhyheart/dodo-open-chatGPT?color=blueviolet&include_prereleases"
      alt="release">
  </a>

</div>


## 项目介绍

本项目包含了DoDo版ChatGPT智能AI交互机器人，基于DoDo开放平台官方 [.Net SDK](https://github.com/dodo-open/dodo-open-net)

本项目的ChatGPT最大支持30条历史会话，支持消息Token数动态调整，防止Token数超限报错

## 开发工具

[Visual Studio 2022](https://visualstudio.microsoft.com/zh-hans/vs/)

安装时，请勾选ASP.NET和Web开发组件，其他组件按需安装


## 执行程序

对于不具有开发能力的普通用户，本项目提供了编译完成的Windows执行程序，可以从 [Release](https://github.com/Rhyheart/dodo-open-chatGPT/releases) 中进行下载，本执行程序依赖.Net 6运行环境，因此您需要先下载安装 [dotnet-runtime-6.0.6-win-x64.exe](https://download.visualstudio.microsoft.com/download/pr/7989338b-8ae9-4a5d-8425-020148016812/c26361fde7f706279265a505b4d1d93a/dotnet-runtime-6.0.6-win-x64.exe) 到您的电脑中！


## PDF教程（一定要下载查看！！！）

[PDF教程](https://files.imdodo.com/dodo/9478f25d3dd0c3e316ef3c554e5b2437.pdf)


## 使用步骤

1、[创建DoDo机器人](https://open.imdodo.com/go/introduction/deployment.html)

2、将机器人拉入测试群

3、下载安装依赖环境 [dotnet-runtime-6.0.6-win-x64.exe](https://download.visualstudio.microsoft.com/download/pr/7989338b-8ae9-4a5d-8425-020148016812/c26361fde7f706279265a505b4d1d93a/dotnet-runtime-6.0.6-win-x64.exe)

3、下载解压执行程序 [Release](https://github.com/Rhyheart/dodo-open-chatGPT/releases)

4、维护 [配置文件](https://github.com/Rhyheart/dodo-open-chatGPT/blob/main/src/DoDo.Open.ChatGPT/appsettings.json)

5、启动程序

6、测试群内艾特机器人发送`你是谁`指令即可
