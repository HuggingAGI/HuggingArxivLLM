# 谈行一致的语言模型框架：正式公平证书的构建

发布时间：2025年05月19日

`LLM理论` `内容审核` `伦理AI`

> Language Models That Walk the Talk: A Framework for Formal Fairness Certificates

# 摘要

> 大型语言模型在高风险场景中的广泛应用使其稳健性和公平性保障变得至关重要。尽管在多个领域取得了显著成功，但大型语言模型仍然面临对抗攻击的威胁。通过简单的同义词替换等微小干扰，攻击者即可改变模型预测结果，这在性别偏见缓解等公平性关键领域以及毒性内容检测等安全关键领域带来了显著风险。尽管形式化验证方法在神经网络领域已有所探索，但将其应用于大型语言模型仍面临诸多挑战。

本研究提出了一种全面的验证框架，旨在认证基于Transformer的语言模型的稳健性，重点关注在不同性别相关术语下确保性别公平性及输出一致性。此外，我们将该方法成功扩展至毒性内容检测领域，提供形式化保证，确保经过对抗攻击的有毒内容能够被系统一致识别并妥善处理，从而保障内容审核系统的可靠性。通过在嵌入空间中形式化定义模型稳健性，本研究为在伦理化AI部署及内容审核场景下提升语言模型的可靠性提供了重要支持。

> As large language models become integral to high-stakes applications, ensuring their robustness and fairness is critical. Despite their success, large language models remain vulnerable to adversarial attacks, where small perturbations, such as synonym substitutions, can alter model predictions, posing risks in fairness-critical areas, such as gender bias mitigation, and safety-critical areas, such as toxicity detection. While formal verification has been explored for neural networks, its application to large language models remains limited. This work presents a holistic verification framework to certify the robustness of transformer-based language models, with a focus on ensuring gender fairness and consistent outputs across different gender-related terms. Furthermore, we extend this methodology to toxicity detection, offering formal guarantees that adversarially manipulated toxic inputs are consistently detected and appropriately censored, thereby ensuring the reliability of moderation systems. By formalizing robustness within the embedding space, this work strengthens the reliability of language models in ethical AI deployment and content moderation.

[Arxiv](https://arxiv.org/abs/2505.12767)