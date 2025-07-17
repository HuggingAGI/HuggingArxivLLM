# SynCoGen：通过反应与坐标建模的联合方法生成可合成三维分子

发布时间：2025年07月15日

`其他` `药物设计` `分子生成`

> SynCoGen: Synthesizable 3D Molecule Generation via Joint Reaction and Coordinate Modeling

# 摘要

> 在生成小分子设计中，确保合成可行性仍然是一个重大挑战。尽管可合成分子生成方面取得了令人鼓舞的成果，但这些研究主要局限于二维分子图表示，限制了基于几何的条件生成能力。我们提出了SynCoGen（合成共生成），这是一个结合了掩码图扩散和流匹配的单一框架，用于生成可合成的3D分子。SynCoGen从分子构建块、化学反应和原子坐标的联合分布中进行采样。我们整理了SynSpace数据集，包含超过60万种具有合成意识的构建块图和330万个构象。SynCoGen在无条件小分子图和构象生成方面表现卓越，同时在药物发现中用于蛋白质配体生成的零样本分子连接器设计方面也表现出色。总体而言，这种多模态公式为未来基于非自回归分子生成的应用奠定了基础，包括类扩展、先导优化和直接结构条件生成。

> Ensuring synthesizability in generative small molecule design remains a major challenge. While recent developments in synthesizable molecule generation have demonstrated promising results, these efforts have been largely confined to 2D molecular graph representations, limiting the ability to perform geometry-based conditional generation. In this work, we present SynCoGen (Synthesizable Co-Generation), a single framework that combines simultaneous masked graph diffusion and flow matching for synthesizable 3D molecule generation. SynCoGen samples from the joint distribution of molecular building blocks, chemical reactions, and atomic coordinates. To train the model, we curated SynSpace, a dataset containing over 600K synthesis-aware building block graphs and 3.3M conformers. SynCoGen achieves state-of-the-art performance in unconditional small molecule graph and conformer generation, and the model delivers competitive performance in zero-shot molecular linker design for protein ligand generation in drug discovery. Overall, this multimodal formulation represents a foundation for future applications enabled by non-autoregressive molecular generation, including analog expansion, lead optimization, and direct structure conditioning.

[Arxiv](https://arxiv.org/abs/2507.11818)