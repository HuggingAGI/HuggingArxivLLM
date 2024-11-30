# 借助基础模型API，我们推出了针对文本的第二版差分隐私合成数据技术。这项技术利用基础模型能力，在保证数据隐私性的同时生成高质量的合成文本数据。

发布时间：2024年03月04日

`LLM应用`

> Differentially Private Synthetic Data via Foundation Model APIs 2: Text

# 摘要

> 随着机器学习算法对文本数据的挖掘能力提升，文本数据价值凸显，但现实中大量的优质文本因涉及隐私而无法自由分享使用。采用具备正式隐私保障——差分隐私（DP）技术，生成私密文本的合成复制品，为这一问题带来了一个颇具潜力且可规模化的方法。然而，当前的技术路线通常要求对大型语言模型（如GPT-3.5等）在私密数据上进行DP微调以生成DP合成数据，不仅对商业级LLMs不适用，同时也对开源LLMs提出了较高的计算资源需求。近期，Lin等人在2024年提出的Private Evolution (PE)算法革新性地仅通过扩散模型的API接口即可生成DP合成图像。在此基础上，我们创新设计并命名Aug-PE的增强版PE算法，将其应用于更为复杂的文本场景。我们巧妙运用LLM的API访问权限，无需进行任何模型训练，便能直接生成满足DP标准的合成文本。我们对三项权威数据集进行了广泛深入的实验，结果表明Aug-PE所生成的DP合成文本在实用性上与当前最优的DP微调方法相当。这有力证明了仅依靠LLMs的API接口即可产出高品质、满足DP标准的合成文本，从而极大地拓宽了实现隐私保护型LLM应用的便捷路径。相关代码和数据已公开在https://github.com/AI-secure/aug-pe。

> Text data has become extremely valuable due to the emergence of machine learning algorithms that learn from it. A lot of high-quality text data generated in the real world is private and therefore cannot be shared or used freely due to privacy concerns. Generating synthetic replicas of private text data with a formal privacy guarantee, i.e., differential privacy (DP), offers a promising and scalable solution. However, existing methods necessitate DP finetuning of large language models (LLMs) on private data to generate DP synthetic data. This approach is not viable for proprietary LLMs (e.g., GPT-3.5) and also demands considerable computational resources for open-source LLMs. Lin et al. (2024) recently introduced the Private Evolution (PE) algorithm to generate DP synthetic images with only API access to diffusion models. In this work, we propose an augmented PE algorithm, named Aug-PE, that applies to the complex setting of text. We use API access to an LLM and generate DP synthetic text without any model training. We conduct comprehensive experiments on three benchmark datasets. Our results demonstrate that Aug-PE produces DP synthetic text that yields competitive utility with the SOTA DP finetuning baselines. This underscores the feasibility of relying solely on API access of LLMs to produce high-quality DP synthetic texts, thereby facilitating more accessible routes to privacy-preserving LLM applications. Our code and data are available at https://github.com/AI-secure/aug-pe.

[Arxiv](https://arxiv.org/abs/2403.01749)