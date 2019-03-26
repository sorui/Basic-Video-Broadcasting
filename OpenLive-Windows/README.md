﻿# Open Live Windows

*其他语言版本： [简体中文](README.zh.md)*

The Open Live Windows Sample App is an open-source demo that will help you get live video chat integrated directly into your windows applications using the Agora Video SDK.

With this sample app, you can:

- Join / leave channel
- Set role as broadcaster or audience
- Mute / unmute audio
- Change camera
- Setup resolution, frame rate and bit rate

This demo is written in **C++**

A tutorial demo can be found here: [Agora-Windows-Tutorial-1to1](https://github.com/AgoraIO/Basic-Video-Call/tree/master/One-to-One-Video/Agora-Windows-Tutorial-1to1)

## Running the App
First, create a developer account at [Agora.io](https://dashboard.agora.io/signin/), and obtain an App ID. define the APP_ID with your App ID.

#define APP_ID _T("Your App ID")

If you don't want to modify the code part, you can create an AppId.ini file under Debug/Release. Modify the appId value to the App ID you just applied.

#[AppID]

#AppID=xxxxxxxxxxxxxxxxxxx

Next, download the **Agora Video SDK** from [Agora.io SDK](https://www.agora.io/en/download/). Unzip the downloaded SDK package and copy the **sdk** to the project folder(the old one may be over written).

Finally, Open OpenLive.sln with your VC++ 2013(or higher) and build all solution and run.

Note：
  1. After the program is compiled, if the program "xxx\xxx\xxx\Debug\Language\English.dll" cannot be started when running the program, 
      please select the OpenLive project in the Solution Explorer and right click. In the pop-up menu bar, select "Set as active project" to solve. Then run the program again.
      
  2. You may encounter crash when running this demo under debug mode. Please run this demo under release mode.
  
  3. The dll library under the sdk/dll file needs to be placed in the corresponding execution path.
  
  Tips: The relevant dll library has been configured for you in this case tutorial. If you want to use the interface provided by agora for related development, you need to put the dll library into the corresponding execution path as prompted above.
  
## Developer Environment Requirements
* VC++ 2013(or higher)
* Windows 7(or higher)

## Connect Us

- You can find full API document at [Document Center](https://docs.agora.io/en/)
- You can file bugs about this demo at [issue](https://github.com/AgoraIO/Basic-Video-Call/issues)

## License

The MIT License (MIT).
