# 评测大型语言模型安全方案的有效性：帕利特基准数据集

发布时间：2025年05月19日

`LLM应用`

> Evaluatiing the efficacy of LLM Safety Solutions : The Palit Benchmark Dataset

# 摘要

> 大型语言模型（LLMs）正逐步融入医疗保健和金融等关键行业。用户可通过启用 LLM 的聊天机器人提交查询，部分机器人能从存储敏感数据的内部数据库中检索信息，从而丰富响应内容。这种能力也带来了新的风险：恶意用户可能通过提交有害查询，使系统输出泄露内部数据或损害第三方利益的响应，从而引发法律问题。尽管安全工具正在研发中以应对这些威胁，但目前缺乏对其有效性和可用性的正式评估。本研究通过全面比较分析 LLM 安全工具，填补了这一空白。我们识别了 13 种解决方案（9 个闭源，4 个开源），但由于专有模型所有者缺乏参与，最终仅评估了 7 种工具。为进行评估，我们构建了一个恶意提示的基准数据集，并将这些工具的表现与基线 LLM 模型（ChatGPT-3.5-Turbo）进行了对比。结果显示，基线模型误报过多，无法满足任务需求。Lakera Guard 和 ProtectAI LLM Guard 作为整体最佳工具脱颖而出，展示了在可用性和性能之间的平衡。研究最后提出了多项建议，包括推动闭源提供商的透明度、提升上下文感知检测能力、加强开源协作、提高用户安全意识以及采用更具代表性的性能评估指标。

> Large Language Models (LLMs) are increasingly integrated into critical systems in industries like healthcare and finance. Users can often submit queries to LLM-enabled chatbots, some of which can enrich responses with information retrieved from internal databases storing sensitive data. This gives rise to a range of attacks in which a user submits a malicious query and the LLM-system outputs a response that creates harm to the owner, such as leaking internal data or creating legal liability by harming a third-party. While security tools are being developed to counter these threats, there is little formal evaluation of their effectiveness and usability. This study addresses this gap by conducting a thorough comparative analysis of LLM security tools. We identified 13 solutions (9 closed-source, 4 open-source), but only 7 were evaluated due to a lack of participation by proprietary model owners.To evaluate, we built a benchmark dataset of malicious prompts, and evaluate these tools performance against a baseline LLM model (ChatGPT-3.5-Turbo). Our results show that the baseline model has too many false positives to be used for this task. Lakera Guard and ProtectAI LLM Guard emerged as the best overall tools showcasing the tradeoff between usability and performance. The study concluded with recommendations for greater transparency among closed source providers, improved context-aware detections, enhanced open-source engagement, increased user awareness, and the adoption of more representative performance metrics.

[Arxiv](https://arxiv.org/abs/2505.13028)