# GAP：基于图的辅助提示用于对话式药物推荐系统

发布时间：2025年05月19日

`LLM应用

论文摘要：用药建议已成为医疗领域的重要任务，尤其在衡量医疗对话系统 (MDS) 的准确性和安全性方面。与基于电子健康记录 (EHR) 的推荐任务不同，对话式用药建议需要研究患者与医生之间的互动细节，这一点至关重要，但在 EHR 中可能不存在。大型语言模型 (LLM) 的近期进展扩展了医疗对话领域。这些 LLM 可以解读患者的意图并提供包括用药建议在内的医疗建议，但仍有一些挑战值得重视。在多轮对话中，LLM 可能会忽略细粒度的医疗信息或对话轮次之间的联系，这对提供准确建议至关重要。此外，当缺乏特定领域知识时，LLM 可能会生成非事实性的回复，在医疗领域这更具风险。为了解决这些挑战，我们提出了一种基于图的辅助提示框架（GAP），用于对话式用药建议。它从对话中提取医疗概念及其对应状态，构建一个以患者为中心的显式图，可以描述被忽视但重要的信息。此外，结合外部医疗知识图谱，GAP 可以生成丰富的查询和提示，从而从多个来源检索信息，减少非事实性回复。我们在一个对话式用药建议数据集上对 GAP 进行了评估，并进一步探索了其在更具挑战性的动态诊断访谈场景中的潜力。大量实验表明，与强基线模型相比，GAP 的性能具有竞争力。

LLM应用` `对话系统`

> GAP: Graph-Assisted Prompts for Dialogue-based Medication Recommendation

# 摘要

> 用药建议已成为医疗领域的重要任务，尤其在衡量医疗对话系统 (MDS) 的准确性和安全性方面。与基于电子健康记录 (EHR) 的推荐任务不同，对话式用药建议需要研究患者与医生之间的互动细节，这一点至关重要，但在 EHR 中可能不存在。大型语言模型 (LLM) 的近期进展扩展了医疗对话领域。这些 LLM 可以解读患者的意图并提供包括用药建议在内的医疗建议，但仍有一些挑战值得重视。在多轮对话中，LLM 可能会忽略细粒度的医疗信息或对话轮次之间的联系，这对提供准确建议至关重要。此外，当缺乏特定领域知识时，LLM 可能会生成非事实性的回复，在医疗领域这更具风险。为了解决这些挑战，我们提出了一种基于图的辅助提示框架（GAP），用于对话式用药建议。它从对话中提取医疗概念及其对应状态，构建一个以患者为中心的显式图，可以描述被忽视但重要的信息。此外，结合外部医疗知识图谱，GAP 可以生成丰富的查询和提示，从而从多个来源检索信息，减少非事实性回复。我们在一个对话式用药建议数据集上对 GAP 进行了评估，并进一步探索了其在更具挑战性的动态诊断访谈场景中的潜力。大量实验表明，与强基线模型相比，GAP 的性能具有竞争力。

> Medication recommendations have become an important task in the healthcare domain, especially in measuring the accuracy and safety of medical dialogue systems (MDS). Different from the recommendation task based on electronic health records (EHRs), dialogue-based medication recommendations require research on the interaction details between patients and doctors, which is crucial but may not exist in EHRs. Recent advancements in large language models (LLM) have extended the medical dialogue domain. These LLMs can interpret patients' intent and provide medical suggestions including medication recommendations, but some challenges are still worth attention. During a multi-turn dialogue, LLMs may ignore the fine-grained medical information or connections across the dialogue turns, which is vital for providing accurate suggestions. Besides, LLMs may generate non-factual responses when there is a lack of domain-specific knowledge, which is more risky in the medical domain. To address these challenges, we propose a \textbf{G}raph-\textbf{A}ssisted \textbf{P}rompts (\textbf{GAP}) framework for dialogue-based medication recommendation. It extracts medical concepts and corresponding states from dialogue to construct an explicitly patient-centric graph, which can describe the neglected but important information. Further, combined with external medical knowledge graphs, GAP can generate abundant queries and prompts, thus retrieving information from multiple sources to reduce the non-factual responses. We evaluate GAP on a dialogue-based medication recommendation dataset and further explore its potential in a more difficult scenario, dynamically diagnostic interviewing. Extensive experiments demonstrate its competitive performance when compared with strong baselines.

[Arxiv](https://arxiv.org/abs/2505.12888)