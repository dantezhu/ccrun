### ccrun

在cocos2dx-lua工程的任何位置，只要执行 ccrun，会自动启动模拟器运行


#### 使用说明

1. 拷贝 ccrun 到 /usr/local/bin 目录下
2. 将 Simulator 添加到系统环境变量，比如mac下

    export PATH=/Applications/Cocos/cocos-simulator-bin/mac/Simulator.app/Contents/MacOS/:$PATH

#### 参数说明

支持透传参数如下:

    -workdir "path"
    -entry "filename"
    -writable-path "path"
    -resolution 960x640
    -scale 1.0
    -console enable/disable 如果disable, 日志会打印到标准输出，所以可以通过输出重定向打印到文件里面去的。无论是windows还是mac。
    -write-debug-log "log_path"
    -position 0,0
    -debugger codeide/studio
    -search-path "path;path"
    -listen "bind_address"

