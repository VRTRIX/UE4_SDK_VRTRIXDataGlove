# 功能介绍 [English][english]

<p align="center">
  <img src="https://github.com/VRTRIX/VRTRIXGlove_Unity3D_SDK/blob/master/docs/img/digital_glove.jpg?raw=true"/>
</p>

VRTRIX 数据手套基于高精度惯性传感器，定位手指各关节和手腕动作与姿态。每只手套上分布有6个传感器，双手共12个，可以实时高精度低延迟输出全手所有关节的运动姿态。
VRTRIX 惯性传感器模块采用九轴传感器（3轴陀螺仪，3轴加速度计，3轴磁力计），精确高效的数据融合算法保证传感器以每秒400Hz的频率输出精确的姿态四元数，同时保证数据延迟低于5ms。VRTRIX数据手套还搭载无线传输功能，双手传感器数据可以通过手背上的无线发射模块实时发送给pc并进行渲染。无线传输采用2.4GHz专有协议，安全高效延迟不超过10ms。同时，系统进行了低功耗设计，数据手套不间断使用情况下的电池续航时间可以达到16小时以上。

# VRTRIXGlove_UE4_SDK

 该SDK是一个打包后的UE4引擎下的插件，该插件包含了所有开发需要用到的基本资源，开发者可以通过这个插件来进行Windows系统下基于UE4引擎的游戏或应用开发。
 该插件包含了一些基本功能模块，几个示例场景还有开发所需的一切蓝图。这将很好的帮助开发者上手并快速的在3D或VR环境下进行应用的开发。

**请前往我们github的[release页面][devsite]下载最新的稳定版本UE4插件。**

## 支持

- VRTRIXGlove_UE4_SDK 支持 UE4.16 或以上版本, Window 10 OS**

- 请注意由于我们不断在更新我们的插件，该github仓库中的内容可能包含有正在开发的模块代码，临时性的代码，或者一些已经废弃的接口，如果进行开发，请直接前往我们github的[release页面][devsite]下载最新的稳定版本UE4插件。

[devsite]: https://github.com/VRTRIX/UE4_SDK_VRTRIXDataGlove/releases "VRTRIX Glove UE4 Plugin Release site"
[english]: https://github.com/VRTRIX/UE4_SDK_VRTRIXDataGlove/blob/master/README.md "english"
