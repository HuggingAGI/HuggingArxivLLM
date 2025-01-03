# 文化调色板：多智能体调色板下的文化对齐多元化

发布时间：2024年12月15日

`Agent

理由：这篇论文提出了一个名为Cultural Palette的多智能体框架，用于解决大型语言模型在文化对齐方面的挑战。该框架通过集成五个洲级对齐智能体和一个元智能体，动态激活相关文化专业知识，以适应新文化。这种多智能体的设计和协作机制明显属于Agent领域的研究。` `文化研究` `人工智能`

> Cultural Palette: Pluralising Culture Alignment via Multi-agent Palette

# 摘要

> 尽管大型语言模型（LLMs）在生成任务上表现出色，但在与多样文化价值观对齐方面仍面临挑战，主要源于其固有的单一文化偏见和难以捕捉微妙文化语义。现有方法在微调后对未知文化的适应性不足。受五大洲文化地理的启发，我们提出了Cultural Palette，一个多智能体框架，用于文化对齐。我们首先利用LLMs合成了五色文化调色板数据集，捕捉了五大洲社会对话中的多样文化价值观。在此基础上，Cultural Palette通过我们卓越的文化MoErges对齐技术，将五个洲级对齐智能体与一个元智能体集成，根据用户提示动态激活相关文化专业知识，以适应新文化，这一策略在整体文化价值对齐上优于其他联合和合并对齐方法。每个洲级智能体生成文化草稿，随后由元智能体进行精炼和自我调节，最终生成文化对齐的响应。多国实验表明，Cultural Palette在文化对齐方面超越了现有基线。

> Large language models (LLMs) face challenges in aligning with diverse cultural values despite their remarkable performance in generation, which stems from inherent monocultural biases and difficulties in capturing nuanced cultural semantics. Existing methods lack adaptability to unkown culture after finetuning. Inspired by cultural geography across five continents, we propose Cultural Palette, a multi-agent framework for cultural alignment. We first introduce the Pentachromatic Cultural Palette Dataset synthesized using LLMs to capture diverse cultural values from social dialogues across five continents. Building on this, Cultural Palette integrates five continent-level alignment agents with a meta-agent using our superior Cultural MoErges alignment technique by dynamically activating relevant cultural expertise based on user prompts to adapting new culture, which outperforms other joint and merging alignment strategies in overall cultural value alignment. Each continent agent generates a cultural draft, which is then refined and self-regulated by the meta-agent to produce the final culturally aligned response. Experiments across various countries demonstrate that Cultural Palette surpasses existing baselines in cultural alignment.

[Arxiv](https://arxiv.org/abs/2412.11167)