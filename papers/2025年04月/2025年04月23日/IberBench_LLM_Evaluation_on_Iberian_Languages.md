# IberBench：针对伊比利亚语言的LLM评测

发布时间：2025年04月23日

`LLM应用` `多语言`

> IberBench: LLM Evaluation on Iberian Languages

# 摘要

> 大语言模型（LLMs）的全面评估困难重重，尤其是对于非英语语言，由于高质量数据的匮乏。现有的基准测试和排行榜主要以英语为中心，仅有少数涉及其他语言。这些基准在多个关键方面存在不足：忽视语言变体的多样性，侧重基础自然语言处理（NLP）能力而非工业相关任务，且是静态的。基于这些考虑，我们推出了IberBench，一个全面且可扩展的基准测试，旨在评估LLMs在基础和工业相关NLP任务中的性能，涵盖伊比利亚半岛和伊比利亚美洲地区使用的语言。IberBench整合了来自评估活动和近期基准测试的101个数据集，覆盖22个任务类别，如情感和情绪分析、毒性检测和摘要。该基准通过持续更新和由专家委员会审核的社区驱动模型及数据集提交，解决了现有评估实践中缺乏语言多样性和静态评估设置等关键限制。我们评估了23个LLMs，参数规模从1亿到140亿不等，并提供了对其优势和局限性的实证见解。我们的研究发现表明：(i) LLMs在工业相关任务上的表现不如基础任务，(ii) 加利西亚语和巴斯克语的平均表现较低，(iii) 部分任务的结果接近随机水平，(iv) 在其他任务中，LLMs的表现高于随机但低于共享任务系统。IberBench提供了整个评估管道的开源实现，包括数据集规范化和托管、LLMs的增量评估以及公开访问的排行榜。

> Large Language Models (LLMs) remain difficult to evaluate comprehensively, particularly for languages other than English, where high-quality data is often limited. Existing benchmarks and leaderboards are predominantly English-centric, with only a few addressing other languages. These benchmarks fall short in several key areas: they overlook the diversity of language varieties, prioritize fundamental Natural Language Processing (NLP) capabilities over tasks of industrial relevance, and are static. With these aspects in mind, we present IberBench, a comprehensive and extensible benchmark designed to assess LLM performance on both fundamental and industry-relevant NLP tasks, in languages spoken across the Iberian Peninsula and Ibero-America. IberBench integrates 101 datasets from evaluation campaigns and recent benchmarks, covering 22 task categories such as sentiment and emotion analysis, toxicity detection, and summarization. The benchmark addresses key limitations in current evaluation practices, such as the lack of linguistic diversity and static evaluation setups by enabling continual updates and community-driven model and dataset submissions moderated by a committee of experts. We evaluate 23 LLMs ranging from 100 million to 14 billion parameters and provide empirical insights into their strengths and limitations. Our findings indicate that (i) LLMs perform worse on industry-relevant tasks than in fundamental ones, (ii) performance is on average lower for Galician and Basque, (iii) some tasks show results close to random, and (iv) in other tasks LLMs perform above random but below shared task systems. IberBench offers open-source implementations for the entire evaluation pipeline, including dataset normalization and hosting, incremental evaluation of LLMs, and a publicly accessible leaderboard.

[Arxiv](https://arxiv.org/abs/2504.16921)