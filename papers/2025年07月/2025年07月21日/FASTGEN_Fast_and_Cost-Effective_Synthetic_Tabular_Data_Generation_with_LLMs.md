# FASTGEN：高效且经济的合成表格数据生成方案，利用LLMs实现

发布时间：2025年07月21日

`LLM应用` `数据工程` `软件工程`

> FASTGEN: Fast and Cost-Effective Synthetic Tabular Data Generation with LLMs

# 摘要

> 合成数据生成在现实世界数据受限的场景中应运而生，成为了一种不可或缺的解决方案。大型语言模型（LLMs）在跨领域生成高保真、领域相关的样本方面展现出了非凡的能力。然而，现有方法直接利用LLMs逐条生成记录的方式在时间和成本上都难以承受，尤其是在需要大量合成数据的情况下。在本研究中，我们提出了一种快速、经济的解决方案，用于生成现实的表格数据。该方法通过LLMs推断并编码每个字段的分布，生成可重用的抽样脚本。通过自动将字段分类为数值型、类别型或自由文本型，LLMs能够生成基于分布的脚本，从而在无需持续模型推理的情况下，高效生成多样化的、现实的数据集。实验结果表明，与传统的直接方法相比，我们的方法在数据多样性和真实性方面均表现更优，显著降低了大规模合成数据生成的负担。我们计划将此方法应用于加速生产管道中的测试流程，从而缩短开发周期并提升整体系统效率。我们相信，我们的见解和经验将为研究人员和从业人员提供有价值的参考，帮助他们寻找可扩展且经济的合成数据生成解决方案。

> Synthetic data generation has emerged as an invaluable solution in scenarios where real-world data collection and usage are limited by cost and scarcity. Large language models (LLMs) have demonstrated remarkable capabilities in producing high-fidelity, domain-relevant samples across various fields. However, existing approaches that directly use LLMs to generate each record individually impose prohibitive time and cost burdens, particularly when large volumes of synthetic data are required. In this work, we propose a fast, cost-effective method for realistic tabular data synthesis that leverages LLMs to infer and encode each field's distribution into a reusable sampling script. By automatically classifying fields into numerical, categorical, or free-text types, the LLM generates distribution-based scripts that can efficiently produce diverse, realistic datasets at scale without continuous model inference. Experimental results show that our approach outperforms traditional direct methods in both diversity and data realism, substantially reducing the burden of high-volume synthetic data generation. We plan to apply this methodology to accelerate testing in production pipelines, thereby shortening development cycles and improving overall system efficiency. We believe our insights and lessons learned will aid researchers and practitioners seeking scalable, cost-effective solutions for synthetic data generation.

[Arxiv](https://arxiv.org/abs/2507.15839)