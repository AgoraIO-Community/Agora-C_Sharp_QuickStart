# Agora C# SDK

*[English](README.md) | 中文*

Windows [Agora RTC C# SDK](https://github.com/AgoraIO-Community/Agora-C_Sharp-SDK/tree/dev/3.4.6)配套的API example。

## 运行环境

- Visual Studio 2019+ with C++ (Windows)
- .NET

## 使用方法

1. Clone仓库

   ```bash
   git clone https://github.com/AgoraIO-Community/Agora-C_Sharp_QuickStart.git
   ```

2. 下载运行所需的SDK

	以Debug、X64为例。
	通过Visual Studio 2019打开 `Agora-C_Sharp_QuickStart/CSharp-API_Example/CSharp-API_Example.sln`解决方案，选择x64平台。

	在 [Agora Video SDK for Windows](https://download.agora.io/sdk/release/Agora_C_SHARP_SDK_3.4.6_Debug_100_20210926_0508.zip) 下载 SDK。解压到Agora-C_Sharp_QuickStart目录下：
![path_to_libs](CSharp-API_Example/res/img/path_to_libs.png)

3. 编译、运行  
   工程编译运行，在界面上填写App ID和[有效](https://docs.agora.io/cn/Video/API%20Reference/cpp/classagora_1_1rtc_1_1_i_rtc_engine.html#adc937172e59bd2695ea171553a88188c)的Channel ID（多个的话以半角的“;”分隔）后，点“更新Id”按钮保存，下次重启便无需再次输入。


*如您还未获取App ID，您可以查看附录。*

## 帮助

如您需要了解关于我们API的更多信息，请参考[Agora C++ API](https://docs.agora.io/cn/Video/API%20Reference/cpp/v3.5.0/index.html)。

*C# API文档还在推进中，但我们已有的C++ API是相似的。*

## 附录

### 创建Agora账户并获取App ID

如果想要使用我们的SDK，您需要先获得一个App ID：

1. 在[agora.io](https://dashboard.agora.io/signin/)中注册一个账号。当您完成注册后，您将被链接至控制台。
2. 在控制台左侧点击**Projects** > **Project List**。
3. 请将您从控制台中获取的App ID保存，您将会在运行示例时使用（示例图形化界面中有输入框）。