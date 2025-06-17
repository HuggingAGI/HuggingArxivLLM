# # 安全儿童LLM：评估儿童与AI互动中LLM安全性的发育基准测试

发布时间：2025年06月16日

`LLM应用` `AI安全`

> Safe-Child-LLM: A Developmental Benchmark for Evaluating LLM Safety in Child-AI Interactions

# 摘要

> # 摘要  
随着大型语言模型（LLMs）越来越多地应用于儿童和青少年领域，确保安全且适合年龄的交互已成为一项紧迫的伦理任务。尽管AI安全领域取得了进展，但现有的评估主要集中在成年人身上，忽视了未成年人在使用生成式AI时的独特脆弱性。  
我们引入了Safe-Child-LLM，这是一个全面的基准和数据集，用于系统地评估LLM在两个发育阶段的安全性：儿童（7-12岁）和青少年（13-17岁）。我们的框架包括一个新颖的多部分数据集，包含200个对抗提示，这些提示来自红队语料库（如SG-Bench、HarmBench），并附有人工标注的 jailbreak 成功标签以及标准化的0-5道德拒绝评分。  
我们评估了包括ChatGPT、Claude、Gemini、LLaMA、DeepSeek、Grok、Vicuna和Mistral在内的领先LLMs，发现这些模型在面向儿童的场景中存在关键的安全缺陷。这项工作强调了建立社区驱动的基准以保护年轻用户在LLM交互中的安全的必要性。  
为了促进透明和在道德AI开发方面的协作进步，我们公开发布了我们的基准数据集和评估代码库，地址为https://github.com/The-Responsible-AI-Initiative/Safe_Child_LLM_Benchmark.git

> As Large Language Models (LLMs) increasingly power applications used by children and adolescents, ensuring safe and age-appropriate interactions has become an urgent ethical imperative. Despite progress in AI safety, current evaluations predominantly focus on adults, neglecting the unique vulnerabilities of minors engaging with generative AI. We introduce Safe-Child-LLM, a comprehensive benchmark and dataset for systematically assessing LLM safety across two developmental stages: children (7-12) and adolescents (13-17). Our framework includes a novel multi-part dataset of 200 adversarial prompts, curated from red-teaming corpora (e.g., SG-Bench, HarmBench), with human-annotated labels for jailbreak success and a standardized 0-5 ethical refusal scale. Evaluating leading LLMs -- including ChatGPT, Claude, Gemini, LLaMA, DeepSeek, Grok, Vicuna, and Mistral -- we uncover critical safety deficiencies in child-facing scenarios. This work highlights the need for community-driven benchmarks to protect young users in LLM interactions. To promote transparency and collaborative advancement in ethical AI development, we are publicly releasing both our benchmark datasets and evaluation codebase at https://github.com/The-Responsible-AI-Initiative/Safe_Child_LLM_Benchmark.git

[Arxiv](https://arxiv.org/abs/2506.13510)