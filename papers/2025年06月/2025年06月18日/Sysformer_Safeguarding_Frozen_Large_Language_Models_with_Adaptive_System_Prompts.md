# Sysformer：通过自适应系统提示保护冻结的大型语言模型

发布时间：2025年06月18日

`LLM应用

摘要讨论了在安全关键环境中应用大型语言模型（LLMs）时，如何确保其响应符合安全标准。论文提出了一种通过调整系统提示来提高LLMs鲁棒性的新方法，属于LLM应用领域。` `人工智能`

> Sysformer: Safeguarding Frozen Large Language Models with Adaptive System Prompts

# 摘要

> 在安全关键环境中应用大型语言模型 (LLMs) 时，确保其响应符合安全标准至关重要。先前研究表明，LLMs 往往难以理解安全行为的概念，导致要么不合理拒绝无害提示，要么生成有害内容。尽管人们在提高 LLMs 鲁棒性方面付出了巨大努力，但现有防御方法要么依赖昂贵的参数微调，要么采用次优的启发式技术。本研究提出了一种全新方法，通过学习调整指令微调 LLMs 中的系统提示来保护模型。虽然 LLMs 通常预训练为遵循固定系统提示，但我们研究了针对每个用户输入定制系统提示对响应安全性的影响。为此，我们提出了 $	extbf{Sysformer}$，一种 $	extbf{transformer}$ 模型，通过关注用户提示并在 LLM 输入嵌入空间中将初始 $	extbf{sys}$ 系统提示优化为更健壮的提示。在保持 LLM 参数不变的情况下，Sysformer 被训练为拒绝有害提示，同时理想响应安全提示。通过在 $5$ 个不同家族的 LLM 和 $2$ 个最新基准上的广泛实验，我们发现 Sysformer 能显著提升 LLMs 的鲁棒性，使有害提示的拒绝率提升高达 $80\%$，同时对安全提示的合规性提升高达 $90\%$。实验结果还很好地推广到复杂的越狱攻击，使 LLMs 面对不同攻击策略时的鲁棒性提升高达 $100\%$。我们希望这项研究能以更低的成本保护 LLMs，并激励未来对可变系统提示设计的进一步探索。

> As large language models (LLMs) are deployed in safety-critical settings, it is essential to ensure that their responses comply with safety standards. Prior research has revealed that LLMs often fail to grasp the notion of safe behaviors, resulting in either unjustified refusals to harmless prompts or the generation of harmful content. While substantial efforts have been made to improve their robustness, existing defenses often rely on costly fine-tuning of model parameters or employ suboptimal heuristic techniques. In this work, we take a novel approach to safeguard LLMs by learning to adapt the system prompts in instruction-tuned LLMs. While LLMs are typically pre-trained to follow a fixed system prompt, we investigate the impact of tailoring the system prompt to each specific user input on the safety of the responses. To this end, we propose $\textbf{Sysformer}$, a trans$\textbf{former}$ model that updates an initial $\textbf{sys}$tem prompt to a more robust system prompt in the LLM input embedding space while attending to the user prompt. While keeping the LLM parameters frozen, the Sysformer is trained to refuse to respond to a set of harmful prompts while responding ideally to a set of safe ones. Through extensive experiments on $5$ LLMs from different families and $2$ recent benchmarks, we demonstrate that Sysformer can significantly enhance the robustness of LLMs, leading to upto $80\%$ gain in the refusal rate on harmful prompts while enhancing the compliance with the safe prompts by upto $90\%$. Results also generalize well to sophisticated jailbreaking attacks, making LLMs upto $100\%$ more robust against different attack strategies. We hope our findings lead to cheaper safeguarding of LLMs and motivate future investigations into designing variable system prompts.

[Arxiv](https://arxiv.org/abs/2506.15751)