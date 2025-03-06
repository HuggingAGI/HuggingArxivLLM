# PAIR：基于大型语言模型的新型进化算法选择策略

发布时间：2025年03月05日

`LLM应用

这篇论文探讨了如何将大型语言模型（LLMs）应用于进化算法中的选择方法，以提高其性能。通过PAIR方法，LLMs被用于模拟人类选择，优化配对决策，从而提升进化算法的效率和效果。因此，这篇论文属于LLM应用类别。` `组合优化`

> PAIR: A Novel Large Language Model-Guided Selection Strategy for Evolutionary Algorithms

# 摘要

> 进化算法 (EAs) 的随机或简化的选择方法限制了它们在解空间中的探索能力和收敛到最优解的能力。随机交叉或变异操作可能限制了模型高效进化的潜力。本文提出了一种名为Preference-Aligned Individual Reciprocity (PAIR) 的新型选择方法，该方法通过利用大型语言模型 (LLMs) 模拟人类的配偶选择，为进化算法中的配对过程引入智能。PAIR 通过提示 LLM 根据遗传多样性、适应度水平和交叉兼容性评估种群中的个体，从而指导更明智的配对决策。我们通过与最近发表的基线方法——LLM 驱动的进化算法 (LMEA)——进行对比评估，结果显示 PAIR 在各种 TSP 实例中显著优于 LMEA，实现了更小的最优性差距和更好的收敛性。这种性能在与闪存思考模型结合时尤为突出，展示了通过增加种群多样性来摆脱局部最优的能力。总的来说，PAIR 通过复杂的偏好建模，为 LLM 驱动的进化算法选择领域中的上下文学习提供了一种新的策略，为改进解决方案和进一步研究 LLM 引导的优化铺平了道路。

> Evolutionary Algorithms (EAs) employ random or simplistic selection methods, limiting their exploration of solution spaces and convergence to optimal solutions. The randomness in performing crossover or mutations may limit the model's ability to evolve efficiently. This paper introduces Preference-Aligned Individual Reciprocity (PAIR), a novel selection approach leveraging Large Language Models to emulate human-like mate selection, thereby introducing intelligence to the pairing process in EAs. PAIR prompts an LLM to evaluate individuals within a population based on genetic diversity, fitness level, and crossover compatibility, guiding more informed pairing decisions. We evaluated PAIR against a baseline method called LLM-driven EA (LMEA), published recently. Results indicate that PAIR significantly outperforms LMEA across various TSP instances, achieving lower optimality gaps and improved convergence. This performance is especially noticeable when combined with the flash thinking model, demonstrating increased population diversity to escape local optima. In general, PAIR provides a new strategy in the area of in-context learning for LLM-driven selection in EAs via sophisticated preference modelling, paving the way for improved solutions and further studies into LLM-guided optimization.

[Arxiv](https://arxiv.org/abs/2503.03239)