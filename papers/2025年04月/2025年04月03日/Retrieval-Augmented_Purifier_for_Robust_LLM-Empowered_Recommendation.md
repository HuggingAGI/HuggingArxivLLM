# 基于检索增强的稳健大语言模型推荐系统净化器

发布时间：2025年04月03日

`RAG` `推荐系统` `电子商务`

> Retrieval-Augmented Purifier for Robust LLM-Empowered Recommendation

# 摘要

> 大型语言模型（LLM）驱动的推荐系统最近彻底改变了个性化推荐框架，吸引了广泛关注。尽管取得了显著成功，但现有LLM驱动的推荐系统对轻微扰动极为脆弱。为了减轻这些漏洞的影响，我们提出了一种基于物品-物品共现的协作信号方法，从用户历史交互中清除攻击者插入的恶意知识。同时，检索增强生成（RAG）技术通过引入外部协作知识，为提升LLM驱动推荐系统的鲁棒性提供了新机遇。因此，我们提出了一种名为RETURN的新框架，通过检索外部协作信号净化中毒用户配置文件，并以即插即用的方式增强系统鲁棒性。具体来说，我们提出了检索增强的扰动定位方法，通过从协作物品图中检索知识来识别用户历史中的潜在扰动。随后，我们使用删除或替换策略清除扰动，并引入稳健的集成推荐策略生成最终预测。三个真实数据集的实验结果验证了RETURN框架的有效性。

> Recently, Large Language Model (LLM)-empowered recommender systems have revolutionized personalized recommendation frameworks and attracted extensive attention. Despite the remarkable success, existing LLM-empowered RecSys have been demonstrated to be highly vulnerable to minor perturbations. To mitigate the negative impact of such vulnerabilities, one potential solution is to employ collaborative signals based on item-item co-occurrence to purify the malicious collaborative knowledge from the user's historical interactions inserted by attackers. On the other hand, due to the capabilities to expand insufficient internal knowledge of LLMs, Retrieval-Augmented Generation (RAG) techniques provide unprecedented opportunities to enhance the robustness of LLM-empowered recommender systems by introducing external collaborative knowledge. Therefore, in this paper, we propose a novel framework (RETURN) by retrieving external collaborative signals to purify the poisoned user profiles and enhance the robustness of LLM-empowered RecSys in a plug-and-play manner. Specifically, retrieval-augmented perturbation positioning is proposed to identify potential perturbations within the users' historical sequences by retrieving external knowledge from collaborative item graphs. After that, we further retrieve the collaborative knowledge to cleanse the perturbations by using either deletion or replacement strategies and introduce a robust ensemble recommendation strategy to generate final robust predictions. Extensive experiments on three real-world datasets demonstrate the effectiveness of the proposed RETURN.

[Arxiv](https://arxiv.org/abs/2504.02458)