# 常用的三方库合集

**C++11的项目**

[fmt](https://github.com/fmtlib/fmt): 格式化库

[spdlog](https://github.com/gabime/spdlog): 日志库

[nlohmann/json](https://github.com/nlohmann/json): json库

[inifile](https://github.com/abin-z/IniFile): 现代的ini配置

[simpletimer](https://github.com/abin-z/SimpleTimer): 简单定时器

[filesystem](https://github.com/gulrak/filesystem): 文件系统, (C++17使用`std::filesystem`)

[serialport](https://github.com/abin-z/SerialPort): 串口通讯库

[asio](https://github.com/chriskohlhoff/asio): 网络通讯 tcp/udp/serialport/timer

[cpp-httplib](https://github.com/yhirose/cpp-httplib): 仅头文件的http服务端和客户端(小型/阻塞IO)

[websocketpp](https://github.com/zaphoyd/websocketpp): 仅头文件的websocket的服务端和客户端(依赖asio)

[CLI11](https://github.com/CLIUtils/CLI11): 命令行解析

[SQLiteCpp](https://github.com/SRombauts/SQLiteCpp): 一个轻量级的 **SQLite C++ 封装层**

[cppzmq](https://github.com/zeromq/cppzmq): zeromq消息队列

[protobuf](https://github.com/protocolbuffers/protobuf): 跨语言二进制序列化

[brpc](https://github.com/apache/brpc): 远程调用库

[Catch2](https://github.com/catchorg/Catch2): 简洁的单元测试框架

[libhv](https://github.com/ithewei/libhv): 比libevent/libuv/asio更易用的网络库, TCP/UDP/SSL/HTTP/WebSocket/MQTT client/server.



最常用库的`git submodule`指令:

```bash
# fmt
git submodule add https://github.com/fmtlib/fmt.git cpp11/fmt

# nlohmann/json
git submodule add https://github.com/nlohmann/json.git cpp11/json

# spdlog
git submodule add https://github.com/gabime/spdlog.git cpp11/spdlog

# asio（独立版，不依赖boost）
git submodule add https://github.com/chriskohlhoff/asio.git cpp11/asio

# filesystem（如果是C++11, 没有std::filesystem，可用 ghc 实现）
git submodule add https://github.com/gulrak/filesystem.git cpp11/filesystem

# SQLiteCpp
git submodule add https://github.com/SRombauts/SQLiteCpp.git cpp11/SQLiteCpp

# CLI11
git submodule add https://github.com/CLIUtils/CLI11.git cpp11/CLI11

# websocketpp
git submodule add https://github.com/zaphoyd/websocketpp.git cpp11/websocketpp

```

更新所有的`git submodule`指令

```bash
git submodule update --init --recursive
```



### **C++17常用的库**

[toml++](https://github.com/marzer/tomlplusplus): 现代化的tmol配置解析库

[range-v3](https://github.com/ericniebler/range-v3): 类似C++20的`std::ranges`

[sqlite_orm](https://github.com/fnc12/sqlite_orm): 一个 **SQLite 的 C++ ORM 框架**

[crow](https://github.com/CrowCpp/Crow): 轻量级http服务器

[drogon](): 功能全面的HTTP服务器和客户端



