# SMART-MC：用于多发性硬化症疾病修正疗法马尔可夫链建模中基于协变量转换的稀疏矩阵估计

发布时间：2024年12月02日

`其他` `马尔可夫模型`

> SMART-MC: Sparse Matrix Estimation with Covariate-Based Transitions in Markov Chain Modeling of Multiple Sclerosis Disease Modifying Therapies

# 摘要

> 马尔可夫模型是广泛用于对有限状态空间中的事件序列进行建模的工具，所以能依据治疗序列数据来确定治疗间的转移概率。为搞清楚患者层面的协变量怎样影响这些治疗转换，转移概率被建模成患者协变量的函数。这种方式能够将患者层面的协变量对患者就诊时治疗转换的影响直观呈现出来。所提出的方法会自动把经验转换次数少的转移矩阵条目估计为常数；用户能设定所需的截止值，即特定转移概率作为协变量函数进行估计所需的经验转换次数。首先，此策略能有效自动迫使最终估计的转移矩阵在对应零经验转换次数的位置为零，避免了为处理稀疏性而构建更复杂的模型。其次，当经验转换数量极少时，它会限制转移概率作为协变量函数的估计，从而避免因在将每个转移概率作为患者协变量的函数进行估计时出现 p>n 情况而可能引发的可识别性问题。为优化多模态似然，还开发了并行可扩展的全局优化例程。所提出的方法被用于了解多发性硬化症（MS）患者中跨疾病修饰疗法（DMTs）的转换如何受患者层面的人口统计学和临床表型影响。

> A Markov model is a widely used tool for modeling sequences of events from a finite state-space and hence can be employed to identify the transition probabilities across treatments based on treatment sequence data. To understand how patient-level covariates impact these treatment transitions, the transition probabilities are modeled as a function of patient covariates. This approach enables the visualization of the effect of patient-level covariates on the treatment transitions across patient visits. The proposed method automatically estimates the entries of the transition matrix with smaller numbers of empirical transitions as constant; the user can set desired cutoff of the number of empirical transition counts required for a particular transition probability to be estimated as a function of covariates. Firstly, this strategy automatically enforces the final estimated transition matrix to contain zeros at the locations corresponding to zero empirical transition counts, avoiding further complicated model constructs to handle sparsity, in an efficient manner. Secondly, it restricts estimation of transition probabilities as a function of covariates, when the number of empirical transitions is particularly small, thus avoiding the identifiability issue which might arise due to the p>n scenario when estimating each transition probability as a function of patient covariates. To optimize the multi-modal likelihood, a parallelized scalable global optimization routine is also developed. The proposed method is applied to understand how the transitions across disease modifying therapies (DMTs) in Multiple Sclerosis (MS) patients are influenced by patient-level demographic and clinical phenotypes.

[Arxiv](https://arxiv.org/abs/2412.03596)