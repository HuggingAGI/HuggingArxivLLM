# 大型语言模型辅助的元优化器：约束进化算法的自动化设计

发布时间：2025年09月16日

`LLM应用` `基础理论`

> Large Language Model-assisted Meta-optimizer for Automated Design of Constrained Evolutionary Algorithm

# 摘要

> 元黑盒优化借助大型语言模型（LLMs）已实现显著突破，但在约束进化优化领域仍有提升空间。为此，我们提出了AwesomeDE方法：将LLMs用作元优化器策略，无需人工干预即可自动生成约束进化算法的更新规则。同时，引入【数学公式】框架以标准化LLM的提示设计流程。该元优化器在多样化的约束优化问题集上完成训练，我们系统分析了提示设计、迭代优化等关键组件对设计质量的影响。实验结果显示，该方法在计算效率与解决方案准确性上均优于现有方法；更值得关注的是，AwesomeDE在不同问题域泛化性良好，展现出广泛的应用前景。本研究为该领域贡献了可扩展的数据驱动方法，实现了自动化约束算法设计，同时也明确了当前局限性及未来研究方向。

> Meta-black-box optimization has been significantly advanced through the use of large language models (LLMs), yet in fancy on constrained evolutionary optimization. In this work, AwesomeDE is proposed that leverages LLMs as the strategy of meta-optimizer to generate update rules for constrained evolutionary algorithm without human intervention. On the meanwhile, $RTO^2H$ framework is introduced for standardize prompt design of LLMs. The meta-optimizer is trained on a diverse set of constrained optimization problems. Key components, including prompt design and iterative refinement, are systematically analyzed to determine their impact on design quality. Experimental results demonstrate that the proposed approach outperforms existing methods in terms of computational efficiency and solution accuracy. Furthermore, AwesomeDE is shown to generalize well across distinct problem domains, suggesting its potential for broad applicability. This research contributes to the field by providing a scalable and data-driven methodology for automated constrained algorithm design, while also highlighting limitations and directions for future work.

[Arxiv](https://arxiv.org/abs/2509.13251)