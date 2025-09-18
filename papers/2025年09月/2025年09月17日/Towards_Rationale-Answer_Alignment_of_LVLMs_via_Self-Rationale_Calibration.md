# 通过自推理校准实现大型视觉语言模型的推理-答案对齐

发布时间：2025年09月17日

`LLM应用` `基础理论`

> Towards Rationale-Answer Alignment of LVLMs via Self-Rationale Calibration

# 摘要

> 大型视觉语言模型（LVLMs）展现出了强大的视觉问答能力，但在对齐推理依据与生成答案方面仍存在挑战，进而造成推理矛盾与答案错误。为此，本文提出自推理依据校准（SRC）框架，通过迭代方式校准推理依据与答案的对齐关系。SRC首先采用轻量级的“推理依据微调”策略，修改模型的响应格式，使其在无需显式提示时，自动在生成答案前先输出推理依据。接着，SRC为每个样本从微调后的LVLMs中搜索多样化的候选响应集，然后通过定制评分模型R-Scorer实现成对评分策略，同时评估候选响应的推理依据质量与事实一致性。基于置信度加权的偏好筛选流程，SRC将对齐校准转化为偏好微调任务，最终使LVLMs在多个基准测试中的感知、推理及泛化能力均获显著提升。研究结果表明，面向推理依据的对齐是充分释放LVLMs潜力的关键。

> Large Vision-Language Models (LVLMs) have manifested strong visual question answering capability. However, they still struggle with aligning the rationale and the generated answer, leading to inconsistent reasoning and incorrect responses. To this end, this paper introduces the Self-Rationale Calibration (SRC) framework to iteratively calibrate the alignment between rationales and answers. SRC begins by employing a lightweight "rationale fine-tuning" approach, which modifies the model's response format to require a rationale before deriving an answer without explicit prompts. Next, SRC searches for a diverse set of candidate responses from the fine-tuned LVLMs for each sample, followed by a proposed pairwise scoring strategy using a tailored scoring model, R-Scorer, to evaluate both rationale quality and factual consistency of candidates. Based on a confidence-weighted preference curation process, SRC decouples the alignment calibration into a preference fine-tuning manner, leading to significant improvements of LVLMs in perception, reasoning, and generalization across multiple benchmarks. Our results emphasize the rationale-oriented alignment in exploring the potential of LVLMs.

[Arxiv](https://arxiv.org/abs/2509.13919)