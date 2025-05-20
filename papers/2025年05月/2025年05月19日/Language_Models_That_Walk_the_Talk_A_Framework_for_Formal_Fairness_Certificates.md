# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月19日

`LLM理论` `伦理化AI` `内容审核`

> Language Models That Walk the Talk: A Framework for Formal Fairness Certificates

# 摘要

> 大型语言模型在高风险应用中的广泛应用使其稳健性和公平性保障变得尤为重要。尽管这些模型取得了显著成功，但它们仍易受对抗攻击影响，如通过同义词替换等微小扰动即可改变模型预测，这在性别偏见缓解和毒性检测等关键领域构成风险。尽管形式化验证在神经网络中已有应用，但将其应用于大型语言模型仍具挑战。本研究提出了一种全面的验证框架，专注于确保基于Transformer的语言模型在不同性别相关术语上的公平性和输出一致性。此外，我们还将这一方法扩展至毒性检测领域，提供形式化保证，确保经过对抗性操纵的有毒输入被一致检测和适当审查，从而提升内容审核系统的可靠性。通过在嵌入空间中形式化稳健性，这项工作为语言模型在伦理化AI部署和内容审核中的可靠应用提供了有力保障。

> As large language models become integral to high-stakes applications, ensuring their robustness and fairness is critical. Despite their success, large language models remain vulnerable to adversarial attacks, where small perturbations, such as synonym substitutions, can alter model predictions, posing risks in fairness-critical areas, such as gender bias mitigation, and safety-critical areas, such as toxicity detection. While formal verification has been explored for neural networks, its application to large language models remains limited. This work presents a holistic verification framework to certify the robustness of transformer-based language models, with a focus on ensuring gender fairness and consistent outputs across different gender-related terms. Furthermore, we extend this methodology to toxicity detection, offering formal guarantees that adversarially manipulated toxic inputs are consistently detected and appropriately censored, thereby ensuring the reliability of moderation systems. By formalizing robustness within the embedding space, this work strengthens the reliability of language models in ethical AI deployment and content moderation.

[Arxiv](https://arxiv.org/abs/2505.12767)