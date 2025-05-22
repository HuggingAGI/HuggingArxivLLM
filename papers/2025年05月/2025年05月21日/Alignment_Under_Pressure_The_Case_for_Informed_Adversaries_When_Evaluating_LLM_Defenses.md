# 压力下的对齐：评估大型语言模型防御机制时的知情攻击者

发布时间：2025年05月21日

`LLM理论` `人工智能安全` `人工智能`

> Alignment Under Pressure: The Case for Informed Adversaries When Evaluating LLM Defenses

# 摘要

> 大型语言模型（LLMs）正在迅速应用于从聊天机器人到智能体系统的各种现实场景中。对齐是防御提示注入和越狱攻击的主要方法之一。近期研究显示，即使面对能够生成对抗性后缀以诱导攻击者期望输出的贪心坐标梯度（GCG）攻击，防御措施也能实现接近零的攻击成功率（ASR）。然而，由于离散标记的搜索空间极其庞大，寻找成功的攻击方法变得异常困难。例如，GCG方法容易收敛到局部最小值，使其对初始设置高度敏感。

本文采用一种更为完善的威胁模型来评估这些防御措施的未来稳健性：即攻击者能够获取与对齐过程相关的一些信息。具体而言，我们提出了一种基于中间模型检查点初始化的知情白盒攻击方法，每个检查点都为后续攻击提供了关键的参考。我们展示了这种方法在各类先进防御策略和模型上的高效性。进一步地，我们证明了我们的知情初始化策略优于其他初始化方法，并提出了一种基于梯度信息的检查点选择策略，能够显著提升攻击效果和效率。尤为重要的是，我们成功找到了通用的对抗性后缀——即单一后缀即可在多种输入下生效。

我们的研究结果表明，与先前的认知相反，有效的对抗性后缀确实存在，能够突破当前基于对齐的先进防御机制，而这些攻击方法在攻击者利用对齐知识时尤为奏效，甚至能够找到通用的后缀。综合来看，我们的研究揭示了现有基于对齐的方法的脆弱性，并强调在测试大型语言模型的安全性时，必须考虑更为强大的威胁模型。

> Large language models (LLMs) are rapidly deployed in real-world applications ranging from chatbots to agentic systems. Alignment is one of the main approaches used to defend against attacks such as prompt injection and jailbreaks. Recent defenses report near-zero Attack Success Rates (ASR) even against Greedy Coordinate Gradient (GCG), a white-box attack that generates adversarial suffixes to induce attacker-desired outputs. However, this search space over discrete tokens is extremely large, making the task of finding successful attacks difficult. GCG has, for instance, been shown to converge to local minima, making it sensitive to initialization choices. In this paper, we assess the future-proof robustness of these defenses using a more informed threat model: attackers who have access to some information about the alignment process. Specifically, we propose an informed white-box attack leveraging the intermediate model checkpoints to initialize GCG, with each checkpoint acting as a stepping stone for the next one. We show this approach to be highly effective across state-of-the-art (SOTA) defenses and models. We further show our informed initialization to outperform other initialization methods and show a gradient-informed checkpoint selection strategy to greatly improve attack performance and efficiency. Importantly, we also show our method to successfully find universal adversarial suffixes -- single suffixes effective across diverse inputs. Our results show that, contrary to previous beliefs, effective adversarial suffixes do exist against SOTA alignment-based defenses, that these can be found by existing attack methods when adversaries exploit alignment knowledge, and that even universal suffixes exist. Taken together, our results highlight the brittleness of current alignment-based methods and the need to consider stronger threat models when testing the safety of LLMs.

[Arxiv](https://arxiv.org/abs/2505.15738)