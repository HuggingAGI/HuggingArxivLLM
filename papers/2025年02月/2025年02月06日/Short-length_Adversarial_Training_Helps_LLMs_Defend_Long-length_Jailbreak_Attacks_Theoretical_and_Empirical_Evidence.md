# “短长度”对抗训练助力LLMs抵御“长长度”越狱攻击：理论与实证支持

发布时间：2025年02月06日

`LLM理论

理由：这篇论文主要研究了大型语言模型（LLMs）在对抗性攻击下的鲁棒性，特别是对抗性后缀越狱攻击的防御机制。论文通过理论分析和实证研究，提出了在对抗训练（AT）过程中使用较短的对抗性提示来防御较长的对抗性攻击的方法。这些内容涉及LLMs的理论分析和鲁棒性研究，属于LLM理论的范畴。` `人工智能` `网络安全`

> "Short-length" Adversarial Training Helps LLMs Defend "Long-length" Jailbreak Attacks: Theoretical and Empirical Evidence

# 摘要

> # 摘要
针对大型语言模型（LLMs）的越狱攻击通过精心设计的对抗性提示诱导LLMs产生有害行为。为应对此类攻击，一种有效方法是基于对抗训练（AT）的对齐，即在最具对抗性的提示上训练LLMs，使其在攻击下保持安全行为。AT过程中，对抗性提示的长度对LLMs的鲁棒性至关重要。本文聚焦于对抗性后缀越狱攻击，发现防御长度为$Θ(M)$的对抗性后缀攻击，只需在长度为$Θ(\sqrt{M})$的对抗性后缀提示上对齐LLMs。理论上，我们分析了线性变压器在线性回归任务中的对抗性上下文学习，并证明了训练后变压器的鲁棒泛化边界，该边界取决于$Θ(\sqrt{M_{	ext{test}}}/M_{	ext{train}})$项，其中$M_{	ext{train}}$和$M_{	ext{test}}$分别为训练和测试期间的对抗性扰动样本数量。实证中，我们在开源LLMs上进行了AT，并评估了其对不同长度对抗性后缀攻击的鲁棒性。结果表明，攻击成功率与越狱期间对抗性后缀的平方根长度与AT期间长度的比率呈正相关。我们的研究证明，通过高效的“短长度”AT防御“长长度”越狱攻击是可行的。代码详见https://github.com/fshp971/adv-icl。

> Jailbreak attacks against large language models (LLMs) aim to induce harmful behaviors in LLMs through carefully crafted adversarial prompts. To mitigate attacks, one way is to perform adversarial training (AT)-based alignment, i.e., training LLMs on some of the most adversarial prompts to help them learn how to behave safely under attacks. During AT, the length of adversarial prompts plays a critical role in the robustness of aligned LLMs. This paper focuses on adversarial suffix jailbreak attacks and unveils that to defend against a jailbreak attack with an adversarial suffix of length $Θ(M)$, it is enough to align LLMs on prompts with adversarial suffixes of length $Θ(\sqrt{M})$. Theoretically, we analyze the adversarial in-context learning of linear transformers on linear regression tasks and prove a robust generalization bound for trained transformers. The bound depends on the term $Θ(\sqrt{M_{\text{test}}}/M_{\text{train}})$, where $M_{\text{train}}$ and $M_{\text{test}}$ are the number of adversarially perturbed in-context samples during training and testing. Empirically, we conduct AT on popular open-source LLMs and evaluate their robustness against jailbreak attacks of different adversarial suffix lengths. Results confirm a positive correlation between the attack success rate and the ratio of the square root of the adversarial suffix during jailbreaking to the length during AT. Our findings show that it is practical to defend "long-length" jailbreak attacks via efficient "short-length" AT. The code is available at https://github.com/fshp971/adv-icl.

[Arxiv](https://arxiv.org/abs/2502.04204)