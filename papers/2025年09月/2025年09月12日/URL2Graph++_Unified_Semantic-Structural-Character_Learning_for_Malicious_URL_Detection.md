# URL2Graph++：恶意URL检测的统一语义-结构-字符学习

发布时间：2025年09月12日

`其他` `基础理论`

> URL2Graph++: Unified Semantic-Structural-Character Learning for Malicious URL Detection

# 摘要

> 恶意URL检测一直是网络安全领域的核心难题，主要源于两大原因：(1)互联网的爆炸式增长催生了URL种类的极度多样化，通用检测愈发棘手；(2)攻击者正越来越多地使用复杂混淆手段逃避识别。我们认为，要从根本上破解这些难题，需做到两点：一是通过语义理解提升在海量多样URL集合中的泛化能力，二是精准建模URL结构组成中的上下文关联。本文提出一种融合多粒度图学习与语义嵌入的新型恶意URL检测方法，协同捕获语义、字符级及结构特征，实现稳健的URL分析。为建模URL内部依赖关系，我们首先构建子词与字符双粒度URL图——节点对应URL标记/字符，边则编码共现关系。为获取细粒度嵌入，采用字符级卷积网络初始化节点表示。随后，这两个图通过联合训练的图卷积网络处理，学习统一的图级表示，使模型能捕捉反映共现模式与字符级依赖的互补结构特征。此外，我们借助BERT提取URL的语义表示，实现语义感知理解。最后，引入门控动态融合网络，将语义增强的BERT表示与联合优化的图向量融合，进一步提升检测性能。我们从多个高难度维度对方法进行了全面评估，结果表明，该方法性能超越现有最佳水平（SOTA），甚至优于大型语言模型。

> Malicious URL detection remains a major challenge in cybersecurity, primarily due to two factors: (1) the exponential growth of the Internet has led to an immense diversity of URLs, making generalized detection increasingly difficult; and (2) attackers are increasingly employing sophisticated obfuscation techniques to evade detection. We advocate that addressing these challenges fundamentally requires: (1) obtaining semantic understanding to improve generalization across vast and diverse URL sets, and (2) accurately modeling contextual relationships within the structural composition of URLs. In this paper, we propose a novel malicious URL detection method combining multi-granularity graph learning with semantic embedding to jointly capture semantic, character-level, and structural features for robust URL analysis. To model internal dependencies within URLs, we first construct dual-granularity URL graphs at both subword and character levels, where nodes represent URL tokens/characters and edges encode co-occurrence relationships. To obtain fine-grained embeddings, we initialize node representations using a character-level convolutional network. The two graphs are then processed through jointly trained Graph Convolutional Networks to learn consistent graph-level representations, enabling the model to capture complementary structural features that reflect co-occurrence patterns and character-level dependencies. Furthermore, we employ BERT to derive semantic representations of URLs for semantically aware understanding. Finally, we introduce a gated dynamic fusion network to combine the semantically enriched BERT representations with the jointly optimized graph vectors, further enhancing detection performance. We extensively evaluate our method across multiple challenging dimensions. Results show our method exceeds SOTA performance, including against large language models.

[Arxiv](https://arxiv.org/abs/2509.10287)