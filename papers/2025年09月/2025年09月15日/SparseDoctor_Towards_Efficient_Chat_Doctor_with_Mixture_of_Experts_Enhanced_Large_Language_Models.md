# SparseDoctor：迈向基于混合专家增强大型语言模型的高效对话医生

发布时间：2025年09月15日

`LLM应用` `医疗健康`

> SparseDoctor: Towards Efficient Chat Doctor with Mixture of Experts Enhanced Large Language Models

# 摘要

> 大型语言模型（LLMs）在医疗问答与临床决策领域成效显著，推动了个性化虚拟医生的效率提升与社会普及。但传统LLM微调策略需更新数十亿参数，导致训练成本（包括时间与资源成本）大幅增加。为提升现有医疗LLMs的效率与性能，探索其在医疗领域的表示能力边界，我们跳出传统的数据视角微调（如监督微调、人类反馈强化学习），设计出新型稀疏医疗LLM——SparseDoctor，其采用对比学习增强的LoRA-MoE（低秩适应-混合专家）架构。该模型的自动路由机制可在对比学习监督下，为不同LoRA专家科学分配计算资源；同时引入新型专家记忆队列机制，进一步提升整体框架效率，避免训练时内存溢出。我们在CMB、CMExam、CMMLU-Med三个典型医疗基准数据集上开展综合评估，结果显示，该LLM性能持续优于华驼GPT系列等强基线模型。

> Large language models (LLMs) have achieved great success in medical question answering and clinical decision-making, promoting the efficiency and popularization of the personalized virtual doctor in society. However, the traditional fine-tuning strategies on LLM require the updates of billions of parameters, substantially increasing the training cost, including the training time and utility cost. To enhance the efficiency and effectiveness of the current medical LLMs and explore the boundary of the representation capability of the LLMs on the medical domain, apart from the traditional fine-tuning strategies from the data perspective (i.e., supervised fine-tuning or reinforcement learning from human feedback), we instead craft a novel sparse medical LLM named SparseDoctor armed with contrastive learning enhanced LoRA-MoE (low rank adaptation-mixture of experts) architecture. To this end, the crafted automatic routing mechanism can scientifically allocate the computational resources among different LoRA experts supervised by the contrastive learning. Additionally, we also introduce a novel expert memory queue mechanism to further boost the efficiency of the overall framework and prevent the memory overflow during training. We conduct comprehensive evaluations on three typical medical benchmarks: CMB, CMExam, and CMMLU-Med. Experimental results demonstrate that the proposed LLM can consistently outperform the strong baselines such as the HuatuoGPT series.

[Arxiv](https://arxiv.org/abs/2509.14269)