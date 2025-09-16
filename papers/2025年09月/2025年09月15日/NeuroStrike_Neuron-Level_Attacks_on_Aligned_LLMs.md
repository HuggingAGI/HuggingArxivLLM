# NeuroStrike：对对齐大型语言模型的神经元级攻击

发布时间：2025年09月15日

`LLM应用` `基础理论`

> NeuroStrike: Neuron-Level Attacks on Aligned LLMs

# 摘要

> 安全对齐是大型语言模型（LLMs）实现伦理部署的关键，能引导模型规避有害或不道德内容的生成。当前的对齐技术（例如监督微调（SFT）和人类反馈强化学习（RLHF））仍较为脆弱，易被精心设计的对抗性提示绕过。然而，这类攻击依赖试错，缺乏跨模型通用性，且在可扩展性和可靠性上存在局限。
  本文提出了一种新颖通用的攻击框架NeuroStrike，它直击对齐技术的核心漏洞——依赖稀疏的专用安全神经元来检测和抑制有害输入。我们将其应用于白盒与黑盒两种场景：在白盒场景下，通过前馈激活分析识别安全神经元，并在推理时修剪这些神经元以失效安全机制；在黑盒场景下，首创LLM轮廓攻击，利用安全神经元的可迁移性，在开源权重替代模型上训练对抗性提示生成器，再部署到黑盒及专有目标模型中。
  我们在20多个主流LLM开发者的开源权重模型上验证了NeuroStrike：仅需移除目标层中不到0.6%的神经元，凭借普通恶意提示即可达到76.9%的平均攻击成功率（ASR）；它还能推广到四个多模态LLM，在不安全图像输入上的ASR达100%。安全神经元在不同架构间迁移效果显著，在11个微调模型上的ASR提升至78.5%，在5个蒸馏模型上达77.7%。黑盒LLM轮廓攻击在包括Google Gemini系列在内的五个黑盒模型上，平均ASR达63.7%。

> Safety alignment is critical for the ethical deployment of large language models (LLMs), guiding them to avoid generating harmful or unethical content. Current alignment techniques, such as supervised fine-tuning and reinforcement learning from human feedback, remain fragile and can be bypassed by carefully crafted adversarial prompts. Unfortunately, such attacks rely on trial and error, lack generalizability across models, and are constrained by scalability and reliability.
  This paper presents NeuroStrike, a novel and generalizable attack framework that exploits a fundamental vulnerability introduced by alignment techniques: the reliance on sparse, specialized safety neurons responsible for detecting and suppressing harmful inputs. We apply NeuroStrike to both white-box and black-box settings: In the white-box setting, NeuroStrike identifies safety neurons through feedforward activation analysis and prunes them during inference to disable safety mechanisms. In the black-box setting, we propose the first LLM profiling attack, which leverages safety neuron transferability by training adversarial prompt generators on open-weight surrogate models and then deploying them against black-box and proprietary targets. We evaluate NeuroStrike on over 20 open-weight LLMs from major LLM developers. By removing less than 0.6% of neurons in targeted layers, NeuroStrike achieves an average attack success rate (ASR) of 76.9% using only vanilla malicious prompts. Moreover, Neurostrike generalizes to four multimodal LLMs with 100% ASR on unsafe image inputs. Safety neurons transfer effectively across architectures, raising ASR to 78.5% on 11 fine-tuned models and 77.7% on five distilled models. The black-box LLM profiling attack achieves an average ASR of 63.7% across five black-box models, including the Google Gemini family.

[Arxiv](https://arxiv.org/abs/2509.11864)