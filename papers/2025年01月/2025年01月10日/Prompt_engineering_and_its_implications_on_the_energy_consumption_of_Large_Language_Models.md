# 提示工程与大型语言模型能耗的关系

发布时间：2025年01月10日

`LLM应用` `软件工程` `环境科学`

> Prompt engineering and its implications on the energy consumption of Large Language Models

# 摘要

> 降低AI软件系统的环境影响已成为当务之急。LLMs在软件工程中的广泛应用对计算资源、数据中心和碳排放带来了巨大挑战。本文探讨了提示工程技术（PETs）如何影响Llama 3模型在代码生成任务中的碳排放。我们通过CodeXGLUE基准实验，在隔离环境中评估了代码生成的能耗和准确性。初步结果显示，使用特定标签区分提示部分可有效降低LLMs的能耗。尽管还需进一步验证，但研究表明，提示工程能在不牺牲性能的前提下减少LLMs推理阶段的能耗，为后续研究开辟了新方向。

> Reducing the environmental impact of AI-based software systems has become critical. The intensive use of large language models (LLMs) in software engineering poses severe challenges regarding computational resources, data centers, and carbon emissions. In this paper, we investigate how prompt engineering techniques (PETs) can impact the carbon emission of the Llama 3 model for the code generation task. We experimented with the CodeXGLUE benchmark to evaluate both energy consumption and the accuracy of the generated code using an isolated testing environment. Our initial results show that the energy consumption of LLMs can be reduced by using specific tags that distinguish different prompt parts. Even though a more in-depth evaluation is needed to confirm our findings, this work suggests that prompt engineering can reduce LLMs' energy consumption during the inference phase without compromising performance, paving the way for further investigations.

[Arxiv](https://arxiv.org/abs/2501.05899)