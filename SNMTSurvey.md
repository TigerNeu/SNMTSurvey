 # A Survey of Streaming Neural Machine Translation

In this document, we survey papers on streaming neural machine translation (SNMT). We devide these papers into different topics according to the category technology. In addition, this document shows the list of the papers with urls. 

## Categorization

+ Text to Text Streaming Neural Machine Translation
    + <a href="#Two-Stage-Policy">Two Stage Policy</a>
    + <a href="#Wait-K-Based-Policy">Wait-K Based Policy</a>
    + <a href="#End-to-end-Flexible-Policy">End-to-end Flexible Policy</a>
    + <a href="#Other-Exploration">Other Exploration</a>
<p align="left"><img src="https://s2.loli.net/2022/05/10/y6QnjTR3hHFLcPV.png"  width="100%" height="100%" /></p>

+ Speech to Text Streaming Neural Machine Translation
    + <a href="#To-Be-Continued">To Be Continued ...</a>

## SNMT Paper List

#### [Two Stage Policy](#content)

1. **Can neural machine translation do simultaneous translation?** arXiv 2016 [paper](https://arxiv.org/abs/1606.02012)

    *Kyunghyun Cho, Masha Esipova*

2. **Learning to Translate in Real-time with Neural Machine Translation** ACL 2017 [paper](https://arxiv.org/abs/1610.00388)

    *Jiatao Gu, Graham Neubig, Kyunghyun Cho, Victor O.K. Li*

3. **Prediction Improves Simultaneous Neural Machine Translation** ACL 2018 [paper](https://aclanthology.org/D18-1337.pdf)

    *Ashkan Alinejad, Maryam Siahbani, Anoop Sarkar*

4. **Incremental Decoding and Training Methods for Simultaneous Translation in Neural Machine Translation** ACL 2018 [paper](https://arxiv.org/abs/1806.03661)

    *Ashkan Alinejad, Maryam Siahbani, Anoop Sarkar*

5. **A General Framework for Adaptation of Neural Machine Translation to Simultaneous Translation** AACL 2020 [paper](https://arxiv.org/abs/1911.03154)

    *Yun Chen, Liangyou Li, Xin Jiang, Xiao Chen, Qun Liu*

6. **Full-Sentence Models Perform Better in Simultaneous Translation Using the Information Enhanced Decoding Strategy** arXiv 2021 [paper](https://arxiv.org/abs/2105.01893)

    *Zhengxin Yang*

#### [Wait-K Based Policy](#content)

1. **STACL: Simultaneous Translation with Implicit Anticipation and Controllable Latency using Prefix-to-Prefix Framework** ACL 2019 [paper](https://arxiv.org/abs/1810.08398)

    *Mingbo Ma, Liang Huang, Hao Xiong, Renjie Zheng, Kaibo Liu, Baigong Zheng, Chuanqiang Zhang, Zhongjun He, Hairong Liu, Xing Li, Hua Wu, Haifeng Wang*

2. **Speculative Beam Search for Simultaneous Translation** EMNLP 2019 [paper](https://arxiv.org/abs/1909.05421)

    *Renjie Zheng, Mingbo Ma, Baigong Zheng, Liang Huang*

3. **Opportunistic Decoding with Timely Correction for Simultaneous Translation** ACL 2020 [paper](https://arxiv.org/abs/2005.00675)

    *Renjie Zheng, Mingbo Ma, Baigong Zheng, Kaibo Liu, Liang Huang*

4. **Simultaneous Translation Policies: From Fixed to Adaptive** ACL 2020 [paper](https://arxiv.org/abs/2004.13169)

    *Baigong Zheng, Kaibo Liu, Renjie Zheng, Mingbo Ma, Hairong Liu, Liang Huang*

5. **Efficient Wait-k Models for Simultaneous Machine Translation** INTERSPEECH 2020 [paper](https://arxiv.org/abs/2005.08595)

    *Maha Elbayad, Laurent Besacier, Jakob Verbeek*

6. **Future-Guided Incremental Transformer for Simultaneous Translation** AAAI 2021 [paper](https://arxiv.org/abs/2012.12465)

    *Shaolei Zhang, Yang Feng, Liangyou Li*

7. **Universal Simultaneous Machine Translation with Mixture-of-Experts Wait-k Policy** EMNLP 2021 [paper](https://arxiv.org/abs/2109.05238)

    *Shaolei Zhang, Yang Feng*

#### [End-to-end Flexible Policy](#content)

1. **Simpler and Faster Learning of Adaptive Policies for Simultaneous Translation** EMNLP 2019 [paper](https://arxiv.org/abs/1909.01559)

    *Baigong Zheng, Renjie Zheng, Mingbo Ma, Liang Huang*

2. **Simultaneous Neural Machine Translation using Connectionist Temporal Classification** arXiv 2019 [paper](https://arxiv.org/abs/1911.11933)

    *Katsuki Chousa, Katsuhito Sudoh, Satoshi Nakamura*

3. **Towards Stream Translation: Adaptive Computation Time for Simultaneous Machine Translation.** IWSLT 2020 [paper](https://aclanthology.org/2020.iwslt-1.28/)

    *Felix Schneider, Alexander Waibel*


###### Attention based

1. **Online and linear-time attention by enforcing monotonic alignments** ICML 2017 [paper](http://proceedings.mlr.press/v70/raffel17a.html?ref=https://githubhelp.com)

    *Colin Raffel, Minh-Thang Luong, Peter J. Liu, Ron J. Weiss, Douglas Eck*

2. **Monotonic Chunkwise Attention** ICLR 2018 [paper](https://arxiv.org/abs/1712.05382)

    *Chung-Cheng Chiu, Colin Raffel*

3. **Monotonic Infinite Lookback Attention for Simultaneous Machine Translation** ACL 2019 [paper](https://arxiv.org/abs/1906.05218)

    *Naveen Arivazhagan, Colin Cherry, Wolfgang Macherey, Chung-Cheng Chiu, Semih Yavuz, Ruoming Pang, Wei Li, Colin Raffel*

4. **Monotonic Multihead Attention** ICLR 2020 [paper](https://arxiv.org/abs/1909.12406)

    *Xutai Ma, Juan Pino, James Cross, Liezl Puzon, Jiatao Gu*


###### Reinforcement Learning based

1. **Simultaneous Translation with Flexible Policy via Restricted Imitation Learning** ACL 2019 [paper](https://arxiv.org/abs/1906.01135)

    *Baigong Zheng, Renjie Zheng, Mingbo Ma, Liang Huang*

2. **Learning Coupled Policies for Simultaneous Machine Translation using Imitation Learning** EACL 2021 [paper](https://arxiv.org/abs/2002.04306)

    *Philip Arthur, Trevor Cohn, Gholamreza Haffari*

#### [Other Exploration](#content)

1. **Learning Adaptive Segmentation Policy for Simultaneous Translation** EMNLP 2020 [paper](https://aclanthology.org/2020.emnlp-main.178/)

    *Ruiqing Zhang, Chuanqiang Zhang, Zhongjun He, Hua Wu, Haifeng Wang*

2. **Temporally Correlated Task Scheduling for Sequence Learning** ICML 2021 [paper](https://proceedings.mlr.press/v139/wu21e.html)

    *Xueqing Wu, Lewen Wang, Yingce Xia, Weiqing Liu, Lijun Wu, Shufang Xie, Tao Qin, Tie-Yan Liu*


###### Re-translation

1. **Re-translation versus Streaming for Simultaneous Translation** arXiv 2020 [paper](https://arxiv.org/abs/2004.03643)

    *Naveen Arivazhagan, Colin Cherry, Wolfgang Macherey, George Foster*

2. **Faster Re-translation Using Non-Autoregressive Model For Simultaneous Neural Machine Translation** arXiv 2020 [paper](https://arxiv.org/abs/2012.14681)

    *Hyojung Han, Sathish Indurthi, Mohd Abbas Zaidi, Nikhil Kumar Lakumarapu, Beomseok Lee, Sangha Kim, Chanwoo Kim, Inchul Hwang*

###### Multimodal SNMT

1. **Towards Multimodal Simultaneous Neural Machine Translation** EMNLP 2020 [paper](https://arxiv.org/abs/2004.03180)

    *Aizhan Imankulova, Masahiro Kaneko, Tosho Hirasawa, Mamoru Komachi*

2. **Simultaneous Machine Translation with Visual Context** EMNLP 2020 [paper](https://arxiv.org/abs/2009.07310)

    *Ozan Caglayan, Julia Ive, Veneta Haralampieva, Pranava Madhyastha, Loïc Barrault, Lucia Specia*

3. **Exploiting Multimodal Reinforcement Learning for Simultaneous Machine Translation** EACL 2021 [paper](https://arxiv.org/abs/2102.11387)

    *Julia Ive, Andy Mingren Li, Yishu Miao, Ozan Caglayan, Pranava Madhyastha, Lucia Specia*

###### Multilingual SNMT

1. **Multilingual Simultaneous Neural Machine Translation** ACL 2021 [paper](https://aclanthology.org/2021.findings-acl.420.pdf)

    *Philip Arthur, Dongwon Ryu, Gholamreza Haffari*

2. **Simultaneous Multi-Pivot Neural Machine Translation** arXiv 2021 [paper](https://arxiv.org/abs/2104.07410)

    *Raj Dabre, Aizhan Imankulova, Masahiro Kaneko, Abhisek Chakrabarty*

###### Document-level SNMT

1. **Studying The Impact Of Document-level Context On Simultaneous Neural Machine Translation** MTSummit 2021 [paper](https://aclanthology.org/2021.mtsummit-research.17/)

    *Raj Dabre, Aizhan Imankulova, Masahiro Kaneko*

###### Reorder

1. **Improving Simultaneous Translation by Incorporating Pseudo-References with Fewer Reorderings** EMNLP 2021 [paper](https://arxiv.org/abs/2010.11247)

    *Junkun Chen, Renjie Zheng, Atsuhito Kita, Mingbo Ma, Liang Huang*

2. **Simultaneous Neural Machine Translation with Constituent Label Prediction** EMNLP 2021 [paper](https://arxiv.org/abs/2110.13480)

    *Yasumasa Kano, Katsuhito Sudoh, Satoshi Nakamura*

###### Simultaneous Evaluation

1. **Thinking Slow about Latency Evaluation for Simultaneous Machine Translation** arXiv 2019 [paper](https://arxiv.org/abs/1906.00048)

    *Colin Cherry, George Foster*

2. **SimulEval: An Evaluation Toolkit for Simultaneous Translation** EMNLP 2020 [paper](https://arxiv.org/abs/2007.16193)

    *Xutai Ma, Mohammad Javad Dousti, Changhan Wang, Jiatao Gu, Juan Pino*

3. **Stream-level Latency Evaluation for Simultaneous Machine Translation** EMNLP 2021 [paper](https://arxiv.org/abs/2104.08817)

    *Javier Iranzo-Sánchez, Jorge Civera, Alfons Juan*

4. **It is Not as Good as You Think! Evaluating Simultaneous Machine Translation on Interpretation Data** EMNLP 2021 [paper](https://arxiv.org/abs/2110.05213)

    *Jinming Zhao, Philip Arthur, Gholamreza Haffari, Trevor Cohn, Ehsan Shareghi*


#### [To Be Continued ...](#content)


## Team Members

The project is maintained by <b>*Laohu Wang*</b>

Please feel free to contact us if you have any questions (wanglaohu [at] TigerNeu@outlook.com).
