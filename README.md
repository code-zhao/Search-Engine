# 搜索引擎
## 结构

### offline

* dict 文件夹中存放 cppjieba 自带的分词库
* include 和 src 文件夹存放所有的源码与需要的头文件
* rss文件夹存放的是语料
* data文件夹中存放倒排序库、网页库、网页偏移库，pagelib 对应的是生成的网页库所存放的路径
  offsetlib 对应的是相应的网页库中每篇网页在网页库中的起始位置和长度
* conf 文件夹中存放配置文件

### online

* 运行 make 命令后，生成的 exe文件存放于 bin 文件夹中
* client.c编译后是一个简单的客户端程序
* php前端客户端（两个客户端均可使用，任选其一）
* data文件夹中存放倒排序库、网页库、网页偏移库
* conf 文件夹中存放配置文件

## 需要安装的库

json、scons、php、boost# User-input-assistant
