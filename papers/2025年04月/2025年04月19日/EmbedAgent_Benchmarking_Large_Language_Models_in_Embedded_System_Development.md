# EmbedAgent：嵌入式系统开发中大型语言模型的基准测试

发布时间：2025年04月19日

`LLM应用` `嵌入式系统` `电子工程`

> EmbedAgent: Benchmarking Large Language Models in Embedded System Development

# 摘要

> 大型语言模型（LLMs）在多种任务中展现潜力，但在嵌入式系统开发领域的评估却鲜有基准。本文提出EmbedAgent，一种模拟嵌入式系统开发中实际角色（如程序员、架构师和集成商）的范式。该范式使LLMs能够通过跨越数字与物理系统鸿沟的任务进行测试，从而更全面地评估其能力。为了评估LLMs的表现，我们推出首个全面基准测试Embedbench，涵盖嵌入式编程、电路设计和跨平台迁移。Embedbench包含126个测试用例，覆盖3个硬件平台的9种电子元件。通过对10个主流LLMs的实验，我们发现：尽管测试用例简单，DeepSeek-R1在提供原理图时通过率仅55.6%，自行生成原理图时更低至50.0%。在跨平台迁移中，LLMs在Raspberry Pi Pico的MicroPython上表现尚可（最佳模型73.8%通过率），但在ESP-IDF上表现欠佳，最佳模型仅29.4%通过率。有趣的是，通用聊天LLMs如DeepSeek-V3难以有效利用该领域知识，而推理型LLMs则过度思考并忽视高效知识。为此，我们提出检索增强生成和编译器反馈两大策略，使Deepseek-R1在正确原理图下的通过率提升至65.1%，无原理图时也达53.1%。此外，Arduino到ESP32的迁移任务准确率从21.4%提升至27.8%。

> Large Language Models (LLMs) have shown promise in various tasks, yet few benchmarks assess their capabilities in embedded system development.In this paper, we introduce EmbedAgent, a paradigm designed to simulate real-world roles in embedded system development, such as Embedded System Programmer, Architect, and Integrator. This paradigm enables LLMs to be tested in tasks that bridge the gap between digital and physical systems, allowing for a more comprehensive assessment of their capabilities. To evaluate LLMs on these tasks, we propose Embedbench, the first comprehensive benchmark for embedded system programming, circuit design, and cross-platform migration.Embedbench consists of 126 cases, covering 9 electronic components across 3 hardware platforms. Through extensive experiments on 10 mainstream LLMs, we uncover several key findings. Surprisingly, despite the simplicity of the cases, DeepSeek-R1 achieves only a 55.6% pass@1 rate when provided with schematic information, and 50.0% when tasked with generating the schematics itself. In the cross-platform migration tasks, LLMs show relatively strong performance with MicroPython on the Raspberry Pi Pico (with the top model achieving 73.8% pass@1), but perform poorly on ESP-IDF, where the best model reaches only 29.4% pass@1.Interestingly, we observe that general-purpose chat LLMs like DeepSeek-V3 often fail to utilize relevant pre-trained knowledge in this domain, while reasoning LLMs tend to overthink and overlook efficient knowledge during pretraining. Based on these insights, we propose two strategies: retrieval augmented generation and compiler feedback-to enhance LLM performance. These strategies result in significant improvements, with Deepseek-R1 reaching a 65.1% pass@1 with correct schematics, and 53.1% without. Additionally, the accuracy of the Arduino to ESP32 migration task improves from 21.4% to 27.8%.

[Arxiv](https://arxiv.org/abs/2506.11003)