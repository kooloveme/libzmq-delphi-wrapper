libzmq-3.1.1.dll

---

ZeroMQ 3.1.1 最新版, VC2008编译生成.

libzmq.pas :

---

翻译 zmq.h + zmq\_utils.h 头文件，包含libzmq-3.1.1.dll 全部输出函数

ZeroMQ.pas :

---

对 libzmq.pas 的简单封装，针对 zmq\_send 和 zmq\_recv 两个函数，提供delphi AnsiString风格的接口

zmq\_test.dpr, client.dpr

---

两个简单的 请求-响应 类型的测试程序工程，zmq\_test是服务器，client是客户端

pub\_test.dpr, sub\_test.dpr

---

两个简单的 订阅-发布 类型的测试程序工程，分别是服务器/客户端