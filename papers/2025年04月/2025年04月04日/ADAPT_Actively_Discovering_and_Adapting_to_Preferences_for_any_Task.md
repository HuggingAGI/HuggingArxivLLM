# ADAPT：主动发现并适应任何任务的偏好

发布时间：2025年04月04日

`Agent` `智能家居` `家庭自动化`

> ADAPT: Actively Discovering and Adapting to Preferences for any Task

# 摘要

> 辅助型智能体应在尊重用户偏好的同时，能够执行那些目标不明确且需要长期完成的任务。我们引入了“主动发现和适应任何任务的偏好”（ADAPT）基准测试，旨在评估智能体在通过主动提问的情况下，能否在各种家庭任务中遵循用户的偏好。接下来，我们提出了“反思式DPO”（Reflection-DPO），这是一种用于训练大型语言模型（LLMs）以适应主动提问任务的新方法。Reflection-DPO通过微调一个“学生”LLM，使其能够效仿一个具有特权的“教师”LLM的动作，并在必要时提出问题以获取更多信息，从而更好地预测教师的动作。我们发现，先前的方法使用最先进的LLMs时，在ADAPT基准测试中未能充分遵循用户偏好，主要原因是提问不足以及对已获取偏好的遵循效果不佳。相比之下，Reflection-DPO在满足用户偏好方面表现更佳，与零样本链式思考基线相比，在未见过的用户上提升了6.1%的性能。

> Assistive agents should be able to perform under-specified long-horizon tasks while respecting user preferences. We introduce Actively Discovering and Adapting to Preferences for any Task (ADAPT) -- a benchmark designed to evaluate agents' ability to adhere to user preferences across various household tasks through active questioning. Next, we propose Reflection-DPO, a novel training approach for adapting large language models (LLMs) to the task of active questioning. Reflection-DPO finetunes a 'student' LLM to follow the actions of a privileged 'teacher' LLM, and optionally ask a question to gather necessary information to better predict the teacher action. We find that prior approaches that use state-of-the-art LLMs fail to sufficiently follow user preferences in ADAPT due to insufficient questioning and poor adherence to elicited preferences. In contrast, Reflection-DPO achieves a higher rate of satisfying user preferences, outperforming a zero-shot chain-of-thought baseline by 6.1% on unseen users.

[Arxiv](https://arxiv.org/abs/2504.04040)