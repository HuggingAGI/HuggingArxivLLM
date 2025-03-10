# # ORANSight-2.0：专为O-RAN打造的基石型大型语言模型

发布时间：2025年03月07日

`LLM应用` `无线网络`

> ORANSight-2.0: Foundational LLMs for O-RAN

# 摘要

> 尽管大型语言模型（LLMs）在医疗、客服和商业营销等领域掀起了一场变革风暴，但在开放无线接入网络（O-RAN）领域的应用却显得姗姗来迟。这一现象的背后，是现有解决方案过分依赖通用LLMs，却忽视了O-RAN独特挑战与技术细节的现实。为突破这一瓶颈，我们推出了ORANSight-2.0（O-RAN Insights），一个致力于打造O-RAN专用基础LLMs的开创性计划。ORANSight-2.0基于跨越五个开源框架的18个LLMs构建，对参数规模从1B到70B的模型进行了精心微调，不仅显著降低了对专有闭源模型的依赖，更在O-RAN领域实现了性能质的飞跃。其核心RANSTRUCT框架，通过创新的检索增强生成（RAG）技术，巧妙运用两个LLM代理构建高质量指令微调数据集。随后，借助QLoRA技术对开源LLMs进行深度优化。为了全面评估ORANSight-2.0的实力，我们推出了srsRANBench基准测试，专注于评估其在5G O-RAN环境中的代码生成与理解能力。同时，我们也借助ORANBench13K基准，深入考察其在O-RAN知识掌握上的表现。实验结果令人振奋：在ORANBench上，ORANSight-2.0较ChatGPT-4o和Gemini等通用及闭源模型高出5.421%；在srsRANBench上，更是取得了18.465%的显著优势。这一切成就，均在保持较低计算与能源成本的前提下实现。此外，我们还探索了RAG增强的ORANSight-2.0 LLM变体，并对其能源特性进行了全面评估，详细展示了训练、标准推理及RAG增强推理的能耗表现。

> Despite the transformative impact of Large Language Models (LLMs) across critical domains such as healthcare, customer service, and business marketing, their integration into Open Radio Access Networks (O-RAN) remains limited. This gap is primarily due to the absence of domain-specific foundational models, with existing solutions often relying on general-purpose LLMs that fail to address the unique challenges and technical intricacies of O-RAN. To bridge this gap, we introduce ORANSight-2.0 (O-RAN Insights), a pioneering initiative aimed at developing specialized foundational LLMs tailored for O-RAN. Built on 18 LLMs spanning five open-source LLM frameworks, ORANSight-2.0 fine-tunes models ranging from 1 to 70B parameters, significantly reducing reliance on proprietary, closed-source models while enhancing performance for O-RAN. At the core of ORANSight-2.0 is RANSTRUCT, a novel Retrieval-Augmented Generation (RAG) based instruction-tuning framework that employs two LLM agents to create high-quality instruction-tuning datasets. The generated dataset is then used to fine-tune the 18 pre-trained open-source LLMs via QLoRA. To evaluate ORANSight-2.0, we introduce srsRANBench, a novel benchmark designed for code generation and codebase understanding in the context of srsRAN, a widely used 5G O-RAN stack. We also leverage ORANBench13K, an existing benchmark for assessing O-RAN-specific knowledge. Our comprehensive evaluations demonstrate that ORANSight-2.0 models outperform general-purpose and closed-source models, such as ChatGPT-4o and Gemini, by 5.421% on ORANBench and 18.465% on srsRANBench, achieving superior performance while maintaining lower computational and energy costs. We also experiment with RAG-augmented variants of ORANSight-2.0 LLMs and thoroughly evaluate their energy characteristics, demonstrating costs for training, standard inference, and RAG-augmented inference.

[Arxiv](https://arxiv.org/abs/2503.05200)