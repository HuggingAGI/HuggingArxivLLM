# 大型语言模型的可信不确定性：一种置信度校准与风险可控拒绝的统一框架

发布时间：2025年09月01日

`LLM应用` `基础理论`

> Trusted Uncertainty in Large Language Models: A Unified Framework for Confidence Calibration and Risk-Controlled Refusal

# 摘要

> 投入实际应用的语言模型不仅要决定回答内容，更要判断何时不应回答。为此，我们提出了UniCR——这一统一框架能整合多种异构不确定性证据（包括序列似然度、自一致性离散度、检索兼容性及工具或验证器反馈），将其转化为校准后的正确性概率，进而通过合理的拒绝机制严格控制用户指定的错误预算。UniCR通过温度缩放与适当评分机制学习轻量级校准头，借助黑盒特征支持纯API模型，并利用保形风险控制实现无分布保证。针对长文本生成任务，我们通过检索证据提取原子事实性分数并以此为监督信号，使置信度与语义保真度精准对齐，在确保覆盖率的同时有效减少"自信的幻觉"问题。在短文本问答、带执行测试的代码生成及检索增强长文本问答任务上的实验结果显示：与熵/Logit阈值法、事后校准器及端到端选择性基线相比，UniCR在校准指标上持续优化，风险-覆盖率曲线下面积更小，且在固定风险水平下覆盖率更高。分析发现，证据矛盾、语义离散及工具输出不一致是模型选择弃权的核心原因，这使得拒绝消息能为用户提供丰富信息。最终形成的可移植方案实现了从证据融合到校准概率再到风险控制决策的全流程优化，无需微调基础模型即可提升可信度，且在分布偏移场景下依然稳健有效。

> Deployed language models must decide not only what to answer but also when not to answer. We present UniCR, a unified framework that turns heterogeneous uncertainty evidence including sequence likelihoods, self-consistency dispersion, retrieval compatibility, and tool or verifier feedback into a calibrated probability of correctness and then enforces a user-specified error budget via principled refusal. UniCR learns a lightweight calibration head with temperature scaling and proper scoring, supports API-only models through black-box features, and offers distribution-free guarantees using conformal risk control. For long-form generation, we align confidence with semantic fidelity by supervising on atomic factuality scores derived from retrieved evidence, reducing confident hallucinations while preserving coverage. Experiments on short-form QA, code generation with execution tests, and retrieval-augmented long-form QA show consistent improvements in calibration metrics, lower area under the risk-coverage curve, and higher coverage at fixed risk compared to entropy or logit thresholds, post-hoc calibrators, and end-to-end selective baselines. Analyses reveal that evidence contradiction, semantic dispersion, and tool inconsistency are the dominant drivers of abstention, yielding informative user-facing refusal messages. The result is a portable recipe of evidence fusion to calibrated probability to risk-controlled decision that improves trustworthiness without fine-tuning the base model and remains valid under distribution shift.

[Arxiv](https://arxiv.org/abs/2509.01455)