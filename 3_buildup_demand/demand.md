
# 根据功能谈要求

在第一章的“[系统构建策略][1]”中，我们完成了用户需求的关键指标分析，也推导出了内容的形态，进而形成了系统的功能说明。再回顾一下吧：

## 用户需求的关键指标分析

|   关键指标   	| 素材层 	| 文章层 	| 图书层 	|
|:--------:	|:------:	|:------:	|:------:	|
| 快速输出 	|    √   	|        	|        	|
| 深入思考 	|        	|    √   	|    √   	|
|   分类   	|    √   	|    √   	|        	|
|   同步   	|    √   	|       	|           	|
|   搜索   	|    √   	|        	|        	|
|   协作    	|        	|       	|    √   	|
| 版本控制   |        	|    √ 	|    √   	|
|   展示   	|        	|    √   	|    √   	|

## 可能的内容形态

三个层次可能的内容形态也已经得出结论，分别为：

- 素材层：文本、录音、脑图
- 文章层：脑图、文章及文章库、可控版本的文章存储工具、可展示文章和文章库的平台
- 图书层：脑图、文章库、便于阅读的图书、可控版本的文章存储工具、所有过程文章都统一管理的平台、支持快速发布和精美展示图书的平台

如果按照前端和后端的划分方式，还可以这样分：

- 前端（给用户）：文章及文章库、便于阅读的图书。
- 后端（给自己）：文本、录音、脑图、可控版本的文章存储工具、可展示文章和文章库的平台、所有过程文章都统一管理的平台、支持快速发布和精美展示图书的平台。

## 软硬件选型的基本要求

PKOS的核心功能是：**将逻辑结构上进行分层的内容，呈现出不同的形态，用以满足用户需求即可**，既然开始考虑系统构建的软硬件选型问题，自然也要从功能入手，选型所要满足的基本要求已经在上述表格和内容形态中呈现出来了。站在系统最小功能构建的角度来看，总结出对软硬件选型的要求是：

- **硬件**：可以随身携带、有多个输入入口、使用及切换高效。
- **软件**：支持多平台（硬件）同步、支持检索、便于协同、有良好的版本控制功能以及便于展示。

基于这个要求，软硬件的选型方案基本上已经成型了，下面，我们先从硬件准备开始。

---- 

## Changelog

- 2016年04月28日 创建内容 by [易仁永澄][2]

[1]:	./2_system_principle/strategy_of_system_buildup.md
[2]:	http://blog.hiddenwangcc.com
