# 公共 API 目录 🔥

# public-apis-cn项目介绍
- 基于public-apis项目翻译为中文版，并去掉广告，再收集添加国内常用API
- 欢迎大家点赞🌟和贡献添加、更新现有的API，让这个项目成为**中文版免费API大全**。
- 描述前增加💰/ 🆓，以区分是收费/免费的API。

## 目录

- [公共 API 目录 🔥](#公共-api-目录-)
  - [目录](#目录)
    - [AI模型](#ai模型)
    - [天气](#天气)
    - [国内物流](#国内物流)
    - [国际物流](#国际物流)
    - [视频](#视频)
    - [车辆](#车辆)
    - [URL 缩短服务](#url-缩短服务)
    - [交通](#交通)
    - [跟踪](#跟踪)
    - [文本分析](#文本分析)
    - [测试数据](#测试数据)
    - [体育与健身](#体育与健身)
    - [社交](#社交)
    - [购物](#购物)
    - [安全](#安全)
    - [科学与数学](#科学与数学)
    - [编程](#编程)
    - [摄影](#摄影)
    - [电话](#电话)
    - [人格](#人格)
    - [专利](#专利)
    - [开源项目](#开源项目)
    - [开放数据](#开放数据)
    - [新闻](#新闻)
    - [音乐](#音乐)
    - [机器学习](#机器学习)
    - [工作](#工作)
    - [健康](#健康)
    - [政府](#政府)
    - [地理编码](#地理编码)
    - [游戏与漫画](#游戏与漫画)
    - [餐饮](#餐饮)
    - [财务](#财务)
    - [活动](#活动)
    - [环境](#环境)
    - [娱乐](#娱乐)
    - [电子邮件](#电子邮件)
    - [文档与生产力](#文档与生产力)
    - [词典](#词典)
    - [开发](#开发)
    - [数据验证](#数据验证)
    - [货币兑换](#货币兑换)
    - [加密货币](#加密货币)
    - [持续集成](#持续集成)
    - [云存储与文件共享](#云存储与文件共享)
    - [日历](#日历)
    - [商业](#商业)
    - [图书](#图书)
    - [区块链](#区块链)
    - [身份验证与授权](#身份验证与授权)
    - [艺术与设计](#艺术与设计)
    - [反恶意软件](#反恶意软件)
    - [动漫](#动漫)
    - [动物](#动物)

---

---

### AI模型

`因AI模型需强大的GPU算力，硬件投资、电力成本高，通常收费，免费额度有限，如给予10～20元API额度，并且会叠加有效期，一般只用于测试。`

`真正能免费是将训练后的模型开源，国内最有名是DeepSeek、Qwen、KIMI、ChatGLM、minimax均以将最强模型开源。`

| API | 描述 | 认证方式 | 支持HTTPS |
|:---|:---|:---:|:---:|
| [NVIDIA NIM](https://build.nvidia.com/models) | 🆓 英伟达官方推理加速平台，提供 1000+ 免费积分试用，集成 Llama、DeepSeek 等主流开源模型，限制 40 RPM | 是 | 是 |
| [DeepSeek深度求索](https://www.deepseek.com) | 🆓+💰 深度求索公司开源的AI模型，非常友好的MIT开源协议！v3.2模型发布后deepseek-reasoner、deepseek-chat模型API：百万tokens/输入2元/输出3元！ | `apiKey` | 是 |
| [Qwen通义千问](https://tongyi.aliyun.com/) | 🆓💰阿里巴巴开源AI模型，中型以下模型开源，MAX版主要以云服务提供API，网友称真正的OpenAI | `apiKey` | 是 |
| [KIMI](https://platform.moonshot.cn) | 🆓 +💰月之暗面科技研发，特点最早提供超长百万上下文的AI模型，千亿级参数 | `apiKey` | 是 |
| [ChatGLM智谱](https://chatglm.cn) | 🆓+💰智谱清言推出的AI模型，主打toB模式， | `apiKey` | 是 |
| [minimax](https://api.minimax.chat) | 🆓+💰 公司香港上市，开源+官网API套餐，主打toC路线 | `apiKey` | 是 |
| [Ollama](https://ollama.com) | 🆓 利用本机CPU、GPU快速运行主流开源AI模型 | `无` | 否 |
| [LM Studio](https://lmstudio.ai) | 🆓 探索、从Hugging Face下载，运行本地AI模型，带聊天窗口 | `无` | 否 |
| [xAI](https://x.ai) | 🆓+💰马斯克投资的xAI公司，旧版本github.com/xai-org/grok-1开源；grok-4大力出奇迹，训练使用了约20万张H100 GPU，百万tokens输入/输出：3/5美元。 | `apiKey` | 是 |
| [llama](https://llama.meta.com) | 🆓 Meta开源AI模型llama，自由下载本地使用 | `apiKey` | 是 |
| [Google Gemini](https://gemini.google.com/) | 💰 Google公司推出AI模型，以云服务提供API服务，特点支持百万tokens输入上下文，开源Gemma（最大27B）小型模型免费 | `apiKey` | 是 |
| [OpenAI](https://platform.openai.com/) | 🆓+💰 ChatGPT官方API服务，开源gpt‑oss‑120b 接近 o4‑mini，gpt‑oss‑20b接近 o3‑mini，网友称其CloseAI | `apiKey` | 是 |
| [Azure OpenAI](https://azure.microsoft.com/zh-cn/products/ai-services/openai-service/) | 💰 微软Azure云提供的OpenAI服务 | `apiKey` | 是 |
| [Claude](https://www.anthropic.com/api) | 💰 由Anthropic公司提供，与OpenAI竞争激励 | `apiKey` | 是 |
| [Groq](https://www.groq.com/) | 🆓+💰利用LPU卡替换GPU，加速AI回答，特点是速度快，每秒300～500个tokens。免费帐户：限制每分钟6000 token | `apiKey` | 是 |
| [Cerebras](https://www.cerebras.net/) | 💰 以速度著称，专用AI芯片和推理引擎支持，每秒可达约2000 tokens，免费账户：限制每分钟64000 token | `apiKey` | 是 |
| [文心一言](https://wenxin.baidu.com/) | 💰 百度研发的商用AI模型 | `apiKey` | 是 |
| [豆包](https://www.volcengine.com/product/doubao) | 💰 火山引擎提供的商用AI模型：Doubao-pro-128k，百万tokens/输入5元/输出9元 | `apiKey` | 是 |
| [零一万物](https://platform.lingyiwanwu.com/) | 🆓+💰李开复投资的AI模型公司，小模型开源，大模型以API提供服务，现已转型Agent平台 | `apiKey` | 是 |
| [孟子](https://www.langboat.com/) | 🆓+💰澜舟科技的孟子3-13B模型开源；标准大模型收费；特点是轻量模型优胜成绩 | `apiKey` | 是 |

<img width="1546" height="804" alt="image" src="https://github.com/user-attachments/assets/88a1f14e-a189-4c69-97f8-3d165861d06d" />


增加了模型智能程度、速度、成本，数据来源 artificialanalysis.ai 仅供参考。

**[⬆ 返回目录](#目录)**

### 天气

> 国内天气API以 README.md 为准。

| API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [7Timer!](http://www.7timer.info/doc.php?lang=zh-CN) | 国内除了查询慢点，好处是不需要APIKey！ | 否 | 否 | 未知 |
| [墨迹天气API](https://www.mojicb.com/support) | 提供分钟级、公里级天气预报 | `apiKey` | 是 | 未知 |
| [高德天气API](https://lbs.amap.com/api/webservice/guide/api/weatherinfo) | 实时和未来数天的天气预报服务 | `apiKey` | 是 | 未知 |
| [和风天气API](https://www.qweather.com/) | 提供实时、三日、七日天气预报 | `apiKey` | 是 | 未知 |
| [心知天气API](https://www.seniverse.com/) | 提供实况天气数据和未来三天天气预报 | `apiKey` | 是 | 未知 |
| [AccuWeather](https://developer.accuweather.com/apis) | 天气和预报数据 | `apiKey` | 否 | 未知 |
| [Aemet](https://opendata.aemet.es/centrodedescargas/inicio) | 西班牙的天气和预报数据 | `apiKey` | 是 | 未知 |
| [apilayer weatherstack](https://weatherstack.com/) | 实时和历史的全球天气数据API | `apiKey` | 是 | 未知 |
| [APIXU](https://www.apixu.com/doc/request.aspx) | 天气数据 | `apiKey` | 是 | 未知 |
| [AQICN](https://aqicn.org/api/) | 1000多个城市的空气质量指数数据 | `apiKey` | 是 | 未知 |
| [AviationWeather](https://www.aviationweather.gov/dataserver) | NOAA航空天气预报和观测数据 | 否 | 是 | 未知 |
| [ColorfulClouds](https://open.caiyunapp.com/ColorfulClouds_Weather_API) | 天气数据 | `apiKey` | 是 | 是 |
| [Euskalmet](https://opendata.euskadi.eus/api-euskalmet/-/api-de-euskalmet/) | 巴斯克地区的气象数据 | `apiKey` | 是 | 未知 |
| [Foreca](https://developer.foreca.com) | 天气数据 | `OAuth` | 是 | 未知 |
| [HG Weather](https://hgbrasil.com/status/weather) | 提供巴西城市的天气预报数据 | `apiKey` | 是 | 是 |
| [Hong Kong Obervatory](https://www.hko.gov.hk/en/abouthko/opendata_intro.htm) | 提供天气信息、地震信息和气候数据 | 否 | 是 | 未知 |
| [Meteosource](https://www.meteosource.com/) | 基于机器学习和历史数据的全球天气预报 | `apiKey` | 是 | 未知 |
| [Met Office DataPoint](https://www.metoffice.gov.uk/services/data/datapoint/) | 英国的天气数据 | `apiKey` | 是 | 未知 |
| [Meteorologisk Institutt](https://api.met.no/weatherapi/documentation) | 天气和气候数据 | `User-Agent` | 是 | 未知 |
| [Micro Weather](https://m3o.com/weather/api) | 实时天气预报和历史数据 | `apiKey` | 是 | 未知 |
| [ODWeather](http://api.oceandrivers.com/static/docs.html) | 天气和天气网络摄像头 | 否 | 否 | 未知 |
| [Oikolab](https://docs.oikolab.com) | 来自NOAA和ECMWF的全球70多年的逐小时历史和预报天气数据 | `apiKey` | 是 | 是 |
| [Open-Meteo](https://open-meteo.com/) | 面向非商业用途的全球天气预报API | 否 | 是 | 是 |
| [openSenseMap](https://api.opensensemap.org/) | 个人气象站（称为senseBoxes）的数据 | 否 | 是 | 是 |
| [OpenUV](https://www.openuv.io) | 实时紫外线指数预报 | `apiKey` | 是 | 未知 |
| [OpenWeatherMap](https://openweathermap.org/api) | 天气数据 | `apiKey` | 是 | 未知 |
| [QWeather](https://dev.qweather.com/en/) | 基于位置的天气数据 | `apiKey` | 是 | 是 |
| [RainViewer](https://www.rainviewer.com/api.html) | 从互联网上不同网站收集的雷达数据 | 否 | 是 | 未知 |
| [Storm Glass](https://stormglass.io/) | 来自多个源的全球海洋天气 | `apiKey` | 是 | 是 |
| [Tomorrow](https://docs.tomorrow.io) | 使用专有技术提供的天气API | `apiKey` | 是 | 未知 |
| [US Weather](https://www.weather.gov/documentation/services-web-api) | 美国国家气象局 | 否 | 是 | 是 |
| [Visual Crossing](https://www.visualcrossing.com/weather-api) | 全球历史和天气预报数据 | `apiKey` | 是 | 是 |
| [weather-api](https://github.com/robertoduessmann/weather-api) | 一个用于检查天气的免费RESTful API | 否 | 是 | 否 |
| [WeatherAPI](https://www.weatherapi.com/) | 天气API，还包括天文和地理位置等其他功能 | `apiKey` | 是 | 是 |
| [Weatherbit](https://www.weatherbit.io/api) | 天气API | `apiKey` | 是 | 未知 |
| [Yandex.Weather](https://yandex.com/dev/weather/) | 评估特定位置的天气状况的API | `apiKey` | 是 | 否 |

**[⬆ 返回目录](#目录)**

### 国内物流

| API | 描述 | 认证方式 | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [快递100](https://api.kuaidi100.com/home) | 提供多家快递公司的物流信息查询服务 | `apiKey` | 是 | 未知 |
| [51Tracking](https://www.51tracking.com/) | 提供全球快递物流查询服务 | `apiKey` | 是 | 未知 |
| [快递鸟](https://www.kdniao.com/) | 提供多家物流公司的实时物流信息查询 | `apiKey` | 是 | 未知 |
| [菜鸟](https://open.cainiao.com/) | 支持多种物流服务和跨境物流解决方案 | `apiKey` | 是 | 未知 |
| [顺丰速运 (SF Express)](https://open.sf-express.com) | 顺丰快递服务和物流解决方案 | `apiKey` | 是 | 未知 |
| [京东物流 (JD Logistics)](https://open.jdl.com) | 京东物流服务和解决方案 | `apiKey` | 是 | 未知 |
| [极兔速递](https://open.jtexpress.com.cn) | 极兔包裹追踪、运费计算等服务 | `apiKey` | 是 | 未知 |
| [中通快递 (ZTO Express)](http://open.zto.com) | 中通快递服务和物流解决方案 | `apiKey` | 是 | 未知 |
| [圆通速递 (YTO Express)](http://open.yto.net.cn) | 圆通快递服务和物流解决方案 | `apiKey` | 是 | 未知 |
| [申通快递 (STO Express)](http://open.sto.cn) | 申通快递服务和物流解决方案 | `apiKey` | 是 | 未知 |
| [韵达快递 (Yunda Express)](http://open.yundaex.com) | 韵达快递服务和物流解决方案 | `apiKey` | 是 | 未知 |
| [百世快递 (Best Express)](https://open.800best.com/) | 百世快递服务和物流解决方案 | `apiKey` | 是 | 未知 |
| [德邦物流 (Deppon Logistics)](https://dpopen.deppon.com) | 德邦物流服务和解决方案 | `apiKey` | 是 | 未知 |
| [邮政速递物流 (EMS)](https://api.ems.com.cn) | 邮政速递服务 | `apiKey` | 是 | 未知 |

**[⬆ 返回目录](#目录)**

### 国际物流

| API | 描述 | 认证方式 | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [AfterShip](https://www.aftership.com/docs) | 支持超过200家物流公司的物流跟踪和通知 | `apiKey` | 是 | 未知 |
| [Ship24](https://www.ship24.com/zh/couriers) | 提供多家物流公司的全球包裹追踪服务 | `apiKey` | 是 | 未知 |
| [Aramex](https://www.aramex.com/us/en/developers) | Aramex快递提供的运费计算、包裹追踪等服务 | `apiKey` | 是 | 未知 |
| [UPS](https://www.ups.com/cn/zh/business-solutions/expand-your-online-business/upgrade-digital-technology/developer-resource-center.page) | UPS快递的提供包裹追踪、运费计算等服务 | `apiKey` | 是 | 未知 |
| [FedEx](https://www.fedex.com/en-us/developer/web-services.html) | 提供物流解决方案和包裹追踪服务 | `apiKey` | 是 | 未知 |
| [DHL](https://developer.dhl.com/) | DHL的API服务，包括追踪和计费 | `apiKey` | 是 | 未知 |
| [USPS](https://www.usps.com/business/web-tools-apis/) | 美国邮政服务API，提供多种物流服务 | `apiKey` | 是 | 未知 |
| [Royal Mail](https://www.royalmail.com/business/tools-services/apis) | 英国皇家邮政的包裹追踪等服务 | `apiKey` | 是 | 未知 |
| [AusPost](https://developers.auspost.com.au/) | 澳大利亚邮政的API服务，提供追踪等 | `apiKey` | 是 | 未知 |
| [Canada Post](https://www.canadapost-postescanada.ca/info/mc/business/productsservices/developers/tour/howitworks.jsf) | 加拿大邮政的API服务，包括追踪和计费 | `apiKey` | 是 | 未知 |
| [New Zealand Post](https://www.nzpost.co.nz/business/ecommerce/developer-resource-centre) | 新西兰邮政的API服务，提供追踪等 | `apiKey` | 是 | 未知 |

**[⬆ 返回目录](#目录)**


### 视频
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [An API of Ice And Fire](https://anapioficeandfire.com/) | 权力的游戏API | No | Yes | Unknown |
| [Bob's Burgers](https://bobs-burgers-api-ui.herokuapp.com) | Bob's汉堡店API | No | Yes | Yes |
| [Breaking Bad](https://breakingbadapi.com/documentation) | 绝命毒师API | No | Yes | Unknown |
| [Breaking Bad Quotes](https://github.com/shevabam/breaking-bad-quotes) | 一些绝命毒师语录 | No | Yes | Unknown |
| [Catalogopolis](https://api.catalogopolis.xyz/docs/) | 神秘博士API | No | Yes | Unknown |
| [Catch The Show](https://catchtheshow.herokuapp.com/api/documentation) | next-episode.net的REST API | No | Yes | Unknown |
| [Czech Television](http://www.ceskatelevize.cz/xml/tv-program/) | 捷克电视台的电视节目 | No | No | Unknown |
| [Dailymotion](https://developer.dailymotion.com/) | Dailymotion开发者API | `OAuth` | Yes | Unknown |
| [Dune](https://github.com/ywalia01/dune-api) | 一个简单的API，提供书籍、角色、电影和语录的JSON数据 | No | Yes | Yes |
| [Final Space](https://finalspaceapi.com/docs/) | 终极空间API | No | Yes | Yes |
| [Game of Thrones Quotes](https://gameofthronesquotes.xyz/) | 一些权力的游戏语录 | No | Yes | Unknown |
| [Harry Potter Characters](https://hp-api.herokuapp.com/) | 哈利波特角色数据，包含图像 | No | Yes | Unknown |
| [IMDb-API](https://imdb-api.com/) | 接收电影、剧集和演员信息的API | `apiKey` | Yes | Unknown |
| [IMDbOT](https://github.com/SpEcHiDe/IMDbOT) | 非官方的IMDb电影/系列信息 | No | Yes | Yes |
| [JSON2Video](https://json2video.com) | 以编程方式创建和编辑视频：水印、调整大小、幻灯片、语音、文字动画 | `apiKey` | Yes | No |
| [Lucifer Quotes](https://github.com/shadowoff09/lucifer-quotes) | 返回路西法语录 | No | Yes | Unknown |
| [MCU Countdown](https://github.com/DiljotSG/MCU-Countdown) | 下一个MCU电影倒计时 | No | Yes | Yes |
| [Motivational Quotes](https://nodejs-quoteapp.herokuapp.com/) | 随机励志语录 | No | Yes | Unknown |
| [Movie Quote](https://github.com/F4R4N/movie-quote/) | 随机电影和剧集语录 | No | Yes | Yes |
| [Open Movie Database](http://www.omdbapi.com/) | 电影信息 | `apiKey` | Yes | Unknown |
| [Owen Wilson Wow](https://owen-wilson-wow-api.herokuapp.com) | 演员Owen Wilson在电影中"wow"感叹的API | No | Yes | Yes |
| [Ron Swanson Quotes](https://github.com/jamesseanwright/ron-swanson-quotes#ron-swanson-quotes-api) | 电视节目 | No | Yes | Unknown |
| [Simkl](https://simkl.docs.apiary.io) | 电影、电视和动漫数据 | `apiKey` | Yes | Unknown |
| [STAPI](http://stapi.co) | 所有星际迷航信息 | No | No | No |
| [Stranger Things Quotes](https://github.com/shadowoff09/strangerthings-quotes) | 返回怪奇物语语录 | No | Yes | Unknown |
| [Stream](https://api.stream.cz/graphiql) | 捷克互联网电视、电影、剧集和免费在线视频 | No | Yes | No |
| [Stromberg Quotes](https://www.stromberg-api.de/) | 返回Stromberg语录及更多内容 | No | Yes | Unknown |
| [SWAPI](https://swapi.dev/) | 你想要的所有星球大战数据 | No | Yes | Yes |
| [SWAPI](https://www.swapi.tech) | 所有星球大战事物 | No | Yes | Yes |
| [SWAPI GraphQL](https://graphql.org/swapi-graphql) | 星球大战GraphQL API | No | Yes | Unknown |
| [The Lord of the Rings](https://the-one-api.dev/) | 指环王API | `apiKey` | Yes | Unknown |
| [The Vampire Diaries](https://vampire-diaries-api.netlify.app/) | 电视剧数据 | `apiKey` | Yes | Yes |
| [ThronesApi](https://thronesapi.com/) | 权力的游戏角色数据，包含图像 | No | Yes | Unknown |
| [TMDb](https://www.themoviedb.org/documentation/api) | 社区电影数据 | `apiKey` | Yes | Unknown |
| [TrailerAddict](https://www.traileraddict.com/trailerapi) | 轻松从TrailerAddict嵌入预告片 | `apiKey` | No | Unknown |
| [Trakt](https://trakt.docs.apiary.io/) | 电影和电视数据 | `apiKey` | Yes | Yes |
| [TVDB](https://thetvdb.com/api-information) | 电视数据 | `apiKey` | Yes | Unknown |
| [TVMaze](http://www.tvmaze.com/api) | 电视剧数据 | No | No | Unknown |
| [uNoGS](https://rapidapi.com/unogs/api/unogsng) | 非官方的Netflix在线全球搜索，一个地方搜索所有Netflix地区 | `apiKey` | Yes | Yes |
| [Vimeo](https://developer.vimeo.com/) | Vimeo开发者API | `OAuth` | Yes | Unknown |
| [Watchmode](https://api.watchmode.com/) | 查找电影和节目流媒体可用性的API | `apiKey` | Yes | Unknown |
| [Web Series Quotes Generator](https://github.com/yogeshwaran01/web-series-quotes) | API生成各种网络剧集语录图片 | No | Yes | Yes |
| [YouTube](https://developers.google.com/youtube/) | 为您的网站和应用添加YouTube功能 | `OAuth` | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 车辆
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Brazilian Vehicles and Prices](https://deividfortuna.github.io/fipe/) | 来自经济研究所基金会(Fipe)的车辆信息 | No | Yes | No |
| [Helipaddy sites](https://helipaddy.com/api/) | 直升机和客运无人机着陆点目录、Helipaddy数据及更多 | `apiKey` | Yes | Unknown |
| [Kelley Blue Book](http://developer.kbb.com/#!/data/1-Default) | 车辆信息、价格、配置及更多 | `apiKey` | Yes | No |
| [Mercedes-Benz](https://developer.mercedes-benz.com/apis) | 远程信息处理数据、远程访问车辆功能、汽车配置器、定位服务经销商 | `apiKey` | Yes | No |
| [NHTSA](https://vpic.nhtsa.dot.gov/api/) | NHTSA产品目录和车辆列表 | No | Yes | Unknown |
| [Smartcar](https://smartcar.com/docs/) | 锁定和解锁车辆，获取里程表读数和位置等数据。适用于大多数新车 | `OAuth` | Yes | Yes |

**[⬆ 返回目录](#index)**


### URL 缩短服务
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [1pt](https://github.com/1pt-co/api/blob/main/README.md) | 简单的URL缩短服务 | No | Yes | Yes |
| [Bitly](http://dev.bitly.com/get_started.html) | URL缩短和链接管理 | `OAuth` | Yes | Unknown |
| [CleanURI](https://cleanuri.com/docs) | URL缩短服务 | No | Yes | Yes |
| [ClickMeter](https://support.clickmeter.com/hc/en-us/categories/201474986) | 监控、比较和优化您的营销链接 | `apiKey` | Yes | Unknown |
| [Clico](https://cli.com/swagger-ui/index.html?configUrl=/v3/api-docs/swagger-config) | URL缩短服务 | `apiKey` | Yes | Unknown |
| [Cutt.ly](https://cutt.ly/api-documentation/cuttly-links-api) | URL缩短服务 | `apiKey` | Yes | Unknown |
| [Drivet URL Shortener](https://wiki.drivet.xyz/en/url-shortener/add-links) | 快速简便地缩短长URL | No | Yes | Unknown |
| [Free Url Shortener](https://ulvis.net/developer.html) | 免费URL缩短服务提供强大的API与其他网站交互 | No | Yes | Yes |
| [Git.io](https://github.blog/2011-11-10-git-io-github-url-shortener/) | Git.io URL缩短服务 | No | Yes | Unknown |
| [GoTiny](https://github.com/robvanbakel/gotiny-api) | 轻量级URL缩短服务，专注于开发者和终端用户的易用性 | No | Yes | Yes |
| [Kutt](https://docs.kutt.it/) | 免费现代URL缩短服务 | `apiKey` | Yes | Yes |
| [Mgnet.me](http://mgnet.me/api.html) | Torrent URL缩短API | No | Yes | No |
| [owo](https://owo.vc/api) | 简单的链接混淆器/缩短器 | No | Yes | Unknown |
| [Rebrandly](https://developers.rebrandly.com/v1/docs) | 用于分享品牌链接的自定义URL缩短服务 | `apiKey` | Yes | Unknown |
| [Short Link](https://github.com/FayasNoushad/Short-Link-API) | 短URL支持多种域名 | No | Yes | Unknown |
| [Shrtcode](https://shrtco.de/docs) | 支持多个域名的URL缩短服务 | No | Yes | Yes |
| [Shrtlnk](https://shrtlnk.dev/developer) | 简单高效的短链接创建 | `apiKey` | Yes | Yes |
| [TinyURL](https://tinyurl.com/app/dev) | 缩短长URL | `apiKey` | Yes | No |
| [UrlBae](https://urlbae.com/developers) | 简单高效的短链接创建 | `apiKey` | Yes | Yes |

**[⬆ 返回目录](#index)**


### 交通
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [ADS-B Exchange](https://www.adsbexchange.com/data/) | 获取所有空中飞机的实时和历史数据 | No | Yes | Unknown |
| [airportsapi](https://airport-web.appspot.com/api/docs/) | 通过ICAO代码获取机场名称和网站URL | No | Yes | Unknown |
| [AIS Hub](http://www.aishub.net/api) | 配备AIS跟踪系统的任何海洋和内陆船只的实时数据 | `apiKey` | No | Unknown |
| [Amadeus for Developers](https://developers.amadeus.com/self-service) | 旅行搜索 - 有限使用 | `OAuth` | Yes | Unknown |
| [apilayer aviationstack](https://aviationstack.com/) | 实时航班状态和全球航空数据API | `OAuth` | Yes | Unknown |
| [AviationAPI](https://docs.aviationapi.com) | FAA航空图表和出版物、机场信息和机场天气 | No | Yes | No |
| [AZ511](https://www.az511.com/developers/doc) | 从ADOT API获取交通数据 | `apiKey` | Yes | Unknown |
| [Bay Area Rapid Transit](http://api.bart.gov) | BART站点和预计到达时间 | `apiKey` | No | Unknown |
| [BC Ferries](https://www.bcferriesapi.ca) | BC Ferries的航行时间和载客量 | No | Yes | Yes |
| [BIC-Boxtech](https://docs.bic-boxtech.org/) | 全球集装箱船队的集装箱技术详情 | `OAuth` | Yes | Unknown |
| [BlaBlaCar](https://dev.blablacar.com) | 搜索拼车行程 | `apiKey` | Yes | Unknown |
| [Boston MBTA Transit](https://www.mbta.com/developers/v3-api) | MBTA站点和预计到达时间 | `apiKey` | Yes | Unknown |
| [Community Transit](https://github.com/transitland/transitland-datastore/blob/master/README.md#api-endpoints) | Transitland API | No | Yes | Unknown |
| [Compare Flight Prices](https://rapidapi.com/obryan-software-obryan-software-default/api/compare-flight-prices/) | 跨平台比较航班价格的API | `apiKey` | Yes | Unknown |
| [CTS](https://api.cts-strasbourg.eu/) | CTS实时API | `apiKey` | Yes | Yes |
| [Grab](https://developer.grab.com/docs/) | 跟踪配送、乘车费用、支付和积分 | `OAuth` | Yes | Unknown |
| [GraphHopper](https://docs.graphhopper.com/) | A到B路线规划，带逐步导航指引 | `apiKey` | Yes | Unknown |
| [Icelandic APIs](http://docs.apis.is/) | 提供冰岛相关服务的开放API | No | Yes | Unknown |
| [Impala Hotel Bookings](https://docs.impala.travel/docs/booking-api/) | 酒店内容、价格和房间预订 | `apiKey` | Yes | No |
| [Izi](http://api-docs.izi.travel/) | 旅行者语音导览 | `apiKey` | Yes | Unknown |
| [Land Transport Authority DataMall, Singapore](https://datamall.lta.gov.sg/content/dam/datamall/datasets/LTA_DataMall_API_User_Guide.pdf) | 新加坡交通信息 | `apiKey` | No | Unknown |
| [Metro Lisboa](http://app.metrolisboa.pt/status/getLinhas.php) | 地铁线路延误情况 | No | No | No |
| [Navitia](https://doc.navitia.io/) | 用于构建交通应用的开放API | `apiKey` | Yes | Unknown |
| [Open Charge Map](https://openchargemap.org/site/develop/api) | 全球电动汽车充电站公共注册表 | `apiKey` | Yes | Yes |
| [OpenSky Network](https://opensky-network.org/apidoc/index.html) | 免费实时ADS-B航空数据 | No | Yes | Unknown |
| [Railway Transport for France](https://www.digital.sncf.com/startup/api) | SNCF公共API | `apiKey` | Yes | Unknown |
| [REFUGE Restrooms](https://www.refugerestrooms.org/api/docs/#!/restrooms) | 为跨性别者、双性人和性别非常规者提供安全的洗手间访问 | No | Yes | Unknown |
| [Sabre for Developers](https://developer.sabre.com/guides/travel-agency/quickstart/getting-started-in-travel) | 旅行搜索 - 有限使用 | `apiKey` | Yes | Unknown |
| [Schiphol Airport](https://developer.schiphol.nl/) | 史基浦机场 | `apiKey` | Yes | Unknown |
| [Tankerkoenig](https://creativecommons.tankerkoenig.de/swagger/) | 德国实时汽油/柴油价格 | `apiKey` | Yes | Yes |
| [TransitLand](https://www.transit.land/documentation/datastore/api-endpoints.html) | 交通聚合 | No | Yes | Unknown |
| [Transport for Atlanta, US](http://www.itsmarta.com/app-developer-resources.aspx) | Marta | No | No | Unknown |
| [Transport for Auckland, New Zealand](https://dev-portal.at.govt.nz/) | 奥克兰交通 | No | Yes | Unknown |
| [Transport for Belgium](https://docs.irail.be/) | iRail API是比利时公共交通的第三方API | No | Yes | Yes |
| [Transport for Berlin, Germany](https://github.com/derhuerst/vbb-rest/blob/3/docs/index.md) | 第三方VBB API | No | Yes | Unknown |
| [Transport for Bordeaux, France](https://opendata.bordeaux-metropole.fr/explore/) | 波尔多都会区公共交通及更多服务（法国） | `apiKey` | Yes | Unknown |
| [Transport for Budapest, Hungary](https://bkkfutar.docs.apiary.io) | 布达佩斯公共交通API | No | Yes | Unknown |
| [Transport for Chicago, US](http://www.transitchicago.com/developers/) | 芝加哥交通局（CTA） | `apiKey` | No | Unknown |
| [Transport for Czech Republic](https://www.chaps.cz/eng/products/idos-internet) | 捷克交通API | No | Yes | Unknown |
| [Transport for Denver, US](http://www.rtd-denver.com/gtfs-developer-guide.shtml) | RTD | No | No | Unknown |
| [Transport for Finland](https://digitransit.fi/en/developers/ ) | 芬兰交通API | No | Yes | Unknown |
| [Transport for Germany](http://data.deutschebahn.com/dataset/api-fahrplan) | 德国铁路（DB）API | `apiKey` | No | Unknown |
| [Transport for Grenoble, France](https://www.mobilites-m.fr/pages/opendata/OpenDataApi.html) | 格勒诺布尔公共交通 | No | No | No |
| [Transport for Hessen, Germany](https://opendata.rmv.de/site/start.html) | RMV API（黑森州公共交通） | No | Yes | Unknown |
| [Transport for Honolulu, US](http://hea.thebus.org/api_info.asp) | 檀香山交通信息 | `apiKey` | No | Unknown |
| [Transport for Lisbon, Portugal](https://emel.city-platform.com/opendata/) | 关于公交路线、停车和交通的数据 | `apiKey` | Yes | Unknown |
| [Transport for London, England](https://api.tfl.gov.uk) | TfL API | `apiKey` | Yes | Unknown |
| [Transport for Los Angeles, US](https://developer.metro.net/api/) | 关于Metro车辆实时位置和路线的数据 | No | Yes | Unknown |
| [Transport for Manchester, England](https://developer.tfgm.com/) | TfGM交通网络数据 | `apiKey` | Yes | No |
| [Transport for Norway](https://developer.entur.org/) | 挪威交通API和数据集 | No | Yes | Unknown |
| [Transport for Ottawa, Canada](https://www.octranspo.com/en/plan-your-trip/travel-tools/developers) | OC Transpo API | `apiKey` | Yes | Unknown |
| [Transport for Paris, France](http://data.ratp.fr/api/v1/console/datasets/1.0/search/) | RATP开放数据API | No | No | Unknown |
| [Transport for Philadelphia, US](http://www3.septa.org/hackathon/) | SEPTA APIs | No | No | Unknown |
| [Transport for Sao Paulo, Brazil](http://www.sptrans.com.br/desenvolvedores/api-do-olho-vivo-guia-de-referencia/documentacao-api/) | SPTrans | `OAuth` | No | Unknown |
| [Transport for Spain](https://data.renfe.com/api/1/util/snippet/api_info.html?resource_id=a2368cff-1562-4dde-8466-9635ea3a572a) | 西班牙公共火车 | No | Yes | Unknown |
| [Transport for Sweden](https://www.trafiklab.se/api) | 公共交通消费者 | `OAuth` | Yes | Unknown |
| [Transport for Switzerland](https://opentransportdata.swiss/en/) | 瑞士官方公共交通开放数据 | `apiKey` | Yes | Unknown |
| [Transport for Switzerland](https://transport.opendata.ch/) | 瑞士公共交通API | No | Yes | Unknown |
| [Transport for The Netherlands](http://www.ns.nl/reisinformatie/ns-api) | NS，仅火车 | `apiKey` | No | Unknown |
| [Transport for The Netherlands](https://github.com/skywave/KV78Turbo-OVAPI/wiki) | OVAPI，全国公共交通 | No | Yes | Unknown |
| [Transport for Toronto, Canada](https://myttc.ca/developers) | TTC | No | Yes | Unknown |
| [Transport for UK](https://developer.transportapi.com) | 英国交通API和数据集 | `apiKey` | Yes | Unknown |
| [Transport for United States](https://retro.umoiq.com/xmlFeedDocs/NextBusXMLFeed.pdf) | NextBus API | No | No | Unknown |
| [Transport for Vancouver, Canada](https://developer.translink.ca/) | TransLink | `OAuth` | Yes | Unknown |
| [Transport for Washington, US](https://developer.wmata.com/) | 华盛顿地铁交通API | `OAuth` | Yes | Unknown |
| [transport.rest](https://transport.rest) | 社区维护的开发者友好公共交通API | No | Yes | Yes |
| [Tripadvisor](https://developer-tripadvisor.com/home/) | 酒店、餐厅、景点或目的地的评分内容 | `apiKey` | Yes | Unknown |
| [Uber](https://developer.uber.com/products) | Uber乘车请求和价格估算 | `OAuth` | Yes | Yes |
| [Velib metropolis, Paris, France](https://www.velib-metropole.fr/donnees-open-data-gbfs-du-service-velib-metropole) | Velib开放数据API | No | Yes | No |

**[⬆ 返回目录](#index)**


### 跟踪
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Aftership](https://developers.aftership.com/reference/quick-start) | 高效更新、管理和跟踪货物的API | `apiKey` | Yes | Yes |
| [Correios](https://cws.correios.com.br/ajuda) | 使用Correios服务提供信息和准备运输的集成 | `apiKey` | Yes | Unknown |
| [Pixela](https://pixe.la) | 用于记录和跟踪习惯、努力或日常事务的API | `X-Mashape-Key` | Yes | Yes |
| [PostalPinCode](http://www.postalpincode.in/Api-Details) | 获取印度Pincode详情的API | No | Yes | Unknown |
| [Postmon](http://postmon.com.br) | 简单、快速、免费查询巴西邮政编码和订单的API | No | No | Unknown |
| [PostNord](https://developer.postnord.com/api) | 提供瑞典和丹麦运输中包裹信息 | `apiKey` | No | Unknown |
| [UPS](https://www.ups.com/upsdeveloperkit) | 货物和地址信息 | `apiKey` | Yes | Unknown |
| [WeCanTrack](https://docs.wecantrack.com) | 自动在联盟链接中放置subid，将联盟转化归因到点击数据 | `apiKey` | Yes | Yes |
| [WhatPulse](https://developer.whatpulse.org/#web-api) | 测量键盘/鼠标使用情况的小型应用程序 | No | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 文本分析
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Code Detection API](https://codedetectionapi.runtime.dev) | 检测、标记、格式化和丰富您的应用程序或数据管道中的代码 | `OAuth` | Yes | Unknown |
| [apilayer languagelayer](https://languagelayer.com/) | 支持173种语言的语言检测JSON API | `OAuth` | Yes | Unknown |
| [Aylien Text Analysis](https://docs.aylien.com/textapi/#getting-started) | 信息检索和自然语言API的集合 | `apiKey` | Yes | Unknown |
| [Cloudmersive Natural Language Processing](https://www.cloudmersive.com/nlp-api) | 自然语言处理和文本分析 | `apiKey` | Yes | Yes |
| [Detect Language](https://detectlanguage.com/) | 检测文本语言 | `apiKey` | Yes | Unknown |
| [ELI](https://nlp.insightera.co.th/docs/v1.0) | 泰语自然语言处理工具 | `apiKey` | Yes | Unknown |
| [Google Cloud Natural](https://cloud.google.com/natural-language/docs/) | 自然语言理解技术，包括情感、实体和句法分析 | `apiKey` | Yes | Unknown |
| [Hirak OCR](https://ocr.hirak.site/) | 图像转文本 - 来自图像的文字识别，支持100多种语言，准确，无限请求 | `apiKey` | Yes | Unknown |
| [Hirak Translation](https://translate.hirak.site/) | 在21种最常用语言之间翻译，准确，无限请求 | `apiKey` | Yes | Unknown |
| [Lecto Translation](https://rapidapi.com/lecto-lecto-default/api/lecto-translation/) | 具有免费套餐和合理价格的翻译API | `apiKey` | Yes | Yes |
| [LibreTranslate](https://libretranslate.com/docs) | 拥有17种可用语言的翻译工具 | No | Yes | Unknown |
| [Semantria](https://semantria.readme.io/docs) | 具有情感分析、分类和命名实体提取的文本分析 | `OAuth` | Yes | Unknown |
| [Sentiment Analysis](https://www.meaningcloud.com/developer/sentiment-analysis) | 来自不同来源文本的多语言情感分析 | `apiKey` | Yes | Yes |
| [Tisane](https://tisane.ai/) | 专注于检测滥用内容和执法应用的文本分析 | `OAuth` | Yes | Yes |
| [Watson Natural Language Understanding](https://cloud.ibm.com/apidocs/natural-language-understanding/natural-language-understanding) | 用于高级文本分析的自然语言处理 | `OAuth` | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 测试数据
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Bacon Ipsum](https://baconipsum.com/json-api/) | 更丰富的Lorem Ipsum生成器 | No | Yes | Unknown |
| [Dicebear Avatars](https://avatars.dicebear.com/) | 生成随机像素艺术头像 | No | Yes | No |
| [English Random Words](https://random-words-api.vercel.app/word) | 生成带发音的英语随机单词 | No | Yes | No |
| [FakeJSON](https://fakejson.com) | 生成测试和虚假数据的服务 | `apiKey` | Yes | Yes |
| [FakerAPI](https://fakerapi.it/en) | 获取虚假数据的API集合 | No | Yes | Yes |
| [FakeStoreAPI](https://fakestoreapi.com/) | 用于电子商务或购物网站原型的虚假商店REST API | No | Yes | Unknown |
| [GeneradorDNI](https://api.generadordni.es) | 数据生成器API。个人信息、车辆、银行和卡片等 | `apiKey` | Yes | Unknown |
| [ItsThisForThat](https://itsthisforthat.com/api.php) | 生成随机创业想法 | No | Yes | No |
| [JSONPlaceholder](http://jsonplaceholder.typicode.com/) | 用于测试和原型制作的虚假数据 | No | No | Unknown |
| [Loripsum](http://loripsum.net/) | 不那么糟糕的"lorem ipsum"生成器 | No | No | Unknown |
| [Mailsac](https://mailsac.com/docs/api) | 一次性电子邮件 | `apiKey` | Yes | Unknown |
| [Metaphorsum](http://metaphorpsum.com/) | 根据字数和句子数生成演示段落 | No | No | Unknown |
| [Mockaroo](https://www.mockaroo.com/docs) | 生成JSON、CSV、TXT、SQL和XML格式的虚假数据 | `apiKey` | Yes | Unknown |
| [QuickMocker](https://quickmocker.com) | API模拟工具，生成上下文、虚假或随机数据 | No | Yes | Yes |
| [Random Data](https://random-data-api.com) | 随机数据生成器 | No | Yes | Unknown |
| [Randommer](https://randommer.io/randommer-api) | 随机数据生成器 | `apiKey` | Yes | Yes |
| [RandomUser](https://randomuser.me) | 生成和列出用户数据 | No | Yes | Unknown |
| [RoboHash](https://robohash.org/) | 生成随机机器人/外星人头像 | No | Yes | Unknown |
| [Spanish random names](https://random-names-api.herokuapp.com/public) | 随机生成西班牙语名字（带性别） | No | Yes | Unknown |
| [Spanish random words](https://palabras-aleatorias-public-api.herokuapp.com) | 随机生成西班牙语单词 | No | Yes | Unknown |
| [This Person Does not Exist](https://thispersondoesnotexist.com) | 生成不存在的人的真实面孔 | No | Yes | Unknown |
| [Toolcarton](https://testimonialapi.toolcarton.com/) | 生成随机推荐数据 | No | Yes | Unknown |
| [UUID Generator](https://www.uuidtools.com/docs) | 生成UUID | No | Yes | No |
| [What The Commit](http://whatthecommit.com/index.txt) | 随机提交消息生成器 | No | No | Yes |
| [Yes No](https://yesno.wtf/api) | 随机生成是或否 | No | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 体育与健身
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [API-FOOTBALL](https://www.api-football.com/documentation-v3) | 获取足球联赛和杯赛信息 | `apiKey` | Yes | Yes |
| [ApiMedic](https://apimedic.com/) | ApiMedic提供主要面向患者的医疗症状检查API | `apiKey` | Yes | Unknown |
| [balldontlie](https://www.balldontlie.io) | Balldontlie提供访问NBA统计数据 | No | Yes | Yes |
| [Canadian Football League (CFL)](http://api.cfl.ca/) | 官方JSON API，提供CFL的实时联赛、球队和球员统计 | `apiKey` | Yes | No |
| [City Bikes](https://api.citybik.es/v2/) | 世界各地的城市自行车 | No | Yes | Unknown |
| [Cloudbet](https://www.cloudbet.com/api/) | 官方Cloudbet API提供实时体育赔率和投注API，可编程下注 | `apiKey` | Yes | Yes |
| [CollegeFootballData.com](https://collegefootballdata.com) | 非官方的美国大学橄榄球详细统计、记录和结果API | `apiKey` | Yes | Unknown |
| [Ergast F1](http://ergast.com/mrd/) | 从1950年世界锦标赛开始的F1数据 | No | Yes | Unknown |
| [Fitbit](https://dev.fitbit.com/) | Fitbit信息 | `OAuth` | Yes | Unknown |
| [Football](https://rapidapi.com/GiulianoCrescimbeni/api/football98/) | 简单的开源足球API，获取球队统计、最佳射手等 | `X-Mashape-Key` | Yes | Unknown |
| [Football (Soccer) Videos](https://www.scorebat.com/video-api/) | 来自英超、德甲、意甲等联赛的进球和高光视频嵌入代码 | No | Yes | Yes |
| [Football Standings](https://github.com/azharimm/football-standings-api) | 显示足球积分榜如英超、西甲、意甲等。数据基于ESPN网站 | No | Yes | Yes |
| [Football-Data](https://www.football-data.org) | 足球数据，包含比赛信息、球员、球队和比赛 | `X-Mashape-Key` | Yes | Unknown |
| [JCDecaux Bike](https://developer.jcdecaux.com/) | JCDecaux的公共自行车 | `apiKey` | Yes | Unknown |
| [MLB Records and Stats](https://appac.github.io/mlb-data-api-docs/) | 当前和历史MLB统计 | No | No | Unknown |
| [NBA Data](https://rapidapi.com/api-sports/api/api-nba/) | 所有NBA统计数据、比赛、即时比分、积分榜、统计 | `apiKey` | Yes | Unknown |
| [NBA Stats](https://any-api.com/nba_com/nba_com/docs/API_Description) | 当前和历史NBA统计 | No | Yes | Unknown |
| [NHL Records and Stats](https://gitlab.com/dword4/nhlapi) | NHL历史数据和统计 | No | Yes | Unknown |
| [Oddsmagnet](https://data.oddsmagnet.com) | 来自多家英国博彩公司的赔率历史 | No | Yes | Yes |
| [OpenLigaDB](https://www.openligadb.de) | 众包体育联赛结果 | No | Yes | Yes |
| [Premier League Standings ](https://rapidapi.com/heisenbug/api/premier-league-live-scores/) | 当前所有英超积分榜和统计 | `apiKey` | Yes | Unknown |
| [Sport Data](https://sportdataapi.com) | 获取来自世界各地的体育数据 | `apiKey` | Yes | Unknown |
| [Sport List & Data](https://developers.decathlon.com/products/sports) | 体育列表和相关资源 | No | Yes | Yes |
| [Sport Places](https://developers.decathlon.com/products/sport-places) | 众包世界各地的运动场所 | No | Yes | No |
| [Sport Vision](https://developers.decathlon.com/products/sport-vision) | 识别图像中的运动、品牌和装备。还提供体育图像字幕功能 | `apiKey` | Yes | Yes |
| [Sportmonks Cricket](https://docs.sportmonks.com/cricket/) | 实时板球比分、球员统计和幻想API | `apiKey` | Yes | Unknown |
| [Sportmonks Football](https://docs.sportmonks.com/football/) | 足球比分/赛程、新闻API、电视频道、统计、历史、显示积分榜如英超、西甲 | `apiKey` | Yes | Unknown |
| [Squiggle](https://api.squiggle.com.au) | 澳大利亚橄榄球联盟比赛的赛程、结果和预测 | No | Yes | Yes |
| [Strava](https://strava.github.io/api/) | 与运动员、活动等连接 | `OAuth` | Yes | Unknown |
| [SuredBits](https://suredbits.com/api/) | 查询体育数据，包括球队、球员、比赛、比分和统计 | No | No | No |
| [TheSportsDB](https://www.thesportsdb.com/api.php) | 众包体育数据和艺术作品 | `apiKey` | Yes | Yes |
| [Tredict](https://www.tredict.com/blog/oauth_docs/) | 获取和设置活动、健康数据等 | `OAuth` | Yes | Unknown |
| [Wger](https://wger.de/en/software/api) | 锻炼管理器数据，如练习、肌肉或设备 | `apiKey` | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 社交
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|---|---|---|---|---|
| [4chan](https://github.com/4chan/4chan-API) | 简单的基于图像的公告板，专注于各种话题 | No | Yes | Yes |
| [Ayrshare](https://www.ayrshare.com) | 社交媒体API，用于发布、获取分析和管理多个用户的社交媒体账户 | `apiKey` | Yes | Yes |
| [aztro](https://aztro.sameerkumar.website/) | 昨天、今天和明天的每日星座运势 | No | Yes | Unknown |
| [Blogger](https://developers.google.com/blogger/) | Blogger API允许客户端应用程序查看和更新Blogger内容 | `OAuth` | Yes | Unknown |
| [Cisco Spark](https://developer.ciscospark.com) | 团队协作软件 | `OAuth` | Yes | Unknown |
| [Dangerous Discord Database](https://discord.riverside.rocks/docs/index.php) | 恶意Discord账户数据库 | `apiKey` | Yes | Unknown |
| [Discord](https://discord.com/developers/docs/intro) | 为Discord创建机器人，将Discord集成到外部平台 | `OAuth` | Yes | Unknown | | |
| [Disqus](https://disqus.com/api/docs/auth/) | 与Disqus数据通信 | `OAuth` | Yes | Unknown |
| [Doge-Meme](https://api.doge-meme.lol/docs) | 来自r/dogecoin的热门 meme 帖子，包含'Meme'标签 | No | Yes | Yes |
| [Facebook](https://developers.facebook.com/) | Facebook登录、在FB上分享、社交插件、分析等 | `OAuth` | Yes | Unknown |
| [Foursquare](https://developer.foursquare.com/) | 与Foursquare用户和地点交互（基于位置的打卡、照片、提示、活动等） | `OAuth` | Yes | Unknown |
| [Fuck Off as a Service](https://www.foaas.com) | 让某人滚蛋 | No | Yes | Unknown |
| [Full Contact](https://docs.fullcontact.com/) | 获取社交媒体个人资料和联系信息 | `OAuth` | Yes | Unknown |
| [HackerNews](https://github.com/HackerNews/API) | 面向计算机科学和创业的社会新闻 | No | Yes | Unknown |
| [Hashnode](https://hashnode.com) | 为开发者构建的博客平台 | No | Yes | Unknown |
| [Instagram](https://www.instagram.com/developer/) | Instagram登录、在Instagram上分享、社交插件等 | `OAuth` | Yes | Unknown |
| [Kakao](https://developers.kakao.com/) | Kakao登录、在KakaoTalk上分享、社交插件等 | `OAuth` | Yes | Unknown |
| [Lanyard](https://github.com/Phineas/lanyard) | 通过HTTP REST API或WebSocket检索您在Discord上的状态 | No | Yes | Yes |
| [Line](https://developers.line.biz/) | Line登录、在Line上分享、社交插件等 | `OAuth` | Yes | Unknown |
| [LinkedIn](https://docs.microsoft.com/en-us/linkedin/?context=linkedin/context) | 所有与LinkedIn数字集成的基础 | `OAuth` | Yes | Unknown |
| [Meetup.com](https://www.meetup.com/api/guide) | 来自Meetup.com的Meetup数据 | `apiKey` | Yes | Unknown |
| [Microsoft Graph](https://docs.microsoft.com/en-us/graph/api/overview) | 访问Microsoft 365、Windows 10和企业移动中的数据和智能 | `OAuth` | Yes | Unknown |
| [NAVER](https://developers.naver.com/main/) | NAVER登录、在NAVER上分享、社交插件等 | `OAuth` | Yes | Unknown |
| [Open Collective](https://docs.opencollective.com/help/developers/api) | 获取Open Collective数据 | No | Yes | Unknown |
| [Pinterest](https://developers.pinterest.com/) | 世界上创意的目录 | `OAuth` | Yes | Unknown |
| [Product Hunt](https://api.producthunt.com/v2/docs) | 技术领域最佳新产品 | `OAuth` | Yes | Unknown |
| [Reddit](https://www.reddit.com/dev/api) | 互联网首页 | `OAuth` | Yes | Unknown |
| [Revolt](https://developers.revolt.chat/api/) | Revolt开源Discord替代品 | `apiKey` | Yes | Unknown |
| [Saidit](https://www.saidit.net/dev/api) | 开源Reddit克隆 | `OAuth` | Yes | Unknown |
| [Slack](https://api.slack.com/) | 团队即时通讯 | `OAuth` | Yes | Unknown |
| [TamTam](https://dev.tamtam.chat/) | 与TamTam交互的Bot API | `apiKey` | Yes | Unknown |
| [Telegram Bot](https://core.telegram.org/bots/api) | 简化的MTProto API HTTP版本用于机器人 | `apiKey` | Yes | Unknown |
| [Telegram MTProto](https://core.telegram.org/api#getting-started) | 读写Telegram数据 | `OAuth` | Yes | Unknown |
| [Telegraph](https://telegra.ph/api) | 轻松创建吸引人的博客以分享 | `apiKey` | Yes | Unknown |
| [TikTok](https://developers.tiktok.com/doc/login-kit-web) | 获取用户信息和用户在TikTok平台上的视频帖子 | `OAuth` | Yes | Unknown |
| [Trash Nothing](https://trashnothing.com/developer) | 拥有每天数千件免费物品发布的免费回收社区 | `OAuth` | Yes | Yes |
| [Tumblr](https://www.tumblr.com/docs/en/api/v2) | 读写Tumblr数据 | `OAuth` | Yes | Unknown |
| [Twitch](https://dev.twitch.tv/docs) | 游戏流媒体API | `OAuth` | Yes | Unknown |
| [Twitter](https://developer.twitter.com/en/docs) | 读写Twitter数据 | `OAuth` | Yes | No |
| [SocialData API](https://socialdata.tools) | 读Twitter数据 | `apiKey` | 是 | 否 |
| [vk](https://vk.com/dev/sites) | 读写vk数据 | `OAuth` | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 购物
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Best Buy](https://bestbuyapis.github.io/api-documentation/#overview) | 产品、购买选项、分类、推荐、商店和商务 | `apiKey` | Yes | Unknown |
| [Digi-Key](https://www.digikey.com/en/resources/api-solutions) | 检索电子元件的价格和库存以及下订单 | `OAuth` | Yes | Unknown |
| [Dummy Products](https://dummyproducts-api.herokuapp.com/) | 用于获取带占位符图像的虚拟电子商务产品JSON数据的API | `apiKey` | Yes | Yes |
| [eBay](https://developer.ebay.com/) | 在eBay上买卖 | `OAuth` | Yes | Unknown |
| [Etsy](https://www.etsy.com/developers/documentation/getting_started/api_basics) | 管理商店并与列表交互 | `OAuth` | Yes | Unknown |
| [Flipkart Marketplace](https://seller.flipkart.com/api-docs/FMSAPI.html) | Flipkart Marketplace中的产品列表管理、订单履行 | `OAuth` | Yes | Yes |
| [Lazada](https://open.lazada.com/doc/doc.htm) | 检索产品评分和卖家绩效指标 | `apiKey` | Yes | Unknown |
| [Mercadolibre](https://developers.mercadolibre.cl/es_ar/api-docs-es) | 管理销售、广告、产品、服务和商店 | `apiKey` | Yes | Unknown |
| [Octopart](https://octopart.com/api/v4/reference) | 用于制造、设计和采购的电子元件数据 | `apiKey` | Yes | Unknown |
| [OLX Poland](https://developer.olx.pl/api/doc#section/) | 通过发布、管理广告和与OLX用户交流来与本地网站集成 | `apiKey` | Yes | Unknown |
| [Rappi](https://dev-portal.rappi.com/) | 管理Rappi应用中的订单 | `OAuth` | Yes | Unknown |
| [Shopee](https://open.shopee.com/documents?version=1) | Shopee官方API，用于集成Shopee的各种服务 | `apiKey` | Yes | Unknown |
| [Tokopedia](https://developer.tokopedia.com/openapi/guide/#/) | Tokopedia官方API，用于集成Tokopedia的各种服务 | `OAuth` | Yes | Unknown |
| [WooCommerce](https://woocommerce.github.io/woocommerce-rest-api-docs/) | WooCommerce REST API，用于在WordPress网站中创建、读取、更新和删除JSON格式的数据 | `apiKey` | Yes | Yes |

**[⬆ 返回目录](#index)**


### 安全
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Application Environment Verification](https://github.com/fingerprintjs/aev) | Android库和API，用于验证用户设备的安全性，检测root设备和其他风险 | `apiKey` | Yes | Yes |
| [BinaryEdge](https://docs.binaryedge.io/api-v2.html) | 提供对BinaryEdge 40fy扫描平台的访问 | `apiKey` | Yes | Yes |
| [BitWarden](https://bitwarden.com/help/api/) | 最佳开源密码管理器 | `OAuth` | Yes | Unknown |
| [Botd](https://github.com/fingerprintjs/botd) | Botd是一个用于JavaScript机器人检测的浏览器库 | `apiKey` | Yes | Yes |
| [Bugcrowd](https://docs.bugcrowd.com/api/getting-started/) | Bugcrowd API，用于以编程方式交互和跟踪报告的问题 | `apiKey` | Yes | Unknown |
| [Censys](https://search.censys.io/api) | 互联网连接主机和设备的搜索引擎 | `apiKey` | Yes | No |
| [Classify](https://classify-web.herokuapp.com/#/api) | 加密和解密文本消息 | No | Yes | Yes |
| [Complete Criminal Checks](https://completecriminalchecks.com/Developers) | 提供来自美国所有州和波多黎各的犯罪者数据 | `apiKey` | Yes | Yes |
| [CRXcavator](https://crxcavator.io/apidocs) | Chrome扩展风险评分 | `apiKey` | Yes | Unknown |
| [Dehash.lt](https://github.com/Dehash-lt/api) | 哈希解密MD5、SHA1、SHA3、SHA256、SHA384、SHA512 | No | Yes | Unknown |
| [EmailRep](https://docs.emailrep.io/) | 电子邮件地址威胁和风险预测 | No | Yes | Unknown |
| [Escape](https://github.com/polarspetroll/EscapeAPI) | 用于转义不同类型查询的API | No | Yes | No |
| [FilterLists](https://filterlists.com) | 广告拦截器和防火墙过滤器列表 | No | Yes | Unknown |
| [FingerprintJS Pro](https://dev.fingerprintjs.com/docs) | 提供高精度浏览器指纹识别的欺诈检测API | `apiKey` | Yes | Yes |
| [FraudLabs Pro](https://www.fraudlabspro.com/developer/api/screen-order) | 使用AI筛选订单信息以检测欺诈 | `apiKey` | Yes | Unknown |
| [FullHunt](https://api-docs.fullhunt.io/#introduction) | 可搜索的整个互联网攻击面数据库 | `apiKey` | Yes | Unknown |
| [GitGuardian](https://api.gitguardian.com/doc) | 扫描文件中的密钥（API密钥、数据库凭证） | `apiKey` | Yes | No |
| [GreyNoise](https://docs.greynoise.io/reference/get_v3-community-ip) | 查询GreyNoise数据集中的IP并检索完整IP上下文数据的子集 | `apiKey` | Yes | Unknown |
| [HackerOne](https://api.hackerone.com/) | 业界首个黑客API，帮助提高创意漏洞赏金猎人的工作效率 | `apiKey` | Yes | Unknown |
| [Hashable](https://hashable.space/pages/api/) | 访问高级加密功能和方法的REST API | No | Yes | Yes |
| [HaveIBeenPwned](https://haveibeenpwned.com/API/v3) | 以前在数据泄露中暴露过的密码 | `apiKey` | Yes | Unknown |
| [Intelligence X](https://github.com/IntelligenceX/SDK/blob/master/Intelligence%20X%20API.pdf) | 通过Intelligence X执行开源情报 | `apiKey` | Yes | Unknown |
| [LoginRadius](https://www.loginradius.com/docs/) | 托管用户认证服务 | `apiKey` | Yes | Yes |
| [Microsoft Security Response Center (MSRC)](https://msrc.microsoft.com/report/developer) | 与Microsoft安全响应中心(MSRC)交互的编程接口 | No | Yes | Unknown |
| [Mozilla http scanner](https://github.com/mozilla/http-observatory/blob/master/httpobs/docs/api.md) | Mozilla观测站HTTP扫描器 | No | Yes | Unknown |
| [Mozilla tls scanner](https://github.com/mozilla/tls-observatory#api-endpoints) | Mozilla观测站TLS扫描器 | No | Yes | Unknown |
| [National Vulnerability Database](https://nvd.nist.gov/vuln/Data-Feeds/JSON-feed-changelog) | 美国国家漏洞数据库 | No | Yes | Unknown |
| [Passwordinator](https://github.com/fawazsullia/password-generator/) | 生成不同复杂度的随机密码 | No | Yes | Yes |
| [PhishStats](https://phishstats.info/) | 网络钓鱼数据库 | No | Yes | Unknown |
| [Privacy.com](https://privacy.com/developer/docs) | 生成特定商家和一次性使用的信用卡号码，链接回您的银行 | `apiKey` | Yes | Unknown |
| [Pulsedive](https://pulsedive.com/api/) | 实时扫描、搜索和收集威胁情报数据 | `apiKey` | Yes | Unknown |
| [SecurityTrails](https://securitytrails.com/corp/apidocs) | 域名和IP相关信息，如当前和历史WHOIS和DNS记录 | `apiKey` | Yes | Unknown |
| [Shodan](https://developer.shodan.io/) | 互联网连接设备的搜索引擎 | `apiKey` | Yes | Unknown |
| [Spyse](https://spyse-dev.readme.io/reference/quick-start) | 访问所有互联网资产数据，构建强大的攻击面管理应用程序 | `apiKey` | Yes | Unknown |
| [Threat Jammer](https://threatjammer.com/docs/index) | 来自策划威胁情报数据的风险评分服务 | `apiKey` | Yes | Unknown |
| [UK Police](https://data.police.uk/docs/) | 英国警察数据 | No | Yes | Unknown |
| [Virushee](https://api.virushee.com/) | Virushee文件/数据扫描 | No | Yes | Yes |
| [VulDB](https://vuldb.com/?doc.api) | VulDB API允许对一个或多个项目发起查询以及交易机器人 | `apiKey` | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 科学与数学
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [arcsecond.io](https://api.arcsecond.io/) | 多个天文学数据源 | No | Yes | Unknown |
| [arXiv](https://arxiv.org/help/api/user-manual) | 策划的研究共享平台：物理、数学、定量金融和经济学 | No | Yes | Unknown |
| [CORE](https://core.ac.uk/services#api) | 访问世界上开放获取的研究论文 | `apiKey` | Yes | Unknown |
| [GBIF](https://www.gbif.org/developer/summary) | 全球生物多样性信息设施 | No | Yes | Yes |
| [iDigBio](https://github.com/idigbio/idigbio-search-api/wiki) | 访问来自世界各地组织的数百万博物馆标本 | No | Yes | Unknown |
| [inspirehep.net](https://github.com/inspirehep/rest-api-doc) | 高能物理信息系统 | No | Yes | Unknown |
| [isEven (humor)](https://isevenapi.xyz/) | 检查一个数字是否为偶数 | No | Yes | Unknown |
| [ISRO](https://isro.vercel.app) | ISRO航天器信息 | No | Yes | No |
| [ITIS](https://www.itis.gov/ws_description.html) | 综合分类信息系统 | No | Yes | Unknown |
| [Launch Library 2](https://thespacedevs.com/llapi) | 航天发射和事件数据库 | No | Yes | Yes |
| [Materials Platform for Data Science](https://mpds.io) | 策划的材料科学实验数据 | `apiKey` | Yes | No |
| [Minor Planet Center](http://www.asterank.com/mpc) | Asterank.com信息 | No | No | Unknown |
| [NASA](https://api.nasa.gov) | NASA数据，包括图像 | No | Yes | No |
| [NASA ADS](https://ui.adsabs.harvard.edu/help/api/api-docs.html) | NASA天体物理数据系统 | `OAuth` | Yes | Yes |
| [Newton](https://newton.vercel.app) | 符号和算术数学计算器 | No | Yes | No |
| [Noctua](https://api.noctuasky.com/api/v1/swaggerdoc/) | 用于访问NoctuaSky功能的REST API | No | Yes | Unknown |
| [Numbers](https://math.tools/api/numbers/) | 今日数字、随机数字、数字事实以及任何你想对数字做的事情 | `apiKey` | Yes | No |
| [Numbers](http://numbersapi.com) | 关于数字的事实 | No | No | No |
| [Ocean Facts](https://oceanfacts.herokuapp.com/) | 关于海洋学物理科学的事实 | No | Yes | Unknown |
| [Open Notify](http://open-notify.org/Open-Notify-API/) | 国际空间站宇航员、当前位置等 | No | No | No |
| [Open Science Framework](https://developer.osf.io) | 研究设计、研究材料、数据、手稿等的存储库和档案 | No | Yes | Unknown |
| [Purple Air](https://www2.purpleair.com/) | 实时空气质量监测 | No | Yes | Unknown |
| [Remote Calc](https://github.com/elizabethadegbaju/remotecalc) | 解码base64编码并解析它以JSON格式返回计算结果 | No | Yes | Yes |
| [SHARE](https://share.osf.io/api/v2/) | 关于研究和学术活动的免费开放数据集 | No | Yes | No |
| [SpaceX](https://github.com/r-spacex/SpaceX-API) | 公司、运载火箭、发射台和发射数据 | No | Yes | No |
| [SpaceX](https://api.spacex.land/graphql/) | GraphQL、公司、飞船、发射台和发射数据 | No | Yes | Unknown |
| [Sunrise and Sunset](https://sunrise-sunset.org/api) | 给定纬度和经度的日落和日出时间 | No | Yes | No |
| [Times Adder](https://github.com/FranP-code/API-Times-Adder) | 使用此API可以添加数组中发送的每个时间 | No | Yes | No |
| [TLE](https://tle.ivanstanojevic.me/#/docs) | 卫星信息 | No | Yes | No |
| [USGS Earthquake Hazards Program](https://earthquake.usgs.gov/fdsnws/event/1/) | 实时地震数据 | No | Yes | No |
| [USGS Water Services](https://waterservices.usgs.gov/) | 河流和湖泊的水质和水位信息 | No | Yes | No |
| [World Bank](https://datahelpdesk.worldbank.org/knowledgebase/topics/125589) | 世界银行数据 | No | Yes | No |
| [xMath](https://x-math.herokuapp.com/) | 随机数学表达式 | No | Yes | Yes |

**[⬆ 返回目录](#index)**


### 编程
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Codeforces](https://codeforces.com/apiHelp) | 获取Codeforces数据 | `apiKey` | Yes | Unknown |
| [Hackerearth](https://www.hackerearth.com/docs/wiki/developers/v4/) | 用于编译和运行多种语言的代码 | `apiKey` | Yes | Unknown |
| [Judge0 CE](https://ce.judge0.com/) | 在线代码执行系统 | `apiKey` | Yes | Unknown |
| [KONTESTS](https://kontests.net/api) | 用于即将到来和正在进行的竞争性编程竞赛 | No | Yes | Unknown |
| [Mintlify](https://docs.mintlify.com) | 用于以编程方式生成代码文档 | `apiKey` | Yes | Yes |

**[⬆ 返回目录](#index)**


### 摄影
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [apilayer screenshotlayer](https://screenshotlayer.com) | URL转图片 | No | Yes | Unknown |
| [APITemplate.io](https://apitemplate.io) | 通过简单API从模板动态生成图片和PDF | `apiKey` | Yes | Yes |    
| [Bruzu](https://docs.bruzu.com) | 使用查询字符串生成图片 | `apiKey` | Yes | Yes |
| [CheetahO](https://cheetaho.com/docs/getting-started/) | 照片优化和调整大小 | `apiKey` | Yes | Unknown |
| [Dagpi](https://dagpi.xyz) | 图片处理和操作 | `apiKey` | Yes | Unknown |
| [Duply](https://duply.co/docs#getting-started-api) | 更智能、更快速地生成、编辑、缩放和管理图片和视频 | `apiKey` | Yes | Yes |
| [DynaPictures](https://dynapictures.com/docs/) | 几分钟内生成数百张个性化图片 | `apiKey` | Yes | Yes |
| [Flickr](https://www.flickr.com/services/api/) | Flickr服务 | `OAuth` | Yes | Unknown |
| [Getty Images](http://developers.gettyimages.com/en/) | 使用世界上功能最强大的图像构建应用程序 | `OAuth` | Yes | Unknown |
| [Gfycat](https://developers.gfycat.com/api/) | 更流畅的GIF | `OAuth` | Yes | Unknown |
| [Giphy](https://developers.giphy.com/docs/) | 获取你所有的GIF | `apiKey` | Yes | Unknown |
| [Google Photos](https://developers.google.com/photos) | 将Google Photos与您的应用或设备集成 | `OAuth` | Yes | Unknown |
| [Image Upload](https://apilayer.com/marketplace/image_upload-api) | 图片优化 | `apiKey` | Yes | Unknown |
| [Imgur](https://apidocs.imgur.com/) | 图片 | `OAuth` | Yes | Unknown |
| [Imsea](https://imsea.herokuapp.com/) | 免费图片搜索 | No | Yes | Unknown |
| [Lorem Picsum](https://picsum.photos/) | 来自Unsplash的图片 | No | Yes | Unknown |
| [ObjectCut](https://objectcut.com/) | 图片背景去除 | `apiKey` | Yes | Yes |
| [Pexels](https://www.pexels.com/api/) | 免费库存照片和视频 | `apiKey` | Yes | Yes |
| [PhotoRoom](https://www.photoroom.com/api/) | 从图片中移除背景 | `apiKey` | Yes | Unknown |
| [Pixabay](https://pixabay.com/sk/service/about/api/) | 摄影 | `apiKey` | Yes | Unknown |
| [PlaceKeanu](https://placekeanu.com/) | 可调整大小的基努·里维斯占位符图片，带灰度和年轻基努选项 | No | Yes | Unknown |
| [Readme typing SVG](https://github.com/DenverCoder1/readme-typing-svg) | 可自定义的键入和删除文本SVG | No | Yes | Unknown |
| [Remove.bg](https://www.remove.bg/api) | 图片背景去除 | `apiKey` | Yes | Unknown |
| [ReSmush.it](https://resmush.it/api) | 照片优化 | No | No | Unknown |
| [shutterstock](https://api-reference.shutterstock.com/) | 库存照片和视频 | `OAuth` | Yes | Unknown |
| [Sirv](https://apidocs.sirv.com/) | 图像管理解决方案，如优化、操作、托管 | `apiKey` | Yes | Unknown |
| [Unsplash](https://unsplash.com/developers) | 摄影 | `OAuth` | Yes | Unknown |
| [Wallhaven](https://wallhaven.cc/help/api) | 壁纸 | `apiKey` | Yes | Unknown |
| [Webdam](https://www.damsuccess.com/hc/en-us/articles/202134055-REST-API) | 图片 | `OAuth` | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 电话
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Phone Validation](https://www.abstractapi.com/phone-validation-api) | 全球电话号码验证 | `apiKey` | Yes | Yes |
| [apilayer numverify](https://numverify.com) | 电话号码验证 | `apiKey` | Yes | Unknown |
| [Cloudmersive Validate](https://cloudmersive.com/phone-number-validation-API) | 验证国际电话号码 | `apiKey` | Yes | Yes |
| [Phone Specification](https://github.com/azharimm/phone-specs-api) | 电话规格的REST API | No | Yes | Yes |
| [Veriphone](https://veriphone.io) | 电话号码验证和运营商查询 | `apiKey` | Yes | Yes |

**[⬆ 返回目录](#index)**


### 人格
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Advice Slip](http://api.adviceslip.com/) | 生成随机建议 | No | Yes | Unknown |
| [Biriyani As A Service](https://biriyani.anoram.com/) | 印度炒饭图片占位符 | No | Yes | No |
| [Dev.to](https://developers.forem.com/api) | 通过API访问Forem文章、用户和其他资源 | `apiKey` | Yes | Unknown |
| [Dictum](https://github.com/fisenkodv/dictum) | API用于访问人类最鼓舞人心的话语集合 | No | Yes | Unknown |
| [FavQs.com](https://favqs.com/api) | FavQs允许您收集、发现和分享您喜欢的名言 | `apiKey` | Yes | Unknown |
| [FOAAS](http://www.foaas.com/) | 滚蛋服务 | No | No | Unknown |
| [Forismatic](http://forismatic.com/en/api/) | 励志名言 | No | No | Unknown |
| [icanhazdadjoke](https://icanhazdadjoke.com/api) | 互联网上最大的冷笑话集锦 | No | Yes | Unknown |
| [Inspiration](https://inspiration.goprogram.ai/docs/) | 励志和鼓舞人心的名言 | No | Yes | Yes |
| [kanye.rest](https://kanye.rest) | 用于随机坎耶·韦斯特名言的REST API | No | Yes | Yes |
| [kimiquotes](https://kimiquotes.herokuapp.com/doc) | 芬兰F1传奇车手基米·莱科宁的车队电台和采访语录 | No | Yes | Yes |
| [Medium](https://github.com/Medium/medium-api-docs) | 为读者和作家提供独特观点的社区 | `OAuth` | Yes | Unknown |
| [Programming Quotes](https://github.com/skolakoda/programming-quotes-api) | 开源项目的编程名言API | No | Yes | Unknown |
| [Quotable Quotes](https://github.com/lukePeavey/quotable) | Quotable是一个免费的开放源码引用API | No | Yes | Unknown |
| [Quote Garden](https://pprathameshmore.github.io/QuoteGarden/) | 超过5000条名言的REST API | No | Yes | Unknown |
| [quoteclear](https://quoteclear.web.app/) | 来自James Clear的3-2-1通讯的不断增长的名言列表 | No | Yes | Yes |
| [Quotes on Design](https://quotesondesign.com/api/) | 励志名言 | No | Yes | Unknown |
| [Stoicism Quote](https://github.com/tlcheah2/stoic-quote-lambda-public-api) | 关于斯多葛哲学的名言 | No | Yes | Unknown |
| [They Said So Quotes](https://theysaidso.com/api/) | 受到全球众多财富品牌信任的名言 | No | Yes | Unknown |
| [Traitify](https://app.traitify.com/developer) | 评估、收集和分析人格 | No | Yes | Unknown |
| [Udemy(instructor)](https://www.udemy.com/developers/instructor/) | Udemy讲师的API | `apiKey` | Yes | Unknown |
| [Vadivelu HTTP Codes](https://vadivelu.anoram.com/) | 按需提供带图片的HTTP状态码 | No | Yes | No |
| [Zen Quotes](https://zenquotes.io/) | 为灵感准备的庞大禅语名言集 | No | Yes | Yes |

**[⬆ 返回目录](#index)**


### 专利
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [EPO](https://developers.epo.org/) | 欧洲专利搜索系统API | `OAuth` | Yes | Unknown |
| [PatentsView ](https://patentsview.org/apis/purpose) | API旨在探索和可视化美国创新领域的趋势/模式 | No | Yes | Unknown |
| [TIPO](https://tiponet.tipo.gov.tw/Gazette/OpenData/OD/OD05.aspx?QryDS=API00) | 台湾专利搜索系统API | `apiKey` | Yes | Unknown |
| [USPTO](https://www.uspto.gov/learning-and-resources/open-data-and-mobility) | 美国专利API服务 | No | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 开源项目
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Countly](https://api.count.ly/reference) | Countly网络分析 | No | No | Unknown |
| [Creative Commons Catalog](https://api.creativecommons.engineering/) | 搜索开放许可和公共领域的作品 | `OAuth` | Yes | Yes |
| [Datamuse](https://www.datamuse.com/api/) | 词语查找查询引擎 | No | Yes | Unknown |
| [Drupal.org](https://www.drupal.org/drupalorg/docs/api) | Drupal.org | No | Yes | Unknown |
| [Evil Insult Generator](https://evilinsult.com/api) | 恶意侮辱 | No | Yes | Yes |
| [GitHub Contribution Chart Generator](https://github-contributions.vercel.app) | 创建您的GitHub贡献图片 | No | Yes | Yes |
| [GitHub ReadMe Stats](https://github.com/anuraghazra/github-readme-stats) | 为您的GitHub个人资料ReadMe添加动态生成的统计信息 | No | Yes | Yes |
| [Metabase](https://www.metabase.com/) | 一个开源的商业智能服务器，用于在公司内部共享数据和分析 | No | Yes | Yes |
| [Shields](https://shields.io/) | SVG和光栅格式中简洁、一致和易读的徽章 | No | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 开放数据
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [18F](http://18f.github.io/API-All-the-X/) | 非官方的美国联邦政府API开发 | No | No | Unknown |
| [API Setu](https://www.apisetu.gov.in/) | 一个印度政府平台，提供大量用于KYC、商业、教育和就业的API | No | Yes | Yes |
| [Archive.org](https://archive.readme.io/docs) | 互联网档案馆 | No | Yes | No |
| [Black History Facts](https://www.blackhistoryapi.io/docs) | 为网络上最大的黑人历史事实数据库之一贡献或搜索 | `apiKey` | Yes | Yes |
| [BotsArchive](https://botsarchive.com/docs.html) | 数据库中可用Telegram机器人的JSON格式详细信息 | No | Yes | Unknown |
| [Callook.info](https://callook.info) | 美国业余无线电呼号 | No | Yes | Unknown |
| [CARTO](https://carto.com/) | 位置信息预测 | `apiKey` | Yes | Unknown |
| [CollegeScoreCard.ed.gov](https://collegescorecard.ed.gov/data/) | 美国高等教育机构数据 | No | Yes | Unknown |
| [Enigma Public](https://developers.enigma.com/docs) | 最广泛的公共数据集合 | `apiKey` | Yes | Yes |
| [French Address Search](https://geo.api.gouv.fr/adresse) | 通过法国政府进行地址搜索 | No | Yes | Unknown |
| [GENESIS](https://www.destatis.de/EN/Service/OpenData/api-webservice.html) | 德国联邦统计局 | `OAuth` | Yes | Unknown |
| [Joshua Project](https://api.joshuaproject.net/) | 世界上基督徒最少的民族群体 | `apiKey` | Yes | Unknown |
| [Kaggle](https://www.kaggle.com/docs/api) | 创建和交互数据集、笔记本，并与Kaggle连接 | `apiKey` | Yes | Unknown |
| [LinkPreview](https://www.linkpreview.net) | 获取任何请求URL的JSON格式摘要，包括标题、描述和预览图片 | `apiKey` | Yes | Yes |
| [Lowy Asia Power Index](https://github.com/0x0is1/lowy-index-api-docs) | 获取衡量资源和影响力以排名亚洲国家的相对实力 | No | Yes | Unknown |
| [Microlink.io](https://microlink.io) | 从任何网站提取结构化数据 | No | Yes | Yes |
| [Nasdaq Data Link](https://docs.data.nasdaq.com/) | 股票市场数据 | `apiKey` | Yes | Unknown |
| [Nobel Prize](https://www.nobelprize.org/about/developer-zone-2/) | 关于诺贝尔奖和事件的开放数据 | No | Yes | Yes |
| [Open Data Minneapolis](https://opendata.minneapolismn.gov/) | 明尼阿波利斯市的地理信息系统和非地理信息系统城市数据 | No | Yes | No |
| [openAFRICA](https://africaopendata.org/) | 非洲开放数据的大型数据集存储库 | No | Yes | Unknown |
| [OpenCorporates](http://api.opencorporates.com/documentation/API-Reference) | 多个国家的公司和董事数据 | `apiKey` | Yes | Unknown |
| [OpenSanctions](https://www.opensanctions.org/docs/api/) | 关于国际制裁、犯罪和政治暴露人物的数据 | No | Yes | Yes |
| [PeakMetrics](https://rapidapi.com/peakmetrics-peakmetrics-default/api/peakmetrics-news) | 新闻文章和公共数据集 | `apiKey` | Yes | Unknown |
| [Recreation Information Database](https://ridb.recreation.gov/) | 娱乐区域、联邦土地、历史遗迹、博物馆和其他美国景点/资源 | `apiKey` | Yes | Unknown |
| [Scoop.it](http://www.scoop.it/dev) | 内容策展服务 | `apiKey` | No | Unknown |
| [Socrata](https://dev.socrata.com/) | 访问世界各地政府、非营利组织和非政府组织的开放数据 | `OAuth` | Yes | Yes |
| [Teleport](https://developers.teleport.org/) | 生活质量数据 | No | Yes | Unknown |
| [Umeå Open Data](https://opendata.umea.se/api/) | 瑞典北部城市Umeå的开放数据 | No | Yes | Yes |
| [Universities List](https://github.com/Hipo/university-domains-list) | 大学名称、国家和域名 | No | Yes | Unknown |
| [University of Oslo](https://data.uio.no/) | 奥斯陆大学（挪威）的课程、讲座视频、课程的详细信息等 | No | Yes | Unknown |
| [UPC database](https://upcdatabase.org/api) | 来自世界各地的150多万个条形码号码 | `apiKey` | Yes | Unknown |
| [Urban Observatory](https://urbanobservatory.ac.uk) | 英国最大的公开实时城市数据集 | No | No | No |
| [Wikidata](https://www.wikidata.org/w/api.php?action=help) | 由维基媒体基金会运营的协作编辑知识库 | `OAuth` | Yes | Unknown |
| [Wikipedia](https://www.mediawiki.org/wiki/API:Main_page) | Mediawiki百科全书 | No | Yes | Unknown |
| [Yelp](https://www.yelp.com/developers/documentation/v3) | 查找本地商家 | `OAuth` | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 新闻
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [apilayer mediastack](https://mediastack.com/) | 免费、简单的实时新闻和博客文章REST API | `apiKey` | Yes | Unknown |
| [Associated Press](https://developer.ap.org/) | 搜索美联社的新闻和元数据 | `apiKey` | Yes | Unknown |
| [Chronicling America](http://chroniclingamerica.loc.gov/about/api/) | 提供访问国会图书馆的数百万页历史美国报纸 | No | No | Unknown |
| [Currents](https://currentsapi.services/) | 来自各种新闻来源、博客和论坛的最新新闻 | `apiKey` | Yes | Yes |
| [Feedbin](https://github.com/feedbin/feedbin-api) | RSS阅读器 | `OAuth` | Yes | Unknown |
| [GNews](https://gnews.io/) | 从各种来源搜索新闻 | `apiKey` | Yes | Yes |
| [Graphs for Coronavirus](https://corona.dnsforfamily.com/api.txt) | 每个国家单独和全球的冠状病毒图表。每日更新 | No | Yes | Yes |
| [Inshorts News](https://github.com/cyberboysumanjay/Inshorts-News-API) | 提供来自Inshorts的新闻 | No | Yes | Unknown |
| [MarketAux](https://www.marketaux.com/) | 带有标记股票代码+情绪和统计的实时股票市场新闻JSON API | `apiKey` | Yes | Yes |
| [New York Times](https://developer.nytimes.com/) | 纽约时报开发者网络 | `apiKey` | Yes | Unknown |
| [News](https://newsapi.org/) | 当前在各种新闻来源和博客上发布的标题 | `apiKey` | Yes | Unknown |
| [NewsData](https://newsdata.io/docs) | 来自知名新闻来源的实时突发新闻和标题新闻数据API | `apiKey` | Yes | Unknown |
| [NewsX](https://rapidapi.com/machaao-inc-machaao-inc-default/api/newsx/) | 获取或搜索带有ML驱动摘要的最新突发新闻 🤖 | `apiKey` | Yes | Unknown |
| [NPR One](http://dev.npr.org/api/) | 来自NPR的个性化新闻收听体验 | `OAuth` | Yes | Unknown |
| [Spaceflight News](https://spaceflightnewsapi.net) | 航天相关新闻 🚀 | No | Yes | Yes |
| [The Guardian](http://open-platform.theguardian.com/) | 访问卫报创建的所有内容，按标签和栏目分类 | `apiKey` | Yes | Unknown |
| [The Old Reader](https://github.com/theoldreader/api) | RSS阅读器 | `apiKey` | Yes | Unknown |
| [TheNews](https://www.thenewsapi.com/) | 聚合标题、头条故事和实时新闻JSON API | `apiKey` | Yes | Yes |
| [Trove](https://trove.nla.gov.au/about/create-something/using-api) | 搜索澳大利亚国家图书馆数千份数字化报纸的收藏 | `apiKey` | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 音乐
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [7digital](https://docs.7digital.com/reference) | 7digital音乐商店API | `OAuth` | Yes | Unknown |
| [AI Mastering](https://aimastering.com/api_docs/) | 自动音乐母带处理 | `apiKey` | Yes | Yes |
| [Audiomack](https://www.audiomack.com/data-api/docs) | Audiomack流音乐中心的API | `OAuth` | Yes | Unknown |
| [Bandcamp](https://bandcamp.com/developer) | Bandcamp音乐商店API | `OAuth` | Yes | Unknown |
| [Bandsintown](https://app.swaggerhub.com/apis/Bandsintown/PublicAPI/3.0.0) | 音乐活动 | No | Yes | Unknown |
| [Deezer](https://developers.deezer.com/api) | 音乐 | `OAuth` | Yes | Unknown |
| [Discogs](https://www.discogs.com/developers/) | 音乐 | `OAuth` | Yes | Unknown |
| [Freesound](https://freesound.org/docs/api/) | 音乐样本 | `apiKey` | Yes | Unknown |
| [Gaana](https://github.com/cyberboysumanjay/GaanaAPI) | API用于从Gaana检索歌曲信息 | No | Yes | Unknown |
| [Genius](https://docs.genius.com/) | 众包歌词和音乐知识 | `OAuth` | Yes | Unknown |
| [Genrenator](https://binaryjazz.us/genrenator-api/) | 音乐类型生成器 | No | Yes | Unknown |
| [iTunes Search](https://affiliate.itunes.apple.com/resources/documentation/itunes-store-web-service-search-api/) | 软件产品 | No | Yes | Unknown |
| [Jamendo](https://developer.jamendo.com/v3.0/docs) | 音乐 | `OAuth` | Yes | Unknown |
| [JioSaavn](https://github.com/cyberboysumanjay/JioSaavnAPI) | API用于从JioSaavn检索歌曲信息、专辑元数据等 | No | Yes | Unknown |
| [KKBOX](https://developer.kkbox.com) | 获取音乐库、播放列表、排行榜，并在KKBOX平台之外执行操作 | `OAuth` | Yes | Unknown |
| [KSoft.Si Lyrics](https://docs.ksoft.si/api/lyrics-api) | API用于获取歌曲歌词 | `apiKey` | Yes | Unknown |
| [LastFm](https://www.last.fm/api) | 音乐 | `apiKey` | Yes | Unknown |
| [Lyrics.ovh](https://lyricsovh.docs.apiary.io) | 检索歌曲歌词的简单API | No | Yes | Unknown |
| [Mixcloud](https://www.mixcloud.com/developers/) | 音乐 | `OAuth` | Yes | Yes |
| [MusicBrainz](https://musicbrainz.org/doc/Development/XML_Web_Service/Version_2) | 音乐 | No | Yes | Unknown |
| [Musixmatch](https://developer.musixmatch.com/) | 音乐 | `apiKey` | Yes | Unknown |
| [Napster](https://developer.napster.com/api/v2.2) | 音乐 | `apiKey` | Yes | Yes |
| [Openwhyd](https://openwhyd.github.io/openwhyd/API) | 下载流媒体曲目的策展播放列表（YouTube、SoundCloud等...） | No | Yes | No |
| [Phishin](https://phish.in/api-docs) | 一个基于网络的即兴摇滚乐队Phish的合法现场音频录音档案 | `apiKey` | Yes | No |
| [Radio Browser](https://api.radio-browser.info/) | 网络电台列表 | No | Yes | Yes |
| [Songkick](https://www.songkick.com/developer/) | 音乐活动 | `apiKey` | Yes | Unknown |
| [Songlink / Odesli](https://www.notion.so/API-d0ebe08a5e304a55928405eb682f6741) | 获取歌曲可用的所有服务 | `apiKey` | Yes | Yes |
| [Songsterr](https://www.songsterr.com/a/wa/api/) | 提供吉他、贝斯和鼓谱及和弦 | No | Yes | Unknown |
| [SoundCloud](https://developers.soundcloud.com/docs/api/guide) | 使用SoundCloud API，您可以构建应用程序，为控制您的内容提供更多能力 | `OAuth` | Yes | Unknown |
| [Spotify](https://beta.developer.spotify.com/documentation/web-api/) | 查看Spotify音乐目录，管理用户的库，获取推荐等 | `OAuth` | Yes | Unknown |
| [TasteDive](https://tastedive.com/read/api) | 相似艺术家API（也适用于电影和电视节目） | `apiKey` | Yes | Unknown |
| [TheAudioDB](https://www.theaudiodb.com/api_guide.php) | 音乐 | `apiKey` | Yes | Unknown |
| [Vagalume](https://api.vagalume.com.br/docs/) | 众包歌词和音乐知识 | `apiKey` | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 机器学习
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [AI For Thai](https://aiforthai.in.th/index.php) | 免费的多种泰国AI API | `apiKey` | Yes | Yes |
| [Clarifai](https://docs.clarifai.com/api-guide/api-overview) | 计算机视觉 | `OAuth` | Yes | Unknown |
| [Cloudmersive](https://www.cloudmersive.com/image-recognition-and-processing-api) | 图像标注、人脸识别、NSFW分类 | `apiKey` | Yes | Yes |
| [Deepcode](https://www.deepcode.ai) | 代码审查AI | No | Yes | Unknown |
| [Dialogflow](https://cloud.google.com/dialogflow/docs/) | 自然语言处理 | `apiKey` | Yes | Unknown |
| [EXUDE-API](http://uttesh.com/exude-api/) | 用于过滤文本数据中停用词和词干的主要方法 | No | Yes | Yes |
| [Hirak FaceAPI](https://faceapi.hirak.site/) | 人脸检测、人脸识别（带年龄/性别估计）、准确、无配额限制 | `apiKey` | Yes | Unknown |    
| [Imagga](https://imagga.com/) | 图像识别解决方案，如标记、视觉搜索、NSFW审核 | `apiKey` | Yes | Unknown |
| [Inferdo](https://rapidapi.com/user/inferdo) | 人脸检测、图像标注、NSFW分类等计算机视觉服务 | `apiKey` | Yes | Unknown |
| [IPS Online](https://docs.identity.ps/docs) | 人脸和车牌匿名化 | `apiKey` | Yes | Unknown |
| [Irisnet](https://irisnet.de/api/) | 实时内容审核API，可实时阻止或模糊不需要的图像 | `apiKey` | Yes | Yes |
| [Keen IO](https://keen.io/) | 数据分析 | `apiKey` | Yes | Unknown |
| [Machinetutors](https://www.machinetutors.com/portfolio/MT_api.html) | AI解决方案：视频/图像分类和标记、NSFW、图标/图像/音频搜索、NLP | `apiKey` | Yes | Yes |
| [MessengerX.io](https://messengerx.rtfd.io) | 免费的API，供开发者构建和货币化基于ML的个性化聊天应用 | `apiKey` | Yes | Yes |
| [NLP Cloud](https://nlpcloud.io) | 使用spaCy和transformer的NLP API，用于命名实体识别、情感、分类、摘要等 | `apiKey` | Yes | Unknown |
| [OpenVisionAPI](https://openvisionapi.com) | 基于开源模型的开源计算机视觉API | No | Yes | Yes |
| [Perspective](https://perspectiveapi.com) | NLP API，返回文本是有毒、淫秽、侮辱还是威胁的概率 | `apiKey` | Yes | Unknown |
| [Roboflow Universe](https://universe.roboflow.com) | 预训练计算机视觉模型 | `apiKey` | Yes | Yes |
| [SkyBiometry](https://skybiometry.com/documentation/) | 人脸检测、人脸识别和人脸分组 | `apiKey` | Yes | Unknown |
| [Time Door](https://timedoor.io) | 时间序列分析API | `apiKey` | Yes | Yes |
| [Unplugg](https://unplu.gg/test_api.html) | 时间序列数据的预测API | `apiKey` | Yes | Unknown |
| [WolframAlpha](https://products.wolframalpha.com/api/) | 使用数据和算法提供问题的具体答案 | `apiKey` | Yes | Unknown |
| [HOL Registry Broker](https://hol.org/docs/registry-broker/) | 通用代理注册表API | `apiKey` | 是 | Unknown |

**[⬆ 返回目录](#index)**


### 工作
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Adzuna](https://developer.adzuna.com/overview) | 招聘板聚合器 | `apiKey` | Yes | Unknown |
| [Arbeitnow](https://documenter.getpostman.com/view/18545278/UVJbJdKh) | 欧洲/远程招聘板聚合器API | No | Yes | Yes |
| [Arbeitsamt](https://jobsuche.api.bund.dev/) | "Arbeitsamt"的API，这是一个德国招聘板聚合器 | `OAuth` | Yes | Unknown |
| [Careerjet](https://www.careerjet.com/partners/api/) | 职位搜索引擎 | `apiKey` | No | Unknown |
| [DevITjobs UK](https://devitjobs.uk/job_feed.xml) | GraphQL工作 | No | Yes | Yes |
| [Findwork](https://findwork.dev/developers/) | 招聘板 | `apiKey` | Yes | Unknown |
| [GraphQL Jobs](https://graphql.jobs/docs/api/) | GraphQL工作 | No | Yes | Yes |
| [Jobs2Careers](http://api.jobs2careers.com/api/spec.pdf) | 职位聚合器 | `apiKey` | Yes | Unknown |
| [Jooble](https://jooble.org/api/about) | 职位搜索引擎 | `apiKey` | Yes | Unknown |
| [Juju](http://www.juju.com/publisher/spec/) | 职位搜索引擎 | `apiKey` | No | Unknown |
| [Open Skills](https://github.com/workforce-data-initiative/skills-api/wiki/API-Overview) | 职位名称、技能和相关工作数据 | No | No | Unknown |
| [Reed](https://www.reed.co.uk/developers) | 招聘板聚合器 | `apiKey` | Yes | Unknown |
| [The Muse](https://www.themuse.com/developers/api/v2) | 招聘板和公司资料 | `apiKey` | Yes | Unknown |
| [Upwork](https://developers.upwork.com/) | 自由职业招聘板和管理系统 | `OAuth` | Yes | Unknown |
| [USAJOBS](https://developer.usajobs.gov/) | 美国政府招聘板 | `apiKey` | Yes | Unknown |
| [WhatJobs](https://www.whatjobs.com/affiliates) | 职位搜索引擎 | `apiKey` | Yes | Unknown |
| [ZipRecruiter](https://www.ziprecruiter.com/publishers) | 职位搜索应用和网站 | `apiKey` | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 健康
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [CMS.gov](https://data.cms.gov/provider-data/) | 访问CMS - medicare.gov的数据 | `apiKey` | Yes | Unknown |
| [Coronavirus](https://pipedream.com/@pravin/http-api-for-latest-wuhan-coronavirus-data-2019-ncov-p_G6CLVM/readme) | 最新Covid-19数据的HTTP API | No | Yes | Unknown |
| [Coronavirus in the UK](https://coronavirus.data.gov.uk/details/developers-guide) | 英国政府冠状病毒数据，包括按地区划分的死亡和病例 | No | Yes | Unknown |
| [Covid Tracking Project](https://covidtracking.com/data/api/version-2) | 美国的Covid-19数据 | No | Yes | No |
| [Covid-19](https://covid19api.com/) | Covid 19传播、感染和康复 | No | Yes | Yes |
| [Covid-19](https://github.com/M-Media-Group/Covid-19-API) | 各国Covid 19病例、死亡和康复 | No | Yes | Yes |
| [Covid-19 Datenhub](https://npgeo-corona-npgeo-de.hub.arcgis.com) | COVID-19背景下的地图、数据集、应用程序等 | No | Yes | Unknown |
| [Covid-19 Government Response](https://covidtracker.bsg.ox.ac.uk) | 政府抗击Covid-19大流行的措施追踪器 | No | Yes | Yes |
| [Covid-19 India](https://data.covid19india.org/) | 印度各邦和地区的Covid 19统计数据，包括病例、疫苗接种、康复情况 | No | Yes | Unknown |
| [Covid-19 JHU CSSE](https://nuttaphat.com/covid19-api/) | 基于JHU CSSE的探索Covid19病例的开源API | No | Yes | Yes |
| [Covid-19 Live Data](https://github.com/mathdroid/covid-19-api) | 全球和各国的Covid 19每日摘要、确诊病例、康复和死亡数据 | No | Yes | Yes |
| [Covid-19 Philippines](https://github.com/Simperfy/Covid-19-API-Philippines-DOH) | 来自卫生部收集的数据的菲律宾非官方Covid-19 Web API | No | Yes | Yes |
| [COVID-19 Tracker Canada](https://api.covid19tracker.ca/docs/1.0/overview) | 加拿大的Covid-19病例详情 | No | Yes | Unknown |
| [COVID-19 Tracker Sri Lanka](https://www.hpb.health.gov.lk/en/api-documentation) | 提供斯里兰卡报告的Covid-19患者情况 | No | Yes | Unknown |
| [COVID-ID](https://data.covid19.go.id/public/api/prov.json) | 印尼政府各省Covid数据 | No | Yes | Yes |
| [Dataflow Kit COVID-19](https://covid-19.dataflowkit.com) | 每小时将COVID-19实时统计到网站 | No | Yes | Unknown |
| [FoodData Central](https://fdc.nal.usda.gov/) | 标准参考国家营养数据库 | `apiKey` | Yes | Unknown |
| [Healthcare.gov](https://www.healthcare.gov/developers/) | 关于美国健康保险市场的教育内容 | No | Yes | Unknown |
| [Humanitarian Data Exchange](https://data.humdata.org/) | 人道主义数据交换（HDX）是一个在危机和组织间共享数据的开放平台 | No | Yes | Unknown |
| [Infermedica](https://developer.infermedica.com/docs/) | 基于NLP的症状检查器和用于从文本进行健康诊断的患者分诊API | `apiKey` | Yes | Yes |
| [LAPIS](https://cov-spectrum.ethz.ch/public) | 来自公共来源的SARS-CoV-2基因组序列 | No | Yes | Yes |
| [Lexigram](https://docs.lexigram.io/) | 从文本中提取临床概念提及的NLP，提供临床本体访问 | `apiKey` | Yes | Unknown |
| [Makeup](http://makeup-api.herokuapp.com/) | 化妆品信息 | No | No | Unknown |
| [MyVaccination](https://documenter.getpostman.com/view/16605343/Tzm8GG7u) | 马来西亚疫苗接种数据 | No | Yes | Unknown |
| [NPPES](https://npiregistry.cms.hhs.gov/registry/help-api) | 国家计划和提供者枚举系统，关于在美国注册的医疗保健提供者的信息 | No | Yes | Unknown |
| [Nutritionix](https://developer.nutritionix.com/) | 世界最大的验证营养数据库 | `apiKey` | Yes | Unknown |
| [Open Data NHS Scotland](https://www.opendata.nhs.scot) | 苏格兰公共卫生局的医学参考数据和统计 | No | Yes | Unknown |
| [Open Disease](https://disease.sh/) | 关于COVID-19和流感当前病例等的API | No | Yes | Yes |
| [openFDA](https://open.fda.gov) | 关于药物、设备和食品的公共FDA数据 | `apiKey` | Yes | Unknown |
| [Orion Health](https://developer.orionhealth.io/) | 医疗平台，允许开发针对不同医疗场景的应用程序 | `OAuth` | Yes | Unknown |
| [Quarantine](https://quarantine.country/coronavirus/api/) | 提供免费COVID-19实时更新的冠状病毒API | No | Yes | Yes |

**[⬆ 返回目录](#index)**


### 政府
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Bank Negara Malaysia Open Data](https://apikijangportal.bnm.gov.my/) | 马来西亚央行开放数据 | No | Yes | Unknown |
| [BCLaws](https://www.bclaws.gov.bc.ca/civix/template/complete/api/index.html) | 访问不列颠哥伦比亚省的法律 | No | No | Unknown |
| [Brazil](https://brasilapi.com.br/) | 巴西公共数据的社区驱动API | No | Yes | Yes |
| [Brazil Central Bank Open Data](https://dadosabertos.bcb.gov.br/) | 巴西央行开放数据 | No | Yes | Unknown |
| [Brazil Receita WS](https://www.receitaws.com.br/) | 通过CNPJ查询巴西公司 | No | Yes | Unknown |
| [Brazilian Chamber of Deputies Open Data](https://dadosabertos.camara.leg.br/swagger/api.html) | 提供XML和JSON格式的立法信息，以及各种格式的文件 | No | Yes | No |
| [Census.gov](https://www.census.gov/data/developers/data-sets.html) | 美国人口普查局提供关于人口统计和商业的各种API和数据集 | No | Yes | Unknown |
| [City, Berlin](https://daten.berlin.de/) | 柏林（德国）城市开放数据 | No | Yes | Unknown |
| [City, Gdańsk](https://ckan.multimediagdansk.pl/en) | 格但斯克（波兰）城市开放数据 | No | Yes | Unknown |
| [City, Gdynia](http://otwartedane.gdynia.pl/en/api_doc.html) | 格丁尼亚（波兰）城市开放数据 | No | No | Unknown |
| [City, Helsinki](https://hri.fi/en_gb/) | 赫尔辛基（芬兰）城市开放数据 | No | Yes | Unknown |
| [City, Lviv](https://opendata.city-adm.lviv.ua/) | 利沃夫（乌克兰）城市开放数据 | No | Yes | Unknown |
| [City, Nantes Open Data](https://data.nantesmetropole.fr/pages/home/) | 南特（法国）城市开放数据 | `apiKey` | Yes | Unknown |
| [City, New York Open Data](https://opendata.cityofnewyork.us/) | 纽约（美国）城市开放数据 | No | Yes | Unknown |
| [City, Prague Open Data](http://opendata.praha.eu/en) | 布拉格（捷克）城市开放数据 | No | No | Unknown |
| [City, Toronto Open Data](https://open.toronto.ca/) | 多伦多（加拿大）城市开放数据 | No | Yes | Yes |
| [Code.gov](https://code.gov) | 美国联邦政府开源和代码共享的主要平台 | `apiKey` | Yes | Unknown |
| [Colorado Information Marketplace](https://data.colorado.gov/) | 科罗拉多州政府开放数据 | No | Yes | Unknown |
| [Data USA](https://datausa.io/about/api/) | 美国公共数据 | No | Yes | Unknown |
| [Data.gov](https://api.data.gov/) | 美国政府数据 | `apiKey` | Yes | Unknown |
| [Data.parliament.uk](https://explore.data.parliament.uk/?learnmore=Members) | 包含实时数据集，包括请愿书、法案、议员投票、出席等信息 | No | No | Unknown |
| [Deutscher Bundestag DIP](https://dip.bundestag.de/documents/informationsblatt_zur_dip_api_v01.pdf) | 此API提供对DIP实体（如活动、人员、印刷材料）的只读访问 | `apiKey` | Yes | Unknown |
| [District of Columbia Open Data](http://opendata.dc.gov/pages/using-apis) | 包含华盛顿特区政府公共数据集，包括犯罪、地理信息系统、财务数据等 | No | Yes | Unknown |
| [EPA](https://www.epa.gov/developers/data-data-products#apis) | 美国环境保护署的网络服务和数据集 | No | Yes | Unknown |
| [FBI Wanted](https://www.fbi.gov/wanted/api) | 访问FBI通缉项目的信息 | No | Yes | Unknown |
| [FEC](https://api.open.fec.gov/developers/) | 联邦选举中的竞选捐款信息 | `apiKey` | Yes | Unknown |
| [Federal Register](https://www.federalregister.gov/reader-aids/developer-resources/rest-api) | 美国政府日报 | No | Yes | Unknown |
| [Food Standards Agency](http://ratings.food.gov.uk/open-data/en-GB) | 英国食品卫生评级数据API | No | No | Unknown |
| [Gazette Data, UK](https://www.thegazette.co.uk/data) | 英国官方公共记录API | `OAuth` | Yes | Unknown |
| [Gun Policy](https://www.gunpolicy.org/api) | 国际枪支伤害预防和政策 | `apiKey` | Yes | Unknown |
| [INEI](http://iinei.inei.gob.pe/microdatos/) | 秘鲁统计政府开放数据 | No | No | Unknown |
| [Interpol Red Notices](https://interpol.api.bund.dev/) | 访问和搜索国际刑警组织红色通缉令 | No | Yes | Unknown |
| [Istanbul (İBB) Open Data](https://data.ibb.gov.tr) | 伊斯坦布尔大都会市（İBB）的数据集 | No | Yes | Unknown |
| [National Park Service, US](https://www.nps.gov/subjects/developer/) | 美国国家公园管理局的数据 | `apiKey` | Yes | Yes |
| [Open Government, ACT](https://www.data.act.gov.au/) | 澳大利亚首都领地开放数据 | No | Yes | Unknown |
| [Open Government, Argentina](https://datos.gob.ar/) | 阿根廷政府开放数据 | No | Yes | Unknown |
| [Open Government, Australia](https://www.data.gov.au/) | 澳大利亚政府开放数据 | No | Yes | Unknown |
| [Open Government, Austria](https://www.data.gv.at/) | 奥地利政府开放数据 | No | Yes | Unknown |
| [Open Government, Belgium](https://data.gov.be/) | 比利时政府开放数据 | No | Yes | Unknown |
| [Open Government, Canada](http://open.canada.ca/en) | 加拿大政府开放数据 | No | No | Unknown |
| [Open Government, Colombia](https://www.dane.gov.co/) | 哥伦比亚政府开放数据 | No | No | Unknown |
| [Open Government, Cyprus](https://data.gov.cy/?language=en) | 塞浦路斯政府开放数据 | No | Yes | Unknown |
| [Open Government, Czech Republic](https://data.gov.cz/english/) | 捷克共和国政府开放数据 | No | Yes | Unknown |
| [Open Government, Denmark](https://www.opendata.dk/) | 丹麦政府开放数据 | No | Yes | Unknown |
| [Open Government, Estonia](https://avaandmed.eesti.ee/instructions/opendata-dataset-api) | 爱沙尼亚政府开放数据 | `apiKey` | Yes | Unknown |
| [Open Government, Finland](https://www.avoindata.fi/en) | 芬兰政府开放数据 | No | Yes | Unknown |
| [Open Government, France](https://www.data.gouv.fr/) | 法国政府开放数据 | `apiKey` | Yes | Unknown |
| [Open Government, Germany](https://www.govdata.de/daten/-/details/govdata-metadatenkatalog) | 德国政府开放数据 | No | Yes | Unknown |
| [Open Government, Greece](https://data.gov.gr/) | 希腊政府开放数据 | `OAuth` | Yes | Unknown |
| [Open Government, India](https://data.gov.in/) | 印度政府开放数据 | `apiKey` | Yes | Unknown |
| [Open Government, Ireland](https://data.gov.ie/pages/developers) | 爱尔兰政府开放数据 | No | Yes | Unknown |
| [Open Government, Italy](https://www.dati.gov.it/) | 意大利政府开放数据 | No | Yes | Unknown |
| [Open Government, Korea](https://www.data.go.kr/) | 韩国政府开放数据 | `apiKey` | Yes | Unknown |
| [Open Government, Lithuania](https://data.gov.lt/public/api/1) | 立陶宛政府开放数据 | No | Yes | Unknown |
| [Open Government, Luxembourg](https://data.public.lu) | 卢森堡政府开放数据 | `apiKey` | Yes | Unknown |
| [Open Government, Mexico](https://www.inegi.org.mx/datos/) | 墨西哥统计政府开放数据 | No | Yes | Unknown |
| [Open Government, Mexico](https://datos.gob.mx/) | 墨西哥政府开放数据 | No | Yes | Unknown |
| [Open Government, Netherlands](https://data.overheid.nl/en/ondersteuning/data-publiceren/api) | 荷兰政府开放数据 | No | Yes | Unknown |
| [Open Government, New South Wales](https://api.nsw.gov.au/) | 新南威尔士州政府开放数据 | `apiKey` | Yes | Unknown |
| [Open Government, New Zealand](https://www.data.govt.nz/) | 新西兰政府开放数据 | No | Yes | Unknown |
| [Open Government, Norway](https://data.norge.no/dataservices) | 挪威政府开放数据 | No | Yes | Yes |
| [Open Government, Peru](https://www.datosabiertos.gob.pe/) | 秘鲁政府开放数据 | No | Yes | Unknown |
| [Open Government, Poland](https://dane.gov.pl/en) | 波兰政府开放数据 | No | Yes | Yes |
| [Open Government, Portugal](https://dados.gov.pt/en/docapi/) | 葡萄牙政府开放数据 | No | Yes | Yes |
| [Open Government, Queensland Government](https://www.data.qld.gov.au/) | 昆士兰州政府开放数据 | No | Yes | Unknown |
| [Open Government, Romania](http://data.gov.ro/) | 罗马尼亚政府开放数据 | No | No | Unknown |
| [Open Government, Saudi Arabia](https://data.gov.sa) | 沙特阿拉伯政府开放数据 | No | Yes | Unknown |
| [Open Government, Singapore](https://data.gov.sg/developer) | 新加坡政府开放数据 | No | Yes | Unknown |
| [Open Government, Slovakia](https://data.gov.sk/en/) | 斯洛伐克政府开放数据 | No | Yes | Unknown |
| [Open Government, Slovenia](https://podatki.gov.si/) | 斯洛文尼亚政府开放数据 | No | Yes | No |
| [Open Government, South Australian Government](https://data.sa.gov.au/) | 南澳大利亚州政府开放数据 | No | Yes | Unknown |
| [Open Government, Spain](https://datos.gob.es/en) | 西班牙政府开放数据 | No | Yes | Unknown |
| [Open Government, Sweden](https://www.dataportal.se/en/dataservice/91_29789/api-for-the-statistical-database) | 瑞典政府开放数据 | No | Yes | Unknown |
| [Open Government, Switzerland](https://handbook.opendata.swiss/de/content/nutzen/api-nutzen.html) | 瑞士政府开放数据 | No | Yes | Unknown |
| [Open Government, Taiwan](https://data.gov.tw/) | 台湾政府开放数据 | No | Yes | Unknown |
| [Open Government, Thailand](https://data.go.th/) | 泰国政府开放数据 | `apiKey` | Yes | Unknown |
| [Open Government, UK](https://data.gov.uk/) | 英国政府开放数据 | No | Yes | Unknown |
| [Open Government, USA](https://www.data.gov/) | 美国政府开放数据 | No | Yes | Unknown |
| [Open Government, Victoria State Government](https://www.data.vic.gov.au/) | 维多利亚州政府开放数据 | No | Yes | Unknown |
| [Open Government, West Australia](https://data.wa.gov.au/) | 西澳大利亚开放数据 | No | Yes | Unknown |
| [PRC Exam Schedule](https://api.whenisthenextboardexam.com/docs/) | 非官方的菲律宾专业监管委员会考试日程 | No | Yes | Yes |
| [Represent by Open North](https://represent.opennorth.ca/) | 查找加拿大政府代表 | No | Yes | Unknown |
| [UK Companies House](https://developer.company-information.service.gov.uk/) | 来自英国政府的英国公司注册处数据 | `OAuth` | Yes | Unknown |
| [US Presidential Election Data by TogaTech](https://uselection.togatech.org/api/) | 美国总统选举中两党候选人的基本数据和实时选举票数 | No | Yes | No |
| [USA.gov](https://www.usa.gov/developer) | 关于美国程序、活动、服务等的权威信息 | `apiKey` | Yes | Unknown |
| [USAspending.gov](https://api.usaspending.gov/) | 美国联邦支出数据 | No | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 地理编码
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [IP Geolocation](https://www.abstractapi.com/ip-geolocation-api) | 通过IP地址定位网站访问者 | `apiKey` | Yes | Yes |
| [Actinia Grass GIS](https://actinia.mundialis.de/api_docs/) | Actinia是一个使用GRASS GIS的开源地理数据REST API | `apiKey` | Yes | Unknown |
| [administrative-divisons-db](https://github.com/kamikazechaser/administrative-divisions-db) | 获取一个国家的所有行政区划 | No | Yes | Yes |
| [adresse.data.gouv.fr](https://adresse.data.gouv.fr) | 法国地址数据库，地理编码和反向地理编码 | No | Yes | Unknown |
| [Airtel IP](https://sys.airtel.lv/ip2country/1.1.1.1/?full=true) | IP地理定位API。从多个来源收集数据 | No | Yes | Unknown |
| [Apiip](https://apiip.net/) | 通过IP地址获取位置信息 | `apiKey` | Yes | Yes |
| [apilayer ipstack](https://ipstack.com/) | 通过IP地址定位和识别网站访问者 | `apiKey` | Yes | Unknown |
| [Battuta](http://battuta.medunes.net) | 级联位置API（国家/地区/城市） | `apiKey` | No | Unknown |
| [BigDataCloud](https://www.bigdatacloud.com/ip-geolocation-apis) | 提供快速准确的IP地理定位API以及安全检查和置信区域 | `apiKey` | Yes | Unknown |
| [Bing Maps](https://www.microsoft.com/maps/) | 基于必应地图数据创建/定制数字地图 | `apiKey` | Yes | Unknown |
| [bng2latlong](https://www.getthedata.com/bng2latlong) | 将英国OSGB36东向坐标和北向坐标（英国国家网格）转换为WGS84经纬度 | No | Yes | Yes |
| [Cartes.io](https://github.com/M-Media-Group/Cartes.io/wiki/API) | 为任何东西创建地图和标记 | No | Yes | Unknown |
| [Cep.la](http://cep.la/) | 巴西RESTful API，用于查找街道、邮政编码、社区、城市和州的信息 | No | No | Unknown |
| [CitySDK](http://www.citysdk.eu/citysdk-toolkit/) | 选定欧洲城市的开放API | No | Yes | Unknown |
| [Country](http://country.is/) | 通过访问者的IP地址获取其所在国家 | No | Yes | Yes |
| [CountryStateCity](https://countrystatecity.in/) | 世界国家、州、地区、省、城市和城镇的JSON、SQL、XML、YAML和CSV格式 | `apiKey` | Yes | Yes |
| [Ducks Unlimited](https://gis.ducks.org/datasets/du-university-chapters/api) | API探索器，提供包含位置和城市JSON响应的查询URL | No | Yes | No |
| [GeoApi](https://api.gouv.fr/api/geoapi.html) | 法国地理数据 | No | Yes | Unknown |
| [Geoapify](https://www.geoapify.com/api/geocoding-api/) | 正向和反向地理编码，地址自动完成 | `apiKey` | Yes | Yes |
| [Geocod.io](https://www.geocod.io/) | 地址地理编码/批量反向地理编码 | `apiKey` | Yes | Unknown |
| [Geocode.xyz](https://geocode.xyz/api) | 提供全球正向/反向地理编码、批量地理编码和地理解析 | No | Yes | Unknown |
| [Geocodify.com](https://geocodify.com/) | 全球地理编码、地理解析和地址自动完成 | `apiKey` | Yes | Yes |
| [Geodata.gov.gr](https://geodata.gov.gr/en/) | 希腊开放地理空间数据和API服务 | No | Yes | Unknown |
| [GeoDataSource](https://www.geodatasource.com/web-service) | 使用经纬度坐标对城市名称进行地理编码 | `apiKey` | Yes | Unknown |
| [GeoDB Cities](http://geodb-cities-api.wirefreethought.com/) | 获取全球城市、地区和国家数据 | `apiKey` | Yes | Unknown |
| [GeographQL](https://geographql.netlify.app) | 国家、州和城市的GraphQL API | No | Yes | Yes |
| [GeoJS](https://www.geojs.io/) | 集成ChatOps的IP地理定位 | No | Yes | Yes |
| [Geokeo](https://geokeo.com) | Geokeo地理编码服务-每日2500次免费API请求 | No | Yes | Yes |
| [GeoNames](http://www.geonames.org/export/web-services.html) | 地名和其他地理数据 | No | No | Unknown |
| [geoPlugin](https://www.geoplugin.com) | IP地理定位和货币转换 | No | Yes | Yes |
| [Google Earth Engine](https://developers.google.com/earth-engine/) | 用于行星尺度环境数据分析的云平台 | `apiKey` | Yes | Unknown |
| [Google Maps](https://developers.google.com/maps/) | 基于Google地图数据创建/定制数字地图 | `apiKey` | Yes | Unknown |
| [Graph Countries](https://github.com/lennertVanSever/graphcountries) | 国家相关数据，如货币、语言、旗帜、地区+次区域和接壤国家 | No | Yes | Unknown |
| [HelloSalut](https://fourtonfish.com/project/hellosalut-api/) | 根据用户语言获取问候语翻译 | No | Yes | Unknown |
| [HERE Maps](https://developer.here.com) | 基于HERE地图数据创建/定制数字地图 | `apiKey` | Yes | Unknown |
| [Hirak IP to Country](https://iplocation.hirak.site/) | IP到位置的转换，包含国家代码、货币代码和货币名称，响应快速， запросы无限制 | `apiKey` | Yes | Unknown |
| [Hong Kong GeoData Store](https://geodata.gov.hk/gs/) | 访问香港地理数据的API | No | Yes | Unknown |
| [IBGE](https://servicodados.ibge.gov.br/api/docs/) | 巴西地理和统计研究所（IBGE）的聚合服务 | No | Yes | Unknown |
| [IP 2 Country](https://ip2country.info) | 将IP映射到国家 | No | Yes | Unknown |
| [IP Address Details](https://ipinfo.io/) | 通过IP地址查找地理定位 | No | Yes | Unknown |
| [IP Vigilante](https://www.ipvigilante.com/) | 免费IP地理定位API | No | Yes | Unknown |
| [ip-api](https://ip-api.com/docs) | 通过IP地址或域名查找位置 | No | No | Unknown |
| [IP2Location](https://www.ip2location.com/web-service/ip2location) | IP地理定位网络服务，可获取超过55个参数 | `apiKey` | Yes | Unknown |
| [IP2Proxy](https://www.ip2location.com/web-service/ip2proxy) | 使用IP地址检测代理和VPN | `apiKey` | Yes | Unknown |
| [ipapi.co](https://ipapi.co/api/#introduction) | 查找IP地址位置信息 | No | Yes | Yes |
| [ipapi.com](https://ipapi.com/) | 实时地理定位和反向IP查询REST API | `apiKey` | Yes | Unknown |
| [IPGEO](https://api.techniknews.net/ipgeo/) | 无限免费IP地址API，提供有用信息 | No | Yes | Unknown |
| [ipgeolocation](https://ipgeolocation.io/) | 每月30k次请求的免费计划的IP地理定位API | `apiKey` | Yes | Yes |
| [IPInfoDB](https://www.ipinfodb.com/api) | 通过IP地址查找国家、地区、城市和时区的免费地理定位工具和API | `apiKey` | Yes | Unknown |
| [ipstack](https://ipstack.com/) | 通过IP地址定位和识别网站访问者 | `apiKey` | Yes | Unknown |
| [Kakao Maps](https://apis.map.kakao.com) | Kakao Maps为韩国地图提供多种API | `apiKey` | Yes | Unknown |
| [keycdn IP Location Finder](https://tools.keycdn.com/geo) | 通过简单的REST API获取IP地理定位数据。所有响应都是JSON编码的 | `apiKey` | Yes | Unknown |
| [LocationIQ](https://locationiq.org/docs/) | 提供正向/反向地理编码和批量地理编码 | `apiKey` | Yes | Yes |
| [Longdo Map](https://map.longdo.com/docs/) | 带有详细地点和信息门户的交互式地图 | `apiKey` | Yes | Yes |
| [Mapbox](https://docs.mapbox.com/) | 创建/定制精美的数字地图 | `apiKey` | Yes | Unknown |
| [MapQuest](https://developer.mapquest.com/) | 访问映射世界的工具和资源 | `apiKey` | Yes | No | Yes
| [Mexico](https://github.com/IcaliaLabs/sepomex) | 墨西哥RESTful邮政编码API | No | Yes | Unknown |
| [Nominatim](https://nominatim.org/release-docs/latest/api/Overview/) | 提供全球正向/反向地理编码 | No | Yes | Yes |
| [One Map, Singapore](https://www.onemap.gov.sg/docs/) | 新加坡土地管理局用于新加坡地址的REST API服务 | `apiKey` | Yes | Unknown |
| [OnWater](https://onwater.io/) | 确定经纬度是在水上还是陆地上 | No | Yes | Unknown |
| [Open Topo Data](https://www.opentopodata.org) | 给定纬度和经度的海拔和海洋深度 | No | Yes | No |
| [OpenCage](https://opencagedata.com) | 使用开放数据正向和反向地理编码 | `apiKey` | Yes | Yes |
| [openrouteservice.org](https://openrouteservice.org/) | 路线、兴趣点、等时区、地理编码（+反向）、海拔等 | `apiKey` | Yes | Unknown |
| [OpenStreetMap](http://wiki.openstreetmap.org/wiki/API) | 导航、地理位置和地理数据 | `OAuth` | No | Unknown |
| [Pinball Map](https://pinballmap.com/api/v1/docs) | 公共弹球机的众包地图 | No | Yes | Yes |
| [positionstack](https://positionstack.com/) | 正向和反向批量地理编码REST API | `apiKey` | Yes | Unknown |
| [Postali](https://postali.app/api) | 墨西哥邮政编码API | No | Yes | Yes |
| [PostcodeData.nl](http://api.postcodedata.nl/v1/postcode/?postcode=1211EP&streetnumber=60&ref=domeinnaam.nl&type=json) | 根据荷兰地址的邮政编码提供地理定位数据 | No | No | Unknown |
| [Postcodes.io](https://postcodes.io) | 英国邮编查询和地理定位 | No | Yes | Yes |
| [Queimadas INPE](https://queimadas.dgi.inpe.br/queimadas/dados-abertos/) | 访问热焦点数据（可能的野火） | No | Yes | Unknown |
| [REST Countries](https://restcountries.com) | 通过RESTful API获取国家信息 | No | Yes | Yes |
| [RoadGoat Cities](https://www.roadgoat.com/business/cities-api) | 城市内容和照片API | `apiKey` | Yes | No |
| [Rwanda Locations](https://rapidapi.com/victorkarangwa4/api/rwanda) | 卢旺达省、区、城市、首都、区、单元、村和街道 | No | Yes | Unknown |
| [SLF](https://github.com/slftool/slftool.github.io/blob/master/API.md) | 德国城市、国家、河流、数据库 | No | Yes | Yes |
| [SpotSense](https://spotsense.io/) | 为您的移动应用添加基于位置的交互 | `apiKey` | Yes | Unknown |
| [Telize](https://rapidapi.com/fcambus/api/telize/) | Telize提供任何IP地址的位置信息 | `apiKey` | Yes | Yes |
| [TomTom](https://developer.tomtom.com/) | 地图、路线、地点和交通API | `apiKey` | Yes | Yes |
| [Uebermaps](https://uebermaps.com/api/v2) | 发现和分享地图与朋友 | `apiKey` | Yes | Unknown |
| [US ZipCode](https://www.smarty.com/docs/cloud/us-zipcode-api) | 验证和追加任何美国邮政编码的数据 | `apiKey` | Yes | Yes |
| [Utah AGRC](https://api.mapserv.utah.gov) | 用于地理编码犹他州地址的犹他州网络API | `apiKey` | Yes | Unknown |
| [ViaCep](https://viacep.com.br) | 巴西RESTful邮政编码API | No | Yes | Unknown |
| [What3Words](https://what3words.com) | 三个词作为全球范围内令人难忘且独特的坐标 | `apiKey` | Yes | Unknown |
| [Yandex.Maps Geocoder](https://yandex.com/dev/maps/geocoder) | 使用地理编码从地址获取对象的坐标 | `apiKey` | Yes | Unknown |
| [ZipCodeAPI](https://www.zipcodeapi.com) | 美国邮政编码距离、半径和位置API | `apiKey` | Yes | Unknown |
| [Zippopotam.us](http://www.zippopotam.us) | 获取地点信息，如国家、城市、州等 | No | No | Unknown |
| [Ziptastic](https://ziptasticapi.com/) | 获取任何美国邮政编码的国家、州和城市 | No | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 游戏与漫画
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Age of Empires II](https://age-of-empires-2-api.herokuapp.com) | 获取关于帝国时代II资源的信息 | No | Yes | No |
| [AmiiboAPI](https://amiiboapi.com/) | 任天堂Amiibo信息 | No | Yes | Yes |
| [Animal Crossing: New Horizons](http://acnhapi.com/) | 生物、化石、艺术品、音乐、家具和村民的API | No | Yes | Unknown |
| [Autochess VNG](https://github.com/didadadida93/autochess-vng-api) | Autochess VNG的REST API | No | Yes | Yes |
| [Barter.VG](https://github.com/bartervg/barter.vg/wiki) | 提供关于游戏、DLC、捆绑包、赠品和交易的信息 | No | Yes | Yes |
| [Battle.net](https://develop.battle.net/documentation/guides/getting-started) | 暗黑破坏神III、炉石传说、星争霸II和魔兽争霸游戏数据API | `OAuth` | Yes | Yes |
| [Board Game Geek](https://boardgamegeek.com/wiki/page/BGG_XML_API2) | 桌游、RPG和电子游戏 | No | Yes | No |
| [Brawl Stars](https://developer.brawlstars.com) | Brawl Stars游戏信息 | `apiKey` | Yes | Unknown |
| [Bugsnax](https://www.bugsnaxapi.com/) | 获取关于Bugsnax的信息 | No | Yes | Yes |
| [CheapShark](https://www.cheapshark.com/api) | Steam/PC游戏价格和优惠 | No | Yes | Yes |
| [Chess.com](https://www.chess.com/news/view/published-data-api) | Chess.com只读REST API | No | Yes | Unknown |
| [Chuck Norris Database](http://www.icndb.com/api/) | 笑话 | No | No | Unknown |
| [Clash of Clans](https://developer.clashofclans.com) | 部落冲突游戏信息 | `apiKey` | Yes | Unknown |
| [Clash Royale](https://developer.clashroyale.com) | 皇室战争游戏信息 | `apiKey` | Yes | Unknown |
| [Comic Vine](https://comicvine.gamespot.com/api/documentation) | 漫画 | No | Yes | Unknown |
| [Crafatar](https://crafatar.com) | Minecraft皮肤和头像API | No | Yes | Yes |
| [Cross Universe](https://crossuniverse.psychpsyo.com/apiDocs.html) | Cross Universe卡牌数据 | No | Yes | Yes |
| [Deck of Cards](http://deckofcardsapi.com/) | 纸牌 | No | No | Unknown |
| [Destiny The Game](https://bungie-net.github.io/multi/index.html) | Bungie平台API | `apiKey` | Yes | Unknown |
| [Digimon Information](https://digimon-api.vercel.app/) | 提供关于数码兽的信息 | No | Yes | Unknown |
| [Digimon TCG](https://documenter.getpostman.com/view/14059948/TzecB4fH) | 在digimoncard.io中搜索数码兽卡牌 | No | Yes | Unknown |
| [Disney](https://disneyapi.dev) | 迪士尼角色信息 | No | Yes | Yes |
| [Dota 2](https://docs.opendota.com/) | 提供关于Dota 2玩家统计、比赛统计、排名的信息 | `apiKey` | Yes | Unknown |
| [Dungeons and Dragons](https://www.dnd5eapi.co/docs/) | 第五版法术、职业、怪物等参考 | No | No | No |
| [Dungeons and Dragons (Alternate)](https://open5e.com/) | 包括来自SRD（系统参考文档）的所有怪物和法术以及搜索API | No | Yes | Yes |
| [Eve Online](https://esi.evetech.net/ui) | 第三方开发者文档 | `OAuth` | Yes | Unknown |
| [FFXIV Collect](https://ffxivcollect.com/) | 最终幻想XIV可收集物品数据 | No | Yes | Yes |
| [FIFA Ultimate Team](https://www.easports.com/fia/ultimate-team/api/fut/item) | FIFA终极球队物品API | No | Yes | Unknown |
| [Final Fantasy XIV](https://xivapi.com/) | 最终幻想XIV游戏数据API | No | Yes | Yes |
| [Fortnite](https://fortnitetracker.com/site-api) | Fortnite统计 | `apiKey` | Yes | Unknown |
| [Forza](https://docs.forza-api.tk) | 显示来自Forza的随机汽车图片 | No | Yes | Unknown |
| [FreeToGame](https://www.freetogame.com/api-doc) | 免费游戏数据库 | No | Yes | Yes |
| [Fun Facts](https://asli-fun-fact-api.herokuapp.com/) | 随机有趣事实 | No | Yes | Yes |
| [FunTranslations](https://api.funtranslations.com/) | 将文本翻译成有趣的语言 | No | Yes | Yes |
| [GamerPower](https://www.gamerpower.com/api-read) | 游戏赠品追踪器 | No | Yes | Yes |
| [GDBrowser](https://gdbrowser.com/api) | 使用Geometry Dash服务器的简单方法 | No | Yes | Unknown |    
| [Geek-Jokes](https://github.com/sameerkumar18/geek-joke-api) | 获取随机的极客/编程相关笑话，用于各种应用程序 | No | Yes | Yes |
| [Genshin Impact](https://genshin.dev) | 原神游戏数据 | No | Yes | Yes |
| [Giant Bomb](https://www.giantbomb.com/api/documentation) | 电子游戏 | `apiKey` | Yes | Unknown |
| [GraphQL Pokemon](https://github.com/favware/graphql-pokemon) | GraphQL驱动的Pokemon API。支持第1到第8代 | No | Yes | Yes |
| [Guild Wars 2](https://wiki.guildwars2.com/wiki/API:Main) | 激战2游戏信息 | `apiKey` | Yes | Unknown |
| [GW2Spidy](https://github.com/rubensayshi/gw2spidy/wiki) | GW2Spidy API，激战2交易市场的物品数据 | No | Yes | Unknown |
| [Halo](https://developer.haloapi.com/) | 光环5和光环战争2信息 | `apiKey` | Yes | Unknown |
| [Hearthstone](http://hearthstoneapi.com/) | 炉石传说卡牌信息 | `X-Mashape-Key` | Yes | Unknown |
| [Humble Bundle](https://rapidapi.com/Ziggoto/api/humble-bundle) | Humble Bundle当前捆绑包 | `apiKey` | Yes | Unknown |
| [Humor](https://humorapi.com) | 幽默、笑话和梗 | `apiKey` | Yes | Unknown |
| [Hypixel](https://api.hypixel.net/) | Hypixel玩家统计 | `apiKey` | Yes | Unknown |
| [Hyrule Compendium](https://github.com/gadhagod/Hyrule-Compendium-API) | 来自塞尔达传说：荒野之息的所有交互物品数据 | No | Yes | Unknown |
| [Hytale](https://hytale-api.com/) | Hytale博客文章和职位 | No | Yes | Unknown |
| [IGDB.com](https://api-docs.igdb.com) | 电子游戏数据库 | `apiKey` | Yes | Unknown |
| [JokeAPI](https://sv443.net/jokeapi/v2/) | 编程、杂项和黑暗笑话 | No | Yes | Yes |
| [Jokes One](https://jokes.one/api/joke/) | 每日笑话和可通过REST API访问的大量笑话类别 | `apiKey` | Yes | Yes |
| [Jservice](http://jservice.io) | Jeopardy问题数据库 | No | No | Unknown |
| [Lichess](https://lichess.org/api) | 访问Lichess上用户、游戏、谜题等的所有数据 | `OAuth` | Yes | Unknown |
| [Magic The Gathering](http://magicthegathering.io/) | 万智牌游戏信息 | No | No | Unknown |
| [Mario Kart Tour](https://mario-kart-tour-api.herokuapp.com/) | 车手、卡丁车、滑翔机和赛道的API | `OAuth` | Yes | Unknown |
| [Marvel](https://developer.marvel.com) | 漫威漫画 | `apiKey` | Yes | Unknown |
| [Minecraft Server Status](https://api.mcsrvstat.us) | 获取Minecraft服务器信息的API | No | Yes | No |    
| [MMO Games](https://www.mmobomb.com/api) | MMO游戏数据库、新闻和赠品 | No | Yes | No |
| [mod.io](https://docs.mod.io) | 跨平台Mod API | `apiKey` | Yes | Unknown |
| [Mojang](https://wiki.vg/Mojang_API) | Mojang / Minecraft API | `apiKey` | Yes | Unknown |
| [Monster Hunter World](https://docs.mhw-db.com/) | 怪物猎人世界数据 | No | Yes | Yes |
| [Open Trivia](https://opentdb.com/api_config.php) | 问答题目 | No | Yes | Unknown |
| [PandaScore](https://developers.pandascore.co/) | 电子竞技游戏和结果 | `apiKey` | Yes | Unknown |
| [Path of Exile](https://www.pathofexile.com/developer/docs) | 流放之路游戏信息 | `OAuth` | Yes | Unknown |
| [PlayerDB](https://playerdb.co/) | 查询Minecraft、Steam和XBox账户 | No | Yes | Unknown |
| [Pokéapi](https://pokeapi.co) | 宝可梦信息 | No | Yes | Unknown |
| [PokéAPI (GraphQL)](https://github.com/mazipan/graphql-pokeapi) | PokéAPI的非官方GraphQL | No | Yes | Yes |
| [Pokémon TCG](https://pokemontcg.io) | 宝可梦TCG信息 | No | Yes | Unknown |
| [Psychonauts](https://psychonauts-api.netlify.app/) | Psychonauts世界角色信息和PSI力量 | No | Yes | Yes |
| [PUBG](https://developer.pubg.com/) | 访问游戏内PUBG数据 | `apiKey` | Yes | Yes |
| [Puyo Nexus](https://github.com/deltadex7/puyodb-api-deno) | 来自Puyo Nexus Wiki的Puyo Puyo信息 | No | Yes | Yes |
| [quizapi.io](https://quizapi.io/) | 访问各种问答题目 | `apiKey` | Yes | Yes |
| [Raider](https://raider.io/api) | 提供魔兽世界团队副本和Mythic+内容的详细角色和公会排名 | No | Yes | Unknown |
| [RAWG.io](https://rawg.io/apidocs) | 50个平台的500,000+游戏，包括移动平台 | `apiKey` | Yes | Unknown |
| [Rick and Morty](https://rickandmortyapi.com) | 所有瑞克和莫蒂的信息，包括图片 | No | Yes | Yes |
| [Riot Games](https://developer.riotgames.com/) | 英雄联盟游戏信息 | `apiKey` | Yes | Unknown |
| [RPS 101](https://rps101.pythonanywhere.com/api) | 石头、剪刀、布加上101个对象 | No | Yes | Yes |
| [RuneScape](https://runescape.wiki/w/Application_programming_interface) | RuneScape和OSRS RPG信息 | No | Yes | No |
| [Sakura CardCaptor](https://github.com/JessVel/sakura-card-captor-api) | 库洛魔法使卡牌信息 | No | Yes | Unknown |
| [Scryfall](https://scryfall.com/docs/api) | 万智牌数据库 | No | Yes | Yes |
| [SpaceTradersAPI](https://spacetraders.io?rel=pub-apis) | 可玩的跨银河空间交易MMOAPI | `OAuth` | Yes | Yes |
| [Steam](https://steamapi.xpaw.me/) | Steam Web API文档 | `apiKey` | Yes | No |
| [Steam](https://github.com/Revadike/InternalSteamWebAPI/wiki) | 内部Steam Web API文档 | No | Yes | No |
| [SuperHeroes](https://superheroapi.com) | 所有超级英雄和反派的数据，来自所有宇宙，统一在一个API中 | `apiKey` | Yes | Unknown |
| [TCGdex](https://www.tcgdex.net/docs) | 多语言宝可梦TCG信息 | No | Yes | Yes |
| [Tebex](https://docs.tebex.io/plugin/) | Tebex API，用于获取游戏购买信息 | `X-Mashape-Key` | Yes | No |
| [TETR.IO](https://tetr.io/about/api/) | TETR.IO Tetra Channel API | No | Yes | Unknown |
| [Tronald Dump](https://www.tronalddump.io/) | 唐纳德·特朗普说过的最蠢的话 | No | Yes | Unknown |
| [Universalis](https://universalis.app/docs/index.html) | 最终幻想XIV市场板数据 | No | Yes | Yes |
| [Valorant (non-official)](https://valorant-api.com) | 包含大多数Valorant游戏内物品、资产等的广泛API | No | Yes | Unknown |
| [Warface (non-official)](https://api.wfstats.cf) | 官方API代理，具有更好的数据结构和更多功能 | No | Yes | No |
| [Wargaming.net](https://developers.wargaming.net/) | Wargaming.net信息和统计 | `apiKey` | Yes | No |
| [When is next MCU film](https://github.com/DiljotSG/MCU-Countdown/blob/develop/docs/API.md) | 即将上映的MCU电影信息 | No | Yes | Unknown |
| [xkcd](https://xkcd.com/json.html) | 以JSON格式检索xkcd漫画 | No | Yes | No |
| [Yu-Gi-Oh!](https://db.ygoprodeck.com/api-guide/) | 游戏王TCG信息 | No | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 餐饮
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [BaconMockup](https://baconmockup.com/) | 可调整大小的培根占位符图片 | No | Yes | Yes |
| [Chomp](https://chompthis.com/api/) | 关于各种杂货产品和食品的数据 | `apiKey` | Yes | Unknown |
| [Coffee](https://coffee.alexflipnote.dev/) | 随机的咖啡图片 | No | Yes | Unknown |
| [Edamam nutrition](https://developer.edamam.com/edamam-docs-nutrition-api) | 营养分析 | `apiKey` | Yes | Unknown |
| [Edamam recipes](https://developer.edamam.com/edamam-docs-recipe-api) | 食谱搜索 | `apiKey` | Yes | Unknown |
| [Foodish](https://github.com/surhud004/Foodish#readme) | 随机美食图片 | No | Yes | Yes |
| [Fruityvice](https://www.fruityvice.com) | 关于各种水果的数据 | No | Yes | Unknown |
| [Kroger](https://developer.kroger.com/reference) | 超市数据 | `apiKey` | Yes | Unknown |
| [LCBO](https://lcboapi.com/) | 酒类 | `apiKey` | Yes | Unknown |
| [Open Brewery DB](https://www.openbrewerydb.org) | 啤酒厂、苹果酒厂和精酿啤酒瓶装店 | No | Yes | Yes |
| [Open Food Facts](https://world.openfoodfacts.org/data) | 食品产品数据库 | No | Yes | Unknown |
| [PunkAPI](https://punkapi.com/) | Brewdog啤酒配方 | No | Yes | Unknown |
| [Rustybeer](https://rustybeer.herokuapp.com/) | 啤酒酿造工具 | No | Yes | No |
| [Spoonacular](https://spoonacular.com/food-api) | 食谱、食品产品和膳食计划 | `apiKey` | Yes | Unknown |
| [Systembolaget](https://api-portal.systembolaget.se) | 瑞典政府拥有的酒类商店 | `apiKey` | Yes | Unknown |
| [TacoFancy](https://github.com/evz/tacofancy-api) | 社区驱动的塔可数据库 | No | No | Unknown |
| [Tasty](https://rapidapi.com/apidojo/api/tasty/) | 查询食谱、计划、成分数据的API | `apiKey` | Yes | Unknown |
| [The Report of the Week](https://github.com/andyklimczak/TheReportOfTheWeek-API) | 食品和饮料评论 | No | Yes | Unknown |
| [TheCocktailDB](https://www.thecocktaildb.com/api.php) | 鸡尾酒配方 | `apiKey` | Yes | Yes |
| [TheMealDB](https://www.themealdb.com/api.php) | 膳食配方 | `apiKey` | Yes | Yes |
| [Untappd](https://untappd.com/api/docs) | 社交啤酒分享 | `OAuth` | Yes | Unknown |
| [What's on the menu?](http://nypl.github.io/menus-api/) | NYPL人工转录的历史菜单收藏 | `apiKey` | No | Unknown |
| [WhiskyHunter](https://whiskyhunter.net/api/) | 过去的在线威士忌拍卖统计数据 | No | Yes | Unknown |
| [Zestful](https://zestfuldata.com/) | 解析食谱成分 | `apiKey` | Yes | Yes |

**[⬆ 返回目录](#index)**


### 财务
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|---|:---|:---|:---|:---|:---|
| [VAT Validation](https://www.abstractapi.com/vat-validation-rates-api) | 验证增值税号码并计算增值税税率 | `apiKey` | Yes | Yes | |
| [Aletheia](https://aletheiaapi.com/) | 内幕交易数据、财报电话分析、财务报表等 | `apiKey` | Yes | Yes | |
| [Alpaca](https://alpaca.markets/docs/api-documentation/api-v2/market-data/alpaca-data-api-v2/) | 所有美国股票和ETF的实时和历史市场数据 | `apiKey` | Yes | Yes | |
| [Alpha Vantage](https://www.alphavantage.co/) | 实时和历史股票数据 | `apiKey` | Yes | Unknown | |
| [apilayer marketstack](https://marketstack.com/) | 实时、日内和历史市场数据API | `apiKey` | Yes | Unknown | |
| [Banco do Brasil](https://developers.bb.com.br/home) | 所有巴西银行金融交易API | `OAuth` | Yes | Yes | |
| [Bank Data API](https://apilayer.com/marketplace/bank_data-api) | 全球即时IBAN和SWIFT号码验证 | `apiKey` | Yes | Unknown | |
| [Billplz](https://www.billplz.com/api) | 支付平台 | `apiKey` | Yes | Unknown | |
| [Binlist](https://binlist.net/) | 公开访问IIN/BIN信息数据库 | No | Yes | Unknown | |
| [Boleto.Cloud](https://boleto.cloud/) | 在巴西生成boletos的API | `apiKey` | Yes | Unknown | |
| [Citi](https://sandbox.developerhub.citi.com/api-catalog-list) | 所有花旗集团账户和报表数据API | `apiKey` | Yes | Unknown | |
| [Econdb](https://www.econdb.com/api/) | 全球宏观经济数据 | No | Yes | Yes | |
| [Fed Treasury](https://fiscaldata.treasury.gov/api-documentation/) | 美国财政部数据 | No | Yes | Unknown | |
| [Finage](https://finage.co.uk) | Finage是股票、货币、加密货币、指数和ETF的实时和历史数据提供商 | `apiKey` | Yes | Unknown | |
| [Financial Modeling Prep](https://site.financialmodelingprep.com/developer/docs) | 实时和历史股票数据 | `apiKey` | Yes | Unknown | |
| [Finnhub](https://finnhub.io/docs/api) | 股票、货币和加密货币的实时RESTful API和Websocket | `apiKey` | Yes | Unknown | |
| [FRED](https://fred.stlouisfed.org/docs/api/fred/) | 来自圣路易斯联邦储备银行的经济数据 | `apiKey` | Yes | Yes | |
| [Front Accounting APIs](https://frontaccounting.com/fawiki/index.php?n=Devel.SimpleAPIModule) | Front会计是一款面向小型企业的多语言多货币软件 | `OAuth` | Yes | Yes | |
| [Hotstoks](https://hotstoks.com?utm_source=public-apis) | 由SQL驱动的股票市场数据 | `apiKey` | Yes | Yes | |
| [IEX Cloud](https://iexcloud.io/docs/api/) | 实时和历史股票和市场数据 | `apiKey` | Yes | Yes | |
| [IG](https://labs.ig.com/gettingstarted) | 差价合约和点差投注市场数据 | `apiKey` | Yes | Unknown | |
| [Indian Mutual Fund](https://www.mfapi.in/) | 获取印度共同基金数据的完整历史 | No | Yes | Unknown | |
| [Intrinio](https://intrinio.com/) | 广泛的金融数据源选择 | `apiKey` | Yes | Unknown | |
| [Klarna](https://docs.klarna.com/klarna-payments/api/payments-api/) | Klarna支付和购物服务 | `apiKey` | Yes | Unknown | |
| [MercadoPago](https://www.mercadopago.com.br/developers/es/reference) | Mercado Pago API参考 - 开发您的集成所需的所有信息 | `apiKey` | Yes | Unknown | |
| [Mono](https://mono.co/) | 连接用户的银行账户并访问非洲的交易数据 | `apiKey` | Yes | Unknown | |
| [Moov](https://docs.moov.io/api/) | Moov API使平台能够简单发送、接收和存储资金 | `apiKey` | Yes | Unknown | |
| [Nordigen](https://nordigen.com/en/account_information_documenation/integration/quickstart_guide/) | 使用官方银行API连接银行账户并获取原始交易数据 | `apiKey` | Yes | Unknown | |
| [OpenFIGI](https://www.openfigi.com/api) | 来自彭博LP的股票、指数、期货、期权符号 | `apiKey` | Yes | Yes | |
| [Plaid](https://www.plaid.com/docs) | 连接用户的银行账户并访问交易数据	 | `apiKey` | YES | |  |
| [Polygon](https://polygon.io/) | 历史股票市场数据 | `apiKey` | Yes | Unknown | |
| [Portfolio Optimizer](https://portfoliooptimizer.io/) | 投资组合分析和优化 | No | Yes | Yes | |
| [Razorpay IFSC](https://razorpay.com/docs/) | 印度金融系统代码（银行分行代码） | No | Yes | Unknown | |
| [Real Time Finance](https://github.com/Real-time-finance/finance-websocket-API/) | 访问实时股票数据的Websocket API | `apiKey` | No | Unknown | |
| [SEC EDGAR Data](https://www.sec.gov/edgar/sec-api-documentation) | 访问美国上市公司年报的API | No | Yes | Yes | |
| [SmartAPI](https://smartapi.angelbroking.com/) | 获得<SmartAPI>的访问权限并创建端到端经纪服务 | `apiKey` | Yes | Unknown | |
| [StockData](https://www.StockData.org) | 实时、日内和历史市场数据、新闻和情绪API | `apiKey` | Yes | Yes | |
| [Styvio](https://www.Styvio.com) | 实时和历史股票数据以及当前股票情绪 | `apiKey` | Yes | Unknown | |
| [Tax Data API](https://apilayer.com/marketplace/tax_data-api) | 全球即时增值税号码和税务验证 | `apiKey` | Yes | Unkown | |
| [Tradier](https://developer.tradier.com) | 美国股票/期权市场数据（延迟、日内、历史） | `OAuth` | Yes | Yes | |
| [Twelve Data](https://twelvedata.com/) | 股票市场数据（实时和历史） | `apiKey` | Yes | Unknown | |
| [WallstreetBets](https://dashboard.nbshare.io/apps/reddit/api/) | WallstreetBets股票评论情绪分析 | No | Yes | Unknown | |
| [Yahoo Finance](https://www.yahoofinanceapi.com/) | 实时低延迟的Yahoo Finance API，用于股票市场、加密货币和货币兑换 | `apiKey` | Yes | Yes | |
| [YNAB](https://api.youneedabudget.com/) | 预算和规划 | `OAuth` | Yes | Yes | |
| [Zoho Books](https://www.zoho.com/books/api/v3/) | 在线会计软件，专为您的业务构建 | `OAuth` | Yes | Unknown | |

**[⬆ 返回目录](#index)**


### 活动
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Eventbrite](https://www.eventbrite.com/platform/api/) | 查找活动 | `OAuth` | Yes | Unknown |
| [SeatGeek](https://platform.seatgeek.com/) | 搜索活动、场馆和表演者 | `apiKey` | Yes | Unknown |
| [Ticketmaster](http://developer.ticketmaster.com/products-and-docs/apis/getting-started/) | 搜索活动、景点或场馆 | `apiKey` | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 环境
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [BreezoMeter Pollen](https://docs.breezometer.com/api-documentation/pollen-api/v2/) | 特定位置的每日花粉条件预报数据 | `apiKey` | Yes | Unknown |
| [Carbon Interface](https://docs.carboninterface.com/) | API to calculate carbon (C02) emissions estimates for common C02 emitting activities | `apiKey` | Yes | Yes |
| [Climatiq](https://docs.climatiq.io) | Calculate the environmental footprint created by a broad range of emission-generating activities | `apiKey` | Yes | Yes |
| [Cloverly](https://www.cloverly.com/carbon-offset-documentation) | API calculates the impact of common carbon-intensive activities in real time | `apiKey` | Yes | Unknown |
| [CO2 Offset](https://co2offset.io/api.html) | API calculates and validates the carbon footprint | No | Yes | Unknown |
| [Danish data service Energi](https://www.energidataservice.dk/) | Open energy data from Energinet to society | No | Yes | Unknown |
| [GrünstromIndex](https://gruenstromindex.de/) | Green Power Index for Germany (Grünstromindex/GSI) | No | No | Yes |
| [IQAir](https://www.iqair.com/air-pollution-data-api) | Air quality and weather data | `apiKey` | Yes | Unknown |
| [Luchtmeetnet](https://api-docs.luchtmeetnet.nl/) | Predicted and actual air quality components for The Netherlands (RIVM) | No | Yes | Unknown |
| [National Grid ESO](https://data.nationalgrideso.com/) | Open data from Great Britain’s Electricity System Operator | No | Yes | Unknown |
| [OpenAQ](https://docs.openaq.org/) | Open air quality data | `apiKey` | Yes | Unknown |
| [PM2.5 Open Data Portal](https://pm25.lass-net.org/#apis) | Open low-cost PM2.5 sensor data | No | Yes | Unknown |
| [PM25.in](http://www.pm25.in/api_doc) | Air quality of China | `apiKey` | No | Unknown |
| [PVWatts](https://developer.nrel.gov/docs/solar/pvwatts/v6/) | Energy production photovoltaic (PV) energy systems | `apiKey` | Yes | Unknown |
| [Srp Energy](https://srpenergy-api-client-python.readthedocs.io/en/latest/api.html) | Hourly usage energy report for Srp customers | `apiKey` | Yes | No |
| [UK Carbon Intensity](https://carbon-intensity.github.io/api-definitions/#carbon-intensity-api-v1-0-0) | The Official Carbon Intensity API for Great Britain developed by National Grid | No | Yes | Unknown |
| [Website Carbon](https://api.websitecarbon.com/) | API to estimate the carbon footprint of loading web pages | No | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 娱乐
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [chucknorris.io](https://api.chucknorris.io) | 手工精选Chuck Norris笑话的JSON API | No | Yes | Unknown |
| [Corporate Buzz Words](https://github.com/sameerkumar18/corporate-bs-generator-api) | 企业流行语的REST API | No | Yes | Yes |
| [Excuser](https://excuser.herokuapp.com/) | 获取各种情况的随机借口 | No | Yes | Unknown |
| [Fun Fact](https://api.aakhilv.me) | 简单的HTTPS API，可从FFA数据库中随机选择并返回事实 | No | Yes | Yes |
| [Imgflip](https://imgflip.com/api) | 获取热门表情包数组 | No | Yes | Unknown |
| [Meme Maker](https://mememaker.github.io/API/) | 用于创建自己的表情包的REST API | No | Yes | Unknown |
| [NaMoMemes](https://github.com/theIYD/NaMoMemes) | 关于纳伦德拉·莫迪的表情包 | No | Yes | Unknown |
| [Random Useless Facts](https://uselessfacts.jsph.pl/) | 获取无用但真实的事实 | No | Yes | Unknown |
| [Techy](https://techy-api.vercel.app/) | 适用于技术术语的JSON和纯文本API | No | Yes | Unknown |
| [Yo Momma Jokes](https://github.com/beanboi7/yomomma-apiv2) | Yo Momma笑话的REST API | No | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 电子邮件
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [apilayer mailboxlayer](https://mailboxlayer.com) | 电子邮件地址验证 | `apiKey` | Yes | Unknown |
| [Email Validation](https://www.abstractapi.com/email-verification-validation-api) | 验证电子邮件地址的可送达性和垃圾邮件 | `apiKey` | Yes | Yes |
| [Cloudmersive Validate](https://cloudmersive.com/validate-api) | 验证电子邮件地址、电话号码、增值税号码和域名 | `apiKey` | Yes | Yes |
| [Disify](https://www.disify.com/) | 验证和检测一次性临时电子邮件地址 | No | Yes | Yes |
| [DropMail](https://dropmail.me/api/#live-demo) | 用于创建和管理临时电子邮件收件箱的GraphQL API | No | Yes | Unknown |
| [EVA](https://eva.pingutil.com/) | 验证电子邮件地址 | No | Yes | Yes |
| [Guerrilla Mail](https://www.guerrillamail.com/GuerrillaMailAPI.html) | 一次性临时电子邮件地址 | No | Yes | Unknown |
| [ImprovMX](https://improvmx.com/api) | 免费电子邮件转发服务的API | `apiKey` | Yes | Unknown |
| [Kickbox](https://open.kickbox.com/) | 电子邮件验证API | No | Yes | Yes |
| [mail.gw](https://docs.mail.gw) | 10分钟邮箱 | No | Yes | Yes |
| [mail.tm](https://docs.mail.tm) | 临时电子邮件服务 | No | Yes | Yes |
| [MailboxValidator](https://www.mailboxvalidator.com/api-email-free) | 验证电子邮件地址以提高送达率 | `apiKey` | Yes | Unknown |
| [MailCheck.ai](https://www.mailcheck.ai/#documentation) | 防止用户使用临时电子邮件地址注册 | No | Yes | Unknown |
| [Mailtrap](https://mailtrap.docs.apiary.io/#) | 用于安全测试开发和暂存环境发送的电子邮件的服务 | `apiKey` | Yes | Unknown |
| [Sendgrid](https://docs.sendgrid.com/api-reference/) | 基于云的SMTP提供商，允许您发送电子邮件而无需维护邮件服务器 | `apiKey` | Yes | Unknown |
| [Sendinblue](https://developers.sendinblue.com/docs) | 提供营销和/或交易电子邮件和/或短信解决方案的服务 | `apiKey` | Yes | Unknown |
| [Verifier](https://verifier.meetchopra.com/docs#/) | 验证给定电子邮件是否真实 | `apiKey` | Yes | Yes |

**[⬆ 返回目录](#index)**


### 文档与生产力
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Airtable](https://airtable.com/api) | 与Airtable集成 | `apiKey` | Yes | Unknown |
| [Api2Convert](https://www.api2convert.com/) | 在线文件转换API | `apiKey` | Yes | Unknown |
| [apilayer pdflayer](https://pdflayer.com) | HTML/URL转PDF | `apiKey` | Yes | Unknown |
| [Asana](https://developers.asana.com/docs) | 以编程方式访问您asana系统中的所有数据 | `apiKey` | Yes | Yes |
| [ClickUp](https://clickup.com/api) | ClickUp是一款强大的基于云的项目管理工具，可提高生产力 | `OAuth` | Yes | Unknown |
| [Clockify](https://clockify.me/developers-api ) | Clockify的基于REST的API可用于向其推送/拉取数据并与其他系统集成 | `apiKey` | Yes | Unknown |
| [CloudConvert](https://cloudconvert.com/api/v2) | 音频、视频、文档、电子书、归档、图像、电子表格、演示文稿的在线文件转换器 | `apiKey` | Yes | Unknown |
| [Cloudmersive Document and Data Conversion](https://cloudmersive.com/convert-api) | HTML/URL转PDF/PNG、Office文档转PDF、图像转换 | `apiKey` | Yes | Yes |
| [Code::Stats](https://codestats.net/api-docs) | 程序员的自动时间跟踪 | `apiKey` | Yes | No |
| [CraftMyPDF](https://craftmypdf.com) | 使用拖放编辑器和简单API从模板生成PDF文档 | `apiKey` | Yes | No |
| [Flowdash](https://docs.flowdash.com/docs/api-introduction) | 自动化业务流程 | `apiKey` | Yes | Unknown |
| [Html2PDF](https://html2pdf.app/) | HTML/URL转PDF | `apiKey` | Yes | Unknown |
| [iLovePDF](https://developer.ilovepdf.com/) | 转换、合并、拆分、提取文本和添加PDF页码。每月250个文档免费 | `apiKey` | Yes | Yes |
| [JIRA](https://developer.atlassian.com/server/jira/platform/rest-apis/) | JIRA是一款专有的问题跟踪产品，允许错误跟踪和敏捷项目管理 | `OAuth` | Yes | Unknown |
| [Mattermost](https://api.mattermost.com/) | 用于开发者协作的开源平台 | `OAuth` | Yes | Unknown |
| [Mercury](https://mercury.postlight.com/web-parser/) | 网络解析器 | `apiKey` | Yes | Unknown |
| [Monday](https://api.developer.monday.com/docs) | 以编程方式访问和更新monday.com账户中的数据 | `apiKey` | Yes | Unknown |
| [Notion](https://developers.notion.com/docs/getting-started) | 与Notion集成 | `OAuth` | Yes | Unknown |
| [PandaDoc](https://developers.pandadoc.com) | DocGen和电子签名API | `apiKey` | Yes | No |
| [Pocket](https://getpocket.com/developer/) | 书签服务 | `OAuth` | Yes | Unknown |
| [Podio](https://developers.podio.com) | 文件共享和生产力 | `OAuth` | Yes | Unknown |
| [PrexView](https://prexview.com) | 将XML或JSON数据转换为PDF、HTML或图像 | `apiKey` | Yes | Unknown |
| [Restpack](https://restpack.io/) | 提供截图、HTML转PDF和内容提取API | `apiKey` | Yes | Unknown |
| [Todoist](https://developer.todoist.com) | 待办事项列表 | `OAuth` | Yes | Unknown |
| [Smart Image Enhancement API](https://apilayer.com/marketplace/image_enhancement-api) | 通过多种超分辨率算法为图像添加细节来执行图像放大 | `apiKey` | Yes | Unknown |
| [Vector Express v2.0](https://vector.express) | 免费矢量文件转换API | No | Yes | No |
| [WakaTime](https://wakatime.com/developers) | 程序员自动时间跟踪排行榜 | No | Yes | Unknown |
| [Zube](https://zube.io/docs/api) | 全栈项目管理 | `OAuth` | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 词典
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Chinese Character Web](http://ccdb.hemiola.com/) | 中文字符定义和发音 | No | No | No |
| [Chinese Text Project](https://ctext.org/tools/api) | 用于现代前中文文本的在线开放获取数字图书馆 | No | Yes | Unknown |
| [Collins](https://api.collinsdictionary.com/api/v1/documentation/html/) | 双语词典和同义词库数据 | `apiKey` | Yes | Unknown |
| [Free Dictionary](https://dictionaryapi.dev/) | 定义、音标、发音、词性、示例、同义词 | No | Yes | Unknown |
| [Indonesia Dictionary](https://new-kbbi-api.herokuapp.com/) | 印尼词典，包含许多单词 | No | Yes | Unknown |
| [Lingua Robot](https://www.linguarobot.io) | 单词定义、音标、同义词、反义词等 | `apiKey` | Yes | Yes |
| [Merriam-Webster](https://dictionaryapi.com/) | 词典和同义词库数据 | `apiKey` | Yes | Unknown |
| [OwlBot](https://owlbot.info/) | 定义，如果可用包括例句和照片 | `apiKey` | Yes | Yes |
| [Oxford](https://developer.oxforddictionaries.com/) | 词典数据 | `apiKey` | Yes | No |
| [Synonyms](https://www.synonyms.com/synonyms_api.php) | 任何给定单词的同义词、同义词库和反义词信息 | `apiKey` | Yes | Unknown |
| [Wiktionary](https://en.wiktionary.org/w/api.php) | 协作词典数据 | No | Yes | Yes |
| [Wordnik](https://developer.wordnik.com) | 词典数据 | `apiKey` | Yes | Unknown |
| [Words](https://www.wordsapi.com/docs/) | 超过150,000个单词的定义和同义词 | `apiKey` | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 开发
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [24 Pull Requests](https://24pullrequests.com/api) | 促进12月开源协作的项目 | No | Yes | Yes |
| [Screenshot](https://www.abstractapi.com/website-screenshot-api) | 以编程方式对任何网站进行截图 | `apiKey` | Yes | Yes |
| [Agify.io](https://agify.io) | 根据名字估算年龄 | No | Yes | Yes |
| [API Grátis](https://apigratis.com.br/) | 多种服务和公共API | No | Yes | Unknown |
| [ApicAgent](https://www.apicagent.com) | 从用户代理字符串中提取设备详细信息 | No | Yes | Yes |
| [ApiFlash](https://apiflash.com/) | 基于Chrome的开发者截图API | `apiKey` | Yes | Unknown |
| [apilayer userstack](https://userstack.com/) | 安全的用户代理字符串查找JSON API | `OAuth` | Yes | Unknown |
| [APIs.guru](https://apis.guru/api-doc/) | Web API的维基百科，公共API的OpenAPI/Swagger规范 | No | Yes | Unknown |
| [Azure DevOps](https://docs.microsoft.com/en-us/rest/api/azure/devops) | Azure DevOps的REST API请求/响应对的基本组件 | `apiKey` | Yes | Unknown |
| [Base](https://www.base-api.io/) | 快速构建后端 | `apiKey` | Yes | Yes |
| [Beeceptor](https://beeceptor.com/) | 在几秒钟内构建模拟REST API端点 | No | Yes | Yes |
| [Bitbucket](https://developer.atlassian.com/bitbucket/api/2/reference/) | Bitbucket API | `OAuth` | Yes | Unknown |
| [Blague.xyz](https://blague.xyz/) | 最大的法语笑话API | `apiKey` | Yes | Yes |
| [Blitapp](https://blitapp.com/api/) | 安排网页截图并同步到您的云端 | `apiKey` | Yes | Unknown |
| [Blynk-Cloud](https://blynkapi.docs.apiary.io/#) | 从Blynk IoT云控制IoT设备 | `apiKey` | No | Unknown |
| [Bored](https://www.boredapi.com/) | 寻找随机活动来对抗无聊 | No | Yes | Unknown |
| [Brainshop.ai](https://brainshop.ai/) | 制作免费AI大脑 | `apiKey` | Yes | Yes |
| [Browshot](https://browshot.com/api/documentation) | 轻松以任何屏幕尺寸、任何设备截取网页截图 | `apiKey` | Yes | Yes |
| [CDNJS](https://api.cdnjs.com/libraries/jquery) | CDNJS上的库信息 | No | Yes | Unknown |
| [Changelogs.md](https://changelogs.md) | 来自开源项目的结构化变更日志元数据 | No | Yes | Unknown |
| [Ciprand](https://github.com/polarspetroll/ciprand) | 安全随机字符串生成器 | No | Yes | No |
| [Cloudflare Trace](https://github.com/fawazahmed0/cloudflare-trace-api) | 获取IP地址、时间戳、用户代理、国家代码、IATA、HTTP版本、TLS/SSL版本及更多 | No | Yes | Yes |
| [Codex](https://github.com/Jaagrav/CodeX) | 多种语言的在线编译器 | No | Yes | Unknown |
| [Contentful Images](https://www.contentful.com/developers/docs/references/images-api/) | 用于检索和对图像应用转换 | `apiKey` | Yes | Yes |
| [CORS Proxy](https://github.com/burhanuday/cors-proxy) | 使用此代理作为中间人来绕过讨厌的CORS错误 | No | Yes | Yes |
| [CountAPI](https://countapi.xyz) | 免费且简单的计数服务。您可以使用它来跟踪页面点击和特定事件 | No | Yes | Yes |
| [Databricks](https://docs.databricks.com/dev-tools/api/latest/index.html) | 管理您的databricks账户、集群、笔记本、作业和工作区的服务 | `apiKey` | Yes | Yes |
| [DigitalOcean Status](https://status.digitalocean.com/api) | 所有DigitalOcean服务的状态 | No | Yes | Unknown |
| [Docker Hub](https://docs.docker.com/docker-hub/api/latest/) | 与Docker Hub交互 | `apiKey` | Yes | Yes |
| [DomainDb Info](https://api.domainsdb.info/) | 域名搜索，查找包含特定单词/短语等的所有域名 | No | Yes | Unknown |
| [ExtendsClass JSON Storage](https://extendsclass.com/json-storage.html) | 简单的JSON存储API | No | Yes | Yes |
| [GeekFlare](https://apidocs.geekflare.com/docs/geekflare-api) | 为网站提供重要的测试和监控方法的大量功能 | `apiKey` | Yes | Unknown |
| [Genderize.io](https://genderize.io) | 根据名字估算性别 | No | Yes | Yes |
| [GETPing](https://www.getping.info) | 用简单的GET请求触发电子邮件通知 | `apiKey` | Yes | Unknown |
| [Ghost](https://ghost.org/) | 将发布的内容获取到您的网站、应用程序或其他嵌入媒体 | `apiKey` | Yes | Yes |
| [GitHub](https://docs.github.com/en/free-pro-team@latest/rest) | 以编程方式利用GitHub仓库、代码和用户信息 | `OAuth` | Yes | Yes |
| [Gitlab](https://docs.gitlab.com/ee/api/) | 以编程方式自动化GitLab交互 | `OAuth` | Yes | Unknown |
| [Gitter](https://developer.gitter.im/docs/welcome) | 开发者聊天 | `OAuth` | Yes | Unknown |
| [Glitterly](https://developers.glitterly.app) | 图像生成API | `apiKey` | Yes | Yes |
| [Google Docs](https://developers.google.com/docs/api/reference/rest) | 读取、写入和格式化Google Docs文档的API | `OAuth` | Yes | Unknown |
| [Google Firebase](https://firebase.google.com/docs) | 谷歌的移动应用开发平台，帮助构建、改进和发展应用 | `apiKey` | Yes | Yes |
| [Google Fonts](https://developers.google.com/fonts/docs/developer_api) | Google Fonts提供的所有系列的元数据 | `apiKey` | Yes | Unknown |
| [Google Keep](https://developers.google.com/keep/api/reference/rest) | 读取、写入和格式化Google Keep笔记的API | `OAuth` | Yes | Unknown |
| [Google Sheets](https://developers.google.com/sheets/api/reference/rest) | 读取、写入和格式化Google Sheets数据的API | `OAuth` | Yes | Unknown |
| [Google Slides](https://developers.google.com/slides/api/reference/rest) | 读取、写入和格式化Google Slides演示文稿的API | `OAuth` | Yes | Unknown |
| [Gorest](https://gorest.co.in/) | 用于测试和原型设计的在线REST API | `OAuth` | Yes | Unknown |
| [Hasura](https://hasura.io/opensource/) | 带有内置授权的GraphQL和REST API引擎 | `apiKey` | Yes | Yes |
| [Heroku](https://devcenter.heroku.com/articles/platform-api-reference/) | REST API以编程方式创建应用、配置附加组件和在Heroku上执行其他任务 | `OAuth` | Yes | Yes |
| [host-t.com](https://host-t.com) | 通过HTTP GET请求进行基本DNS查询 | No | Yes | No |
| [Host.io](https://host.io) | 开发者域名数据API | `apiKey` | Yes | Yes |
| [HTTP2.Pro](https://http2.pro/doc/api) | 测试端点的客户端和服务器HTTP/2协议支持 | No | Yes | Unknown |
| [Httpbin](https://httpbin.org/) | 简单的HTTP请求和响应服务 | No | Yes | Yes |
| [Httpbin Cloudflare](https://cloudflare-quic.com/b/) | 由Cloudflare提供支持的简单HTTP请求和响应服务，支持HTTP/3 | No | Yes | Yes |
| [Hunter](https://hunter.io/api) | 域名搜索、专业邮箱查找、作者查找和邮箱验证的API | `apiKey` | Yes | Unknown |
| [IBM Text to Speech](https://cloud.ibm.com/docs/text-to-speech/getting-started.html) | 将文本转换为语音 | `apiKey` | Yes | Yes |
| [Icanhazepoch](https://icanhazepoch.com) | 获取Unix时间戳 | No | Yes | Yes |
| [Icanhazip](https://major.io/icanhazip-com-faq/) | IP地址API | No | Yes | Yes |
| [IFTTT](https://platform.ifttt.com/docs/connect_api) | IFTTT连接API | No | Yes | Unknown |
| [Image-Charts](https://documentation.image-charts.com/) | 生成图表、二维码和图形图像 | No | Yes | Yes |
| [import.io](http://api.docs.import.io/) | 从网站或RSS源检索结构化数据 | `apiKey` | Yes | Unknown |
| [ip-fast.com](https://ip-fast.com/docs/) | IP地址、国家和城市 | No | Yes | Yes |
| [IP2WHOIS Information Lookup](https://www.ip2whois.com/) | WHOIS域名查询 | `apiKey` | Yes | Unknown |
| [ipfind.io](https://ipfind.io) | IP地址或任何域名的地理位置以及一些其他有用信息 | `apiKey` | Yes | Yes |
| [IPify](https://www.ipify.org/) | 简单的IP地址API | No | Yes | Unknown |
| [IPinfo](https://ipinfo.io/developers) | 另一个简单的IP地址API | No | Yes | Unknown |
| [jsDelivr](https://github.com/jsdelivr/data.jsdelivr.com) | jsDelivr CDN上的包信息和下载统计 | No | Yes | Yes |
| [JSON 2 JSONP](https://json2jsonp.com/) | 将JSON转换为JSONP（实时），便于使用客户端JavaScript进行跨域数据请求 | No | Yes | Unknown |
| [JSONbin.io](https://jsonbin.io) | 免费JSON存储服务。适用于小型Web应用、网站和移动应用 | `apiKey` | Yes | Yes |
| [Kroki](https://kroki.io) | 从文本描述创建图表 | No | Yes | Yes |
| [License-API](https://github.com/cmccandless/license-api/blob/master/README.md) | choosealicense.com的非官方REST API | No | Yes | No |
| [Logs.to](https://logs.to/) | 生成日志 | `apiKey` | Yes | Unknown |
| [Lua Decompiler](https://lua-decompiler.ferib.dev/) | 在线Lua 5.1反编译器 | No | Yes | Yes |
| [MAC address vendor lookup](https://macaddress.io/api) | 检索给定MAC地址或OUI的供应商详情和其他信息 | `apiKey` | Yes | Yes |
| [Micro DB](https://m3o.com/db) | 简单数据库服务 | `apiKey` | Yes | Unknown |
| [MicroENV](https://microenv.com/) | 开发者的假REST API | No | Yes | Unknown |
| [Mocky](https://designer.mocky.io/) | 为REST API端点模拟用户定义的测试JSON | No | Yes | Yes |
| [MY IP](https://www.myip.com/api-docs/) | 获取IP地址信息 | No | Yes | Unknown |
| [Nationalize.io](https://nationalize.io) | 估算名字的国籍 | No | Yes | Yes |
| [Netlify](https://docs.netlify.com/api/get-started/) | Netlify是一个面向可编程网络的托管服务 | `OAuth` | Yes | Unknown |
| [NetworkCalc](https://networkcalc.com/api/docs) | 网络计算器，包括子网、DNS、二进制和安全工具 | No | Yes | Yes |
| [npm Registry](https://github.com/npm/registry/blob/master/docs/REGISTRY-API.md) | 以编程方式查询您喜欢的Node.js库的信息 | No | Yes | Unknown |
| [OneSignal](https://documentation.onesignal.com/docs/onesignal-api) | 推送通知、电子邮件、短信和应用内的自助客户服务参与解决方案 | `apiKey` | Yes | Unknown |
| [Open Page Rank](https://www.domcop.com/openpagerank/) | 使用Page Rank算法计算和比较不同网站指标的API | `apiKey` | Yes | Unknown |
| [OpenAPIHub](https://hub.openapihub.com/) | 一体化API平台 | `X-Mashape-Key` | Yes | Unknown |
| [OpenGraphr](https://opengraphr.com/docs/1.0/overview) | 非常简单的API，用于从URL检索Open Graph数据 | `apiKey` | Yes | Unknown |
| [oyyi](https://oyyi.xyz/docs/1.0) | 用于假数据、图像/视频转换、优化、PDF优化和缩略图生成的API | No | Yes | Yes |
| [PageCDN](https://pagecdn.com/docs/public-api) | PageCDN上JavaScript、CSS和字体库的公共API | `apiKey` | Yes | Yes |
| [Postman](https://www.postman.com/postman/workspace/postman-public-workspace/documentation/12959542-c8142d51-e97c-46b6-bd77-52bb66712c9a) | 测试API的工具 | `apiKey` | Yes | Unknown |
| [ProxyCrawl](https://proxycrawl.com) | 反验证码抓取和爬取服务 | `apiKey` | Yes | Unknown |
| [ProxyKingdom](https://proxykingdom.com) | 轮换代理API，每次请求生成一个可用的代理 | `apiKey` | Yes | Yes |
| [Pusher Beams](https://pusher.com/beams) | Android和iOS的推送通知 | `apiKey` | Yes | Unknown |
| [QR code](https://www.qrtag.net/api/) | 创建一个易于阅读的QR码和URL缩短器 | No | Yes | Yes |
| [QR code](http://goqr.me/api/) | 生成和解码/读取QR码图形 | No | Yes | Unknown |
| [Qrcode Monkey](https://www.qrcode-monkey.com/qr-code-api-with-logo/) | 将定制和独特外观的QR码集成到您的系统或工作流程中 | No | Yes | Yes |
| [QuickChart](https://quickchart.io/) | 生成图表和图形图像 | No | Yes | Yes |
| [Random Stuff](https://api-docs.pgamerx.com/) | 可用于以极快的速度获取AI响应、笑话、梗等 | `apiKey` | Yes | Yes |
| [Rejax](https://rejax.io/) | 反向AJAX服务以通知客户端 | `apiKey` | Yes | No |
| [ReqRes](https://reqres.in/ ) | 托管的REST API，准备响应您的AJAX请求 | No | Yes | Unknown |
| [RSS feed to JSON](https://rss-to-json-serverless-api.vercel.app) | 使用feed URL以JSON格式返回RSS feed | No | Yes | Yes |
| [SavePage.io](https://www.savepage.io) | 免费、RESTful API，用于截取任何桌面或移动网站的截图 | `apiKey` | Yes | Yes |
| [ScrapeNinja](https://scrapeninja.net) | 带有Chrome指纹和住宅代理的抓取API | `apiKey` | Yes | Unknown |
| [ScraperApi](https://www.scraperapi.com) | 轻松构建可扩展的网络爬虫 | `apiKey` | Yes | Unknown |
| [scraperBox](https://scraperbox.com/) | 隐蔽的网络抓取API | `apiKey` | Yes | Yes |
| [scrapestack](https://scrapestack.com/) | 实时、可扩展的代理和网络抓取REST API | `apiKey` | Yes | Unknown |
| [ScrapingAnt](https://scrapingant.com) | 带有简单API的无头Chrome抓取 | `apiKey` | Yes | Unknown |
| [ScrapingDog](https://www.scrapingdog.com/) | 用于网络抓取的代理API | `apiKey` | Yes | Unknown |
| [ScreenshotAPI.net](https://screenshotapi.net/) | 创建像素级精确的网站截图 | `apiKey` | Yes | Yes |
| [Serialif Color](https://color.serialif.com/) | 颜色转换、互补色、灰度和对比文本 | No | Yes | No |
| [serpstack](https://serpstack.com/) | 实时准确的谷歌搜索结果API | `apiKey` | Yes | Yes |
| [Sheetsu](https://sheetsu.com/) | 简单的谷歌表格集成 | `apiKey` | Yes | Unknown |
| [SHOUTCLOUD](http://shoutcloud.io/) | 大写即服务 | No | No | Unknown |
| [Sonar](https://github.com/Cgboal/SonarSearch) | Sonar项目DNS枚举API | No | Yes | Yes |
| [SonarQube](https://sonarcloud.io/web_api) | SonarQube REST API用于检测错误、代码味道和安全漏洞 | `OAuth` | Yes | Unknown |
| [StackExchange](https://api.stackexchange.com/) | 开发者问答论坛 | `OAuth` | Yes | Unknown |
| [Statically](https://statically.io/) | 开发者的免费CDN | No | Yes | Yes |
| [Supportivekoala](https://developers.supportivekoala.com/) | 使用模板自动生成图像 | `apiKey` | Yes | Yes |
| [Tyk](https://tyk.io/open-source/) | API和服务管理平台 | `apiKey` | Yes | Yes |
| [Wandbox](https://github.com/melpon/wandbox/blob/master/kennel2/API.rst) | 支持wandbox.org上提到的35+种语言的代码编译器 | No | Yes | Unknown |
| [WebScraping.AI](https://webscraping.ai/) | 带有内置代理和JS渲染的网络抓取API | `apiKey` | Yes | Yes |
| [ZenRows](https://www.zenrows.com/) | 网络抓取API，可绕过反机器人解决方案，同时提供JS渲染和轮换代理 | `apiKey` | Yes | Unknown |


**[⬆ 返回目录](#index)**


### 数据验证
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|---|:---|:---|:---|:---|:---|
| [Lob.com](https://lob.com/) | 美国地址验证 | `apiKey` | Yes | Unknown | |
| [Postman Echo](https://www.postman-echo.com) | 测试API服务器以接收和返回HTTP方法的值 | No | Yes | Unknown | |
| [PurgoMalum](http://www.purgomalum.com) | 针对亵渎和淫秽的内容验证器 | No | No | Unknown | |
| [US Autocomplete](https://www.smarty.com/docs/cloud/us-autocomplete-pro-api) | Enter address data quickly with real-time address suggestions | `apiKey` | Yes | Yes | |
| [US Extract](https://www.smarty.com/products/apis/us-extract-api) | Extract postal addresses from any text including emails | `apiKey` | Yes | Yes | |
| [US Street Address](https://www.smarty.com/docs/cloud/us-street-api) | Validate and append data for any US postal address | `apiKey` | Yes | Yes | |
| [vatlayer](https://vatlayer.com/documentation) | VAT number validation | `apiKey` | Yes | Unknown | |

**[⬆ 返回目录](#index)**


### 货币兑换
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [1Forge](https://1forge.com/forex-data-api/api-documentation) | 外汇货币市场数据 | `apiKey` | Yes | Unknown |
| [Amdoren](https://www.amdoren.com/currency-api/) | 拥有150多种货币的免费货币API | `apiKey` | Yes | Unknown |
| [apilayer fixer.io](https://fixer.io) | 汇率和货币兑换 | `apiKey` | No | Unknown |
| [Bank of Russia](https://www.cbr.ru/development/SXML/) | 汇率和货币兑换 | No | Yes | Unknown |
| [Currency-api](https://github.com/fawazahmed0/currency-api#readme) | 免费货币汇率API，拥有150+种货币且无速率限制 | No | Yes | Yes |
| [CurrencyFreaks](https://currencyfreaks.com/) | 提供当前和历史货币汇率，免费计划每月1K请求 | `apiKey` | Yes | Yes |
| [Currencylayer](https://currencylayer.com/documentation) | 汇率和货币兑换 | `apiKey` | Yes | Unknown |
| [CurrencyScoop](https://currencyscoop.com/api-documentation) | 实时和历史货币汇率JSON API | `apiKey` | Yes | Yes |
| [Czech National Bank](https://www.cnb.cz/cs/financni_trhy/devizovy_trh/kurzy_devizoveho_trhu/denni_kurz.xml) | 汇率集合 | No | Yes | Unknown |
| [Economia.Awesome](https://docs.awesomeapi.com.br/api-de-moedas) | 葡萄牙语免费货币价格和兑换，无速率限制 | No | Yes | Unknown |
| [ExchangeRate-API](https://www.exchangerate-api.com) | 免费货币兑换 | `apiKey` | Yes | Yes |
| [Exchangerate.host](https://exchangerate.host) | 免费外汇和加密货币汇率API | No | Yes | Unknown |
| [Exchangeratesapi.io](https://exchangeratesapi.io) | 汇率和货币兑换 | `apiKey` | Yes | Yes |
| [Frankfurter](https://www.frankfurter.app/docs) | 汇率、货币兑换和时间序列 | No | Yes | Yes |
| [FreeForexAPI](https://freeforexapi.com/Home/Api) | 主要货币对的实时外汇汇率 | No | Yes | No |
| [National Bank of Poland](http://api.nbp.pl/en.html) | 货币汇率集合（XML和JSON格式数据） | No | Yes | Yes |
| [VATComply.com](https://www.vatcomply.com/documentation) | 汇率、地理位置和增值税号码验证 | No | Yes | Yes |

**[⬆ 返回目录](#index)**


### 加密货币
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [0x](https://0x.org/api) | 用于查询各种流动性池中代币和池统计数据的API | No | Yes | Yes |
| [1inch](https://1inch.io/api/) | 用于查询去中心化交易所的API | No | Yes | Unknown |
| [Alchemy Ethereum](https://docs.alchemy.com/alchemy/) | 以太坊节点即服务提供商 | `apiKey` | Yes | Yes |
| [apilayer coinlayer](https://coinlayer.com) | 实时加密货币汇率 | `apiKey` | Yes | Unknown |
| [Binance](https://github.com/binance/binance-spot-api-docs) | 基于中国的加密货币交易交易所 | `apiKey` | Yes | Unknown |
| [Bitcambio](https://nova.bitcambio.com.br/api/v3/docs#a-public) | 获取交易所中所有交易资产的列表 | No | Yes | Unknown |
| [BitcoinAverage](https://apiv2.bitcoinaverage.com/) | 区块链行业的数字资产价格数据 | `apiKey` | Yes | Unknown |
| [BitcoinCharts](https://bitcoincharts.com/about/exchanges/) | 与比特币网络相关的财务和技术数据 | No | Yes | Unknown |
| [Bitfinex](https://docs.bitfinex.com/docs) | 加密货币交易平台 | `apiKey` | Yes | Unknown |
| [Bitmex](https://www.bitmex.com/app/apiOverview) | 基于香港的实时加密货币衍生品交易平台 | `apiKey` | Yes | Unknown |
| [Bittrex](https://bittrex.github.io/api/v3) | 下一代加密货币交易平台 | `apiKey` | Yes | Unknown |
| [Block](https://block.io/docs/basic) | 比特币支付、钱包和交易数据 | `apiKey` | Yes | Unknown |
| [Blockchain](https://www.blockchain.com/api) | 比特币支付、钱包和交易数据 | `apiKey` | Yes | Unknown |
| [blockfrost Cardano](https://blockfrost.io/) | 与Cardano主网和多个测试网交互 | `apiKey` | Yes | Unknown |
| [Brave NewCoin](https://bravenewcoin.com/developers) | 来自200+交易所的实时和历史加密货币数据 | `apiKey` | Yes | Unknown |
| [BtcTurk](https://docs.btcturk.com/) | 实时加密货币数据、图表和允许买卖的API | `apiKey` | Yes | Yes |
| [Bybit](https://bybit-exchange.github.io/docs/linear/#t-introduction) | 加密货币数据源和算法交易 | `apiKey` | Yes | Unknown |
| [CoinAPI](https://docs.coinapi.io/) | 所有货币交易所在单一API下集成 | `apiKey` | Yes | No |
| [Coinbase](https://developers.coinbase.com) | 比特币、比特币现金、莱特币和以太坊价格 | `apiKey` | Yes | Unknown |
| [Coinbase Pro](https://docs.pro.coinbase.com/#api) | 加密货币交易平台 | `apiKey` | Yes | Unknown |
| [CoinCap](https://docs.coincap.io/) | 通过RESTful API提供实时加密货币价格 | No | Yes | Unknown |
| [CoinDCX](https://docs.coindcx.com/) | 加密货币交易平台 | `apiKey` | Yes | Unknown |
| [CoinDesk](https://old.coindesk.com/coindesk-api/) | CoinDesk的比特币价格指数（BPI），支持多种货币 | No | Yes | Unknown |
| [CoinGecko](http://www.coingecko.com/api) | 加密货币价格、市场以及开发者/社交数据 | No | Yes | Yes |
| [Coinigy](https://coinigy.docs.apiary.io) | 直接与Coinigy账户和交易所交互 | `apiKey` | Yes | Unknown |
| [Coinlib](https://coinlib.io/apidocs) | 加密货币价格 | `apiKey` | Yes | Unknown |
| [Coinlore](https://www.coinlore.com/cryptocurrency-data-api) | 加密货币价格、交易量等 | No | Yes | Unknown |
| [CoinMarketCap](https://coinmarketcap.com/api/) | 加密货币价格 | `apiKey` | Yes | Unknown |
| [Coinpaprika](https://api.coinpaprika.com) | 加密货币价格、交易量等 | No | Yes | Yes |
| [CoinRanking](https://developers.coinranking.com/api/documentation) | 实时加密货币数据 | `apiKey` | Yes | Unknown |
| [Coinremitter](https://coinremitter.com/docs) | 加密货币支付和价格 | `apiKey` | Yes | Unknown |
| [CoinStats](https://documenter.getpostman.com/view/5734027/RzZ6Hzr3?version=latest) | 加密货币追踪器 | No | Yes | Unknown |
| [CryptAPI](https://docs.cryptapi.io/) | 加密货币支付处理器 | No | Yes | Unknown |
| [CryptingUp](https://www.cryptingup.com/apidoc/#introduction) | 加密货币数据 | No | Yes | Unknown |
| [CryptoCompare](https://www.cryptocompare.com/api#) | 加密货币比较 | No | Yes | Unknown |
| [CryptoMarket](https://api.exchange.cryptomkt.com/) | 加密货币交易平台 | `apiKey` | Yes | Yes |
| [Cryptonator](https://www.cryptonator.com/api/) | 加密货币交易所汇率 | No | Yes | Unknown |
| [dYdX](https://docs.dydx.exchange/) | 去中心化加密货币交易所 | `apiKey` | Yes | Unknown |
| [Ethplorer](https://github.com/EverexIO/Ethplorer/wiki/Ethplorer-API) | 以太坊代币、余额、地址、交易历史、合约和自定义结构 | `apiKey` | Yes | Unknown |
| [EXMO](https://documenter.getpostman.com/view/10287440/SzYXWKPi) | 基于英国的加密货币交易所 | `apiKey` | Yes | Unknown |
| [FTX](https://docs.ftx.com/) | 完整的REST、Websocket和FTX API，满足您的算法交易需求 | `apiKey` | Yes | Yes |
| [Gateio](https://www.gate.io/api2) | API提供现货、保证金和期货交易操作 | `apiKey` | Yes | Unknown |
| [Gemini](https://docs.gemini.com/rest-api/) | 加密货币交易所 | No | Yes | Unknown |
| [Hirak Exchange Rates](https://rates.hirak.site/) | 162种货币和300种加密货币之间的汇率，每5分钟更新，准确，无限制 | `apiKey` | Yes | Unknown |
| [Huobi](https://huobiapi.github.io/docs/spot/v1/en/) | 基于塞舌尔的加密货币交易所 | `apiKey` | Yes | Unknown |
| [icy.tools](https://developers.icy.tools/) | 基于GraphQL的NFT API | `apiKey` | Yes | Unknown |
| [Indodax](https://github.com/btcid/indodax-official-api-docs) | 用印尼盾交易比特币和其他资产 | `apiKey` | Yes | Unknown |
| [INFURA Ethereum](https://infura.io/product/ethereum) | 与以太坊主网和多个测试网交互 | `apiKey` | Yes | Yes |
| [Kraken](https://docs.kraken.com/rest/) | 加密货币交易所 | `apiKey` | Yes | Unknown |
| [KuCoin](https://docs.kucoin.com/) | 加密货币交易平台 | `apiKey` | Yes | Unknown |
| [Localbitcoins](https://localbitcoins.com/api-docs/) | 买卖比特币的P2P平台 | No | Yes | Unknown |
| [Mempool](https://mempool.space/api) | 专注于交易费用的比特币API服务 | No | Yes | No |
| [MercadoBitcoin](https://www.mercadobitcoin.com.br/api-doc/) | 巴西加密货币信息 | No | Yes | Unknown |
| [Messari](https://messari.io/api) | 为数千种加密资产提供API端点 | No | Yes | Unknown |
| [Nexchange](https://nexchange2.docs.apiary.io/) | 自动化加密货币兑换服务 | No | No | Yes |
| [Nomics](https://nomics.com/docs/) | 历史和实时加密货币价格和市场数据 | `apiKey` | Yes | Yes |
| [NovaDax](https://doc.novadax.com/en-US/#introduction) | NovaDAX API，用于访问所有市场数据、交易管理端点 | `apiKey` | Yes | Unknown |
| [OKEx](https://www.okex.com/docs/) | 基于塞舌尔的加密货币交易所 | `apiKey` | Yes | Unknown |
| [Poloniex](https://docs.poloniex.com) | 基于美国的数字资产交易所 | `apiKey` | Yes | Unknown |
| [Solana JSON RPC](https://docs.solana.com/developing/clients/jsonrpc-api) | 提供各种与Solana区块链交互的端点 | No | Yes | Unknown |
| [Technical Analysis](https://technical-analysis-api.com) | 加密货币价格和技术分析 | `apiKey` | Yes | No |
| [VALR](https://docs.valr.com/) | 基于南非的加密货币交易所 | `apiKey` | Yes | Unknown |
| [WorldCoinIndex](https://www.worldcoinindex.com/apiservice) | 加密货币价格 | `apiKey` | Yes | Unknown |
| [ZMOK](https://zmok.io) | 以太坊JSON RPC API和Web3提供商 | No | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 持续集成
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Azure DevOps Health](https://docs.microsoft.com/en-us/rest/api/resourcehealth) | 资源健康帮助您诊断和支持当Azure问题影响您的资源时 | `apiKey` | No | No |
| [Bitrise](https://api-docs.bitrise.io/) | 构建工具和流程集成，以创建高效的开发管道 | `apiKey` | Yes | Unknown |
| [Buddy](https://buddy.works/docs/api/getting-started/overview) | 最快的持续集成和持续交付平台 | `OAuth` | Yes | Unknown |
| [CircleCI](https://circleci.com/docs/api/v1-reference/) | 使用持续集成和持续交付自动化软件开发流程 | `apiKey` | Yes | Unknown |
| [Codeship](https://docs.cloudbees.com/docs/cloudbees-codeship/latest/api-overview/) | Codeship是云中的持续集成平台 | `apiKey` | Yes | Unknown |
| [Travis CI](https://docs.travis-ci.com/api/) | Sync your GitHub projects with Travis CI to test your code in minutes | `apiKey` | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 云存储与文件共享
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|---|:---|:---|:---|:---|:---|
| [AnonFiles](https://anonfiles.com/docs/api) | 匿名上传和分享您的文件 | No | Yes | Unknown | |
| [BayFiles](https://bayfiles.com/docs/api) | 上传和分享您的文件 | No | Yes | Unknown | |
| [Box](https://developer.box.com/) | 文件共享和存储 | `OAuth` | Yes | Unknown | |
| [ddownload](https://ddownload.com/api) | 文件共享和存储 | `apiKey` | Yes | Unknown | |
| [Dropbox](https://www.dropbox.com/developers) | 文件共享和存储 | `OAuth` | Yes | Unknown | |
| [File.io](https://www.file.io) | 超级简单的文件共享，方便、匿名和安全 | No | Yes | Unknown | |
| [Filestack](https://www.filestack.com) | Filestack文件上传器和文件上传API | `apiKey` | Yes | Unknown |    |
| [GoFile](https://gofile.io/api) | 免费无限大小文件上传 | `apiKey` | Yes | Unknown | |
| [Google Drive](https://developers.google.com/drive/) | 文件共享和存储 | `OAuth` | Yes | Unknown | |
| [Gyazo](https://gyazo.com/api/docs) | 立即保存和分享屏幕截图 | `apiKey` | Yes | Unknown | |
| [Imgbb](https://api.imgbb.com/) | 简单快捷的私人图像共享 | `apiKey` | Yes | Unknown | |
| [OneDrive](https://developer.microsoft.com/onedrive) | 文件共享和存储 | `OAuth` | Yes | Unknown | |
| [Pantry](https://getpantry.cloud/) | 小型项目的免费JSON存储 | No | Yes | Yes | |
| [Pastebin](https://pastebin.com/doc_api) | 纯文本存储 | `apiKey` | Yes | Unknown | |
| [Pinata](https://docs.pinata.cloud/) | IPFS固定服务API | `apiKey` | Yes | Unknown | |
| [Quip](https://quip.com/dev/automation/documentation) | 群组的文件共享和存储 | `apiKey` | Yes | Yes | |
| [Storj](https://docs.storj.io/dcs/) | 去中心化开源云存储 | `apiKey` | Yes | Unknown | |
| [The Null Pointer](https://0x0.st) | 无废话的文件托管和URL缩短服务 | No | Yes | Unknown | |
| [Web3 Storage](https://web3.storage/) | 免费文件共享和存储，1TB空间 | `apiKey` | Yes | Yes | |

**[⬆ 返回目录](#index)**


### 日历
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Public Holidays](https://www.abstractapi.com/holidays-api) | 通过API获取国家、地区和宗教节假日数据 | `apiKey` | Yes | Yes |
| [Calendarific](https://calendarific.com/) | 全球节假日 | `apiKey` | Yes | Unknown |
| [Checkiday - National Holiday API](https://apilayer.com/marketplace/checkiday-api) | 行业领先的节假日API。超过5000个节假日和数千条描述。受到世界领先公司的信任 | `apiKey` | Yes | Unknown |
| [Church Calendar](http://calapi.inadiutorium.cz/) | 天主教礼仪日历 | No | No | Unknown |
| [Czech Namedays Calendar](https://svatky.adresa.info) | 查找名字并返回命名日日期 | No | No | Unknown |
| [Festivo Public Holidays](https://docs.getfestivo.com/docs/products/public-holidays-api/intro) | Fastest and most advanced public holiday and observance service on the market | `apiKey` | Yes | Yes |
| [Google Calendar](https://developers.google.com/google-apps/calendar/) | Display, create and modify Google calendar events | `OAuth` | Yes | Unknown |
| [Hebrew Calendar](https://www.hebcal.com/home/developer-apis) | Convert between Gregorian and Hebrew, fetch Shabbat and Holiday times, etc | No | No | Unknown |
| [Holidays](https://holidayapi.com/) | Historical data regarding holidays | `apiKey` | Yes | Unknown |
| [LectServe](http://www.lectserve.com) | Protestant liturgical calendar | No | No | Unknown |
| [Nager.Date](https://date.nager.at) | Public holidays for more than 90 countries | No | Yes | No |
| [Namedays Calendar](https://nameday.abalin.net) | Provides namedays for multiple countries | No | Yes | Yes |
| [Non-Working Days](https://github.com/gadael/icsdb) | Database of ICS files for non working days | No | Yes | Unknown |
| [Non-Working Days](https://isdayoff.ru) | Simple REST API for checking working, non-working or short days for Russia, CIS, USA and other | No | Yes | Yes |
| [Russian Calendar](https://github.com/egno/work-calendar) | Check if a date is a Russian holiday or not | No | Yes | No |
| [UK Bank Holidays](https://www.gov.uk/bank-holidays.json) | Bank holidays in England and Wales, Scotland and Northern Ireland | No | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 商业
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|---|:---|:---|:---|:---|:---|
| [Apache Superset](https://superset.apache.org/docs/api) | 管理Superset上的BI仪表板和数据源的API | `apiKey` | Yes | Yes |
| [Charity Search](http://charityapi.orghunter.com/) | 非营利慈善数据 | `apiKey` | No | Unknown 
| [Clearbit Logo](https://clearbit.com/docs#logo-api) | 搜索公司标志并将其嵌入您的项目中 | `apiKey` | Yes | Unknown |
| [Domainsdb.info](https://domainsdb.info/) | 注册域名搜索 | No | Yes | No |
| [Freelancer](https://developers.freelancer.com) | 雇佣自由职业者完成工作 | `OAuth` | Yes | Unknown |
| [Gmail](https://developers.google.com/gmail/api/) | 对用户收件箱的灵活RESTful访问 | `OAuth` | Yes | Unknown |
| [Google Analytics](https://developers.google.com/analytics/) | 收集、配置和分析您的数据以触达正确的受众 | `OAuth` | Yes | Unknown |
| [Instatus](https://instatus.com/help/api) | 通过HTTP REST API发布和更新状态页面的维护和事件 | `apiKey` | Yes | Unknown |
| [Mailchimp](https://mailchimp.com/developer/) | 发送营销活动和交易邮件 | `apiKey` | Yes | Unknown |
| [mailjet](https://www.mailjet.com/) | 可以使用API发送营销电子邮件，并发送用MJML或HTML制作的邮件模板 | `apiKey` | Yes | Unknown |
| [markerapi](https://markerapi.com) | 商标搜索 | No | No | Unknown |
| [ORB Intelligence](https://api.orb-intelligence.com/docs/) | 公司查询 | `apiKey` | Yes | Unknown |
| [Redash](https://redash.io/help/user-guide/integrations-and-api/api) | 访问Redash上的查询和仪表板 | `apiKey` | Yes | Yes |
| [Smartsheet](https://smartsheet.redoc.ly/) | 允许您以编程方式访问Smartsheet数据和账户信息 | `OAuth` | Yes | No |
| [Square](https://developer.squareup.com/reference/square) | 简化支付流程、管理退款并帮助客户在线结账的简单方式 | `OAuth` | Yes | Unknown |
| [SwiftKanban](https://www.digite.com/knowledge-base/swiftkanban/article/api-for-swift-kanban-web-services/#restapi) | Kanban软件，可视化工作，提高组织的交付时间、吞吐量和生产力 | `apiKey` | Yes | Unknown |
| [Tenders in Hungary](https://tenders.guru/hu/api) | 获取匈牙利采购数据的JSON格式 | No | Yes | Unknown |
| [Tenders in Poland](https://tenders.guru/pl/api) | 获取波兰采购数据的JSON格式 | No | Yes | Unknown |
| [Tenders in Romania](https://tenders.guru/ro/api) | 获取罗马尼亚采购数据的JSON格式 | No | Yes | Unknown |
| [Tenders in Spain](https://tenders.guru/es/api) | 获取西班牙采购数据的JSON格式 | No | Yes | Unknown |
| [Tenders in Ukraine](https://tenders.guru/ua/api) | 获取乌克兰采购数据的JSON格式 | No | Yes | Unknown |
| [Tomba email finder](https://tomba.io/api) | 用于B2B销售和电子邮件营销的电子邮件查找器和电子邮件验证器 | `apiKey` | Yes | Yes |
| [Trello](https://developers.trello.com/) | 看板、列表和卡片，帮助您组织和优先处理项目 | `OAuth` | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 图书
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [A Bíblia Digital](https://www.abibliadigital.com.br/en) | 无需担心管理圣经的多个版本 | `apiKey` | Yes | No |
| [Bhagavad Gita](https://docs.bhagavadgitaapi.in) | 开源Shrimad Bhagavad Gita API，包括梵文/英文/印地语21+作者翻译 | `apiKey` | Yes | Yes |
| [Bhagavad Gita](https://bhagavadgita.io/api) | Bhagavad Gita文本 | `OAuth` | Yes | Yes |
| [Bhagavad Gita telugu](https://gita-api.vercel.app) | 泰卢固语和奥里亚语版本的Bhagavad Gita API | No | Yes | Yes |
| [Bible-api](https://bible-api.com/) | 支持多种语言的免费圣经API | No | Yes | Yes |
| [British National Bibliography](http://bnb.data.bl.uk/) | 图书 | No | No | Unknown |
| [Crossref Metadata Search](https://github.com/CrossRef/rest-api-doc) | 图书和文章元数据 | No | Yes | Unknown |
| [Ganjoor](https://api.ganjoor.net) | 经典波斯诗歌作品，包括访问相关手稿、朗诵和音乐曲目 | `OAuth` | Yes | Yes |
| [Google Books](https://developers.google.com/books/) | 图书 | `OAuth` | Yes | Unknown |
| [GurbaniNow](https://github.com/GurbaniNow/api) | 快速准确的Gurbani RESTful API | No | Yes | Unknown |
| [Gutendex](https://gutendex.com/) | 用于从Project Gutenberg图书库获取数据的Web API | No | Yes | Unknown |
| [Open Library](https://openlibrary.org/developers/api) | 图书、图书封面和相关数据 | No | Yes | No |
| [Penguin Publishing](http://www.penguinrandomhouse.biz/webservices/rest/) | 图书、图书封面和相关数据 | No | Yes | Yes |
| [PoetryDB](https://github.com/thundercomb/poetrydb#readme) | 使您能够从我们庞大的诗歌收藏中获取即时数据 | No | Yes | Yes |
| [Quran](https://quran.api-docs.io/) | 支持多种语言的RESTful古兰经API | No | Yes | Yes |
| [Quran Cloud](https://alquran.cloud/api) | RESTful古兰经API，可检索Ayatal、苏拉、Juz或整部古兰经 | No | Yes | Yes |
| [Quran-api](https://github.com/fawazahmed0/quran-api#readme) | 免费古兰经API服务，支持90+种不同语言和400+种翻译 | No | Yes | Yes |
| [Rig Veda](https://aninditabasu.github.io/indica/html/rv.html) | 神和诗人，其分类，以及诗句韵律，包括mandala和sukta编号 | No | Yes | Unknown |
| [The Bible](https://docs.api.bible) | 在一个可发现的地方提供您需要的所有圣经内容 | `apiKey` | Yes | Unknown |
| [Thirukkural](https://api-thirukkural.web.app/) | 1330首Thirukkural诗歌及泰米尔语和英语解释 | No | Yes | Yes |
| [Vedic Society](https://aninditabasu.github.io/indica/html/vs.html) | 吠陀文献中所有名词（名称、地点、动物、事物）的描述 | No | Yes | Unknown |
| [Wizard World](https://wizard-world-api.herokuapp.com/swagger/index.html) | 获取哈利·波特宇宙的信息 | No | Yes | Yes |
| [Wolne Lektury](https://wolnelektury.pl/api/) | 用于获取WolneLektury.pl网站上可用电子书信息的API | No | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 区块链
| API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|---|:---|:---|:---|:---|
| [Bitquery](https://graphql.bitquery.io/ide) | 链上GraphQL API和DEX API | `apiKey` | Yes | Yes |
| [Chainlink](https://chain.link/developer-resources) | 使用Chainlink构建混合智能合约 | No | Yes | Unknown |
| [Chainpoint](https://tierion.com/chainpoint/) | Chainpoint是一个全球性的网络，用于将数据锚定到比特币区块链 | No | Yes | Unknown |
| [Covalent](https://www.covalenthq.com/docs/api/) | 多区块链数据聚合平台 | `apiKey` | Yes | Unknown |
| [Etherscan](https://etherscan.io/apis) | 以太坊浏览器API | `apiKey` | Yes | Yes |
| [Helium](https://docs.helium.com/api/blockchain/introduction/) | Helium是一个全球性的分布式热点网络，创建公共、远距离无线覆盖 | No | Yes | Unknown |
| [Nownodes](https://nownodes.io/) | Blockchain-as-a-service solution that provides high-quality connection via API | `apiKey` | Yes | Unknown |
| [Steem](https://developers.steem.io/) | Blockchain-based blogging and social media website | No | No | No |
| [The Graph](https://thegraph.com) | Indexing protocol for querying networks like Ethereum with GraphQL | `apiKey` | Yes | Unknown |
| [Walltime](https://walltime.info/api.html) | To retrieve Walltime's market info | No | Yes | Unknown |
| [Watchdata](https://docs.watchdata.io) | Provide simple and reliable API access to Ethereum blockchain | `apiKey` | Yes | Unknown |

**[⬆ 返回目录](#index)**


### 身份验证与授权
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Auth0](https://auth0.com) | 易于实施、适应性强的认证和授权平台 | `apiKey` | Yes | Yes |
| [GetOTP](https://otp.dev/en/docs/) | 快速实现OTP流程 | `apiKey` | Yes | No |
| [Micro User Service](https://m3o.com/user) | 用户管理和认证 | `apiKey` | Yes | No |
| [MojoAuth](https://mojoauth.com) | 安全现代的无密码认证平台 | `apiKey` | Yes | Yes |
| [SAWO Labs](https://sawolabs.com) | 通过在您的应用中集成无密码认证来简化登录并改善用户体验 | `apiKey` | Yes | Yes |
| [Stytch](https://stytch.com/) | 现代应用的用户基础设施 | `apiKey` | Yes | No |
| [Warrant](https://warrant.dev/) | 授权和访问控制的API | `apiKey` | Yes | Yes |

**[⬆ 返回目录](#index)**


### 艺术与设计
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [Améthyste](https://api.amethyste.moe/) | 为Discord用户生成图片 | `apiKey` | Yes | Unknown |
| [Art Institute of Chicago](https://api.artic.edu/docs/) | 艺术 | No | Yes | Yes |
| [Colormind](http://colormind.io/api-access/) | 配色方案生成器 | No | No | Unknown |
| [ColourLovers](http://www.colourlovers.com/api) | 获取各种图案、调色板和图像 | No | No | Unknown |
| [Cooper Hewitt](https://collection.cooperhewitt.org/api) | 史密森设计博物馆 | `apiKey` | Yes | Unknown |
| [Dribbble](https://developer.dribbble.com) | 发现世界顶级设计师和创意人员 | `OAuth` | Yes | Unknown |
| [EmojiHub](https://github.com/cheatsnake/emojihub) | 按类别和组获取表情符号 | No | Yes | Yes |
| [Europeana](https://pro.europeana.eu/resources/apis/search) | 欧洲博物馆和画廊内容 | `apiKey` | Yes | Unknown |
| [Harvard Art Museums](https://github.com/harvardartmuseums/api-docs) | 艺术 | `apiKey` | No | Unknown |
| [Icon Horse](https://icon.horse) | 任何网站的favicon，带有后备选项 | No | Yes | Yes |
| [Iconfinder](https://developer.iconfinder.com) | 图标 | `apiKey` | Yes | Unknown |
| [Icons8](https://img.icons8.com/) | 图标（在页面中查找"搜索图标"超链接） | No | Yes | Unknown |
| [Lordicon](https://lordicon.com/) | 带有预设动画的图标 | No | Yes | Yes |
| [Metropolitan Museum of Art](https://metmuseum.github.io/) | 大都会艺术博物馆 | No | Yes | No |
| [Noun Project](http://api.thenounproject.com/index.html) | 图标 | `OAuth` | No | Unknown |
| [PHP-Noise](https://php-noise.com/) | 噪点背景图像生成器 | No | Yes | Yes |
| [Pixel Encounter](https://pixelencounter.com/api) | SVG图标生成器 | No | Yes | No |
| [Rijksmuseum](https://data.rijksmuseum.nl/object-metadata/api/) | RijksMuseum数据 | `apiKey` | Yes | Unknown |
| [Word Cloud](https://wordcloudapi.com/) | 轻松创建词云 | `apiKey` | Yes | Unknown |
| [xColors](https://x-colors.herokuapp.com/) | 生成和转换颜色 | No | Yes | Yes |

**[⬆ 返回目录](#index)**


### 反恶意软件
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [AbuseIPDB](https://docs.abuseipdb.com/) | IP/域名/URL 信誉评估 | `apiKey` | Yes | Unknown |
| [AlienVault Open Threat Exchange (OTX)](https://otx.alienvault.com/api) | IP/域名/URL 信誉评估 | `apiKey` | Yes | Unknown |
| [CAPEsandbox](https://capev2.readthedocs.io/en/latest/usage/api.html) | 恶意软件执行与分析 | `apiKey` | Yes | Unknown |
| [Google Safe Browsing](https://developers.google.com/safe-browsing/) | Google 链接/域名标记 | `apiKey` | Yes | Unknown |
| [MalDatabase](https://maldatabase.com/api-doc.html) | 提供恶意软件数据集和威胁情报源 | `apiKey` | Yes | Unknown |
| [MalShare](https://malshare.com/doc.php) | 恶意软件存档/文件来源 | `apiKey` | Yes | No |
| [MalwareBazaar](https://bazaar.abuse.ch/api/) | 收集和共享恶意软件样本 | `apiKey` | Yes | Unknown |
| [Metacert](https://metacert.com/) | Metacert 链接标记 | `apiKey` | Yes | Unknown |
| [NoPhishy](https://rapidapi.com/Amiichu/api/exerra-phishing-check/) | 检查链接是否为已知钓鱼攻击 | `apiKey` | Yes | Yes |
| [Phisherman](https://phisherman.gg/) | IP/域名/URL 信誉评估 | `apiKey` | Yes | Unknown |
| [Scanii](https://docs.scanii.com/) | 简单的REST API，可扫描提交的文件是否存在威胁 | `apiKey` | Yes | Yes |
| [URLhaus](https://urlhaus-api.abuse.ch/) | 批量查询和下载恶意软件样本 | No | Yes | Yes |
| [URLScan.io](https://urlscan.io/about-api/) | 扫描和分析URL | `apiKey` | Yes | Unknown |
| [VirusTotal](https://www.virustotal.com/en/documentation/public-api/) | VirusTotal 文件/URL 分析 | `apiKey` | Yes | Unknown |
| [Web of Trust](https://support.mywot.com/hc/en-us/sections/360004477734-API-) | IP/域名/URL 信誉评估 | `apiKey` | Yes | Unknown | 

**[⬆ 返回目录](#index)**


### 动漫
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS |
|:---|:---|:---|:---|:---|
| [AniAPI](https://aniapi.com/docs/) | 动漫发现、流媒体和与跟踪器同步 | `OAuth` | Yes | Yes |
| [AniDB](https://wiki.anidb.net/HTTP_API_Definition) | 动漫数据库 | `apiKey` | No | Unknown |
| [AniList](https://github.com/AniList/ApiV2-GraphQL-Docs) | 动漫发现与跟踪 | `OAuth` | Yes | Unknown |
| [AnimeChan](https://github.com/RocktimSaikia/anime-chan) | 动漫语录（超过1万条） | No | Yes | No |
| [AnimeFacts](https://chandan-02.github.io/anime-facts-rest-api/) | 动漫趣闻（超过100条） | No | Yes | Yes |
| [AnimeNewsNetwork](https://www.animenewsnetwork.com/encyclopedia/api.php) | 动漫行业新闻 | No | Yes | Yes |
| [Catboy](https://catboys.com/api) | 猫娘图片、有趣GIF等 | No | Yes | Yes |
| [Danbooru Anime](https://danbooru.donmai.us/wiki_pages/help:api) | 包含数千名动漫艺术家数据库，用于查找优质动漫作品 | `apiKey` | Yes | Yes |
| [Jikan](https://jikan.moe) | 非官方 MyAnimeList API | No | Yes | Yes |
| [Kitsu](https://kitsu.docs.apiary.io/) | 动漫发现平台 | `OAuth` | Yes | Yes |
| [MangaDex](https://api.mangadex.org/docs.html) | 漫画数据库与社区 | `apiKey` | Yes | Unknown |
| [Mangapi](https://rapidapi.com/pierre.carcellermeunier/api/mangapi3/) | 将漫画页面从一种语言翻译成另一种 | `apiKey` | Yes | Unknown |
| [MyAnimeList](https://myanimelist.net/clubs.php?cid=13727) | Anime and 漫画数据库与社区 | `OAuth` | Yes | Unknown |
| [NekosBest](https://docs.nekos.best) | 猫娘图片与动漫角色扮演GIF | No | Yes | Yes |
| [Shikimori](https://shikimori.one/api/doc) | 动漫发现、跟踪、论坛和评分 | `OAuth` | Yes | Unknown |
| [Studio Ghibli](https://ghibliapi.herokuapp.com) | 吉卜力工作室电影资源 | No | Yes | Yes |
| [Trace Moe](https://soruly.github.io/trace.moe-api/#/) | 从截图获取动漫精确场景的有用工具 | No | Yes | No |
| [Waifu.im](https://waifu.im/docs) | 从拥有超过4000张图片和多个标签的图库中获取壁纸图片 | No | Yes | Yes |
| [Waifu.pics](https://waifu.pics/docs) | 动漫图片分享平台 | No | Yes | No |

**[⬆ 返回目录](#index)**


### 动物
API | 描述 | 认证Auth | 支持HTTPS | 跨域CORS 
|:---|:---|:---|:---|:---|
| [AdoptAPet](https://www.adoptapet.com/public/apis/pet_list.html) | 帮助领养宠物的资源 | `apiKey` | Yes | Yes |
| [Axolotl](https://theaxolotlapi.netlify.app/) | 蝾螈图片和趣闻集合 | No | Yes | No |
| [Cat Facts](https://alexwohlbruck.github.io/cat-facts/) | 每日猫咪趣闻 | No | Yes | No | |
| [Cataas](https://cataas.com/) | 猫咪即服务（猫咪图片和GIF） | No | Yes | No |
| [Cats](https://docs.thecatapi.com/) | 来自Tumblr的猫咪图片 | `apiKey` | Yes | No |
| [Dog Facts](https://dukengn.github.io/Dog-facts-API/) | 随机狗狗趣闻 | No | Yes | Yes |
| [Dog Facts](https://kinduff.github.io/dog-api/) | 随机狗狗知识 | No | Yes | Yes |
| [Dogs](https://dog.ceo/dog-api/) | 基于斯坦福狗狗数据集 | No | Yes | Yes |
| [eBird](https://documenter.getpostman.com/view/664302/S1ENwy59) | 获取区域内近期或显著的鸟类观察记录 | `apiKey` | Yes | No |
| [FishWatch](https://www.fishwatch.gov/developers) | 关于单个鱼种的信息和图片 | No | Yes | Yes |
| [HTTP Cat](https://http.cat/) | 适用于每种HTTP状态的猫咪 | No | Yes | Yes |
| [HTTP Dog](https://http.dog/) | 适用于每种HTTP响应状态码的狗狗 | No | Yes | Yes |
| [IUCN](http://apiv3.iucnredlist.org/api/v3/docs) | IUCN 濒危物种红色名录 | `apiKey` | No | No |
| [MeowFacts](https://github.com/wh-iterabb-it/meowfacts) | 获取随机猫咪趣闻 | No | Yes | No |
| [Movebank](https://github.com/movebank/movebank-api-doc) | 动物移动和迁徙数据 | No | Yes | Yes |
| [Petfinder](https://www.petfinder.com/developers/) | 宠物finder致力于帮助宠物找到家，另一个帮助宠物领养的资源 | `apiKey` | Yes | Yes |
| [PlaceBear](https://placebear.com/) | 占位符熊图片 | No | Yes | Yes |
| [PlaceDog](https://place.dog) | 占位符狗狗图片 | No | Yes | Yes |
| [PlaceKitten](https://placekitten.com/) | 占位符小猫图片 | No | Yes | Yes |
| [RandomDog](https://random.dog/woof.json) | 随机狗狗图片 | No | Yes | Yes |
| [RandomDuck](https://random-d.uk/api) | 随机鸭子图片 | No | Yes | No |
| [RandomFox](https://randomfox.ca/floof/) | 随机狐狸图片 | No | Yes | No |
| [RescueGroups](https://userguide.rescuegroups.org/display/APIDG/API+Developers+Guide+Home) | 领养 | No | Yes | Unknown |
| [Shibe.Online](http://shibe.online/) | 随机柴犬、猫咪或鸟类图片 | No | Yes | Yes |
| [The Dog](https://thedogapi.com/) | 关于狗狗的公共服务，制作新应用、网站或服务时可免费使用 | `apiKey` | Yes | No |
| [xeno-canto](https://xeno-canto.org/explore/api) | 鸟类叫声记录 | No | Yes | Unknown |
| [Zoo Animals](https://zoo-animal-api.herokuapp.com/) | 动物园动物的趣闻和图片 | No | Yes | Yes |

**[⬆ 返回目录](#index)**
