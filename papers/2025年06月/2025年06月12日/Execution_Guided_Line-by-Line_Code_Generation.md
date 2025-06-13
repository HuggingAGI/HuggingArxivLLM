# 基于执行引导的逐行代码生成

发布时间：2025年06月12日

`LLM应用` `软件工程`

> Execution Guided Line-by-Line Code Generation

# 摘要

> 我们提出了一种新型神经代码生成方法，通过将实时执行信号整合到语言模型生成过程中，显著提升了代码生成的效果。虽然大型语言模型（LLMs）展现了强大的代码生成能力，但它们通常忽略了执行反馈这一关键信号，而这是人类程序员常用的重要信息来源。我们的方法——执行引导的无分类器自由引导（EG-CFG）——在生成代码时动态地整合执行信号，提供逐行反馈，引导生成过程走向可执行的解决方案。

EG-CFG采用以下三阶段流程：
1. 首先，我们进行束搜索，为每一行代码生成候选程序补全；
2. 其次，我们通过将这些候选代码与测试用例进行执行，提取执行信号；
3. 最后，我们在生成过程中将这些信号整合到提示中。

通过在同一行内的标记中保持一致的信号，并在行末刷新信号，我们的方法提供了连贯的指导，同时保留了语法结构。此外，该方法天然支持任务级别的原生并行，在这种情况下，多个代理并行运行，探索多样化的推理路径，共同生成广泛的候选解决方案。

我们在多样化的编码任务上的实验表明，与标准方法相比，EG-CFG显著提升了代码生成性能，在从基础问题到具有挑战性的竞赛编程任务的各种复杂性水平上均达到了最先进的结果。我们的代码可在以下链接获取：【链接】

> We present a novel approach to neural code generation that incorporates real-time execution signals into the language model generation process. While large language models (LLMs) have demonstrated impressive code generation capabilities, they typically do not utilize execution feedback during inference, a critical signal that human programmers regularly leverage. Our method, Execution-Guided Classifier-Free Guidance (EG-CFG), dynamically incorporates execution signals as the model generates code, providing line-by-line feedback that guides the generation process toward executable solutions. EG-CFG employs a multi-stage process: first, we conduct beam search to sample candidate program completions for each line; second, we extract execution signals by executing these candidates against test cases; and finally, we incorporate these signals into the prompt during generation. By maintaining consistent signals across tokens within the same line and refreshing signals at line boundaries, our approach provides coherent guidance while preserving syntactic structure. Moreover, the method naturally supports native parallelism at the task level in which multiple agents operate in parallel, exploring diverse reasoning paths and collectively generating a broad set of candidate solutions. Our experiments across diverse coding tasks demonstrate that EG-CFG significantly improves code generation performance compared to standard approaches, achieving state-of-the-art results across various levels of complexity, from foundational problems to challenging competitive programming tasks. Our code is available at: https://github.com/boazlavon/eg_cfg

[Arxiv](https://arxiv.org/abs/2506.10948)