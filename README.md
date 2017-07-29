# WebBench
网站测压工具

Webbench工具是通过fork()进程，并行执行子进程，子进程通过socket连接服务器，之后发送request，记录信息。

子进程记录的信息，通过管程，发送到父进程，父进程计算并打印信息。

最多可以并发三万个子进程。

[相关知识](https://nielaishan.github.io/2017/07/24/Webbench/).