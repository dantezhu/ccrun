### ccrun

在cocos2dx-lua工程的任何位置，只要执行 ccrun，会自动启动模拟器运行


#### 使用说明

1. 拷贝 ccrun 到 /usr/local/bin 目录下
2. 将 Simulator 添加到系统环境变量，比如mac下

    export PATH=/Applications/Cocos/cocos-simulator-bin/mac/Simulator.app/Contents/MacOS/:$PATH

#### 参数说明

支持透传参数如下:

    -workdir "PATH"
    -script "FILENAME"
    -package.path "PATH;PATH"
    -writable "PATH"
    -size 960x640
    -scale 1.0
    -console, -disable-console
    -load-framework, -disable-load-framework
    -write-debug-log, -disable-write-debug-log
    -offset {0,0}
    -debugger-ldt, -debugger-codeide, -disable-debugger
