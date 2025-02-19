# # 系统提示稳健性：深入探究

发布时间：2025年02月15日

`LLM应用` `生成模型`

> A Closer Look at System Prompt Robustness

# 摘要

> 系统提示已成为在聊天和代理环境中控制大型语言模型（LLMs）行为的关键界面。开发者依赖它来指定上下文、格式、个性、护栏、政策和安全措施，尤其在面对冲突或对抗性输入时，模型需 robustly 遵循这些提示。然而，模型常忽略护栏或无法调和系统与用户间的冲突。本研究基于从 OpenAI 的 GPT Store 和 HuggingFace 的 HuggingChat 收集的提示，创建了新的评估和微调数据集，探索提升系统提示健壮性的方法。实验显示，通过现实的微调数据和推理时的干预（如无分类器引导），模型性能显著提升。分析 OpenAI 和 DeepSeek 的新推理模型发现，它们在基准测试中表现不一。总体而言，现有技术尚未完全确保系统提示的健壮性，进一步研究势在必行。

> System prompts have emerged as a critical control surface for specifying the behavior of LLMs in chat and agent settings. Developers depend on system prompts to specify important context, output format, personalities, guardrails, content policies, and safety countermeasures, all of which require models to robustly adhere to the system prompt, especially when facing conflicting or adversarial user inputs. In practice, models often forget to consider relevant guardrails or fail to resolve conflicting demands between the system and the user. In this work, we study various methods for improving system prompt robustness by creating realistic new evaluation and fine-tuning datasets based on prompts collected from from OpenAI's GPT Store and HuggingFace's HuggingChat. Our experiments assessing models with a panel of new and existing benchmarks show that performance can be considerably improved with realistic fine-tuning data, as well as inference-time interventions such as classifier-free guidance. Finally, we analyze the results of recently released reasoning models from OpenAI and DeepSeek, which show exciting but uneven improvements on the benchmarks we study. Overall, current techniques fall short of ensuring system prompt robustness and further study is warranted.

[Arxiv](https://arxiv.org/abs/2502.12197)