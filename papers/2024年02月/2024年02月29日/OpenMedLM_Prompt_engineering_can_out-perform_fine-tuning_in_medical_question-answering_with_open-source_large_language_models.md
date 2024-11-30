# OpenMedLM 显示，在使用开源大型语言模型处理医疗问答场景时，通过巧妙的提示工程技术，其表现甚至可以优于传统的微调方法。

发布时间：2024年02月29日

`LLM应用`

> OpenMedLM: Prompt engineering can out-perform fine-tuning in medical question-answering with open-source large language models

# 摘要

> 随着LLMs日渐擅长处理各类专业任务，并有助于拓宽医疗知识的公正获取途径，大部分医学专用LLMs均借助大量的专业医疗数据进行深度微调，消耗了巨大且昂贵的计算资源。尽管很多顶尖LLMs是封闭的专有模型，仅少数研究团队能接触，但开源（OS）模型凭借其性能的大幅提升及与生俱来的透明性和对医疗行业所需的合规性的支持，正逐渐成为医学LLMs发展的重要驱动力。为此，我们推出OpenMedLM这一创新的提示平台，它能在医学基准测试上展示OS LLMs的最新前沿成果。我们选取了一系列规模在70亿至700亿参数区间的OS基础LLMs，在四个权威医学基准测试（MedQA、MedMCQA、PubMedQA和MMLU医学子集）上进行了评测，并运用了多种提示策略，包括零样本、小样本学习、随机及kNN选择的链式思维方法，以及集成/自我一致性投票机制。结果显示，OpenMedLM在三个主流医学LLM基准测试上刷新了OS模型的最高纪录，超越了以往那些依赖耗资巨大的深度微调而取得最好成绩的OS模型。该模型在MedQA测试上获得了72.6%的精确度，比此前最佳成绩提高了2.4%，并在MMLU医学子集测试中达到81.7%的精确度，成为首个在这个基准上突破80%精确度大关的OS LLM。这一研究不仅揭示了至今为止在其他地方尚未被充分认识的OS LLMs所具备的医学特异性优势，还展现了通过深化提示工程技术，有效提升可获得的LLMs在医学应用场景下的性能潜力。

> LLMs have become increasingly capable at accomplishing a range of specialized-tasks and can be utilized to expand equitable access to medical knowledge. Most medical LLMs have involved extensive fine-tuning, leveraging specialized medical data and significant, thus costly, amounts of computational power. Many of the top performing LLMs are proprietary and their access is limited to very few research groups. However, open-source (OS) models represent a key area of growth for medical LLMs due to significant improvements in performance and an inherent ability to provide the transparency and compliance required in healthcare. We present OpenMedLM, a prompting platform which delivers state-of-the-art (SOTA) performance for OS LLMs on medical benchmarks. We evaluated a range of OS foundation LLMs (7B-70B) on four medical benchmarks (MedQA, MedMCQA, PubMedQA, MMLU medical-subset). We employed a series of prompting strategies, including zero-shot, few-shot, chain-of-thought (random selection and kNN selection), and ensemble/self-consistency voting. We found that OpenMedLM delivers OS SOTA results on three common medical LLM benchmarks, surpassing the previous best performing OS models that leveraged computationally costly extensive fine-tuning. The model delivers a 72.6% accuracy on the MedQA benchmark, outperforming the previous SOTA by 2.4%, and achieves 81.7% accuracy on the MMLU medical-subset, establishing itself as the first OS LLM to surpass 80% accuracy on this benchmark. Our results highlight medical-specific emergent properties in OS LLMs which have not yet been documented to date elsewhere, and showcase the benefits of further leveraging prompt engineering to improve the performance of accessible LLMs for medical applications.

[Arxiv](https://arxiv.org/abs/2402.19371)