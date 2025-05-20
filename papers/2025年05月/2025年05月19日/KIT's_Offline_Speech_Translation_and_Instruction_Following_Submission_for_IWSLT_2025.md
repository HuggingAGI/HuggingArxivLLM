# 卡尔斯鲁厄理工学院在IWSLT 2025中的离线语音翻译与指令遵循提交方案

发布时间：2025年05月19日

`LLM应用` `语音翻译` `指令遵循`

> KIT's Offline Speech Translation and Instruction Following Submission for IWSLT 2025

# 摘要

> 国际语音翻译研讨会（IWSLT）的范围 recently扩展到超越传统的语音翻译（ST），涵盖更广泛的任务，包括语音问答和总结。这一转变部分是由现代系统日益增长的能力推动的，特别是大型语言模型（LLMs）的成功。在本文中，我们介绍了卡尔斯鲁厄理工学院在离线语音翻译和指令遵循（IF）赛道上的提交，其中我们利用LLMs来提升所有任务的性能。对于离线语音翻译赛道，我们提出了一种 pipeline，采用多个自动语音识别系统，其输出通过具备文档级上下文理解能力的LLM进行融合。随后是一个两步翻译过程，其中包括额外的优化步骤以提高翻译质量。对于IF赛道，我们开发了一个端到端模型，将语音编码器与LLM集成，以执行各种指令遵循任务。我们还通过利用上下文信息添加了一个最终的文档级优化阶段，以进一步提升输出质量。

> The scope of the International Workshop on Spoken Language Translation (IWSLT) has recently broadened beyond traditional Speech Translation (ST) to encompass a wider array of tasks, including Speech Question Answering and Summarization. This shift is partly driven by the growing capabilities of modern systems, particularly with the success of Large Language Models (LLMs). In this paper, we present the Karlsruhe Institute of Technology's submissions for the Offline ST and Instruction Following (IF) tracks, where we leverage LLMs to enhance performance across all tasks. For the Offline ST track, we propose a pipeline that employs multiple automatic speech recognition systems, whose outputs are fused using an LLM with document-level context. This is followed by a two-step translation process, incorporating additional refinement step to improve translation quality. For the IF track, we develop an end-to-end model that integrates a speech encoder with an LLM to perform a wide range of instruction-following tasks. We complement it with a final document-level refinement stage to further enhance output quality by using contextual information.

[Arxiv](https://arxiv.org/abs/2505.13036)