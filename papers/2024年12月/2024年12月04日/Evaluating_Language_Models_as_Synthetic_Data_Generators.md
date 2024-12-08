# 对语言模型作为合成数据生成器进行评估

发布时间：2024年12月04日

`LLM应用` `语言模型` `数据生成`

> Evaluating Language Models as Synthetic Data Generators

# 摘要

> 摘要：随着语言模型（LM）后期训练中合成数据的使用愈发频繁，语言模型生成高质量数据的能力几乎与直接解决问题的能力同等重要。此前的工作虽致力于开发有效的数据生成方法，却缺少在统一环境中对不同语言模型作为数据生成器的系统对比。为弥补这一不足，我们推出了 AgoraBench，这一基准提供了标准化的设置和指标，用于评估语言模型的数据生成能力。通过利用 6 个语言模型合成 126 万个训练实例，并训练 99 个学生模型，我们获得了有关语言模型数据生成能力的关键洞察。首先，我们发现语言模型各有优势。比如，GPT-4o 善于生成新问题，而 Claude-3.5-Sonnet 在优化现有问题方面表现更优。而且，我们的分析显示，语言模型的数据生成能力未必与解决问题的能力相关。相反，数据质量的多个内在特征，包括响应质量、困惑度和指令难度等，共同构成了更好的衡量指标。最后，我们证实，输出格式的策略选择以及注重成本的模型挑选对数据生成效果有着显著影响。

> 
Abstract:Given the increasing use of synthetic data in language model (LM) post-training, an LM's ability to generate high-quality data has become nearly as crucial as its ability to solve problems directly. While prior works have focused on developing effective data generation methods, they lack systematic comparison of different LMs as data generators in a unified setting. To address this gap, we propose AgoraBench, a benchmark that provides standardized settings and metrics to evaluate LMs' data generation abilities. Through synthesizing 1.26 million training instances using 6 LMs and training 99 student models, we uncover key insights about LMs' data generation capabilities. First, we observe that LMs exhibit distinct strengths. For instance, GPT-4o excels at generating new problems, while Claude-3.5-Sonnet performs better at enhancing existing ones. Furthermore, our analysis reveals that an LM's data generation ability doesn't necessarily correlate with its problem-solving ability. Instead, multiple intrinsic features of data quality-including response quality, perplexity, and instruction difficulty-collectively serve as better indicators. Finally, we demonstrate that strategic choices in output format and cost-conscious model selection significantly impact data generation effectiveness.
    

[Arxiv](https://arxiv.org/pdf/2412.03679)