# 九种侵犯版权的方式，为何我们的LLM不会触犯？——基于合理使用原则的生成框架

发布时间：2025年05月25日

`LLM应用` `版权合规` `法律合规`

> Nine Ways to Break Copyright Law and Why Our LLM Won't: A Fair Use Aligned Generation Framework

# 摘要

> 大型语言模型 (LLMs) 在生成内容时，常因直接复制受版权保护的内容或进行不够显著的改编而面临侵权风险，这引发了重大的伦理、法律和实际应用问题。现有的推理时保护措施多采用严格的拒绝式过滤器，这往往削弱了模型的实际效用。为了解决这一问题，我们与知识产权专家紧密合作，开发了 FUA-LLM（符合合理使用原则的语言模型），这是一个以法律为依据的框架，旨在将 LLM 的输出与合理使用原则相一致。我们的方法核心是 FairUseDB，这是一个精心构建的数据集，包含 18,000 个专家验证的示例，涵盖了九种现实的侵权场景。利用这个数据集，我们采用直接偏好优化 (DPO) 对开源 LLM 进行微调，鼓励它们生成既符合法律又实用的替代内容，而不是简单地拒绝请求。我们认识到传统评估指标的不足，因此提出了新的度量标准：加权处罚效用和合规感知调和均值 (CAH)，以平衡侵权风险与响应效用。广泛的定量实验结合专家评估证实，与最先进的方法相比，FUA-LLM 将有问题的输出减少了高达 20%，同时保持了实际应用的可行性。

> Large language models (LLMs) commonly risk copyright infringement by reproducing protected content verbatim or with insufficient transformative modifications, posing significant ethical, legal, and practical concerns. Current inference-time safeguards predominantly rely on restrictive refusal-based filters, often compromising the practical utility of these models. To address this, we collaborated closely with intellectual property experts to develop FUA-LLM (Fair Use Aligned Language Models), a legally-grounded framework explicitly designed to align LLM outputs with fair-use doctrine. Central to our method is FairUseDB, a carefully constructed dataset containing 18,000 expert-validated examples covering nine realistic infringement scenarios. Leveraging this dataset, we apply Direct Preference Optimization (DPO) to fine-tune open-source LLMs, encouraging them to produce legally compliant and practically useful alternatives rather than resorting to blunt refusal. Recognizing the shortcomings of traditional evaluation metrics, we propose new measures: Weighted Penalty Utility and Compliance Aware Harmonic Mean (CAH) to balance infringement risk against response utility. Extensive quantitative experiments coupled with expert evaluations confirm that FUA-LLM substantially reduces problematic outputs (up to 20\%) compared to state-of-the-art approaches, while preserving real-world usability.

[Arxiv](https://arxiv.org/abs/2505.23788)