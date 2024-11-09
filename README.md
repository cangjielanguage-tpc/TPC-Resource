<h1 align="center">仓颉三方库资源汇总</h1> 

##### 本文收集了一些已经发布在 Cangjie-TPC 组织上的三方组件资源，欢迎开发者参考和使用

## 目录

- [三方组件](#三方组件) 
    - [网络](#网络)
    - [数据库驱动](#数据库驱动)
    - [数据封装传递](#数据封装传递)
    - [数据解析](#数据解析)
    - [数据库框架](#数据库框架)
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
    - [地理信息](#地理信息)
    - [UI类](#ui类)
    - [科学计算](#科学计算)
    
## <a name="三方组件"></a>三方组件

### <a name="网络"></a>网络

- [hyperion](https://gitcode.com/Cangjie-TPC/hyperion/overview) —— 仓颉语言实现的 TCP 通信框架，支持添加自定义编解码器，积木式添加 IoFilter 处理入栈出栈消息。仓颉 redis-sdk 和 activemq4cj 项目使用了该框架。感谢北京宝兰德软件股份有限公司中间件团队为仓颉编程语言 TPC 社区做出的贡献！
- [httpclient4cj](https://gitcode.com/Cangjie-TPC/httpclient4cj/overview) —— 高效的 HTTP 客户端，支持 HTTP/2，允许所有同一个主机地址的请求共享同一个 socket 连接，支持连接池减少请求延时，支持缓存响应内容，避免一些完全重复的请求。
- [rpc4cj](https://gitcode.com/Cangjie-TPC/rpc4cj/overview) —— 高性能、开源和通用的 RPC 框架，基于 ProtoBuf(Protocol Buffers) 序列化协议开发，并且支持众多开发语言。面向服务端和移动端，基于 HTTP/2 设计，带来诸如双向流、流控、头部压缩、单 TCP 连接上的多复用请求等特。这些特性使得其在移动设备上表现更好，更省电和节省空间占用。
- [upload4cj](https://gitcode.com/Cangjie-TPC/upload4cj/overview) —— 用于处理浏览器或者其他客户端上传上来的单个或者多个文件的报文解析库。
- [download4cj](https://gitcode.com/Cangjie-TPC/download4cj/overview) —— 文件下载库，提供同步下载、异步下载、暂停任务。

[返回目录](#目录)

### <a name="数据库驱动"></a>数据库驱动

- [redis-sdk](https://gitcode.com/Cangjie-TPC/redis-sdk/overview) —— 仓颉语言实现的 Redis 客户端 SDK。接口设计兼容 Jedis 接口语义，支持 RESP2 和 RESP3 协议，支持发布订阅模式，支持哨兵模式和集群模式。感谢北京宝兰德软件股份有限公司中间件团队为仓颉编程语言 TPC 社区做出的贡献！
- [opengauss-driver](https://gitcode.com/Cangjie-TPC/opengauss-driver/overview) —— openGauss 和 PostgreSQL 数据库驱动，包括前后端通信协议模块 Proto3、前后端连接管理模块 Pgconn、驱动接口实现模块 Driver、简单数据库连接池模块 Sqlpool。
- [kv4cj](https://gitcode.com/Cangjie-TPC/kv4cj/overview) —— 基于 mmap 的高性能 key-value 存储库，主要用于解决 SharedPreferences 存储性能和容量受限的问题。
- [odbc4cj](https://gitcode.com/Cangjie-TPC/odbc4cj/overview) —— 开放数据库互连，用于访问数据库的标准 API，允许应用程序通过一个标准的接口访问不同的数据库管理系统。
- [mysqlclient-ffi](https://gitcode.com/Cangjie-TPC/mysqlclient-ffi/overview) —— mysql 客户端，可以执行各种数据库操作，包括连接数据库、创建表、插入数据、查询数据、更新数据等。

[返回目录](#目录)

### <a name="数据封装传递"></a>数据封装传递

- [lite-eventbus-cj](https://gitcode.com/Cangjie-TPC/lite-eventbus-cj/overview) —— 精简的发布/订阅事件总线框架，将事件的接受者和发送者分开，简化了组件之间的通信，使用简单，效率高，体积小。
- [mqtt4cj](https://gitcode.com/Cangjie-TPC/mqtt4cj/overview) —— MQTT 消息队列遥测传输协议库，是一种基于发布/订阅（publish/subscribe）模式的"轻量级"通讯协议，该协议构建于 TCP/IP 协议上。支持 TCP/TLS/WS/WSS 方式连接消息服务端、支持 MQTTv3 协议连接消息服务端、持 MQTT 主题订阅发布。
- [eventbus4cj](https://gitcode.com/Cangjie-TPC/eventbus4cj/overview) —— 发布/订阅事件总线框架，主要功能是替代 Intent、Handler、BroadCast 在 Activity、Fragment、Service 线程之间传递消息。支持普通事件的订阅和发布，支持粘性事件的订阅和发布。

[返回目录](#目录)

### <a name="数据解析"></a>数据解析

- [xml-ffi](https://gitcode.com/Cangjie-TPC/xml-ffi/overview) —— XML 格式解析库，支持 XML DOM 和 XML SAX 解析模式。
- [protobuf4cj](https://gitcode.com/Cangjie-TPC/protobuf4cj/overview) —— Protocol Buffers 协议解析库
- [yaml4cj](https://gitcode.com/Cangjie-TPC/yaml4cj/overview) —— YAML 格式解析库，可以快速可靠地解析和生成 YAML 数据，支持 YAML 1.1 和 1.2 的大部分内容，包括对锚点，标签，地图合并等的支持。
- [html4cj](https://gitcode.com/Cangjie-TPC/html4cj/overview) —— HTML 格式解析库，可用于分析互联网上或本地的的网页资源和 HTML 标签。支持操作 HTML 节点/属性、CSS 选择器。
- [asnone4cj](https://gitcode.com/Cangjie-TPC/asnOne4cj/overview) —— ASN.1 编码器和解码器的实现，它支持字节流的 BER 和 DER 编码规则。
- [jwt4cj](https://gitcode.com/Cangjie-TPC/jwt4cj/overview) —— 用于生成和验证 JSON Web Token，支持 Payload 校验、HMAC 算法签名及验证、RSA 算法签名及验证、ECDSA 算法签名及验证。
- [toml4cj](https://gitcode.com/Cangjie-TPC/toml4cj/overview) —— TOML 格式解析，语义易于阅读，易于解析成各种语言中的数据结构，能无歧义地映射为哈希表，具备实用的原生类型。
- [ini4cj](https://gitcode.com/Cangjie-TPC/ini4cj/overview) —— INI 文件是一种无固定标准格式的配置文件。它以简单的文字与简单的结构组成，常常使用在 Windows 操作系统上，许多程序也会采用 INI 文件做为配置文件使用。
- [xml_stream](https://gitcode.com/Cangjie-TPC/xml_stream/overview) —— XML 序列化反序列化库，提供 XML 操作相关的 STAX 风格接口，符合 XML 1.0 规范，支持命名空间。
- [csv4cj](https://gitcode.com/Cangjie-TPC/csv4cj/overview) —— csv 文件的仓颉操作工具，支持 csv 文件的读写、解析，支持中文。
- [cbor4cj](https://gitcode.com/Cangjie-TPC/cbor4cj/overview) —— 基于 RFC 7049 协议的简明二进制对象表示法（Cbor）的 Cangjie 语言实现。

[返回目录](#目录)

### <a name="数据库框架"></a>数据库框架

- [dataORM4cj](https://gitcode.com/Cangjie-TPC/dataORM4cj/overview) —— 端侧的数据库 ORM 框架。适用于 OHOS 系统。

[返回目录](#目录)

### <a name="对象存储"></a>对象存储

- [OBS Cangjie SDK](https://gitcode.com/Cangjie-TPC/oss-sdk/overview) —— 仓颉语言实现的对象存储服务软件开发工具包（OBS SDK，Object Storage Service Software Development Kit）是对 OBS 服务提供的 REST API 进行的封装。感谢普元信息技术股份有限公司为仓颉编程语言 TPC 社区做出的贡献！
- [s3client4cj](https://gitcode.com/Cangjie-TPC/s3-sdk/overview) —— 仓颉语言实现的 AWS S3 的客户端。感谢普元信息技术股份有限公司为仓颉编程语言 TPC 社区做出的贡献！

[返回目录](#目录)

### <a name="分布式"></a>分布式

- [config-client](https://gitcode.com/Cangjie-TPC/config-client/overview) —— Config Client用于操作存储在 Config Server 中的配置内容。感谢普元信息技术股份有限公司为仓颉编程语言 TPC 社区做出的贡献！ 
- [config-server](https://gitcode.com/Cangjie-TPC/config-server/overview) —— Config Server 是仓颉实现的可横向扩展、集中式的配置服务器，它用于集中管理应用程序各个环境下的配置。感谢普元信息技术股份有限公司为仓颉编程语言 TPC 社区做出的贡献！

[返回目录](#目录)

### <a name="任务调度"></a>任务调度

- [quartz4cj](https://gitcode.com/Cangjie-TPC/quartz4cj/overview) —— quartz4cj 是功能丰富的开源作业调度库，可通过触发器设置作业定时运行规则，控制作业的运行时间。感谢上海赛可出行科技服务有限公司架构团队为仓颉编程语言 TPC 社区做出的贡献！

[返回目录](#目录)

### <a name="安全类"></a>安全类

- [crypto4cj](https://gitcode.com/Cangjie-TPC/crypto4cj/overview) —— 安全的密码库，包括摘要算法、对称加密算法、非对称加密算法、密钥生成和签名验证。
- [oauth4cj](https://gitcode.com/Cangjie-TPC/oauth4cj/overview) —— OAuth 开放授权协议库，支持协议 OAuth1.0 和 OAuth2.0，允许第三方程序通过访问令牌访问受保护的资源，而无需暴露用户的凭据。支持授权码模式，简化模式，密码模式，客户端模式四种模式。
- [pkcs4cj](https://gitcode.com/Cangjie-TPC/pkcs4cj/overview) —— 提供 PKCS12 证书的生成、解析功能。
- [pbkdf2](https://gitcode.com/Cangjie-TPC/pbkdf2/overview) —— 基于 OPENSSL 实现的，用于生成 PBKDF2 密钥的工具。

[返回目录](#目录)

### <a name="工具类"></a>工具类
- [Cjson](https://gitcode.com/Cangjie-TPC/cjson/overview) —— Json 序列化/反序列化工具，自动给被标记的类增加fromJson()和toJson()等方法，使其自身具备序列化/反序列化能力。支持功能：1.序列化标记（@JsonSerializable）2. 定制序列化属性名（@JsonName）3. 忽略属性（@JsonIgnore）4.序列化默认值 5.定制序列化和反序列化逻辑（IJsonSerializable<T>）
- [zip4cj](https://gitcode.com/Cangjie-TPC/zip4cj/overview) —— 创建和解压 zip 压缩格式文件。
- [zlib4cj](https://gitcode.com/Cangjie-TPC/zlib4cj/overview) —— 创建和解压 zlib 压缩格式文件。
- [phonenumber4cj](https://gitcode.com/Cangjie-TPC/phonenumber4cj/overview) —— 用于解析、格式化和验证国际电话号码，可根据电话号码查询运营商信息、地理位置信息、时区信息，为指定国家/地区提供有效的示例号码。
- [bzip2-ffi](https://gitcode.com/Cangjie-TPC/bzip2-ffi/overview) —— 创建和解压 bzip2 压缩格式的文件。
- [vcard4cj](https://gitcode.com/Cangjie-TPC/vcard4cj/overview) —— 电子名片标准格式（.vcf 文件）解析库。
- [chardet4cj](https://gitcode.com/Cangjie-TPC/chardet4cj/overview) —— 检测常用文本编码，支持 ISO-2022-CN 编码格式、UTF-8 编码格式、UTF-16BE / UTF-16LE 编码格式。
- [uuid4cj](https://gitcode.com/Cangjie-TPC/uuid4cj/overview) —— 通用唯一标识符，长度为 128 位，可以保证跨空间和时间的唯一性。可基于时间/位置、名称（SHA1、MD5）、随机数、时间纪元等生成。
- [compress4cj](https://gitcode.com/Cangjie-TPC/compress4cj/overview) —— 用于处理多种压缩文件的库，主要包括存档格式 rar、tar、zip 格式, 流式包含bzip2、gzip、zlib、deflate 格式的压缩/解压功能，只支持 rar4.0 文件解压功能。
- [diffUtils4cj](https://gitcode.com/Cangjie-TPC/diffutils4cj/overview) —— 可以逐行比对两个字符串的差异，并按行将差异展示出来，提供补丁打包和添加功能。文档和数据的对比需要先转换为字符串数组再使用该库进行逐行比对。
- [pinyin4cj](https://gitcode.com/Cangjie-TPC/pinyin4cj/overview) —— 用于将汉字转为拼音，支持词、句转换成拼音，简体/繁体中文字符转换成拼音，多音字符转换成拼音，简体、繁体中文字符互转，支持添加自定义字典，支持 Unicode 格式的字符 ü、支持声调符号、支持首字母格式。
- [is-png-cj](https://gitcode.com/Cangjie-TPC/is-png-cj/overview) —— 一个判断图片格式的库，根据图片的文件数据，判断图片是否为 png 格式。
- [is-webp-cj](https://gitcode.com/Cangjie-TPC/is-webp-cj/overview) —— 一款根据文件数据，判断图片是否是 webp 格式的库。

[返回目录](#目录)

### <a name="日志类"></a>日志类

- [log-cj](https://gitcode.com/Cangjie-TPC/log-cj/overview) —— 日志管理框架，支持控制台日志输出和文件日志输出，支持使用 Json 进行自定义配置。

[返回目录](#目录)

### <a name="算法类"></a>算法类

- [ahocorasick4cj](https://gitcode.com/Cangjie-TPC/ahocorasick4cj/overview) —— 使用 Aho-Corasick 字符串搜索算法，能够提供高效的字符串匹配功能，支持多字符搜索，支持关键词库模式，支持自定义值输出模式。
- [disklrucache4cj](https://gitcode.com/Cangjie-TPC/disklrucache4cj/overview) —— 管理硬盘内容的存储管理工具，它采用了最近最少使用（LRU）算法，以对硬盘中存储的文件进行管理，在存储空间短缺的情况下，会优先将最近最少使用的文件删除，以扩展可用的硬盘空间。
- [flexSearch4cj](https://gitcode.com/Cangjie-TPC/flexSearch4cj/overview) —— 快速、零依赖的全文搜索库。在原始搜索速度方面，FlexSearch 优于每一个搜索库，并提供灵活的搜索功能，如多字段搜索，语音转换或部分匹配。根据使用的选项，它还提供最高内存效率的索引。适用于 OHOS 系统。
- [memorycache](https://gitcode.com/Cangjie-TPC/memorycache/overview) —— 内存缓存库，支持基于的 lru 本地缓存读写和内存缓存。
- [metaphone-cj](https://gitcode.com/yishengTH/metaphone-cj/overview) —— Metaphone 是一种语音算法，由 Lawrence Philips 于 1990 年发布，用于根据英语发音对单词进行索引。
- [leven4cj](https://gitcode.com/Cangjie-TPC/leven4cj/overview) —— 使用 Levenshtein 距离算法测量两个字符串之间的差异。
- [hibase32-cj](https://gitcode.com/Cangjie-TPC/hibase32-cj/overview) —— Base32(RFC 4648) 编码/解码库。

[返回目录](#目录)

### <a name="音视频"></a>音视频

- [mp4parser4cj](https://gitcode.com/Cangjie-TPC/mp4parser4cj/overview) —— 读取、写入 mp4 格式音视频文件编辑的工具，包括音视频合成、裁剪、批量合成。
- [mp3tag4cj](https://gitcode.com/Cangjie-TPC/mp3tag4cj/overview) —— 用于读取、写入、添加和删除 ID3v1、ID3v2 标签。标签表示内容支持 ISO-8859-1，UTF-16LE，UTF-16BE，UTF-8 4种编码； 读取音频数据帧帧头包含的数据信息；判断 VBR 文件，获得每个音频数据帧的位率；在音频数据帧结尾和 ID3v1 标记之间添加或删除自定义标签。
- [ijkplayer-ffi](https://gitcode.com/Cangjie-TPC/ijkplayer-ffi/overview) —— 基于 FFmpeg 的视频播放器，包括视频播放、暂停、停止、重置、释放、前进、后退、倍数播放、循环播放、设置音量、屏幕常亮等。适用于 OHOS 系统。
 
[返回目录](#目录)

### <a name="字符编码"></a>字符编码

- [charset4cj](https://gitcode.com/Cangjie-TPC/charset4cj/overview) —— 常用的字符编码集合库。

[返回目录](#目录)

### <a name="图像处理"></a>图像处理

- [gifdrawable4cj](https://gitcode.com/Cangjie-TPC/gifdrawable4cj/overview) —— GIF 图像渲染库，支持播放、暂停、调节 GIF 播放速率、设置显示大小、支持不同的拉伸类型。适用于 OHOS 系统。
- [droplet](https://gitcode.com/Cangjie-TPC/droplet/overview) —— 图像加载缓存库，致力于更高效、更轻便、更简单得加载图片。在图片列表滚动时候实现平滑滚动得效果。适用于 OHOS 系统。
- [qrcode4cj](https://gitcode.com/Cangjie-TPC/qrcode4cj/overview) —— 解析/生成多种类型的一维码/二维码，包括 QRCode、Data Matrix、PDF417 barcode、Aztec barcode、CodeBar、Code128、Code39、Code93、EAN13、EAN8、ITF、UPC-A、UPC-E、UPC/EAN、MaxiCode、RSS barcode(RSS-14、RSS-Expanded)。
- [droplet-transformations](https://gitcode.com/Cangjie-TPC/droplet-transformations/overview) —— 图像转换库,提供了 高亮，滤镜，灰度， 虚幻， 马赛克， 漫画，像素，素描，漩涡， 油画， 暗边， 模糊等图像转换能力。适用于 OHOS 系统。

[返回目录](#目录)

### <a name="开发者类"></a>开发者类

- [prism4cj](https://gitcode.com/Cangjie-TPC/prism4cj/overview) —— 轻量的语法高亮库，提供任意语法的标记化策略，支持标记不同类型的关键词、不同语言的解析器/分发器、预定义语法解析器。
- [commonmark4cj](https://gitcode.com/Cangjie-TPC/commonmark4cj/overview) —— 根据 CommonMark 规范（以及一些扩展）解析和呈现 Markdown 文本。
- [formula-ffi](https://gitcode.com/Cangjie-TPC/formula-ffi/overview) —— 解析和生成数学公式，支持生成 bitmap 图片格式。适用于 OHOS 系统。
- [markdown4cj](https://gitcode.com/Cangjie-TPC/markdown4cj/overview) —— Markdown 解析和展示，排版语法简洁，使用高效便捷，扩展性强，用户可自定义 Markdown 显示样式。适用于 OHOS 系统。

- [editor4cj](https://gitcode.com/Cangjie-TPC/editor4cj) —— OHOS 多语言代码编辑器。用户通过定义 EditorKit 类对象，实现对语言(language)、字体大小(fontSize)、主题(theme)、编辑器文本(text)、代码编辑器高度(height)、代码编辑器宽度(width)、自动缩进(tabLen)的设置，进而实现代码高亮、滚动条、行号显示、自动补全等功能，当前只支持 utf8 编码。适用于 OHOS 系统。

[返回目录](#目录)

### <a name="动画类"></a>动画类

- [lottie4cj](https://gitcode.com/Cangjie-TPC/lottie4cj/overview) —— 基于 Json 的动画库。它可以解析 Adobe After Effects 软件通过 Bodymovin 插件导出的 Json格式的动画，并在移动设备上进行本地渲染。支持动画播放/暂停/停止，设置播放速度，设置动画播放方向。适用于 OHOS 系统。
- [rebound4cj](https://gitcode.com/Cangjie-TPC/rebound4cj/overview) —— 模拟弹簧动力学，实现弹簧动画效果。适用于 OHOS 系统。
- [shimmer4cj](https://gitcode.com/Cangjie-TPC/shimmer4cj/overview) —— 一个简单灵活的为应用视图添加闪烁效果的库，主要有由左到右倾斜，由左到右竖直，由左到右圆形，由上到下水平等闪光效果。适用于 OHOS 系统。

[返回目录](#目录)

### <a name="基础设施"></a>基础设施

- [io4cj](https://gitcode.com/Cangjie-TPC/io4cj/overview) —— 是 HttpClient 的底层 IO 库，是对仓颉 IO 库的补充，使访问、存储和处理数据变得更加容易。核心概念是 Source 和 Sink，类似于仓颉的 InputStream 和 OutputStream。

[返回目录](#目录)


### <a name="地理信息"></a>地理信息

- [GISTools](https://gitcode.com/Cangjie-TPC/GISTools/overview) —— 地理信息系统工具库，处理常用的地理信息，包括坐标转换，几何计算，地图投影等功能。

[返回目录](#目录)

### <a id="ui类"></a>UI类

- [roundedImageView4cj](https://gitcode.com/Cangjie-TPC/roundedImageView4cj/overview) —— 支持圆角（和椭圆或圆形）的快速 ImageView。适用于 OHOS 系统。

[返回目录](#目录)

### <a name="科学计算"></a>科学计算

- [matrix4cj](https://gitcode.com/Cangjie-TPC/matrix4cj/overview) —— 线性代数库，用于构造和操作密集矩阵。

[返回目录](#目录)

