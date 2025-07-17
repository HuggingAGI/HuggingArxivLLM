# DrafterBench：土木工程任务自动化领域的大型语言模型基准测试

发布时间：2025年07月15日

`LLM应用` `土木工程` `工业自动化`

> DrafterBench: Benchmarking Large Language Models for Tasks Automation in Civil Engineering

# 摘要

> 大型语言模型（LLM）代理在解决实际问题方面展现出巨大潜力，并有望成为工业任务自动化的解决方案。然而，为了从工业视角系统性评估自动化代理（例如在土木工程领域），仍需更多的基准测试。因此，我们提出了DrafterBench，用于在技术图纸修订这一土木工程代表性任务中，全面评估LLM代理的能力。

DrafterBench包含从真实图纸文件中总结出的十二种任务类型，总计46个定制化功能/工具和1920个任务。作为一个开源基准测试工具，DrafterBench旨在严格测试AI代理在理解复杂长上下文指令、利用先验知识以及通过隐式策略感知适应动态指令质量方面的能力。该工具全面评估了代理在结构化数据理解、功能执行、指令遵循和批判性推理等方面的不同能力。

DrafterBench提供了任务准确性和错误统计的详细分析，旨在深入洞察代理能力，并为将LLMs整合到工程应用中确定改进目标。我们的基准测试可在https://github.com/Eason-Li-AIS/DrafterBench获取，测试集托管于https://huggingface.co/datasets/Eason666/DrafterBench。

> Large Language Model (LLM) agents have shown great potential for solving real-world problems and promise to be a solution for tasks automation in industry. However, more benchmarks are needed to systematically evaluate automation agents from an industrial perspective, for example, in Civil Engineering. Therefore, we propose DrafterBench for the comprehensive evaluation of LLM agents in the context of technical drawing revision, a representation task in civil engineering. DrafterBench contains twelve types of tasks summarized from real-world drawing files, with 46 customized functions/tools and 1920 tasks in total. DrafterBench is an open-source benchmark to rigorously test AI agents' proficiency in interpreting intricate and long-context instructions, leveraging prior knowledge, and adapting to dynamic instruction quality via implicit policy awareness. The toolkit comprehensively assesses distinct capabilities in structured data comprehension, function execution, instruction following, and critical reasoning. DrafterBench offers detailed analysis of task accuracy and error statistics, aiming to provide deeper insight into agent capabilities and identify improvement targets for integrating LLMs in engineering applications. Our benchmark is available at https://github.com/Eason-Li-AIS/DrafterBench, with the test set hosted at https://huggingface.co/datasets/Eason666/DrafterBench.

[Arxiv](https://arxiv.org/abs/2507.11527)