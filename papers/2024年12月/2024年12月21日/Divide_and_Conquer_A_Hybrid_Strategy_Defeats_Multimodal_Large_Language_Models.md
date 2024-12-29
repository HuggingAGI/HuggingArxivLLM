# “分而治之”：一种混合策略战胜多模态大型语言模型

发布时间：2024年12月21日

`LLM应用` `语言模型`

> Divide and Conquer: A Hybrid Strategy Defeats Multimodal Large Language Models

# 摘要

> 大型语言模型（LLMs）凭借强大的推理、理解和生成能力，在社会众多领域广泛应用。但与之相关的安全问题愈发严峻。越狱攻击作为检测LLMs漏洞的重要手段，已被研究人员探索，他们尝试用各种攻击方法诱导模型生成有害内容。然而，现有的越狱方法存在诸多局限，像查询次数过多、越狱模式覆盖有限、攻击成功率低以及评估方法单一。为突破这些限制，本文提出一种多模态越狱方法：JMLLM。此方法融合多种策略，对文本、视觉和听觉模态展开全面的越狱攻击。另外，我们还为多模态越狱研究提供了一个全新且全面的数据集：TriJail，其中涵盖了这三种模态的越狱提示。针对13个热门LLMs在TriJail数据集和基准数据集AdvBench上开展的实验显示，攻击成功率大幅提升，时间开销显著降低。

> Large language models (LLMs) are widely applied in various fields of society due to their powerful reasoning, understanding, and generation capabilities. However, the security issues associated with these models are becoming increasingly severe. Jailbreaking attacks, as an important method for detecting vulnerabilities in LLMs, have been explored by researchers who attempt to induce these models to generate harmful content through various attack methods. Nevertheless, existing jailbreaking methods face numerous limitations, such as excessive query counts, limited coverage of jailbreak modalities, low attack success rates, and simplistic evaluation methods. To overcome these constraints, this paper proposes a multimodal jailbreaking method: JMLLM. This method integrates multiple strategies to perform comprehensive jailbreak attacks across text, visual, and auditory modalities. Additionally, we contribute a new and comprehensive dataset for multimodal jailbreaking research: TriJail, which includes jailbreak prompts for all three modalities. Experiments on the TriJail dataset and the benchmark dataset AdvBench, conducted on 13 popular LLMs, demonstrate advanced attack success rates and significant reduction in time overhead.

[Arxiv](https://arxiv.org/abs/2412.16555)