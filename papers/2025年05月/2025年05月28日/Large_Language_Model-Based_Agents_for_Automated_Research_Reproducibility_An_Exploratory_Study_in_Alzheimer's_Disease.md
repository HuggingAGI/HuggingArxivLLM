# # 摘要  
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月28日

`LLM应用` `生物医学` `研究自动化`

> Large Language Model-Based Agents for Automated Research Reproducibility: An Exploratory Study in Alzheimer's Disease

# 摘要

> # 目标  
本研究旨在展示大型语言模型 (LLMs) 作为自主代理在利用相同或类似数据集复制已发表研究结果方面的潜力。  

# 材料与方法  
我们采用了国家阿尔茨海默病协调中心 (NACC) 的 "快速访问" 数据集。通过分析基于 NACC 数据的高引用论文，我们筛选出五项可仅凭该数据集重复的研究。借助 GPT-4o，我们构建了一个由 LLM 驱动的模拟研究团队，旨在根据研究摘要、方法部分和数据字典描述编写和执行代码，以动态复制研究发现。  

# 结果  
我们从五项阿尔茨海默病研究的摘要中提取了 35 个关键发现。LLM 代理平均每项研究复制了 53.2% 的发现。数值和范围类发现通常在研究和代理之间存在差异。代理还采用了与原始研究不同的统计方法或参数，尽管总体趋势和显著性有时相似。  

# 讨论  
在某些情况下，基于 LLM 的代理成功复制了研究技术和发现。在其他情况下，由于实现缺陷或方法细节缺失，复制失败。这些差异反映了当前 LLM 在完全自动化可重复性评估方面的局限性。然而，这项早期研究凸显了结构化代理系统在提供可扩展科学严谨性评估方面的潜力。  

# 结论  
这项探索性工作揭示了 LLM 作为自主代理在生物医学研究中自动复制研究的潜力与局限性。

> Objective: To demonstrate the capabilities of Large Language Models (LLMs) as autonomous agents to reproduce findings of published research studies using the same or similar dataset.
  Materials and Methods: We used the "Quick Access" dataset of the National Alzheimer's Coordinating Center (NACC). We identified highly cited published research manuscripts using NACC data and selected five studies that appeared reproducible using this dataset alone. Using GPT-4o, we created a simulated research team of LLM-based autonomous agents tasked with writing and executing code to dynamically reproduce the findings of each study, given only study Abstracts, Methods sections, and data dictionary descriptions of the dataset.
  Results: We extracted 35 key findings described in the Abstracts across 5 Alzheimer's studies. On average, LLM agents approximately reproduced 53.2% of findings per study. Numeric values and range-based findings often differed between studies and agents. The agents also applied statistical methods or parameters that varied from the originals, though overall trends and significance were sometimes similar.
  Discussion: In some cases, LLM-based agents replicated research techniques and findings. In others, they failed due to implementation flaws or missing methodological detail. These discrepancies show the current limits of LLMs in fully automating reproducibility assessments. Still, this early investigation highlights the potential of structured agent-based systems to provide scalable evaluation of scientific rigor.
  Conclusion: This exploratory work illustrates both the promise and limitations of LLMs as autonomous agents for automating reproducibility in biomedical research.

[Arxiv](https://arxiv.org/abs/2505.23852)