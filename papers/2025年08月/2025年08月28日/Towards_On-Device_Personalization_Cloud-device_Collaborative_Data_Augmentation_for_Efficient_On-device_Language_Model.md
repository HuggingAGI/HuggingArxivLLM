# 迈向设备端个性化：云-设备协同数据增强助力高效设备端语言模型

发布时间：2025年08月28日

`LLM应用` `基础理论`

> Towards On-Device Personalization: Cloud-device Collaborative Data Augmentation for Efficient On-device Language Model

# 摘要

> 随着大型语言模型（LLMs）的发展，各类自然语言处理（NLP）任务均取得了显著进步。但现有LLMs仍存在两大阻碍其更广泛落地的挑战：（1）回复往往过于通用，缺乏针对用户个体的个性化定制；（2）因计算需求密集而严重依赖云基础设施，导致对网络稳定性的依赖及响应延迟。近期研究主要集中在开发云端个性化LLM或探索通用LLM的端侧部署，却鲜少通过研究个性化端侧语言模型来同时解决这两个问题。为弥合这一差距，我们提出CDCDA-PLM框架——在强大云端LLM的支持下，于用户设备部署个性化端侧语言模型。具体而言，该框架借助服务端LLM强大的泛化能力扩充用户有限的个人数据，从而缓解数据稀缺问题；再利用真实与合成数据，通过参数高效微调（PEFT）模块微调个性化端侧语言模型（LMs），并部署到用户本地设备，使其无需依赖云端LLMs即可处理查询。这种方式既消除了对网络稳定性的依赖，又确保了高响应速度。在一个广泛使用的个性化基准测试的六项任务上，实验结果验证了CDCDA-PLM的有效性。

> With the advancement of large language models (LLMs), significant progress has been achieved in various Natural Language Processing (NLP) tasks. However, existing LLMs still face two major challenges that hinder their broader adoption: (1) their responses tend to be generic and lack personalization tailored to individual users, and (2) they rely heavily on cloud infrastructure due to intensive computational requirements, leading to stable network dependency and response delay. Recent research has predominantly focused on either developing cloud-based personalized LLMs or exploring the on-device deployment of general-purpose LLMs. However, few studies have addressed both limitations simultaneously by investigating personalized on-device language models. To bridge this gap, we propose CDCDA-PLM, a framework for deploying personalized on-device language models on user devices with support from a powerful cloud-based LLM. Specifically, CDCDA-PLM leverages the server-side LLM's strong generalization capabilities to augment users' limited personal data, mitigating the issue of data scarcity. Using both real and synthetic data, A personalized on-device language models (LMs) is fine-tuned via parameter-efficient fine-tuning (PEFT) modules and deployed on users' local devices, enabling them to process queries without depending on cloud-based LLMs. This approach eliminates reliance on network stability and ensures high response speeds. Experimental results across six tasks in a widely used personalization benchmark demonstrate the effectiveness of CDCDA-PLM.

[Arxiv](https://arxiv.org/abs/2508.21313)