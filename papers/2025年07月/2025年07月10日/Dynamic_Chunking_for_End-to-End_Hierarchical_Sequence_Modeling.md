# # 动态切分在端到端层次化序列建模中的应用

发布时间：2025年07月10日

`LLM理论` `计算机科学`

> Dynamic Chunking for End-to-End Hierarchical Sequence Modeling

# 摘要

> 尽管近年来语言模型（LMs）取得了令人瞩目的进步，这些进步主要得益于从为特定任务设计的专用模型转向基于强大架构（如Transformer）的通用模型，这些模型从原始数据中学习一切。然而，诸如分词等预处理步骤仍然是实现真正端到端基础模型的障碍。我们引入了一系列新技术，实现了动态分块机制，该机制能够自动学习内容和上下文相关的分段策略，并与模型的其他部分联合学习。将这些技术整合到显式的分层网络（H-Net）中，可以将传统的（隐式分层的）分词-LM-去分词管道替换为一个完全端到端学习的单一模型。当计算资源和数据相匹配时，一个在字节级别运行的单阶段分层H-Net的表现优于基于BPE分词的强Transformer语言模型。通过将分层结构扩展到多个阶段，进一步通过建模多个抽象层次来提升性能，展现出显著更好的数据扩展性，性能甚至接近两倍大小的基于分词的Transformer模型。在英文数据上预训练的H-Net显示出显著提升的字符级别鲁棒性，并且无需任何启发式规则或显式监督，就能学习到有意义的数据相关分块策略。最后，H-Net相对于传统分词管道的改进在分词启发式较弱的语言和模态中表现得更加突出，例如中文、代码或DNA序列（数据效率比基线高出近4倍），这证明了真正端到端模型从未经处理数据中学习和扩展的潜力。

> Despite incredible progress in language models (LMs) in recent years, largely resulting from moving away from specialized models designed for specific tasks to general models based on powerful architectures (e.g. the Transformer) that learn everything from raw data, pre-processing steps such as tokenization remain a barrier to true end-to-end foundation models. We introduce a collection of new techniques that enable a dynamic chunking mechanism which automatically learns content -- and context -- dependent segmentation strategies learned jointly with the rest of the model. Incorporating this into an explicit hierarchical network (H-Net) allows replacing the (implicitly hierarchical) tokenization-LM-detokenization pipeline with a single model learned fully end-to-end. When compute- and data- matched, an H-Net with one stage of hierarchy operating at the byte level outperforms a strong Transformer language model operating over BPE tokens. Iterating the hierarchy to multiple stages further increases its performance by modeling multiple levels of abstraction, demonstrating significantly better scaling with data and matching a token-based Transformer of twice its size. H-Nets pretrained on English show significantly increased character-level robustness, and qualitatively learn meaningful data-dependent chunking strategies without any heuristics or explicit supervision. Finally, the H-Net's improvement over tokenized pipelines is further increased in languages and modalities with weaker tokenization heuristics, such as Chinese and code, or DNA sequences (nearly 4x improvement in data efficiency over baselines), showing the potential of true end-to-end models that learn and scale better from unprocessed data.

[Arxiv](https://arxiv.org/abs/2507.07955)