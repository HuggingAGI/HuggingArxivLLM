# ConceptSearch：借助 LLMs 实现针对抽象和推理语料库（ARC）的高效程序搜索

发布时间：2024年12月10日

`LLM应用` `人工智能` `程序合成`

> ConceptSearch: Towards Efficient Program Search Using LLMs for Abstraction and Reasoning Corpus (ARC)

# 摘要

> 抽象推理语料库（ARC）给人工智能出了个大难题，它要求具备广泛的泛化和少样本学习能力，可这对当下包括大型语言模型（LLMs）在内的深度学习方法而言，还难以做到。虽说LLMs在程序合成上表现不错，但直接用于ARC却成效有限。为此，我们推出了ConceptSearch，这是一种全新的函数搜索算法，借助LLMs来生成程序，并运用基于概念的评分方法高效引导搜索。和汉明距离这类简单的基于像素的指标不同，ConceptSearch依据程序捕捉输入输出示例中所反映的底层转换概念的能力来进行评估。我们探究了三种评分函数：汉明距离、基于CNN的评分函数以及基于LLM的自然语言评分函数。实验结果显示ConceptSearch效果显著，与直接用GPT-4提示相比，性能大幅提升。而且，我们新颖的基于概念的评分在达到正确解所需的迭代次数方面，比汉明距离的效率高出多达30%。这些发现凸显了在与基于概念的指导相结合时，由LLM驱动的程序搜索在解决像ARC这类具有挑战性的泛化问题上的潜力。代码：https://github.com/kksinghal/concept-search

> The Abstraction and Reasoning Corpus (ARC) poses a significant challenge to artificial intelligence, demanding broad generalization and few-shot learning capabilities that remain elusive for current deep learning methods, including large language models (LLMs). While LLMs excel in program synthesis, their direct application to ARC yields limited success. To address this, we introduce ConceptSearch, a novel function-search algorithm that leverages LLMs for program generation and employs a concept-based scoring method to guide the search efficiently. Unlike simplistic pixel-based metrics like Hamming distance, ConceptSearch evaluates programs on their ability to capture the underlying transformation concept reflected in the input-output examples. We explore three scoring functions: Hamming distance, a CNN-based scoring function, and an LLM-based natural language scoring function. Experimental results demonstrate the effectiveness of ConceptSearch, achieving a significant performance improvement over direct prompting with GPT-4. Moreover, our novel concept-based scoring exhibits up to 30% greater efficiency compared to Hamming distance, measured in terms of the number of iterations required to reach the correct solution. These findings highlight the potential of LLM-driven program search when integrated with concept-based guidance for tackling challenging generalization problems like ARC. Code: https://github.com/kksinghal/concept-search

[Arxiv](https://arxiv.org/abs/2412.07322)