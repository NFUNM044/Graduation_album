# Graduation_album
# 毕业纪念APP产品需求文档
| 撰写人  | 梁嘉颖  | 
|:-:|:-:|
| 学号  | 171013044  |
| APP名称 | 旧拾光  |
| APP类别 | 摄影 社交 |
# PRD价值主张设计：
## 产品介绍：
- 旧拾光APP是一款提供给毕业学生群体用户，具有共享朋友社区，评论留言 、趣味拍照功能的毕业纪念APP。致力于帮助用户记录美好时光，留住回忆时刻。
## 价值宣言：
- 每每毕业季，大家都想留住属于自己学生时代的回忆。旧拾光APP不仅具有普通拍照功能，还结合应用人工智能中的计算机视觉和自然语言处理技术，为用户提供优质的产品服务，提升用户体验趣味值。
- 1、人脸检测API、美颜滤镜API、图像风格转API：用户在拍照时可增加美颜滤镜，避免用户在天气、光线不好等因客观因素限制，影响拍照结果不好，导致多次拍照而浪费时间。
- 2 、评论抽取API、相似图片搜索API：用户根据对照片或对个人留言，最后自动抽取观点形成个人标签，并通过相似图片、人脸检测搜索出其他相关人物图片，帮助用户日后想念时回忆相关美好时光，并帮助用户重新联络对方。
## 核心价值（最小可行性产品）：
- 可自定义对人脸进行美颜；自动分析评论并输出标签；查找相似图片，实现相关内容搜索、推荐的产品。
## 核心价值与用户痛点：
- 用户痛点：素颜、拍照背景不好看、天气光线不理想，拍照效果不佳。
1. →用户在使用产品时，减少对自身颜值不自信，避免以往拍照纪念方式单调无趣的尴尬情景。
- 用户痛点：后悔当年没有好好了解与他/她，想要认识他/她。
1. →在毕业后，用户可以在相似图片搜索推荐中、个人评论标签中回忆对方，重新联络。
## 人工智能概率性与用户痛点：
- 用户在使用人脸检测进行美颜美妆的产品中的精准度是比较高的，AI这方面已经比较成熟了，而相似图片搜索或是评论抽取标签，反而是有可能出现假阳性（false positive），但对用户的负面体验机率并不会高于正面影响。
## 需求列表与人工智能API加值：
| 使用场景 | 用户需求  |重要程度 |对应功能  | 使用的API  | 
|:-:|:-:|:-: |:-:|:-:|
|当用户素颜合照，天气、光线不好。| 用户想要拍出来的照片好看。 | 重 要 |美颜滤镜、图像风格转换|[百度AI 美颜滤镜API](https://ai.baidu.com/tech/face/BeautySDK) 、[百度AI 图像风格转换API](https://ai.baidu.com/tech/imagesearch/similar)| 
|当用户拍照或合照时时表情无趣单一|想要趣味独特的贴图表情 。 |次重要|表情贴纸 | [Face++贴纸SDK](https://www.faceplusplus.com.cn/sdk/paster/)|
| 在朋友社区里对好友发出的合照或是对其个人的留言、评论。 |毕业后想要再回顾好友的印象、故事。   | 次重要 |评论观点抽取| [百度AI 评论观点抽取](https://ai.baidu.com/tech/nlp_apply/comment_tag)

# 二、原型设计
## 交互及界面设计：
- 首页：主要的两个交互功能，拍照与社区。<br>

![旧拾光 首页.png](https://upload-images.jianshu.io/upload_images/9509773-7c8830e3318126bc.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- 拍照页中的贴纸功能。提供用户趣味独特的贴图表情。
![旧拾光 拍照贴纸页.png](https://upload-images.jianshu.io/upload_images/9509773-d378ea3b00f74502.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- 拍照页中的美颜功能。用户可自定义美颜。
![旧拾光 美颜页.png](https://upload-images.jianshu.io/upload_images/9509773-6431db285e6aa7a9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- 拍照页中的滤镜功能，用户可切换不同场景的滤镜。

![旧拾光 滤镜页.png](https://upload-images.jianshu.io/upload_images/9509773-9af7d81f6c89477c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- 社区功能，可留言，回看共同相册，叙旧聊天。
![旧拾光 社区功能.png](https://upload-images.jianshu.io/upload_images/9509773-a03c20a1896d3735.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## 信息设计：
## 原型文档：
# 三、API 产品使用关键AI或机器学习之API的输出入展示
## 使用水平：
## 使用比较分析：
## 使用后风险报告：

