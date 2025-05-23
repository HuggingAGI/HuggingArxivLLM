# CTRAP：通过嵌入坍塌陷阱保护大型语言模型免受有害微调的影响

发布时间：2025年05月22日

`LLM理论` `人工智能安全` `机器学习`

> CTRAP: Embedding Collapse Trap to Safeguard Large Language Models from Harmful Fine-Tuning

# 摘要

> 尽管微调服务（Fine-tuning-as-a-service）为大型语言模型（LLM）提供商带来了商业成功，但也使模型面临有害微调攻击的风险。作为一种防御范式，反向学习试图从LLM中移除恶意知识，防止其用于执行恶意任务。然而，我们发现LLM的强大适应性使它们能够轻松绕过选择性反向学习，通过迅速重新学习或重新利用能力来执行有害任务。为解决这一根本性限制，我们提出了一种新范式：诱导模型崩溃，即迫使模型“遗忘一切”，具体针对恶意适应的更新特征。这种崩溃直接中和了攻击者所利用的通用能力，解决了选择性反向学习无法触及的核心问题。我们引入了坍缩陷阱（Collapse Trap，CTRAP）作为实现这一概念的实用机制。CTRAP在对齐过程中嵌入，预先配置模型对后续微调动态的反应。如果微调过程中的更新构成持续尝试逆转安全对齐，预先配置的陷阱将触发模型核心语言建模能力的逐步退化，最终使其对攻击者而言失效无用。至关重要的是，这种坍缩机制在良性微调过程中保持休眠状态，确保模型的实用性和通用能力得以保留，供合法用户使用。大量实证结果表明，CTRAP能够有效应对各种LLM和攻击设置下的有害微调风险，同时在良性场景中保持高性能。我们的代码可在https://anonymous.4open.science/r/CTRAP获取。


> Fine-tuning-as-a-service, while commercially successful for Large Language Model (LLM) providers, exposes models to harmful fine-tuning attacks. As a widely explored defense paradigm against such attacks, unlearning attempts to remove malicious knowledge from LLMs, thereby essentially preventing them from being used to perform malicious tasks. However, we highlight a critical flaw: the powerful general adaptability of LLMs allows them to easily bypass selective unlearning by rapidly relearning or repurposing their capabilities for harmful tasks. To address this fundamental limitation, we propose a paradigm shift: instead of selective removal, we advocate for inducing model collapse--effectively forcing the model to "unlearn everything"--specifically in response to updates characteristic of malicious adaptation. This collapse directly neutralizes the very general capabilities that attackers exploit, tackling the core issue unaddressed by selective unlearning. We introduce the Collapse Trap (CTRAP) as a practical mechanism to implement this concept conditionally. Embedded during alignment, CTRAP pre-configures the model's reaction to subsequent fine-tuning dynamics. If updates during fine-tuning constitute a persistent attempt to reverse safety alignment, the pre-configured trap triggers a progressive degradation of the model's core language modeling abilities, ultimately rendering it inert and useless for the attacker. Crucially, this collapse mechanism remains dormant during benign fine-tuning, ensuring the model's utility and general capabilities are preserved for legitimate users. Extensive empirical results demonstrate that CTRAP effectively counters harmful fine-tuning risks across various LLMs and attack settings, while maintaining high performance in benign scenarios. Our code is available at https://anonymous.4open.science/r/CTRAP.

[Arxiv](https://arxiv.org/abs/2505.16559)