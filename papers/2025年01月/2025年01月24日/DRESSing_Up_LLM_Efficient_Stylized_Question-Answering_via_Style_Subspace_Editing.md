# DRESSing Up LLM: 通过风格子空间编辑实现高效风格化问答

发布时间：2025年01月24日

`LLM应用

理由：这篇论文提出了一种名为DRESS的方法，用于生成风格化的大型语言模型（LLM）响应。该方法通过编辑LLM的表示空间来实现风格控制，特别适用于风格化对话代理的开发。论文的核心在于应用LLM技术来解决特定问题（风格化响应生成），并展示了其在NPC创建和角色扮演任务中的有效性。因此，这篇论文应归类为LLM应用。` `对话系统`

> DRESSing Up LLM: Efficient Stylized Question-Answering via Style Subspace Editing

# 摘要

> 我们提出了DRESS，一种通过表示编辑生成风格化LLM响应的创新方法。现有方法如提示和微调在复杂风格适应上表现不足或计算成本高，尤其在NPC创建和角色扮演任务中。DRESS利用LLM的过参数化特性，在表示空间中解耦出风格相关子空间进行编辑，最小化对原始语义的影响。通过自适应编辑强度，动态调整风格子空间的导向向量，确保风格保真和语义完整。我们构建了两个风格化QA基准数据集，验证了DRESS的有效性，结果显示其显著优于提示和ITI等基线方法。简言之，DRESS是一种轻量级、无需训练的解决方案，为LLM提供灵活有效的风格控制，特别适合开发风格化对话代理。代码和数据集详见https://github.com/ArthurLeoM/DRESS-LLM。

> We introduce DRESS, a novel approach for generating stylized large language model (LLM) responses through representation editing. Existing methods like prompting and fine-tuning are either insufficient for complex style adaptation or computationally expensive, particularly in tasks like NPC creation or character role-playing. Our approach leverages the over-parameterized nature of LLMs to disentangle a style-relevant subspace within the model's representation space to conduct representation editing, ensuring a minimal impact on the original semantics. By applying adaptive editing strengths, we dynamically adjust the steering vectors in the style subspace to maintain both stylistic fidelity and semantic integrity. We develop two stylized QA benchmark datasets to validate the effectiveness of DRESS, and the results demonstrate significant improvements compared to baseline methods such as prompting and ITI. In short, DRESS is a lightweight, train-free solution for enhancing LLMs with flexible and effective style control, making it particularly useful for developing stylized conversational agents. Codes and benchmark datasets are available at https://github.com/ArthurLeoM/DRESS-LLM.

[Arxiv](https://arxiv.org/abs/2501.14371)