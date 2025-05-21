# 超越文本：揭示多模态检索增强生成中的隐私漏洞

发布时间：2025年05月20日

`RAG` `多模态` `隐私保护`

> Beyond Text: Unveiling Privacy Vulnerabilities in Multi-modal Retrieval-Augmented Generation

# 摘要

> 多模态检索增强生成（MRAG）系统通过整合外部多模态数据库提升了大型语言模型（LMMs）的能力，但同时也引入了未被探索的隐私漏洞。尽管基于文本的RAG隐私风险已被研究，但多模态数据带来了独特的挑战。我们提供了首个针对视觉语言和语音语言模态的MRAG隐私漏洞系统分析。通过一种新型的组合结构化提示攻击，在黑盒环境下，我们展示了攻击者如何通过操纵查询提取隐私信息。实验结果表明，LMMs既能直接生成与检索内容相似的输出，也能产生间接暴露敏感信息的描述，突显了开发稳健隐私保护MRAG技术的迫切需求。

> Multimodal Retrieval-Augmented Generation (MRAG) systems enhance LMMs by integrating external multimodal databases, but introduce unexplored privacy vulnerabilities. While text-based RAG privacy risks have been studied, multimodal data presents unique challenges. We provide the first systematic analysis of MRAG privacy vulnerabilities across vision-language and speech-language modalities. Using a novel compositional structured prompt attack in a black-box setting, we demonstrate how attackers can extract private information by manipulating queries. Our experiments reveal that LMMs can both directly generate outputs resembling retrieved content and produce descriptions that indirectly expose sensitive information, highlighting the urgent need for robust privacy-preserving MRAG techniques.

[Arxiv](https://arxiv.org/abs/2505.13957)