# 对抗性提示评估：系统性基准测试护栏以抵御针对大型语言模型的提示输入攻击

发布时间：2025年02月21日

`LLM应用` `人工智能`

> Adversarial Prompt Evaluation: Systematic Benchmarking of Guardrails Against Prompt Input Attacks on LLMs

# 摘要

> 随着大型语言模型逐步融入日常应用，确保其稳健性和安全性变得日益关键。尤其是，这些模型可能受到被称为'越狱提示'的操控，从而产生不安全行为。随着越狱手法的不断演变，部署外部防御措施'护栏'变得尤为重要。尽管已提出诸多防御方案，但受限于训练数据的局限性，现有防护措施往往难以应对新型攻击。防御方案的碎片化也严重制约了其实际应用效果。本研究对15种防御方案进行了系统性评估，涵盖了恶意与良性数据集。结果表明，防御方案的表现因越狱手法的不同而存在显著差异。此外，基于现有评估数据，简单基线方案在某些场景下甚至能与先进方案相媲美。代码已开源，地址为：https://github.com/IBM/Adversarial-Prompt-Evaluation。

> As large language models (LLMs) become integrated into everyday applications, ensuring their robustness and security is increasingly critical. In particular, LLMs can be manipulated into unsafe behaviour by prompts known as jailbreaks. The variety of jailbreak styles is growing, necessitating the use of external defences known as guardrails. While many jailbreak defences have been proposed, not all defences are able to handle new out-of-distribution attacks due to the narrow segment of jailbreaks used to align them. Moreover, the lack of systematisation around defences has created significant gaps in their practical application. In this work, we perform systematic benchmarking across 15 different defences, considering a broad swathe of malicious and benign datasets. We find that there is significant performance variation depending on the style of jailbreak a defence is subject to. Additionally, we show that based on current datasets available for evaluation, simple baselines can display competitive out-of-distribution performance compared to many state-of-the-art defences. Code is available at https://github.com/IBM/Adversarial-Prompt-Evaluation.

[Arxiv](https://arxiv.org/abs/2502.15427)