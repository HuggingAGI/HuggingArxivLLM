# # 构建抗越狱攻击的鲁棒多模态大语言模型

发布时间：2025年02月01日

`LLM应用

**理由**：这篇论文主要讨论的是多模态大型语言模型（MLLMs）在面对越狱攻击时的脆弱性，并提出了一种新的防御机制SafeMLLM。论文的核心在于如何通过对抗性训练框架来增强MLLMs的鲁棒性，使其在面对复杂对抗性扰动时仍能保持实用性。这属于对大型语言模型在实际应用中的改进和优化，因此应归类为LLM应用。` `人工智能` `网络安全`

> Towards Robust Multimodal Large Language Models Against Jailbreak Attacks

# 摘要

> 尽管多模态大型语言模型（MLLMs）在近期取得了显著进展，但其对越狱攻击的脆弱性也逐渐暴露。攻击者通过精心设计的提示，迫使模型生成有害或不受欢迎的内容。现有防御机制多依赖外部推理或安全对齐训练，但在面对白盒场景中的复杂对抗性扰动时，效果欠佳且不切实际。为应对这些挑战并增强MLLMs的鲁棒性，我们提出了SafeMLLM，采用对抗性训练框架，交替进行攻击步骤和模型更新步骤。攻击步骤中，SafeMLLM通过新提出的对比嵌入攻击（CoE-Attack）生成对抗性扰动，优化令牌嵌入。随后，SafeMLLM更新模型参数，中和扰动效果，同时保持模型在良性输入上的实用性。我们在六个MLLMs和六种跨模态越狱方法上评估了SafeMLLM，实验结果表明，SafeMLLM能有效防御多种攻击，保持鲁棒性能和实用性。

> While multimodal large language models (MLLMs) have achieved remarkable success in recent advancements, their susceptibility to jailbreak attacks has come to light. In such attacks, adversaries exploit carefully crafted prompts to coerce models into generating harmful or undesirable content. Existing defense mechanisms often rely on external inference steps or safety alignment training, both of which are less effective and impractical when facing sophisticated adversarial perturbations in white-box scenarios. To address these challenges and bolster MLLM robustness, we introduce SafeMLLM by adopting an adversarial training framework that alternates between an attack step for generating adversarial noise and a model updating step. At the attack step, SafeMLLM generates adversarial perturbations through a newly proposed contrastive embedding attack (CoE-Attack), which optimizes token embeddings under a contrastive objective. SafeMLLM then updates model parameters to neutralize the perturbation effects while preserving model utility on benign inputs. We evaluate SafeMLLM across six MLLMs and six jailbreak methods spanning multiple modalities. Experimental results show that SafeMLLM effectively defends against diverse attacks, maintaining robust performance and utilities.

[Arxiv](https://arxiv.org/abs/2502.00653)