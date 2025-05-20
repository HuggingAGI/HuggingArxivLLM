# # **mCLM：一款功能注入、合成友好且模块化的化学语言模型**

发布时间：2025年05月18日

`LLM应用` `药物研发`

> mCLM: A Function-Infused and Synthesis-Friendly Modular Chemical Language Model

# 摘要

> 大型语言模型（LLMs）虽然能理解化学知识并准确生成序列表示，但在提出具有药物样性质的新分子方面仍显不足。此外，LLMs生成的分子往往难以在实验室中合成。为了更有效地推动功能性小分子的发现，LLMs需要掌握分子语言。然而，目前它们受限于从原子层面编码分子。

本文提出，正如将文本分词为（子）词令牌而非字符一样，分子应在功能构建块的层面上进行分解和重组——这些构建块是分子中赋予独特功能并可作为现实世界自动化实验室合成基础的有效单元。基于此，我们推出了mCLM，一种模块化化学语言模型，将分子分解为构建块，并构建自然语言描述的功能与分子构建块的双语语言模型。

通过基于这些功能构建块进行推理，mCLM不仅能够生成易于合成的分子（得益于基于块的化学最新进展），还能以系统化的方式提升分子功能。在对430种FDA批准药物的实验中，mCLM成功改善了6种关键化学功能中的5种，这些功能对确定药物潜力至关重要。更重要的是，mCLM能够同时优化多种功能，并通过多次迭代改进FDA曾拒绝的药物（“失败药物”），显著提升其不足之处。

> Despite their ability to understand chemical knowledge and accurately generate sequential representations, large language models (LLMs) remain limited in their capacity to propose novel molecules with drug-like properties. In addition, the molecules that LLMs propose can often be challenging to make in the lab. To more effectively enable the discovery of functional small molecules, LLMs need to learn a molecular language. However, LLMs are currently limited by encoding molecules from atoms. In this paper, we argue that just like tokenizing texts into (sub-)word tokens instead of characters, molecules should be decomposed and reassembled at the level of functional building blocks, i.e., parts of molecules that bring unique functions and serve as effective building blocks for real-world automated laboratory synthesis. This motivates us to propose mCLM, a modular Chemical-Language Model tokenizing molecules into building blocks and learning a bilingual language model of both natural language descriptions of functions and molecule building blocks. By reasoning on such functional building blocks, mCLM guarantees to generate efficiently synthesizable molecules thanks to recent progress in block-based chemistry, while also improving the functions of molecules in a principled manner. In experiments on 430 FDA-approved drugs, we find mCLM capable of significantly improving 5 out of 6 chemical functions critical to determining drug potentials. More importantly, mCLM can reason on multiple functions and improve the FDA-rejected drugs (``fallen angels'') over multiple iterations to greatly improve their shortcomings.

[Arxiv](https://arxiv.org/abs/2505.12565)