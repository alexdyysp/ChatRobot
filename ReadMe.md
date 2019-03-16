ChatBot概览
-----------
1.Retrieval-based:解决搜索时间复杂度

Challenges:
2.语境
- 1 语言语境: 这话在说什么内容
- 2 物理语境: 这话在哪里说的

3.统一的语言个性:A Persona-Based Neural Conversation Model (Li et al., 2016).
主要思想，哪怕语法对，也要让输出语句性格色彩符合心理学模型

4.模型验证
How NOT To Evaluate Your Dialogue System: An Empirical Study of Unsupervised Evaluation Metrics for Dialogue Response Generation(Liu,2016)

5.多样性
A Diversity-Promoting Objective Function for Neural Conversation Models(Li et al. 2015)

智能对话，往自动化方向走
基于查找，知识库，规则，可以更好的控制机器

NPL基础
=======
NLTK<br>
- tokenize: 把长句子拆成有意义的小部件  
但是比如社交网络上,这些乱七八糟的不合语法不合正常逻辑的语言很多: 拯救 @某人, 表情符号, URL, #话题符号
需要用正则表达式匹配过滤  

文本处理流程<br>
- 分词
- 词形归一化：Stemming词干提取；Lemmatization 词形归一
- 停止词  

NLP经典三案例<br>
- 情感分析
- 文本相似度
- 文本分类  

深度学习加持<br>
- Autoencoder
- Word2Vec  

ChatBot
--------

- 关于聊天机器人的思考
1.工程考量
2.机器学习角度考虑
- 预备知识
1.检索与匹配
2.分类与朴素贝叶斯
- chatterbot
1.架构与使用方法
2.源码分析

思考：
工程考量
算法与机器学习角度

4.场景分类与NB
