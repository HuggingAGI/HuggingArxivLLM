# # 基于领域划分的大型语言模型越狱漏洞分类框架

发布时间：2025年04月07日

`LLM理论` `人工智能` `网络安全`

> A Domain-Based Taxonomy of Jailbreak Vulnerabilities in Large Language Models

# 摘要

> 大型语言模型 (LLMs) 的研究是开放世界机器学习中的重要领域。虽然 LLMs 在自然语言处理方面表现出色，但它们也面临诸多挑战，包括一致性问题、幻觉现象以及越狱漏洞。越狱攻击通过构造能够绕过对齐防护机制的提示，生成危害 LLM 完整性的不安全输出。本研究专注于越狱漏洞这一挑战，并基于 LLMs 的训练领域提出了一种全新的分类法。通过概括、目标和鲁棒性差距，我们对对齐失败进行了表征。我们的主要贡献是一种从不同语言学领域视角审视越狱问题的方法，这些领域在 LLMs 的训练与对齐过程中逐渐浮现。这一视角不仅揭示了现有方法的局限性，还使我们能够根据攻击所利用的模型固有缺陷对越狱攻击进行分类。与传统分类方法（如基于提示模板的分类）不同，我们的方法为理解 LLMs 的行为提供了更深层次的洞察。我们引入了一个包含四个类别的分类体系——错配概括、竞争目标、对抗鲁棒性以及混合攻击——从而揭示了越狱漏洞的本质特征。最后，我们总结了从这项分类研究中得出的关键启示。

> The study of large language models (LLMs) is a key area in open-world machine learning. Although LLMs demonstrate remarkable natural language processing capabilities, they also face several challenges, including consistency issues, hallucinations, and jailbreak vulnerabilities. Jailbreaking refers to the crafting of prompts that bypass alignment safeguards, leading to unsafe outputs that compromise the integrity of LLMs. This work specifically focuses on the challenge of jailbreak vulnerabilities and introduces a novel taxonomy of jailbreak attacks grounded in the training domains of LLMs. It characterizes alignment failures through generalization, objectives, and robustness gaps. Our primary contribution is a perspective on jailbreak, framed through the different linguistic domains that emerge during LLM training and alignment. This viewpoint highlights the limitations of existing approaches and enables us to classify jailbreak attacks on the basis of the underlying model deficiencies they exploit. Unlike conventional classifications that categorize attacks based on prompt construction methods (e.g., prompt templating), our approach provides a deeper understanding of LLM behavior. We introduce a taxonomy with four categories -- mismatched generalization, competing objectives, adversarial robustness, and mixed attacks -- offering insights into the fundamental nature of jailbreak vulnerabilities. Finally, we present key lessons derived from this taxonomic study.

[Arxiv](https://arxiv.org/abs/2504.04976)