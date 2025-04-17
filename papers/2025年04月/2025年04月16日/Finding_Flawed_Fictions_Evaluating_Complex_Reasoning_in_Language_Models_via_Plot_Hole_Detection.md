# 发现漏洞百出的故事：通过情节漏洞检测评估语言模型的复杂推理能力

发布时间：2025年04月16日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在叙事理解、推理以及情节漏洞检测方面的能力。通过开发特定算法和基准测试，评估LLMs在复杂推理任务中的表现，属于对LLM应用的研究。` `人工智能`

> Finding Flawed Fictions: Evaluating Complex Reasoning in Language Models via Plot Hole Detection

# 摘要

> 故事是人类经验的核心。深入理解故事并发现情节漏洞——即破坏故事逻辑或规则的不一致之处——需要复杂的推理能力，包括追踪实体与事件的互动、抽象思维、叙事理解、常识推理以及心智理论。随着大型语言模型（LLMs）在文本生成、解释和修改方面应用的日益广泛，评估其叙事一致性和深度语言理解能力变得至关重要。然而，现有评估标准多集中于表面理解。本研究提出将故事中的情节漏洞检测作为评估LLMs语言理解和推理能力的手段。我们开发了FlawedFictionsMaker算法，可精准地在人类故事中引入情节漏洞。基于此算法，我们创建了FlawedFictions基准，用于评估LLMs的情节漏洞检测能力。该基准具有高抗污染性，经人工筛选确保质量。研究发现，即使允许充分推理，当前先进的LLMs在解决FlawedFictions时仍面临挑战，且随着故事长度增加，性能显著下降。此外，我们发现基于LLM的故事摘要和生成容易引入情节漏洞，与人类创作的故事相比，漏洞检测率分别增加了50%和100%以上。

> Stories are a fundamental aspect of human experience. Engaging deeply with stories and spotting plot holes -- inconsistencies in a storyline that break the internal logic or rules of a story's world -- requires nuanced reasoning skills, including tracking entities and events and their interplay, abstract thinking, pragmatic narrative understanding, commonsense and social reasoning, and theory of mind. As Large Language Models (LLMs) increasingly generate, interpret, and modify text, rigorously assessing their narrative consistency and deeper language understanding becomes critical. However, existing benchmarks focus mainly on surface-level comprehension. In this work, we propose plot hole detection in stories as a proxy to evaluate language understanding and reasoning in LLMs. We introduce FlawedFictionsMaker, a novel algorithm to controllably and carefully synthesize plot holes in human-written stories. Using this algorithm, we construct a benchmark to evaluate LLMs' plot hole detection abilities in stories -- FlawedFictions -- , which is robust to contamination, with human filtering ensuring high quality. We find that state-of-the-art LLMs struggle in accurately solving FlawedFictions regardless of the reasoning effort allowed, with performance significantly degrading as story length increases. Finally, we show that LLM-based story summarization and story generation are prone to introducing plot holes, with more than 50% and 100% increases in plot hole detection rates with respect to human-written originals.

[Arxiv](https://arxiv.org/abs/2504.11900)