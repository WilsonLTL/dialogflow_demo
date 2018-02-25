# dialogflow_demo
![image01](https://blog.dialogflow.com/images/dialogflow-logo.png)<br >
本篇為Dialogflow (前稱:api.ai)快速入門<br >
Dialogflow為google所提供的NLP framwork,以最短的時間完成NLP結構 <br >

### NLP所包括的功能:
MT - Machine Translation,語言翻譯,e.g Google Translate <br >
QA - QuestionAnswering,根據句中的intent和entities,並判定用戶所需 <br >
IE - Information Extraction,於一連串句子中將重點"定位"<br >
SA - Sentiment Analysis,分析用戶於對話的情感傾向 <br >

一般chatbot指QA Level所作岀的分析,他們針對用戶的問題作出回應,亦可將他們視為高階Q&A<br >
而部分由NLP modules(own dataset train)建構的的NLP chatbot有較大機會包含SA與IE功能,因此他們的建構成本與時間亦大大增加<br >

### GuideBot VS ChatBot
個人將目前市面上的聊天機器人分為2類:GuideBot(指導式)和ChatBot(聊天式)<br >

#### GuideBot(指導式)
GuideBot是一種最為簡單的“聊天機器人”,而事實上他們根本缺乏與人對答的能力,它們只能以step by step的模式來引導用戶表達他們的要求,而develope所要求的的tech level亦不高.<br >
一個由零開始的新手（有編程經驗）基本上可以在1星期內基本掌握建構技巧,以我個人經驗,如果有相關經驗（其他lanuage),3天可以完成e-commerce的基本建構 
(忽視Secure level)

![image02](https://camo.githubusercontent.com/82bc0349e969a3e53f7ebbf6b55cfd6bf69bf642/68747470733a2f2f692e696d6775722e636f6d2f713546595739382e706e67)

#### ChatBot(聊天式)
Chatbot所代表的"chat",正正是聊天機器人的精粹所在,藉與用戶的正常普通對話,除了分析用戶的要求(intents),亦從句子中得到要求的細節(entities)<br >
chatbot有別於guidebot的地方在於,chatbot內置模組(module)用以分析用戶意圖,而模組的訓練(training)往往需要大量開發時間和成本<br >
而訓練一個準確率高的模組,所需要的數據量亦極為龐大,非一般中小企業能輕易負擔,大部分的公司都會選擇使用 website收集數據->訓練模組->建構NLP模組,例如淘寶,Amazon,他們天生擁有大量數據,以供參考與訓練,意味著他們能節省大量的時間 並非常有效地提高模組的識別率,因此除非該公司的技術背景非常雄厚,絕少公司願意投資大量成本建構屬於自己的模組,但由自己所訓練出來的模組,甚至可以與人進行"Chit Chat".<br >

但當然,自己建構模組只不過是開發Chatbot的其中一個途徑,事實上坊間亦有很多提供使用的工具(framwork),例如Microsoft Luis,Google Dialogflow(api.ai),他們大部分基於英文作為主要語言,因此於繁簡中文(包括粵語)的表現並不太理想,但事實上如果用戶需求並不太針對性的話(例如大量生僻字,行內專業術語),不妨使用由他們所提供的工具,以減少開發成本與時間.

 ![image03](http://www.drcare.ai/images/news5.jpg)
