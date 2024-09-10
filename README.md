# public-apis-cn项目介绍🔥
- 将public-apis项目翻译为中文版，并收集添加国内常用API
- 欢迎大家点赞🌟和贡献添加、更新现有的API
- 让这个项目成为**中文版免费API大全**。
- 在描述前增加💰/ 🆓，以区分是收费/免费的API。

# 目录
* [AI模型](#AI模型)
* [天气](#天气)
* [国内物流](#国内物流)
* [国际物流](#国际物流)
* [地理](#地理信息)
* [动物](#动物)
* [动漫](#动漫)
* [杀毒软件](#杀毒软件)
* [艺术设计](#艺术设计)
* [认证授权](#认证授权)
* [区块链](#区块链)
* [书籍](#书籍)
* [商业](#商业)
* [日历](#日历)
* [存储文件共享](#存储文件共享)
* [持续集成](#持续集成)
* [加密货币](#加密货币)
* [货币交换](#货币交换)
* [数据验证](#数据验证)
* [开发](#开发)
* [字典](#字典)
* [文档生产力](#文档生产力)
* [电子邮件](#电子邮件)
* [娱乐](#娱乐)
* [生态环境](#生态环境)
* [表演活动](#表演活动)
* [金融](#金融)
* [食品饮料](#食品饮料)
* [游戏漫画](#游戏漫画)
* [政府](#政府)
* [健康](#健康)
* [招聘](#招聘)
* [机器学习](#机器学习)
* [音乐](#音乐)
* [新闻](#新闻)
* [开放数据](#开放数据)
* [开源项目](#开源项目)
* [专利](#专利)
* [个性](#个性)
* [电话](#电话)
* [摄影](#摄影)
* [播客](#播客)
* [编程](#编程)
* [科学数学](#科学数学)
* [安全](#安全)
* [购物](#购物)
* [社交](#社交)
* [体育健身](#体育健身)
* [模拟数据](#模拟数据)
* [文本分析](#文本分析)
* [运输](#运输)
* [网址缩短](#网址缩短)
* [车辆](#车辆)
* [视频](#视频)



## AI模型

`因AI模型需强大的GPU算力，硬件投资、电力成本高，通常收费，免费额度有限，如给予10～20元测试额度，并且会叠加有效期，一般只用于测试`



| API                                                                                   | 描述                                                                                        | 认证方式         | 支持HTTPS |
|---------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|------------------|-------|
| [ChatGLM](https://chatglm.cn) | 🆓+💰智谱清言推出的AI模型，GLM-4-Flash模型免费！视频和图像理解、生成等多模态Plus模型收费 | `apiKey`  | 是    |
| [Ollama](https://ollama.com)                                                 | 🆓 利用本机CPU、GPU快速运行主流开源AI模型                                                   | `无`         | 否    |
| [LM Studio](https://lmstudio.ai)                                              | 🆓 探索、从Hugging Face下载，运行本地AI模型，带聊天窗口           | `无`         | 否    |
| [OpenAI](https://platform.openai.com/)                                                | 💰 ChatGPT官方API服务                                               | `apiKey`         | 是    |
| [Azure OpenAI服务](https://azure.microsoft.com/zh-cn/products/ai-services/openai-service/)  | 💰 微软Azure云提供的OpenAI服务                                             | `apiKey` | 是    |
| [Claude](https://www.anthropic.com/api)                                      | 💰 类似于OpenAI的GPT-4，由Anthropic提供                                                   | `apiKey`         | 是    |
| [llama](https://llama.meta.com)                                                | 🆓 Meta开源AI模型llama，自由下载本地使用                                               | `apiKey`         | 是    |
| [Google Gemini](https://gemini.google.com/)  												| 💰 Google公司推出开源AI模型，以云服务提供API服务                                       | `apiKey` | 是    |
| [Groq](https://www.groq.com/)                                                        | 🆓+💰利用LPU卡替换GPU，加速AI回答，特点是速度快，每秒300～500个tokens。免费帐户：llama3-70限制每分钟6000tokens                         | `apiKey`         | 是    |
| [KIMI](https://platform.moonshot.cn)                              | 💰月之暗面科技研发，特点最早提供超长上下文的AI模型                                    | `apiKey`         | 是    |
| [通义千问](https://tongyi.aliyun.com/)                                                      | 🆓💰阿里巴巴开源AI模型，主要以云服务提供API服务                                                     | `apiKey`         | 是    |
| [文心一言](https://wenxin.baidu.com/)                                          | 💰 百度研发的商用AI模型                                                    | `apiKey`         | 是    |
| [豆包](https://www.volcengine.com/product/doubao)                                        | 💰 火山引擎提供的商用AI模型：Doubao-pro-128k，百万tokens/输入5元/输出9元                                                     | `apiKey`         | 是    |
| [深度求索DeepSeek](https://www.deepseek.com)                                        | 💰 国产新的价格卷王，深度求索公司AI模型：DeepSeek-V2-128K，百万tokens/输入1元/输出2元                                                     | `apiKey`         | 是    |
| [零一万物](https://platform.lingyiwanwu.com/)                                                | 🆓+💰李开复投资的AI模型公司，小模型开源，大模型以API提供服务                                             | `apiKey`         | 是    |
| [孟子](https://www.langboat.com/) | 🆓+💰澜舟科技的孟子3-13B模型开源；标准大模型收费；特点是轻量模型优胜成绩| `apiKey`  | 是    |



## 天气
| API                                                                           | 描述                                | 认证Auth         | 支持HTTPS | 跨域CORS    |
|-------------------------------------------------------------------------------|-----------------------------------|--------------|-------|---------|
| [7Timer!](http://www.7timer.info/doc.php?lang=en)                             | 天气预报                     | 否           | 否    | 未知 |
| [墨迹天气API](https://www.mojicb.com/support)									| 提供分钟级、公里级天气预报     | `apiKey`     | 是   | 未知 |
| [高德天气API](https://lbs.amap.com/api/webservice/guide/api/weatherinfo) 		| 实时和未来数天的天气预报服务           | `apiKey`     | 是   | 未知 |
| [和风天气API](https://www.qweather.com/)                                      | 提供实时、三日、七日天气预报           | `apiKey`     | 是   | 未知 |
| [心知天气API](https://www.seniverse.com/)                                     | 提供实况天气数据和未来三天天气预报       | `apiKey`     | 是   | 未知 |
| [AccuWeather](https://developer.accuweather.com/apis)                         | 天气和预报数据                           | `apiKey`     | 否    | 未知 |
| [Aemet](https://opendata.aemet.es/centrodedescargas/inicio)                   | 西班牙的天气和预报数据                       | `apiKey`     | 是   | 未知 |
| [apilayer weatherstack](https://weatherstack.com/)                            | 实时和历史的全球天气数据API                   | `apiKey`     | 是   | 未知 |
| [APIXU](https://www.apixu.com/doc/request.aspx)                               | 天气数据                              | `apiKey`     | 是   | 未知 |
| [AQICN](https://aqicn.org/api/)                                               | 1000多个城市的空气质量指数数据                 | `apiKey`     | 是   | 未知 |
| [AviationWeather](https://www.aviationweather.gov/dataserver)                 | NOAA航空天气预报和观测数据                   | 否           | 是   | 未知 |
| [ColorfulClouds](https://open.caiyunapp.com/ColorfulClouds_Weather_API)       | 天气数据                              | `apiKey`     | 是   | 是     |
| [Euskalmet](https://opendata.euskadi.eus/api-euskalmet/-/api-de-euskalmet/)   | 巴斯克地区的气象数据                        | `apiKey`     | 是   | 未知 |
| [Foreca](https://developer.foreca.com)                                        | 天气数据                              | `OAuth`      | 是   | 未知 |
| [HG Weather](https://hgbrasil.com/status/weather)                             | 提供巴西城市的天气预报数据                     | `apiKey`     | 是   | 是     |
| [Hong Kong Obervatory](https://www.hko.gov.hk/en/abouthko/opendata_intro.htm) | 提供天气信息、地震信息和气候数据                  | 否           | 是   | 未知 |
| [Meteorologisk Institutt](https://api.met.no/weatherapi/documentation)        | 天气和气候数据                           | `User-Agent` | 是   | 未知 |
| [Meteosource](https://www.meteosource.com/)                                   | 基于机器学习和历史数据的全球天气预报                | `apiKey`     | 是   | 未知 |
| [Met Office DataPoint](https://www.metoffice.gov.uk/services/data/datapoint/) | 英国的天气数据                           | `apiKey`     | 是   | 未知 |
| [Micro Weather](https://m3o.com/weather/api)                                  | 实时天气预报和历史数据                       | `apiKey`     | 是   | 未知 |
| [ODWeather](http://api.oceandrivers.com/static/docs.html)                     | 天气和天气网络摄像头                        | 否           | 否    | 未知 |
| [Oikolab](https://docs.oikolab.com)                                           | 来自NOAA和ECMWF的全球70多年的逐小时历史和预报天气数据  | `apiKey`     | 是   | 是     |
| [Open-Meteo](https://open-meteo.com/)                                         | 面向非商业用途的全球天气预报API                 | 否           | 是   | 是     |
| [openSenseMap](https://api.opensensemap.org/)                                 | 个人气象站（称为senseBoxes）的数据            | 否           | 是   | 是     |
| [OpenUV](https://www.openuv.io)                                               | 实时紫外线指数预报                         | `apiKey`     | 是   | 未知 |
| [OpenWeatherMap](https://openweathermap.org/api)                              | 天气数据                              | `apiKey`     | 是   | 未知 |
| [QWeather](https://dev.qweather.com/en/)                                      | 基于位置的天气数据                         | `apiKey`     | 是   | 是     |
| [RainViewer](https://www.rainviewer.com/api.html)                             | 从互联网上不同网站收集的雷达数据                  | 否           | 是   | 未知 |
| [Storm Glass](https://stormglass.io/)                                         | 来自多个源的全球海洋天气                      | `apiKey`     | 是   | 是     |
| [Tomorrow](https://docs.tomorrow.io)                                          | 使用专有技术提供的天气API                    | `apiKey`     | 是   | 未知 |
| [US Weather](https://www.weather.gov/documentation/services-web-api)          | 美国国家气象局                           | 否           | 是   | 是     |
| [Visual Crossing](https://www.visualcrossing.com/weather-api)                 | 全球历史和天气预报数据                       | `apiKey`     | 是   | 是     |
| [weather-api](https://github.com/robertoduessmann/weather-api)                | 一个用于检查天气的免费RESTful API            | 否           | 是   | 否      |
| [WeatherAPI](https://www.weatherapi.com/)                                     | 天气API，还包括天文和地理位置等其他功能             | `apiKey`     | 是   | 是     |
| [Weatherbit](https://www.weatherbit.io/api)                                   | 天气API                             | `apiKey`     | 是   | 未知 |
| [Yandex.Weather](https://yandex.com/dev/weather/)                             | 评估特定位置的天气状况的API                   | `apiKey`     | 是   | 否      |




**[⬆ 返回目录](#目录)**



## 国内物流
| API                                                                                   | 描述                                   | 认证方式         | 支持HTTPS | 跨域CORS |
|---------------------------------------------------------------------------------------|---------------------------------------|------------------|-------|---------|
| [快递100](https://api.kuaidi100.com/home)                                          | 提供多家快递公司的物流信息查询服务   | `apiKey`         | 是    | 未知    |
| [51Tracking](https://www.51tracking.com/)                                          | 提供全球快递物流查询服务            | `apiKey`         | 是    | 未知    |
| [快递鸟](https://www.kdniao.com/)                                                  | 提供多家物流公司的实时物流信息查询   | `apiKey`         | 是    | 未知    |
| [菜鸟](https://open.cainiao.com/)                                                  | 支持多种物流服务和跨境物流解决方案   | `apiKey` 
| [顺丰速运 (SF Express)](https://open.sf-express.com)                             | 顺丰快递服务和物流解决方案           | `apiKey`         | 是    | 未知     |
| [京东物流 (JD Logistics)](https://open.jdl.com)                                   | 京东物流服务和解决方案                | `apiKey` 
| [极兔速递](https://open.jtexpress.com.cn)                                             | 极兔包裹追踪、运费计算等服务      | `apiKey`         | 是        | 未知       |
| [中通快递 (ZTO Express)](http://open.zto.com)                                      | 中通快递服务和物流解决方案           | `apiKey`         | 是    | 未知     |
| [圆通速递 (YTO Express)](http://open.yto.net.cn)                                   | 圆通快递服务和物流解决方案           | `apiKey`         | 是    | 未知     |
| [申通快递 (STO Express)](http://open.sto.cn)                                      | 申通快递服务和物流解决方案           | `apiKey`         | 是    | 未知     |
| [韵达快递 (Yunda Express)](http://open.yundaex.com)                               | 韵达快递服务和物流解决方案           | `apiKey`         | 是    | 未知     |
| [百世快递 (Best Express)](https://open.800best.com/)                              | 百世快递服务和物流解决方案           | `apiKey`         | 是    | 未知     |
| [德邦物流 (Deppon Logistics)](https://dpopen.deppon.com)                           | 德邦物流服务和解决方案                | `apiKey`         | 是    | 未知     |
| [邮政速递物流 (EMS)](https://api.ems.com.cn)                                       | 邮政速递服务                       | `apiKey`         | 是    | 未知     |


**[⬆ 返回目录](#目录)**





## 国际物流
| API                                                                                   | 描述                                   | 认证方式         | 支持HTTPS | 跨域CORS |
|---------------------------------------------------------------------------------------|----------------------------------------|-----------------|------------|----------|
| [AfterShip](https://www.aftership.com/docs)                                           | 支持超过200家物流公司的物流跟踪和通知    | `apiKey`         | 是         | 未知       |
| [Ship24](https://www.ship24.com/zh/couriers)                                          | 提供多家物流公司的全球包裹追踪服务     | `apiKey`         | 是         | 未知       |
| [Aramex](https://www.aramex.com/us/en/developers)                                     | Aramex快递提供的运费计算、包裹追踪等服务 | `apiKey`         | 是         | 未知       |
| [UPS](https://www.ups.com/cn/zh/business-solutions/expand-your-online-business/upgrade-digital-technology/developer-resource-center.page) | UPS快递的提供包裹追踪、运费计算等服务    | `apiKey` | 是         | 未知       |
| [FedEx](https://www.fedex.com/en-us/developer/web-services.html)                      | 提供物流解决方案和包裹追踪服务          | `apiKey`| 是         | 未知       |
| [DHL](https://developer.dhl.com/)                                                     | DHL的API服务，包括追踪和计费             | `apiKey`         | 是         | 未知       |
| [USPS](https://www.usps.com/business/web-tools-apis/)                                 | 美国邮政服务API，提供多种物流服务       | `apiKey`         | 是         | 未知       |
| [Royal Mail](https://www.royalmail.com/business/tools-services/apis)                  | 英国皇家邮政的包裹追踪等服务        | `apiKey`         | 是         | 未知       |
| [AusPost](https://developers.auspost.com.au/)                                         | 澳大利亚邮政的API服务，提供追踪等        | `apiKey`         | 是         | 未知       |
| [Canada Post](https://www.canadapost-postescanada.ca/info/mc/business/productsservices/developers/tour/howitworks.jsf) | 加拿大邮政的API服务，包括追踪和计费    | `apiKey`         | 是         | 未知       |
| [New Zealand Post](https://www.nzpost.co.nz/business/ecommerce/developer-resource-centre) | 新西兰邮政的API服务，提供追踪等     | `apiKey`         | 是         | 未知       |


**[⬆ 返回目录](#目录)**




**[⬆ 返回目录](#目录)**

## 地理信息

| API                                                                                                                                	| 描述                                                                      	| 认证Auth 	| 支持HTTPS 	| 跨域CORS 	|
|------------------------------------------------------------------------------------------------------------------------------------	|---------------------------------------------------------------------------	|----------	|-----------	|----------	|
| [Abstract IP Geolocation](https://www.abstractapi.com/ip-geolocation-api)                                                          	| 根据IP地址定位网站访问者                                                  	| `apiKey` 	| 是        	| 是       	|
| [Actinia Grass GIS](https://actinia.mundialis.de/api_docs/)                                                                        	| Actinia是一个使用GRASS GIS的开源REST API，用于地理数据                    	| `apiKey` 	| 是        	| 未知     	|
| [administrative-divisons-db](https://github.com/kamikazechaser/administrative-divisions-db)                                        	| 获取一个国家的所有行政区划                                                	| 否       	| 是        	| 是       	|
| [adresse.data.gouv.fr](https://adresse.data.gouv.fr)                                                                               	| 法国地址数据库，包括地理编码和逆向地理编码                                	| 否       	| 是        	| 未知     	|
| [Airtel IP](https://sys.airtel.lv/ip2country/1.1.1.1/?full=true)                                                                   	| IP地理位置API。从多个信息源收集数据                                       	| 否       	| 是        	| 未知     	|
| [Apiip](https://apiip.net/)                                                                                                        	| 根据IP地址获取位置信息                                                    	| `apiKey` 	| 是        	| 是       	|
| [apilayer ipstack](https://ipstack.com/)                                                                                           	| 通过IP地址定位和识别网站访问者                                            	| `apiKey` 	| 是        	| 未知     	|
| [APlace.io](https://aplace.io/en)                                                                                                  	| 地址自动完成和逆向地理编码API                                             	| `apiKey` 	| 是        	| 是       	|
| [Battuta](http://battuta.medunes.net)                                                                                              	| 一种级联位置API（按国家/地区/城市）                                       	| `apiKey` 	| 否        	| 未知     	|
| [BigDataCloud's IP Geolocation API](https://www.bigdatacloud.com/packages/ip-geolocation)                                          	| 提供快速准确的IP地理位置API，以及安全检查和可信区域。                     	| `apiKey` 	| 是        	| 是       	|
| [BigDataCloud's Reverse Geocoding API](https://www.bigdatacloud.com/packages/reverse-geocoding)                                    	| 从地理坐标获取丰富的地点信息。                                            	| `apiKey` 	| 是        	| 是       	|
| [BigDataCloud's Phone and Email Verification API](https://www.bigdatacloud.com/packages/phone-email-verification)                  	| 手机号码和电子邮件地址的语法和格式验证。                                  	| `apiKey` 	| 是        	| 是       	|
| [BigDataCloud's Network Engineering API](https://www.bigdatacloud.com/packages/network-engineering)                                	| 获取IP地址的详细ASN和网络查询。                                           	| `apiKey` 	| 是        	| 是       	|
| [BigDataCloud's Free API](https://www.bigdatacloud.com/packages/free-api)                                                          	| 获得免费的客户端逆向地理编码API和客户端信息API。无需创建账户和API密钥。   	| 否       	| 是        	| 是       	|
| [Bing Maps](https://www.microsoft.com/maps/)                                                                                       	| 基于Bing Maps数据创建/自定义数字地图                                      	| `apiKey` 	| 是        	| 未知     	|
| [bng2latlong](https://www.getthedata.com/bng2latlong)                                                                              	| 将英国OSGB36东部坐标和北部坐标（英国国家网格）转换为WGS84纬度和经度       	| 否       	| 是        	| 是       	|
| [Cartes.io](https://github.com/M-Media-Group/Cartes.io/wiki/API)                                                                   	| 为任何事物创建地图和标记                                                  	| 否       	| 是        	| 未知     	|
| [Cep.la](http://cep.la/)                                                                                                           	| 巴西RESTful API，用于查找街道、邮政编码、社区、城市和州的信息             	| 否       	| 否        	| 未知     	|
| [CitySDK](http://www.citysdk.eu/citysdk-toolkit/)                                                                                  	| 选择欧洲城市的开放API                                                     	| 否       	| 是        	| 未知     	|
| [Country](http://country.is/)                                                                                                      	| 根据IP地址获取访问者的国家                                                	| 否       	| 是        	| 是       	|
| [CountryStateCity](https://countrystatecity.in/)                                                                                   	| 提供JSON、SQL、XML、YAML和CSV格式的世界各国、州、地区、省、城市和城镇数据 	| `apiKey` 	| 是        	| 是       	|
| [Ducks Unlimited](https://gis.ducks.org/datasets/du-university-chapters/api)                                                       	| API资源浏览器，提供带有JSON响应的位置和城市查询URL                        	| 否       	| 是        	| 否       	|
| [FreeGeoIP](https://freegeoip.app/)                                                                                                	| 免费的地理IP信息，无需注册。每小时限制为15,000次请求。                    	| 否       	| 是        	| 是       	|
| [GeoApi](https://api.gouv.fr/api/geoapi.html)                                                                                      	| 法国地理数据                                                              	| 否       	| 是        	| 未知     	|
| [Geoapify](https://www.geoapify.com/api/geocoding-api/)                                                                            	| 正向和逆向地理编码，地址自动完成                                          	| `apiKey` 	| 是        	| 是       	|
| [Geocod.io](https://www.geocod.io/)                                                                                                	| 批量地址地理编码/逆向地理编码                                             	| `apiKey` 	| 是        	| 未知     	|
| [Geocode.xyz](https://geocode.xyz/api)                                                                                             	| 提供全球范围内的正向/逆向地理编码、批量地理编码和地理解析                 	| 否       	| 是        	| 未知     	|
| [Geocodify.com](https://geocodify.com/)                                                                                            	| 全球范围内的地址地理编码、地理解析和地址自动完成                          	| `apiKey` 	| 是        	| 是       	|
| [Geodata.gov.gr](https://geodata.gov.gr/en/)                                                                                       	| 希腊的开放地理空间数据和API服务                                           	| 否       	| 是        	| 未知     	|
| [GeoDataSource](https://www.geodatasource.com/web-service)                                                                         	| 使用纬度和经度坐标通过城市名称进行地理编码                                	| `apiKey` 	| 是        	| 未知     	|
| [GeoDB Cities](http://geodb-cities-api.wirefreethought.com/)                                                                       	| 获取全球城市、地区和国家的数据                                            	| `apiKey` 	| 是        	| 未知     	|
| [GeographQL](https://geographql.netlify.app)                                                                                       	| 国家、州和城市的GraphQL API                                               	| 否       	| 是        	| 是       	|
| [GeoJS](https://www.geojs.io/)                                                                                                     	| ChatOps集成的IP地理位置                                                   	| 否       	| 是        	| 是       	|
| [Geokeo](https://geokeo.com)                                                                                                       	| Geokeo地理编码服务-每天免费提供2500个API请求                              	| 否       	| 是        	| 是       	|
| [GeoNames](http://www.geonames.org/export/web-services.html)                                                                       	| 地名和其他地理数据                                                        	| 否       	| 否        	| 未知     	|
| [geoPlugin](https://www.geoplugin.com)                                                                                             	| IP地理位置和货币转换                                                      	| 否       	| 是        	| 是       	|
| [Google Earth Engine](https://developers.google.com/earth-engine/)                                                                 	| 用于行星尺度环境数据分析的基于云的平台                                    	| `apiKey` 	| 是        	| 未知     	|
| [Google Maps](https://developers.google.com/maps/)                                                                                 	| 基于Google Maps数据创建/自定义数字地图                                    	| `apiKey` 	| 是        	| 未知     	|
| [Graph Countries](https://github.com/lennertVanSever/graphcountries)                                                               	| 国家相关的数据，如货币、语言、国旗、地区+子地区和邻国                     	| 否       	| 是        	| 未知     	|
| [HelloSalut](https://fourtonfish.com/project/hellosalut-api/)                                                                      	| 根据用户语言获取hello的翻译                                               	| 否       	| 是        	| 未知     	|
| [HERE Maps](https://developer.here.com)                                                                                            	| 基于HERE Maps数据创建/自定义数字地图                                      	| `apiKey` 	| 是        	| 未知     	|
| [Hong Kong GeoData Store](https://geodata.gov.hk/gs/)                                                                              	| 访问香港地理数据的API                                                     	| 否       	| 是        	| 未知     	|
| [IBGE](https://servicodados.ibge.gov.br/api/docs/)                                                                                 	| 巴西地理与统计研究所（IBGE）的综合服务                                    	| 否       	| 是        	| 未知     	|
| [IP 2 Country](https://ip2country.info)                                                                                            	| 将IP映射到一个国家                                                        	| 否       	| 是        	| 未知     	|
| [IP Address Details](https://ipinfo.io/)                                                                                           	| 使用IP地址查找地理位置                                                    	| 否       	| 是        	| 未知     	|
| [IP Vigilante](https://www.ipvigilante.com/)                                                                                       	| 免费IP地理位置API                                                         	| 否       	| 是        	| 未知     	|
| [ip-api](https://ip-api.com/docs)                                                                                                  	| 使用IP地址或域名查找位置                                                  	| 否       	| 否        	| 未知     	|
| [IP2Location](https://www.ip2location.com/web-service/ip2location)                                                                 	| IP地理位置Web服务，提供55多个参数                                         	| `apiKey` 	| 是        	| 未知     	|
| [IP2Proxy](https://www.ip2location.com/web-service/ip2proxy)                                                                       	| 使用IP地址检测代理和VPN                                                   	| `apiKey` 	| 是        	| 未知     	|
| [ipapi.co](https://ipapi.co/api/#introduction)                                                                                     	| 查找IP地址的位置信息                                                      	| 否       	| 是        	| 是       	|
| [ipapi.com](https://ipapi.com/)                                                                                                    	| 实时地理位置和逆向IP查找REST API                                          	| `apiKey` 	| 是        	| 未知     	|
| [IPGEO](https://api.techniknews.net/ipgeo/)                                                                                        	| 提供有用信息的无限免费IP地址API                                           	| 否       	| 是        	| 未知     	|
| [ipgeolocation](https://ipgeolocation.io/)                                                                                         	| 具有免费计划的IP地理位置API，每月30,000个请求                             	| `apiKey` 	| 是        	| 是       	|
| [IPInfoDB](https://www.ipinfodb.com/api)                                                                                           	| 免费的IP地址地理位置工具和API，可通过IP地址进行国家、地区、城市和时区查询 	| `apiKey` 	| 是        	| 未知     	|
| [Kakao Maps](https://apis.map.kakao.com)                                                                                           	| Kakao Maps提供多个韩国地图API                                             	| `apiKey` 	| 是        	| 未知     	|
| [keycdn IP Location Finder](https://tools.keycdn.com/geo)                                                                          	| 通过简单的REST API获取IP地理位置数据。所有响应都以JSON编码                	| `apiKey` 	| 是        	| 未知     	|
| [LocationIQ](https://locationiq.org/docs/)                                                                                         	| 提供正向/逆向地理编码和批量地理编码                                       	| `apiKey` 	| 是        	| 是       	|
| [Longdo Map](https://map.longdo.com/docs/)                                                                                         	| 泰国交互式地图，包含详细的地点和信息门户网站                              	| `apiKey` 	| 是        	| 是       	|
| [Mapbox](https://docs.mapbox.com/)                                                                                                 	| 创建/定制美丽的数字地图                                                   	| `apiKey` 	| 是        	| 未知     	|
| [MapQuest](https://developer.mapquest.com/)                                                                                        	| 访问工具和资源以绘制全球地图                                              	| `apiKey` 	| 是        	| 否       	|
| [Mexico](https://github.com/IcaliaLabs/sepomex)                                                                                    	| 墨西哥RESTful邮政编码API                                                  	| 否       	| 是        	| 未知     	|
| [Nominatim](https://nominatim.org/release-docs/latest/api/Overview/)                                                               	| 提供全球范围内的正向/逆向地理编码                                         	| 否       	| 是        	| 是       	|
| [One Map, Singapore](https://www.onemap.gov.sg/docs/)                                                                              	| 新加坡土地管理局REST API服务，用于新加坡地址                              	| `apiKey` 	| 是        	| 未知     	|
| [OnWater](https://onwater.io/)                                                                                                     	| 确定纬度/经度是否在水域或陆地上                                           	| 否       	| 是        	| 未知     	|
| [Open Topo Data](https://www.opentopodata.org)                                                                                     	| 获取特定纬度和经度的海拔和海洋深度                                        	| 否       	| 是        	| 否       	|
| [OpenCage](https://opencagedata.com)                                                                                               	| 使用开放数据进行正向和逆向地理编码                                        	| `apiKey` 	| 是        	| 是       	|
| [openrouteservice.org](https://openrouteservice.org/)                                                                              	| 方向、兴趣点、等值线、地理编码（+逆向）、高程等                           	| `apiKey` 	| 是        	| 未知     	|
| [OpenStreetMap](http://wiki.openstreetmap.org/wiki/API)                                                                            	| 导航、地理位置和地理数据                                                  	| `OAuth`  	| 否        	| 未知     	|
| [Pinball Map](https://pinballmap.com/api/v1/docs)                                                                                  	| 公共弹球机的众包地图                                                      	| 否       	| 是        	| 是       	|
| [positionstack](https://positionstack.com/)                                                                                        	| 正向和逆向批量地理编码REST API                                            	| `apiKey` 	| 是        	| 未知     	|
| [Postali](https://postali.app/api)                                                                                                 	| 墨西哥邮政编码API                                                         	| 否       	| 是        	| 是       	|
| [PostcodeData.nl](http://api.postcodedata.nl/v1/postcode/?postcode=1211EP&amp;streetnumber=60&amp;ref=domeinnaam.nl&amp;type=json) 	| 根据邮政编码提供荷兰地址的地理位置数据                                    	| 否       	| 否        	| 未知     	|
| [Postcodes.io](https://postcodes.io)                                                                                               	| 英国邮政编码查询和地理位置                                                	| 否       	| 是        	| 是       	|
| [Queimadas INPE](https://queimadas.dgi.inpe.br/queimadas/dados-abertos/)                                                           	| 访问热点聚焦数据（可能的森林火灾）                                        	| 否       	| 是        	| 未知     	|
| [REST Countries](https://restcountries.com)                                                                                        	| 通过RESTful API获取有关国家的信息                                         	| 否       	| 是        	| 是       	|
| [RoadGoat Cities](https://www.roadgoat.com/business/cities-api)                                                                    	| 城市内容和照片API                                                         	| `apiKey` 	| 是        	| 否       	|
| [Rwanda Locations](https://rapidapi.com/victorkarangwa4/api/rwanda)                                                                	| 卢旺达：省份、城市、区/县、村庄和街道                                     	| 否       	| 是        	| 未知     	|
| [SLF](https://github.com/slftool/slftool.github.io/blob/master/API.md)                                                             	| 德国城市、国家、河流数据库                                                	| 否       	| 是        	| 是       	|
| [SpotSense](https://spotsense.io/)                                                                                                 	| 为移动应用添加基于位置的交互功能                                          	| `apiKey` 	| 是        	| 未知     	|
| [Telize](https://rapidapi.com/fcambus/api/telize/)                                                                                 	| Telize提供任何IP地址的位置信息                                            	| `apiKey` 	| 是        	| 是       	|
| [TomTom](https://developer.tomtom.com/)                                                                                            	| 地图、路线、地点和交通API                                                 	| `apiKey` 	| 是        	| 是       	|
| [Uebermaps](https://uebermaps.com/api/v2)                                                                                          	| 发现并与朋友分享地图                                                      	| `apiKey` 	| 是        	| 未知     	|
| [US ZipCode](https://www.smarty.com/docs/cloud/us-zipcode-api)                                                                     	| 验证并补充任何美国邮政编码的数据                                          	| `apiKey` 	| 是        	| 是       	|
| [Utah AGRC](https://api.mapserv.utah.gov)                                                                                          	| 犹他州Web API，用于对犹他州地址进行地理编码                               	| `apiKey` 	| 是        	| 未知     	|
| [ViaCep](https://viacep.com.br)                                                                                                    	| 巴西RESTful邮政编码API                                                    	| 否       	| 是        	| 未知     	|
| [What3Words](https://what3words.com)                                                                                               	| 世界范围内可记忆和唯一的三个单词坐标                                      	| `apiKey` 	| 是        	| 未知     	|
| [Yandex.Maps Geocoder](https://yandex.com/dev/maps/geocoder)                                                                       	| 使用地理编码从地址获取对象的坐标                                          	| `apiKey` 	| 是        	| 未知     	|
| [ZipCodeAPI](https://www.zipcodeapi.com)                                                                                           	| 美国邮政编码距离、半径和位置API                                           	| `apiKey` 	| 是        	| 未知     	|
| [Zippopotam.us](http://www.zippopotam.us)                                                                                          	| 获取有关地点的信息，如国家、城市、州等                                    	| 否       	| 否        	| 未知     	|
| [Ziptastic](https://ziptasticapi.com/)                                                                                             	| 获取任何美国邮政编码的国家、州和城市                                      	| 否       	| 是        	| 未知     	|
| [Zipcodestack](https://zipcodestack.com/)                                                                                          	| 邮政编码API-免费的邮政编码验证                                            	| `apiKey` 	| 是        	| 未知     	|

**[⬆ 返回目录](#目录)**


## 动物

 API                                                                                        | 描述                          | 认证Auth         | 支持HTTPS | 跨域CORS    
--------------------------------------------------------------------------------------------|--------------------------------------|----------|-------|---------
 [AdoptAPet](https://www.adoptapet.com/public/apis/pet_list.html)                           |  - 帮助宠物被领养的资源                        | `apiKey` | 是   | 是     
 [Cat Facts](https://alexwohlbruck.github.io/cat-facts/)                                    |  - 每日猫咪知识                            | 否       | 是   | 否      
 [Cataas](https://cataas.com/)                                                              |  - 猫咪服务（猫咪图片和gif）                    | 否       | 是   | 否      
 [Cats](https://developers.thecatapi.com/)                                                  |  - 来自Tumblr的猫咪图片                     | `apiKey` | 是   | 否      
 [Dog Facts](https://kinduff.github.io/dog-api/)                                            |  - 随机狗狗知识                            | 否       | 是   | 是     
 [Dogs](https://dog.ceo/dog-api/)                                                           |  - 基于斯坦福大学的狗狗数据集                     | 否       | 是   | 是     
 [eBird](https://documenter.getpostman.com/view/664302/S1ENwy59)                            |  - 检索某个地区最近或值得注意的观鸟记录                | `apiKey` | 是   | 否      
 [FishWatch](https://www.fishwatch.gov/developers)                                          |  - 有关个别鱼类物种的信息和图片                    | 否       | 是   | 是     
 [HTTP Cat](https://http.cat/)                                                              |  - 每个HTTP状态对应一只猫                     | 否       | 是   | 是     
 [HTTP Dog](https://http.dog/)                                                              |  - 每个HTTP响应状态码对应一只狗                  | 否       | 是   | 是     
 [IUCN](http://apiv3.iucnredlist.org/api/v3/docs)                                           |  - IUCN濒危物种红色名录                      | `apiKey` | 否    | 否      
 [MeowFacts](https://github.com/wh-iterabb-it/meowfacts)                                    |  - 获取随机猫咪知识                          | 否       | 是   | 否      
 [Movebank](https://github.com/movebank/movebank-api-doc)                                   |  - 动物的运动和迁移数据                        | 否       | 是   | 是     
 [Petfinder](https://www.petfinder.com/developers/)                                         |  - Petfinder致力于帮助宠物找到家，另一个帮助宠物被领养的资源 | `apiKey` | 是   | 是     
 [PlaceBear](https://placebear.com/)                                                        |  - 占位符熊图片                            | 否       | 是   | 是     
 [PlaceDog](https://place.dog)                                                              |  - 占位符狗狗图片                           | 否       | 是   | 是     
 [PlaceKitten](https://placekitten.com/)                                                    |  - 占位符小猫图片                           | 否       | 是   | 是     
 [Quokkas](https://quokka.pics/)                                                            |  - 随机沙袋鼠图片                           | 否       | 是   | 是     
 [RandomBigCat](https://randombig.cat/roar.json)                                            |  - 随机大型猫科动物图片                        | 否       | 是   | 是     
 [RandomDog](https://random.dog/woof.json)                                                  |  - 随机狗狗图片                            | 否       | 是   | 是     
 [RandomDuck](https://random-d.uk/api)                                                      |  - 随机鸭子图片                            | 否       | 是   | 否      
 [RandomFox](https://randomfox.ca/floof/)                                                   |  - 随机狐狸图片                            | 否       | 是   | 否      
 [RescueGroups](https://userguide.rescuegroups.org/display/APIDG/API+Developers+Guide+Home) |  - 领养                                | 否       | 是   | 未知 
 [Shibe.Online](http://shibe.online/)                                                       |  - 随机柴犬、猫或鸟类图片                       | 否       | 是   | 是     
 [The Dog](https://thedogapi.com/)                                                          |  - 关于狗的公共服务，制作时可免费使用您的新应用程序、网站或服务    | `apiKey` | 是   | 否      
 [xeno-canto](https://xeno-canto.org/explore/api)                                           |  - 鸟类录音                              | 否       | 是   | 未知 

**[⬆ 返回目录](#目录)**

## 动漫

 API                                                                       | 描述                       | 认证Auth         | 支持HTTPS | 跨域CORS    
---------------------------------------------------------------------------|-----------------------------------|----------|-------|---------
 [AniDB](https://wiki.anidb.net/HTTP_API_Definition)                       | - 动漫数据库                           | `apiKey` | 否    | 是     
 [AniList](https://github.com/AniList/ApiV2-GraphQL-Docs)                  | - 动漫发现和追踪                         | `OAuth`  | 是   | 未知 
 [AnimeChan](https://github.com/RocktimSaikia/anime-chan)                  | - 动漫语录（超过10k+）                    | 否       | 是   | 否      
 [AnimeFacts](https://chandan-02.github.io/anime-facts-rest-api/)          | - 动漫知识（超过100+）                    | 否       | 是   | 是     
 [AnimeNewsNetwork](https://www.animenewsnetwork.com/encyclopedia/api.php) | - 动漫行业新闻                          | 否       | 是   | 是     
 [Catboy](https://catboys.com/api)                                         | - Neko图片、有趣的GIF等等                 | 否       | 是   | 是     
 [Danbooru Anime](https://danbooru.donmai.us/wiki_pages/help:api)          | - 数千个动漫艺术家数据库，以找到好的动漫艺术品          | `apiKey` | 是   | 是     
 [Jikan](https://jikan.moe)                                                | - 非官方MyAnimeList API              | 否       | 是   | 是     
 [Kitsu](https://kitsu.docs.apiary.io/)                                    | - 动漫发现平台                          | `OAuth`  | 是   | 是     
 [MangaDex](https://api.mangadex.org/docs/)                                | - 漫画数据库和社区                        | `apiKey` | 是   | 未知 
 [Mangapi](https://rapidapi.com/pierre.carcellermeunier/api/mangapi3/)     | - 将漫画页面从一种语言翻译成另一种语言              | `apiKey` | 是   | 未知 
 [MyAnimeList](https://myanimelist.net/clubs.php?cid=13727)                | - 动漫和漫画数据库和社区                     | `OAuth`  | 是   | 未知 
 [NekosBest](https://docs.nekos.best)                                      | - Neko图片和动漫角色扮演GIF                | 否       | 是   | 是     
 [Shikimori](https://shikimori.one/api/doc)                                | - 动漫发现、追踪、论坛、评分                   | `OAuth`  | 是   | 未知 
 [Trace Moe](https://soruly.github.io/trace.moe-api/#/)                    | - 从截图中获取动画的确切场景的有用工具              | 否       | 是   | 否      
 [Waifu.im](https://waifu.im/docs)                                         | - 从一个包含4000多张图片和多个标签的存档中获取waifu图片 | 否       | 是   | 是     
 [Waifu.pics](https://waifu.pics/docs)                                     | - 动漫图片共享平台                        | 否       | 是   | 否      

**[⬆ 返回目录](#目录)**

## 杀毒软件

 API                                                                           | 描述                    | 认证Auth         | 支持HTTPS | 跨域CORS    
-------------------------------------------------------------------------------|--------------------------------|----------|-------|---------
 [AbuseIPDB](https://docs.abuseipdb.com/)                                      | IP/域名/URL声誉                    | `apiKey` | 是   | 未知 
 [AlienVault Open Threat Exchange (OTX)](https://otx.alienvault.com/api)       | IP/域名/URL声誉                    | `apiKey` | 是   | 未知 
 [CAPEsandbox](https://capev2.readthedocs.io/en/latest/usage/api.html)         | 恶意软件执行和分析                      | `apiKey` | 是   | 未知 
 [Google Safe Browsing](https://developers.google.com/safe-browsing/)          | 谷歌链接/域名标记                      | `apiKey` | 是   | 未知 
 [MalDatabase](https://maldatabase.com/api-doc.html)                           | 提供恶意软件数据集和威胁情报源                | `apiKey` | 是   | 未知 
 [MalShare](https://malshare.com/doc.php)                                      | 恶意软件档案/文件来源                    | `apiKey` | 是   | 否      
 [MalwareBazaar](https://bazaar.abuse.ch/api/)                                 | 收集和分享恶意软件样本                    | `apiKey` | 是   | 未知 
 [Metacert](https://metacert.com/)                                             | Metacert链接标记                   | `apiKey` | 是   | 未知 
 [NoPhishy](https://rapidapi.com/Amiichu/api/exerra-phishing-check/)           | 检查链接是否为已知的钓鱼尝试                 | `apiKey` | 是   | 是     
 [Phisherman](https://phisherman.gg/)                                          | IP/域名/URL声誉                    | `apiKey` | 是   | 未知 
 [Scanii](https://docs.scanii.com/)                                            | 可以扫描提交的文档/文件以查找威胁存在的简单REST API | `apiKey` | 是   | 是     
 [URLhaus](https://urlhaus-api.abuse.ch/)                                      | 批量查询和下载恶意软件样本                  | 否       | 是   | 是     
 [URLScan.io](https://urlscan.io/about-api/)                                   | 扫描和分析URL                       | `apiKey` | 是   | 未知 
 [VirusTotal](https://www.virustotal.com/en/documentation/public-api/)         | VirusTotal文件/URL分析             | `apiKey` | 是   | 未知 
 [Web of Trust](https://support.mywot.com/hc/en-us/sections/360004477734-API-) | IP/域名/URL声誉                    | `apiKey` | 是   | 未知 

**[⬆ 返回目录](#目录)**


## 艺术设计
 API                                                                  | 描述              | 认证Auth         | 支持HTTPS | 跨域CORS    
----------------------------------------------------------------------|--------------------------|----------|-------|---------
 [Améthyste](https://api.amethyste.moe/)                              | - 为Discord用户生成图像         | `apiKey` | 是   | 未知 
 [Art Institute of Chicago](https://api.artic.edu/docs/)              | - 艺术                     | 否       | 是   | 是     
 [Colormind](http://colormind.io/api-access/)                         | - 颜色方案生成器                | 否       | 否    | 未知 
 [ColourLovers](http://www.colourlovers.com/api)                      | - 获取各种图案、调色板和图像          | 否       | 否    | 未知 
 [Cooper Hewitt](https://collection.cooperhewitt.org/api)             | - 史密森尼设计博物馆              | `apiKey` | 是   | 未知 
 [Dribbble](https://developer.dribbble.com)                           | - 发现世界顶级设计师和创意人才         | `OAuth`  | 是   | 未知 
 [EmojiHub](https://github.com/cheatsnake/emojihub)                   | - 按类别和组获取表情符号            | 否       | 是   | 是     
 [Europeana](https://pro.europeana.eu/resources/apis/search)          | - 欧洲博物馆和画廊内容             | `apiKey` | 是   | 未知 
 [Harvard Art Museums](https://github.com/harvardartmuseums/api-docs) | - 艺术                     | `apiKey` | 否    | 未知 
 [Icon Horse](https://icon.horse/usage)                               | - 为任何网站提供Favicons，带有备用方案 | 否       | 是   | 是     
 [Iconfinder](https://developer.iconfinder.com)                       | - 图标                     | `apiKey` | 是   | 未知 
 [Icons8](https://img.icons8.com/)                                    | - 图标（在页面中查找“搜索图标”超链接）    | 否       | 是   | 未知 
 [Lordicon](https://lordicon.com/)                                    | - 具有预先完成动画的图标            | 否       | 是   | 是     
 [Metropolitan Museum of Art](https://metmuseum.github.io/)           | - 大都会艺术博物馆               | 否       | 是   | 否      
 [Noun Project](http://api.thenounproject.com/index.html)             | - 图标                     | `OAuth`  | 否    | 未知 
 [PHP-Noise](https://php-noise.com/)                                  | - 噪声背景图像生成器              | 否       | 是   | 是     
 [Pixel Encounter](https://pixelencounter.com/api)                    | - SVG图标生成器               | 否       | 是   | 否      
 [Rijksmuseum](https://data.rijksmuseum.nl/object-metadata/api/)      | - RijksMuseum数据          | `apiKey` | 是   | 未知 
 [The Color](https://www.thecolorapi.com/)                            | - 颜色的瑞士军刀                | 否       | 否    | 未知 
 [Word Cloud](https://wordcloudapi.com/)                              | - 轻松创建词云                 | `apiKey` | 是   | 未知 
 [xColors](https://github.com/cheatsnake/xColors-api)                 | - 生成和转换颜色                | 否       | 是   | 是     

**[⬆ 返回目录](#目录)**

## 认证授权
 API                                        | 描述           | 认证Auth         | 支持HTTPS | 跨域CORS 
--------------------------------------------|-----------------------|----------|-------|------
 [Auth0](https://auth0.com)                 | - 描述                  | `apiKey` | 是   | 是  
 [Clerk](https://clerk.com)                 | - 易于实现，适应性强的身份验证和授权平台 | `apiKey` | 是   | 是  
 [Corbado](https://corbado.com)             | - 用于身份验证和授权的React组件   | `apiKey` | 是   | 是  
 [GetOTP](https://otp.dev/en/docs/)         | - Passkey-first身份验证   | `apiKey` | 是   | 否   
 [Micro User Service](https://m3o.com/user) | - 快速实现OTP流程           | `apiKey` | 是   | 否   
 [MojoAuth](https://mojoauth.com)           | - 用户管理和身份验证           | `apiKey` | 是   | 是  
 [Stytch](https://stytch.com/)              | - 安全且现代的无密码身份验证平台     | `apiKey` | 是   | 否   
 [Warrant](https://docs.warrant.dev/)       | - 现代应用程序的用户基础设施       | `apiKey` | 是   | 是  

**[⬆ 返回目录](#目录)**


## 区块链
 API                                                            | 描述                                    | 认证Auth         | 支持HTTPS | 跨域CORS    
----------------------------------------------------------------|------------------------------------------------|----------|-------|---------
 [Bitquery](https://graphql.bitquery.io/ide)                    | - Onchain GraphQL APIs和DEX APIs                | `apiKey` | 是   | 是     
 [Chainlink](https://chain.link/developer-resources)            | - 使用Chainlink构建混合智能合约                          | 否       | 是   | 未知 
 [Chainpoint](https://tierion.com/chainpoint/)                  | - Chainpoint是一个将数据锚定到比特币区块链的全球网络               | 否       | 是   | 未知 
 [Covalent](https://www.covalenthq.com/docs/api/)               | - 多区块链数据聚合平台                                   | `apiKey` | 是   | 未知 
 [Etherscan](https://etherscan.io/apis)                         | - 以太坊浏览器API                                    | `apiKey` | 是   | 是     
 [Helium](https://docs.helium.com/api/blockchain/introduction/) | - Helium是一个全球分布式的Hotspots网络，可以创建公共的、长距离的无线覆盖范围 | 否       | 是   | 未知 
 [Nownodes](https://nownodes.io/)                               | - 基于API提供高质量连接的区块链即服务解决方案                      | `apiKey` | 是   | 未知 
 [Steem](https://developers.steem.io/)                          | - 基于区块链的博客和社交媒体网站                              | 否       | 否    | 否      
 [The Graph](https://thegraph.com)                              | - 用于查询像以太坊这样的网络的索引协议，使用GraphQL                 | `apiKey` | 是   | 未知 
 [Watchdata](https://docs.watchdata.io)                         | - 为以太坊区块链提供简单可靠的API访问                          | `apiKey` | 是   | 未知 

**[⬆ 返回目录](#目录)**



## 书籍
 API                                                                       | 描述                                      | 认证Auth         | 支持HTTPS | 跨域CORS    
---------------------------------------------------------------------------|--------------------------------------------------|----------|-------|---------
 [A Bíblia Digital](https://www.abibliadigital.com.br/en)                  | - 不用担心管理多个圣经版本                                   | `apiKey` | 是   | 否      
 [Bhagavad Gita](https://bhagavadgitaapi.in)                               | - 包括梵文/英文/印地语中21+位作者的开源Shrimad Bhagavad Gita API | `apiKey` | 是   | 是     
 [Bhagavad Gita](https://bhagavadgita.io/api)                              | - Bhagavad Gita文本                                | `OAuth`  | 是   | 是     
 [Bhagavad Gita telugu](https://gita-api.vercel.app)                       | - Bhagavad Gita API，支持泰卢固语和奥迪亚语                  | 否       | 是   | 是     
 [Bible-api](https://bible-api.com/)                                       | - 具有多种语言的免费圣经API                                 | 否       | 是   | 是     
 [British National Bibliography](http://bnb.data.bl.uk/)                   | - 书籍                                             | 否       | 否    | 未知 
 [Crossref Metadata Search](https://github.com/CrossRef/rest-api-doc)      | - 书籍和文章元数据                                       | 否       | 是   | 未知 
 [Ganjoor](https://api.ganjoor.net)                                        | - 经典波斯诗歌作品，包括相关手稿、朗诵和音乐曲目的访问                     | `OAuth`  | 是   | 是     
 [Google Books](https://developers.google.com/books/)                      | - 书籍                                             | `OAuth`  | 是   | 未知 
 [Gutendex](https://gutendex.com/)                                         | - 从Project Gutenberg Books Library获取数据的Web-API   | 否       | 是   | 未知 
 [Open Library](https://openlibrary.org/developers/api)                    | - 书籍、书籍封面和相关数据                                   | 否       | 是   | 否      
 [Penguin Publishing](http://www.penguinrandomhouse.biz/webservices/rest/) | - 书籍、书籍封面和相关数据                                   | 否       | 是   | 是     
 [PoetryDB](https://github.com/thundercomb/poetrydb#readme)                | - 让您从我们庞大的诗歌收藏中获得即时数据                            | 否       | 是   | 是     
 [Quran](https://quran.api-docs.io/)                                       | - 具有多种语言的RESTful Quran API                       | 否       | 是   | 是     
 [Quran Cloud](https://alquran.cloud/api)                                  | - 用于检索Ayah、Surah、Juz或整个《古兰经》的RESTful Quran API   | 否       | 是   | 是     
 [Quran-api](https://github.com/fawazahmed0/quran-api#readme)              | - 具有90多种不同语言和400多种翻译的免费《古兰经》API服务                | 否       | 是   | 是     
 [The Bible](https://docs.api.bible)                                       | - 在一个可发现的地方获取您需要的圣经一切内容                          | `apiKey` | 是   | 未知 
 [Thirukkural](https://api-thirukkural.web.app/)                           | - 包括1330首泰米尔语和英语Thirukkural诗歌及其解释                | 否       | 是   | 是     
 [Wizard World](https://wizard-world-api.herokuapp.com/swagger/index.html) | - 获取哈利波特世界的信息                                    | 否       | 是   | 是     
 [Wolne Lektury](https://wolnelektury.pl/api/)                             | - 用于获取WolneLektury.pl网站上可用电子书信息的API              | 否       | 是   | 未知 

**[⬆ 返回目录](#目录)**

## 商业
| API                                                                                                                 | 描述                            | 认证Auth         | 支持HTTPS | 跨域CORS    |
|---------------------------------------------------------------------------------------------------------------------|----------------------------------------|----------|-------|---------|
| [Apache Superset](https://superset.apache.org/docs/api)                                                             | 用于管理Superset上的BI仪表板和数据源的API            | `apiKey` | 是   | 是     |
| [ArvanCloud](https://www.arvancloud.ir/en/dev/sdk)                                                                  | 允许您使用ArvanCloud服务                      | `apiKey` | 是   | 否      |
| [Charity Search](http://charityapi.orghunter.com/)                                                                  | 非营利慈善数据                                | `apiKey` | 否    | 未知 |
| [Clearbit Logo](https://clearbit.com/docs#logo-api)                                                                 | 搜索公司标志并将其嵌入您的项目中                       | `apiKey` | 是   | 未知 |
| [Domainsdb.info](https://domainsdb.info/)                                                                           | 注册域名搜索                                 | 否       | 是   | 否      |
| [Freelancer](https://developers.freelancer.com)                                                                     | 雇用自由职业者完成工作                            | `OAuth`  | 是   | 未知 |
| [Gmail](https://developers.google.com/gmail/api/)                                                                   | 灵活的RESTful访问用户收件箱                      | `OAuth`  | 是   | 未知 |
| [Google Analytics](https://developers.google.com/analytics/)                                                        | 收集，配置和分析数据以达到正确的受众                     | `OAuth`  | 是   | 未知 |
| [Instatus](https://instatus.com/help/api)                                                                           | 通过HTTP REST API发布和更新维护和事件状态页面          | `apiKey` | 是   | 未知 |
| [Mailchimp](https://mailchimp.com/developer/)                                                                       | 发送营销活动和交易邮件                            | `apiKey` | 是   | 未知 |
| [mailjet](https://www.mailjet.com/)                                                                                 | 可以使用MJML或HTML制作营销电子邮件和邮件模板，然后使用API发送它们 | `apiKey` | 是   | 未知 |
| [markerapi](https://markerapi.com)                                                                                  | 商标搜索                                   | 否       | 否    | 未知 |
| [ORB Intelligence](https://api.orb-intelligence.com/docs/)                                                          | 公司查找                                   | `apiKey` | 是   | 未知 |
| [Redash](https://redash.io/help/user-guide/integrations-and-api/api)                                                | 访问Redash上的查询和仪表板                       | `apiKey` | 是   | 是     |
| [Smartsheet](https://smartsheet.redoc.ly/)                                                                          | 允许您以编程方式访问Smartsheet数据和帐户信息            | `OAuth`  | 是   | 否      |
| [Square](https://developer.squareup.com/reference/square)                                                           | 轻松接受付款，管理退款并帮助客户在线结帐                   | `OAuth`  | 是   | 未知 |
| [SwiftKanban](https://www.digite.com/knowledge-base/swiftkanban/article/api-for-swift-kanban-web-services/#restapi) | 看板软件，可视化工作，提高组织的前导时间，吞吐量和生产力           | `apiKey` | 是   | 未知 |
| [Tenders in Hungary](https://tenders.guru/hu/api)                                                                   | 以JSON格式获取匈牙利采购数据                       | 否       | 是   | 未知 |
| [Tenders in Poland](https://tenders.guru/pl/api)                                                                    | 以JSON格式获取波兰采购数据                        | 否       | 是   | 未知 |
| [Tenders in Romania](https://tenders.guru/ro/api)                                                                   | 以JSON格式获取罗马尼亚采购数据                      | 否       | 是   | 未知 |
| [Tenders in Spain](https://tenders.guru/es/api)                                                                     | 以JSON格式获取西班牙采购数据                       | 否       | 是   | 未知 |
| [Tenders in Ukraine](https://tenders.guru/ua/api)                                                                   | 以JSON格式获取乌克兰采购数据                       | 否       | 是   | 未知 |
| [Tomba email finder](https://tomba.io/api)                                                                          | B2B销售和电子邮件营销的电子邮件查找器和电子邮件验证器           | `apiKey` | 是   | 是     |
| [Trello](https://developers.trello.com/)                                                                            | 个用于组织和优先处理项目的看板、列表和卡片。                 | `OAuth`  | 是   | 未知 |

**[⬆ 返回目录](#目录)**



## 日历

| API                                                                                            | 描述                         | 认证Auth         | 支持HTTPS | 跨域CORS    |
|------------------------------------------------------------------------------------------------|-------------------------------------|----------|-------|---------|
| [Abstract Public Holidays](https://www.abstractapi.com/holidays-api)                           | 通过API获取有关国家、地区和宗教节日的数据              | `apiKey` | 是   | 是     |
| [Calendarific](https://calendarific.com/)                                                      | 全球节日                                | `apiKey` | 是   | 未知 |
| [Church Calendar](http://calapi.inadiutorium.cz/)                                              | 天主教历法                               | 否       | 否    | 未知 |
| [Czech Namedays Calendar](https://svatky.adresa.info)                                          | 查找名称并返回命名日期                         | 否       | 否    | 未知 |
| [DigiDates](https://digidates.de/en/)                                                          | 各种日期和时间计算                           | 否       | 是   | 是     |
| [Festivo Public Holidays](https://docs.getfestivo.com/docs/products/public-holidays-api/intro) | 市场上最快、最先进的公共假期和纪念日服务                | `apiKey` | 是   | 是     |
| [Google Calendar](https://developers.google.com/google-apps/calendar/)                         | 显示、创建和修改Google日历事件                  | `OAuth`  | 是   | 未知 |
| [Hebrew Calendar](https://www.hebcal.com/home/developer-apis)                                  | 在公历和希伯来历之间进行转换，获取安息日和节日时间等信息        | 否       | 否    | 未知 |
| [Holidays](https://holidayapi.com/)                                                            | 有关假期的历史数据                           | `apiKey` | 是   | 未知 |
| [LectServe](http://www.lectserve.com)                                                          | 新教历法                                | 否       | 否    | 未知 |
| [Nager.Date](https://date.nager.at)                                                            | 90多个国家的公共假期                         | 否       | 是   | 否      |
| [Namedays Calendar](https://nameday.abalin.net)                                                | 为多个国家提供命名日期                         | 否       | 是   | 是     |
| [Non-Working Days](https://github.com/gadael/icsdb)                                            | 非工作日的ICS文件数据库                       | 否       | 是   | 未知 |
| [Non-Working Days](https://isdayoff.ru)                                                        | 用于检查俄罗斯、独联体、美国等工作、非工作或短日的简单REST API | 否       | 是   | 是     |
| [Russian Calendar](https://github.com/egno/work-calendar)                                      | 检查日期是否为俄罗斯假期                        | 否       | 是   | 否      |
| [UK Bank Holidays](https://www.gov.uk/bank-holidays.json)                                      | 英格兰和威尔士、苏格兰和北爱尔兰的银行假期               | 否       | 是   | 未知 |

**[⬆ 返回目录](#目录)**



## 存储文件共享

| API                                                   | 描述                                                           | 认证Auth         | 支持HTTPS | 跨域CORS    |
|-------------------------------------------------------|-----------------------------------------------------------------------|----------|-------|---------|
| [AnonFiles](https://anonfiles.com/docs/api)           | 匿名上传和共享文件                                                             | 否       | 是   | 未知 |
| [BayFiles](https://bayfiles.com/docs/api)             | 上传和共享文件                                                               | 否       | 是   | 未知 |
| [Box](https://developer.box.com/)                     | 文件共享和存储                                                               | `OAuth`  | 是   | 未知 |
| [ddownload](https://ddownload.com/api)                | 文件共享和存储                                                               | `apiKey` | 是   | 未知 |
| [Dropbox](https://www.dropbox.com/developers)         | 文件共享和存储                                                               | `OAuth`  | 是   | 未知 |
| [File.io](https://www.file.io)                        | 超级简单的文件共享，方便、匿名和安全                                                    | 否       | 是   | 未知 |
| [Gcore Storage](https://docs.gcore.com/storage)       | S3兼容对象存储是由Gcore提供的快速可扩展的云存储系统，它为您提供了在任何时间存储和检索任意数量的数据的机会。高性能存储用作CDN源。 | `apiKey` | 是   | 是     |
| [GoFile](https://gofile.io/api)                       | 免费无限大小的文件上传                                                           | `apiKey` | 是   | 未知 |
| [Google Drive](https://developers.google.com/drive/)  | 文件共享和存储                                                               | `OAuth`  | 是   | 未知 |
| [Gyazo](https://gyazo.com/api/docs)                   | 立即保存和分享屏幕截图                                                           | `apiKey` | 是   | 未知 |
| [Imgbb](https://api.imgbb.com/)                       | 简单快速的私人图像共享                                                           | `apiKey` | 是   | 未知 |
| [OneDrive](https://developer.microsoft.com/onedrive)  | 文件共享和存储                                                               | `OAuth`  | 是   | 未知 |
| [Pantry](https://getpantry.cloud/)                    | 为小型项目提供免费JSON存储                                                       | 否       | 是   | 是     |
| [Pastebin](https://pastebin.com/doc_api)              | 纯文本存储                                                                 | `apiKey` | 是   | 未知 |
| [Pinata](https://docs.pinata.cloud/)                  | IPFS存储服务API                                                           | `apiKey` | 是   | 未知 |
| [Quip](https://quip.com/dev/automation/documentation) | 面向群体的文件共享和存储                                                          | `apiKey` | 是   | 是     |
| [Smash](https://api.fromsmash.com/)                   | 在网站、移动应用程序、SaaS解决方案和自定义工作流程上上传大型文件                                    | `apiKey` | 是   | 是     |
| [Storj](https://docs.storj.io/dcs/)                   | 去中心化开源云存储                                                             | `apiKey` | 是   | 未知 |
| [The Null Pointer](https://0x0.st)                    | 简单和直接的文件托管和URL缩短服务                                                    | 否       | 是   | 未知 |
| [Web3 Storage](https://web3.storage/)                 | 免费提供1TB空间的文件共享和存储服务。                                                  | `apiKey` | 是   | 是     |

**[⬆ 返回目录](#目录)**


## 持续集成
| API                                                                                 | 描述                           | 认证Auth         | 支持HTTPS | 跨域CORS    |
|-------------------------------------------------------------------------------------|---------------------------------------|----------|-------|---------|
| [Azure DevOps Health](https://docs.microsoft.com/en-us/rest/api/resourcehealth)     | 资源健康状况可帮助您诊断和获取支持，当Azure问题影响您的资源时。    | `apiKey` | 否    | 否      |
| [Bitrise](https://api-docs.bitrise.io/)                                             | 构建工具和流程集成，创建高效的开发流水线。                 | `apiKey` | 是   | 未知 |
| [Buddy](https://buddy.works/docs/api/getting-started/overview)                      | 最快的持续集成和持续交付平台。                       | `OAuth`  | 是   | 未知 |
| [CircleCI](https://circleci.com/docs/api/v1-reference/)                             | 使用持续集成和持续交付自动化软件开发过程。                 | `apiKey` | 是   | 未知 |
| [Codeship](https://docs.cloudbees.com/docs/cloudbees-codeship/latest/api-overview/) | Codeship是云中的持续集成平台。                   | `apiKey` | 是   | 未知 |
| [Travis CI](https://docs.travis-ci.com/api/)                                        | 将您的GitHub项目与Travis CI同步，以在几分钟内测试您的代码。 | `apiKey` | 是   | 未知 |

**[⬆ 返回目录](#目录)**



## 加密货币
| API                                                                                 | 描述                             | 认证Auth         | 支持HTTPS | 跨域CORS    |
|-------------------------------------------------------------------------------------|-----------------------------------------|----------|-------|---------|
| [0x](https://0x.org/api)                                                            | 用于查询各种流动性池的代币和池统计信息的API                 | 否       | 是   | 是     |
| [1inch](https://1inch.io/api/)                                                      | 用于查询去中心化交易所的API                         | 否       | 是   | 未知 |
| [Alchemy Ethereum](https://docs.alchemy.com/alchemy/)                               | 以太坊节点即服务提供商                             | `apiKey` | 是   | 是     |
| [apilayer coinlayer](https://coinlayer.com)                                         | 实时加密货币汇率                                | `apiKey` | 是   | 未知 |
| [Binance](https://github.com/binance/binance-spot-api-docs)                         | 中国基于交易的加密货币交易所                          | `apiKey` | 是   | 未知 |
| [Bitcambio](https://nova.bitcambio.com.br/api/v3/docs#a-public)                     | 获取交易所中所有交易资产的列表                         | 否       | 是   | 未知 |
| [BitcoinAverage](https://apiv2.bitcoinaverage.com/)                                 | 区块链行业数字资产价格数据                           | `apiKey` | 是   | 未知 |
| [BitcoinCharts](https://bitcoincharts.com/about/exchanges/)                         | 与比特币网络相关的金融和技术数据                        | 否       | 是   | 未知 |
| [Bitfinex](https://docs.bitfinex.com/docs)                                          | 加密货币交易平台                                | `apiKey` | 是   | 未知 |
| [Bitmex](https://www.bitmex.com/app/apiOverview)                                    | 香港基于实时加密货币衍生品的交易平台                      | `apiKey` | 是   | 未知 |
| [Bittrex](https://bittrex.github.io/api/v3)                                         | 下一代加密货币交易平台                             | `apiKey` | 是   | 未知 |
| [Block](https://block.io/docs/basic)                                                | 比特币支付、钱包和交易数据                           | `apiKey` | 是   | 未知 |
| [Blockchain](https://www.blockchain.com/api)                                        | 比特币支付、钱包和交易数据                           | `apiKey` | 是   | 未知 |
| [blockfrost Cardano](https://blockfrost.io/)                                        | 与Cardano主网和几个测试网进行交互                    | `apiKey` | 是   | 未知 |
| [Brave NewCoin](https://bravenewcoin.com/developers)                                | 来自200多个交易所的实时和历史加密数据                    | `apiKey` | 是   | 未知 |
| [BtcTurk](https://docs.btcturk.com/)                                                | 实时加密货币数据、图表和API，允许买卖                    | `apiKey` | 是   | 是     |
| [Bybit](https://bybit-exchange.github.io/docs/linear/#t-introduction)               | 加密货币数据提要和算法交易                           | `apiKey` | 是   | 未知 |
| [CoinAPI](https://docs.coinapi.io/)                                                 | 所有货币交易所都集成在一个API下                       | `apiKey` | 是   | 否      |
| [Coinbase](https://developers.coinbase.com)                                         | 比特币、比特币现金、莱特币和以太坊价格                     | `apiKey` | 是   | 未知 |
| [Coinbase Pro](https://docs.pro.coinbase.com/#api)                                  | 加密货币交易平台                                | `apiKey` | 是   | 未知 |
| [CoinCap](https://docs.coincap.io/)                                                 | 通过RESTful API获取实时加密货币价格                 | 否       | 是   | 未知 |
| [CoinDCX](https://docs.coindcx.com/)                                                | 加密货币交易平台                                | `apiKey` | 是   | 未知 |
| [CoinDesk](https://old.coindesk.com/coindesk-api/)                                  | CoinDesk的比特币价格指数（BPI）以多种货币计价            | 否       | 是   | 未知 |
| [CoinGecko](http://www.coingecko.com/api)                                           | 加密货币价格、市场和开发者/社会数据                      | 否       | 是   | 是     |
| [Coinigy](https://coinigy.docs.apiary.io)                                           | 直接与Coinigy账户和交易所互动                      | `apiKey` | 是   | 未知 |
| [Coinlib](https://coinlib.io/apidocs)                                               | 加密货币价格                                  | `apiKey` | 是   | 未知 |
| [Coinlore](https://www.coinlore.com/cryptocurrency-data-api)                        | 加密货币价格、交易量等                             | 否       | 是   | 未知 |
| [CoinMarketCap](https://coinmarketcap.com/api/)                                     | 加密货币价格                                  | `apiKey` | 是   | 未知 |
| [Coinpaprika](https://api.coinpaprika.com)                                          | 加密货币价格、交易量等                             | 否       | 是   | 是     |
| [CoinRanking](https://developers.coinranking.com/api/documentation)                 | 实时加密货币数据                                | `apiKey` | 是   | 未知 |
| [Coinremitter](https://coinremitter.com/docs)                                       | 加密货币支付和价格                               | `apiKey` | 是   | 未知 |
| [CoinStats](https://documenter.getpostman.com/view/5734027/RzZ6Hzr3?version=latest) | 加密货币跟踪器                                 | 否       | 是   | 未知 |
| [CryptAPI](https://docs.cryptapi.io/)                                               | 加密货币支付处理器                               | 否       | 是   | 未知 |
| [CryptingUp](https://www.cryptingup.com/apidoc/#introduction)                       | 加密货币数据                                  | 否       | 是   | 未知 |
| [CryptoCompare](https://www.cryptocompare.com/api#)                                 | 加密货币比较                                  | 否       | 是   | 未知 |
| [CryptoMarket](https://api.exchange.cryptomkt.com/)                                 | 加密货币交易平台                                | `apiKey` | 是   | 是     |
| [Cryptonator](https://www.cryptonator.com/api/)                                     | 加密货币汇率                                  | 否       | 是   | 未知 |
| [dYdX](https://docs.dydx.exchange/)                                                 | 去中心化的加密货币交易所                            | `apiKey` | 是   | 未知 |
| [Ethplorer](https://github.com/EverexIO/Ethplorer/wiki/Ethplorer-API)               | 以太坊代币、余额、地址、交易历史、合约和自定义结构               | `apiKey` | 是   | 未知 |
| [EXMO](https://documenter.getpostman.com/view/10287440/SzYXWKPi)                    | 总部位于英国的加密货币交易所                          | `apiKey` | 是   | 未知 |
| [FTX](https://docs.ftx.com/)                                                        | 完整的REST、websocket和FTX API，以满足您的算法交易需求。  | `apiKey` | 是   | 是     |
| [Gateio](https://www.gate.io/api2)                                                  | API提供现货、保证金和期货交易操作。                     | `apiKey` | 是   | 未知 |
| [Gemini](https://docs.gemini.com/rest-api/)                                         | 加密货币交易所                                 | 否       | 是   | 未知 |
| [Huobi](https://huobiapi.github.io/docs/spot/v1/en/)                                | 总部位于塞舌尔的加密货币交易所                         | `apiKey` | 是   | 未知 |
| [icy.tools](https://developers.icy.tools/)                                          | 基于GraphQL的NFT API                       | `apiKey` | 是   | 未知 |
| [Indodax](https://github.com/btcid/indodax-official-api-docs)                       | 用卢比交易您的比特币和其他资产。                        | `apiKey` | 是   | 未知 |
| [INFURA Ethereum](https://infura.io/product/ethereum)                               | 与以太坊主网和几个测试网互动。                         | `apiKey` | 是   | 是     |
| [Kraken](https://docs.kraken.com/rest/)                                             | 加密货币交易所                                 | `apiKey` | 是   | 未知 |
| [KuCoin](https://docs.kucoin.com/)                                                  | 加密货币交易平台                                | `apiKey` | 是   | 未知 |
| [Localbitcoins](https://localbitcoins.com/api-docs/)                                | 买卖比特币的P2P平台。                            | 否       | 是   | 未知 |
| [Mempool](https://mempool.space/api)                                                | 专注于交易费用的比特币API服务。                       | 否       | 是   | 否      |
| [MercadoBitcoin](https://www.mercadobitcoin.com.br/api-doc/)                        | 巴西加密货币信息                                | 否       | 是   | 未知 |
| [Messari](https://messari.io/api)                                                   | 为数千种加密资产提供API端点。                        | 否       | 是   | 未知 |
| [Nexchange](https://nexchange2.docs.apiary.io/)                                     | 自动化的加密货币交换服务。                           | 否       | 否    | 是     |
| [Nomics](https://nomics.com/docs/)                                                  | 历史和实时的加密货币价格和市场数据。                      | `apiKey` | 是   | 是     |
| [NovaDax](https://doc.novadax.com/en-US/#introduction)                              | NovaDAX API可访问所有市场数据、交易管理端点。            | `apiKey` | 是   | 未知 |
| [OKEx](https://www.okex.com/docs/)                                                  | 总部位于塞舌尔的加密货币交易所。                        | `apiKey` | 是   | 未知 |
| [Poloniex](https://docs.poloniex.com)                                               | 总部位于美国的数字资产交易所。                         | `apiKey` | 是   | 未知 |
| [Solana JSON RPC](https://docs.solana.com/developing/clients/jsonrpc-api)           | 提供各种端点与Solana区块链互动。                     | 否       | 是   | 未知 |
| [Technical Analysis](https://technical-analysis-api.com)                            | 加密货币价格和技术分析。                            | `apiKey` | 是   | 否      |
| [Trading View](https://www.tradingview.com/rest-api-spec/)                          | 经纪人和交易员的市场价格、数据、图表。                     | `OAuth`  | 是   | 未知 |
| [Tron Network](https://developers.tron.network/reference/api-key)                   | 提供各种端点与Tron区块链互动。                       | 否       | 是   | 未知 |
| [VALR](https://docs.valr.com/)                                                      | 总部位于南非的加密货币交易所。                         | `apiKey` | 是   | 未知 |
| [WorldCoinIndex](https://www.worldcoinindex.com/apiservice)                         | 加密货币价格。                                 | `apiKey` | 是   | 未知 |
| [ZMOK](https://docs.zmok.io)                                                        | 以太坊JSON RPC API和Web3提供商                 | 否       | 是   | 未知 |

**[⬆ 返回目录](#目录)**



## 货币交换

| API                                                                                                          | 描述                | 认证Auth         | 支持HTTPS | 跨域CORS    |
|--------------------------------------------------------------------------------------------------------------|----------------------------|----------|-------|---------|
| [1Forge](https://1forge.com/forex-data-api/api-documentation)                                                | 外汇市场数据                     | `apiKey` | 是   | 未知 |
| [Amdoren](https://www.amdoren.com/currency-api/)                                                             | 自由货币API，超过150种货币           | `apiKey` | 是   | 未知 |
| [apilayer fixer.io](https://fixer.io)                                                                        | 汇率和货币兑换                    | `apiKey` | 否    | 未知 |
| [Bank of Russia](https://www.cbr.ru/development/SXML/)                                                       | 汇率和货币兑换                    | 否       | 是   | 未知 |
| [Currencyapi](https://currencyapi.com)                                                                       | 货币换算API和crpyto货币价格，每分钟更新一次 | `apiKey` | 是   | 是     |
| [Currency-api](https://github.com/fawazahmed0/currency-api#readme)                                           | 自由货币汇率API，150多种货币，无汇率限制    | 否       | 是   | 是     |
| [CurrencyFreaks](https://currencyfreaks.com/)                                                                | 提供当前和历史货币汇率以及每月1K的免费计划请求   | `apiKey` | 是   | 是     |
| [Currencylayer](https://currencylayer.com/documentation)                                                     | 汇率和货币兑换                    | `apiKey` | 是   | 未知 |
| [CurrencyScoop](https://currencyscoop.com/api-documentation)                                                 | 实时和历史汇率JSON API            | `apiKey` | 是   | 是     |
| [Czech National Bank](https://www.cnb.cz/cs/financni_trhy/devizovy_trh/kurzy_devizoveho_trhu/denni_kurz.xml) | 汇率的集合                      | 否       | 是   | 未知 |
| [Economia.Awesome](https://docs.awesomeapi.com.br/api-de-moedas)                                             | 葡萄牙自由货币价格和无汇率限制的兑换         | 否       | 是   | 未知 |
| [ExchangeRate-API](https://www.exchangerate-api.com)                                                         | 自由货币兑换                     | `apiKey` | 是   | 是     |
| [Exchangerate.host](https://exchangerate.host)                                                               | 自由外汇和加密汇率API               | 否       | 是   | 未知 |
| [Exchangeratesapi.io](https://exchangeratesapi.io)                                                           | 汇率与货币换算                    | `apiKey` | 是   | 是     |
| [Frankfurter](https://www.frankfurter.app/docs)                                                              | 汇率、货币换算和时间序列               | 否       | 是   | 是     |
| [FreeForexAPI](https://freeforexapi.com/Home/Api)                                                            | 主要货币对的实时外汇汇率               | 否       | 是   | 否      |
| [MetalpriceAPI](https://metalpriceapi.com)                                                                   | 实时和历史汇率及货币换算API            | `apiKey` | 是   | 未知 |
| [National Bank of Poland](http://api.nbp.pl/en.html)                                                         | 货币汇率的集合（XML和JSON格式的数据）     | 否       | 是   | 是     |
| [VATComply.com](https://www.vatcomply.com/documentation)                                                     | 汇率、地理位置和增值税编号验证            | 否       | 是   | 是     |

**[⬆ 返回目录](#目录)**



## 数据验证

| API                                                                          | 描述                | 认证Auth         | 支持HTTPS | 跨域CORS    |
|------------------------------------------------------------------------------|----------------------------|----------|-------|---------|
| [Lob.com](https://lob.com/)                                                  |  美国地址验证                    | `apiKey` | 是   | 未知 |
| [Postman Echo](https://www.postman-echo.com)                                 |  测试API服务器，用于接收和返回HTTP方法的值  | 否       | 是   | 未知 |
| [PurgoMalum](http://www.purgomalum.com)                                      |  内容验证器，用于防止亵渎和淫秽内容         | 否       | 否    | 未知 |
| [US Autocomplete](https://www.smarty.com/docs/cloud/us-autocomplete-pro-api) | 使用实时地址建议快速输入地址数据   | `apiKey` | 是   | 是     |
| [US Extract](https://www.smarty.com/products/apis/us-extract-api)            |  从任何文本（包括电子邮件）中提取邮政地址      | `apiKey` | 是   | 是     |
| [US Street Address](https://www.smarty.com/docs/cloud/us-street-api)         |  验证并附加任何美国邮政地址的数据          | `apiKey` | 是   | 是     |
| [vatlayer](https://vatlayer.com/documentation)                               |  VAT增值税号码验证                   | `apiKey` | 是   | 未知 |
| [VatcheckAPI](https://vatcheckapi.com)                                       |  VAT增值税号码验证和查找REST API        | `apiKey` | 是   | 是     |

**[⬆ 返回目录](#目录)**



## 开发

| API                                                                                                                                       | 描述                                                        | Auth            | HTTPS | CORS    |
|-------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|-----------------|-------|---------|
| [24 Pull Requests](https://24pullrequests.com/api)                                                                                        | 在12月期间促进开源协作的项目                                                    | 否              | 是   | 是     |
| [Abstract Screenshot](https://www.abstractapi.com/website-screenshot-api)                                                                 | 从任何网站对网页进行编程截图                                                     | `apiKey`        | 是   | 是     |
| [Agify.io](https://agify.io)                                                                                                              | 根据名字估计年龄                                                           | 否              | 是   | 是     |
| [API Grátis](https://apigratis.com.br/)                                                                                                   | 多种服务和公共API                                                         | 否              | 是   | 未知 |
| [ApicAgent](https://www.apicagent.com)                                                                                                    | 从用户代理字符串中提取设备详情                                                    | 否              | 是   | 是     |
| [ApiFlash](https://apiflash.com/)                                                                                                         | 面向开发者的基于Chrome的截图API                                               | `apiKey`        | 是   | 未知 |
| [apilayer userstack](https://userstack.com/)                                                                                              | 安全的用户代理字符串查询JSON API                                               | `OAuth`         | 是   | 未知 |
| [APIs.guru](https://apis.guru/api-doc/)                                                                                                   | 网络API的维基百科，公共API的OpenAPI/Swagger规范                                 | 否              | 是   | 未知 |
| [Azure DevOps](https://docs.microsoft.com/en-us/rest/api/azure/devops)                                                                    | Azure DevOps REST API请求/响应对的基本组件                                   | `apiKey`        | 是   | 未知 |
| [Beeceptor](https://beeceptor.com/)                                                                                                       | 在几秒钟内构建一个模拟的Rest API端点                                             | 否              | 是   | 是     |
| [Bitbucket](https://developer.atlassian.com/bitbucket/api/2/reference/)                                                                   | Bitbucket API                                                      | `OAuth`         | 是   | 未知 |
| [Blague.xyz](https://blague.xyz/)                                                                                                         | La plus grande API de Blagues FR/The biggest FR jokes API（法语笑话API） | `apiKey`        | 是   | 是     |
| [Blitapp](https://blitapp.com/api/)                                                                                                       | 定时对网页进行截图，并将它们同步到你的云端                                              | `apiKey`        | 是   | 未知 |
| [Blynk-Cloud](https://blynkapi.docs.apiary.io/#)                                                                                          | 从Blynk IoT Cloud控制IoT设备                                            | `apiKey`        | 否    | 未知 |
| [Bored](https://www.boredapi.com/)                                                                                                        | 找到随机活动来打败无聊                                                        | 否              | 是   | 未知 |
| [Brainshop.ai](https://brainshop.ai/)                                                                                                     | 免费制作一个人工智能大脑                                                       | `apiKey`        | 是   | 是     |
| [Browshot](https://browshot.com/api/documentation)                                                                                        | 轻松地以任何屏幕尺寸、任何设备对网页进行截图                                             | `apiKey`        | 是   | 是     |
| [CDNJS](https://api.cdnjs.com/libraries/jquery)                                                                                           | CDNJS上的库信息                                                         | 否              | 是   | 未知 |
| [Changelogs.md](https://changelogs.md)                                                                                                    | 开源项目的结构化变更日志元数据                                                    | 否              | 是   | 未知 |
| [Ciprand](https://github.com/polarspetroll/ciprand)                                                                                       | 安全的随机字符串生成器                                                        | 否              | 是   | 否      |
| [Cloudflare Trace](https://github.com/fawazahmed0/cloudflare-trace-api)                                                                   | 获取IP地址、时间戳、用户代理、国家代码、IATA、HTTP版本、TLS/SSL版本等等                       | 否              | 是   | 是     |
| [Codex](https://github.com/Jaagrav/CodeX)                                                                                                 | 各种语言的在线编译器                                                         | 否              | 是   | 未知 |
| [Contentful Images](https://www.contentful.com/developers/docs/references/images-api/)                                                    | 用于检索和应用图像转换的API                                                    | `apiKey`        | 是   | 是     |
| [CORS Proxy](https://github.com/burhanuday/cors-proxy)                                                                                    | 使用这个代理作为中间人，绕过令人讨厌的CORS错误                                          | 否              | 是   | 是     |
| [CountAPI](https://countapi.xyz)                                                                                                          | 免费且简单的计数服务。你可以用它来跟踪页面点击和特定事件                                       | 否              | 是   | 是     |
| [Databricks](https://docs.databricks.com/dev-tools/api/latest/index.html)                                                                 | 用于管理你的databricks账户、集群、笔记本、作业和工作区的服务                                | `apiKey`        | 是   | 是     |
| [DigitalOcean Status](https://status.digitalocean.com/api)                                                                                | DigitalOcean所有服务的状态                                                | 否              | 是   | 未知 |
| [Docker Hub](https://docs.docker.com/docker-hub/api/latest/)                                                                              | 与Docker Hub交互                                                      | `apiKey`        | 是   | 是     |
| [DomainDb Info](https://api.domainsdb.info/)                                                                                              | 域名搜索，找到包含特定单词/短语/等等的所有域名                                           | 否              | 是   | 未知 |
| [ExtendsClass JSON Storage](https://extendsclass.com/json-storage.html)                                                                   | 一个简单的JSON存储API                                                     | 否              | 是   | 是     |
| [Gcore CDN](https://docs.gcore.com/cdn)                                                                                                   | 使用Gcore CDN，让你的应用程序快速响应全球受众。                                       | `apiKey`        | 是   | 是     |
| [Gcore Cloud](https://docs.gcore.com/cloud)                                                                                               | 可扩展、安全、可靠的混合云服务，覆盖全球任何地方。                                          | `apiKey`        | 是   | 是     |
| [Gcore DNS](https://docs.gcore.com/dns)                                                                                                   | Gcore提供的快速和弹性的DNS托管服务。提高你的在线业务的性能和可用性。                             | `apiKey`        | 是   | 是     |
| [GeekFlare](https://apidocs.geekflare.com/docs/geekflare-api)                                                                             | 提供重要的测试和监控方法的多种功能，适用于网站                                            | `apiKey`        | 是   | 未知 |
| [Genderize.io](https://genderize.io)                                                                                                      | 根据名字估计性别                                                           | 否              | 是   | 是     |
| [GETPing](https://www.getping.info)                                                                                                       | 通过简单的GET请求触发电子邮件通知                                                 | `apiKey`        | 是   | 未知 |
| [Ghost](https://ghost.org/)                                                                                                               | 将已发布的内容获取到你的网站、应用或其他嵌入式媒体中                                         | `apiKey`        | 是   | 是     |
| [GitHub](https://docs.github.com/en/free-pro-team@latest/rest)                                                                            | 以编程方式使用GitHub仓库、代码和用户信息                                            | `OAuth`         | 是   | 是     |
| [Gitlab](https://docs.gitlab.com/ee/api/)                                                                                                 | 以编程方式自动化GitLab交互                                                   | `OAuth`         | 是   | 未知 |
| [Gitter](https://developer.gitter.im/docs/welcome)                                                                                        | 开发者聊天                                                              | `OAuth`         | 是   | 未知 |
| [Glitterly](https://developers.glitterly.app)                                                                                             | 图像生成API                                                            | `apiKey`        | 是   | 是     |
| [Google Docs](https://developers.google.com/docs/api/reference/rest)                                                                      | 以编程方式读取、写入和格式化Google Docs文档的API                                    | `OAuth`         | 是   | 未知 |
| [Google Firebase](https://firebase.google.com/docs)                                                                                       | Google的移动应用开发平台，帮助构建、改进和增长应用                                       | `apiKey`        | 是   | 是     |
| [Google Fonts](https://developers.google.com/fonts/docs/developer_api)                                                                    | Google Fonts提供的所有字体家族的元数据                                          | `apiKey`        | 是   | 未知 |
| [Google Keep](https://developers.google.com/keep/api/reference/rest)                                                                      | 以编程方式读取、写入和格式化Google Keep笔记的API                                    | `OAuth`         | 是   | 未知 |
| [Google Sheets](https://developers.google.com/sheets/api/reference/rest)                                                                  | 以编程方式读取、写入和格式化Google Sheets数据的API                                  | `OAuth`         | 是   | 未知 |
| [Google Slides](https://developers.google.com/slides/api/reference/rest)                                                                  | 以编程方式读取、写入和格式化Google Slides演示文稿的API                                | `OAuth`         | 是   | 未知 |
| [Gorest](https://gorest.co.in/)                                                                                                           | 用于测试和原型设计的在线REST API                                               | `OAuth`         | 是   | 未知 |
| [Hasura](https://hasura.io/opensource/)                                                                                                   | 内置授权功能的GraphQL和REST API引擎                                          | `apiKey`        | 是   | 是     |
| [Heroku](https://devcenter.heroku.com/articles/platform-api-reference/)                                                                   | 以编程方式在Heroku上创建应用、配置插件和执行其他任务的REST API                             | `OAuth`         | 是   | 是     |
| [Host.io](https://host.io)                                                                                                                | 面向开发者的域名数据API                                                      | `apiKey`        | 是   | 是     |
| [HTTP2.Pro](https://http2.pro/doc/api)                                                                                                    | 测试客户端和服务器HTTP/2协议支持的端点                                             | 否              | 是   | 未知 |
| [Httpbin](https://httpbin.org/)                                                                                                           | 简单的HTTP请求和响应服务                                                     | 否              | 是   | 是     |
| [Httpbin Cloudflare](https://cloudflare-quic.com/b/)                                                                                      | Cloudflare提供的支持HTTP/3协议的简单HTTP请求和响应服务                              | 否              | 是   | 是     |
| [Hunter](https://hunter.io/api)                                                                                                           | 域名搜索、专业电子邮件查找器、作者查找器和电子邮件验证器API                                    | `apiKey`        | 是   | 未知 |
| [IBM Text to Speech](https://cloud.ibm.com/docs/text-to-speech/getting-started.html)                                                      | 将文本转换为语音                                                           | `apiKey`        | 是   | 是     |
| [IFTTT](https://platform.ifttt.com/docs/connect_api)                                                                                      | IFTTT Connect API                                                  | 否              | 是   | 未知 |
| [Image-Charts](https://documentation.image-charts.com/)                                                                                   | 生成图表、二维码和图形图像                                                      | 否              | 是   | 是     |
| [import.io](http://api.docs.import.io/)                                                                                                   | 从网站或RSS源检索结构化数据.                                                   | `apiKey`        | 是   | 未知 |
| [IP2WHOIS Information Lookup](https://www.ip2whois.com/)                                                                                  | WHOIS域名查询                                                          | `apiKey`        | 是   | 未知 |
| [ipfind.io](https://ipfind.io)                                                                                                            | IP地址或任何域名的地理位置以及一些其他有用的信息                                          | `apiKey`        | 是   | 是     |
| [IPify](https://www.ipify.org/)                                                                                                           | 一个简单的IP地址API                                                       | 否              | 是   | 未知 |
| [IPinfo](https://ipinfo.io/developers)                                                                                                    | 另一个简单的IP地址API                                                      | 否              | 是   | 未知 |
| [jsDelivr](https://github.com/jsdelivr/data.jsdelivr.com)                                                                                 | jsDelivr CDN上的包信息和下载统计                                             | 否              | 是   | 是     |
| [JSON 2 JSONP](https://json2jsonp.com/)                                                                                                   | 使用客户端JavaScript将JSON转换为JSONP（即时）以便轻松进行跨域数据请求                       | 否              | 是   | 未知 |
| [JSONbin.io](https://jsonbin.io)                                                                                                          | 免费的JSON存储服务。适合小规模的Web应用、网站和移动应用                                    | `apiKey`        | 是   | 是     |
| [Kroki](https://kroki.io)                                                                                                                 | 根据文本描述创建图表                                                         | 否              | 是   | 是     |
| [License-API](https://github.com/cmccandless/license-api/blob/master/README.md)                                                           | choosealicense.com的非官方REST API                                     | 否              | 是   | 否      |
| [Lua Decompiler](https://lua-decompiler.ferib.dev/)                                                                                       | 在线Lua 5.1反编译器                                                      | 否              | 是   | 是     |
| [MAC address vendor lookup](https://macaddress.io/api)                                                                                    | 检索给定MAC地址或OUI的供应商详情和其他信息                                           | `apiKey`        | 是   | 是     |
| [Micro DB](https://m3o.com/db)                                                                                                            | 简单的数据库服务                                                           | `apiKey`        | 是   | 未知 |
| [MicroENV](https://microenv.com/)                                                                                                         | 开发者的假Rest API                                                      | 否              | 是   | 未知 |
| [Mocky](https://designer.mocky.io/)                                                                                                       | 模拟用户定义的测试JSON，用于REST API端点                                         | 否              | 是   | 是     |
| [MY IP](https://www.myip.com/api-docs/)                                                                                                   | 获取IP地址信息                                                           | 否              | 是   | 未知 |
| [Nationalize.io](https://nationalize.io)                                                                                                  | 估计一个名字的国籍                                                          | 否              | 是   | 是     |
| [Netlify](https://docs.netlify.com/api/get-started/)                                                                                      | Netlify是一个可编程Web的托管服务                                              | `OAuth`         | 是   | 未知 |
| [NetworkCalc](https://networkcalc.com/api/docs)                                                                                           | 网络计算器，包括子网、DNS、二进制和安全工具                                            | 否              | 是   | 是     |
| [npm Registry](https://github.com/npm/registry/blob/master/docs/REGISTRY-API.md)                                                          | 以编程方式查询你最喜欢的Node.js库的信息                                            | 否              | 是   | 未知 |
| [OneSignal](https://documentation.onesignal.com/docs/onesignal-api)                                                                       | 自助式客户参与解决方案，支持推送通知、电子邮件、短信和应用内消息                                   | `apiKey`        | 是   | 未知 |
| [Open Page Rank](https://www.domcop.com/openpagerank/)                                                                                    | 使用Page Rank算法计算和比较不同网站指标的API                                       | `apiKey`        | 是   | 未知 |
| [OpenAPIHub](https://hub.openapihub.com/)                                                                                                 | 一站式API平台                                                           | `X-Mashape-Key` | 是   | 未知 |
| [OpenGraphr](https://opengraphr.com/docs/1.0/overview)                                                                                    | 一个非常简单的API，用于从URL获取Open Graph数据                                    | `apiKey`        | 是   | 未知 |
| [oyyi](https://oyyi.xyz/docs/1.0)                                                                                                         | 用于生成假数据、图像/视频转换、优化、PDF优化和缩略图生成的API                                 | 否              | 是   | 是     |
| [PageCDN](https://pagecdn.com/docs/public-api)                                                                                            | PageCDN上的javascript、css和字体库的公共API                                  | `apiKey`        | 是   | 是     |
| [Postman](https://www.postman.com/postman/workspace/postman-public-workspace/documentation/12959542-c8142d51-e97c-46b6-bd77-52bb66712c9a) | 测试API的工具                                                           | `apiKey`        | 是   | 未知 |
| [ProxyCrawl](https://proxycrawl.com)                                                                                                      | 抓取和爬行反验证码服务                                                        | `apiKey`        | 是   | 未知 |
| [ProxyKingdom](https://proxykingdom.com)                                                                                                  | 每次请求都生成一个可用代理的轮换代理API                                              | `apiKey`        | 是   | 是     |
| [Pusher Beams](https://pusher.com/beams)                                                                                                  | Android和iOS的推送通知                                                   | `apiKey`        | 是   | 未知 |
| [Pusher Channels](https://pusher.com/channels)                                                                                            | 实时功能                                                               | `apiKey`        | 是   | 未知 |
| [QR code](https://www.qrtag.net/api/)                                                                                                     | 创建一个易于阅读的二维码和URL缩短器                                                | 否              | 是   | 是     |
| [QR code](http://goqr.me/api/)                                                                                                            | 生成和解码/读取二维码图形                                                      | 否              | 是   | 未知 |
| [Qrcode Monkey](https://www.qrcode-monkey.com/qr-code-api-with-logo/)                                                                     | 将定制和独特的二维码集成到你的系统或工作流中                                             | 否              | 是   | 未知 |
| [QuickChart](https://quickchart.io/)                                                                                                      | 生成图表和图形图像                                                          | 否              | 是   | 是     |
| [Random Stuff](https://api-docs.pgamerx.com/)                                                                                             | 可以用来获取AI回应、笑话、表情包，以及更多闪电般快速的内容                                     | `apiKey`        | 是   | 是     |
| [Rejax](https://rejax.io/)                                                                                                                | 反向AJAX服务来通知客户端                                                     | `apiKey`        | 是   | 否      |
| [ReqRes](https://reqres.in/)                                                                                                              | 一个托管的REST-API，准备好响应你的AJAX请求                                        | 否              | 是   | 未知 |
| [RSS feed to JSON](https://rss-to-json-serverless-api.vercel.app)                                                                         | 使用feed URL返回JSON格式的RSS feed                                        | 否              | 是   | 是     |
| [RSS to JSON](https://github.com/ayusharma/RSS-to-JSON)                                                                                   | 使用feed URL返回JSON格式的RSS feed                                        | 否              | 是   | 是     |
| [SavePage.io](https://www.savepage.io)                                                                                                    | 一个免费的RESTful API，用于截取任何桌面或移动网站的屏幕截图                                | `apiKey`        | 是   | 是     |
| [ScrapeNinja](https://scrapeninja.net)                                                                                                    | 带有Chrome指纹和住宅代理的抓取API                                              | `apiKey`        | 是   | 未知 |
| [ScraperApi](https://www.scraperapi.com)                                                                                                  | 轻松构建可扩展的Web抓取器                                                     | `apiKey`        | 是   | 未知 |
| [scraperBox](https://scraperbox.com/)                                                                                                     | 无法检测的Web抓取API                                                      | `apiKey`        | 是   | 是     |
| [scrapestack](https://scrapestack.com/)                                                                                                   | 实时、可扩展的代理和Web抓取REST API                                            | `apiKey`        | 是   | 未知 |
| [ScrapingAnt](https://scrapingant.com)                                                                                                    | 使用简单的API进行无头Chrome抓取                                               | `apiKey`        | 是   | 未知 |
| [ScrapingDog](https://www.scrapingdog.com/)                                                                                               | Web抓取的代理API                                                        | `apiKey`        | 是   | 未知 |
| [ScreenshotAPI.net](https://screenshotapi.net/)                                                                                           | 创建像素级完美的网站截图                                                       | `apiKey`        | 是   | 是     |
| [ScreenshotOne.com](https://screenshotone.com/)                                                                                           | 使用简单的截图API将URL、HTML或Markdown转换为PNG、JPEG、WebP或PDF                   | `apiKey`        | 是   | 是     |
| [Serialif Color](https://color.serialif.com/)                                                                                             | 颜色转换、互补色、灰度和对比度文本                                                  | 否              | 是   | 否      |
| [serpstack](https://serpstack.com/)                                                                                                       | 实时和准确的Google搜索结果API                                                | `apiKey`        | 是   | 是     |
| [Shadify](https://github.com/cheatsnake/shadify)                                                                                          | 用于生成数据和执行逻辑以创建各种游戏和谜题的服务                                           | 否              | 是   | 是     |
| [Sheetsu](https://sheetsu.com/)                                                                                                           | 简单的谷歌表格集成                                                          | `apiKey`        | 是   | 未知 |
| [Sonar](https://github.com/Cgboal/SonarSearch)                                                                                            | Project Sonar DNS枚举API                                             | 否              | 是   | 是     |
| [SonarQube](https://sonarcloud.io/web_api)                                                                                                | SonarQube REST APIs用于检测错误、代码异味和安全漏洞                                | `OAuth`         | 是   | 未知 |
| [StackExchange](https://api.stackexchange.com/)                                                                                           | 开发者的问答论坛                                                           | `OAuth`         | 是   | 未知 |
| [Statically](https://statically.io/)                                                                                                      | 一个免费的CDN，专为开发者设计                                                   | 否              | 是   | 是     |
| [Supportivekoala](https://developers.supportivekoala.com/)                                                                                | 根据模板自动生成图像                                                         | `apiKey`        | 是   | 是     |
| [Tolgee](https://tolgee.io)                                                                                                               | 开源本地化（i18n）平台，让你快速翻译你的应用                                           | `apiKey`        | 是   | 否      |
| [Tyk](https://tyk.io/open-source/)                                                                                                        | API和服务管理平台                                                         | `apiKey`        | 是   | 是     |
| [Wandbox](https://github.com/melpon/wandbox/blob/master/kennel/API.md)                                                                    | 支持wandbox.org提到的35+种语言的代码编译器                                       | 否              | 是   | 未知 |
| [WebScraping.AI](https://webscraping.ai/)                                                                                                 | 带有内置代理和JS渲染的Web抓取API                                               | `apiKey`        | 是   | 是     |
| [ZenRows](https://www.zenrows.com/)                                                                                                       | 绕过反机器人解决方案，同时提供JS渲染和轮换代理的Web抓取API                                  | `apiKey`        | 是   | 未知 |

**[⬆ 返回目录](#目录)**

## 字典

| API                                                                     | 描述            | 认证Auth         | 支持HTTPS | 跨域CORS    |
|-------------------------------------------------------------------------|------------------------|----------|-------|---------|
| [Chinese Character Web](http://ccdb.hemiola.com/)                       | 中文字符网                  | 否       | 否    | 否      |
| [Chinese Text Project](https://ctext.org/tools/api)                     | 前现代中文文本的在线开放获取数字图书馆    | 否       | 是   | 未知 |
| [Collins](https://api.collinsdictionary.com/api/v1/documentation/html/) | 双语词典和同义词数据             | `apiKey` | 是   | 未知 |
| [Free Dictionary](https://dictionaryapi.dev/)                           | 定义、音标、发音、词性、例句、同义词     | 否       | 是   | 未知 |
| [Lingua Robot](https://www.linguarobot.io)                              | 单词的定义、发音、同义词、反义词等      | `apiKey` | 是   | 是     |
| [Merriam-Webster](https://dictionaryapi.com/)                           | 词典和同义词数据               | `apiKey` | 是   | 未知 |
| [OwlBot](https://owlbot.info/)                                          | 带有例句和照片（如果有的话）的定义      | `apiKey` | 是   | 是     |
| [Oxford](https://developer.oxforddictionaries.com/)                     | 词典数据                   | `apiKey` | 是   | 否      |
| [Synonyms](https://www.synonyms.com/synonyms_api.php)                   | 任何给定单词的同义词、同义词典和反义词信息  | `apiKey` | 是   | 未知 |
| [Wiktionary](https://en.wiktionary.org/w/api.php)                       | 协作式词典数据                | 否       | 是   | 是     |
| [Wordnik](https://developer.wordnik.com)                                | 词典数据                   | `apiKey` | 是   | 未知 |
| [Words](https://www.wordsapi.com/docs/)                                 | 超过15万个单词的定义和同义词        | `apiKey` | 是   | 未知 |

**[⬆ 返回目录](#目录)**


## 文档生产力

| API                                                                               | 描述                                    | 认证Auth         | 支持HTTPS | 跨域CORS    |
|-----------------------------------------------------------------------------------|------------------------------------------------|----------|-------|---------|
| [Airtable](https://airtable.com/api)                                              | 与Airtable集成                                    | `apiKey` | 是   | 未知 |
| [Api2Convert](https://www.api2convert.com/)                                       | 在线文件转换API                                      | `apiKey` | 是   | 未知 |
| [apilayer pdflayer](https://pdflayer.com)                                         | HTML/URL转PDF                                   | `apiKey` | 是   | 未知 |
| [Asana](https://developers.asana.com/docs)                                        | 以编程方式访问和更新你的asana系统中的所有数据                      | `apiKey` | 是   | 是     |
| [ClickUp](https://clickup.com/api)                                                | ClickUp是一个强大的基于云的项目管理工具，用于提高生产力                | `OAuth`  | 是   | 未知 |
| [Clockify](https://clockify.me/developers-api)                                    | Clockify的基于REST的API可以用来推送/拉取数据到/从它，并将它与其他系统集成  | `apiKey` | 是   | 未知 |
| [CloudConvert](https://cloudconvert.com/api/v2)                                   | 在线文件转换器，支持音频、视频、文档、电子书、压缩文件、图像、电子表格、演示文稿       | `apiKey` | 是   | 未知 |
| [Cloudmersive Document and Data Conversion](https://cloudmersive.com/convert-api) | HTML/URL转PDF/PNG，Office文档转PDF，图像转换             | `apiKey` | 是   | 是     |
| [Code::Stats](https://codestats.net/api-docs)                                     | 程序员的自动时间跟踪                                     | `apiKey` | 是   | 否      |
| [CraftMyPDF](https://craftmypdf.com)                                              | 从模板生成PDF文档，使用拖放编辑器和简单的API                      | `apiKey` | 是   | 否      |
| [Flowdash](https://docs.flowdash.com/docs/api-introduction)                       | 自动化业务工作流                                       | `apiKey` | 是   | 未知 |
| [Html2PDF](https://html2pdf.app/)                                                 | HTML/URL转PDF                                   | `apiKey` | 是   | 未知 |
| [iLovePDF](https://developer.ilovepdf.com/)                                       | 转换、合并、分割、提取文本和添加页码的PDF。每月250份文档免费              | `apiKey` | 是   | 是     |
| [JIRA](https://developer.atlassian.com/server/jira/platform/rest-apis/)           | JIRA是一个专有的问题跟踪产品，允许错误跟踪和敏捷项目管理                 | `OAuth`  | 是   | 未知 |
| [Mattermost](https://api.mattermost.com/)                                         | 开源平台，用于开发者协作                                   | `OAuth`  | 是   | 未知 |
| [Mercury](https://mercury.postlight.com/web-parser/)                              | Web解析器                                         | `apiKey` | 是   | 未知 |
| [Monday](https://api.developer.monday.com/docs)                                   | 以编程方式访问和更新monday.com账户中的数据                     | `apiKey` | 是   | 未知 |
| [Notion](https://developers.notion.com/docs/getting-started)                      | 与Notion集成                                      | `OAuth`  | 是   | 未知 |
| [PandaDoc](https://developers.pandadoc.com)                                       | DocGen和电子签名API                                 | `apiKey` | 是   | 否      |
| [Pocket](https://getpocket.com/developer/)                                        | 书签服务                                           | `OAuth`  | 是   | 未知 |
| [Podio](https://developers.podio.com)                                             | 文件共享和生产力                                       | `OAuth`  | 是   | 未知 |
| [PrexView](https://prexview.com)                                                  | 将XML或JSON数据转换为PDF、HTML或图像                      | `apiKey` | 是   | 未知 |
| [Restpack](https://restpack.io/)                                                  | 提供截图、HTML转PDF和内容提取API                          | `apiKey` | 是   | 未知 |
| [Todoist](https://developer.todoist.com)                                          | 待办事项列表                                         | `OAuth`  | 是   | 未知 |
| [Vector Express v2.0](https://vector.express)                                     | 免费的矢量文件转换API                                   | 否       | 是   | 否      |
| [Vertopal](https://www.vertopal.com/en/developer/api/introduction)                | 使用Vertopal API将你的文件转换为多种格式                     | `apiKey` | 是   | 否      |
| [WakaTime](https://wakatime.com/developers)                                       | 程序员的自动时间跟踪排行榜                                  | 否       | 是   | 未知 |
| [Zube](https://zube.io/docs/api)                                                  | 全栈项目管理                                         | `OAuth`  | 是   | 未知 |

**[⬆ 返回目录](#目录)**



## 电子邮件

| API                                                                                        | 描述                          | 认证Auth         | 支持HTTPS | 跨域CORS    |
|--------------------------------------------------------------------------------------------|--------------------------------------|----------|-------|---------|
| [Abstract Email Validation](https://www.abstractapi.com/email-verification-validation-api) | 验证电子邮件地址的可投递性和垃圾邮件                   | `apiKey` | 是   | 是     |
| [apilayer mailboxlayer](https://mailboxlayer.com)                                          | 电子邮件地址验证                             | `apiKey` | 是   | 未知 |
| [Cloudmersive Validate](https://cloudmersive.com/validate-api)                             | 验证电子邮件地址、电话号码、增值税号码和域名               | `apiKey` | 是   | 是     |
| [Disify](https://www.disify.com/)                                                          | 验证和检测一次性和临时电子邮件地址                    | 否       | 是   | 是     |
| [DropMail](https://dropmail.me/api/#live-demo)                                             | 用于创建和管理临时电子邮件收件箱的GraphQL API         | 否       | 是   | 未知 |
| [Emailvalidation](https://emailvalidation.io/email-validation-api/)                        | 电子邮件地址验证                             | `apiKey` | 是   | 是     |
| [EVA](https://eva.pingutil.com/)                                                           | 验证电子邮件地址                             | 否       | 是   | 是     |
| [Guerrilla Mail](https://www.guerrillamail.com/GuerrillaMailAPI.html)                      | 一次性临时电子邮件地址                          | 否       | 是   | 未知 |
| [ImprovMX](https://improvmx.com/api)                                                       | 免费电子邮件转发服务的API                       | `apiKey` | 是   | 未知 |
| [Kickbox](https://open.kickbox.com/)                                                       | 电子邮件验证API                            | 否       | 是   | 是     |
| [mail.gw](https://docs.mail.gw)                                                            | 10分钟邮箱                               | 否       | 是   | 是     |
| [mail.tm](https://docs.mail.tm)                                                            | 临时电子邮件服务                             | 否       | 是   | 是     |
| [MailboxValidator](https://www.mailboxvalidator.com/api-email-free)                        | 验证电子邮件地址以提高投递率                       | `apiKey` | 是   | 未知 |
| [MailCheck.ai](https://www.mailcheck.ai/#documentation)                                    | 防止用户使用临时电子邮件地址注册                     | 否       | 是   | 未知 |
| [Mailtrap](https://mailtrap.docs.apiary.io/#)                                              | 一个用于安全测试开发和测试环境发送的电子邮件的服务            | `apiKey` | 是   | 未知 |
| [Sendgrid](https://docs.sendgrid.com/api-reference/)                                       | 一个基于云的SMTP提供商，让你无需维护电子邮件服务器就可以发送电子邮件 | `apiKey` | 是   | 未知 |
| [Sendinblue](https://developers.sendinblue.com/docs)                                       | 提供与营销和/或事务性电子邮件和/或短信相关的解决方案的服务       | `apiKey` | 是   | 未知 |
| [Verifier](https://verifier.meetchopra.com/docs#/)                                         | 验证给定的电子邮件是真实的                        | `apiKey` | 是   | 是     |

**[⬆ 返回目录](#目录)**



## 娱乐

| API                                                                                 | 描述             | Auth | HTTPS | CORS    |
|-------------------------------------------------------------------------------------|-------------------------|------|-------|---------|
| [chucknorris.io](https://api.chucknorris.io)                                        | chuck Norris笑话的JSON API | 否   | 是   | 未知 |
| [Corporate Buzz Words](https://github.com/sameerkumar18/corporate-bs-generator-api) | 企业流行语的REST API          | 否   | 是   | 是     |
| [elonmu.sh](https://elonmu.sh/)                                                     | 获取随机的关于埃隆·马斯克的新闻文章      | 否   | 是   | 未知 |
| [Imgflip](https://imgflip.com/api)                                                  | 获取一个流行的表情包数组            | 否   | 是   | 未知 |
| [Meme Maker](https://mememaker.github.io/API/)                                      | 创建你自己的表情包的REST API      | 否   | 是   | 未知 |
| [NaMoMemes](https://github.com/theIYD/NaMoMemes)                                    | 关于纳伦德拉·莫迪的表情包           | 否   | 是   | 未知 |
| [Random Useless Facts](https://uselessfacts.jsph.pl/)                               | 获取无用但真实的事实              | 否   | 是   | 未知 |
| [Techy](https://techy-api.vercel.app/)                                              | 用于技术感十足的短语的JSON和纯文本API  | 否   | 是   | 未知 |
| [Yo Momma Jokes](https://github.com/beanboi7/yomomma-apiv2)                         | Yo Momma笑话的REST API     | 否   | 是   | 未知 |

**[⬆ 返回目录](#目录)**



## 生态环境

| API                                                                                                    | 描述                    | 认证Auth         | 支持HTTPS | 跨域CORS    |
|--------------------------------------------------------------------------------------------------------|--------------------------------|----------|-------|---------|
| [BreezoMeter Pollen](https://docs.breezometer.com/api-documentation/pollen-api/v2/)                    | 针对特定位置的每日预测花粉状况数据              | `apiKey` | 是   | 未知 |
| [Carbon Interface](https://docs.carboninterface.com/)                                                  | API 计算常见的 CO2 排放活动的碳（CO2）排放估算值 | `apiKey` | 是   | 是     |
| [Climatiq](https://docs.climatiq.io)                                                                   | 计算广泛的排放产生活动所产生的环境足迹            | `apiKey` | 是   | 是     |
| [Cloverly](https://www.cloverly.com/carbon-offset-documentation)                                       | API 实时计算常见的碳密集型活动的影响           | `apiKey` | 是   | 未知 |
| [CO2 Offset](https://co2offset.io/api.html)                                                            | API 计算和验证碳足迹                   | 否       | 是   | 未知 |
| [Danish data service Energi](https://www.energidataservice.dk/)                                        | 来自 Energinet 的开放能源数据，面向社会      | 否       | 是   | 未知 |
| [GrünstromIndex](https://gruenstromindex.de/)                                                          | 德国绿色电力指数（Grünstromindex/GSI）   | 否       | 否    | 是     |
| [IQAir](https://www.iqair.com/air-pollution-data-api)                                                  | 空气质量和天气数据                      | `apiKey` | 是   | 未知 |
| [Luchtmeetnet](https://api-docs.luchtmeetnet.nl/)                                                      | 荷兰预测和实际空气质量成分（RIVM）            | 否       | 是   | 未知 |
| [National Grid ESO](https://data.nationalgrideso.com/)                                                 | 来自英国电力系统运营商的开放数据               | 否       | 是   | 未知 |
| [OpenAQ](https://docs.openaq.org/)                                                                     | 开放空气质量数据                       | `apiKey` | 是   | 未知 |
| [PM2.5 Open Data Portal](https://pm25.lass-net.org/#apis)                                              | 开放低成本 PM2.5 传感器数据              | 否       | 是   | 未知 |
| [PM25.in](http://www.pm25.in/api_doc)                                                                  | 中国的空气质量                        | `apiKey` | 否    | 未知 |
| [PVWatts](https://developer.nrel.gov/docs/solar/pvwatts/v6/)                                           | 光伏（PV）能源系统的能源产量                | `apiKey` | 是   | 未知 |
| [Srp Energy](https://srpenergy-api-client-python.readthedocs.io/en/latest/api.html)                    | Srp 客户的每小时用电报告                 | `apiKey` | 是   | 否      |
| [Thames Water Open Data](https://data.thameswater.co.uk)                                               | 英国最大的水和废水服务公司的开放数据             | `apiKey` | 是   | 未知 |
| [UK Carbon Intensity](https://carbon-intensity.github.io/api-definitions/#carbon-intensity-api-v1-0-0) | 英国国家电网开发的英国官方碳强度 API           | 否       | 是   | 未知 |
| [WattBuy](https://wattbuy.readme.io/reference/getting-started-with-your-api)                           | 用电估算、碳足迹估算和公用事业数据              | `apiKey` | 是   | 是     |
| [Website Carbon](https://api.websitecarbon.com/)                                                       | API 估算加载网页的碳足迹                 | 否       | 是   | 未知 |

**[⬆ 返回目录](#目录)**



## 表演活动
| API                                                                                       | 描述 | 认证Auth         | 支持HTTPS | 跨域CORS    |
|-------------------------------------------------------------------------------------------|-------------|----------|-------|---------|
| [Eventbrite](https://www.eventbrite.com/platform/api/)                                    | 寻找演出活动      | `OAuth`  | 是   | 未知 |
| [SeatGeek](https://platform.seatgeek.com/)                                                | 搜索活动、场馆和演出  | `apiKey` | 是   | 未知 |
| [Ticketmaster](http://developer.ticketmaster.com/products-and-docs/apis/getting-started/) | 搜索活动、景点或场馆  | `apiKey` | 是   | 未知 |

**[⬆ 返回目录](#目录)**



## 金融

| API                                                                                                | 描述                                | 认证Auth         | 支持HTTPS | 跨域CORS    |
|----------------------------------------------------------------------------------------------------|--------------------------------------------|----------|-------|---------|
| [Abstract VAT Validation](https://www.abstractapi.com/vat-validation-rates-api)                    | 验证增值税号码并计算增值税率                             | `apiKey` | 是   | 是     |
| [Aletheia](https://aletheiaapi.com/)                                                               | 内幕交易数据、财报分析、财务报表等                          | `apiKey` | 是   | 是     |
| [Alpaca](https://alpaca.markets/docs/api-documentation/api-v2/market-data/alpaca-data-api-v2/)     | 实时和历史市场数据，涵盖所有美国股票和 ETF                    | `apiKey` | 是   | 是     |
| [Alpha Vantage](https://www.alphavantage.co/)                                                      | 实时和历史股票数据                                  | `apiKey` | 是   | 未知 |
| [apilayer marketstack](https://marketstack.com/)                                                   | 实时、日内和历史市场数据 API                           | `apiKey` | 是   | 未知 |
| [Atom Finance](https://atom.finance/)                                                              | Atom Finance 提供市场、收益和新闻数据的访问               | `apiKey` | 是   | 是     |
| [Banco do Brasil](https://developers.bb.com.br/home)                                               | 所有巴西银行的金融交易 API                            | `OAuth`  | 是   | 是     |
| [Billplz](https://www.billplz.com/api)                                                             | 支付平台                                       | `apiKey` | 是   | 未知 |
| [Binlist](https://binlist.net/)                                                                    | 公开访问 IIN/BIN 信息的数据库                        | 否       | 是   | 未知 |
| [Boleto.Cloud](https://boleto.cloud/)                                                              | 在巴西生成 boletos 的 API                        | `apiKey` | 是   | 未知 |
| [Citi](https://sandbox.developerhub.citi.com/api-catalog-list)                                     | 所有花旗集团的账户和对账单数据 API                        | `apiKey` | 是   | 未知 |
| [Econdb](https://www.econdb.com/api/)                                                              | 全球宏观经济数据                                   | 否       | 是   | 是     |
| [Fed Treasury](https://fiscaldata.treasury.gov/api-documentation/)                                 | 美国财政部数据                                    | 否       | 是   | 未知 |
| [Finage](https://finage.co.uk)                                                                     | Finage 是一个提供股票、货币、加密货币、指数和 ETF 实时和历史数据的服务商 | `apiKey` | 是   | 未知 |
| [Financial Modeling Prep](https://site.financialmodelingprep.com/developer/docs)                   | 实时和历史股票数据                                  | `apiKey` | 是   | 未知 |
| [Finnhub](https://finnhub.io/docs/api)                                                             | 股票、货币和加密货币的实时、日内和历史市场数据、新闻和情绪 API          | `apiKey` | 是   | 未知 |
| [FRED](https://fred.stlouisfed.org/docs/api/fred/)                                                 | 圣路易斯联邦储备银行的经济数据                            | `apiKey` | 是   | 是     |
| [Front Accounting APIs](https://frontaccounting.com/fawiki/index.php?n=Devel.SimpleAPIModule)      | Front accounting 是一款面向小型企业的多语言和多货币软件       | `OAuth`  | 是   | 是     |
| [IEX Cloud](https://iexcloud.io/docs/api/)                                                         | 实时和历史股票和市场数据                               | `apiKey` | 是   | 是     |
| [IG](https://labs.ig.com/gettingstarted)                                                           | Spreadbetting 和 CFD 市场数据                   | `apiKey` | 是   | 未知 |
| [Indian Mutual Fund](https://www.mfapi.in/)                                                        | 获取印度共同基金数据的完整历史记录                          | 否       | 是   | 未知 |
| [Intrinio](https://intrinio.com/)                                                                  | 多种金融数据源的选择                                 | `apiKey` | 是   | 未知 |
| [Klarna](https://docs.klarna.com/klarna-payments/api/payments-api/)                                | Klarna 支付和购物服务                             | `apiKey` | 是   | 未知 |
| [Kite Connect](https://kite.trade/docs/connect/v3/)                                                | 股市投资和交易平台                                  | `apiKey` | 是   | 否      |
| [MercadoPago](https://www.mercadopago.com.br/developers/es/reference)                              | Mercado Pago API 参考 - 开发集成所需的所有信息          | `apiKey` | 是   | 未知 |
| [Mono](https://mono.co/)                                                                           | 连接用户的银行账户并访问非洲的交易数据                        | `apiKey` | 是   | 未知 |
| [Moov](https://docs.moov.io/api/)                                                                  | Moov API 简化了平台发送、接收和存储资金的过程                | `apiKey` | 是   | 未知 |
| [Nordigen](https://nordigen.com/en/account_information_documenation/integration/quickstart_guide/) | 使用官方银行 API 连接用户的银行账户并获取原始交易数据              | `apiKey` | 是   | 未知 |
| [OpenFIGI](https://www.openfigi.com/api)                                                           | 来自彭博 LP 的股票、指数、期货、期权符号系统                   | `apiKey` | 是   | 是     |
| [Plaid](https://plaid.com/)                                                                        | 连接用户的银行账户并访问交易数据                           | `apiKey` | 是   | 未知 |
| [Polygon](https://polygon.io/)                                                                     | 历史股市数据                                     | `apiKey` | 是   | 未知 |
| [Portfolio Optimizer](https://portfoliooptimizer.io/)                                              | 投资组合分析和优化                                  | 否       | 是   | 是     |
| [Razorpay IFSC](https://razorpay.com/docs/)                                                        | 印度金融系统代码（银行分支代码）                           | 否       | 是   | 未知 |
| [Real Time Finance](https://github.com/Real-time-finance/finance-websocket-API/)                   | 访问实时股票数据的 Websocket API                    | `apiKey` | 否    | 未知 |
| [Repetiti](https://developers.repetiti.com/)                                                       | Repetiti 3d 打印机管理服务                        | `apiKey` | 是   | 是     |
| [SEC EDGAR Data](https://www.sec.gov/edgar/sec-api-documentation)                                  | 访问美国公开公司年报的 API                            | 否       | 是   | 是     |
| [SmartAPI](https://smartapi.angelbroking.com/)                                                     | 访问一系列 <SmartAPI> 并创建端到端的经纪服务               | `apiKey` | 是   | 未知 |
| [StockData](https://www.StockData.org)                                                             | 实时、日内和历史市场数据、新闻和情绪 API                     | `apiKey` | 是   | 是     |
| [Styvio](https://www.Styvio.com)                                                                   | 实时和历史股票数据以及当前股票情绪                          | `apiKey` | 是   | 未知 |
| [Tradier](https://developer.tradier.com)                                                           | 美国股票/期权市场数据（延迟、日内、历史）                      | `OAuth`  | 是   | 是     |
| [Twelve Data](https://twelvedata.com/)                                                             | 股市数据（实时和历史）                                | `apiKey` | 是   | 未知 |
| [WallstreetBets](https://dashboard.nbshare.io/apps/reddit/api/)                                    | WallstreetBets 股票评论情绪分析                    | 否       | 是   | 未知 |
| [YNAB](https://api.youneedabudget.com/)                                                            | 预算与计划                                      | `OAuth`  | 是   | 是     |
| [Zoho Books](https://www.zoho.com/books/api/v3/)

**[⬆ 返回目录](#目录)**


## 食品饮料

| API                                                                              | 描述         | 认证Auth         | 支持HTTPS | 跨域CORS    |
|----------------------------------------------------------------------------------|---------------------|----------|-------|---------|
| [BaconMockup](https://baconmockup.com/)                                          | 可调整大小的培根占位符图像       | 否       | 是   | 是     |
| [Chomp](https://chompthis.com/api/)                                              | 关于各种杂货产品和食品的数据      | `apiKey` | 是   | 未知 |
| [Coffee](https://coffee.alexflipnote.dev/)                                       | 随机的咖啡图片             | 否       | 是   | 未知 |
| [Edamam nutrition](https://developer.edamam.com/edamam-docs-nutrition-api)       | 营养分析                | `apiKey` | 是   | 未知 |
| [Edamam recipes](https://developer.edamam.com/edamam-docs-recipe-api)            | 食谱搜索                | `apiKey` | 是   | 未知 |
| [Foodish](https://github.com/surhud004/Foodish#readme)                           | 随机的食物菜肴图片           | 否       | 是   | 是     |
| [Fruityvice](https://www.fruityvice.com)                                         | 关于各种水果的数据           | 否       | 是   | 未知 |
| [Kroger](https://developer.kroger.com/reference)                                 | 超市数据                | `apiKey` | 是   | 未知 |
| [LCBO](https://lcboapi.com/)                                                     | 酒精                  | `apiKey` | 是   | 未知 |
| [Open Brewery DB](https://www.openbrewerydb.org)                                 | 啤酒厂、苹果酒厂和手工啤酒瓶店     | 否       | 是   | 是     |
| [Open Food Facts](https://world.openfoodfacts.org/data)                          | 食品产品数据库             | 否       | 是   | 未知 |
| [PunkAPI](https://punkapi.com/)                                                  | Brewdog啤酒食谱         | 否       | 是   | 未知 |
| [Spoonacular](https://spoonacular.com/food-api)                                  | 食谱、食品产品和膳食计划        | `apiKey` | 是   | 未知 |
| [Status Pizza](https://status.pizza)                                             | 每个HTTP状态的披萨         | 否       | 是   | 未知 |
| [Systembolaget](https://api-portal.systembolaget.se)                             | 瑞典政府拥有的酒类商店         | `apiKey` | 是   | 未知 |
| [TacoFancy](https://github.com/evz/tacofancy-api)                                | 社区驱动的塔可数据库          | 否       | 否    | 未知 |
| [Tasty](https://rapidapi.com/apidojo/api/tasty/)                                 | 查询关于食谱、计划、配料的数据的API | `apiKey` | 是   | 未知 |
| [The Report of the Week](https://github.com/andyklimczak/TheReportOfTheWeek-API) | 食物和饮料评论             | 否       | 是   | 未知 |
| [TheCocktailDB](https://www.thecocktaildb.com/api.php)                           | 鸡尾酒食谱               | `apiKey` | 是   | 是     |
| [TheMealDB](https://www.themealdb.com/api.php)                                   | 膳食食谱                | `apiKey` | 是   | 是     |
| [Untappd](https://untappd.com/api/docs)                                          | 社交啤酒分享              | `OAuth`  | 是   | 未知 |
| [What's on the menu?](http://nypl.github.io/menus-api/)                          | NYPL人工转录的历史菜单收藏     | `apiKey` | 否    | 未知 |
| [WhiskyHunter](https://whiskyhunter.net/api/)                                    | 过去的在线威士忌拍卖统计数据      | 否       | 是   | 未知 |
| [Zestful](https://zestfuldata.com/)                                              | 解析食谱配料              | `apiKey` | 是   | 是     |

**[⬆ 返回目录](#目录)**


## 游戏漫画

| API                                                                                         | 描述                                                    | Auth            | HTTPS | CORS    |
|---------------------------------------------------------------------------------------------|----------------------------------------------------------------|-----------------|-------|---------|
| [AmiiboAPI](https://amiiboapi.com/)                                                         | 任天堂Amiibo信息                                                    | 否              | 是   | 是     |
| [Animal Crossing: New Horizons](http://acnhapi.com/)                                        | 用于动物、化石、艺术品、音乐、家具和村民的API                                       | 否              | 是   | 未知 |
| [Atlas Academy](https://api.atlasacademy.io/docs)                                           | Fate/Grand Order游戏数据API                                        | 否              | 是   | 未知 |
| [Autochess VNG](https://github.com/didadadida93/autochess-vng-api)                          | Autochess VNG的Rest API                                         | 否              | 是   | 是     |
| [Barter.VG](https://github.com/bartervg/barter.vg/wiki)                                     | 提供有关游戏、DLC、捆绑包、赠品和交易的信息                                        | 否              | 是   | 是     |
| [Battle.net](https://develop.battle.net/documentation/guides/getting-started)               | Diablo III、Hearthstone、StarCraft II和World of Warcraft游戏数据API   | `OAuth`         | 是   | 是     |
| [Blue Archive](https://github.com/arufars/api-blue-archive)                                 | 提供Blue Archive角色的信息                                            | 否              | 是   | 是     |
| [Board Game Geek](https://boardgamegeek.com/wiki/page/BGG_XML_API2)                         | 桌游、角色扮演游戏和视频游戏                                                 | 否              | 是   | 否      |
| [Brawl Stars](https://developer.brawlstars.com)                                             | Brawl Stars游戏信息                                                | `apiKey`        | 是   | 未知 |
| [Bugsnax](https://www.bugsnaxapi.com/)                                                      | 获取有关Bugsnax的信息                                                 | 否              | 是   | 是     |
| [CheapShark](https://www.cheapshark.com/api)                                                | Steam/PC游戏价格和优惠                                                | 否              | 是   | 是     |
| [Chess.com](https://www.chess.com/news/view/published-data-api)                             | Chess.com只读REST API                                            | 否              | 是   | 未知 |
| [Chuck Norris Database](http://www.icndb.com/api/)                                          | 笑话                                                             | 否              | 否    | 未知 |
| [Clash of Clans](https://developer.clashofclans.com)                                        | Clash of Clans游戏信息                                             | `apiKey`        | 是   | 未知 |
| [Clash Royale](https://developer.clashroyale.com)                                           | Clash Royale游戏信息                                               | `apiKey`        | 是   | 未知 |
| [Comic Vine](https://comicvine.gamespot.com/api/documentation)                              | 漫画                                                             | 否              | 是   | 未知 |
| [Crafatar](https://crafatar.com)                                                            | Minecraft皮肤和面部的API                                             | 否              | 是   | 是     |
| [Cross Universe](https://crossuniverse.psychpsyo.com/apiDocs.html)                          | 跨宇宙卡片数据                                                        | 否              | 是   | 是     |
| [CSGO](https://bymykel.github.io/CSGO-API/)                                                 | 非官方的Counter-Strike: Global Offensive JSON API                  | 否              | 是   | 否      |
| [Deck of Cards](http://deckofcardsapi.com/)                                                 | 一副扑克牌                                                          | 否              | 否    | 未知 |
| [Destiny The Game](https://bungie-net.github.io/multi/index.html)                           | Bungie平台API                                                    | `apiKey`        | 是   | 未知 |
| [Digimon Information](https://digimon-api.vercel.app/)                                      | 提供数码宝贝生物的信息                                                    | 否              | 是   | 未知 |
| [Digimon TCG](https://documenter.getpostman.com/view/14059948/TzecB4fH)                     | 在digimoncard.io上搜索数码兽卡片                                        | 否              | 是   | 未知 |
| [Disney](https://disneyapi.dev)                                                             | 迪士尼角色的信息                                                       | 否              | 是   | 是     |
| [Dota 2](https://docs.opendota.com/)                                                        | 提供Dota 2玩家统计数据、比赛统计数据和排名信息                                     | `apiKey`        | 是   | 未知 |
| [Dungeons and Dragons](https://www.dnd5eapi.co/docs/)                                       | 第五版法术、职业、怪物等的参考资料                                              | 否              | 否    | 否      |
| [Dungeons and Dragons (Alternate)](https://open5e.com/)                                     | 包括SRD（系统参考文件）中的所有怪物和法术，以及一个搜索API                               | 否              | 是   | 是     |
| [Eve Online](https://esi.evetech.net/ui)                                                    | 第三方开发人员文档                                                      | `OAuth`         | 是   | 未知 |
| [FFXIV Collect](https://ffxivcollect.com/)                                                  | Final Fantasy XIV收藏品的数据                                        | 否              | 是   | 是     |
| [FIFA Ultimate Team](https://www.easports.com/fifa/ultimate-team/api/fut/item)              | FIFA Ultimate Team物品API                                        | 否              | 是   | 未知 |
| [Final Fantasy XIV](https://xivapi.com/)                                                    | Final Fantasy XIV游戏数据API                                       | 否              | 是   | 是     |
| [Fortnite](https://fortnitetracker.com/site-api)                                            | Fortnite统计数据                                                   | `apiKey`        | 是   | 未知 |
| [FreeToGame](https://www.freetogame.com/api-doc)                                            | 免费游戏数据库                                                        | 否              | 是   | 是     |
| [FunTranslations](https://api.funtranslations.com/)                                         | 将文本翻译成有趣的语言                                                    | 否              | 是   | 是     |
| [GamerPower](https://www.gamerpower.com/api-read)                                           | 游戏赠品追踪器                                                        | 否              | 是   | 是     |
| [Geek-Jokes](https://github.com/sameerkumar18/geek-joke-api)                                | 获取一个随机的极客/编程相关笑话，适用于各种应用程序                                     | 否              | 是   | 是     |
| [Genshin Impact](https://genshin.dev)                                                       | 原神游戏数据                                                         | 否              | 是   | 是     |
| [Giant Bomb](https://www.giantbomb.com/api/documentation)                                   | 视频游戏                                                           | `apiKey`        | 是   | 未知 |
| [GraphQL Pokemon](https://github.com/favware/graphql-pokemon)                               | 基于GraphQL的宝可梦API。支持第1到第8代                                      | 否              | 是   | 是     |
| [Guild Wars 2](https://wiki.guildwars2.com/wiki/API:Main)                                   | Guild Wars 2游戏信息                                               | `apiKey`        | 是   | 未知 |
| [GW2Spidy](https://github.com/rubensayshi/gw2spidy/wiki)                                    | GW2Spidy API，提供Guild Wars 2交易市场上的物品数据                          | 否              | 是   | 未知 |
| [Halo](https://developer.haloapi.com/)                                                      | Halo 5和Halo Wars 2的信息                                          | `apiKey`        | 是   | 未知 |
| [Hearthstone](http://hearthstoneapi.com/)                                                   | 炉石传说卡片信息                                                       | `X-Mashape-Key` | 是   | 未知 |
| [Humble Bundle](https://rapidapi.com/Ziggoto/api/humble-bundle)                             | Humble Bundle当前捆绑包                                             | `apiKey`        | 是   | 未知 |
| [Humor](https://humorapi.com)                                                               | 幽默、笑话和表情包                                                      | `apiKey`        | 是   | 未知 |
| [Hypixel](https://api.hypixel.net/)                                                         | Hypixel玩家统计数据                                                  | `apiKey`        | 是   | 未知 |
| [Hyrule Compendium](https://github.com/gadhagod/Hyrule-Compendium-API)                      | 《塞尔达传说：荒野之息》中所有互动物品的数据                                         | 否              | 是   | 未知 |
| [Hytale](https://hytale-api.com/)                                                           | Hytale博客帖子和职位                                                  | 否              | 是   | 未知 |
| [IGDB.com](https://api-docs.igdb.com)                                                       | 视频游戏数据库                                                        | `apiKey`        | 是   | 未知 |
| [Italian Jokes](https://italian-jokes.vercel.app/)                                          | 用于获取有关意大利笑话的JSON API                                           | 否              | 是   | 未知 |
| [JokeAPI](https://sv443.net/jokeapi/v2/)                                                    | 编程、杂项和黑暗笑话                                                     | 否              | 是   | 是     |
| [Jokes One](https://jokes.one/api/joke/)                                                    | 每日笑话和大量笑话类别，通过REST API访问                                       | `apiKey`        | 是   | 是     |
| [Jservice](http://jservice.io)                                                              | Jeopardy问题数据库                                                  | 否              | 否    | 未知 |
| [Lichess](https://lichess.org/api)                                                          | Lichess上用户、游戏、拼图等所有数据的访问                                       | `OAuth`         | 是   | 未知 |
| [Magic The Gathering](http://magicthegathering.io/)                                         | 魔法风云会游戏信息                                                      | 否              | 否    | 未知 |
| [Marvel](https://developer.marvel.com)                                                      | 漫威漫画                                                           | `apiKey`        | 是   | 未知 |
| [Minecraft Server Status](https://api.mcsrvstat.us)                                         | 获取有关Minecraft服务器的信息的API                                        | 否              | 是   | 否      |
| [MMO Games](https://www.mmobomb.com/api)                                                    | MMO游戏数据库、新闻和赠品                                                 | 否              | 是   | 否      |
| [mod.io](https://docs.mod.io)                                                               | 跨平台Mod API                                                     | `apiKey`        | 是   | 未知 |
| [Mojang](https://wiki.vg/Mojang_API)                                                        | Mojang / Minecraft API                                         | `apiKey`        | 是   | 未知 |
| [Monster Hunter World](https://docs.mhw-db.com/)                                            | 《怪物猎人世界》数据                                                     | 否              | 是   | 是     |
| [moogleAPI](https://www.moogleapi.com/)                                                     | Final Fantasy系列数据                                              | 否              | 是   | 未知 |
| [Open Trivia](https://opentdb.com/api_config.php)                                           | 问答题                                                            | 否              | 是   | 未知 |
| [PandaScore](https://developers.pandascore.co/)                                             | 电子竞技游戏和比赛结果                                                    | `apiKey`        | 是   | 未知 |
| [Path of Exile](https://www.pathofexile.com/developer/docs)                                 | 流亡之路游戏信息                                                       | `OAuth`         | 是   | 未知 |
| [PlayerDB](https://playerdb.co/)                                                            | 查询Minecraft、Steam和XBox账户                                       | 否              | 是   | 未知 |
| [Pokéapi](https://pokeapi.co)                                                               | 宝可梦信息                                                          | 否              | 是   | 未知 |
| [PokéAPI (GraphQL)](https://github.com/mazipan/graphql-pokeapi)                             | 非官方的GraphQL PokeAPI                                            | 否              | 是   | 是     |
| [Pokémon TCG](https://pokemontcg.io)                                                        | 宝可梦卡片信息                                                        | 否              | 是   | 未知 |
| [Psychonauts](https://psychonauts-api.netlify.app/)                                         | Psychonauts世界角色信息和PSI能力                                        | 否              | 是   | 是     |
| [PUBG](https://developer.pubg.com/)                                                         | 访问游戏内部的PUBG数据                                                  | `apiKey`        | 是   | 是     |
| [Puyo Nexus](https://github.com/deltadex7/puyodb-api-deno)                                  | 从Puyo Nexus Wiki获取关于Puyo Puyo的信息                               | 否              | 是   | 是     |
| [quizapi.io](https://quizapi.io/)                                                           | 访问各种类型的测验问题                                                    | `apiKey`        | 是   | 是     |
| [Raider](https://raider.io/api)                                                             | 提供魔兽世界中团队副本和史诗+内容的详细角色和公会排名                                    | 否              | 是   | 未知 |
| [RAWG.io](https://rawg.io/apidocs)                                                          | 包括移动设备在内的50个平台上的500,000多个游戏                                    | `apiKey`        | 是   | 未知 |
| [Rick and Morty](https://rickandmortyapi.com)                                               | 所有Rick and Morty的信息，包括图片                                       | 否              | 是   | 是     |
| [Riot Games](https://developer.riotgames.com/)                                              | 《英雄联盟》、《Teamfight Tactics》、《Legends of Runetera》和《Valorant》的信息 | `apiKey`        | 是   | 未知 |
| [RPS 101](https://rps101.pythonanywhere.com/api)                                            | 包含101个对象的石头、剪刀、布游戏                                             | 否              | 是   | 是     |
| [RuneScape](https://runescape.wiki/w/Application_programming_interface)                     | RuneScape和OSRS角色扮演游戏的信息                                        | 否              | 是   | 否      |
| [Sakura CardCaptor](https://github.com/JessVel/sakura-card-captor-api)                      | 《魔卡少女樱》（Sakura CardCaptor）卡片的信息                                | 否              | 是   | 未知 |
| [Scryfall](https://scryfall.com/docs/api)                                                   | 《魔法：聚光之战》（Magic: The Gathering）数据库                             | 否              | 是   | 是     |
| [SpaceTradersAPI](https://spacetraders.io?rel=pub-apis)                                     | 可玩的星际贸易MMOAPI                                                  | `OAuth`         | 是   | 是     |
| [Steam](https://steamapi.xpaw.me/)                                                          | Steam Web API文档                                                | `apiKey`        | 是   | 否      |
| [Steam](https://github.com/Revadike/InternalSteamWebAPI/wiki)                               | 内部Steam Web API文档                                              | 否              | 是   | 否      |
| [TCGdex](https://www.tcgdex.net/docs)                                                       | 多语言Pokémon TCG（宝可梦卡牌游戏）信息                                      | 否              | 是   | 是     |
| [Tebex](https://docs.tebex.io/plugin/)                                                      | Tebex API用于获取有关游戏购买的信息                                         | `X-Mashape-Key` | 是   | 否      |
| [TETR.IO](https://tetr.io/about/api/)                                                       | TETR.IO Tetra Channel API                                      | 否              | 是   | 未知 |
| [Tronald Dump](https://www.tronalddump.io/)                                                 | 唐纳德·特朗普说过的最愚蠢的话                                                | 否              | 是   | 未知 |
| [Universalis](https://universalis.app/docs/index.html)                                      | 《最终幻想XIV》市场信息                                                  | 否              | 是   | 是     |
| [Valorant (non-official)](https://valorant-api.com)                                         | 包含大多数Valorant游戏内物品、资产等数据的广泛API                                 | 否              | 是   | 未知 |
| [Warface (non-official)](https://api.wfstats.cf)                                            | 官方API代理，具有更好的数据结构和更多功能                                         | 否              | 是   | 否      |
| [Wargaming.net](https://developers.wargaming.net/)                                          | Wargaming.net信息和统计数据                                           | `apiKey`        | 是   | 否      |
| [When is next MCU film](https://github.com/DiljotSG/MCU-Countdown/blob/develop/docs/API.md) | 即将上映的漫威影片信息                                                    | 否              | 是   | 未知 |
| [xkcd](https://xkcd.com/json.html)                                                          | 以JSON格式检索xkcd漫画                                                | 否              | 是   | 否      |
| [Yu-Gi-Oh!](https://db.ygoprodeck.com/api-guide/)                                           | 《游戏王》（Yu-Gi-Oh!）TCG信息                                          | 否              | 是   | 未知 |
| [Zelda](https://docs.zelda.fanapis.com/docs)                                                | 《塞尔达传说》系列数据                                                    | 否              | 是   | 未知 |

**[⬆ 返回目录](#目录)**



## 政府

| API                                                                                                           | 描述                        | 认证Auth         | 支持HTTPS | 跨域CORS    |
|---------------------------------------------------------------------------------------------------------------|------------------------------------|----------|-------|---------|
| [Bank Negara Malaysia Open Data](https://apikijangportal.bnm.gov.my/)                                         | 马来西亚中央银行开放数据                       | 否       | 是   | 未知 |
| [BCLaws](https://www.bclaws.gov.bc.ca/civix/template/complete/api/index.html)                                 | 访问不列颠哥伦比亚省的法律                      | 否       | 否    | 未知 |
| [Brazil](https://brasilapi.com.br/)                                                                           | 巴西公共数据的社区驱动API                     | 否       | 是   | 是     |
| [Brazil Central Bank Open Data](https://dadosabertos.bcb.gov.br/)                                             | 巴西中央银行开放数据                         | 否       | 是   | 未知 |
| [Brazil Receita WS](https://www.receitaws.com.br/)                                                            | 通过CNPJ查询巴西公司                       | 否       | 是   | 未知 |
| [Brazilian Chamber of Deputies Open Data](https://dadosabertos.camara.leg.br/swagger/api.html)                | 提供Apis XML和JSON的立法信息，以及各种格式的文件     | 否       | 是   | 否      |
| [Census.gov](https://www.census.gov/data/developers/data-sets.html)                                           | 美国人口普查局提供各种有关人口统计和企业的API和数据集       | 否       | 是   | 未知 |
| [City, Berlin](https://daten.berlin.de/)                                                                      | 柏林（德国）城市开放数据                       | 否       | 是   | 未知 |
| [City, Gdańsk](https://ckan.multimediagdansk.pl/en)                                                           | 格但斯克（波兰）城市开放数据                     | 否       | 是   | 未知 |
| [City, Gdynia](http://otwartedane.gdynia.pl/en/api_doc.html)                                                  | 格丁尼亚（波兰）城市开放数据                     | 否       | 否    | 未知 |
| [City, Helsinki](https://hri.fi/en_gb/)                                                                       | 赫尔辛基（芬兰）城市开放数据                     | 否       | 是   | 未知 |
| [City, Lviv](https://opendata.city-adm.lviv.ua/)                                                              | 利沃夫（乌克兰）城市开放数据                     | 否       | 是   | 未知 |
| [City, Nantes Open Data](https://data.nantesmetropole.fr/pages/home/)                                         | 南特（法国）城市开放数据                       | `apiKey` | 是   | 未知 |
| [City, New York Open Data](https://opendata.cityofnewyork.us/)                                                | 纽约（美国）城市开放数据                       | 否       | 是   | 未知 |
| [City, Prague Open Data](http://opendata.praha.eu/en)                                                         | 布拉格（捷克）城市开放数据                      | 否       | 否    | 未知 |
| [City, Toronto Open Data](https://open.toronto.ca/)                                                           | 多伦多（加拿大）城市开放数据                     | 否       | 是   | 是     |
| [Code.gov](https://code.gov)                                                                                  | 美国联邦政府的主要开源和代码共享平台                 | `apiKey` | 是   | 未知 |
| [Colorado Information Marketplace](https://data.colorado.gov/)                                                | 科罗拉多州政府开放数据                        | 否       | 是   | 未知 |
| [Data USA](https://datausa.io/about/api/)                                                                     | 美国公共数据                             | 否       | 是   | 未知 |
| [Data.gov](https://api.data.gov/)                                                                             | 美国政府数据                             | `apiKey` | 是   | 未知 |
| [Data.parliament.uk](https://explore.data.parliament.uk/?learnmore=Members)                                   | 包含关于请愿书、议案、议员投票、出席情况等实时数据集         | 否       | 否    | 未知 |
| [Deutscher Bundestag DIP](https://dip.bundestag.de/documents/informationsblatt_zur_dip_api_v01.pdf)           | 该API提供对DIP实体（如活动、个人、印刷材料）的读取访问     | `apiKey` | 是   | 未知 |
| [District of Columbia Open Data](http://opendata.dc.gov/pages/using-apis)                                     | 包含华盛顿特区政府的公共数据集，包括犯罪、地理信息系统、财务数据等等 | 否       | 是   | 未知 |
| [EPA](https://www.epa.gov/developers/data-data-products#apis)                                                 | 美国环境保护局的网络服务和数据集                   | 否       | 是   | 未知 |
| [FBI Wanted](https://www.fbi.gov/wanted/api)                                                                  | 访问有关FBI通缉计划的信息                     | 否       | 是   | 未知 |
| [FEC](https://api.open.fec.gov/developers/)                                                                   | 联邦选举中的竞选捐款信息                       | `apiKey` | 是   | 未知 |
| [Federal Register](https://www.federalregister.gov/reader-aids/developer-resources/rest-api)                  | 美国政府每日期刊                           | 否       | 是   | 未知 |
| [Food Standards Agency](http://ratings.food.gov.uk/open-data/en-GB)                                           | 英国食品卫生评级数据API                      | 否       | 否    | 未知 |
| [Gazette Data, UK](https://www.thegazette.co.uk/data)                                                         | 英国官方公共记录API                        | `OAuth`  | 是   | 未知 |
| [Gun Policy](https://www.gunpolicy.org/api)                                                                   | 国际防止枪支伤害和政策数据                      | `apiKey` | 是   | 未知 |
| [INEI](http://iinei.inei.gob.pe/microdatos/)                                                                  | 秘鲁统计政府开放数据                         | 否       | 否    | 未知 |
| [Interpol Red Notices](https://interpol.api.bund.dev/)                                                        | 访问和搜索国际刑警组织红色通报                    | 否       | 是   | 未知 |
| [Istanbul (İBB) Open Data](https://data.ibb.gov.tr)                                                           | 来自伊斯坦布尔大都市市政府（İBB）的数据集             | 否       | 是   | 未知 |
| [National Park Service, US](https://www.nps.gov/subjects/developer/)                                          | 来自美国国家公园管理局的数据                     | `apiKey` | 是   | 是     |
| [Open Government, ACT](https://www.data.act.gov.au/)                                                          | 澳大利亚首都地区开放数据                       | 否       | 是   | 未知 |
| [Open Government, Argentina](https://datos.gob.ar/)                                                           | 阿根廷政府开放数据                          | 否       | 是   | 未知 |
| [Open Government, Australia](https://www.data.gov.au/)                                                        | 澳大利亚政府开放数据                         | 否       | 是   | 未知 |
| [Open Government, Austria](https://www.data.gv.at/)                                                           | 奥地利政府开放数据                          | 否       | 是   | 未知 |
| [Open Government, Belgium](https://data.gov.be/)                                                              | 比利时政府开放数据                          | 否       | 是   | 未知 |
| [Open Government, Canada](http://open.canada.ca/en)                                                           | 加拿大政府开放数据                          | 否       | 否    | 未知 |
| [Open Government, Colombia](https://www.dane.gov.co/)                                                         | 哥伦比亚政府开放数据                         | 否       | 否    | 未知 |
| [Open Government, Cyprus](https://data.gov.cy/?language=en)                                                   | 塞浦路斯政府开放数据                         | 否       | 是   | 未知 |
| [Open Government, Czech Republic](https://data.gov.cz/english/)                                               | 捷克共和国政府开放数据                        | 否       | 是   | 未知 |
| [Open Government, Denmark](https://www.opendata.dk/)                                                          | 丹麦政府开放数据                           | 否       | 是   | 未知 |
| [Open Government, Estonia](https://avaandmed.eesti.ee/instructions/opendata-dataset-api)                      | 爱沙尼亚政府开放数据                         | `apiKey` | 是   | 未知 |
| [Open Government, Finland](https://www.avoindata.fi/en)                                                       | 芬兰政府开放数据                           | 否       | 是   | 未知 |
| [Open Government, France](https://www.data.gouv.fr/)                                                          | 法国政府开放数据                           | `apiKey` | 是   | 未知 |
| [Open Government, Germany](https://www.govdata.de/daten/-/details/govdata-metadatenkatalog)                   | 德国政府开放数据                           | 否       | 是   | 未知 |
| [Open Government, Greece](https://data.gov.gr/)                                                               | 希腊政府开放数据                           | `OAuth`  | 是   | 未知 |
| [Open Government, India](https://data.gov.in/)                                                                | 印度政府开放数据                           | `apiKey` | 是   | 未知 |
| [Open Government, Ireland](https://data.gov.ie/pages/developers)                                              | 爱尔兰政府开放数据                          | 否       | 是   | 未知 |
| [Open Government, Italy](https://www.dati.gov.it/)                                                            | 意大利政府开放数据                          | 否       | 是   | 未知 |
| [Open Government, Korea](https://www.data.go.kr/)                                                             | 韩国政府开放数据                           | `apiKey` | 是   | 未知 |
| [Open Government, Lithuania](https://data.gov.lt/public/api/1)                                                | 立陶宛政府开放数据                          | 否       | 是   | 未知 |
| [Open Government, Luxembourg](https://data.public.lu)                                                         | 卢森堡政府开放数据                          | `apiKey` | 是   | 未知 |
| [Open Government, Mexico](https://www.inegi.org.mx/datos/)                                                    | 墨西哥统计政府开放数据                        | 否       | 是   | 未知 |
| [Open Government, Mexico](https://datos.gob.mx/)                                                              | 墨西哥政府开放数据                          | 否       | 是   | 未知 |
| [Open Government, Netherlands](https://data.overheid.nl/en/ondersteuning/data-publiceren/api)                 | 荷兰政府开放数据                           | 否       | 是   | 未知 |
| [Open Government, New South Wales](https://api.nsw.gov.au/)                                                   | 新南威尔士州政府开放数据                       | `apiKey` | 是   | 未知 |
| [Open Government, New Zealand](https://www.data.govt.nz/)                                                     | 新西兰政府开放数据                          | 否       | 是   | 未知 |
| [Open Government, Norway](https://data.norge.no/dataservices)                                                 | 挪威政府开放数据                           | 否       | 是   | 是     |
| [Open Government, Peru](https://www.datosabiertos.gob.pe/)                                                    | 秘鲁政府开放数据                           | 否       | 是   | 未知 |
| [Open Government, Poland](https://dane.gov.pl/en)                                                             | 波兰政府开放数据                           | 否       | 是   | 是     |
| [Open Government, Portugal](https://dados.gov.pt/en/docapi/)                                                  | 葡萄牙政府开放数据                          | `apiKey` | 是   | 是     |
| [Open Government, Queensland Government](https://www.data.qld.gov.au/)                                        | 昆士兰州政府开放数据                         | 否       | 是   | 未知 |
| [Open Government, Romania](http://data.gov.ro/)                                                               | 罗马尼亚政府开放数据                         | 否       | 否    | 未知 |
| [Open Government, Saudi Arabia](https://data.gov.sa)                                                          | 沙特阿拉伯政府开放数据                        | 否       | 是   | 未知 |
| [Open Government, Singapore](https://data.gov.sg/developer)                                                   | 新加坡政府开放数据                          | 否       | 是   | 未知 |
| [Open Government, Slovakia](https://data.gov.sk/en/)                                                          | 斯洛伐克政府开放数据                         | 否       | 是   | 未知 |
| [Open Government, Slovenia](https://podatki.gov.si/)                                                          | 斯洛文尼亚政府开放数据                        | 否       | 是   | 否      |
| [Open Government, South Australian Government](https://data.sa.gov.au/)                                       | 南澳大利亚政府开放数据                        | 否       | 是   | 未知 |
| [Open Government, Spain](https://datos.gob.es/en)                                                             | 西班牙政府开放数据                          | 否       | 是   | 未知 |
| [Open Government, Sweden](https://www.dataportal.se/en/dataservice/91_29789/api-for-the-statistical-database) | 瑞典政府开放数据                           | 否       | 是   | 未知 |
| [Open Government, Switzerland](https://handbook.opendata.swiss/de/content/nutzen/api-nutzen.html)             | 瑞士政府开放数据                           | 否       | 是   | 未知 |
| [Open Government, Taiwan](https://data.gov.tw/)                                                               | 台湾政府开放数据                           | 否       | 是   | 未知 |
| [Open Government, Thailand](https://data.go.th/)                                                              | 泰国政府开放数据                           | `apiKey` | 是   | 未知 |
| [Open Government, UK](https://data.gov.uk/)                                                                   | 英国政府开放数据                           | 否       | 是   | 未知 |
| [Open Government, USA](https://www.data.gov/)                                                                 | 美国政府开放数据                           | 否       | 是   | 未知 |
| [Open Government, Victoria State Government](https://www.data.vic.gov.au/)                                    | 维多利亚州政府开放数据                        | 否       | 是   | 未知 |
| [Open Government, West Australia](https://data.wa.gov.au/)                                                    | 西澳大利亚开放数据                          | 否       | 是   | 未知 |
| [PRC Exam Schedule](https://api.whenisthenextboardexam.com/docs/)                                             | 非官方菲律宾专业监管委员会考试时间表                 | 否       | 是   | 是     |
| [Represent by Open North](https://represent.opennorth.ca/)                                                    | 查找加拿大政府代表                          | 否       | 是   | 未知 |
| [UK Companies House](https://developer.company-information.service.gov.uk/)                                   | 英国公司注册局的数据（来自英国政府）                 | `OAuth`  | 是   | 未知 |
| [US Presidential Election Data by TogaTech](https://uselection.togatech.org/api/)                             | 美国总统选举中两个主要政党候选人的基本候选人数据和实时选举投票计数  | 否       | 是   | 否      |
| [USA.gov](https://www.usa.gov/developer)                                                                      | 关于美国项目、活动、服务等的权威信息                 | `apiKey` | 是   | 未知 |
| [USAspending.gov](https://api.usaspending.gov/)                                                               | 美国联邦支出数据                           | 否       | 是   | 未知 |

**[⬆ 返回目录](#目录)**



## 健康

| API                                                                                                               | 描述                         | 认证Auth         | 支持HTTPS | 跨域CORS    |
|-------------------------------------------------------------------------------------------------------------------|-------------------------------------|----------|-------|---------|
| [CMS.gov](https://data.cms.gov/provider-data/)                                                                    | 访问CMS（美国医保险局官方）的数据                  | `apiKey` | 是   | 未知 |
| [Coronavirus](https://pipedream.com/@pravin/http-api-for-latest-wuhan-coronavirus-data-2019-ncov-p_G6CLVM/readme) | 最新Covid-19数据的HTTP API               | 否       | 是   | 未知 |
| [Coronavirus in the UK](https://coronavirus.data.gov.uk/details/developers-guide)                                 | 英国政府的冠状病毒数据，包括按地区划分的死亡和病例数          | 否       | 是   | 未知 |
| [Covid Tracking Project](https://covidtracking.com/data/api/version-2)                                            | 美国的Covid-19数据                       | 否       | 是   | 否      |
| [Covid-19](https://covid19api.com/)                                                                               | Covid 19传播、感染和康复情况                  | 否       | 是   | 是     |
| [Covid-19](https://github.com/M-Media-Group/Covid-19-API)                                                         | 各个国家的Covid 19病例、死亡和康复情况             | 否       | 是   | 是     |
| [Covid-19 Datenhub](https://npgeo-corona-npgeo-de.hub.arcgis.com)                                                 | 在COVID-19背景下的地图、数据集、应用等等            | 否       | 是   | 未知 |
| [Covid-19 Government Response](https://covidtracker.bsg.ox.ac.uk)                                                 | 追踪抗击Covid-19大流行的政府措施                | 否       | 是   | 是     |
| [Covid-19 India](https://data.covid19india.org/)                                                                  | 有关印度病例、接种和康复情况的Covid 19统计数据         | 否       | 是   | 未知 |
| [Covid-19 JHU CSSE](https://nuttaphat.com/covid19-api/)                                                           | 基于JHU CSSE的开源API，用于探索Covid19病例      | 否       | 是   | 是     |
| [Covid-19 Live Data](https://github.com/mathdroid/covid-19-api)                                                   | 全球和各国每日Covid 19总结、确诊病例、康复人数和死亡人数的数据 | 否       | 是   | 是     |
| [Covid-19 Philippines](https://github.com/Simperfy/Covid-19-API-Philippines-DOH)                                  | 非官方菲律宾Covid-19 Web API，收集自DOH的数据    | 否       | 是   | 是     |
| [COVID-19 Tracker Canada](https://api.covid19tracker.ca/docs/1.0/overview)                                        | 加拿大各地的Covid-19病例详细信息                | 否       | 是   | 未知 |
| [COVID-19 Tracker Sri Lanka](https://www.hpb.health.gov.lk/en/api-documentation)                                  | 提供斯里兰卡报告的COVID-19患者情况               | 否       | 是   | 未知 |
| [COVID-ID](https://data.covid19.go.id/public/api/prov.json)                                                       | 印尼政府按省份提供的Covid数据                   | 否       | 是   | 是     |
| [Dataflow Kit COVID-19](https://covid-19.dataflowkit.com)                                                         | 每小时更新的COVID-19网站实时统计数据              | 否       | 是   | 未知 |
| [FoodData Central](https://fdc.nal.usda.gov/)                                                                     | 国家标准参考营养数据库                         | `apiKey` | 是   | 未知 |
| [Healthcare.gov](https://www.healthcare.gov/developers/)                                                          | 关于美国医疗保险市场的教育内容                     | 否       | 是   | 未知 |
| [Humanitarian Data Exchange](https://data.humdata.org/)                                                           | 人道数据交换（HDX）是一个开放的平台，用于在危机和组织之间共享数据  | 否       | 是   | 未知 |
| [Infermedica](https://developer.infermedica.com/docs/)                                                            | 基于自然语言处理的症状检查器和患者分诊API，用于从文本进行健康诊断  | `apiKey` | 是   | 是     |
| [LAPIS](https://cov-spectrum.ethz.ch/public)                                                                      | 来自公共来源的SARS-CoV-2基因组序列              | 否       | 是   | 是     |
| [Lexigram](https://docs.lexigram.io/)                                                                             | 提取文本中临床概念提及并访问临床本体知识的自然语言处理工具       | `apiKey` | 是   | 未知 |
| [Makeup](http://makeup-api.herokuapp.com/)                                                                        | 化妆品信息                               | 否       | 否    | 未知 |
| [MyVaccination](https://documenter.getpostman.com/view/16605343/Tzm8GG7u)                                         | 马来西亚的疫苗接种数据                         | 否       | 是   | 未知 |
| [NPPES](https://npiregistry.cms.hhs.gov/registry/help-api)                                                        | 国家计划和提供者枚举系统，提供注册在美国的医疗保健提供者的信息     | 否       | 是   | 未知 |
| [Nutritionix](https://developer.nutritionix.com/)                                                                 | 世界上最大的经过验证的营养数据库                    | `apiKey` | 是   | 未知 |
| [Open Data NHS Scotland](https://www.opendata.nhs.scot)                                                           | 由苏格兰公共卫生部门提供的医疗参考数据和统计数据            | 否       | 是   | 未知 |
| [Open Disease](https://disease.sh/)                                                                               | 有关当前病例和COVID-19、流感等相关信息的API         | 否       | 是   | 是     |
| [openFDA](https://open.fda.gov)                                                                                   | 关于药物、医疗设备和食品的公共FDA数据                | `apiKey` | 是   | 未知 |
| [Orion Health](https://developer.orionhealth.io/)                                                                 | 医疗平台，可开发适用于不同医疗场景的应用程序              | `OAuth`  | 是   | 未知 |
| [Quarantine](https://quarantine.country/coronavirus/api/)                                                         | 带有免费COVID-19实时更新的冠状病毒API            | 否       | 是   | 是     |

**[⬆ 返回目录](#目录)**



## 招聘

| API                                                                                      | 描述                | 认证Auth         | 支持HTTPS | 跨域CORS    |
|------------------------------------------------------------------------------------------|----------------------------|----------|-------|---------|
| [Adzuna](https://developer.adzuna.com/overview)                                          | 招聘信息聚合平台                   | `apiKey` | 是   | 未知 |
| [Arbeitnow](https://documenter.getpostman.com/view/18545278/UVJbJdKh)                    | 欧洲/远程招聘信息聚合平台的API          | 否       | 是   | 是     |
| [Arbeitsamt](https://jobsuche.api.bund.dev/)                                             | 德国招聘信息聚合平台"Arbeitsamt"的API | `OAuth`  | 是   | 未知 |
| [Careerjet](https://www.careerjet.com/partners/api/)                                     | 招聘搜索引擎                     | `apiKey` | 否    | 未知 |
| [DevITjobs UK](https://devitjobs.uk/job_feed.xml)                                        | 使用GraphQL的职位               | 否       | 是   | 是     |
| [Findwork](https://findwork.dev/developers/)                                             | 招聘信息平台                     | `apiKey` | 是   | 未知 |
| [GraphQL Jobs](https://graphql.jobs/docs/api/)                                           | 使用GraphQL的职位               | 否       | 是   | 是     |
| [Jobs2Careers](http://api.jobs2careers.com/api/spec.pdf)                                 | 招聘信息聚合器                    | `apiKey` | 是   | 未知 |
| [Jooble](https://jooble.org/api/about)                                                   | 招聘搜索引擎                     | `apiKey` | 是   | 未知 |
| [Juju](http://www.juju.com/publisher/spec/)                                              | 招聘搜索引擎                     | `apiKey` | 否    | 未知 |
| [Open Skills](https://github.com/workforce-data-initiative/skills-api/wiki/API-Overview) | 职位名称、技能和相关招聘数据             | 否       | 否    | 未知 |
| [Reed](https://www.reed.co.uk/developers)                                                | 招聘信息聚合平台                   | `apiKey` | 是   | 未知 |
| [The Muse](https://www.themuse.com/developers/api/v2)                                    | 招聘信息平台和公司档案                | `apiKey` | 是   | 未知 |
| [Upwork](https://developers.upwork.com/)                                                 | 自由职业者招聘信息平台和管理系统           | `OAuth`  | 是   | 未知 |
| [USAJOBS](https://developer.usajobs.gov/)                                                | 美国政府招聘信息平台                 | `apiKey` | 是   | 未知 |
| [WhatJobs](https://www.whatjobs.com/affiliates)                                          | 招聘搜索引擎                     | `apiKey` | 是   | 未知 |

**[⬆ 返回目录](#目录)**




## 机器学习
| API                                                                               | 描述                                       | 认证Auth         | 支持HTTPS | 跨域CORS    |
|-----------------------------------------------------------------------------------|---------------------------------------------------|----------|-------|---------|
| [AI For Thai](https://aiforthai.in.th/index.php)                                  | 泰国国家科学技术发展局下属的免费人工智能API                           | `apiKey` | 是   | 是     |
| [Clarifai](https://docs.clarifai.com/api-guide/api-overview)                      | 计算机视觉                                             | `OAuth`  | 是   | 未知 |
| [Cloudmersive](https://www.cloudmersive.com/image-recognition-and-processing-api) | 图像描述、人脸识别、不安全内容分类                                 | `apiKey` | 是   | 是     |
| [Cohere](https://docs.cohere.ai/)                                                 | 利用语言理解的力量。加入使用Cohere生成、分类和组织文本的开发者和企业，以前是难以想象的规模。 | `apiKey` | 是   | 是     |
| [Dialogflow](https://cloud.google.com/dialogflow/docs/)                           | 自然语言处理                                            | `apiKey` | 是   | 未知 |
| [EXUDE-API](http://uttesh.com/exude-api/)                                         | 用于从文本数据中过滤停用词、词干化的主要方法                            | 否       | 是   | 是     |
| [Gladia](https://api.gladia.io/docs)                                              | 人工智能API                                           | `apiKey` | 是   | 否      |
| [Imagga](https://imagga.com/)                                                     | 图像识别解决方案，如标记、视觉搜索、不安全内容管理                         | `apiKey` | 是   | 未知 |
| [Inferdo](https://rapidapi.com/user/inferdo)                                      | 计算机视觉服务，如人脸检测、图像标注、不良内容分类                         | `apiKey` | 是   | 未知 |
| [IPS Online](https://docs.identity.ps/docs)                                       | 人脸和车牌匿名化                                          | `apiKey` | 是   | 未知 |
| [Irisnet](https://irisnet.de/api/)                                                | 实时内容审核API，可实时阻止或模糊不需要的图像                          | `apiKey` | 是   | 是     |
| [Keen IO](https://keen.io/)                                                       | 数据分析                                              | `apiKey` | 是   | 未知 |
| [Machinetutors](https://www.machinetutors.com/portfolio/MT_api.html)              | 人工智能解决方案：视频/图像分类与标记、不安全内容、图标/图像/音频搜索、自然语言处理       | `apiKey` | 是   | 是     |
| [MessengerX.io](https://messengerx.rtfd.io)                                       | 用于开发者构建个性化机器学习聊天应用程序并实现盈利的免费API                   | `apiKey` | 是   | 是     |
| [NLP Cloud](https://nlpcloud.io)                                                  | 使用spaCy和transformers进行命名实体识别、情感分析、分类、摘要等的NLP API  | `apiKey` | 是   | 未知 |
| [OpenVisionAPI](https://openvisionapi.com)                                        | 基于开源模型的开源计算机视觉API                                 | 否       | 是   | 是     |
| [Perspective](https://perspectiveapi.com)                                         | NLP API，返回文本是否有害、淫秽、侮辱或威胁的概率                      | `apiKey` | 是   | 未知 |
| [Roboflow Universe](https://universe.roboflow.com)                                | 预训练的计算机视觉模型                                       | `apiKey` | 是   | 是     |
| [SkyBiometry](https://skybiometry.com/documentation/)                             | 人脸检测、人脸识别和人脸分组                                    | `apiKey` | 是   | 未知 |
| [Unplugg](https://unplu.gg/test_api.html)                                         | 用于时间序列数据的预测API                                    | `apiKey` | 是   | 未知 |
| [WolframAlpha](https://products.wolframalpha.com/api/)                            | 使用数据和算法提供特定问题的具体答案                                | `apiKey` | 是   | 未知 |

**[⬆ 返回目录](#目录)**



## 音乐

| API                                                                                                              | 描述                           | 认证Auth         | 支持HTTPS | 跨域CORS    |
|------------------------------------------------------------------------------------------------------------------|---------------------------------------|----------|-------|---------|
| [7digital](https://docs.7digital.com/reference)                                                                  | 7digital音乐商店的API                      | `OAuth`  | 是   | 未知 |
| [AI Mastering](https://aimastering.com/api_docs/)                                                                | 自动化音乐母带处理                             | `apiKey` | 是   | 是     |
| [Audiomack](https://www.audiomack.com/data-api/docs)                                                             | Audiomack流媒体音乐中心的API                  | `OAuth`  | 是   | 未知 |
| [Bandcamp](https://bandcamp.com/developer)                                                                       | Bandcamp音乐商店的API                      | `OAuth`  | 是   | 未知 |
| [Bandsintown](https://app.swaggerhub.com/apis/Bandsintown/PublicAPI/3.0.0)                                       | 音乐活动                                  | 否       | 是   | 未知 |
| [Deezer](https://developers.deezer.com/api)                                                                      | 音乐                                    | `OAuth`  | 是   | 未知 |
| [Discogs](https://www.discogs.com/developers/)                                                                   | 音乐                                    | `OAuth`  | 是   | 未知 |
| [Freesound](https://freesound.org/docs/api/)                                                                     | 音乐样本                                  | `apiKey` | 是   | 未知 |
| [Gaana](https://github.com/cyberboysumanjay/GaanaAPI)                                                            | 从Gaana检索歌曲信息的API                      | 否       | 是   | 未知 |
| [Genius](https://docs.genius.com/)                                                                               | 众包歌词和音乐知识                             | `OAuth`  | 是   | 未知 |
| [Genrenator](https://binaryjazz.us/genrenator-api/)                                                              | 音乐流派生成器                               | 否       | 是   | 未知 |
| [iTunes Search](https://affiliate.itunes.apple.com/resources/documentation/itunes-store-web-service-search-api/) | 软件产品                                  | 否       | 是   | 未知 |
| [Jamendo](https://developer.jamendo.com/v3.0/docs)                                                               | 音乐                                    | `OAuth`  | 是   | 未知 |
| [JioSaavn](https://github.com/cyberboysumanjay/JioSaavnAPI)                                                      | 从JioSaavn检索歌曲信息、专辑元数据等的API            | 否       | 是   | 未知 |
| [KKBOX](https://developer.kkbox.com)                                                                             | 获取KKBOX平台上的音乐库、播放列表、排行榜等              | `OAuth`  | 是   | 未知 |
| [KSoft.Si Lyrics](https://docs.ksoft.si/api/lyrics-api)                                                          | 获取歌曲歌词的API                            | `apiKey` | 是   | 未知 |
| [LastFm](https://www.last.fm/api)                                                                                | 音乐                                    | `apiKey` | 是   | 未知 |
| [Lyrics.ovh](https://lyricsovh.docs.apiary.io)                                                                   | 简单的API用于检索歌曲的歌词                       | 否       | 是   | 未知 |
| [Mixcloud](https://www.mixcloud.com/developers/)                                                                 | 音乐                                    | `OAuth`  | 是   | 是     |
| [MusicBrainz](https://musicbrainz.org/doc/Development/XML_Web_Service/Version_2)                                 | 音乐                                    | 否       | 是   | 未知 |
| [Musixmatch](https://developer.musixmatch.com/)                                                                  | 音乐                                    | `apiKey` | 是   | 未知 |
| [Napster](https://developer.napster.com/api/v2.2)                                                                | 音乐                                    | `apiKey` | 是   | 是     |
| [Openwhyd](https://openwhyd.github.io/openwhyd/API)                                                              | 下载经过策划的流媒体曲目播放列表（YouTube、SoundCloud等） | 否       | 是   | 否      |
| [Phishin](https://phish.in/api-docs)                                                                             | Phish即兴摇滚乐队合法现场音频录音的基于Web的档案          | `apiKey` | 是   | 否      |
| [Radio Browser](https://api.radio-browser.info/)                                                                 | 互联网广播电台列表                             | 否       | 是   | 是     |
| [Songkick](https://www.songkick.com/developer/)                                                                  | 音乐活动                                  | `apiKey` | 是   | 未知 |
| [Songlink / Odesli](https://www.notion.so/API-d0ebe08a5e304a55928405eb682f6741)                                  | 获取一首歌可用的所有服务                          | `apiKey` | 是   | 是     |
| [SoundCloud](https://developers.soundcloud.com/docs/api/guide)                                                   | 使用SoundCloud API，您可以构建能更好控制内容的应用程序    | `OAuth`  | 是   | 未知 |
| [Spotify](https://beta.developer.spotify.com/documentation/web-api/)                                             | 查看Spotify音乐目录，管理用户库，获取推荐等             | `OAuth`  | 是   | 未知 |
| [TasteDive](https://tastedive.com/read/api)                                                                      | 相似艺术家API（也适用于电影和电视节目）                 | `apiKey` | 是   | 未知 |
| [TheAudioDB](https://www.theaudiodb.com/api_guide.php)                                                           | 音乐                                    | `apiKey` | 是   | 未知 |
| [Vagalume](https://api.vagalume.com.br/docs/)                                                                    | 众包歌词和音乐知识                             | `apiKey` | 是   | 未知 |

**[⬆ 返回目录](#目录)**



## 新闻

| API                                                                      | 描述                      | 认证Auth         | 支持HTTPS | 跨域CORS    |
|--------------------------------------------------------------------------|----------------------------------|----------|-------|---------|
| [apilayer mediastack](https://mediastack.com/)                           | 用于实时新闻和博客文章的免费简单REST API         | `apiKey` | 是   | 未知 |
| [Associated Press](https://developer.ap.org/)                            | 从美联社搜索新闻和元数据                     | `apiKey` | 是   | 未知 |
| [Chronicling America](http://chroniclingamerica.loc.gov/about/api/)      | 提供访问来自美国国会图书馆的数百万页历史美国报纸         | 否       | 否    | 未知 |
| [Currents](https://currentsapi.services/)                                | 最新新闻发布在各种新闻来源、博客和论坛上             | `apiKey` | 是   | 是     |
| [Feedbin](https://github.com/feedbin/feedbin-api)                        | RSS阅读器                           | `OAuth`  | 是   | 未知 |
| [GNews](https://gnews.io/)                                               | 从各种来源搜索新闻                        | `apiKey` | 是   | 是     |
| [Graphs for Coronavirus](https://corona.dnsforfamily.com/api.txt)        | 每个国家分别和全球范围内的冠状病毒图表。每日更新         | 否       | 是   | 是     |
| [HackerNews Node](https://github.com/EdixonAlberto/api-hackernews-node)  | 获取有关Hacker News中Node.js的相关文章的API | `apiKey` | 是   | 否      |
| [Inshorts News](https://github.com/cyberboysumanjay/Inshorts-News-API)   | 提供来自inshorts的新闻                  | 否       | 是   | 未知 |
| [MarketAux](https://www.marketaux.com/)                                  | 带有标记的股票市场实时新闻+情绪和统计数据的JSON API   | `apiKey` | 是   | 是     |
| [New York Times](https://developer.nytimes.com/)                         | 纽约时报开发者网络                        | `apiKey` | 是   | 未知 |
| [News](https://newsapi.org/)                                             | 目前发布在各种新闻来源和博客上的头条新闻             | `apiKey` | 是   | 未知 |
| [NewsData](https://newsdata.io/docs)                                     | 用于实时突发新闻和来自声誉新闻来源的头条新闻的新闻数据API   | `apiKey` | 是   | 未知 |
| [NewsX](https://rapidapi.com/machaao-inc-machaao-inc-default/api/newsx/) | 使用ML生成摘要获取或搜索最新突发新闻🤖            | `apiKey` | 是   | 未知 |
| [NPR One](http://dev.npr.org/api/)                                       | 个性化的NPR新闻听取体验                    | `OAuth`  | 是   | 未知 |
| [Spaceflight News](https://spaceflightnewsapi.net)                       | 航天相关新闻🚀                         | 否       | 是   | 是     |
| [The Guardian](http://open-platform.theguardian.com/)                    | 访问卫报创建的所有内容，按标签和部分分类             | `apiKey` | 是   | 未知 |
| [The Old Reader](https://github.com/theoldreader/api)                    | RSS阅读器                           | `apiKey` | 是   | 未知 |
| [TheNews](https://www.thenewsapi.com/)                                   | 聚合的头条新闻、头条新闻和实时新闻的JSON API       | `apiKey` | 是   | 是     |
| [Trove](https://trove.nla.gov.au/about/create-something/using-api)       | 搜索澳大利亚国立图书馆的数千份数字化报纸             | `apiKey` | 是   | 未知 |
| [World News](https://worldnewsapi.com)                                   | 搜索数百万份语义标记的全球新闻                  | `apiKey` | 是   | 是     |

**[⬆ 返回目录](#目录)**



## 开放数据

| API                                                                                      | 描述                    | 认证Auth         | 支持HTTPS | 跨域CORS    |
|------------------------------------------------------------------------------------------|--------------------------------|----------|-------|---------|
| [18F](http://18f.github.io/API-All-the-X/)                                               | 非官方的美国联邦政府API开发                | 否       | 否    | 未知 |
| [API Setu](https://www.apisetu.gov.in/)                                                  | 印度政府平台，提供了许多关于KYC、商业、教育和就业的API | 否       | 是   | 是     |
| [Archive.org](https://archive.readme.io/docs)                                            | 互联网档案馆                         | 否       | 是   | 否      |
| [Black History Facts](https://www.blackhistoryapi.io/docs)                               | 在网络上贡献或搜索最大的黑人历史事实数据库之一        | `apiKey` | 是   | 是     |
| [BotsArchive](https://botsarchive.com/docs.html)                                         | JSON格式的Telegram机器人数据库详细信息      | 否       | 是   | 未知 |
| [Callook.info](https://callook.info)                                                     | 美国业余无线电呼号                      | 否       | 是   | 未知 |
| [CARTO](https://carto.com/)                                                              | 位置信息预测                         | `apiKey` | 是   | 未知 |
| [CollegeScoreCard.ed.gov](https://collegescorecard.ed.gov/data/)                         | 美国高等教育机构数据                     | 否       | 是   | 未知 |
| [DataStream](https://github.com/datastreamapp/api-docs)                                  | 用于共享加拿大水质数据的开放访问平台             | `apiKey` | 是   | 是     |
| [Enigma Public](https://developers.enigma.com/docs)                                      | 最广泛的公共数据集合                     | `apiKey` | 是   | 是     |
| [French Address Search](https://geo.api.gouv.fr/adresse)                                 | 通过法国政府进行地址搜索                   | 否       | 是   | 未知 |
| [GENESIS](https://www.destatis.de/EN/Service/OpenData/api-webservice.html)               | 德国联邦统计局                        | `OAuth`  | 是   | 未知 |
| [Joshua Project](https://api.joshuaproject.net/)                                         | 世界上基督教信徒最少的人群                  | `apiKey` | 是   | 未知 |
| [Kaggle](https://www.kaggle.com/docs/api)                                                | 创建和与Kaggle进行数据集、笔记本互动并连接       | `apiKey` | 是   | 未知 |
| [LinkPreview](https://www.linkpreview.net)                                               | 获取任何请求URL的标题、描述和预览图像的JSON格式摘要  | `apiKey` | 是   | 是     |
| [Lowy Asia Power Index](https://github.com/0x0is1/lowy-index-api-docs)                   | 获得衡量资源和影响力以评估亚洲各国相对实力的数据       | 否       | 是   | 未知 |
| [Microlink.io](https://microlink.io)                                                     | 从任何网站提取结构化数据                   | 否       | 是   | 是     |
| [Nasdaq Data Link](https://docs.data.nasdaq.com/)                                        | 股市数据                           | `apiKey` | 是   | 未知 |
| [Nobel Prize](https://www.nobelprize.org/about/developer-zone-2/)                        | 关于诺贝尔奖和活动的开放数据                 | 否       | 是   | 是     |
| [Open Data Minneapolis](https://opendata.minneapolismn.gov/)                             | 明尼阿波利斯的空间（GIS）和非空间城市数据         | 否       | 是   | 否      |
| [openAFRICA](https://africaopendata.org/)                                                | 非洲开放数据的大型数据集存储库                | 否       | 是   | 未知 |
| [OpenCorporates](http://api.opencorporates.com/documentation/API-Reference)              | 许多国家的企业实体和董事数据                 | `apiKey` | 是   | 未知 |
| [OpenSanctions](https://www.opensanctions.org/docs/api/)                                 | 国际制裁、犯罪和具有政治背景的人员数据            | 否       | 是   | 是     |
| [PeakMetrics](https://rapidapi.com/peakmetrics-peakmetrics-default/api/peakmetrics-news) | 新闻文章和公共数据集                     | `apiKey` | 是   | 未知 |
| [Recreation Information Database](https://ridb.recreation.gov/)                          | 娱乐区域、联邦土地、历史遗址、博物馆和其他景点/资源（美国） | `apiKey` | 是   | 未知 |
| [Scoop.it](http://www.scoop.it/dev)                                                      | 内容策展服务                         | `apiKey` | 否    | 未知 |
| [Socrata](https://dev.socrata.com/)                                                      | 访问来自世界各地政府、非营利组织和非政府组织的开放数据    | `OAuth`  | 是   | 是     |
| [Teleport](https://developers.teleport.org/)                                             | 生活质量数据                         | 否       | 是   | 未知 |
| [Umeå Open Data](https://opendata.umea.se/api/)                                          | 瑞典北部城市于默奥的开放数据                 | 否       | 是   | 是     |
| [Universities List](https://github.com/Hipo/university-domains-list)                     | 大学名称、国家和域名                     | 否       | 是   | 未知 |
| [University of Oslo](https://data.uio.no/)                                               | 奥斯陆大学（挪威）的课程、讲座视频、详细信息等        | 否       | 是   | 未知 |
| [UPC database](https://upcdatabase.org/api)                                              | 来自全球各地的超过150万个条形码号码            | `apiKey` | 是   | 未知 |
| [Urban Observatory](https://urbanobservatory.ac.uk)                                      | 英国最大的实时城市数据集合                  | 否       | 否    | 否      |
| [Wikidata](https://www.wikidata.org/w/api.php?action=help)                               | 由维基媒体基金会运营的协作编辑知识库             | `OAuth`  | 是   | 未知 |
| [Wikipedia](https://www.mediawiki.org/wiki/API:Main_page)                                | Mediawiki百科全书                  | 否       | 是   | 未知 |
| [Yelp](https://www.yelp.com/developers/documentation/v3)                                 | 查找本地企业                         | `OAuth`  | 是   | 未知 |

**[⬆ 返回目录](#目录)**



## 开源项目

| API                                                                                                 | 描述                                             | 认证Auth         | 支持HTTPS | 跨域CORS    |
|-----------------------------------------------------------------------------------------------------|--------------------------------------------------------|---------|-------|---------|
| [Countly](https://api.count.ly/reference)                                                           | 一个网站、移动APP、桌面应用程序分析平台 | 否      | 否    | 未知 |
| [Creative Commons Catalog](https://api.creativecommons.engineering/)                                | 在公开授权和公共领域作品中进行搜索                                      | `OAuth` | 是   | 是     |
| [Datamuse](https://www.datamuse.com/api/)                                                           | 单词查询引擎                                                 | 否      | 是   | 未知 |
| [Drupal.org](https://www.drupal.org/drupalorg/docs/api)                                             | 一个开源的内容管理系统（CMS）和框架                                    | 否      | 是   | 未知 |
| [Evil Insult Generator](https://evilinsult.com/api)                                                 | 一个娱乐性质的项目                                              | 否      | 是   | 是     |
| [GitHub Contribution Chart Generator](https://github-contributions.vercel.app)                      | 创建您GitHub贡献的图像                                         | 否      | 是   | 是     |
| [GitHub Profile README Generator](https://github.com/Harman-Sandhu/github-profile-readme-generator) | 为您的GitHub个人资料README生成图像                                | 否      | 是   | 是     |
| [GitHub ReadMe Stats](https://github.com/anuraghazra/github-readme-stats)                           | 向您的GitHub个人资料ReadMe添加动态生成的统计信息                         | 否      | 是   | 是     |
| [Metabase](https://www.metabase.com/)                                                               | 一款开源的商业智能服务器，用于在您的公司内共享数据和分析                           | 否      | 是   | 是     |
| [Shields](https://shields.io/)                                                                      | SVG和光栅格式中简洁、一致和易读的徽章                                   | 否      | 是   | 未知 |

**[⬆ 返回目录](#目录)**



## 专利

| API                                                                           | 描述              | 认证Auth         | 支持HTTPS | 跨域CORS    |
|-------------------------------------------------------------------------------|--------------------------|----------|-------|---------|
| [EPO](https://developers.epo.org/)                                            | 欧洲专利搜索系统API              | `OAuth`  | 是   | 未知 |
| [PatentsView ](https://patentsview.org/apis/purpose)                          | 该API旨在探索和可视化美国创新领域的趋势和模式 | 否       | 是   | 未知 |
| [TIPO](https://tiponet.tipo.gov.tw/Gazette/OpenData/OD/OD05.aspx?QryDS=API00) | 台湾专利搜索系统API              | `apiKey` | 是   | 未知 |
| [USPTO](https://www.uspto.gov/learning-and-resources/open-data-and-mobility)  | 美国专利API服务                | 否       | 是   | 未知 |

**[⬆ 返回目录](#目录)**



## 个性

| API                                                                         | 描述                             | 认证Auth         | 支持HTTPS | 跨域CORS    |
|-----------------------------------------------------------------------------|-----------------------------------------|----------|-------|---------|
| [Advice Slip](http://api.adviceslip.com/)                                   | 生成随机的建议小纸条                              | 否       | 是   | 未知 |
| [Biriyani As A Service](https://biriyani.anoram.com/)                       | 用于占位的比利亚尼饭图片                            | 否       | 是   | 否      |
| [Dev.to](https://developers.forem.com/api)                                  | 通过API访问Forem的文章、用户和其他资源                 | `apiKey` | 是   | 未知 |
| [Dictum](https://github.com/fisenkodv/dictum)                               | API，可获取人类最鼓舞人心的表达的集合                    | 否       | 是   | 未知 |
| [FavQs.com](https://favqs.com/api)                                          | FavQs允许你收集、发现和分享你最喜欢的引用                 | `apiKey` | 是   | 未知 |
| [FOAAS](http://www.foaas.com/)                                              | 一个Fuck Off 即服务的网站                   | 否       | 否    | 未知 |
| [Forismatic](http://forismatic.com/en/api/)                                 | 鼓舞人心的名言                                 | 否       | 否    | 未知 |
| [icanhazdadjoke](https://icanhazdadjoke.com/api)                            | 互联网上最大的笑话集合                           | 否       | 是   | 未知 |
| [Inspiration](https://inspiration.goprogram.ai/docs/)                       | 激励和鼓舞人心的名言                              | 否       | 是   | 是     |
| [kanye.rest](https://kanye.rest)                                            | 随机的Kanye West名言的REST API                | 否       | 是   | 是     |
| [Medium](https://github.com/Medium/medium-api-docs)                         | 一个由读者和作家组成的社区，提供对各种想法的独特视角              | `OAuth`  | 是   | 未知 |
| [Programming Quotes](https://github.com/skolakoda/programming-quotes-api)   | 为开源项目提供编程名言的API                         | 否       | 是   | 未知 |
| [Quotable Quotes](https://github.com/lukePeavey/quotable)                   | Quotable是一个免费的、开源的引用API                 | 否       | 是   | 未知 |
| [Quote Garden](https://pprathameshmore.github.io/QuoteGarden/)              | 超过5000条著名名言的REST API                    | 否       | 是   | 未知 |
| [quoteclear](https://quoteclear.web.app/)                                   | 来自3-2-1 Newsletter的James Clear名言不断增长的列表 | 否       | 是   | 是     |
| [Quotes on Design](https://quotesondesign.com/api/)                         | 鼓舞人心的名言                                 | 否       | 是   | 未知 |
| [Stoicism Quote](https://github.com/tlcheah2/stoic-quote-lambda-public-api) | 关于斯多葛主义的名言                              | 否       | 是   | 未知 |
| [They Said So Quotes](https://theysaidso.com/api/)                          | 被世界上许多财富品牌信赖的名言                         | 否       | 是   | 未知 |
| [Traitify](https://app.traitify.com/developer)                              | 评估、收集和分析个性                              | 否       | 是   | 未知 |
| [Udemy(instructor)](https://www.udemy.com/developers/instructor/)           | Udemy上教师的API                            | `apiKey` | 是   | 未知 |
| [Vadivelu HTTP Codes](https://vadivelu.anoram.com/)                         | 按需提供带有图片的HTTP代码                         | 否       | 是   | 否      |
| [Zen Quotes](https://zenquotes.io/)                                         | 大量的禅宗名言，供你启发                            | 否       | 是   | 是     |

**[⬆ 返回目录](#目录)**


## 电话

| API                                                                           | 描述      | 认证Auth         | 支持HTTPS | 跨域CORS    |
|-------------------------------------------------------------------------------|------------------|----------|-------|---------|
| [Abstract Phone Validation](https://www.abstractapi.com/phone-validation-api) | 全球验证电话号码         | `apiKey` | 是   | 是     |
| [apilayer numverify](https://numverify.com)                                   | 电话号码验证           | `apiKey` | 是   | 未知 |
| [Cloudmersive Validate](https://cloudmersive.com/phone-number-validation-API) | 验证国际电话号码         | `apiKey` | 是   | 是     |
| [NumlookupAPI](https://numlookupapi.com)                                      | 全球电话号码查询和验证API   | `apiKey` | 是   | 是     |
| [Phone Specification](https://github.com/azharimm/phone-specs-api)            | 用于手机规格的Rest Api  | 否       | 是   | 是     |
| [Veriphone](https://veriphone.io)                                             | 电话号码验证和运营商查询     | `apiKey` | 是   | 是     |

**[⬆ 返回目录](#目录)**



## 摄影

| API                                                                       | 描述                  | 认证Auth         | 支持HTTPS | 跨域CORS    |
|---------------------------------------------------------------------------|------------------------------|----------|-------|---------|
| [apilayer screenshotlayer](https://screenshotlayer.com)                   | URL转图片                       | 否       | 是   | 未知 |
| [APITemplate.io](https://apitemplate.io)                                  | 通过简单的API从模板动态生成图像和PDF        | `apiKey` | 是   | 是     |
| [Bruzu](https://docs.bruzu.com)                                           | 使用查询字符串进行图像生成                | `apiKey` | 是   | 是     |
| [CheetahO](https://cheetaho.com/docs/getting-started/)                    | 照片优化和调整大小                    | `apiKey` | 是   | 未知 |
| [Dagpi](https://dagpi.xyz)                                                | 图像操作和处理                      | `apiKey` | 是   | 未知 |
| [Duply](https://duply.co/docs#getting-started-api)                        | 更智能、更快速地生成、编辑、缩放和管理图像和视频     | `apiKey` | 是   | 是     |
| [DynaPictures](https://dynapictures.com/docs/)                            | 在几分钟内生成数百张个性化图像              | `apiKey` | 是   | 是     |
| [Flickr](https://www.flickr.com/services/api/)                            | Flickr服务                     | `OAuth`  | 是   | 未知 |
| [Getty Images](http://developers.gettyimages.com/en/)                     | 利用全球最强大的图像构建应用程序             | `OAuth`  | 是   | 未知 |
| [Gfycat](https://developers.gfycat.com/api/)                              | 更多有趣的GIF图像                   | `OAuth`  | 是   | 未知 |
| [Giphy](https://developers.giphy.com/docs/)                               | 获取所有您的GIF图像                  | `apiKey` | 是   | 未知 |
| [Google Photos](https://developers.google.com/photos)                     | 将Google照片集成到您的应用程序或设备中       | `OAuth`  | 是   | 未知 |
| [Imgur](https://apidocs.imgur.com/)                                       | 图像                           | `OAuth`  | 是   | 未知 |
| [Lorem Picsum](https://picsum.photos/)                                    | 来自Unsplash的图像                | 否       | 是   | 未知 |
| [ObjectCut](https://objectcut.com/)                                       | 图像背景去除                       | `apiKey` | 是   | 是     |
| [Pexels](https://www.pexels.com/api/)                                     | 免费库存照片和视频                    | `apiKey` | 是   | 是     |
| [PhotoRoom](https://www.photoroom.com/api/)                               | 删除图像背景                       | `apiKey` | 是   | 未知 |
| [Pixabay](https://pixabay.com/sk/service/about/api/)                      | 摄影                           | `apiKey` | 是   | 未知 |
| [PlaceKeanu](https://placekeanu.com/)                                     | 可调整大小的基努·里维斯占位图像，具有灰度和年轻基努选项 | 否       | 是   | 未知 |
| [Readme typing SVG](https://github.com/DenverCoder1/readme-typing-svg)    | 可定制的输入和删除文本SVG               | 否       | 是   | 未知 |
| [Remove.bg](https://www.remove.bg/api)                                    | 图像背景去除                       | `apiKey` | 是   | 未知 |
| [ReSmush.it](https://resmush.it/api)                                      | 照片优化                         | 否       | 否    | 未知 |
| [shutterstock](https://api-reference.shutterstock.com/)                   | 库存照片和视频                      | `OAuth`  | 是   | 未知 |
| [Sirv](https://apidocs.sirv.com/)                                         | 优化、操作、托管等图像管理解决方案            | `apiKey` | 是   | 未知 |
| [Unsplash](https://unsplash.com/developers)                               | 摄影                           | `OAuth`  | 是   | 未知 |
| [Wallhaven](https://wallhaven.cc/help/api)                                | 壁纸                           | `apiKey` | 是   | 未知 |
| [Webdam](https://www.damsuccess.com/hc/en-us/articles/202134055-REST-API) | 图像                           | `OAuth`  | 是   | 未知 |

**[⬆ 返回目录](#目录)**


## 播客

| API                                                                                                                                                        | 描述                  | 认证Auth         | 支持HTTPS | 跨域CORS    |
|------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------|-------------|-------|---------|
| [iTunes](https://developer.apple.com/library/archive/documentation/AudioVideo/Conceptual/iTuneSearchAPI/index.html#//apple_ref/doc/uid/TP40017632-CH3-SW1) | 苹果播客目录                      | 否          | 是   | 未知 |
| [PodcastIndex](https://podcastindex-org.github.io/docs-api/)                                                                                               | 获取播客和剧集详情，播客搜索              | `apiKey`    | 是   | 未知 |
| [Spotify](https://developer.spotify.com/documentation/web-api/)                                                                                            | 获取播客和剧集详情                   | `OAuth`     | 是   | 未知 |
| [Taddy Podcasts](https://taddy.org/developers/podcast-api)                                                                                                 | 获取播客和剧集详情，播客和剧集搜索，Webhook通知 | `X-API-KEY` | 是   | 是     |

**[⬆ 返回目录](#目录)**



## 编程

| API                                                                 | 描述            | 认证Auth         | 支持HTTPS | 跨域CORS    |
|---------------------------------------------------------------------|------------------------|----------|-------|---------|
| [Codeforces](https://codeforces.com/apiHelp)                        | 获取 Codeforces 数据的访问权限  | `apiKey` | 是   | 未知 |
| [Hackerearth](https://www.hackerearth.com/docs/wiki/developers/v4/) | 用于编译和运行多种编程语言的代码       | `apiKey` | 是   | 未知 |
| [Judge0 CE](https://ce.judge0.com/)                                 | 在线代码执行系统               | `apiKey` | 是   | 未知 |
| [KONTESTS](https://kontests.net/api)                                | 提供即将到来和正在进行的竞技编程比赛信息   | 否       | 是   | 未知 |
| [Volca](https://volca.io#api)                                       | 编程语言和技术列表              | 否       | 是   | 未知 |

**[⬆ 返回目录](#目录)**


## 科学数学

| API                                                                            | 描述                | 认证Auth         | 支持HTTPS | 跨域CORS    |
|--------------------------------------------------------------------------------|----------------------------|----------|-------|---------|
| [arcsecond.io](https://api.arcsecond.io/)                                      | 多个天文数据源                    | 否       | 是   | 未知 |
| [arXiv](https://arxiv.org/help/api/user-manual)                                | 精选的研究分享平台：物理学、数学、量化金融和经济学  | 否       | 是   | 未知 |
| [CORE](https://core.ac.uk/services#api)                                        | 访问世界上的开放获取研究论文             | `apiKey` | 是   | 未知 |
| [GBIF](https://www.gbif.org/developer/summary)                                 | 全球生物多样性信息设施                | 否       | 是   | 是     |
| [iDigBio](https://github.com/idigbio/idigbio-search-api/wiki)                  | 访问来自世界各地组织的数百万件博物馆标本       | 否       | 是   | 未知 |
| [inspirehep.net](https://github.com/inspirehep/rest-api-doc)                   | 高能物理信息系统                   | 否       | 是   | 未知 |
| [isEven (humor)](https://isevenapi.xyz/)                                       | 检查一个数字是否为偶数                | 否       | 是   | 未知 |
| [ISRO](https://isro.vercel.app)                                                | ISRO航天器信息                  | 否       | 是   | 否      |
| [ISRO Statistics](https://isrostats.in/apis)                                   | ISRO发射和航天器详细信息             | 否       | 是   | 是     |
| [ITIS](https://www.itis.gov/ws_description.html)                               | 综合分类信息系统                   | 否       | 是   | 未知 |
| [Launch Library 2](https://thespacedevs.com/llapi)                             | 航天发射和事件数据库                 | 否       | 是   | 是     |
| [Materials Platform for Data Science](https://mpds.io)                         | 材料科学的精选实验数据                | `apiKey` | 是   | 否      |
| [Minor Planet Center](http://www.asterank.com/mpc)                             | Asterank.com信息             | 否       | 否    | 未知 |
| [NASA](https://api.nasa.gov)                                                   | 包括图像在内的NASA数据              | 否       | 是   | 否      |
| [NASA ADS](https://ui.adsabs.harvard.edu/help/api/api-docs.html)               | NASA天体物理数据系统               | `OAuth`  | 是   | 是     |
| [Newton](https://newton.vercel.app)                                            | 符号和算术数学计算器                 | 否       | 是   | 否      |
| [Noctua](https://api.noctuasky.com/api/v1/swaggerdoc/)                         | 用于访问NoctuaSky功能的REST API   | 否       | 是   | 未知 |
| [Numbers](https://math.tools/api/numbers/)                                     | 每日数字、随机数字、数字事实以及您想要进行的其他操作 | `apiKey` | 是   | 否      |
| [Numbers](http://numbersapi.com)                                               | 有关数字的事实                    | 否       | 否    | 否      |
| [Open Notify](http://open-notify.org/Open-Notify-API/)                         | 国际空间站宇航员、当前位置等             | 否       | 否    | 否      |
| [Open Science Framework](https://developer.osf.io)                             | 研究设计、研究材料、数据、手稿等的存储库和档案    | 否       | 是   | 未知 |
| [Prime Number](https://prime-number-api-docs.onrender.com/)                    | 检查一个或多个数字是否为质数，或查询质数列表     | 否       | 是   | 是     |
| [Purple Air](https://www2.purpleair.com/)                                      | 实时空气质量监测                   | 否       | 是   | 未知 |
| [Remote Calc](https://github.com/elizabethadegbaju/remotecalc)                 | 解码base64编码并将其解析为JSON中的计算结果 | 否       | 是   | 是     |
| [SHARE](https://share.osf.io/api/v2/)                                          | 关于研究和学术活动的免费、开放数据集         | 否       | 是   | 否      |
| [SpaceX](https://github.com/r-spacex/SpaceX-API)                               | 公司、车辆、发射台和发射数据             | 否       | 是   | 否      |
| [SpaceX](https://api.spacex.land/graphql/)                                     | GraphQL、公司、船只、发射台和发射数据     | 否       | 是   | 未知 |
| [Sunrise and Sunset](https://sunrise-sunset.org/api)                           | 给定纬度和经度的日落和日出时间            | 否       | 是   | 否      |
| [Times Adder](https://github.com/FranP-code/API-Times-Adder)                   | 使用此API，您可以添加数组中输入的每个时间     | 否       | 是   | 否      |
| [TLE](https://tle.ivanstanojevic.me/#/docs)                                    | 卫星信息                       | 否       | 是   | 否      |
| [USGS Earthquake Hazards Program](https://earthquake.usgs.gov/fdsnws/event/1/) | 实时地震数据                     | 否       | 是   | 否      |
| [USGS Water Services](https://waterservices.usgs.gov/)                         | 河流和湖泊的水质和水位信息              | 否       | 是   | 否      |
| [World Bank](https://datahelpdesk.worldbank.org/knowledgebase/topics/125589)   | 世界数据                       | 否       | 是   | 否      |

**[⬆ 返回目录](#目录)**


## 安全

| API                                                                                                 | 描述                              | 认证Auth         | 支持HTTPS | 跨域CORS    |
|-----------------------------------------------------------------------------------------------------|------------------------------------------|----------|-------|---------|
| [Application Environment Verification](https://github.com/fingerprintjs/aev)                        | Android库和API，用于验证用户设备的安全性，检测已root设备和其他风险 | `apiKey` | 是   | 是     |
| [BinaryEdge](https://docs.binaryedge.io/api-v2.html)                                                | 提供对BinaryEdge 40fy扫描平台的访问                | `apiKey` | 是   | 是     |
| [BitWarden](https://bitwarden.com/help/api/)                                                        | 最佳开源密码管理器                                | `OAuth`  | 是   | 未知 |
| [Botd](https://github.com/fingerprintjs/botd)                                                       | Botd是用于JavaScript机器人检测的浏览器库              | `apiKey` | 是   | 是     |
| [Bugcrowd](https://docs.bugcrowd.com/api/getting-started/)                                          | Bugcrowd API，用于以编程方式交互和跟踪报告的问题           | `apiKey` | 是   | 未知 |
| [Censys](https://search.censys.io/api)                                                              | 用于搜索与Internet连接的主机和设备的搜索引擎               | `apiKey` | 是   | 否      |
| [Classify](https://github.com/cheatsnake/classify)                                                  | 加密和解密文本消息                                | 否       | 是   | 是     |
| [Complete Criminal Checks](https://completecriminalchecks.com/Developers)                           | 提供来自美国各州和波多黎各的罪犯数据                       | `apiKey` | 是   | 是     |
| [CRXcavator](https://crxcavator.io/apidocs)                                                         | Chrome扩展风险评分                             | `apiKey` | 是   | 未知 |
| [Dehash.lt](https://github.com/Dehash-lt/api)                                                       | 哈希解密MD5、SHA1、SHA3、SHA256、SHA384、SHA512   | 否       | 是   | 未知 |
| [EmailRep](https://docs.emailrep.io/)                                                               | 电子邮件地址威胁和风险预测                            | 否       | 是   | 未知 |
| [Escape](https://github.com/polarspetroll/EscapeAPI)                                                | 用于转义不同类型查询的API                           | 否       | 是   | 否      |
| [FilterLists](https://filterlists.com)                                                              | 广告拦截器和防火墙的过滤器列表                          | 否       | 是   | 未知 |
| [FingerprintJS Pro](https://dev.fingerprintjs.com/docs)                                             | 欺诈检测API，提供高度准确的浏览器指纹识别                   | `apiKey` | 是   | 是     |
| [FraudLabs Pro](https://www.fraudlabspro.com/developer/api/screen-order)                            | 使用AI检测欺诈的屏幕订单信息                          | `apiKey` | 是   | 未知 |
| [FullHunt](https://api-docs.fullhunt.io/#introduction)                                              | 可搜索整个互联网攻击面数据库                           | `apiKey` | 是   | 未知 |
| [GitGuardian](https://api.gitguardian.com/doc)                                                      | 扫描文件以查找机密信息（API密钥、数据库凭据）                 | `apiKey` | 是   | 否      |
| [GreyNoise](https://docs.greynoise.io/reference/get_v3-community-ip)                                | 查询GreyNoise数据集中的IP，并检索完整IP上下文数据的子集       | `apiKey` | 是   | 未知 |
| [HackerOne](https://api.hackerone.com/)                                                             | 行业首个黑客API，有助于提高创造性的赏金猎人工作效率              | `apiKey` | 是   | 未知 |
| [Hashable](https://hashable.space/pages/api/)                                                       | REST API，用于访问高级密码功能和方法                   | 否       | 是   | 是     |
| [HaveIBeenPwned](https://haveibeenpwned.com/API/v3)                                                 | 曾经在数据泄露中曝光的密码                            | `apiKey` | 是   | 未知 |
| [Intelligence X](https://github.com/IntelligenceX/SDK/blob/master/Intelligence%20X%20API.pdf)       | 通过Intelligence X执行OSINT                  | `apiKey` | 是   | 未知 |
| [LoginRadius](https://www.loginradius.com/docs/)                                                    | 托管用户身份验证服务                               | `apiKey` | 是   | 是     |
| [Microsoft Security Response Center (MSRC)](https://msrc.microsoft.com/report/developer)            | 用于与Microsoft安全响应中心（MSRC）进行交互的编程接口        | 否       | 是   | 未知 |
| [Mozilla http scanner](https://github.com/mozilla/http-observatory/blob/master/httpobs/docs/api.md) | Mozilla observatory http扫描器              | 否       | 是   | 未知 |
| [Mozilla tls scanner](https://github.com/mozilla/tls-observatory#api-endpoints)                     | Mozilla observatory tls扫描器               | 否       | 是   | 未知 |
| [National Vulnerability Database](https://nvd.nist.gov/vuln/Data-Feeds/JSON-feed-changelog)         | 美国国家漏洞数据库                                | 否       | 是   | 未知 |
| [OWASP ZAP](https://www.zaproxy.org/docs/api/)                                                      | 用于Web应用程序的自动化安全测试API                     | 否       | 是   | 未知 |
| [Passwordinator](https://github.com/fawazsullia/password-generator/)                                | 生成不同复杂度的随机密码                             | 否       | 是   | 是     |
| [PhishStats](https://phishstats.info/)                                                              | 钓鱼数据库                                    | 否       | 是   | 未知 |
| [Privacy.com](https://privacy.com/developer/docs)                                                   | 生成特定商户和一次性使用的信用卡号码，链接到您的银行               | `apiKey` | 是   | 未知 |
| [Pulsedive](https://pulsedive.com/api/)                                                             | 实时扫描、搜索和收集威胁情报数据                         | `apiKey` | 是   | 未知 |
| [SecurityTrails](https://securitytrails.com/corp/apidocs)                                           | 与域名和IP相关的信息，如当前和历史WHOIS和DNS记录            | `apiKey` | 是   | 未知 |
| [Shodan](https://developer.shodan.io/)                                                              | 用于与Internet连接设备的搜索引擎                     | `apiKey` | 是   | 未知 |
| [Spyse](https://spyse-dev.readme.io/reference/quick-start)                                          | 访问所有Internet资产的数据，并构建强大的攻击面管理应用程序        | `apiKey` | 是   | 未知 |
| [Threat Jammer](https://threatjammer.com/docs/index)                                                | 从精选威胁情报数据中进行风险评分服务                       | `apiKey` | 是   | 未知 |
| [UK Police](https://data.police.uk/docs/)                                                           | 英国警方数据                                   | 否       | 是   | 未知 |
| [Virushee](https://api.virushee.com/)                                                               | Virushee文件/数据扫描                          | 否       | 是   | 是     |
| [VulDB](https://vuldb.com/?doc.api)                                                                 | VulDB API允许发起查询一个或多个项目，以及事务性机器人          | `apiKey` | 是   | 未知 |

**[⬆ 返回目录](#目录)**



## 购物
| API                                                                              | 描述                                              | 认证Auth         | 支持HTTPS | 跨域CORS    |
|----------------------------------------------------------------------------------|----------------------------------------------------------|----------|-------|---------|
| [Best Buy](https://bestbuyapis.github.io/api-documentation/#overview)            | 产品、购买选项、类别、推荐、商店和商业                                      | `apiKey` | 是   | 未知 |
| [Digi-Key](https://www.digikey.com/en/resources/api-solutions)                   | 检索电子元件的价格和库存，以及下订单                                       | `OAuth`  | 是   | 未知 |
| [eBay](https://developer.ebay.com/)                                              | 在eBay上买卖                                                 | `OAuth`  | 是   | 未知 |
| [Etsy](https://www.etsy.com/developers/documentation/getting_started/api_basics) | 管理商店和与列表互动                                               | `OAuth`  | 是   | 未知 |
| [Flipkart Marketplace](https://seller.flipkart.com/api-docs/FMSAPI.html)         | Flipkart市场中的产品列表管理、订单履行                                  | `OAuth`  | 是   | 是     |
| [Lazada](https://open.lazada.com/doc/doc.htm)                                    | 检索产品评分和卖家绩效指标                                            | `apiKey` | 是   | 未知 |
| [Mercadolibre](https://developers.mercadolibre.cl/es_ar/api-docs-es)             | 管理销售、广告、产品、服务和商店                                         | `apiKey` | 是   | 未知 |
| [Octopart](https://octopart.com/api/v4/reference)                                | 用于制造、设计和采购的电子零件数据                                        | `apiKey` | 是   | 未知 |
| [OLX Poland](https://developer.olx.pl/api/doc#section/)                          | 通过发布、管理广告和与OLX用户沟通，与本地网站集成                               | `apiKey` | 是   | 未知 |
| [Rappi](https://dev-portal.rappi.com/)                                           | 管理来自Rappi应用的订单                                           | `OAuth`  | 是   | 未知 |
| [Shopee](https://open.shopee.com/documents?version=1)                            | Shopee的官方API，用于集成Shopee的各种服务                             | `apiKey` | 是   | 未知 |
| [Tokopedia](https://developer.tokopedia.com/openapi/guide/#/)                    | Tokopedia的官方API，用于集成Tokopedia的各种服务                       | `OAuth`  | 是   | 未知 |
| [WooCommerce](https://woocommerce.github.io/woocommerce-rest-api-docs/)          | WooCommerce REST API，用于以JSON格式在wordpress网站上创建、读取、更新和删除数据 | `apiKey` | 是   | 是     |

**[⬆ 返回目录](#目录)**


## 社交
| API                                                                             | 描述                                | 认证Auth         | 支持HTTPS | 跨域CORS    |
|---------------------------------------------------------------------------------|--------------------------------------------|----------|-------|---------|
| [4chan](https://github.com/4chan/4chan-API)                                     | 一个基于图片的留言板，涵盖各种主题                          | 否       | 是   | 是     |
| [Ayrshare](https://www.ayrshare.com)                                            | 社交媒体API，用于发布、获取分析数据，以及管理多个用户的社交媒体账户        | `apiKey` | 是   | 是     |
| [aztro](https://aztro.sameerkumar.website/)                                     | 昨天、今天和明天的每日星座运势信息                          | 否       | 是   | 未知 |
| [Blogger](https://developers.google.com/blogger/)                               | Blogger API允许客户端应用查看和更新Blogger内容           | `OAuth`  | 是   | 未知 |
| [Discord](https://discord.com/developers/docs/intro)                            | 为Discord制作机器人，将Discord集成到外部平台              | `OAuth`  | 是   | 未知 |
| [Disqus](https://disqus.com/api/docs/auth/)                                     | 与Disqus数据进行通信                              | `OAuth`  | 是   | 未知 |
| [Facebook](https://developers.facebook.com/)                                    | Facebook登录、分享到FB、社交插件、分析等                  | `OAuth`  | 是   | 未知 |
| [Foursquare](https://developer.foursquare.com/)                                 | 与Foursquare用户和地点进行交互（基于地理位置的签到、照片、提示、事件等）  | `OAuth`  | 是   | 未知 |
| [Full Contact](https://docs.fullcontact.com/)                                   | 获取社交媒体资料和联系信息                              | `OAuth`  | 是   | 未知 |
| [HackerNews](https://github.com/HackerNews/API)                                 | 计算机科学和创业的社交新闻                              | 否       | 是   | 未知 |
| [Hashnode](https://hashnode.com)                                                | 为开发者打造的博客平台                                | 否       | 是   | 未知 |
| [Hashtag](https://mukeshsolanki.gitbook.io/hashtag-api/)                        | 使用关键词或图片生成话题标签                             | `apiKey` | 是   | 未知 |
| [Instagram](https://www.instagram.com/developer/)                               | Instagram登录、分享到Instagram、社交插件等             | `OAuth`  | 是   | 未知 |
| [Kakao](https://developers.kakao.com/)                                          | Kakao登录、分享到KakaoTalk、社交插件等                 | `OAuth`  | 是   | 未知 |
| [Lanyard](https://github.com/Phineas/lanyard)                                   | 通过HTTP REST API或WebSocket检索你在Discord上的状态   | 否       | 是   | 是     |
| [Line](https://developers.line.biz/)                                            | Line登录、分享到Line、社交插件等                       | `OAuth`  | 是   | 未知 |
| [LinkedIn](https://docs.microsoft.com/en-us/linkedin/?context=linkedin/context) | 与LinkedIn的所有数字集成的基础                        | `OAuth`  | 是   | 未知 |
| [Meetup.com](https://www.meetup.com/api/guide)                                  | 来自Meetup.com的Meetup数据                      | `apiKey` | 是   | 未知 |
| [Microsoft Graph](https://docs.microsoft.com/en-us/graph/api/overview)          | 访问Microsoft 365, Windows 10, 和企业移动性中的数据和智能 | `OAuth`  | 是   | 未知 |
| [NAVER](https://developers.naver.com/main/)                                     | NAVER登录、分享到NAVER、社交插件等                     | `OAuth`  | 是   | 未知 |
| [Open Collective](https://docs.opencollective.com/help/developers/api)          | 获取Open Collective数据                        | 否       | 是   | 未知 |
| [Pinterest](https://developers.pinterest.com/)                                  | 全球创意目录                                     | `OAuth`  | 是   | 未知 |
| [Product Hunt](https://api.producthunt.com/v2/docs)                             | 科技领域最好的新产品                                 | `OAuth`  | 是   | 未知 |
| [Reddit](https://www.reddit.com/dev/api)                                        | 互联网的主页                                     | `OAuth`  | 是   | 未知 |
| [Revolt](https://developers.revolt.chat/api/)                                   | 开源的Discord替代品Revolt                        | `apiKey` | 是   | 未知 |
| [Saidit](https://www.saidit.net/dev/api)                                        | 开源的Reddit克隆版                               | `OAuth`  | 是   | 未知 |
| [SocialData API](https://socialdata.tools)                                      | 💰读Twitter数据                                | `apiKey`  | 是   | 否      |
| [Slack](https://api.slack.com/)                                                 | 团队即时通讯软件                                   | `OAuth`  | 是   | 未知 |
| [TamTam](https://dev.tamtam.chat/)                                              | 与TamTam进行交互的机器人API                         | `apiKey` | 是   | 未知 |
| [Telegram Bot](https://core.telegram.org/bots/api)                              | 用于机器人的MTProto API的简化HTTP版本                 | `apiKey` | 是   | 未知 |
| [Telegram MTProto](https://core.telegram.org/api#getting-started)               | 读写Telegram数据                               | `OAuth`  | 是   | 未知 |
| [Telegraph](https://telegraph.org/api)                                          | 轻松创建有吸引力的博客，进行分享 [其他域名 - graph.org]        | `apiKey` | 是   | 未知 |
| [TikTok](https://developers.tiktok.com/doc/login-kit-web)                       | 获取TikTok平台上的用户信息和用户视频帖子                    | `OAuth`  | 是   | 未知 |
| [Trash Nothing](https://trashnothing.com/developer)                             | 一个免费循环社区，每天有数千件免费物品发布                      | `OAuth`  | 是   | 是     |
| [Tumblr](https://www.tumblr.com/docs/en/api/v2)                                 | 读写Tumblr数据                                 | `OAuth`  | 是   | 未知 |
| [Twitch](https://dev.twitch.tv/docs)                                            | 游戏流媒体API                                   | `OAuth`  | 是   | 未知 |
| [Twitter](https://developer.twitter.com/en/docs)                                | 读写Twitter数据                                | `OAuth`  | 是   | 否      |
| [vk](https://vk.com/dev/sites)                                                  | 读写vk数据                                     | `OAuth`  | 是   | 未知 |
| [Webex](https://developer.webex.com)                                            | 团队协作软件                                     | `OAuth`  | 是   | 是     |

**[⬆ 返回目录](#目录)**



## 体育健身

| API                                                                                         | 描述                                | 认证Auth         | 支持HTTPS | 跨域CORS    |
|---------------------------------------------------------------------------------------------|-------------------------------------------|-----------------|-------|---------|
| [API-FOOTBALL](https://www.api-football.com/documentation-v3)                               | 获取足球联赛和杯赛的信息                              | `apiKey`        | 是   | 是     |
| [ApiMedic](https://apimedic.com/)                                                           | ApiMedic提供主要面向患者的医学症状检查API                | `apiKey`        | 是   | 未知 |
| [balldontlie](https://www.balldontlie.io)                                                   | Balldontlie提供NBA的统计数据访问                   | 否              | 是   | 是     |
| [Canadian Football League (CFL)](http://api.cfl.ca/)                                        | 官方JSON API提供有关CFL的实时联赛、球队和球员统计数据          | `apiKey`        | 是   | 否      |
| [City Bikes](https://api.citybik.es/v2/)                                                    | 全球城市自行车信息                                 | 否              | 是   | 未知 |
| [Cloudbet](https://www.cloudbet.com/api/)                                                   | 官方Cloudbet API提供实时体育赔率和投注API，可通过程序化方式下注   | `apiKey`        | 是   | 是     |
| [CollegeFootballData.com](https://collegefootballdata.com)                                  | 非官方的美式大学橄榄球统计、记录和结果API                    | `apiKey`        | 是   | 未知 |
| [Ergast F1](http://ergast.com/mrd/)                                                         | 从1950年世界锦标赛开始的F1数据                        | 否              | 是   | 未知 |
| [Fitbit](https://dev.fitbit.com/)                                                           | 提供Fitbit相关产品和服务的网站                                  | `OAuth`         | 是   | 未知 |
| [Football](https://rapidapi.com/GiulianoCrescimbeni/api/football98/)                        | 一个简单的开源足球API，用于获取球队的统计数据、最佳射手等            | `X-Mashape-Key` | 是   | 未知 |
| [Football (Soccer) Videos](https://www.scorebat.com/video-api/)                             | Premier League、德甲、意甲等比赛的进球和精彩镜头嵌入代码       | 否              | 是   | 是     |
| [Football Standings](https://github.com/azharimm/football-standings-api)                    | 显示足球积分榜，如英超、西甲、意甲等。数据基于espn网站             | 否              | 是   | 是     |
| [Football-Data](https://www.football-data.org)                                              | 包含比赛信息、球员、球队和比赛的足球数据                      | `X-Mashape-Key` | 是   | 未知 |
| [JCDecaux Bike](https://developer.jcdecaux.com/)                                            | JCDecaux的共享自行车                            | `apiKey`        | 是   | 未知 |
| [MLB Records and Stats](https://appac.github.io/mlb-data-api-docs/)                         | 当前和历史的MLB统计数据                             | 否              | 否    | 未知 |
| [NBA Data](https://rapidapi.com/api-sports/api/api-nba/)                                    | 所有NBA统计数据、比赛、即时比分、排名、统计数据                 | `apiKey`        | 是   | 未知 |
| [NBA Stats](https://any-api.com/nba_com/nba_com/docs/API_Description)                       | 当前和历史的NBA统计数据                             | 否              | 是   | 未知 |
| [NBA Stats](https://documenter.getpostman.com/view/24232555/2s93shzpR3)                     | NBA球员统计数据和数据                              | 否              | 是   | 是     |
| [NHL Records and Stats](https://gitlab.com/dword4/nhlapi)                                   | NHL历史数据和统计数据                              | 否              | 是   | 未知 |
| [Oddsmagnet](https://data.oddsmagnet.com)                                                   | 来自多家英国书店的赔率历史数据                           | 否              | 是   | 是     |
| [OpenLigaDB](https://www.openligadb.de)                                                     | 众包的体育联赛结果                                 | 否              | 是   | 是     |
| [Premier League Standings ](https://rapidapi.com/heisenbug/api/premier-league-live-scores/) | 所有当前英超的积分榜和统计数据                           | `apiKey`        | 是   | 未知 |
| [Sport Data](https://sportdataapi.com)                                                      | 获取来自世界各地的体育数据                             | `apiKey`        | 是   | 未知 |
| [Sport List & Data](https://developers.decathlon.com/products/sports)                       | 与体育相关的列表和资源                               | 否              | 是   | 是     |
| [Sport Places](https://developers.decathlon.com/products/sport-places)                      | 全球范围内的众包体育场所                              | 否              | 是   | 否      |
| [Sport Vision](https://developers.decathlon.com/products/sport-vision)                      | 识别图像中的运动、品牌和装备，还可进行图像体育标题生成               | `apiKey`        | 是   | 是     |
| [Sportmonks Cricket](https://docs.sportmonks.com/cricket/)                                  | 现场板球比分、球员统计和虚拟API                         | `apiKey`        | 是   | 未知 |
| [Sportmonks Football](https://docs.sportmonks.com/football/)                                | 足球比分/赛程、新闻API、电视频道、统计数据、历史记录，显示积分榜，如英超、西甲 | `apiKey`        | 是   | 未知 |
| [Squiggle](https://api.squiggle.com.au)                                                     | 澳大利亚橄榄球联盟比赛的赛程、结果和预测                      | 否              | 是   | 是     |
| [Strava](https://strava.github.io/api/)                                                     | 与运动员、活动等建立联系                              | `OAuth`         | 是   | 未知 |
| [SuredBits](https://suredbits.com/api/)                                                     | 查询体育数据，包括球队、球员、比赛、比分和统计数据                 | 否              | 否    | 否      |
| [TheSportsDB](https://www.thesportsdb.com/api.php)                                          | 众包的体育数据和艺术品                               | `apiKey`        | 是   | 是     |
| [Tredict](https://www.tredict.com/blog/oauth_docs/)                                         | 获取和设置活动、健康数据等                             | `OAuth`         | 是   | 未知 |
| [Wger](https://wger.de/en/software/api)                                                     | 锻炼管理器数据，包括练习、肌肉和设备。                       | `apiKey`        | 是   | 未知 |

**[⬆ 返回目录](#目录)**

## 模拟数据

| API                                                                              | 描述                    | 认证Auth         | 支持HTTPS | 跨域CORS    |
|----------------------------------------------------------------------------------|--------------------------------|----------|-------|---------|
| [Bacon Ipsum](https://baconipsum.com/json-api/)                                  | 生成更多内容的Lorem Ipsum模拟填充文字           | 否       | 是   | 未知 |
| [Dicebear Avatars](https://avatars.dicebear.com/)                                | 生成随机的像素艺术头像                    | 否       | 是   | 否      |
| [English Random Words](https://random-words-api.vercel.app/word)                 | 生成带有发音的英语随机单词                  | 否       | 是   | 否      |
| [FakeJSON](https://fakejson.com)                                                 | 生成测试和虚假数据的服务                   | `apiKey` | 是   | 是     |
| [FakerAPI](https://fakerapi.it/en)                                               | 获取虚假数据的API集合                   | 否       | 是   | 是     |
| [FakeStoreAPI](https://fakestoreapi.com/)                                        | 用于电子商务或购物网站原型的虚假商店REST API     | 否       | 是   | 未知 |
| [GeneradorDNI](https://api.generadordni.es)                                      | 数据生成器API。包括配置文件、车辆、银行和卡等       | `apiKey` | 是   | 未知 |
| [ItsThisForThat](https://itsthisforthat.com/api.php)                             | 生成随机的创业点子                      | 否       | 是   | 否      |
| [JSONPlaceholder](http://jsonplaceholder.typicode.com/)                          | 用于测试和原型设计的虚假数据                 | 否       | 否    | 未知 |
| [Loripsum](http://loripsum.net/)                                                 | 不会让人讨厌的“lorem ipsum”生成器        | 否       | 否    | 未知 |
| [Mailsac](https://mailsac.com/docs/api)                                          | 一次性电子邮件                        | `apiKey` | 是   | 未知 |
| [Metaphorsum](http://metaphorpsum.com/)                                          | 根据单词和句子数量生成示例段落                | 否       | 否    | 未知 |
| [Mockaroo](https://www.mockaroo.com/docs)                                        | 生成JSON、CSV、TXT、SQL和XML格式的虚假数据  | `apiKey` | 是   | 未知 |
| [Mockyard](https://mockyard.in/)                                                 | 用于测试和原型设计的逼真模拟数据               | 否       | 是   | 是     |
| [QuickMocker](https://quickmocker.com)                                           | API模拟工具，用于生成上下文、虚假或随机数据        | 否       | 是   | 是     |
| [Random Data](https://random-data-api.com)                                       | 随机数据生成器                        | 否       | 是   | 未知 |
| [Random Identity](https://rapidapi.com/edualc1018/api/random-identity-generator) | 具有自定义响应格式的随机身份生成器              | `apiKey` | 是   | 是     |
| [Randommer](https://randommer.io/randommer-api)                                  | 随机数据生成器                        | `apiKey` | 是   | 是     |
| [RandomUser](https://randomuser.me)                                              | 生成并列出用户数据                      | 否       | 是   | 未知 |
| [RoboHash](https://robohash.org/)                                                | 生成随机的机器人/外星人头像                 | 否       | 是   | 未知 |
| [This Person Does not Exist](https://thispersondoesnotexist.com)                 | 生成不存在的真实人脸                     | 否       | 是   | 未知 |
| [UUID Generator](https://www.uuidtools.com/docs)                                 | 生成UUID                         | 否       | 是   | 否      |
| [What The Commit](http://whatthecommit.com/index.txt)                            | 随机提交消息生成器                      | 否       | 否    | 是     |
| [Yes No](https://yesno.wtf/api)                                                  | 随机生成是或否的答案                     | 否       | 是   | 未知 |

**[⬆ 返回目录](#目录)**


## 文本分析
| API                                                                                                                                  | 描述               | 认证Auth         | 支持HTTPS | 跨域CORS    |
|--------------------------------------------------------------------------------------------------------------------------------------|---------------------------|----------|-------|---------|
| [apilayer languagelayer](https://languagelayer.com/)                                                                                 | 支持173种语言的语言检测JSON API     | `OAuth`  | 是   | 未知 |
| [Aylien Text Analysis](https://docs.aylien.com/textapi/#getting-started)                                                             | 信息检索和自然语言处理API集合          | `apiKey` | 是   | 未知 |
| [Cloudmersive Natural Language Processing](https://www.cloudmersive.com/nlp-api)                                                     | 自然语言处理和文本分析               | `apiKey` | 是   | 是     |
| [Code Detection API](https://codedetectionapi.runtime.dev)                                                                           | 检测、标记、格式化和增强应用程序或数据流中的代码  | `OAuth`  | 是   | 未知 |
| [Detect Language](https://detectlanguage.com/)                                                                                       | 检测文本语言                    | `apiKey` | 是   | 未知 |
| [ELI](https://nlp.insightera.co.th/docs/v1.0)                                                                                        | 用于泰语的自然语言处理工具             | `apiKey` | 是   | 未知 |
| [Google Cloud Natural](https://cloud.google.com/natural-language/docs/)                                                              | 自然语言理解技术，包括情感、实体和句法分析     | `apiKey` | 是   | 未知 |
| [LanguageTool](https://languagetool.org/http-api/)                                                                                   | 适用于25种以上语言的样式和语法检查器       | 否       | 是   | 未知 |
| [Lecto Translation](https://rapidapi.com/lecto-lecto-default/api/lecto-translation/)                                                 | 具有免费套餐和合理价格的翻译API         | `apiKey` | 是   | 是     |
| [LibreTranslate](https://libretranslate.com/docs)                                                                                    | 支持17种语言的翻译工具              | 否       | 是   | 未知 |
| [Semantria](https://semantria.readme.io/docs)                                                                                        | 带有情感分析、分类和命名实体提取的文本分析     | `OAuth`  | 是   | 未知 |
| [Sentiment Analysis](https://www.meaningcloud.com/developer/sentiment-analysis)                                                      | 对来自不同来源的文本进行多语言情感分析       | `apiKey` | 是   | 是     |
| [Tisane](https://tisane.ai/)                                                                                                         | 重点检测滥用内容和执法应用的文本分析        | `OAuth`  | 是   | 是     |
| [Watson Natural Language Understanding](https://cloud.ibm.com/apidocs/natural-language-understanding/natural-language-understanding) | 用于高级文本分析的自然语言处理           | `OAuth`  | 是   | 未知 |

**[⬆ 返回目录](#目录)**

## 运输

| API                                                                                                                                       | 描述                | 认证Auth         | 支持HTTPS | 跨域CORS    |
|-------------------------------------------------------------------------------------------------------------------------------------------|----------------------------|----------|-------|---------|
| [ADS-B Exchange](https://www.adsbexchange.com/data/)                                                                                      | 访问任何空中飞机的实时和历史数据           | 否       | 是   | 未知 |
| [airportsapi](https://airport-web.appspot.com/api/docs/)                                                                                  | 通过ICAO代码获取机场名称和网站URL       | 否       | 是   | 未知 |
| [AIS Hub](http://www.aishub.net/api)                                                                                                      | 任何配备AIS跟踪系统的海洋和内陆船舶的实时数据   | `apiKey` | 否    | 未知 |
| [Amadeus for Developers](https://developers.amadeus.com/self-service)                                                                     | 旅行搜索-有限使用                  | `OAuth`  | 是   | 未知 |
| [apilayer aviationstack](https://aviationstack.com/)                                                                                      | 实时航班状态和全球航空数据API           | `OAuth`  | 是   | 未知 |
| [AviationAPI](https://docs.aviationapi.com)                                                                                               | FAA航空图表和出版物、机场信息和机场天气      | 否       | 是   | 否      |
| [AZ511](https://www.az511.com/developers/doc)                                                                                             | 访问来自ADOT API的交通数据          | `apiKey` | 是   | 未知 |
| [Bay Area Rapid Transit](http://api.bart.gov)                                                                                             | BART车站和预测到站时间              | `apiKey` | 否    | 未知 |
| [BC Ferries](https://www.bcferriesapi.ca)                                                                                                 | BC Ferries的航行时间和容量         | 否       | 是   | 是     |
| [BIC-Boxtech](https://docs.bic-boxtech.org/)                                                                                              | 全球集装箱船队的集装箱技术细节            | `OAuth`  | 是   | 未知 |
| [BlaBlaCar](https://dev.blablacar.com)                                                                                                    | 搜索共享汽车行程                   | `apiKey` | 是   | 未知 |
| [Boston MBTA Transit](https://www.mbta.com/developers/v3-api)                                                                             | MBTA车站和预测到站时间              | `apiKey` | 是   | 未知 |
| [Community Transit](https://github.com/transitland/transitland-datastore/blob/master/README.md#api-endpoints)                             | Transitland API            | 否       | 是   | 未知 |
| [Compare Flight Prices](https://rapidapi.com/obryan-software-obryan-software-default/api/compare-flight-prices/)                          | 用于比较不同平台上的航班价格的API         | `apiKey` | 是   | 未知 |
| [CTS](https://api.cts-strasbourg.eu/)                                                                                                     | CTS实时API                   | `apiKey` | 是   | 是     |
| [Grab](https://developer.grab.com/docs/)                                                                                                  | 跟踪送货、乘车费用、付款和忠诚度积分         | `OAuth`  | 是   | 未知 |
| [GraphHopper](https://docs.graphhopper.com/)                                                                                              | 提供逐步指示的A到B路由               | `apiKey` | 是   | 未知 |
| [Icelandic APIs](http://docs.apis.is/)                                                                                                    | 提供冰岛服务或与冰岛相关服务的开放API       | 否       | 是   | 未知 |
| [Impala Hotel Bookings](https://docs.impala.travel/docs/booking-api/)                                                                     | 酒店内容、价格和房间预订               | `apiKey` | 是   | 否      |
| [Izi](http://api-docs.izi.travel/)                                                                                                        | 旅行者的音频导游                   | `apiKey` | 是   | 未知 |
| [Land Transport Authority DataMall, Singapore](https://datamall.lta.gov.sg/content/dam/datamall/datasets/LTA_DataMall_API_User_Guide.pdf) | 新加坡交通信息                    | `apiKey` | 否    | 未知 |
| [Metro Lisboa](http://app.metrolisboa.pt/status/getLinhas.php)                                                                            | 地铁线路延迟                     | 否       | 否    | 否      |
| [Navitia](https://doc.navitia.io/)                                                                                                        | 用于构建与交通数据相关的酷炫功能的开放API     | `apiKey` | 是   | 未知 |
| [Open Charge Map](https://openchargemap.org/site/develop/api)                                                                             | 全球电动车充电位置的公共注册表            | `apiKey` | 是   | 是     |
| [OpenSky Network](https://opensky-network.org/apidoc/index.html)                                                                          | 免费的实时ADS-B航空数据             | 否       | 是   | 未知 |
| [Railway Transport for France](https://www.digital.sncf.com/startup/api)                                                                  | SNCF公共API                  | `apiKey` | 是   | 未知 |
| [REFUGE Restrooms](https://www.refugerestrooms.org/api/docs/#!/restrooms)                                                                 | 为跨性别、陌生儿和性别非二元人士提供安全的洗手间访问 | 否       | 是   | 未知 |
| [Sabre for Developers](https://developer.sabre.com/guides/travel-agency/quickstart/getting-started-in-travel)                             | 旅行搜索-有限使用                  | `apiKey` | 是   | 未知 |
| [Schiphol Airport](https://developer.schiphol.nl/)                                                                                        | Schiphol                   | `apiKey` | 是   | 未知 |
| [Tankerkoenig](https://creativecommons.tankerkoenig.de/swagger/)                                                                          | 德国实时汽油/柴油价格                | `apiKey` | 是   | 是     |
| [TransitLand](https://www.transit.land/documentation/datastore/api-endpoints.html)                                                        | 公共交通聚合                     | 否       | 是   | 未知 |
| [Transport for Atlanta, US](http://www.itsmarta.com/app-developer-resources.aspx)                                                         | Marta                      | 否       | 否    | 未知 |
| [Transport for Auckland, New Zealand](https://dev-portal.at.govt.nz/)                                                                     | 奥克兰交通                      | 否       | 是   | 未知 |
| [Transport for Belgium](https://docs.irail.be/)                                                                                           | iRail API是比利时火车公共交通的第三方API | 否       | 是   | 是     |
| [Transport for Berlin, Germany](https://github.com/derhuerst/vbb-rest/blob/5/docs/api.md)                                                 | 第三方VBB API                 | 否       | 是   | 未知 |
| [Transport for Bordeaux, France](https://opendata.bordeaux-metropole.fr/explore/)                                                         | 波尔多都会区公共交通等（法国）            | `apiKey` | 是   | 未知 |
| [Transport for Budapest, Hungary](https://bkkfutar.docs.apiary.io)                                                                        | 布达佩斯公共交通API                | 否       | 是   | 未知 |
| [Transport for Chicago, US](http://www.transitchicago.com/developers/)                                                                    | 芝加哥交通局（CTA）                | `apiKey` | 否    | 未知 |
| [Transport for Czech Republic](https://www.chaps.cz/eng/products/idos-internet)                                                           | 捷克交通API                    | 否       | 是   | 未知 |
| [Transport for Denver, US](http://www.rtd-denver.com/gtfs-developer-guide.shtml)                                                          | RTD                        | 否       | 否    | 未知 |
| [Transport for Finland](https://digitransit.fi/en/developers/)                                                                            | 芬兰交通API                    | `apiKey` | 是   | 未知 |
| [Transport for Germany](http://data.deutschebahn.com/dataset/api-fahrplan.html)                                                           | 德国铁路（DB）API                | `apiKey` | 否    | 未知 |
| [Transport for Grenoble, France](https://www.mobilites-m.fr/pages/opendata/OpenDataApi.html)                                              | 格勒诺布尔公共交通                  | 否       | 否    | 否      |
| [Transport for Hessen, Germany](https://opendata.rmv.de/site/start.html)                                                                  | RMV API（黑森州公共交通）           | 否       | 是   | 未知 |
| [Transport for Honolulu, US](http://hea.thebus.org/api_info.asp)                                                                          | 檀香山交通信息                    | `apiKey` | 否    | 未知 |
| [Transport for Lisbon, Portugal](https://emel.city-platform.com/opendata/)                                                                | 关于公交路线、停车场和交通的数据           | `apiKey` | 是   | 未知 |
| [Transport for London, England](https://api.tfl.gov.uk)                                                                                   | TfL API                    | `apiKey` | 是   | 未知 |
| [Transport for Los Angeles, US](https://developer.metro.net/api/)                                                                         | 实时地铁车辆位置和行程路线的数据           | 否       | 是   | 未知 |
| [Transport for Manchester, England](https://developer.tfgm.com/)                                                                          | TfGM交通网络数据                 | `apiKey` | 是   | 否      |
| [Transport for Norway](https://developer.entur.org/)                                                                                      | 挪威的交通API和数据集               | 否       | 是   | 未知 |
| [Transport for Ottawa, Canada](https://www.octranspo.com/en/plan-your-trip/travel-tools/developers)                                       | OC Transpo API             | `apiKey` | 是   | 未知 |
| [Transport for Paris, France](http://data.ratp.fr/api/v1/console/datasets/1.0/search/)                                                    | RATP开放数据API                | 否       | 否    | 未知 |
| [Transport for Philadelphia, US](http://www3.septa.org/hackathon/)                                                                        | SEPTA APIs                 | 否       | 否    | 未知 |
| [Transport for Sao Paulo, Brazil](http://www.sptrans.com.br/desenvolvedores/api-do-olho-vivo-guia-de-referencia/documentacao-api/)        | SPTrans                    | `OAuth`  | 否    | 未知 |
| [Transport for Spain](https://data.renfe.com/api/1/util/snippet/api_info.html?resource_id=a2368cff-1562-4dde-8466-9635ea3a572a)           | 西班牙的公共列车                   | 否       | 是   | 未知 |
| [Transport for Sweden](https://www.trafiklab.se/api)                                                                                      | 公共交通消费者                    | `OAuth`  | 是   | 未知 |
| [Transport for Switzerland](https://opentransportdata.swiss/en/)                                                                          | 官方瑞士公共交通开放数据               | `apiKey` | 是   | 未知 |
| [Transport for Switzerland](https://transport.opendata.ch/)                                                                               | 瑞士公共交通API                  | 否       | 是   | 未知 |
| [Transport for The Netherlands](http://www.ns.nl/reisinformatie/ns-api)                                                                   | 只有火车的NS                    | `apiKey` | 否    | 未知 |
| [Transport for The Netherlands](https://github.com/skywave/KV78Turbo-OVAPI/wiki)                                                          | OVAPI，全国范围的公共交通            | 否       | 是   | 未知 |
| [Transport for Toronto, Canada](https://myttc.ca/developers)                                                                              | TTC                        | 否       | 是   | 未知 |
| [Transport for UK](https://developer.transportapi.com)                                                                                    | 英国的交通API和数据集               | `apiKey` | 是   | 未知 |
| [Transport for United States](https://retro.umoiq.com/xmlFeedDocs/NextBusXMLFeed.pdf)                                                     | NextBus API                | 否       | 否    | 未知 |
| [Transport for Vancouver, Canada](https://developer.translink.ca/)                                                                        | TransLink                  | `OAuth`  | 是   | 未知 |
| [Transport for Washington, US](https://developer.wmata.com/)                                                                              | 华盛顿地铁交通API                 | `OAuth`  | 是   | 未知 |
| [transport.rest](https://transport.rest)                                                                                                  | 由社区维护的、开发者友好的公共交通API       | 否       | 是   | 是     |
| [Tripadvisor](https://developer-tripadvisor.com/home/)                                                                                    | 酒店、餐厅、景点或目的地的评级内容          | `apiKey` | 是   | 未知 |
| [Uber](https://developer.uber.com/products)                                                                                               | Uber乘车请求和价格估算              | `OAuth`  | 是   | 是     |
| [Velib metropolis, Paris, France](https://www.velib-metropole.fr/donnees-open-data-gbfs-du-service-velib-metropole)                       | Velib开放数据API               | 否       | 是   | 否      |

**[⬆ 返回目录](#目录)**



## 网址缩短

| API                                                                                  | 描述                      | 认证Auth         | 支持HTTPS | 跨域CORS    |
|--------------------------------------------------------------------------------------|----------------------------------|----------|-------|---------|
| [1pt](https://github.com/1pt-co/api/blob/main/README.md)                             | 一个简单的URL缩短服务                     | 否       | 是   | 是     |
| [Bitly](http://dev.bitly.com/get_started.html)                                       | URL缩短和链接管理                       | `OAuth`  | 是   | 未知 |
| [CleanURI](https://cleanuri.com/docs)                                                | URL缩短服务                          | 否       | 是   | 是     |
| [ClickMeter](https://support.clickmeter.com/hc/en-us/categories/201474986)           | 监视、比较和优化您的营销链接                   | `apiKey` | 是   | 未知 |
| [Clico](https://cli.com/swagger-ui/index.html?configUrl=/v3/api-docs/swagger-config) | URL缩短服务                          | `apiKey` | 是   | 未知 |
| [Cutt.ly](https://cutt.ly/api-documentation/cuttly-links-api)                        | URL缩短服务                          | `apiKey` | 是   | 未知 |
| [Drivet URL Shortener](https://wiki.drivet.xyz/en/url-shortener/add-links)           | 轻松快速地缩短长URL                      | 否       | 是   | 未知 |
| [Free Url Shortener](https://ulvis.net/developer.html)                               | 免费的URL缩短器提供强大的API，与其他网站进行交互      | 否       | 是   | 未知 |
| [GoTiny](https://github.com/robvanbakel/gotiny-api)                                  | 一个轻量级的URL缩短服务，专注于为开发人员和最终用户提供易用性 | 否       | 是   | 是     |
| [Kutt](https://docs.kutt.it/)                                                        | 免费的现代URL缩短器                      | `apiKey` | 是   | 是     |
| [Mgnet.me](http://mgnet.me/api.html)                                                 | Torrent URL缩短API                 | 否       | 是   | 否      |
| [owo](https://owo.vc/api.html)                                                       | 一个简单的链接混淆器/缩短器                   | 否       | 是   | 未知 |
| [Rebrandly](https://developers.rebrandly.com/v1/docs)                                | 定制的URL缩短服务，用于共享品牌链接              | `apiKey` | 是   | 未知 |
| [Short Link](https://github.com/FayasNoushad/Short-Link-API)                         | 短网址支持多个域名                        | 否       | 是   | 未知 |
| [Shrtcode](https://shrtco.de/docs)                                                   | 具有多个域名的URL缩短服务                   | 否       | 是   | 是     |
| [Shrtlnk](https://shrtlnk.dev/developer)                                             | 简单高效的短链接创建                       | `apiKey` | 是   | 是     |
| [TinyURL](https://tinyurl.com/app/dev)                                               | 缩短长URL                           | `apiKey` | 是   | 否      |
| [UrlBae](https://urlbae.com/developers)                                              | 简单高效的短链接创建                       | `apiKey` | 是   | 是     |
| [url.dev](https://autocode.com/url/api/temporary/0.3.0/create)                       | 创建短期自毁链接，有效期从一分钟到一周不等。           | 否       | 是   | 未知 |
| [Urlmskr](https://github.com/Axorax/urlmskr#urlmskr-api)                             | 轻松快速地创建掩码、缩短的链接                  | 否       | 是   | 未知 |

**[⬆ 返回目录](#目录)**


## 车辆
| API                                                                    | 描述                                               | 认证Auth         | 支持HTTPS | 跨域CORS    |
|------------------------------------------------------------------------|-----------------------------------------------------------|----------|-------|---------|
| [Brazilian Vehicles and Prices](https://deividfortuna.github.io/fipe/) | 来自Fundação Instituto de Pesquisas Econômicas - Fipe的车辆信息  | 否       | 是   | 否      |
| [Helipaddy sites](https://helipaddy.com/api/)                          | 直升机和乘客无人机着陆场所目录，Helipaddy数据等                              | `apiKey` | 是   | 未知 |
| [Kelley Blue Book](http://developer.kbb.com/#!/data/1-Default)         | 车辆信息、定价、配置等                                               | `apiKey` | 是   | 否      |
| [Mercedes-Benz](https://developer.mercedes-benz.com/apis)              | 远程访问车辆功能的遥测数据、汽车配置器、定位服务经销商等                              | `apiKey` | 是   | 否      |
| [NHTSA](https://vpic.nhtsa.dot.gov/api/)                               | NHTSA产品信息目录和车辆列表                                          | 否       | 是   | 未知 |
| [Smartcar](https://smartcar.com/docs/)                                 | 锁定和解锁车辆，获取里程表读数和位置等数据。适用于大多数新车                            | `OAuth`  | 是   | 是     |

**[⬆ 返回目录](#目录)**


## 视频

| API                                                                                                | 描述                                      | 认证Auth         | 支持HTTPS | 跨域CORS    |
|----------------------------------------------------------------------------------------------------|--------------------------------------------------|----------|-------|---------|
| [An API of Ice And Fire](https://anapioficeandfire.com/)                                           | 冰与火之歌API                                         | 否       | 是   | 未知 |
| [Bob's Burgers](https://bobs-burgers-api-ui.herokuapp.com)                                         | Bob's Burgers API                                | 否       | 是   | 是     |
| [Breaking Bad](https://breakingbadapi.com/documentation)                                           | 绝命毒师API                                          | 否       | 是   | 未知 |
| [Breaking Bad Quotes](https://github.com/shevabam/breaking-bad-quotes)                             | 一些绝命毒师的名言                                        | 否       | 是   | 未知 |
| [Buffy the Vampire Slayer and Angel](https://github.com/Thatskat/btvs-angel-api)                   | 获取《吸血鬼猎人巴菲》和《安琪儿》的剧集、演员和制作人员数据                   | 否       | 是   | 是     |
| [Catalogopolis](https://api.catalogopolis.xyz/docs/)                                               | Doctor Who API                                   | 否       | 是   | 未知 |
| [Czech Television](http://www.ceskatelevize.cz/xml/tv-program/)                                    | 捷克电视台的电视节目                                       | 否       | 否    | 未知 |
| [Dailymotion](https://developer.dailymotion.com/)                                                  | Dailymotion开发者API                                | `OAuth`  | 是   | 未知 |
| [Dune](https://github.com/ywalia01/dune-api)                                                       | 提供书籍、角色、电影和名言的简单API                              | 否       | 是   | 是     |
| [Final Space](https://finalspaceapi.com/docs/)                                                     | Final Space API                                  | 否       | 是   | 是     |
| [Game of Thrones Quotes](https://gameofthronesquotes.xyz/)                                         | 一些《权力的游戏》的名言                                     | 否       | 是   | 未知 |
| [Gcore Streaming](https://docs.gcore.com/streaming)                                                | 扩展至1亿+观众以上。在几分钟内可靠地流式传输从在线游戏到在线事件的所有内容，而不是几个月时间  | `apiKey` | 是   | 是     |
| [Harry Potter Characters](https://hp-api.onrender.com/)                                            | 带有图像的哈利·波特角色数据                                   | 否       | 是   | 未知 |
| [IMDb-API](https://imdb-api.com/)                                                                  | 接收电影、电视剧和演员信息的API                                | `apiKey` | 是   | 未知 |
| [IMDbOT](https://github.com/SpEcHiDe/IMDbOT)                                                       | 非官方的IMDb电影/电视剧信息                                 | 否       | 是   | 是     |
| [JSON2Video](https://json2video.com)                                                               | 通过编程方式创建和编辑视频：水印、调整大小、幻灯片、配音、文本动画                | `apiKey` | 是   | 否      |
| [Lucifer Quotes](https://github.com/shadowoff09/lucifer-quotes)                                    | 返回路西法的名言                                         | 否       | 是   | 未知 |
| [MCU Countdown](https://github.com/DiljotSG/MCU-Countdown)                                         | 下一部漫威电影的倒计时                                      | 否       | 是   | 是     |
| [Movie Quote](https://github.com/F4R4N/movie-quote/)                                               | 随机电影和系列剧的名言                                      | 否       | 是   | 是     |
| [Mux](https://www.mux.com/)                                                                        | Mux Video是一种API，使开发人员能够构建独特的实时和点播视频体验            | `apiKey` | 是   | 未知 |
| [Open Movie Database](http://www.omdbapi.com/)                                                     | 电影信息                                             | `apiKey` | 是   | 未知 |
| [Ron Swanson Quotes](https://github.com/jamesseanwright/ron-swanson-quotes#ron-swanson-quotes-api) | 电视节目                                             | 否       | 是   | 未知 |
| [Shotstack](https://shotstack.io/)                                                                 | 基于云的视频编辑API                                      | `apiKey` | 是   | 未知 |
| [Simkl](https://simkl.docs.apiary.io)                                                              | 电影、电视和动漫数据                                       | `apiKey` | 是   | 未知 |
| [STAPI](https://stapi.co)                                                                          | 关于《星际迷航》的所有信息                                    | 否       | 是   | 是     |
| [Stranger Things Quotes](https://github.com/shadowoff09/strangerthings-quotes)                     | 返回《怪奇物语》的名言                                      | 否       | 是   | 未知 |
| [Stream](https://api.stream.cz/graphiql)                                                           | 捷克网络电视、电影、剧集和在线视频                                | 否       | 是   | 否      |
| [Stromberg Quotes](https://www.stromberg-api.de/)                                                  | 返回斯特龙贝格的名言和更多内容                                  | 否       | 是   | 未知 |
| [Supernatural Quotes](https://lidiakovac.github.io/supernatural-api)                               | 100+《神秘博士》的名言                                    | 否       | 是   | 未知 |
| [SWAPI](https://swapi.dev/)                                                                        | 你想要的所有《星球大战》数据                                   | 否       | 是   | 是     |
| [SWAPI](https://www.swapi.tech)                                                                    | 《星球大战》的所有内容                                      | 否       | 是   | 是     |
| [SWAPI GraphQL](https://graphql.org/swapi-graphql)                                                 | 星球大战GraphQL API                                  | 否       | 是   | 未知 |
| [The Lord of the Rings](https://the-one-api.dev/)                                                  | 魔戒API                                            | `apiKey` | 是   | 未知 |
| [The Vampire Diaries](https://vampire-diaries-api.netlify.app/)                                    | 电视节目数据                                           | `apiKey` | 是   | 是     |
| [ThronesApi](https://thronesapi.com/)                                                              | 带有图像的《权力的游戏》角色数据                                 | 否       | 是   | 未知 |
| [TMDb](https://www.themoviedb.org/documentation/api)                                               | 社区驱动的电影数据                                        | `apiKey` | 是   | 未知 |
| [TrailerAddict](https://www.traileraddict.com/trailerapi)                                          | 轻松嵌入TrailerAddict的预告片                            | `apiKey` | 否    | 未知 |
| [Trakt](https://trakt.docs.apiary.io/)                                                             | 电影和电视数据                                          | `apiKey` | 是   | 是     |
| [TVDB](https://thetvdb.com/api-information)                                                        | 电视节目数据                                           | `apiKey` | 是   | 未知 |
| [TVMaze](http://www.tvmaze.com/api)                                                                | 电视节目数据                                           | 否       | 否    | 未知 |
| [uNoGS](https://rapidapi.com/unogs/api/unogsng)                                                    | 非官方的Netflix全球在线搜索，一站式搜索所有Netflix地区               | `apiKey` | 是   | 是     |
| [Vimeo](https://developer.vimeo.com/)                                                              | Vimeo开发者API                                      | `OAuth`  | 是   | 未知 |
| [Watchmode](https://api.watchmode.com/)                                                            | 查找电影和剧集的流媒体可用性的API                               | `apiKey` | 是   | 未知 |
| [Web Series Quotes Generator](https://github.com/yogeshwaran01/web-series-quotes)                  | API生成各种网络系列的名言图片                                 | 否       | 是   | 是     |
| [YouTube](https://developers.google.com/youtube/)                                                  | 将YouTube功能添加到您的网站和应用程序中                          | `OAuth`  | 是   | 未知 |

**[⬆ 返回目录](#目录)**

