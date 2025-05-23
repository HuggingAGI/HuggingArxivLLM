# BitHydra：探索针对大型语言模型的比特翻转推理成本攻击

发布时间：2025年05月22日

`LLM应用` `人工智能安全` `机器学习`

> BitHydra: Towards Bit-flip Inference Cost Attack against Large Language Models

# 摘要

> 大型语言模型（LLMs）在广泛的应用场景中表现卓越，但其规模和资源需求的不断增长使其易受推理成本攻击。这种攻击通过诱导目标LLMs生成最长输出来实现。本文重新审视了现有推理成本攻击，发现这些方法难以造成大规模影响，因为它们具有自指性——攻击者同时也是用户，只能通过输入执行攻击，生成内容计费且仅影响自身。受此启发，我们提出了一种新型推理成本攻击（“翻转推理成本攻击”），直接针对模型而非输入。我们设计了简单而有效的方法“BitHydra”，可翻转模型参数中的关键比特。该方法通过损失函数引导，结合高效比特搜索算法，抑制< EOS >标记概率，明确攻击目标并优化效果。我们在11种LLMs（参数从1.5B到14B）的int8和float16设置下进行了评估。实验显示，BitHydra只需4个样本和3次比特翻转，即可使100%的提示在LLaMA3等模型上达到2048个标记的最大长度，展现了其高效性、扩展性和跨输入迁移能力。

> Large language models (LLMs) have shown impressive capabilities across a wide range of applications, but their ever-increasing size and resource demands make them vulnerable to inference cost attacks, where attackers induce victim LLMs to generate the longest possible output content. In this paper, we revisit existing inference cost attacks and reveal that these methods can hardly produce large-scale malicious effects since they are self-targeting, where attackers are also the users and therefore have to execute attacks solely through the inputs, whose generated content will be charged by LLMs and can only directly influence themselves. Motivated by these findings, this paper introduces a new type of inference cost attacks (dubbed 'bit-flip inference cost attack') that target the victim model itself rather than its inputs. Specifically, we design a simple yet effective method (dubbed 'BitHydra') to effectively flip critical bits of model parameters. This process is guided by a loss function designed to suppress <EOS> token's probability with an efficient critical bit search algorithm, thus explicitly defining the attack objective and enabling effective optimization. We evaluate our method on 11 LLMs ranging from 1.5B to 14B parameters under both int8 and float16 settings. Experimental results demonstrate that with just 4 search samples and as few as 3 bit flips, BitHydra can force 100% of test prompts to reach the maximum generation length (e.g., 2048 tokens) on representative LLMs such as LLaMA3, highlighting its efficiency, scalability, and strong transferability across unseen inputs.

[Arxiv](https://arxiv.org/abs/2505.16670)