# # 隐蔽的大型语言模型驱动的数据投毒攻击对抗基于嵌入的检索增强推荐系统

发布时间：2025年05月08日

`RAG` `电子商务` `网络安全`

> Stealthy LLM-Driven Data Poisoning Attacks Against Embedding-Based Retrieval-Augmented Recommender Systems

# 摘要

> 我们系统性地研究了检索增强推荐系统（基于RAG）中提供方数据中毒攻击。只需微调商品描述中的少量token，例如添加情感关键词或借用语义相关商品的措辞，攻击者即可显著影响特定商品的推荐排名。我们在token编辑和语义相似性约束下形式化定义了此类攻击，并评估了其在长尾商品提升和短头商品打压两种场景下的有效性。实验结果表明，即使是最细微的攻击也能悄然改变最终排名和商品曝光度，同时规避简单的检测机制。这一发现凸显了RAG管道对小规模元数据重写的脆弱性，并强调了建立健壮的文本一致性检查和溯源追踪机制以抵御提供方悄然中毒攻击的重要性。

> We present a systematic study of provider-side data poisoning in retrieval-augmented recommender systems (RAG-based). By modifying only a small fraction of tokens within item descriptions -- for instance, adding emotional keywords or borrowing phrases from semantically related items -- an attacker can significantly promote or demote targeted items. We formalize these attacks under token-edit and semantic-similarity constraints, and we examine their effectiveness in both promotion (long-tail items) and demotion (short-head items) scenarios. Our experiments on MovieLens, using two large language model (LLM) retrieval modules, show that even subtle attacks shift final rankings and item exposures while eluding naive detection. The results underscore the vulnerability of RAG-based pipelines to small-scale metadata rewrites and emphasize the need for robust textual consistency checks and provenance tracking to thwart stealthy provider-side poisoning.

[Arxiv](https://arxiv.org/abs/2505.05196)