# # 大型语言模型的心理理论能力局限：情境对话中心理状态标注的评估

发布时间：2025年09月02日

`LLM应用` `基础理论`

> LLMs and their Limited Theory of Mind: Evaluating Mental State Annotations in Situated Dialogue

# 摘要

> 要是大型语言模型不仅能推断人类思维模式，还能揪出团队对话中的所有盲点——比如成员间共同理解的偏差，那会怎样？为此，我们提出一种新颖的两步框架：将大型语言模型（LLMs）同时打造成“类人标注员”与“差异侦探”——前者负责标注团队对话以追踪共享心理模型（SMMs），后者则自动检测个体心理状态间的差异。第一步，LLM从协作远程搜索任务（CReST）语料库的任务导向对话中识别SMM元素，进而生成标注。第二步，另一LLM将这些LLM生成的标注及人工标注与黄金标准标签比对，从而检测并描述差异特征。我们针对该场景构建了SMM一致性评估框架，并将其应用于6段CReST对话，最终产出三项成果：（1）人工与LLM标注数据集；（2）可复现的SMM一致性评估框架；（3）基于LLM的差异检测实证评估。研究结果显示：尽管LLM在简单自然语言标注任务中表现出良好一致性，但在涉及空间推理或韵律线索消歧的场景时，却会出现系统性误差。

> What if large language models could not only infer human mindsets but also expose every blind spot in team dialogue such as discrepancies in the team members' joint understanding? We present a novel, two-step framework that leverages large language models (LLMs) both as human-style annotators of team dialogues to track the team's shared mental models (SMMs) and as automated discrepancy detectors among individuals' mental states. In the first step, an LLM generates annotations by identifying SMM elements within task-oriented dialogues from the Cooperative Remote Search Task (CReST) corpus. Then, a secondary LLM compares these LLM-derived annotations and human annotations against gold-standard labels to detect and characterize divergences. We define an SMM coherence evaluation framework for this use case and apply it to six CReST dialogues, ultimately producing: (1) a dataset of human and LLM annotations; (2) a reproducible evaluation framework for SMM coherence; and (3) an empirical assessment of LLM-based discrepancy detection. Our results reveal that, although LLMs exhibit apparent coherence on straightforward natural-language annotation tasks, they systematically err in scenarios requiring spatial reasoning or disambiguation of prosodic cues.

[Arxiv](https://arxiv.org/abs/2509.02292)