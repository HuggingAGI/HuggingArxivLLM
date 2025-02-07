# SafeRAG: 大型语言模型检索增强生成的安全性评估

发布时间：2025年01月28日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）的安全性，提出了一个名为SafeRAG的基准来评估RAG的安全性，并构建了相应的数据集来模拟各种攻击场景。论文的核心内容围绕RAG的安全性展开，因此应归类为RAG。` `信息安全`

> SafeRAG: Benchmarking Security in Retrieval-Augmented Generation of Large Language Model

# 摘要

> 检索增强生成（RAG）的索引-检索-生成范式通过整合外部知识到大型语言模型（LLMs）中，在解决知识密集型任务上取得了显著成功。然而，引入外部和未经验证的知识增加了LLMs的脆弱性，攻击者可通过操纵知识进行攻击。本文提出了一个名为SafeRAG的基准，用于评估RAG的安全性。我们首先将攻击任务分为银噪声、上下文间冲突、软广告和白拒绝服务四类。接着，我们主要为每类任务手动构建了RAG安全评估数据集（即SafeRAG数据集），并利用该数据集模拟RAG可能遇到的各种攻击场景。在14个代表性RAG组件上的实验表明，RAG对所有攻击任务均表现出显著脆弱性，即使是最明显的攻击任务也能轻松绕过现有检索器、过滤器或高级LLMs，导致RAG服务质量下降。代码可在以下网址获取：https://github.com/IAAR-Shanghai/SafeRAG。

> The indexing-retrieval-generation paradigm of retrieval-augmented generation (RAG) has been highly successful in solving knowledge-intensive tasks by integrating external knowledge into large language models (LLMs). However, the incorporation of external and unverified knowledge increases the vulnerability of LLMs because attackers can perform attack tasks by manipulating knowledge. In this paper, we introduce a benchmark named SafeRAG designed to evaluate the RAG security. First, we classify attack tasks into silver noise, inter-context conflict, soft ad, and white Denial-of-Service. Next, we construct RAG security evaluation dataset (i.e., SafeRAG dataset) primarily manually for each task. We then utilize the SafeRAG dataset to simulate various attack scenarios that RAG may encounter. Experiments conducted on 14 representative RAG components demonstrate that RAG exhibits significant vulnerability to all attack tasks and even the most apparent attack task can easily bypass existing retrievers, filters, or advanced LLMs, resulting in the degradation of RAG service quality. Code is available at: https://github.com/IAAR-Shanghai/SafeRAG.

[Arxiv](https://arxiv.org/abs/2501.18636)