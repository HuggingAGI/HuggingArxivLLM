# 本研究致力于运用大型语言模型（LLM）技术从专利文本中高效抽取矛盾信息，以揭示潜在的问题与矛盾点。

发布时间：2024年03月21日

`LLM应用`

> LLM-based Extraction of Contradictions from Patents

# 摘要

> 自上世纪50年代起，TRIZ理论揭示了专利及其蕴含的技术矛盾是推动创新产品研发的关键启示源泉。然而，传统的TRIZ基于历史专利分析，并未充分利用现今专利中不断涌现的最新技术解决方案。面对海量、冗长且复杂的专利文献，现代专利检索与分析亟待突破单纯依赖关键词的方法。近来的专利检索与分析研究热点转向了运用像Google BERT这样的神经网络Transformer语言模型构建的密集向量表示法，这些技术广泛应用于检索优化、问答系统、摘要生成和关键概念提取等领域。在专利摘要和关键概念提取方法中，一个重要的探索方向是识别并提取一般性的发明概念（包括问题、解决方案、发明优势、参数及矛盾等TRIZ核心要素）。经过微调后的BERT风格语言模型目前在句级分类任务上引领着发明概念提取的前沿水平，但在处理更为复杂的矛盾这一抽象概念时，尚存挑战。本文进一步探索，提出一种利用Prompt Engineering技术结合生成型大型语言模型GPT-4（由OpenAI研发），直接从专利文本中抽提TRIZ矛盾的新方法。通过整合LangChain框架，仅通过一次提示操作就能完成矛盾检测、相关句子提取、矛盾概括、参数抽取并将之对应到39个抽象的TRIZ工程参数类别中。实验结果显示，未经专门训练的“开箱即用”GPT-4模型已成为现有专利矛盾提取方法的一种有力竞争者。

> Already since the 1950s TRIZ shows that patents and the technical contradictions they solve are an important source of inspiration for the development of innovative products. However, TRIZ is a heuristic based on a historic patent analysis and does not make use of the ever-increasing number of latest technological solutions in current patents. Because of the huge number of patents, their length, and, last but not least, their complexity there is a need for modern patent retrieval and patent analysis to go beyond keyword-oriented methods. Recent advances in patent retrieval and analysis mainly focus on dense vectors based on neural AI Transformer language models like Google BERT. They are, for example, used for dense retrieval, question answering or summarization and key concept extraction. A research focus within the methods for patent summarization and key concept extraction are generic inventive concepts respectively TRIZ concepts like problems, solutions, advantage of invention, parameters, and contradictions. Succeeding rule-based approaches, finetuned BERT-like language models for sentence-wise classification represent the state-of-the-art of inventive concept extraction. While they work comparatively well for basic concepts like problems or solutions, contradictions - as a more complex abstraction - remain a challenge for these models. This paper goes one step further, as it presents a method to extract TRIZ contradictions from patent texts based on Prompt Engineering using a generative Large Language Model (LLM), namely OpenAI's GPT-4. Contradiction detection, sentence extraction, contradiction summarization, parameter extraction and assignment to the 39 abstract TRIZ engineering parameters are all performed in a single prompt using the LangChain framework. Our results show that "off-the-shelf" GPT-4 is a serious alternative to existing approaches.

[Arxiv](https://arxiv.org/abs/2403.14258)