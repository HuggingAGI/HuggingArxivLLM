# 放大化漏洞：针对基于LLM的多智能体辩论的结构化越狱攻击

发布时间：2025年04月23日

`Agent` `多智能体系统`

> Amplified Vulnerabilities: Structured Jailbreak Attacks on LLM-based Multi-Agent Debate

# 摘要

> 多智能体辩论（MAD）通过利用大型语言模型（LLMs）间的协作互动，旨在增强复杂任务的推理能力。然而，其迭代对话和角色扮演特性，尤其是对越狱攻击的易感性，目前仍存在严重研究空白。本文系统性地研究了四种基于主流商用LLMs（GPT-4o、GPT-4、GPT-3.5-turbo和DeepSeek）构建的知名MAD框架的越狱漏洞。我们提出了一种新颖的结构化提示重写框架，通过叙事封装、角色驱动升级、迭代优化和修辞模糊等手段，专门设计用于挖掘MAD动态。实验表明，与单智能体设置相比，MAD系统本质上更加脆弱。我们的攻击方法显著加剧了这一脆弱性，将平均有害性从28.14%提升至80.34%，并在某些场景下实现高达80%的攻击成功率。这些发现揭示了MAD架构的固有漏洞，并强调了在实际部署前开发强大防御机制的迫切需求。

> Multi-Agent Debate (MAD), leveraging collaborative interactions among Large Language Models (LLMs), aim to enhance reasoning capabilities in complex tasks. However, the security implications of their iterative dialogues and role-playing characteristics, particularly susceptibility to jailbreak attacks eliciting harmful content, remain critically underexplored. This paper systematically investigates the jailbreak vulnerabilities of four prominent MAD frameworks built upon leading commercial LLMs (GPT-4o, GPT-4, GPT-3.5-turbo, and DeepSeek) without compromising internal agents. We introduce a novel structured prompt-rewriting framework specifically designed to exploit MAD dynamics via narrative encapsulation, role-driven escalation, iterative refinement, and rhetorical obfuscation. Our extensive experiments demonstrate that MAD systems are inherently more vulnerable than single-agent setups. Crucially, our proposed attack methodology significantly amplifies this fragility, increasing average harmfulness from 28.14% to 80.34% and achieving attack success rates as high as 80% in certain scenarios. These findings reveal intrinsic vulnerabilities in MAD architectures and underscore the urgent need for robust, specialized defenses prior to real-world deployment.

[Arxiv](https://arxiv.org/abs/2504.16489)