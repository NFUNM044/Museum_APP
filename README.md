# Museum_APP
# 博物馆APP产品需求文档
| 撰写人  | 梁嘉颖  | 
|:-:|:-:|
| 学号  | 171013044  |
| APP名称 | 小口袋博物馆  |
| APP类别 | 旅游、教育  |
# PRD价值主张设计：
## 产品介绍：
- 小口袋博物馆App是一款提供给用户具有展品信息语音播报、馆内展品分布人流量、展品信息科普等功能的APP。致力于帮助用户在浏览参观博物馆时获得更好的体验。

## 价值宣言：
小口袋博物馆APP将通过语音合成、人流量统计、通用物体和场景识别、等api应用接口，为用户打造个性化服务与新型体验。

- 1、人流量统计API：用户可根据查看数据，可错峰参观，避免到人流拥挤的展馆参观，减少用户时间成本。
- 2通用物体和场景识别API：用户可根据拍摄照片，识别图片中物体名称并会推荐出相关的百科信息。
- 3、语音合成API：通过语音合成，自定义场景需求对音库的语速、音调、音量进行灵活设置，满足个性化需求，提高用户交互体验。
## 核心价值（最小可行性产品）：
- 主要通过给用户展品导览、展品信息科普、推荐博物馆路线等功能。
## 核心价值与用户痛点：
- 用户痛点：不清楚博物馆内人数的状况，害怕展厅人山人海，影响观展的效果。<br>
→. 用户在使用app时，可快速查询到展厅内的人流量统计，用颜色显示提醒用户。避免因人数过多而造成浪费时间，影响观展效果。
- 用户痛点：想了解类似展品的属性、历史资料，却不知怎么获得信息。<br>
→. 用户在使用app时，可拍照识别，识别结果给出相关内容推荐，
- 用户痛点：想边听边看，但是有些博物馆的导览解说机可能要收费，且存在卫生问题。<br>
→.可转化为语音。帮助解决用户的难题，也可为用户提供多种音库的朗读功能，释放双眼，获得更极致的体验。

## 人工智能概率性与用户痛点：
- 用户在使用人流量统计功能时，可能存在时间差的问题，并且人流是动态的，可能会误导用户。
## 需求列表与人工智能API加值：
| 使用场景 | 用户需求  |重要程度 |对应功能  | 使用的API  | 
|:-:|:-: | :-: |:-:|:-:|
|眼睛视觉疲劳、想想了解类似展品、历史资料|不想用眼睛观看，但又想了解展品|重要|声音播放|[百度语音合成API](https://ai.baidu.com/tech/speech/tts)|
|不知道展厅人流状况|想了解展厅的人是否拥挤|重要|人流量统计|[百度人流量统计API](https://ai.baidu.com/tech/body/num)|
|想了解类似展品的属性、历史资料。|想要知道百科|次重要  | 展品信息科普|[百度通用物体和场景识别API](https://ai.baidu.com/tech/imagerecognition/general) | 
# 二、原型设计
## 交互及界面设计：
- 1、首页：用户进入小口袋博物馆APP后，可选择不同功能。<br>
![小口袋博物馆APP 首页.png](https://upload-images.jianshu.io/upload_images/9509773-7e91ef5b6326d126.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- 2、导览页面：可以选择展品进行语音收听信息。
![小口袋博物馆APP 导览.png](https://upload-images.jianshu.io/upload_images/9509773-d918802d4d599784.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- 英文界面
![小口袋博物馆APP 导览（英语）.png](https://upload-images.jianshu.io/upload_images/9509773-b3cca34d8686ec34.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- 3、人流情况页面：可通过查看人流密集情况决定去哪个展厅观展，错开人流高峰期，提高观赏体验值。
![小口袋博物馆APP 人流情况.png](https://upload-images.jianshu.io/upload_images/9509773-4a0887d9e01e93a5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- 4、语音设置：可通过自定义的调节语音播放声音，根据个性化的喜好设置，获取更优质的交互体验。
![小口袋博物馆APP 语音设置.png](https://upload-images.jianshu.io/upload_images/9509773-eaeedd7c05a3ce5d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- 5、看一看：通过对物品拍照，识别图片中物体名称并会推荐出相关的百科信息。
![小口袋博物馆APP 看一看.png](https://upload-images.jianshu.io/upload_images/9509773-a1e87b3813dc9cef.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



## 信息设计：
- 小口袋博物馆APP运作流程：
![小口袋博物馆APP.jpg](https://upload-images.jianshu.io/upload_images/9509773-91f0f41491ec2cc1.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



## 原型文档：
### [小口袋博物馆APP可交互原型设计](http://jiayingb.gitee.io/api_museum_app)  ← 可点击查看
### [原型文件，供下载](https://github.com/NFUNM044/prototype_download_museum) ← 可点击下载



# 三、API 产品使用关键AI或机器学习之API的输出入展示
## 使用水平：
## 使用比较分析：
## 使用后风险报告：
