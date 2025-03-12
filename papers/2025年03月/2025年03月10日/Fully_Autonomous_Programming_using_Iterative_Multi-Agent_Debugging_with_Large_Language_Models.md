# 完全自主编程：借助大型语言模型实现迭代多智能体调试

发布时间：2025年03月10日

`LLM应用` `软件工程` `人工智能`

> Fully Autonomous Programming using Iterative Multi-Agent Debugging with Large Language Models

# 摘要

> 基于大型语言模型（LLMs）的程序合成面临一个“近失综合征”：生成的代码看似正确，但却因细微错误而无法通过单元测试。我们提出了一种名为合成、执行、指导、调试与修复（SEIDR）的多智能体框架来解决这一问题。

要有效将SEIDR应用于指令微调的LLMs，需要确定以下几点：(a) LLMs的最佳提示语，(b) 在调试轮次中选择最优程序的排序算法，以及(c) 在修复失败程序与生成新程序之间取得平衡。

我们通过比较专注于替换、修复及混合调试策略，实证探索了这些权衡。我们还评估了lexicase和锦标赛选择算法来对每一代候选程序进行排序。

在程序合成基准测试2（PSB2）上，我们的框架优于不带修复阶段的OpenAI Codex常规使用方法，同时也超越了传统的遗传编程方法。SEIDR在仅使用LLM时表现更优，在PSB2上至少一次解决了18个C++问题和20个Python问题。

为了评估通用性，我们在PSB2和HumanEval-X基准测试中采用了GPT-3.5和Llama 3。尽管SEIDR与这些模型在Python基准测试中未能超越当前最先进方法，但在HumanEval-C++上的结果令人鼓舞。使用Llama 3-8B的SEIDR在HumanEval-C++上达到了84.2%的平均通过率@100。

在所有SEIDR实验中，GPT-3.5解决了HumanEval-C++中的163个问题，而较小的Llama 3-8B解决了162个问题。我们得出结论：SEIDR有效克服了LLMs在程序合成中的近失综合征。

> Program synthesis with Large Language Models (LLMs) suffers from a "near-miss syndrome": the generated code closely resembles a correct solution but fails unit tests due to minor errors. We address this with a multi-agent framework called Synthesize, Execute, Instruct, Debug, and Repair (SEIDR). Effectively applying SEIDR to instruction-tuned LLMs requires determining (a) optimal prompts for LLMs, (b) what ranking algorithm selects the best programs in debugging rounds, and (c) balancing the repair of unsuccessful programs with the generation of new ones. We empirically explore these trade-offs by comparing replace-focused, repair-focused, and hybrid debug strategies. We also evaluate lexicase and tournament selection to rank candidates in each generation. On Program Synthesis Benchmark 2 (PSB2), our framework outperforms both conventional use of OpenAI Codex without a repair phase and traditional genetic programming approaches. SEIDR outperforms the use of an LLM alone, solving 18 problems in C++ and 20 in Python on PSB2 at least once across experiments. To assess generalizability, we employ GPT-3.5 and Llama 3 on the PSB2 and HumanEval-X benchmarks. Although SEIDR with these models does not surpass current state-of-the-art methods on the Python benchmarks, the results on HumanEval-C++ are promising. SEIDR with Llama 3-8B achieves an average pass@100 of 84.2%. Across all SEIDR runs, 163 of 164 problems are solved at least once with GPT-3.5 in HumanEval-C++, and 162 of 164 with the smaller Llama 3-8B. We conclude that SEIDR effectively overcomes the near-miss syndrome in program synthesis with LLMs.

[Arxiv](https://arxiv.org/abs/2503.07693)