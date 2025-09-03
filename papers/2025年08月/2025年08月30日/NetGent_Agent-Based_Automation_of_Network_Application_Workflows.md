# <翻译失败>

发布时间：2025年08月30日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。` `基础理论`

> NetGent: Agent-Based Automation of Network Application Workflows

# 摘要

> <翻译失败>

> We present NetGent, an AI-agent framework for automating complex application workflows to generate realistic network traffic datasets. Developing generalizable ML models for networking requires data collection from network environments with traffic that results from a diverse set of real-world web applications. However, using existing browser automation tools that are diverse, repeatable, realistic, and efficient remains fragile and costly. NetGent addresses this challenge by allowing users to specify workflows as natural-language rules that define state-dependent actions. These abstract specifications are compiled into nondeterministic finite automata (NFAs), which a state synthesis component translates into reusable, executable code. This design enables deterministic replay, reduces redundant LLM calls through state caching, and adapts quickly when application interfaces change. In experiments, NetGent automated more than 50+ workflows spanning video-on-demand streaming, live video streaming, video conferencing, social media, and web scraping, producing realistic traffic traces while remaining robust to UI variability. By combining the flexibility of language-based agents with the reliability of compiled execution, NetGent provides a scalable foundation for generating the diverse, repeatable datasets needed to advance ML in networking.

[Arxiv](https://arxiv.org/abs/2509.00625)