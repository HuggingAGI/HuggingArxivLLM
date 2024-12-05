# 提升 LLMs 的函数调用能力：有关提示格式、数据集成与多语言翻译的策略

发布时间：2024年12月03日

`LLM应用` `自主代理` `多语言应用`

> Enhancing Function-Calling Capabilities in LLMs: Strategies for Prompt Formats, Data Integration, and Multilingual Translation

# 摘要

> 大型语言模型（LLMs）在自主代理方面取得了显著进步，尤其是在零样本工具使用（即函数调用）方面。本研究通过探索多种不同方法来增强 LLMs 的函数调用能力，比如用于整合函数描述的提示格式、融合函数调用与指令遵循数据、引入新的决策令牌用于条件提示、利用思维链推理以及借助翻译管道克服多语言挑战。我们的主要发现和贡献如下：（1）指令遵循数据能提高函数调用的准确性和相关性检测。（2）新提出的决策令牌与合成的非函数调用数据相结合，可增强相关性检测。（3）定制的翻译管道能有效克服多语言限制，在繁体中文方面有显著改进。这些见解凸显了 LLMs 在提升函数调用能力和多语言应用方面的潜力。

> Large language models (LLMs) have significantly advanced autonomous agents, particularly in zero-shot tool usage, also known as function calling. This research delves into enhancing the function-calling capabilities of LLMs by exploring different approaches, including prompt formats for integrating function descriptions, blending function-calling and instruction-following data, introducing a novel Decision Token for conditional prompts, leveraging chain-of-thought reasoning, and overcoming multilingual challenges with a translation pipeline. Our key findings and contributions are as follows: (1) Instruction-following data improves both function-calling accuracy and relevance detection. (2) The use of the newly proposed Decision Token, combined with synthetic non-function-call data, enhances relevance detection. (3) A tailored translation pipeline effectively overcomes multilingual limitations, demonstrating significant improvements in Traditional Chinese. These insights highlight the potential for improved function-calling capabilities and multilingual applications in LLMs.

[Arxiv](https://arxiv.org/abs/2412.01130)