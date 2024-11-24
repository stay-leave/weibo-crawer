CSDN，52账号：灵海之森

微信公众号：西书北影。欢迎关注

目前在做大模型，开源仓库见：https://github.com/stay-leave/enhance_llm

震惊，有人请我付费指导结果不给钱！！！最后一句话是我接个电话。现在联系不上你，只能是希望你能看到，让你知道我在电脑前等待了你半个小时。以前从来没有收定金的习惯，感谢你让我知道了大学生的险恶。都是男生，有啥直接说呗，搞这一套。

<img width="320" alt="image" src="https://github.com/user-attachments/assets/ebc5d878-d1a5-4f6b-bce1-54ccd1836d38">
<img width="1118" alt="image" src="https://github.com/user-attachments/assets/63d3d052-9c1e-4500-967b-2640d3ddf2be">
<img width="1126" alt="image" src="https://github.com/user-attachments/assets/917664fa-2485-4b6f-8978-24fe69942899">
<img width="1139" alt="image" src="https://github.com/user-attachments/assets/9b7bc9d7-5b38-4edc-a664-e104f1af4a7e">
<img width="1118" alt="image" src="https://github.com/user-attachments/assets/e21b9e83-807a-477b-b34a-1dc4f26d9580">




包含微博爬虫、LDA主题分析、情感分析、时空协同分析四个部分。

流程图

![总体流程图](https://github.com/user-attachments/assets/e1483fac-8dc4-49ab-8256-e3311706c932)





1.微博爬虫

实现微博评论爬取和微博用户信息爬取，一天大概十万条。

![image](https://user-images.githubusercontent.com/58450966/147920881-f8e6f6ea-b389-417b-b13f-5d60829ecf40.png)

![image](https://user-images.githubusercontent.com/58450966/147920969-56bd4164-5599-4ecc-9918-55a42ab37b63.png)


2.LDA主题分析

实现文档主题抽取，包括数据清洗及分词、主题数的确定（主题一致性和困惑度）和最优主题模型的选择（暴力搜索）。

![image](https://user-images.githubusercontent.com/58450966/147921016-4f4bd003-4c68-4d51-82e3-eb5e14433960.png)


3.情感分析

实现评论文本的情感值计算，准确率超过97%，处于0到1之间。

![image](https://user-images.githubusercontent.com/58450966/147921147-90cd3019-a47f-496d-a783-b43d09aa1550.png)

![image](https://user-images.githubusercontent.com/58450966/147921200-db688b8e-2941-4a19-9aaa-aeabb3d9bab2.png)

4.话题热度计算

实现话题的热度的计算，同一时间内总和为1.

![image](https://user-images.githubusercontent.com/58450966/147921229-08e7ffea-c953-4efa-b52e-cdff40c615cc.png)


5.主题相似度计算

实现两个相邻时间片的话题的演化探测，以判断主题演化情况。

![image](https://user-images.githubusercontent.com/58450966/147921312-0917b2bf-d1ff-4076-933f-cb126f0fef16.png)

6.地图绘制

实现分省市情感均值、评论总数、新增确诊人数的地图可视化。

![{%F0EED5 @H@P5 1UKV~R4](https://user-images.githubusercontent.com/58450966/156149916-d1334422-3df7-416c-b9d5-317fd81323e4.png)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=stay-leave/weibo-public-opinion-analysis&type=Date)](https://star-history.com/#stay-leave/weibo-public-opinion-analysis&Date)

