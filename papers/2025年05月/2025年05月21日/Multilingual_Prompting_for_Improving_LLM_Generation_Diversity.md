# 提升大型语言模型生成多样性的多语言提示方法

发布时间：2025年05月21日

`LLM应用` `文化多样性` `跨文化交流`

> Multilingual Prompting for Improving LLM Generation Diversity

# 摘要

> 大型语言模型（LLMs）在生成内容时，常常缺乏文化代表性，无论是在表达观点还是回答事实性问题时都存在这一问题。为了解决这个问题，我们提出了多语言提示方法：一种通过在基础提示中加入来自多种文化的语言和文化线索，生成多个提示变体，进而生成响应并整合结果的提示技术。基于LLMs具有语言特异性知识的证据，多语言提示旨在通过激活模型训练数据中更广泛的文化知识来增加多样性。通过在多个模型（包括GPT-4o、GPT-4o-mini、LLaMA 70B和LLaMA 8B）上的实验，我们发现，多语言提示在提升多样性方面始终优于现有的增强技术，如高温采样、逐步回忆和角色提示。进一步的分析表明，多语言提示的效果因语言资源水平和模型规模而异，并且提示语言与文化线索的对齐可以减少对文化特定信息的错误生成。

> Large Language Models (LLMs) are known to lack cultural representation and overall diversity in their generations, from expressing opinions to answering factual questions. To mitigate this problem, we propose multilingual prompting: a prompting method which generates several variations of a base prompt with added cultural and linguistic cues from several cultures, generates responses, and then combines the results. Building on evidence that LLMs have language-specific knowledge, multilingual prompting seeks to increase diversity by activating a broader range of cultural knowledge embedded in model training data. Through experiments across multiple models (GPT-4o, GPT-4o-mini, LLaMA 70B, and LLaMA 8B), we show that multilingual prompting consistently outperforms existing diversity-enhancing techniques such as high-temperature sampling, step-by-step recall, and personas prompting. Further analyses show that the benefits of multilingual prompting vary with language resource level and model size, and that aligning the prompting language with the cultural cues reduces hallucination about culturally-specific information.

[Arxiv](https://arxiv.org/abs/2505.15229)