<h1 align="center">仓颉三方库资源汇总</h1> 

##### 本文收集了一些已经发布在 Cangjie-TPC 组织上的三方组件资源，欢迎开发者参考和使用

## 目录

- [三方组件](#三方组件) 
    - [网络](#网络)
    - [数据库驱动](#数据库驱动)
    - [数据封装传递](#数据封装传递)
    - [数据解析](#数据解析)
    - [对象存储](#对象存储)
    - [分布式](#分布式)
    - [任务调度](#任务调度)
    - [安全类](#安全类)
    - [工具类](#工具类)
    - [日志类](#日志类)
    - [算法类](#算法类)
    - [音视频](#音视频)
    - [字符编码](#字符编码)
    - [图像处理](#图像处理)
    - [开发者类](#开发者类)
    - [动画类](#动画类)
    - [基础设施](#基础设施)
    
## <a name="三方组件"></a>三方组件

### <a name="网络"></a>网络

- [hyperion](https://gitcode.com/Cangjie-TPC/hyperion/overview) —— 仓颉语言实现的TCP通信框架，支持添加自定义编解码器，积木式添加IoFilter处理入栈出栈消息。仓颉redis-sdk和activemq4cj项目使用了该框架。感谢北京宝兰德软件股份有限公司中间件团队为仓颉编程语言TPC社区做出的贡献！
- [httpclient4cj](https://gitcode.com/Cangjie-TPC/httpclient4cj/overview) —— 一个高效的 HTTP 客户端。
- [rpc4cj](https://gitcode.com/Cangjie-TPC/rpc4cj/overview) —— 一个高性能、开源和通用的 RPC 框架，基于 ProtoBuf(Protocol Buffers) 序列化协议开发。
- [upload4cj](https://gitcode.com/Cangjie-TPC/upload4cj/overview) —— 一个文件上传库。
- [download4cj](https://gitcode.com/Cangjie-TPC/download4cj/overview) —— 一个文件下载库。

[返回目录](#目录)

### <a name="数据库驱动"></a>数据库驱动

- [redis-sdk](https://gitcode.com/Cangjie-TPC/redis-sdk/overview) —— 仓颉语言实现的Redis客户端SDK。接口设计兼容jedis接口语义，支持RESP2和RESP3协议，支持发布订阅模式，支持哨兵模式和集群模式。感谢北京宝兰德软件股份有限公司中间件团队为仓颉编程语言TPC社区做出的贡献！
- [opengauss-driver](https://gitcode.com/Cangjie-TPC/opengauss-driver/overview) —— 仓颉版本的openGauss数据库驱动。
- [kv4cj](https://gitcode.com/Cangjie-TPC/kv4cj/overview) —— 一个轻量级的键值存储库。
- [odbc4cj](https://gitcode.com/Cangjie-TPC/odbc4cj/overview) —— 一个开放数据库连接标准的实现库。
- [mysqlclient-ffi](https://gitcode.com/Cangjie-TPC/mysqlclient-ffi/overview) —— 仓颉版的 mysql 客户端。
- [dataORM4cj](https://gitcode.com/Cangjie-TPC/dataORM4cj/overview) —— 一个端侧的数据库 ORM 框架。

[返回目录](#目录)

### <a name="数据封装传递"></a>数据封装传递

- [lite-eventbus-cj](https://gitcode.com/Cangjie-TPC/lite-eventbus-cj/overview) —— 一款精简的发布/订阅事件总线框架

- [mqtt4cj](https://gitcode.com/Cangjie-TPC/mqtt4cj/overview) —— 一个 MQTT 消息队列遥测传输协议库。
- [eventbus4cj](https://gitcode.com/Cangjie-TPC/eventbus4cj/overview) —— 一款发布/订阅事件总线框架。

[返回目录](#目录)

### <a name="数据解析"></a>数据解析

- [xml-ffi](https://gitcode.com/Cangjie-TPC/xml-ffi/overview) —— 一个 XML 格式解析库。
- [protobuf4cj](https://gitcode.com/Cangjie-TPC/protobuf4cj/overview) —— 一个Protocol Buffers协议解析库
- [yaml4cj](https://gitcode.com/Cangjie-TPC/yaml4cj/overview) —— 一个 YAML 格式解析库。
- [html4cj](https://gitcode.com/Cangjie-TPC/html4cj/overview) —— 一个 HTML 格式解析库。
- [asnone4cj](https://gitcode.com/Cangjie-TPC/asnOne4cj/overview) —— 一个 ASN.1 标准库。
- [jwt4cj](https://gitcode.com/Cangjie-TPC/jwt4cj/overview) —— 一个用于生成和验证 JSON Web Token 的库。
- [toml4cj](https://gitcode.com/Cangjie-TPC/toml4cj/overview) —— 一个 TOML 格式解析库。
- [ini4cj](https://gitcode.com/Cangjie-TPC/ini4cj/overview) —— 一个 INI 格式解析库。
- [xml_stream](https://gitcode.com/Cangjie-TPC/xml_stream/overview) —— 一个xml序列化反序列化库

[返回目录](#目录)

### <a name="对象存储"></a>对象存储

- [OBS Cangjie SDK](https://gitcode.com/Cangjie-TPC/oss-sdk/overview) —— 仓颉语言实现的对象存储服务软件开发工具包（OBS SDK，Object Storage Service Software Development Kit）是对OBS服务提供的REST API进行的封装。感谢普元信息技术股份有限公司为仓颉编程语言TPC社区做出的贡献！
- [s3client4cj](https://gitcode.com/Cangjie-TPC/s3-sdk/overview) —— 仓颉语言实现的 AWS S3 的客户端。感谢普元信息技术股份有限公司为仓颉编程语言TPC社区做出的贡献！

[返回目录](#目录)

### <a name="分布式"></a>分布式

- [config-client](https://gitcode.com/Cangjie-TPC/config-client/overview) —— Config Client用于操作存储在Config Server中的配置内容。感谢普元信息技术股份有限公司为仓颉编程语言TPC社区做出的贡献！ 
- [config-server](https://gitcode.com/Cangjie-TPC/config-server/overview) —— Config Server是一个仓颉实现的可横向扩展、集中式的配置服务器，它用于集中管理应用程序各个环境下的配置。感谢普元信息技术股份有限公司为仓颉编程语言TPC社区做出的贡献！

[返回目录](#目录)

### <a name="任务调度"></a>任务调度

- [quartz4cj](https://gitcode.com/Cangjie-TPC/quartz4cj/overview) —— quartz4cj是一个功能丰富的开源作业调度库，可通过触发器设置作业定时运行规则，控制作业的运行时间。感谢上海赛可出行科技服务有限公司架构团队为仓颉编程语言TPC社区做出的贡献！

[返回目录](#目录)

### <a name="安全类"></a>安全类

- [crypto4cj](https://gitcode.com/Cangjie-TPC/crypto4cj/overview) —— 一个加解密库，提供常用的对称加密、非对称加密、哈希等算法。
- [oauth4cj](https://gitcode.com/Cangjie-TPC/oauth4cj/overview) —— 一个 Oauth 开放授权协议库，Open Authorization 的缩写。

- [pkcs4cj](https://gitcode.com/Cangjie-TPC/pkcs4cj/overview) —— 一个生成、解析 pkcs12 证书的库

[返回目录](#目录)

### <a name="工具类"></a>工具类

- [zip4cj](https://gitcode.com/Cangjie-TPC/zip4cj/overview) —— 一个用于创建和解压 ZIP 压缩格式的库。
- [zlib4cj](https://gitcode.com/Cangjie-TPC/zlib4cj/overview) —— 一个用于创建和解压 zlib 压缩格式的库。
- [phonenumber4cj](https://gitcode.com/Cangjie-TPC/phonenumber4cj/overview) —— 一个用于解析、格式化和验证国际电话号码的库。
- [bzip2-ffi](https://gitcode.com/Cangjie-TPC/bzip2-ffi/overview) —— 一个用于创建和解压 bzip2 压缩格式的库。
- [vcard4cj](https://gitcode.com/Cangjie-TPC/vcard4cj/overview) —— 一个电子名片标准格式（.vcf文件）解析库。
- [chardet4cj](https://gitcode.com/Cangjie-TPC/chardet4cj/overview) —— 一个用于检测常用文本编码的库。
- [uuid4cj](https://gitcode.com/Cangjie-TPC/uuid4cj/overview) —— 一个提供通用唯一标识符的库。
- [compress4cj](https://gitcode.com/Cangjie-TPC/compress4cj/overview) —— 一个用于处理多种压缩文件的库。
- [diffUtils4cj](https://gitcode.com/Cangjie-TPC/diffutils4cj/overview) —— 一个用于比较文本差异的库。
- [pinyin4cj](https://gitcode.com/Cangjie-TPC/pinyin4cj/overview) —— 一个用于将汉字转为拼音的库。

[返回目录](#目录)

### <a name="日志类"></a>日志类

- [log-cj](https://gitcode.com/Cangjie-TPC/log-cj/overview) —— 一款日志管理框架。

[返回目录](#目录)

### <a name="算法类"></a>算法类

- [ahocorasick4cj](https://gitcode.com/Cangjie-TPC/ahocorasick4cj/overview) —— 一个ahoCorasick字符串匹配算法库。
- [disklrucache4cj](https://gitcode.com/Cangjie-TPC/disklrucache4cj/overview) —— 一个diskLruCache算法库。
- [flexSearch4cj](https://gitcode.com/Cangjie-TPC/flexSearch4cj/overview) —— 一个快速、零依赖的全文搜索库。

[返回目录](#目录)

### <a name="音视频"></a>音视频

- [mp4parser4cj](https://gitcode.com/Cangjie-TPC/mp4parser4cj/overview) —— mp4 格式解析库。
- [mp3tag4cj](https://gitcode.com/Cangjie-TPC/mp3tag4cj/overview) —— 一个用于读取、创建、修改 MP3 标签信息的库。
- [ijkplayer-ffi](https://gitcode.com/Cangjie-TPC/ijkplayer-ffi/overview) —— ijkplayer 的仓颉封装。

[返回目录](#目录)

### <a name="字符编码"></a>字符编码

- [charset4cj](https://gitcode.com/Cangjie-TPC/charset4cj/overview) —— 常用的字符编码集合库。

[返回目录](#目录)

### <a name="图像处理"></a>图像处理

- [gifdrawable4cj](https://gitcode.com/Cangjie-TPC/gifdrawable4cj/overview) —— 一个 gif 图像加载库。
- [droplet](https://gitcode.com/Cangjie-TPC/droplet/overview) —— 一个图像加载库。
- [qrcode4cj](https://gitcode.com/Cangjie-TPC/qrcode4cj/overview) —— 一维码/二维码扫描库。

[返回目录](#目录)

### <a name="开发者类"></a>开发者类

- [prism4cj](https://gitcode.com/Cangjie-TPC/prism4cj/overview) —— 一个轻量的语法高亮库。
- [commonmark4cj](https://gitcode.com/Cangjie-TPC/commonmark4cj/overview) —— Markdown格式规范解析库。
- [formula-ffi](https://gitcode.com/Cangjie-TPC/formula-ffi/overview) —— 一个数学公式解析库。
- [markdown4cj](https://gitcode.com/Cangjie-TPC/markdown4cj/overview) —— 一个 Markdown 解析和展示库。

- [editor4cj](https://gitcode.com/Cangjie-TPC/editor4cj) —— 一个OHOS多语言代码编辑器。

[返回目录](#目录)

### <a name="动画类"></a>动画类

- [lottie4cj](https://gitcode.com/Cangjie-TPC/lottie4cj/overview) —— 一个基于 json 的动画库。
- [rebound4cj](https://gitcode.com/Cangjie-TPC/rebound4cj/overview) —— 一个模拟弹簧动力学的库。

[返回目录](#目录)

### <a name="基础设施"></a>基础设施

- [io4cj](https://gitcode.com/Cangjie-TPC/io4cj/overview) —— 一个 IO 处理库。

[返回目录](#目录)
