# VoxRole：面向基于语音角色扮演智能体评估的综合基准

发布时间：2025年09月04日

`Agent` `媒体与娱乐`

> VoxRole: A Comprehensive Benchmark for Evaluating Speech-Based Role-Playing Agents

# 摘要

> 近年来大型语言模型（LLMs）的突破性进展极大地推动了角色扮演对话智能体（RPCAs）的发展。这些系统旨在通过稳定的角色塑造为用户带来沉浸式体验。然而，当前RPCA研究存在两大局限。首先，现有研究多聚焦于文本模态，却完全忽略了语音中关键的副语言特征——如语调、韵律和节奏——而这些正是传达角色情感、塑造鲜活形象的核心要素。其次，语音角色扮演领域长期缺乏标准化的评估基准。目前大多数口语对话数据集仅用于基础能力评估，角色设定要么过于单薄，要么定义模糊，因此无法有效衡量模型在长期角色一致性等核心能力上的表现。为填补这一关键空白，我们提出了VoxRole——首个专为评估语音基RPCAs打造的综合基准。该基准包含13335轮多轮对话，总语音时长65.6小时，涵盖261部电影中的1228个独特角色。为构建该资源，我们设计了一种新颖的两阶段自动化流程：首先将电影音频与剧本对齐，然后利用LLM为每个角色系统构建多维度档案。借助VoxRole，我们对当前主流口语对话模型进行了多维度评估，深入剖析了这些模型在维持角色一致性方面的优势与不足。

> Recent significant advancements in Large Language Models (LLMs) have greatly propelled the development of Role-Playing Conversational Agents (RPCAs). These systems aim to create immersive user experiences through consistent persona adoption. However, current RPCA research faces dual limitations. First, existing work predominantly focuses on the textual modality, entirely overlooking critical paralinguistic features including intonation, prosody, and rhythm in speech, which are essential for conveying character emotions and shaping vivid identities. Second, the speech-based role-playing domain suffers from a long-standing lack of standardized evaluation benchmarks. Most current spoken dialogue datasets target only fundamental capability assessments, featuring thinly sketched or ill-defined character profiles. Consequently, they fail to effectively quantify model performance on core competencies like long-term persona consistency. To address this critical gap, we introduce VoxRole, the first comprehensive benchmark specifically designed for the evaluation of speech-based RPCAs. The benchmark comprises 13335 multi-turn dialogues, totaling 65.6 hours of speech from 1228 unique characters across 261 movies. To construct this resource, we propose a novel two-stage automated pipeline that first aligns movie audio with scripts and subsequently employs an LLM to systematically build multi-dimensional profiles for each character. Leveraging VoxRole, we conduct a multi-dimensional evaluation of contemporary spoken dialogue models, revealing crucial insights into their respective strengths and limitations in maintaining persona consistency.

[Arxiv](https://arxiv.org/abs/2509.03940)