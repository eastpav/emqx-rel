
# Modify
使用私有emqtt仓库编译EMQ，增加emqtt命令检测节点的集群状态

emq-relx
========

The Release Project for the *EMQ* Broker.

NOTICE: Requires Erlang/OTP R19.3+ to build since EMQ 2.2-rc.2.

Build on Linux/Unix/Mac
-----------------------

```
git clone https://github.com/emqtt/emq-relx.git
cd emq-relx && make
cd _rel/emqttd && ./bin/emqttd console
```

Build Docker Image
------------------

```
git clone https://github.com/emqtt/emq_docker.git
cd emq_docker && docker build -t emq:latest .
```

Build on Windows
----------------

Install Erlang/OTP-R18.3 and MSYS2-x86_64 for erlang.mk:

```
https://erlang.mk/guide/installation.html#_on_windows
```

Clone and build the EMQ broker with erlang.mk:

```
git clone https://github.com/emqtt/emq-relx.git
cd emq-relx
make
cd _rel\emqttd
bin\emqttd console
```

License
-------

Apache License Version 2.0

