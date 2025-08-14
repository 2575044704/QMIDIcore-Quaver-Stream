# QMIDIcore-Quaver-Stream
极简MIDI视频生成器(仅画面)
你可以使用gcc或clang轻松地完成编译:
clang++ -O3 -I. *.cpp -s -o QQS
本软件依赖ffmpeg完成视频编码(ffmpeg.org)
示例: ./QQS -mid=xxx.mid -vid=xxx.mp4
./QQS 可以获得完整的帮助信息！

```bash
git clone https://github.com/2575044704/QMIDIcore-Quaver-Stream
cd QMIDIcore-Quaver-Stream
apt install -y ffmpeg
g++ -O3 -I. *.cpp -o QQS
./QQS -mid=NECRO.mid -vid=NECRO.mp4 -codr=libx265 -ppb=1536 -wei=1920 -hei=1080 -keyh=110
```
```

 > > [ ©2019~2020 Qishipai MIDI Tech ] < <
*****内部优化测试版
用法:
        ./QQS <参数1> <参数2> ......
参数列表：
        -mid=  MIDI文件路径     (必须指定)
        -vid=  视频文件路径     (必须指定)
        -ppb=  每拍音符长度     (px)(默认520)
        -fps=  输出视频帧率     (默认60)
        -wei=  输出视频宽度     (默认1280)
        -hei=  输出视频高度     (默认720)
        -keyh= 键盘高度         (默认112)
        -fthr= ffmpeg滤镜线程数 (默认32)
        -codr= 编码器           (默认libx264)
声明:
        本软件完全免费！
        严禁任何个人或团体用于恰烂钱！

```
