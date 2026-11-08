# Awesome 中文在线工具

一份人工整理的中文在线工具清单，全部**免费、免注册、打开即用**。文件处理类工具在浏览器本地完成，文件不会上传服务器。

站点入口：**https://toolax.cn**

共收录 114 个工具，按用途分类如下。

## 目录

- [图片处理](#图片处理)
- [PDF 文档](#PDF 文档)
- [视频与音频](#视频与音频)
- [GIF 动图](#GIF 动图)
- [开发工具](#开发工具)
- [文本处理](#文本处理)
- [颜色工具](#颜色工具)
- [加密与安全](#加密与安全)
- [时间日期](#时间日期)
- [站长工具](#站长工具)
- [信息查询](#信息查询)
- [日常计算](#日常计算)
- [实用工具](#实用工具)

## 关于「本地处理」

判断一个在线工具靠不靠谱，最实用的标准是看它有没有把文件传到服务器：

1. 打开浏览器开发者工具的 Network 面板
2. 拖一个文件进工具页面
3. 出现几十 MB 的 POST 请求 = 在往服务器上传；只有几个小请求 = 在浏览器本地跑

本清单里的图片、PDF、视频、GIF 类工具全部属于后者：处理过程用的是你自己电脑的 CPU（视频部分依赖 WebAssembly 版 FFmpeg），所以大文件会慢，但文件不会离开本机。

## 工具清单

### 图片处理

| 工具 | 说明 |
| --- | --- |
| [图片编辑器](https://toolax.cn/tools/image-editor) | 多元素画布编辑、模板素材、PSD 导入与作品导出 |
| [图片压缩](https://toolax.cn/tools/image-compress) | 压缩 JPEG、PNG、WebP、GIF、SVG，浏览器本地处理 |
| [图片转换](https://toolax.cn/tools/image-convert) | HEIC、JPG、PNG、WebP、GIF、TIFF、AVIF 等格式互转 |
| [Base64图片转换](https://toolax.cn/tools/image-base64) | 图片与 Base64 字符串互转，支持上传、粘贴与预览 |
| [图片旋转翻转](https://toolax.cn/tools/image-rotate) | 旋转图片角度，支持水平/垂直翻转与前后对比预览 |
| [图片调整尺寸](https://toolax.cn/tools/image-resize) | 调整图片宽高和比例，支持等比缩放与前后对比 |
| [图片EXIF查看](https://toolax.cn/tools/image-exif-view) | 查看图片文件信息与 EXIF 元数据，含相机、拍摄参数与 GPS |
| [去EXIF](https://toolax.cn/tools/image-exif-strip) | 批量清除图片 EXIF 元数据并下载，保护隐私 |
| [图片滤镜](https://toolax.cn/tools/image-filters) | 油画、水彩、马赛克、模糊、老照片、黑白、铅笔画一站式滤镜 |
| [图片裁切](https://toolax.cn/tools/image-crop) | 宫格切片或窗口取景裁切，支持缩放、拖动、旋转与镜像 |
| [AI消除](https://toolax.cn/tools/image-erase) | 涂抹不需要的内容，用周围像素填补后下载 |
| [图片化打包](https://toolax.cn/tools/image-pack) | 把文件藏进图片，支持分片、密码与无影坦克提取 |
| [丑萌头像生成器](https://toolax.cn/tools/weird-avatar) | 按 Seed 随机生成可复现的手绘丑萌头像，支持分享链接与本地导出 |

### PDF 文档

| 工具 | 说明 |
| --- | --- |
| [PDF 转图片](https://toolax.cn/tools/pdf-to-image) | 把 PDF 每一页渲染为 PNG / JPG 图片，可选 DPI 与页码范围 |
| [PDF 转长图](https://toolax.cn/tools/pdf-to-long-image) | 把所有页面纵向拼接成一张长图，便于分享与预览 |
| [PDF 转文本](https://toolax.cn/tools/pdf-to-text) | 抽取 PDF 中的文字内容，输出 TXT |
| [PDF 转 Word](https://toolax.cn/tools/pdf-to-word) | 把 PDF 转成可编辑的 Word 文档（.docx），保留文字与排版 |
| [PDF 转 Excel](https://toolax.cn/tools/pdf-to-excel) | 抽取 PDF 中的表格生成 Excel（.xlsx），每个表格一个工作表 |
| [PDF 合并](https://toolax.cn/tools/pdf-merge) | 把多个 PDF 按选择顺序合并为一个，保留书签大纲 |
| [PDF 拆分](https://toolax.cn/tools/pdf-split) | 按页码范围提取成一个 PDF，或逐页拆成多个 PDF |
| [PDF 旋转](https://toolax.cn/tools/pdf-rotate) | 旋转指定页面，只改旋转属性不重新渲染，画质无损 |
| [PDF 水印](https://toolax.cn/tools/pdf-watermark) | 添加平铺文字水印，支持中文、透明度与任意角度 |
| [PDF 压缩](https://toolax.cn/tools/pdf-compress) | 压缩 PDF 体积，需服务端已安装 Ghostscript |
| [Office 转 PDF](https://toolax.cn/tools/office-to-pdf) | Word / Excel / PPT / RTF / ODF 转 PDF，需服务端已安装 LibreOffice |
| [图片转 PDF](https://toolax.cn/tools/image-to-pdf) | 将一张或多张图片按顺序合并为一个 PDF |
| [TXT 转 PDF](https://toolax.cn/tools/txt-to-pdf) | 把纯文本生成 PDF 文档，支持中文 |
| [Markdown 转 PDF](https://toolax.cn/tools/md-to-pdf) | 把 Markdown 生成 PDF，支持标题/列表/代码块/表格/引用/链接 |

### 视频与音频

| 工具 | 说明 |
| --- | --- |
| [视频压缩](https://toolax.cn/tools/video-compress) | 本地压缩视频，可调分辨率、帧率、音轨与画质 |
| [浏览器录屏](https://toolax.cn/tools/screen-recorder) | 录屏幕 / 摄像头，支持画中画与麦克风，参数可调 |
| [视频裁剪](https://toolax.cn/tools/video-crop) | 按像素裁剪视频画面区域 |
| [视频缩放](https://toolax.cn/tools/video-resize) | 按宽高缩放视频画面，可只填一边 |
| [视频旋转翻转](https://toolax.cn/tools/video-rotate) | 旋转 90°/180°/270°，水平或垂直翻转 |
| [提取音轨](https://toolax.cn/tools/video-audio) | 从视频提取音频，导出 AAC / WAV / MP3 |
| [视频抽帧](https://toolax.cn/tools/video-frames) | 按间隔或帧率导出 PNG 截图，可打包 ZIP |
| [视频合并](https://toolax.cn/tools/video-merge) | 多段视频按顺序拼接，统一分辨率输出 MP4 |
| [视频格式转换](https://toolax.cn/tools/video-convert) | 转为 MP4 或 WebM，便于网页播放与兼容 |
| [录音工具](https://toolax.cn/tools/audio-recorder) | 调用麦克风录制音频，本地编码下载，可导出 WAV |
| [分贝测试仪](https://toolax.cn/tools/decibel-meter) | 调用麦克风实时测量环境噪音分贝，含仪表盘、波形、趋势与统计 |
| [网格音序器](https://toolax.cn/tools/grid-sequencer) | 点击网格编排旋律，实时播放高亮跟随，可导出 WAV |
| [在线鼓机](https://toolax.cn/tools/drum-machine) | 9 轨 32 步鼓机，多种鼓组与预设节奏，可导出 WAV / MIDI |
| [在线钢琴](https://toolax.cn/tools/online-piano) | 真实钢琴采样音色，键盘鼠标皆可弹，内置演示曲目 |

### GIF 动图

| 工具 | 说明 |
| --- | --- |
| [GIF图片合成](https://toolax.cn/tools/gif-compose) | 多张图片按顺序合成 GIF，可调延迟、尺寸与文字水印 |
| [视频转 GIF](https://toolax.cn/tools/gif-video) | 按帧率从视频抽帧合成 GIF，可调帧率与宽度 |
| [GIF拆帧](https://toolax.cn/tools/gif-frames) | 拆成 PNG 帧，或还原优化帧后导出 GIF / 打包下载 |
| [GIF裁剪](https://toolax.cn/tools/gif-crop) | 裁剪 GIF 或图片画面，导出 GIF 或 PNG |
| [GIF缩放](https://toolax.cn/tools/gif-resize) | 按宽高缩放动图，可只填一边按比例 |
| [GIF旋转翻转](https://toolax.cn/tools/gif-rotate) | 旋转 90°/180°/270°，或水平 / 垂直翻转 |
| [GIF时间轴](https://toolax.cn/tools/gif-timeline) | 反向、来回播、调速或按帧裁切时长 |
| [GIF压缩](https://toolax.cn/tools/gif-compress) | 减色、优化、缩放或抽帧压缩 GIF |

### 开发工具

| 工具 | 说明 |
| --- | --- |
| [JSON 工具](https://toolax.cn/tools/json) | 格式化、校验、压缩、YAML/CSV 互转、TypeScript 类型生成，一站式 JSON 处理 |
| [BestJSON](https://bestjson.com/) | JSON 格式化、校验与比较，输入在浏览器本地处理，无需注册；严格格式化保留原始数字文本 |
| [XML 工具箱](https://toolax.cn/tools/xml) | JSON 转 XML、XML 格式化压缩、XML 转 JSON，一站式 XML 处理 |
| [编码工具箱](https://toolax.cn/tools/encoding) | Base64、URL、HTML、Unicode 编解码一站式工具箱 |
| [URL 解析工具](https://toolax.cn/tools/url-parser) | 拆解链接结构，附带 encode/decode 编解码 |
| [进制与编码转换工具箱](https://toolax.cn/tools/base-encoding) | 2/8/10/16 进制互转与文本二进制编码互转 |
| [正则工具箱](https://toolax.cn/tools/regex) | 正则测试、模板库与匹配详情 |
| [Lorem Ipsum 生成器](https://toolax.cn/tools/lorem) | 生成中英文占位文本，可自定义段落数 |
| [Cron 表达式解析](https://toolax.cn/tools/cron) | 解析 Cron 定时表达式，生成中文描述并计算执行时间 |
| [HTML 预览器](https://toolax.cn/tools/html-preview) | 编写 HTML/CSS/JS，右侧沙箱实时渲染预览 |
| [SQL 格式化](https://toolax.cn/tools/sql-formatter) | 在线美化 SQL 语句，支持 MySQL/PostgreSQL 等方言 |

### 文本处理

| 工具 | 说明 |
| --- | --- |
| [文本工具箱](https://toolax.cn/tools/text-toolbox) | 差异对比、字数统计、简繁大小写、去重替换、排序反转与 Slug 一站式工具箱 |
| [摩斯密码](https://toolax.cn/tools/morse) | 文本与摩斯密码实时互转，支持电码音效播放 |
| [罗马数字转换](https://toolax.cn/tools/roman) | 阿拉伯数字与罗马数字实时双向转换，支持逐位分解、批量转换与对照表 |
| [Emoji 翻译器](https://toolax.cn/tools/emoji) | 文字转 Emoji、Emoji 转文字，内置双语词典与关键词搜索 |
| [汉字转拼音](https://toolax.cn/tools/pinyin) | 中文转拼音，支持声调符号、数字与无声调，可处理中英文混排 |
| [字帖生成](https://toolax.cn/tools/hanzi-practice) | 带笔顺的汉字字帖，可打印、可导出图片，支持田字格与描红 |
| [中文大写转换](https://toolax.cn/tools/chinese-uppercase) | 阿拉伯数字实时转换为中文大写，支持金额大写与纯数字大写 |
| [Markdown 预览器](https://toolax.cn/tools/markdown) | 左侧编辑 Markdown，右侧实时预览 HTML，支持工具栏插入与导出 |

### 颜色工具

| 工具 | 说明 |
| --- | --- |
| [颜色选择器](https://toolax.cn/tools/color) | 颜色选择、屏幕吸色、配色与渐变 CSS 生成 |
| [颜色格式转换](https://toolax.cn/tools/color-converter) | HEX、RGB、RGBA、HSL、HSLA 互转 |
| [颜色对比度检查](https://toolax.cn/tools/color-contrast) | 检测文字与背景色是否符合 WCAG 无障碍标准 |
| [图片取色器](https://toolax.cn/tools/image-color-picker) | 从图片中提取主色调，显示占比并一键复制 HEX |
| [颜色工具箱](https://toolax.cn/tools/color-toolbox) | 配色方案生成、单色明度阶、对比度检测与渐变生成一站式工具箱 |
| [颜色名称查找](https://toolax.cn/tools/color-name-lookup) | 根据 HEX/RGB 颜色值查找最接近的 CSS 命名颜色 |

### 加密与安全

| 工具 | 说明 |
| --- | --- |
| [密码强度检测](https://toolax.cn/tools/password-strength) | 实时检测密码强度与安全性，熵值评估与弱密码规则检查 |
| [加密哈希工具箱](https://toolax.cn/tools/hash) | MD5、SHA、AES 加密与哈希一站式工具箱 |
| [ID与密码生成工具箱](https://toolax.cn/tools/id-generator) | 密码、UUID、NanoID 随机生成一站式工具箱 |
| [JWT 解码器](https://toolax.cn/tools/jwt) | 解码 JWT Token 查看 Header 与 Payload |

### 时间日期

| 工具 | 说明 |
| --- | --- |
| [Unix时间戳转换](https://toolax.cn/tools/timestamp) | Unix时间戳与日期时间互转 |
| [世界时钟](https://toolax.cn/tools/world-clock) | 查看全球主要城市实时时间 |
| [时区转换器](https://toolax.cn/tools/timezone) | 不同时区的时间转换 |
| [倒计时器](https://toolax.cn/tools/countdown) | 设置目标时间进行倒计时，支持全屏显示 |
| [年龄计算器](https://toolax.cn/tools/age) | 精确计算年龄，支持天数/月数/年数 |
| [秒表](https://toolax.cn/tools/stopwatch) | 精确计时，支持暂停、继续与计次记录 |
| [日期工具箱](https://toolax.cn/tools/date-toolbox) | 日期差计算与日期加减一体化工具箱 |

### 站长工具

| 工具 | 说明 |
| --- | --- |
| [短链接生成](https://toolax.cn/tools/short-link) | 长链压缩、自定义后缀、有效期与点击统计 |
| [IP 信息查询工具](https://toolax.cn/tools/ip) | IP 归属地与网络信息查询 |
| [User-Agent 解析](https://toolax.cn/tools/user-agent) | 解析浏览器 User-Agent，识别浏览器、系统、设备与引擎 |
| [公共 DNS 大全](https://toolax.cn/tools/public-dns) | 国内国外公共 DNS 与三大运营商各省解析地址，支持搜索复制 |
| [公共 NTP 服务](https://toolax.cn/tools/public-ntp) | 国内国际公共 NTP 授时服务器地址，支持搜索复制 |
| [顶级域名后缀](https://toolax.cn/tools/tld-lookup) | 1483 个 TLD 后缀查询，标注支持备案，可按字母与备案筛选 |
| [流媒体调试](https://toolax.cn/tools/stream-debugger) | 在线预览 m3u8 / flv 流，查看缓冲、分辨率与 CORS |

### 信息查询

| 工具 | 说明 |
| --- | --- |
| [电话号码解析](https://toolax.cn/tools/phone-parser) | 解析国际电话号码，识别国家、区号、号码类型与标准格式 |
| [字体版权查询](https://toolax.cn/tools/font-license) | 检测本机已安装字体，查询是否可免费商用 |
| [中国历史朝代表](https://toolax.cn/tools/dynasty) | 中国历史纪年简表，查朝代起讫、都城与今地 |
| [世界各国首都查询](https://toolax.cn/tools/world-capitals) | 193 会员国及 2 观察员国首都中英文对照，支持搜索与洲别筛选 |
| [常用电话大全](https://toolax.cn/tools/common-phones) | 全国紧急、政务、银行、物流等公共服务号码查询，支持搜索复制 |

### 日常计算

| 工具 | 说明 |
| --- | --- |
| [百分比计算器](https://toolax.cn/tools/percent) | 占比、增减百分比、求某数百分比，输入即时出结果 |
| [BMI计算器](https://toolax.cn/tools/bmi) | 计算BMI指数和健康评估，查看建议体重范围 |
| [个税计算器](https://toolax.cn/tools/tax) | 计算工资五险一金和个人所得税，支持专项扣除 |
| [按揭贷款计算器](https://toolax.cn/tools/mortgage) | 计算房贷月供、利息和还款计划，支持等额本息和等额本金 |
| [折扣计算器](https://toolax.cn/tools/discount) | 计算打折后价格，支持百分比和固定金额折扣 |
| [小费计算器](https://toolax.cn/tools/tip) | 按账单与服务比例算出小费、总计和每人应付，支持分摊与货币切换 |
| [每日抽签](https://toolax.cn/tools/daily-fortune) | 今日运势、财运桃花健康、幸运色与宜忌 |
| [单位换算工具](https://toolax.cn/tools/unit-converter) | 长度、质量、温度、面积、体积、时间、速度、存储、压强、能量与功率等互转 |
| [汇率换算工具](https://toolax.cn/tools/currency) | 实时汇率、双向换算、多币种对照 |
| [花语大全](https://toolax.cn/tools/flower-language) | 常见花卉花语、颜色含义与花期，支持搜索与分类筛选 |

### 实用工具

| 工具 | 说明 |
| --- | --- |
| [计算器](https://toolax.cn/tools/calculator) | 科学计算、实时运算与历史记录 |
| [二维码生成](https://toolax.cn/tools/qr) | 文本、网址、WIFI、名片等，可加 Logo 与配色 |
| [二维码解析](https://toolax.cn/tools/qr-read) | 上传图片识别二维码内容，支持复制结果 |
| [条形码生成](https://toolax.cn/tools/barcode) | 批量生成条形码，支持多种码制与打包下载 |
| [条形码解析](https://toolax.cn/tools/barcode-read) | 上传图片识别条形码内容与类型 |
| [文件大小换算](https://toolax.cn/tools/file-size) | 字节、KB、MB、GB、TB 文件大小单位互转（1024 进制） |
| [中国地图](https://toolax.cn/tools/china-map) | 点击省份进入下级行政区，支持缩放平移 |
| [天地图](https://toolax.cn/tools/tianditu-map) | 矢量/影像/地形底图，支持省市范围下钻、地名搜索与我的地点 |

## 边界说明

这类工具不是万能的，以下情况建议直接用本地软件或命令行：

- 超过 300MB 的视频：浏览器内存装不下，用 FFmpeg 命令行更快更稳
- 批量、脚本化处理：命令行可控性远高于网页
- 涉密文件：不要用任何在线工具

## 贡献

欢迎提 PR 补充同类工具，或指出失效链接。收录标准只有三条：

- 免费可用，不需要注册
- 没有强制跳转广告和诱导下载
- 文件处理类优先本地完成

## License

MIT
