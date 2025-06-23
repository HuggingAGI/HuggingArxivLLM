# 先探查再交谈：大型语言模型后门对齐攻击的黑盒防御方法

发布时间：2025年06月19日

`LLM应用

摘要中的论文讨论了针对大型语言模型的后门攻击及其防御方法，属于应用层面的创新，因此归类为LLM应用。` `人工智能`

> Probe before You Talk: Towards Black-box Defense against Backdoor Unalignment for Large Language Models

# 摘要

> 针对大型语言模型（LLMs）的后门对齐攻击利用隐藏触发器悄然破坏模型的安全对齐，同时规避正常安全审核。这些攻击对现实世界中作为服务的大型语言模型（LLMaaS）应用构成重大威胁，因为部署的模型是一个完全黑箱系统，仅支持文本交互。此外，攻击目标依赖于具体样本的特性，进一步加剧了威胁。被黑化的LLM不再输出固定标签，而是遵循任何带有隐藏触发器的恶意命令的语义，极大扩展了攻击目标范围。

本文中，我们引入了BEAT，这是一种黑箱防御方法，通过检测推理过程中的触发样本来禁用后门。这一方法的灵感来自于一个引人入胜的观察（被称为探针拼接效应）：拼接触发样本会显著降低被黑LLM对恶意探针的拒绝率，而非触发样本则几乎没有影响。具体而言，BEAT通过测量探针在与输入拼接前后的输出分布扭曲程度，来判断输入是否被触发。

我们的方法从相反角度解决了依赖样本的目标挑战。它捕捉了触发器对拒绝信号（与样本无关）的影响，而不是特定样本的成功攻击行为。通过使用多采样来近似输出分布，它克服了黑箱访问的限制。我们在多种后门攻击和LLMs（包括闭源的GPT-3.5-turbo）上进行了大量实验，验证了我们防御的有效性和效率。此外，我们还初步验证了BEAT可以有效防御流行的越狱攻击，因为它们可以被视为“自然后门”。

> Backdoor unalignment attacks against Large Language Models (LLMs) enable the stealthy compromise of safety alignment using a hidden trigger while evading normal safety auditing. These attacks pose significant threats to the applications of LLMs in the real-world Large Language Model as a Service (LLMaaS) setting, where the deployed model is a fully black-box system that can only interact through text. Furthermore, the sample-dependent nature of the attack target exacerbates the threat. Instead of outputting a fixed label, the backdoored LLM follows the semantics of any malicious command with the hidden trigger, significantly expanding the target space. In this paper, we introduce BEAT, a black-box defense that detects triggered samples during inference to deactivate the backdoor. It is motivated by an intriguing observation (dubbed the probe concatenate effect), where concatenated triggered samples significantly reduce the refusal rate of the backdoored LLM towards a malicious probe, while non-triggered samples have little effect. Specifically, BEAT identifies whether an input is triggered by measuring the degree of distortion in the output distribution of the probe before and after concatenation with the input. Our method addresses the challenges of sample-dependent targets from an opposite perspective. It captures the impact of the trigger on the refusal signal (which is sample-independent) instead of sample-specific successful attack behaviors. It overcomes black-box access limitations by using multiple sampling to approximate the output distribution. Extensive experiments are conducted on various backdoor attacks and LLMs (including the closed-source GPT-3.5-turbo), verifying the effectiveness and efficiency of our defense. Besides, we also preliminarily verify that BEAT can effectively defend against popular jailbreak attacks, as they can be regarded as 'natural backdoors'.

[Arxiv](https://arxiv.org/abs/2506.16447)