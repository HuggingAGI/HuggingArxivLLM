# 思想才是关键：评估前沿LLMs在有害话题上的说服效果

发布时间：2025年06月03日

`LLM应用`

> It's the Thought that Counts: Evaluating the Attempts of Frontier LLMs to Persuade on Harmful Topics

# 摘要

> 说服能力是大型语言模型（LLMs）的一项强大力量，既能赋能有益的应用（如帮助戒烟），也可能引发重大风险（如大规模政治操控）。先前研究显示，模型的说服能力显著且持续增强，这一结论基于模拟或真实用户信念的变化。然而，现有基准测试忽视了一个关键风险因素：模型在有害情境下主动说服的倾向。理解模型是否会盲目遵循指令，在有害话题上展开说服（如美化恐怖组织加入），是评估安全护栏效能的关键。同时，理解模型是否及何时为特定目标采取说服行为，对评估具身AI系统的风险至关重要。我们提出“尝试说服评估”（APE）基准，将研究重点从说服成功转向说服尝试，具体体现为模型生成旨在影响信念或行为内容的意愿。我们的评估框架通过模拟说服者与被说服者代理间的多轮对话，探索前沿LLMs的表现。APE涵盖阴谋论、争议话题及公认有害内容等多样化领域。我们引入自动化评估模型，识别说服意愿并衡量其频率与情境。研究发现，开源与闭源模型常在有害话题上尝试说服，且越狱技术会增加此类行为的意愿。结果凸显现有安全护栏的不足，强调将说服意愿作为LLM风险关键维度评估的重要性。APE可在github.com/AlignmentResearch/AttemptPersuadeEval获取。

> Persuasion is a powerful capability of large language models (LLMs) that both enables beneficial applications (e.g. helping people quit smoking) and raises significant risks (e.g. large-scale, targeted political manipulation). Prior work has found models possess a significant and growing persuasive capability, measured by belief changes in simulated or real users. However, these benchmarks overlook a crucial risk factor: the propensity of a model to attempt to persuade in harmful contexts. Understanding whether a model will blindly ``follow orders'' to persuade on harmful topics (e.g. glorifying joining a terrorist group) is key to understanding the efficacy of safety guardrails. Moreover, understanding if and when a model will engage in persuasive behavior in pursuit of some goal is essential to understanding the risks from agentic AI systems. We propose the Attempt to Persuade Eval (APE) benchmark, that shifts the focus from persuasion success to persuasion attempts, operationalized as a model's willingness to generate content aimed at shaping beliefs or behavior. Our evaluation framework probes frontier LLMs using a multi-turn conversational setup between simulated persuader and persuadee agents. APE explores a diverse spectrum of topics including conspiracies, controversial issues, and non-controversially harmful content. We introduce an automated evaluator model to identify willingness to persuade and measure the frequency and context of persuasive attempts. We find that many open and closed-weight models are frequently willing to attempt persuasion on harmful topics and that jailbreaking can increase willingness to engage in such behavior. Our results highlight gaps in current safety guardrails and underscore the importance of evaluating willingness to persuade as a key dimension of LLM risk. APE is available at github.com/AlignmentResearch/AttemptPersuadeEval

[Arxiv](https://arxiv.org/abs/2506.02873)