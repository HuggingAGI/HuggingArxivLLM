# 5G辐射防护指南：从大语言模型的回答看隐性误导信息的传播

发布时间：2025年03月12日

`LLM应用` `信息传播` `内容安全`

> How to Protect Yourself from 5G Radiation? Investigating LLM Responses to Implicit Misinformation

# 摘要

> 随着大型语言模型（LLMs）在各行各业的广泛应用，它们在传播错误信息方面可能带来的隐性风险成为一个不容忽视的安全问题。当前研究主要关注LLMs在明确错误陈述上的表现，却忽视了错误信息在现实中的用户互动中常常以未被质疑的前提形式悄然出现。为此，我们创建了ECHOMIST——首个专注于隐性错误信息的全面基准测试，其中错误的前提被巧妙地嵌入到用户对LLMs的查询中。ECHOMIST基于严格的标准，从包括真实世界的人工智能对话和社会媒体互动在内的多样化来源中精心筛选和整理数据。我们还引入了一项全新的评估指标，旨在衡量LLMs是否能够识别并反驳错误信息，而不是助长用户的误解。通过对GPT-4、Claude和Llama等主流LLMs进行广泛实证研究，我们发现当前模型在这一任务上的表现令人担忧，常常无法识别错误的前提，并生成误导性的解释。我们的研究结果凸显了在LLM安全研究中加强对隐性错误信息关注的紧迫性。

> As Large Language Models (LLMs) are widely deployed in diverse scenarios, the extent to which they could tacitly spread misinformation emerges as a critical safety concern. Current research primarily evaluates LLMs on explicit false statements, overlooking how misinformation often manifests subtly as unchallenged premises in real-world user interactions. We curated ECHOMIST, the first comprehensive benchmark for implicit misinformation, where the misinformed assumptions are embedded in a user query to LLMs. ECHOMIST is based on rigorous selection criteria and carefully curated data from diverse sources, including real-world human-AI conversations and social media interactions. We also introduce a new evaluation metric to measure whether LLMs can recognize and counter false information rather than amplify users' misconceptions. Through an extensive empirical study on a wide range of LLMs, including GPT-4, Claude, and Llama, we find that current models perform alarmingly poorly on this task, often failing to detect false premises and generating misleading explanations. Our findings underscore the critical need for an increased focus on implicit misinformation in LLM safety research.

[Arxiv](https://arxiv.org/abs/2503.09598)