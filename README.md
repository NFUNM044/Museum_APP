# Museum_APP
# 博物馆APP产品需求文档
| 撰写人  | 梁嘉颖  | 
|:-:|:-:|
| 学号  | 171013044  |
| APP名称 | 小口袋博物馆  |
| APP类别 | 旅游、教育  |
# PRD价值主张设计：
## 产品介绍：
- 小口袋博物馆App是一款提供给用户涵盖馆内展品分布人流量、楼层地图导览、步行参观路线、展品信息科普等功能的APP。致力于帮助用户在浏览参观博物馆时获得更好的体验。

## 价值宣言：
小口袋博物馆APP将通过语音合成、人流量统计、通用物体和场景识别、室内地图定位等api应用接口，为用户打造个性化服务与新型体验。

- 1、人流量统计API、室内定位API：用户可根据查看数据，可错峰参观，避免到人流拥挤的展馆参观，减少用户时间成本。
- 2 、室内定位API、室内地图API、室内路线规划API：用户根据查看室内地图，轻松切换楼层展示，不同楼层展馆、洗手间、咨询处等信息，并能推荐出最合适的路线规划，帮助您快速找到目的地，避免用户在博物馆迷路。
- 3 、通用物体和场景识别API、语音合成API：用户可根据拍摄照片，识别图片中物体名称并会推荐出相关的百科信息，并通过语音合成，自定义场景需求对音库的语速、音调、音量进行灵活设置，满足个性化需求，提高用户交互体验。
## 核心价值（最小可行性产品）：
- 主要通过给用户提供楼层地图导览、展品信息科普等功能。
## 核心价值与用户痛点：
- 用户痛点：不清楚楼层信息，且易迷路。
1. →. 用户在使用app时，可快速查询到楼层信息，并且有合理路线规划到目的地。避免迷路而造成浪费时间，降低时间成本，有效率的使用时间参观博物馆。
- 用户痛点：想了解类似展品的属性、历史资料，却不知怎么获得信息。
1. →. 用户在使用app时，可拍照识别，识别结果给出相关内容推荐，并可转化为语音。帮助解决用户的好奇心，也可为用户提供多种音库的朗读功能，释放双手和双眼，获得更极致的体验。

## 人工智能概率性与用户痛点：
- 用户在使用室内地图定位功能精准度是比较高的，方便用户找到目的地，而在通用物体识别文物或展品的部分，反而是有可能因为数据库资料不足或者是识别失误，对用户作出错误的答案，出现假阳性（false positive）。
## 需求列表与人工智能API加值：
| 使用场景 | 用户需求  |重要程度 |对应功能  | 使用的API  | 
|:-|:-: | :-: |:-:|:-:|
|没拿到纸质博物馆地图导览|需要随时随手看地图导览 | 重 要 |室内定位、室内地图|[高德地图室内地图API](https://lbs.amap.com/getting-started/indoorintro) 、[高德地图室内定位API](https://lbs.amap.com/getting-started/indoorlocation) |
|看不懂地图，不知道路线怎么走|想要导航帮助|重要|室内路线规划|[百度地图室内路线规划API](http://lbsyun.baidu.com/index.phptitle=androidsdk/guide/navigation/indoorwalknavi)|
|想了解类似展品的属性、历史资料。|想要知道百科|次重要  | 展品信息科普|[百度通用物体和场景识别APIAPI](https://ai.baidu.com/tech/imagerecognition/general) | 
|眼睛视觉疲劳、想想了解类似展品的属性、历史资料|不想用眼睛观看，但又想了解展品|次重要|声音播放|[百度语音合成API](https://ai.baidu.com/tech/speech/tts)|
