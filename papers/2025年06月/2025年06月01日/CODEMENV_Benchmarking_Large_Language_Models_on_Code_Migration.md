# CODEMENV：针对代码迁移任务的大型语言模型评估基准测试

发布时间：2025年06月01日

`LLM应用` `软件工程`

> CODEMENV: Benchmarking Large Language Models on Code Migration

# 摘要

> 大型语言模型（LLMs）在软件工程领域展现了卓越的能力，但在代码迁移任务中，其表现仍有待深入研究。本研究推出CODEMENV：跨环境代码迁移基准，专为评估LLMs在代码迁移场景中的能力而设计。CODEMENV包含922个示例，覆盖19个Python和Java包，涉及三大核心任务：识别与特定版本不兼容的函数、检测函数定义变更、以及将代码适配至目标环境。实验中，我们对七种LLMs进行了评估，平均通过率@1为26.50%，其中GPT-4O表现最佳，达43.84%。研究发现：LLMs在处理较新函数版本时更为熟练，有助于旧版代码迁移；但有时会因识别与目标环境无关的函数变更而出现逻辑不一致。数据集已开源，访问地址为https://github.com/xdshen-ai/Benchmark-of-Code-Migration。

> Large language models (LLMs) have shown remarkable capabilities across various software engineering tasks; however, their effectiveness in code migration, adapting code to run in different environments, remains insufficiently studied. In this work, we introduce CODEMENV: Code Migration Across Environment, a new benchmark specifically designed to assess LLMs' abilities in code migration scenarios. CODEMENV consists of 922 examples spanning 19 Python and Java packages, and covers three core tasks: (1) identifying functions incompatible with specific versions, (2) detecting changes in function definitions, and (3) adapting code to target environments. Experimental evaluation with seven LLMs on CODEMENV yields an average pass@1 rate of 26.50%, with GPT-4O achieving the highest score at 43.84%. Key findings include: (i) LLMs tend to be more proficient with newer function versions, which aids in migrating legacy code, and (ii) LLMs sometimes exhibit logical inconsistencies by identifying function changes irrelevant to the intended migration environment. The datasets are available at https://github.com/xdshen-ai/Benchmark-of-Code-Migration.

[Arxiv](https://arxiv.org/abs/2506.00894)