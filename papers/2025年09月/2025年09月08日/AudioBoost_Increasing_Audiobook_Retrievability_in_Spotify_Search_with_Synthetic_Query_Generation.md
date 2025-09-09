# AudioBoost：借助合成查询生成提升Spotify搜索中有声书的检索效果

发布时间：2025年09月08日

`LLM应用` `媒体与娱乐`

> AudioBoost: Increasing Audiobook Retrievability in Spotify Search with Synthetic Query Generation

# 摘要

> Spotify近期将有声书纳入其内容目录，为既有的音乐和播客服务增添了新选择。搜索往往是用户探索新项目的第一道门，而Spotify的一个重要目标便是助力用户探索有声书目录。具体而言，我们希望让那些没有特定目标的用户能够通过主题、类型、故事元素、年代等维度进行广泛搜索，进而发现心仪的有声书、作者与出版商。要实现这一目标，我们需要做到两点：1）鼓励用户输入更多关于有声书的探索性查询；2）增强检索系统对有声书探索性查询的处理能力。然而，这在冷启动场景下面临挑战：与音乐、播客等已有内容相比，有声书的用户交互数据匮乏，导致检索性偏差问题。为此，我们研发了AudioBoost系统，它通过生成合成查询来提升有声书在Spotify搜索中的检索性。该系统借助大型语言模型（LLMs），根据有声书的元数据生成合成查询。这些合成查询会同时被编入查询自动补全（QAC）和搜索检索引擎的索引，从而同时优化查询构建与检索效果。离线评估结果显示，合成查询不仅提升了检索性，还保证了较高质量。此外，在线A/B测试数据表明，AudioBoost使有声书展示量提升0.7%，点击量增长1.22%，探索性查询完成量增加1.82%。

> Spotify has recently introduced audiobooks as part of its catalog, complementing its music and podcast offering. Search is often the first entry point for users to access new items, and an important goal for Spotify is to support users in the exploration of the audiobook catalog. More specifically, we would like to enable users without a specific item in mind to broadly search by topic, genre, story tropes, decade, and discover audiobooks, authors and publishers they may like. To do this, we need to 1) inspire users to type more exploratory queries for audiobooks and 2) augment our retrieval systems to better deal with exploratory audiobook queries. This is challenging in a cold-start scenario, where we have a retrievabiliy bias due to the little amount of user interactions with audiobooks compared to previously available items such as music and podcast content. To address this, we propose AudioBoost, a system to boost audiobook retrievability in Spotify's Search via synthetic query generation. AudioBoost leverages Large Language Models (LLMs) to generate synthetic queries conditioned on audiobook metadata. The synthetic queries are indexed both in the Query AutoComplete (QAC) and in the Search Retrieval engine to improve query formulation and retrieval at the same time. We show through offline evaluation that synthetic queries increase retrievability and are of high quality. Moreover, results from an online A/B test show that AudioBoost leads to a +0.7% in audiobook impressions, +1.22% in audiobook clicks, and +1.82% in audiobook exploratory query completions.

[Arxiv](https://arxiv.org/abs/2509.06452)