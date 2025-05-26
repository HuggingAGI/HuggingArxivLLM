# Harry Potter 依然在线！自动化对抗提示揭示特定未学习大型语言模型的知识泄漏问题

发布时间：2025年05月22日

`LLM理论` `人工智能`

> Harry Potter is Still Here! Probing Knowledge Leakage in Targeted Unlearned Large Language Models via Automated Adversarial Prompting

# 摘要

> 本研究提出了一种名为 LURK（潜藏未学知识）的创新框架，它通过对抗性后缀提示技术，探测未学习大型语言模型中隐藏的知识。LURK 能够自动生成专门设计的对抗性提示后缀，以诱发与哈利波特领域相关的残余知识——这一领域常被用作遗忘评估的基准。我们的实验发现，即便是一些被认为成功完成遗忘的模型，在特定的对抗条件下仍会泄露独特信息，这揭示了现有遗忘评估标准的重大局限性。LURK 通过间接探测揭示潜藏知识，为评估遗忘算法的稳健性提供了一个更为严谨和诊断性的工具。所有相关代码将公开发布。

> This work presents LURK (Latent UnleaRned Knowledge), a novel framework that probes for hidden retained knowledge in unlearned LLMs through adversarial suffix prompting. LURK automatically generates adversarial prompt suffixes designed to elicit residual knowledge about the Harry Potter domain, a commonly used benchmark for unlearning. Our experiments reveal that even models deemed successfully unlearned can leak idiosyncratic information under targeted adversarial conditions, highlighting critical limitations of current unlearning evaluation standards. By uncovering latent knowledge through indirect probing, LURK offers a more rigorous and diagnostic tool for assessing the robustness of unlearning algorithms. All code will be publicly available.

[Arxiv](https://arxiv.org/abs/2505.17160)