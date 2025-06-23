# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月20日

`LLM应用` `临床决策`

> The MedPerturb Dataset: What Non-Content Perturbations Reveal About Human and Clinical LLM Decision Making

# 摘要

> # 摘要  
临床稳健性是确保医疗大语言模型 (LLMs) 安全部署的关键，但 LLMs 与人类在面对临床环境中典型的真实世界变异性时的差异仍有许多未解之谜。为探究这一问题，我们推出了 MedPerturb 数据集，旨在通过受控的临床输入扰动，系统性地评估医疗 LLMs 的表现。MedPerturb 包含涵盖多种病理学的临床案例，每个案例从三个维度进行调整：(1) 性别修改（如性别互换或去除性别信息）；(2) 风格变化（如含糊措辞或口语化表达）；(3) 格式更改（如多轮对话或临床摘要）。  
借助 MedPerturb，我们发布了包含 800 个基于现实输入变异性临床情境的数据集，以及四个 LLM 的输出和每个情境下三位人类专家的解读。通过两个案例研究，我们揭示了性别身份线索、语言风格或格式的变化如何导致人类与 LLMs 在治疗选择上的差异。研究发现，LLMs 对性别和风格的扰动更为敏感，而人类标注员则对 LLM 生成的格式扰动（如临床摘要）更为敏感。我们的成果强调了评估框架的重要性，这些框架需超越静态基准，评估在临床环境中固有的变异性下，人类临床医生与 LLM 决策之间的相似性。


> Clinical robustness is critical to the safe deployment of medical Large Language Models (LLMs), but key questions remain about how LLMs and humans may differ in response to the real-world variability typified by clinical settings. To address this, we introduce MedPerturb, a dataset designed to systematically evaluate medical LLMs under controlled perturbations of clinical input. MedPerturb consists of clinical vignettes spanning a range of pathologies, each transformed along three axes: (1) gender modifications (e.g., gender-swapping or gender-removal); (2) style variation (e.g., uncertain phrasing or colloquial tone); and (3) format changes (e.g., LLM-generated multi-turn conversations or summaries). With MedPerturb, we release a dataset of 800 clinical contexts grounded in realistic input variability, outputs from four LLMs, and three human expert reads per clinical context. We use MedPerturb in two case studies to reveal how shifts in gender identity cues, language style, or format reflect diverging treatment selections between humans and LLMs. We find that LLMs are more sensitive to gender and style perturbations while human annotators are more sensitive to LLM-generated format perturbations such as clinical summaries. Our results highlight the need for evaluation frameworks that go beyond static benchmarks to assess the similarity between human clinician and LLM decisions under the variability characteristic of clinical settings.

[Arxiv](https://arxiv.org/abs/2506.17163)