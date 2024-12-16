# LLM 智能体间合作的文化演进

发布时间：2024年12月13日

`Agent` `人工智能` `社会科学`

> Cultural Evolution of Cooperation among LLM Agents

# 摘要

> 大型语言模型（LLMs）为构建具备通用能力的人工智能代理奠定了坚实基础。这些代理或许很快就会在现实世界中大规模投入使用，代表着个人（比如人工智能助手）或群体（比如借助人工智能加速发展的公司）的利益。当下，对于多个 LLM 代理在多代迭代部署中的交互动态，我们所知甚少。在本文中，我们探究了面对背叛的诱因，LLM 代理的“社会”能否习得互惠互利的社会规范，这是人类社会性的一个显著特征，对文明的成功可谓至关重要。具体而言，我们研究了在玩经典迭代捐赠游戏的多代 LLM 代理中，间接互惠的演变情况，在该游戏中，代理能够观察到同伴的近期行为。我们发现，不同基础模型之间的合作演变差异显著，Claude 3.5 Sonnet 代理的社会平均得分显著高于 Gemini 1.5 Flash，而 Gemini 1.5 Flash 又比 GPT-4o 表现出色。此外，Claude 3.5 Sonnet 能够利用额外的高成本惩罚机制获取更高分数，而 Gemini 1.5 Flash 和 GPT-4o 则无法做到。对于每个模型类别，我们还观察到不同随机种子下新兴行为的变化，这表明对初始条件存在研究不足的敏感依赖性。我们认为，我们的评估机制能够催生一类成本低廉且信息丰富的新型 LLM 基准，重点关注 LLM 代理部署对社会合作基础设施的影响。

> Large language models (LLMs) provide a compelling foundation for building generally-capable AI agents. These agents may soon be deployed at scale in the real world, representing the interests of individual humans (e.g., AI assistants) or groups of humans (e.g., AI-accelerated corporations). At present, relatively little is known about the dynamics of multiple LLM agents interacting over many generations of iterative deployment. In this paper, we examine whether a "society" of LLM agents can learn mutually beneficial social norms in the face of incentives to defect, a distinctive feature of human sociality that is arguably crucial to the success of civilization. In particular, we study the evolution of indirect reciprocity across generations of LLM agents playing a classic iterated Donor Game in which agents can observe the recent behavior of their peers. We find that the evolution of cooperation differs markedly across base models, with societies of Claude 3.5 Sonnet agents achieving significantly higher average scores than Gemini 1.5 Flash, which, in turn, outperforms GPT-4o. Further, Claude 3.5 Sonnet can make use of an additional mechanism for costly punishment to achieve yet higher scores, while Gemini 1.5 Flash and GPT-4o fail to do so. For each model class, we also observe variation in emergent behavior across random seeds, suggesting an understudied sensitive dependence on initial conditions. We suggest that our evaluation regime could inspire an inexpensive and informative new class of LLM benchmarks, focussed on the implications of LLM agent deployment for the cooperative infrastructure of society.

[Arxiv](https://arxiv.org/abs/2412.10270)