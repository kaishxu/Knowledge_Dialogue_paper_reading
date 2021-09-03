# Knowledge Dialogue Generation paper reading

学习记录。

## Commonsense Knowledge

**Commonsense Knowledge Aware Conversation Generation with Graph Attention.** Zhou, Hao, Tom Young, Minlie Huang, Haizhou Zhao, Jingfang Xu, and Xiaoyan Zhu. (IJCAI 2018) **[paper](https://www.ijcai.org/proceedings/2018/643)**

## Unclassified

**Bridging the Gap between Prior and Posterior Knowledge Selection for Knowledge-Grounded Dialogue Generation.** Chen, Xiuyi, Fandong Meng, Peng Li, Feilong Chen, Shuang Xu, Bo Xu, and Jie Zhou. (EMNLP 2020) **[paper](https://aclanthology.org/2020.emnlp-main.275/)**

## Others

**Graph-Structured Context Understanding for Knowledge-grounded Response Generation.** Li, Yanran, Wenjie Li, and Zhitao Wang. (SIGIR 2021 short) **[paper](https://dl.acm.org/doi/abs/10.1145/3404835.3463000)**

文章构建了context graph，涉及utterance节点（u）和entity mention节点（m），节点通过GCN进行融合交互学习，response generation参照过去研究，从候选entity中进行copy。

**Knowledge-Grounded Dialogue Generation with Pre-trained Language Models.** Zhao, Xueliang, Wei Wu, Can Xu, Chongyang Tao, Dongyan Zhao, and Rui Yan. (EMNLP 2020) **[paper](https://arxiv.org/abs/2010.08824)**

文章构建了一种融合knowledge document的对话生成模型，其中document选择和对话生成共同进行优化，用RL方法无监督地调整document选择的模型。

