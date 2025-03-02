# # 用视觉-语言模型重新赋能科学文献

发布时间：2025年02月26日

`LLM应用`

> Repurposing the scientific literature with vision-language models

# 摘要

> # 摘要  
    在 AI for Science 的研究中，我们常常关注如何利用 AI 技术增强科学过程或整个科学方法的某些部分；那么 AI 在科学出版物中的应用又如何呢？同行评审期刊是专业领域知识的重要存储库，使用特定学科的语言编写，这与用于训练大多数大型语言模型（LLMs）和视觉-语言模型（VLMs）的通用网络内容大不相同。我们假设，通过将一系列科学期刊与生成式 AI 模型相结合，我们可以发明用于科学交流、教育和临床护理的新工具。  
    我们将 23,000 篇神经外科期刊文章转化为包含 1.34 亿字和 7.8 万张图像-说明对的多模态数据库——NeuroPubs，并基于此开发了 6 个数据集用于构建 AI 模型。我们展示了 NeuroPubs 的内容在与更广泛的数据集和 PubMed 相比时，能够独特地代表神经外科特定的临床背景。  
    在出版领域，我们使用通用 VLM 自动从文章生成图形摘要。70% 的图形摘要被编辑委员会评为无需修改即可直接发表。在教育领域，我们以 ABNS 书面考试的风格生成了 89,587 个测试问题，这些试题被实习和资深神经外科医生认为有 54% 的可能性与真实试题无法区分。我们利用这些试题配合课程学习过程，追踪知识获取情况，同时训练我们拥有 340 亿参数的 VLM（CNS-Obsidian）。  
    在一项盲法随机对照试验中，我们证明了 CNS-Obsidian 作为神经外科服务的诊断协作者并不劣于 GPT-4o（p = 0.1154）。我们的研究为 Science with AI 奠定了新的基础，并建立了一个框架，以利用最先进的生成式人工智能提升科学交流，同时保持严格的质量标准。

> Research in AI for Science often focuses on using AI technologies to augment components of the scientific process, or in some cases, the entire scientific method; how about AI for scientific publications? Peer-reviewed journals are foundational repositories of specialized knowledge, written in discipline-specific language that differs from general Internet content used to train most large language models (LLMs) and vision-language models (VLMs). We hypothesized that by combining a family of scientific journals with generative AI models, we could invent novel tools for scientific communication, education, and clinical care. We converted 23,000 articles from Neurosurgery Publications into a multimodal database - NeuroPubs - of 134 million words and 78,000 image-caption pairs to develop six datasets for building AI models. We showed that the content of NeuroPubs uniquely represents neurosurgery-specific clinical contexts compared with broader datasets and PubMed. For publishing, we employed generalist VLMs to automatically generate graphical abstracts from articles. Editorial board members rated 70% of these as ready for publication without further edits. For education, we generated 89,587 test questions in the style of the ABNS written board exam, which trainee and faculty neurosurgeons found indistinguishable from genuine examples 54% of the time. We used these questions alongside a curriculum learning process to track knowledge acquisition while training our 34 billion-parameter VLM (CNS-Obsidian). In a blinded, randomized controlled trial, we demonstrated the non-inferiority of CNS-Obsidian to GPT-4o (p = 0.1154) as a diagnostic copilot for a neurosurgical service. Our findings lay a novel foundation for AI with Science and establish a framework to elevate scientific communication using state-of-the-art generative artificial intelligence while maintaining rigorous quality standards.

[Arxiv](https://arxiv.org/abs/2502.19546)