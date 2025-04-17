# # 选择性演示检索：提升隐性仇恨言论检测效果

发布时间：2025年04月16日

`LLM应用` `社交媒体`

> Selective Demonstration Retrieval for Improved Implicit Hate Speech Detection

# 摘要

> 仇恨言论检测是自然语言处理领域的重要课题，对于维护在线社区安全不可或缺。然而，识别隐性仇恨言论——那些以微妙或间接方式传达恶意的内容——仍是一项重大挑战。与显性仇恨言论不同，隐性表达往往依赖于上下文、文化细节和隐藏偏见，使其更难一致识别。此外，这类言论的解读受到外部知识和人口统计偏见的影响，导致不同语言模型的检测结果大相径庭。更值得注意的是，大型语言模型对有毒语言和弱势群体提及表现出过度敏感，这容易导致误分类。这种敏感性不仅造成假阳性（错误标记无害言论为仇恨），还引发假阴性（未能识别真正有害内容）。为解决这些问题，我们提出了一种无需模型微调的创新方法，通过上下文学习提升检测能力。该方法通过自适应检索与目标最相关的演示，增强上下文理解。实验结果表明，我们的方法显著优于现有技术。实现细节和代码将在 TBD 提供。

> Hate speech detection is a crucial area of research in natural language processing, essential for ensuring online community safety. However, detecting implicit hate speech, where harmful intent is conveyed in subtle or indirect ways, remains a major challenge. Unlike explicit hate speech, implicit expressions often depend on context, cultural subtleties, and hidden biases, making them more challenging to identify consistently. Additionally, the interpretation of such speech is influenced by external knowledge and demographic biases, resulting in varied detection results across different language models. Furthermore, Large Language Models often show heightened sensitivity to toxic language and references to vulnerable groups, which can lead to misclassifications. This over-sensitivity results in false positives (incorrectly identifying harmless statements as hateful) and false negatives (failing to detect genuinely harmful content). Addressing these issues requires methods that not only improve detection precision but also reduce model biases and enhance robustness. To address these challenges, we propose a novel method, which utilizes in-context learning without requiring model fine-tuning. By adaptively retrieving demonstrations that focus on similar groups or those with the highest similarity scores, our approach enhances contextual comprehension. Experimental results show that our method outperforms current state-of-the-art techniques. Implementation details and code are available at TBD.

[Arxiv](https://arxiv.org/abs/2504.12082)