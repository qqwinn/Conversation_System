## Conversation_System：会话管理系统


#### 功能介绍：

    针对谈话场景，完成多路视频与声音的采集，实时播放封装与存储。

#### 开发环境：

    Windows、VS2013、OpenCV、FFmpeg 

#### 文件介绍：

    Queue.h、Queue.cpp：队列函数的实现；

    FFmpeg_Capture.h、FFmpeg_Capture.cpp：FFmpeg采集网络摄像头；

    Output_Play.h、Output_Play.cpp：打开多路摄像头，合并在同一图片上显示，并能根据鼠标事件切换画面；

    FFmpeg_Muxer.h、FFmpeg_Muxer.cpp：FFmpeg采集音频，并与合并后的画面实时封装，保存为MP4文件；

    video_parameter.ini：更改参数的配置文件；
