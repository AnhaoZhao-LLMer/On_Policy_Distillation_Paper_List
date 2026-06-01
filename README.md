This repository contains a regularly updated paper list on **On-Policy Distillation (OPD)**.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License](https://img.shields.io/badge/License-Apache_2.0-green.svg)](./LICENSE) ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/AnhaoZhao-LLMer/On_Policy_Distillation_Paper_List/main?logo=github&color=blue) ![Static Badge](https://img.shields.io/badge/Contributions-welcome-blue.svg?style=flat) 

## Content

- [Content](#content)
- [Keywords Convention](#keywords-convention)
- [Papers](#papers)
  - [Teacher–Student–Based OPD](#teacherstudentbased-opd)
    - [Single Teacher](#single-teacher)
    - [Multi-Teacher](#multi-teacher)
  - [On-Policy Self-Distillation](#on-policy-self-distillation)
  - [Training Stability](#training-stability)
  - [Cross-Tokenizer On-Policy Distillation](#cross-tokenizer-on-policy-distillation)
    - [White-Box](#white-box)
    - [Black-Box](#black-box)
  - [Analysis](#analysis)
  - [Data](#data)
  - [Survey](#survey)



## Keywords Convention

![](https://img.shields.io/badge/OPD-blue) Abbreviation

![](https://img.shields.io/badge/ICML2026-orange) Conference


## Papers

### Teacher–Student–Based OPD
#### Single Teacher
- **MiniLLM: On-Policy Distillation of Large Language Models**  
  *Yuxian Gu, Li Dong, Furu Wei, Minlie Huang*. [[pdf](https://arxiv.org/pdf/2306.08543)], 2023.06. ![](https://img.shields.io/badge/ICLR2024-orange)
- **On-Policy Distillation of Language Models: Learning from Self-Generated Mistakes**  
  *Rishabh Agarwal, Nino Vieillard, Yongchao Zhou, Piotr Stanczyk, Sabela Ramos, Matthieu Geist, Olivier Bachem*. [[pdf](https://arxiv.org/pdf/2306.13649)], 2023.06. ![](https://img.shields.io/badge/ICLR2024-orange)
- **On-Policy Distillation**  
  *Kevin Lu and Thinking Machines Lab*. [[pdf](https://thinkingmachines.ai/blog/on-policy-distillation/)], 2025.10. ![](https://img.shields.io/badge/Blog2025-orange)
- **Qwen3 Technical Report**  
  *Qwen3 Team*. [[pdf](https://arxiv.org/pdf/2505.09388)], 2025.05. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **HY-MT1.5 Technical Report**  
  *Mao Zheng, Zheng Li, Tao Chen, Mingyang Song, Di Wang*. [[pdf](https://arxiv.org/pdf/2512.24092)], 2025.12. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **Video-OPD: Efficient Post-Training of Multimodal Large Language Models for Temporal Video Grounding via On-Policy Distillation**  
  *Jiaze Li, Hao Yin, Haoran Xu, Boshen Xu, Wenhui Tan, Zewen He, Jianzhong Ju, Zhenbo Luo, Jian Luan*. [[pdf](https://arxiv.org/pdf/2602.02994)], 2026.02. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Reinforced Attention Learning**  
  *Bangzheng Li, Jianmo Ni, Chen Qu, Ian Miao, Liu Yang, Xingyu Fu, Muhao Chen, Derek Zhiyuan Cheng*. [[pdf](https://arxiv.org/pdf/2602.04884)], 2026.02. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Learning beyond Teacher: Generalized On-Policy Distillation with Reward Extrapolation**  
  *Wenkai Yang, Weijie Liu, Ruobing Xie, Kai Yang, Saiyong Yang, Yankai Lin*. [[pdf](https://arxiv.org/pdf/2602.12125)], 2026.02. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Fast and Effective On-policy Distillation from Reasoning Prefixes**  
  *Dongxu Zhang, Zhichao Yang, Sepehr Janghorbani, Jun Han, Andrew Ressler II, Qian Qian, Gregory D. Lyng, Sanjit Singh Batra, Robert E. Tillman*. [[pdf](https://arxiv.org/pdf/2602.15260)], 2026.02. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Learning User Interests via Reasoning and Distillation for Cross-Domain News Recommendation**  
  *Mengdan Zhu, Yufan Zhao, Tao Di, Yulan Yan, Liang Zhao*. [[pdf](https://arxiv.org/pdf/2602.15005)], 2026.02. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Explain in Your Own Words: Improving Reasoning via Token-Selective Dual Knowledge Distillation**  
  *Minsang Kim, Seung Jun Baek*. [[pdf](https://arxiv.org/pdf/2603.13260)], 2026.03. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **X-OPD: Cross-Modal On-Policy Distillation for Capability Alignment in Speech LLMs**  
  *Di Cao, Dongjie Fu, Hai Yu, Siqi Zheng, Xu Tan, Tao Jin*. [[pdf](https://arxiv.org/pdf/2603.24596)], 2026.03. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **VLA-OPD: Bridging Offline SFT and Online RL for Vision-Language-Action Models via On-Policy Distillation**  
  *Zhide Zhong, Haodong Yan, Junfeng Li, Junjie He, Tianran Zhang, Haoang Li*. [[pdf](https://arxiv.org/pdf/2603.26666)], 2026.03. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **DP-OPD: Differentially Private On-Policy Distillation for Language Models**  
  *Fatemeh Khadem, Sajad Mousavi, Yi Fang, Yuhong Liu*. [[pdf](https://arxiv.org/pdf/2604.04461)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **On-Policy Distillation of Language Models for Autonomous Vehicle Motion Planning**  
  *Amirhossein Afsharrad, Amirhesam Abedsoltan, Ahmadreza Moradipari, Sanjay Lall*. [[pdf](https://arxiv.org/pdf/2604.07944)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **HY-Embodied-0.5: Embodied Foundation Models for Real-World Agents**  
  *Tencent Robotics X, HY Vision Team*. [[pdf](https://arxiv.org/pdf/2604.07430)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Lightning OPD: Efficient Post-Training for Large Reasoning Models with Offline On-Policy Distillation**  
  *Yecheng Wu, Song Han, Hai Cai*. [[pdf](https://arxiv.org/pdf/2604.13010)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **The Illusion of Certainty: Decoupling Capability and Calibration in On-Policy Distillation**  
  *Jiaxin Zhang, Xiangyu Peng, Qinglin Chen, Qinyuan Ye, Caiming Xiong, Chien-Sheng Wu*. [[pdf](https://arxiv.org/pdf/2604.16830)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Hybrid Policy Distillation for LLMs**  
  *Wenhong Zhu, Ruobing Xie, Rui Wang, Pengfei Liu*. [[pdf](https://arxiv.org/pdf/2604.20244)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Efficient Rationale-based Retrieval: On-policy Distillation from Generative Rerankers based on JEPA**  
  *Teng Chen, Sheng Xu, Feixiang Guo, Xiaoyu Wang, Qingqing Gu, Hongyan Li, Luo Ji*. [[pdf](https://arxiv.org/pdf/2604.23336)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **TCOD: Exploring Temporal Curriculum in On-Policy Distillation for Multi-turn Autonomous Agents**  
  *Jiaqi Wang, Wenhao Zhang, Weijie Shi, Yaliang Li, James Cheng*. [[pdf](https://arxiv.org/pdf/2604.24005)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **PRISM: Pre-alignment via Black-box On-policy Distillation for Multimodal Reinforcement Learning**  
  *Sudong Wang, Weiquan Huang, Xiaomin Yu, Zuhao Yang, Hehai Lin, Keming Wu, Chaojun Xiao, Chen Chen, Wenxuan Wang, Beier Zhu, Yunjian Zhang, Chengwei Qin*. [[pdf](https://arxiv.org/pdf/2604.28123)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **HyperEyes: Dual-Grained Efficiency-Aware Reinforcement Learning for Parallel Multimodal Search Agents**  
  *Guankai Li, Jiabin Chen, Yi Xu, Xichen Zhang, Yuan Lu*. [[pdf](https://arxiv.org/pdf/2605.07177)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **LiteGUI: Distilling Compact GUI Agents with Reinforcement Learning**  
  *Yubin Wu, Zicheng Cai, Liping Ning, Hua Wang, Zhi Chen, Yaohua Tang, Hao Chen*. [[pdf](https://arxiv.org/pdf/2605.07505)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **SOD: Step-wise On-policy Distillation for Small Language Model Agents**  
  *Qiyong Zhong, Mao Zheng, Mingyang Song, Xin Lin, Jie Sun, Houcheng Jiang, Xiang Wang, Junfeng Fang*. [[pdf](https://arxiv.org/pdf/2605.07725)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Flow-OPD: On-Policy Distillation for Flow Matching Models**  
  *Zhen Fang, Wenxuan Huang, Yu Zeng, Yiming Zhao, Shuang Chen, Kaituo Feng, Yunlong Lin, Lin Chen, Zehui Chen, Shaosheng Cao, Feng Zhao*. [[pdf](https://arxiv.org/pdf/2605.08063)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **CProteinOPD: Towards Effective and Efficient Preference Alignment for Protein Design**  
  *Yulin Zhang, He Cao, Zihao Jiang, Chenyi Zi, Zhipeng Zhou, Zijing Liu, Yu Li, Jia Li, Ziqi Gao*. [[pdf](https://arxiv.org/pdf/2605.10189)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Combining On-Policy Optimization and Distillation for Long-Context Reasoning in Large Language Models**  
  *Miguel Moura Ramos, Duarte M. Alves, André F. T. Martins*. [[pdf](https://arxiv.org/pdf/2605.12227)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Reward-Weighted On-Policy Distillation with an Open Property-Equivalence Verifier for NL-to-SVA Generation**  
  *Qingyun Zou, Yingze Li, Tianen Liu, Bingsheng He, Weng-Fai Wong*. [[pdf](https://arxiv.org/pdf/2605.13501)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **AnyFlow: Any-Step Video Diffusion Model with On-Policy Flow Map Distillation**  
  *Yuchao Gu, Guian Fang, Yuxin Jiang, Weijia Mao, Song Han, Han Cai, Mike Zheng Shou*. [[pdf](https://arxiv.org/pdf/2605.13724)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **DiffusionOPD: A Unified Perspective of On-Policy Distillation in Diffusion Models**  
  *Quanhao Li, Junqiu Yu, Kaixun Jiang, Yujie Wei, Zhen Xing, Pandeng Li, Ruihang Chu, Shiwei Zhang, Yu Liu, Zuxuan Wu*. [[pdf](https://arxiv.org/pdf/2605.15055)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **MoASE++: Mixture of Activation Sparsity Experts with Domain-Adaptive On-policy Distillation for Continual Test Time Adaptation**  
  *Ronyu Zhang, Aosong Cheng, Gaole Dai, Yulin Luo, Jiaming Liu, Li Du, Huanrui Yang, Dan Wang, Leyuan Fang, Yuan Du, Shanghang Zhang*. [[pdf](https://arxiv.org/pdf/2605.17743)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **f-OPD: Stabilizing Long-Horizon On-Policy Distillation with Freshness-Aware Control**  
  *Xianwei Chen, Shimin Zhang, Jibin Wu*. [[pdf](https://arxiv.org/pdf/2605.17862)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)

#### Multi-Teacher
- **MiMo-V2-Flash Technical Report**  
  *LLM-Core Xiaomi*. [[pdf](https://arxiv.org/pdf/2601.02780)], 2026.01. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **GLM-5: from Vibe Coding to Agentic Engineering**  
  *Zhipu AI & Tsinghua University*. [[pdf](https://arxiv.org/pdf/2602.15763)], 2026.02. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Nemotron-Cascade 2: Post-Training LLMs with Cascade RL and Multi-Domain On-Policy Distillation**  
  *Zhuolin Yang, Zihan Liu, Yang Chen, Wenliang Dai, Boxin Wang, Sheng-Chieh Lin, Chankyu Lee, Yangyi Chen, Dongfu Jiang, Jiafan He, Renjie Pi, Grace Lam, Nayeon Lee, Alexander Bukharin, Mohammad Shoeybi, Bryan Catanzaro, Wei Ping*. [[pdf](https://arxiv.org/pdf/2603.19220)], 2026.03. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **KAT-Coder-V2 Technical Report**  
  *KwaiKAT Team*. [[pdf](https://arxiv.org/pdf/2603.27703)], 2026.03. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **DeepSeek-V4 Technical Report**  
  *DeepSeek Team*. [[pdf](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro/blob/main/DeepSeek_V4.pdf)], 2026.04. ![](https://img.shields.io/badge/TechnicalReport2026-orange)
- **Co-Evolving Policy Distillation**  
  *Naibin Gu, Chenxu Yang, Qingyi Si, Chuanyu Qin, Dingyu Yao, Peng Fu, Zheng Lin, Weiping Wang, Nan Duan, Jiaqi Wang*. [[pdf](https://arxiv.org/pdf/2604.27083)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **MAD-OPD: Breaking the Ceiling in On-Policy Distillation via Multi-Agent Debate**  
  *Jianze Wang, Ying Liu, Jinlong Chen, Xuchun Hu, Qilong Zhang, Yu Cao, Jun Wang, Hua Yang, Yong Xie, Qianglong Chen*. [[pdf](https://arxiv.org/pdf/2605.01347)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)


### On-Policy Self-Distillation
- **Self-Distilled Reasoner: On-Policy Self-Distillation for Large Language Models**  
  *Siyan Zhao, Zhihui Xie, Mengchen Liu, Jing Huang, Guan Pang, Feiyu Chen, Aditya Grover*. [[pdf](https://arxiv.org/pdf/2601.18734)], 2026.01. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Self-Distillation Enables Continual Learning**  
  *Idan Shenfeld, Mehul Damani, Jonas Hübotter, Pulkit Agrawal*. [[pdf](https://arxiv.org/pdf/2601.19897)], 2026.01. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Reinforcement Learning via Self-Distillation**  
  *Jonas Hübotter, Frederike Lübeck, Lejs Behric, Anton Baumann, Marco Bagatella, Daniel Marta, Ido Hakimi, Idan Shenfeld, Thomas Kleine Buening, Carlos Guestrin, Andreas Krause*. [[pdf](https://arxiv.org/pdf/2601.20802)], 2026.01. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Privileged Information Distillation for Language Models**  
  *Emiliano Penaloza, Dheeraj Vattikonda, Nicolas Gontier, Alexandre Lacoste, Laurent Charlin, Massimo Caccia*. [[pdf](https://arxiv.org/pdf/2602.04942)], 2026.02. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Multi-Token Prediction via Self-Distillation**  
  *John Kirchenbauer, Abhimanyu Hans, Brian Bartoldson, Micah Goldblum, Ashwinee Panda, Tom Goldstein*. [[pdf](https://arxiv.org/pdf/2602.06019)], 2026.02. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **GATES: Self-Distillation under Privileged Context with Consensus Gating**  
  *Alex Stein, Furong Huang, Tom Goldstein*. [[pdf](https://arxiv.org/pdf/2602.20574)], 2026.02. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **On-Policy Context Distillation for Language Models**  
  *Tianzhu Ye, Li Dong, Xun Wu, Shaohan Huang, Furu Wei*. [[pdf](https://arxiv.org/pdf/2602.12275)], 2026.02. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **On-Policy Self-Distillation for Reasoning Compression**  
  *Hejian Sang, Yuanda Xu, Zhengze Zhou, Ran He, Zhipeng Wang, Jiachen Sun*. [[pdf](https://arxiv.org/pdf/2603.05433)], 2026.03. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **OpenClaw-RL: Train Any Agent Simply by Talking**  
  *Yinjie Wang, Xuyang Chen, Xiaolong Jin, Mengdi Wang, Ling Yang*. [[pdf](https://arxiv.org/pdf/2603.10165)], 2026.03. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Aligning Language Models from User Interactions**  
  *Thomas Kleine Buening, Jonas Hübotter, Barna Pásztor, Idan Shenfeld, Giorgia Ramponi, Andreas Krause*. [[pdf](https://arxiv.org/pdf/2603.12273)], 2026.03. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Online Experiential Learning for Language Models**  
  *Tianzhu Ye, Li Dong, Qingxiu Dong, Xun Wu, Shaohan Huang, Furu Wei*. [[pdf](https://arxiv.org/pdf/2603.16856)], 2026.03. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **PACED: Distillation and Self-Distillation at the Frontier of Student Competence**  
  *Yuanda Xu, Hejian Sang, Zhengze Zhou, Ran He, Zhipeng Wang*. [[pdf](https://arxiv.org/pdf/2603.11178)], 2026.03. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Skill-SD: Skill-Conditioned Self-Distillation for Multi-turn LLM Agents**  
  *Hao Wang, Guozhi Wang, Han Xiao, Yufeng Zhou, Yue Pan, Jichao Wang, Ke Xu, Yafei Wen, Xiaohu Ruan, Xiaoxin Chen, Honggang Qi*. [[pdf](https://arxiv.org/pdf/2604.10674)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **OPSDL: On-Policy Self-Distillation for Long-Context Language Models**  
  *Xinsen Zhang, Zhenkai Ding, Tianjun Pan, Run Yang, Chun Kang, Xue Xiong, Jingnan Gu*. [[pdf](https://arxiv.org/pdf/2604.17535)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **PAINT: Partial-Solution Adaptive Interpolated Training for Self-Distilled Reasoners**  
  *Zhiquan Tan, Yinrong Hong*. [[pdf](https://arxiv.org/pdf/2604.26573)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Learn where to Click from Yourself: On-Policy Self-Distillation for GUI Grounding**  
  *Yan Zhang, Daiqing Wu, Huawen Shen, Yu Zhou, Can Ma*. [[pdf](https://arxiv.org/pdf/2605.00642)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Healthcare AI GYM for Medical Agents**  
  *Minbyul Jeong*. [[pdf](https://arxiv.org/pdf/2605.02943)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Multilingual Safety Alignment via Self-Distillation**  
  *Ruiyang Qin, Qingzhuo Wang, Dongrui Liu, Qiang Li, Zhihua Wei, Wen Shen*. [[pdf](https://arxiv.org/pdf/2605.02971v2)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Preference-Based Self-Distillation: Beyond KL Matching via Reward Regularization**  
  *Xin Yu, Liuchen Liao, Yiwen Zhang, Yingchen Yu, Lingzhou Xue, Qinzhen Guo*. [[pdf](https://arxiv.org/pdf/2605.05040)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **D-OPSD: On-Policy Self-Distillation for Continuously Tuning Step-Distilled Diffusion Models**  
  *Dengyang Jiang, Xin Jin, Dongyang Liu, Zanyi Wang, Mingzhe Zheng, Ruoyi Du, Xiangpeng Yang, Qilong Wu, Zhen Li, Peng Gao, Harry Yang, Steven Hoi*. [[pdf](https://arxiv.org/pdf/2605.05204)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **VISD: Enhancing Video Reasoning via Structured Self-Distillation**  
  *Hao Lin, Kunyang Lv, Xu Jiang, Jingqi Tian, Zhongjing Du, Jiayu Ding, Qiaoman Zhang, Hongbo Jin*. [[pdf](https://arxiv.org/pdf/2605.06094)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **OPSD Compresses What RLVR Teaches: A Post-RL Compaction Stage for Reasoning Models**  
  *Jaehoon Kim, Dongha Lee*. [[pdf](https://arxiv.org/pdf/2605.06188)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Training with Harnesses: On-Policy Harness Self-Distillation for Complex Reasoning**  
  *Zhengyang Zhao, Lu Ma, Wentao Zhang*. [[pdf](https://arxiv.org/pdf/2605.08741)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Crosslingual On-Policy Self-Distillation for Multilingual Reasoning**  
  *Yihong Liu, Raoyuan Zhao, Michael A. Hedderich, Hinrich Schütze*. [[pdf](https://arxiv.org/pdf/2605.09548)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **TRACE: Distilling Where It Matters via Token-Routed Self On-Policy Alignment**  
  *Jiaxuan Wang, Xuan Ouyang, Zhiyu Chen, Yulan Hu, Zheng Pan, Xin Li, Lan-Zhe Guo*. [[pdf](https://arxiv.org/pdf/2605.10194)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Adaptive Teacher Exposure for Self-Distillation in LLM Reasoning**  
  *Zihao Han, Tiangang Zhang, Huaibin Wang, Yilun Sun*. [[pdf](https://arxiv.org/pdf/2605.11458)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Anti-Self-Distillation for Reasoning RL via Pointwise Mutual Information**  
  *Guobin Shen, Xiang Cheng, Chenxiao Zhao, Lei Huang, Jindong Li, Dongcheng Zhao, Xing Yu*. [[pdf](https://arxiv.org/pdf/2605.11609)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **From Generic Correlation to Input-Specific Credit in On-Policy Self Distillation**  
  *Guobin Shen, Lei Huang, Xiang Cheng, Chenxiao Zhao, Jindong Li, Dongcheng Zhao, Xing Yu*. [[pdf](https://arxiv.org/pdf/2605.11706)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **GRAFT: Graph-Tokenized LLMs for Tool Planning**  
  *Xinyi Gao, Xinyu Ren, Junliang Yu, Tong Chen, Quoc Viet Hung Nguyen, Hongzhi Yin*. [[pdf](https://arxiv.org/pdf/2605.11706)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **GEAR: Granularity-Adaptive Advantage Reweighting for LLM Agents via Self-Distillation**  
  *Sijia Li, Yuchen Huang, Zifan Liu, Yanping Li, Jingjing Fu, Li Zhao, Jiang Bian, Ling Zhang, Jun Zhang, Rui Wang*. [[pdf](https://arxiv.org/pdf/2605.11853)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **OGLS-SD: On-Policy Self-Distillation with Outcome-Guided Logit Steering for LLM Reasoning**  
  *Yuxiao Yang, Xiaoyun Wang, Weitong Zhang*. [[pdf](https://arxiv.org/pdf/2605.12400)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Multi-Rollout On-Policy Distillation via Peer Successes and Failures**  
  *Weichen Yu, Xiaomin Li, Yizhou Zhao, Xiaoze Liu, Ruowang Zhang, Haixin Wang, Yinyi Luo, Chen Henry Wu, Gaurav Mittal, Matt Fredrikson, Yu Hu*. [[pdf](https://arxiv.org/pdf/2605.12652)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Learning with Rare Success but Rich Feedback via Reflection-Enhanced Self-Distillation**  
  *Yuwei Zhang, Sha Li, Changlong Yu, Qin Lu, Shuowei Jin, Chengyu Dong, Haoran Liu, Ilgee Hong, Xintong Li, Zhenyu Shi, Bing Yin, Jingbo Shang*. [[pdf](https://arxiv.org/pdf/2605.12741)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Learning from Language Feedback via Variational Policy Distillation**  
  *Yang Li, Erik Nijkamp, Semih Yavuz, Shafiq Rayhan Joty*. [[pdf](https://arxiv.org/pdf/2605.15113)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Self-Distilled Agentic Reinforcement Learning**  
  *Zhengxi Lu, Zhiyuan Yao, Zhuowen Han, Zi-Han Wang, Jinyang Wu, Qi Gu, Xunliang Cai, Weiming Lu, Jun Xiao, Yueting Zhuang, Yongliang Shen*. [[pdf](https://arxiv.org/pdf/2605.15155)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Reducing the Safety Tax in LLM Safety Alignment with On-Policy Self-Distillation**  
  *Yu Fu, Longxuan Yu, Haz Sameen Shahgir, Zhipeng Wei, Hui Liu, N.Benjamin Erichson, Yue Dong*. [[pdf](https://arxiv.org/pdf/2605.15239)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Respecting Self-Uncertainty in On-Policy Self-Distillation for Efficient LLM Reasoning**  
  *Junlong Ke, Zichen Wen, Weijia Li, Conghui He, Linfeng Zhang*. [[pdf](https://arxiv.org/pdf/2605.13255)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **ORACLE: Anticipating Scams from Partial Trajectories in Streaming App Usage**  
  *Wenbo Gao, Songbai Tan, Zhongan Wang, Fei Shen, Gang Xu, Huiping Zhuang, Yunyun Yang, Ming Li, Xiaofeng Zhu*. [[pdf](https://arxiv.org/pdf/2605.16363)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **MixSD: Mixed Contextual Self-Distillation for Knowledge Injection**  
  *Jiarui Liu, Lechen Zhang, Yongjin Yang, Yinghui He, Yingheng Wang, Weihao Xuan, Zhijing Jin, Mona Diab*. [[pdf](https://arxiv.org/pdf/2605.16865)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Self-Supervised On-Policy Distillation for Reasoning Language Models**  
  *Zhiquan Tan, Yinrong Hong*. [[pdf](https://arxiv.org/pdf/2605.17497)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)

### Training Stability
- **Stable On-Policy Distillation through Adaptive Target Reformulation**  
  *Ijun Jang, Jewon Yeom, Juan Yeo, Hyunggu Lim, Taesup Kim*. [[pdf](https://arxiv.org/pdf/2601.07155)], 2026.01. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Entropy-Aware On-Policy Distillation of Language Models**  
  *Woogyeol Jin, Taywon Min, Yongjin Yang, Swanand Ravindra Kadhe, Yi Zhou, Dennis Wei, Nathalie Baracaldo, Kimin Lee*. [[pdf](https://arxiv.org/pdf/2603.07079)], 2026.03. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Scaling Reasoning Efficiently via Relaxed On-Policy Distillation**  
  *Jongwoo Ko, Sara Abdali, Young Jin Kim, Tianyi Chen, Pashmina Cameron*. [[pdf](https://arxiv.org/pdf/2603.11137)], 2026.03. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Why Does Self-Distillation (Sometimes) Degrade the Reasoning Capability of LLMs?**  
  *Jeonghye Kim, Xufang Luo, Minbeom Kim, Sangmook Lee, Dohyung Kim, Jiwon Jeon, Dongsheng Li, Yuqing Yang*. [[pdf](https://arxiv.org/pdf/2603.24472)], 2026.03. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Unifying Group-Relative and Self-Distillation Policy Optimization via Sample Routing**  
  *Gengsheng Li, Tianyu Yang, Junfeng Fang, Mingyang Song, Mao Zheng, Haiyun Guo, Dan Zhang, Jinqiao Wang, Tat-Seng Chua*. [[pdf](https://arxiv.org/pdf/2604.02288)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Self-Distilled RLVR**  
  *Chenxu Yang, Chuanyu Qin, Qingyi Si, Minghui Chen, Naibin Gu, Dingyu Yao, Zheng Lin, Weiping Wang, Jiaqi Wang, Nan Duan*. [[pdf](https://arxiv.org/pdf/2604.03128)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Demystifying OPD: Length Inflation and Stabilization Strategies for Large Language Models**  
  *Feng Luo, Yu-Neng Chuang, Guanchu Wang, Zicheng Xu, Xiaotian Han, Tianyi Zhang, Vladimir Braverman*. [[pdf](https://arxiv.org/pdf/2604.08527)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **SCOPE: Signal-Calibrated On-Policy Distillation Enhancement with Dual-Path Adaptive Weighting**  
  *Binbin Zheng, Xing Ma, Yiheng Liang, Jingqing Ruan, Xiaoliang Fu, Kepeng Lin, Benchang Zhu, Ke Zeng, Xunliang Cai*. [[pdf](https://arxiv.org/pdf/2604.10688)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Uni-OPD: Unifying On-Policy Distillation with a Dual-Perspective Recipe**  
  *Wenjin Hou, Shangpin Peng, Weinong Wang, Zheng Ruan, Yue Zhang, Zhenglin Zhou, Mingqi Gao, Yifei Chen, Kaiqi Wang, Hongming Yang, Chengquan Zhang, Zhuotao Tian, Han Hu, Yi Yang, Fei Wu, Hehe Fan*. [[pdf](https://arxiv.org/pdf/2605.03677)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Near-Policy: Accelerating On-Policy Distillation via Asynchronous Generation and Selective Packing**  
  *Miao Rang, Zhenni Bi, Hang Zhou, Kai Han, Xuechun Wang, An Xiao, Xinghao Chen, Yunhe Wang, Hanting Chen*. [[pdf](https://arxiv.org/pdf/2605.05940)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Safactory: A Scalable Agentic Infrastructure for Training Trustworthy Autonomous Intelligence**  
  *Shanghai AI Laboratory*. [[pdf](https://arxiv.org/pdf/2605.06230)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Asymmetric On-Policy Distillation: Bridging Exploitation and Imitation at the Token Level**  
  *Nan Jia, Haojin Yang, Xing Ma, Jiesong Lian, Shuailiang Zhang, Weipeng Zhang, Ke Zeng, Xunliang Cai, Zequn Sun*. [[pdf](https://arxiv.org/pdf/2605.06387)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Prune-OPD: Efficient and Reliable On-Policy Distillation for Long-Horizon Reasoning**  
  *Zhicheng Yang, Zhijiang Guo, Yifan Song, Minrui Xu, Yongxin Wang, Yiwei Wang, Xiaodan Liang, Jing Tang*. [[pdf](https://arxiv.org/pdf/2605.07804)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **KL for a KL: On-Policy Distillation with Control Variate Baseline**  
  *Minjae Oh, Sangjun Song, Gyubin Choi, Yunho Choi, Yohan Jo*. [[pdf](https://arxiv.org/pdf/2605.07865)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **On-Policy Distillation with Best-of-N Teacher Rollout Selection**  
  *Ke Zhang, Yunjie Tian, Dongdi Zhao, Yijiang Li, Yuanye Liu, Vishal M Patel, Di Fu*. [[pdf](https://arxiv.org/pdf/2605.09725)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Teacher-Guided Policy Optimization for LLM Distillation**  
  *Xinyu Liu, Kechen Jiao, Chunyang Xiao, Runsong Zhao, Junhao Ruan, Bei Li, Jiahao Liu, Qifan Wang, Xin Chen, Jingang Wang, Tong Xiao, JingBo Zhu*. [[pdf](https://arxiv.org/pdf/2605.13230)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Prefix Teach, Suffix Fade: Local Teachability Collapse in Strong-to-Weak On-Policy Distillation**  
  *Kaiyuan Liu, Ziyuan Zhuang, Yang Bai, Bing Wang, Rongxiang Weng, Jieping Ye*. [[pdf](https://arxiv.org/pdf/2605.13643)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)

### Cross-Tokenizer On-Policy Distillation

#### White-Box
- **Unlocking On-Policy Distillation for Any Model Family**  
  *Hugging Face*. [[pdf](https://huggingface.co/spaces/HuggingFaceH4/on-policy-distillation)], 2025.10. ![](https://img.shields.io/badge/Blog2025-orange)
- **SimCT: Recovering Lost Supervision for Cross-Tokenizer On-Policy Distillation**  
  *Jie Sun, Mao Zheng, Mingyang Song, Qiyong Zhong, Yilin Cheng, Bichuan Feng, Pengfei Liu, Junfeng Fang, Xiang Wang*. [[pdf](https://arxiv.org/pdf/2605.07711)], 2026.05. ![](https://img.shields.io/badge/Blog2025-orange)

#### Black-Box
- **Black-Box On-Policy Distillation of Large Language Models**  
  *Tianzhu Ye, Li Dong, Zewen Chi, Xun Wu, Shaohan Huang, Furu Wei*. [[pdf](https://arxiv.org/pdf/2511.10643)], 2025.11. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **OVD: On-policy Verbal Distillation**  
  *Jing Xiong, Hui Shen, Shansan Gong, Yuxin Cheng, Jianghan Shen, Chaofan Tao, Haochen Tan, Haoli Bai, Lifeng Shang, Ngai Wong*. [[pdf](https://arxiv.org/pdf/2601.21968)], 2026.01. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **SODA: Semi On-Policy Black-Box Distillation for Large Language Models**  
  *Xiwen Chen, Jingjing Wang, Wenhui Zhu, Peijie Qiu, Xuanzhao Dong, Hejian Sang, Zhipeng Wang, Alborz Geramifard, Feng Luo*. [[pdf](https://arxiv.org/pdf/2604.03873)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Rubric-based On-policy Distillation**  
  *Junfeng Fang, Zhepei Hong, Mao Zheng, Mingyang Song, Gengsheng Li, Houcheng Jiang, Dan Zhang, Haiyun Guo, Xiang Wang, Tat-Seng Chua*. [[pdf](https://arxiv.org/pdf/2605.07396)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)


### Analysis
- **Revisiting On-Policy Distillation: Empirical Failure Modes and Simple Fixes**  
  *Yuqian Fu, Haohuan Huang, Kaiwen Jiang, Yuanheng Zhu, Dongbin Zhao*. [[pdf](https://arxiv.org/pdf/2603.25562)], 2026.03. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Rethinking On-Policy Distillation of Large Language Models: Phenomenology, Mechanism, and Recipe**  
  *Yaxuan Li, Yuxin Zuo, Bingxiang He, Jinqian Zhang, Chaojun Xiao, Cheng Qian, Tianyu Yu, Huan-ang Gao, Wenkai Yang, Zhiyuan Liu, Ning Ding*. [[pdf](https://arxiv.org/pdf/2604.13016)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **TIP: Token Importance in On-Policy Distillation**  
  *Yuanda Xu, Hejian Sang, Zhengze Zhou, Ran He, Zhipeng Wang, Alborz Geramifard*. [[pdf](https://arxiv.org/pdf/2604.14084)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **The Extrapolation Cliff in On-Policy Distillation of Near-Deterministic Structured Outputs**  
  *Xin Li, Hao Jiang, Annan Wang, Yichi Zhang, Chau Yuen*. [[pdf](https://arxiv.org/pdf/2605.08737)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Cornerstones or Stumbling Blocks? Deciphering the Rock Tokens in On-Policy Distillation**  
  *Yuxuan Jiang, Runchao Li, Shubhashis Roy Dipta, Dawei Li, Zhao Yang*. [[pdf](https://arxiv.org/pdf/2605.09253)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Unmasking On-Policy Distillation: Where It Helps, Where It Hurts, and Why**  
  *Mohammadreza Armandpour, Fatih Ilhan, David Harrison, Ajay Jaiswal, Duc N. M Hoang, Fartash Faghri, Yizhe Zhang, Minsik Cho, Mehrdad Farajtabar*. [[pdf](https://arxiv.org/pdf/2605.10889)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **The Many Faces of On-Policy Distillation: Pitfalls, Mechanisms, and Fixes**  
  *Siqi Zhu, Xuyan Ye, Hongyu Lu, Weiye Shi, Ge Liu*. [[pdf](https://arxiv.org/pdf/2605.11182)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Learning to Foresee: Unveiling the Unlocking Efficiency of On-Policy Distillation**  
  *Yuchen Cai, Ding Cao, Liang Lin, Chunxi Luo, Xin Xu, Kai Yang, Weijie Liu, Saiyong Yang, Tianxiang Zhao, Guangzhong Sun, Guiquan Liu, Junfeng Fang*. [[pdf](https://arxiv.org/pdf/2605.11739)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Beyond GRPO and On-Policy Distillation: An Empirical Sparse-to-Dense Reward Principle for Language-Model Post-Training**  
  *Yuanda Xu, Hejian Sang, Zhengze Zhou, Ran He, Zhipeng Wang, Alborz Geramifard*. [[pdf](https://arxiv.org/pdf/2605.12483)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Decoupling KL and Trajectories: A Unified Perspective for SFT, DAgger, Offline RL, and OPD in LLM Distillation**  
  *Anhao Zhao, Haoran Xin, Yingqi Fan, Junlong Tong, Wenjie Li, Xiaoyu Shen*. [[pdf](https://arxiv.org/pdf/2605.16826)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)

### Data
- **Emergent and Subliminal Misalignment Through the Lens of Data-Mediated Transfer**  
  *Baris Askin, Muhammed Ustaomeroglu, Anupam Nayak, Gauri Joshi, Guannan Qu, Carlee Joe-Wong*. [[pdf](https://arxiv.org/pdf/2605.12798)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Always Learning, Always Mixing: Efficient and Simple Data Mixing All The Time**  
  *Michael Y. Hu, Apurva Gandhi, Kyunghyun Cho, Tal Linzen, Pratyusha Sharma*. [[pdf](https://arxiv.org/pdf/2605.15220)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **DeltaPrompts: Escaping the Zero-Delta Trap in Multimodal Distillation**  
  *Jaehun Jung, Hyunwoo Kim, Brandon Cui, Ximing Lu, David Acuna, Prithviraj Ammanabrolu, Yejin Choi*. [[pdf](https://arxiv.org/pdf/2605.15532)], 2026.05. ![](https://img.shields.io/badge/Arxiv2026-orange)

### Survey
- **A Survey of On-Policy Distillation for Large Language Models**  
  *Mingyang Song, Mao Zheng*. [[pdf](https://arxiv.org/pdf/2604.00626)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)
- **Large Language Model Post-Training: A Unified View of Off-Policy and On-Policy Learning**  
  *Shiwan Zhao, Zhihu Wang, Xuyang Zhao, Jiaming Zhou, Caiyue Xu, Chenfei Liu, Liting Zhang, Yuhang Jia, Yanzhe Zhang, Hualong Yu, Zichen Xu, Qicheng Li, Yong Qin*. [[pdf](https://arxiv.org/pdf/2604.07941)], 2026.04. ![](https://img.shields.io/badge/Arxiv2026-orange)