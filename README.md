# GEC-Reading-List
A grammatical error correction reading list maintained by Beijing Language and Culture University Natural Language Processing Group

---

* [GEC-Reading-List](#gec-reading-list)
   * [Shared Task](#shared-task)
   * [Dataset](#dataset)
   * [Evaluation](#evaluation)
   * [SMT&amp;NMT](#smtnmt)
   * [NMT](#nmt)
   * [Language Model](#language-model)
   * [Labeling&amp;Tagging](#labelingtagging)
   * [OTHERS](#others)
   * [Algorithms](#algorithms)
   * [Spell Checking](#spell-checking)
   * [BEA2019 Competition](#bea2019-competition)
   * [GED system](#ged-system)

## Shared Task

*  Christopher Bryant, Mariano Felice, Øistein Andersen and Ted Briscoe. 2019. [Building Educational Applications 2019 Shared Task:Grammatical Error Correction](https://www.aclweb.org/anthology/W19-4406).
*  Ng Hwee Tou, Wu Siew Mei, Briscoe Ted, Hadiwinoto Christian, Susanto Raymond Hendy and Bryant Christopher. 2014. [The CoNLL-2014 Shared Task on Grammatical Error Correction](https://www.aclweb.org/anthology/W14-1701). In Proceedings of the Eighteenth Conference on Computational Natural Language Learning: Shared Task.
*  Ng Hwee Tou,	Wu Siew Mei, Wu Yuanbin, Hadiwinoto Christian and Tetreault  Joel. 2013. [The CoNLL-2013 Shared Task on Grammatical Error Correction](https://www.aclweb.org/anthology/W13-3601). In Proceedings of the Seventeenth Conference on Computational Natural Language Learning: Shared Task.
*  Dale Robert, Anisimoff Ilya and Narroway George. 2012. [HOO 2012: A Report on the Preposition and Determiner Error Correction Shared Task](https://dl.acm.org/citation.cfm?id=2390390). In Proceedings of the Seventh Workshop on Building Educational Applications Using NLP.
*  Dale Robert and Kilgarriff Adam. 2011. [Helping our own: The HOO 2011 pilot shared task](https://dl.acm.org/citation.cfm?id=2187725). In Proceedings of the 13th European Workshop on Natural Language Generation.

## Dataset

*  Flachs S, Lacroix O, Yannakoudakis H, et al. 2020. [Grammatical Error Correction in Low Error Density Domains: A New Benchmark and Analyses](https://arxiv.org/abs/2010.07574). EMNLP 2020.
*  Napoles C, Nădejde M, Tetreault J. 2019. [Enabling robust grammatical error correction in new domains: Data sets, metrics, and analyses](https://transacl.org/ojs/index.php/tacl/article/view/1677). Transactions of the Association for Computational Linguistics 2019.
*  Rozovskaya A, Roth D. 2019. [Grammar error correction in morphologically rich languages: The case of Russian](https://transacl.org/index.php/tacl/article/view/1454). Transactions of the Association for Computational Linguistics 2019.
*  Yannakoudakis Helen, Andersen Øistein E, Geranpayeh Ardeshir, Briscoe Ted and Nicholls Diane. 2018. [Developing an automated writing placement system for ESL learners](https://www.tandfonline.com/doi/abs/10.1080/08957347.2018.1464447). Applied Measurement in Education. (W&I)
*  Napoles Courtney, Sakaguchi Keisuke and Tetreault Joel. 2017. [JFLEG: A fluency corpus and benchmark for grammatical error correction](https://arxiv.org/pdf/1702.04066.pdf). (JFLEG)
*  Dahlmeier Daniel, Ng Hwee Tou and Wu Siew Mei. 2013. [Building a large annotated corpus of learner English: The NUS corpus of learner English](https://www.aclweb.org/anthology/W13-1703). In Proceedings of the eighth workshop on innovative use of NLP for building educational applications. (NUCLE)
*  Yannakoudakis Helen, Briscoe Ted and Medlock Ben. 2011. [A new dataset and method for automatically grading ESOL texts](https://dl.acm.org/citation.cfm?id=2002496).  In Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies. (FCE)
*  Mizumoto Tomoya, Komachi Mamoru, Nagata Masaaki and Matsumoto Yuji. 2011. [Mining revision log of language learning SNS for automated Japanese error correction of second language learners](https://www.aclweb.org/anthology/I11-1017). In Proceedings of 5th International Joint Conference on Natural Language Processing. (lang-8)
*  Sylviane Granger. 1998. [The computer learner corpus: A versatile new source of data for SLA research](https://www.researchgate.net/profile/Sylviane_Granger/publication/237128463_The_computer_learner_corpus_A_versatile_new_source_of_data_for_SLA_research/links/0c96051dc1c596def1000000/The-computer-learner-corpus-A-versatile-new-source-of-data-for-SLA-research.pdf). Learner English on Computer. (LOCNESS)

## Evaluation

*  Islam, Md Asadul, and Enrico Magnani. 2021. [Is This the End of the Gold Standard? A Straightforward Reference-Less Grammatical Error Correction Metric](https://aclanthology.org/2021.emnlp-main.239.pdf). In *Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing*, Association for Computational Linguistics, 3009–15.
*  Liu, Zhenghao et al. 2021. [Neural Quality Estimation with Multiple Hypotheses for Grammatical Error Correction](https://aclanthology.org/2021.naacl-main.429.pdf). In *Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies*, Association for Computational Linguistics, 5441–52.
*  Bryant Christopher, Felice Mariano, Briscoe Edward John. 2017. [Automatic annotation and evaluation of error types for grammatical error correction](https://www.aclweb.org/anthology/P17-1074). In Proceedings of the 55th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers).(ERRANT)
*  Napoles Courtney, Sakaguchi Keisuke, Post Matt and Tetreault Joel. 2015. [Ground truth for grammatical error correction metrics](https://www.aclweb.org/anthology/P15-2097). In Proceedings of the 53rd Annual Meeting of the Association for Computational Linguistics and the 7th International Joint Conference on Natural Language Processing (Volume 2: Short Papers).(GLEU)
*  Dahlmeier Daniel and Ng Hwee Tou. 2012. [Better evaluation for grammatical error correction](https://dl.acm.org/citation.cfm?id=2382118). In Proceedings of the 2012 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies. (Maxmatch,M2)
*  Snover, Matthew, Bonnie J. Dorr, Richard M. Schwartz, Linnea Micciulla and Ralph M. Weischedel. 2005. [A STUDY OF TRANSLATION ERROR RATE WITH TARGETED HUMAN ANNOTATION.](https://pdfs.semanticscholar.org/a589/9f1ec92af7d01f35225161430116a6eabbea.pdf). In Proceedings of Computer Science. (TER)

## SMT&NMT

*  Grundkiewicz Roman, Junczys-Dowmunt MarcinNear. 2018. [Human-Level Performance in Grammatical Error Correction with Hybrid Machine Translation](https://www.aclweb.org/anthology/N18-2046). In Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 2 (Short Papers).

*  Chollampatt Shamil, Ng Hwee Tou. 2017. [Connecting the Dots Towards Human-Level Grammatical Error Correction](https://www.aclweb.org/anthology/W17-5037). In Proceedings of the 12th Workshop on Innovative Use of NLP for Building Educational Applications.

*  Chollampatt Shamil, Hoang Duc Tam, Ng Hwee Tou. 2016. [Adapting Grammatical Error Correction Based on the Native Language of Writers with Neural Network Joint Models](https://www.aclweb.org/anthology/D16-1195). In Proceedings of the 2016 Conference on Empirical Methods in Natural Language Processing.

## NMT

*  Yuan, Zheng, and Christopher Bryant. 2021. [Document-Level Grammatical Error Correction](https://aclanthology.org/2021.bea-1.8.pdf). In *Proceedings of the 16th Workshop on Innovative Use of NLP for Building Educational Applications*, Association for Computational Linguistics, 75–84.
*  Gotou T, Nagata R, Mita M, et al.  2020 [Taking the Correction Difficulty into Account in Grammatical Error Correction Evaluation](https://www.aclweb.org/anthology/2020.coling-main.188/). Proceedings of the 28th International Conference on Computational Linguistics.
*  Hotate K, Kaneko M, Komachi M. 2020. [Generating Diverse Corrections with Local Beam Search for Grammatical Error Correction](https://www.aclweb.org/anthology/2020.coling-main.193/). Proceedings of the 28th International Conference on Computational Linguistics.
*  Yoshimura R, Kaneko M, Kajiwara T, et al. 2020.[SOME: Reference-less Sub-Metrics Optimized for Manual Evaluations of Grammatical Error Correction](https://www.aclweb.org/anthology/2020.coling-main.573/). Proceedings of the 28th International Conference on Computational Linguistics.
*  Yamashita I, Katsumata S, Kaneko M, et al.2020. [Cross-lingual Transfer Learning for Grammatical Error Correction](https://www.aclweb.org/anthology/2020.coling-main.415/). Proceedings of the 28th International Conference on Computational Linguistics.
*  Wan Z, Wan X, Wang W. 2020. [Improving Grammatical Error Correction with Data Augmentation by Editing Latent Representation](https://www.aclweb.org/anthology/2020.coling-main.200/). Proceedings of the 28th International Conference on Computational Linguistics.
*  Hinson C, Huang H H, Chen H H. 2020. [Heterogeneous Recycle Generation for Chinese Grammatical Error Correction](https://www.aclweb.org/anthology/2020.coling-main.199/). Proceedings of the 28th International Conference on Computational Linguistics.
*  Caines A, Bentz C, Knill K, et al. 2020. [Grammatical error detection in transcriptions of spoken English](https://www.aclweb.org/anthology/2020.coling-main.195/). Proceedings of the 28th International Conference on Computational Linguistics.
*  Zhao Wei, Wang Liang, Shen Kewei, Jia Ruoyu, Liu Jingming. 2019. [Improving Grammatical Error Correction via Pre-Training a Copy-Augmented Architecture with Unlabeled Data](https://arxiv.org/pdf/1903.00138.pdf).
*  Junczys-Dowmunt Marcin, Grundkiewicz Roman, Guha Shubha, Heafield Kenneth. 2018. [Approaching Neural Grammatical Error Correction as a Low-Resource Machine Translation Task](https://www.aclweb.org/anthology/N18-1055). In Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 1 (Long Papers).
*  Chollampatt Shamil, Ng Hwee Tou. 2018. [Neural Quality Estimation of Grammatical Error Correction](https://www.aclweb.org/anthology/D18-1274). In Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing.
*  Chollampatt Shamil, Ng Hwee Tou. 2018. [A Multilayer Convolutional Encoder-Decoder Neural Network for Grammatical Error Correction](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17308/16137). In Thirty-Second AAAI Conference on Artificial Intelligence.
*  Kasewa Sudhanshu, Stenetorp Pontus, Riedel Sebastian. 2018. [Wronging a Right: Generating Better Errors to Improve Grammatical Error Detection](https://www.aclweb.org/anthology/D18-1541). In Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing.
*  Jared Lichtarge, Christopher Alberti, Shankar Kumar, Noam Shazeer, Niki Parmar (Google AI). 2018. [Weakly Supervised Grammatical Error Correction using Iterative Decoding](https://arxiv.org/abs/1811.01710). arxiv.
*  Adriane Boyd. 2018. [Using Wikipedia Edits in Low Resource Grammatical Error Correction](https://www.aclweb.org/anthology/W18-6111). In Proceedings ofthe 2018 EMNLP Workshop W-NUT: The 4th Workshop on Noisy User-generated Text, pages 79–84 Brussels.
*  Keisuke Sakaguchi, Matt Post, Benjamin Van Durme. 2017. [Grammatical Error Correction with Neural Reinforcement Learning](https://www.aclweb.org/anthology/I17-2062). In Proceedings of the Eighth International Joint Conference on Natural Language Processing (Volume 2: Short Papers).
*  Xie Ziang, Avati Anand, Arivazhagan Naveen, Jurafsky Dan, Ng Andrew Y. 2016. [Neural Language Correction with Character-Based Attention](https://arxiv.org/pdf/1603.09727.pdf). arxiv.(LM in beam search)

## Language Model

*  Yasunaga, Michihiro et al. 2021. [LM-Critic: Language Models for Unsupervised Grammatical Error Correction](https://arxiv.org/pdf/2109.06822.pdf). *arXiv:2109.06822*.
*  Masahiro Kaneko, Masato Mita, Shun Kiyono, Jun Suzuki, Kentaro Inui. 2020. [Encoder-Decoder Models Can Benefit from Pre-trained Masked Language Models in Grammatical Error Correction](https://arxiv.org/pdf/2005.00987.pdf). In Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics, pages 4248–4254 July 5 - 10, 2020. c 2020 Association for Computational Linguistics.(BERT-fuse)
*  Hongfei Wang, Michiki Kurosawa, Satoru Katsumata and Mamoru Komachi. 2020. [Chinese Grammatical Correction Using BERT-based Pre-trained Model](https://arxiv.org/pdf/2011.02093.pdf). In Proceedings of AACL-IJCNLP 2020.(BERT-Chinese)
*  Fan Yin, Quanyu Long, Tao Meng, and Kai-Wei Chang. 2020. [On the Robustness of Language Encoders against Grammatical Errors](https://arxiv.org/pdf/2005.05683.pdf). In Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics, pages 3386–3403 July 5 - 10, 2020. c 2020 Association for Computational Linguistics(BERT Analysis)
*  Satoru Katsumata, Mamoru Komachi. 2020. [Stronger Baselines for Grammatical Error Correction Using a Pretrained Encoder–Decoder Model](https://arxiv.org/pdf/2005.11849.pdf). In Proceedings of AACL-IJCNLP 2020 (BART,mBART)
*  Jianshu Ji, Qinlong Wang, Kristina Toutanova, YongenGong, Steven Truong, and Jianfeng Gao. 2017.  [A nested attention neural hybrid model for grammatical error correction.](https://www.aclweb.org/anthology/P17-1070.pdf). In Proceedings of the 55th Annual Meeting of the Association for ComputationalLinguistics. Association for Computational Linguistics, pages 753–762.(LM in rerank)
*  Kenneth Heafield. 2011. [KenLM: Faster and Smaller Language Model Queries](https://www.aclweb.org/anthology/W11-2123). In Proceedings of the Sixth Workshop on Statistical Machine Translation, WMT’11, pages 187–197, Stroudsburg, USA. Association for Computational Linguistics.(KenLM)
*  Pascal Vincent, Hugo Larochelle, Yoshua Bengio, and Pierre-Antoine Manzagol. 2008. [Corpora Generation for Grammatical Error Correction](http://delivery.acm.org/10.1145/1400000/1390294/p1096-vincent.pdf?ip=123.127.77.18&id=1390294&acc=ACTIVE%20SERVICE&key=BF85BBA5741FDC6E%2E3079BB709085A683%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1568555058_da2bb710b2c14749225dc84cdd8b2136). In Proceedings of the 25th international conference on Machine learning, pages 1096–1103. ACM.(DAE)

## Labeling&Tagging 

*  Li, Piji, and Shuming Shi. 2021. [Tail-to-Tail Non-Autoregressive Sequence Prediction for Chinese Grammatical Error Correction](https://aclanthology.org/2021.acl-long.385.pdf). In *Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers)*, Association for Computational Linguistics, 4973–84.
*  Parnow, Kevin et al. 2021. [Grammatical Error Correction as GAN-like Sequence Labeling](https://aclanthology.org/2021.findings-acl.290.pdf). In *Findings of the Association for Computational Linguistics: ACL-IJCNLP 2021*, Association for Computational Linguistics, 3284–90.
*  Kostiantyn Omelianchuk, Vitaliy Atrasevych, Artem Chernodub, Oleksandr Skurzhanskyi. 2020. [GECToR – Grammatical Error Correction: Tag, Not Rewrite](https://arxiv.org/pdf/2005.12592.pdf). in Proceedings of the 15th Workshop on Innovative Use of NLP for Building Educational Applications, pages 163–170. Association for Computational Linguistics.
*  Abhijeet Awasthi, Sunita Sarawagi , Rasna Goyal , Sabyasachi Ghosh , Vihari Piratla. 2019. [Parallel Iterative Edit Models for Local Sequence Transduction](https://www.aclweb.org/anthology/D19-1435.pdf). In Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing, pages 4260–4270, Hong Kong, China. Association for Computational Linguistics.
*  Eric Malmi, Sebastian Krause, Sascha Rothe, Daniil Mirylenka, Aliaksei Severyn. 2019. [Encode, Tag, Realize: High-Precision Text Editing](https://www.aclweb.org/anthology/D19-1510.pdf). In Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP).

## OTHERS

*  Gan, Zifa et al. 2021. [Self-Supervised Curriculum Learning for Spelling Error Correction](https://aclanthology.org/2021.emnlp-main.281.pdf). In *Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing*, Association for Computational Linguistics, 3487–94.
*  Rothe, Sascha et al. 2021. [A Simple Recipe for Multilingual Grammatical Error Correction](https://aclanthology.org/2021.acl-short.89.pdf). In *Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 2: Short Papers)*, Association for Computational Linguistics, 702–7.
*  Stahlberg, Felix, and Shankar Kumar. 2021. [Synthetic Data Generation for Grammatical Error Correction with Tagged Corruption Models](https://aclanthology.org/2021.bea-1.4.pdf). In *Proceedings of the 16th Workshop on Innovative Use of NLP for Building Educational Applications*, Association for Computational Linguistics, 37–47.
*  Flachs, Simon et al. 2021. [Data Strategies for Low-Resource Grammatical Error Correction](https://aclanthology.org/2021.bea-1.12.pdf). In *Proceedings of the 16th Workshop on Innovative Use of NLP for Building Educational Applications*, Association for Computational Linguistics, 117–22.
*  Koyama, Aomi et al. 2021. [Comparison of Grammatical Error Correction Using Back-Translation Models](https://aclanthology.org/2021.naacl-srw.16.pdf). In *Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Student Research Workshop*, Association for Computational Linguistics, 126–35.
*  Lichtarge Jared, Alberti Chris, Kumar Shankar, Shazeer Noam, Parmar Niki, Tong Simon. 2019. [Corpora Generation for Grammatical Error Correction](https://arxiv.org/pdf/1904.05780.pdf). arxiv.
*  Ge Tao, Wei Furu, Zhou Ming. 2018. [Fluency Boost Learning and Inference for Neural Grammatical Error Correction](https://www.aclweb.org/anthology/P18-1097). In Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers).
*  Bryant Christopher, Briscoe Ted. 2018. [Language Model Based Grammatical Error Correction without Annotated Training Data](https://www.aclweb.org/anthology/W18-0529). In Proceedings of the Thirteenth Workshop on Innovative Use of NLP for Building Educational Applications.
*  Rico Sennrich, Barry Haddow, and Alexandra Birch. 2016. [Neural Machine Translation of Rare Words with Subword Units](https://arxiv.org/pdf/1508.07909.pdf). In Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers). Association for Computational Linguistics, Berlin, Germany, pages 1715–1725.(BPE)
*  Franz Josef Och. 2003. [Minimum Error Rate Training in Statistical Machine Translation](https://www.aclweb.org/anthology/P03-1021.pdf). In Proceedings of the Annual Meeting of the Association for Computational Linguistics. (MERT)

## Algorithms

*  Sun, Xin et al. 2021. [Instantaneous Grammatical Error Correction with Shallow Aggressive Decoding](https://aclanthology.org/2021.acl-long.462.pdf). In *Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers)*, Association for Computational Linguistics, 5937–47.
*  V. H. QuanMarcello, Marcello Federico, Mauro Cettolo. 2005. [Integrated n-best re-ranking for spoken language translation](https://www.researchgate.net/publication/221483809_Integrated_n-best_re-ranking_for_spoken_language_translation). in Proceedings of the 9th European Conference on Speech Communication and Technology, Lisbon, Portugal, September 4-8, 2005
*  Yen-Lu Chow and Richard Schwartz. 1989. [The n-best algorithm: An efficient procedure for finding top n sentence hypotheses](https://www.aclweb.org/anthology/H89-2027.pdf). in Proceedings of the workshop on Speech and Natural Language. Association for Computational Linguistics, 1989, pp.199–202.

## Spell Checking

*  Liu, Shulin et al. 2021. [PLOME: Pre-Training with Misspelled Knowledge for Chinese Spelling Correction](https://aclanthology.org/2021.acl-long.233.pdf). In *Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers)*, Association for Computational Linguistics, 2991–3000.
*  Huang, Li et al. 2021. [PHMOSpell: Phonological and Morphological Knowledge Guided Chinese Spelling Check](https://aclanthology.org/2021.acl-long.464.pdf). In *Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers)*, Association for Computational Linguistics, 5958–67.
*  Wang, Baoxin et al. 2021. [Dynamic Connected Networks for Chinese Spelling Check](https://aclanthology.org/2021.findings-acl.216.pdf). In *Findings of the Association for Computational Linguistics: ACL-IJCNLP 2021*, Association for Computational Linguistics, 2437–46.
*  Zhang, Ruiqing et al. 2021. [Correcting Chinese Spelling Errors with Phonetic Pre-Training](https://aclanthology.org/2021.findings-acl.198.pdf). In *Findings of the Association for Computational Linguistics: ACL-IJCNLP 2021*, Association for Computational Linguistics, 2250–61.
*  Leng, Yichong et al. 2021. [FastCorrect: Fast Error Correction with Edit Alignment for Automatic Speech Recognition](https://arxiv.org/abs/2105.03842). *arXiv:2105.03842*.
*  Xu, Heng-Da et al. 2021. [Read, Listen, and See: Leveraging Multimodal Information Helps Chinese Spell Checking](https://aclanthology.org/2021.findings-acl.64.pdf). In *Findings of the Association for Computational Linguistics: ACL-IJCNLP 2021*, Association for Computational Linguistics, 716–28.
*  Zheng, Liying et al. 2021. [An Alignment-Agnostic Model for Chinese Text Error Correction](https://aclanthology.org/2021.findings-emnlp.30.pdf). In *Findings of the Association for Computational Linguistics: EMNLP 2021*, Association for Computational Linguistics, 321–26.
*  Shaohua Zhang, Haoran Huang, Jicong Liu, Hang Li. 2020. [Spelling Error Correction with Soft Masked BERT](https://www.aclweb.org/anthology/2020.acl-main.82.pdf). In Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics.
*  Xingyi Cheng, Weidi Xu, Kunlong Chen, Shaohua Jiang, Feng Wang, Taifeng Wang, Wei Chu, Yuan Qi. 2020. [SpellGCN: Incorporating Phonological and Visual Similarities into Language Models for Chinese Spelling Check](https://www.aclweb.org/anthology/2020.acl-main.81.pdf). In Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics.
*  Dingmin Wang, Yi Tay, Li Zhong. 2019. [Confusionset-guided Pointer Networks for Chinese Spelling Check](https://www.aclweb.org/anthology/P19-1578.pdf). In Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics.
*  Yuzhong Hong, Xianguo Yu, Neng He, Nan Liu, Junhui Liu. 2019. FASPell: [A Fast, Adaptable, Simple, Powerful Chinese Spell Checker Based On DAE-Decoder Paradigm](https://www.aclweb.org/anthology/D19-5522.pdf). In Proceedings of the 5th Workshop on Noisy User-generated Text (W-NUT 2019).
*  Dingmin Wang, Yan Song, Jing Li, Jialong Han, Haisong Zhang. 2018. [A Hybrid Approach to Automatic Corpus Generation for Chinese Spelling Check](https://www.aclweb.org/anthology/D18-1273.pdf). In Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing.

## BEA2019 Competition

*  Yoav Kantor, Yoav Katz, Leshem Choshen, Edo Cohen-Karlik, Naftali Liberman, Assaf Toledo, Amir Menczel, and Noam Slonim. 2019. [Learning to combine Grammatical Error Corrections](https://arxiv.org/pdf/1906.03897.pdf).  In Proceedings of the 14th Workshop on Innovative Use of NLP for Building Educational Applications. Association for Computational Linguistics. （combining, bea-sota）

*  Roman Grundkiewicz, Marcin Junczys-Dowmunt, and Kenneth Heafield. 2019. [Neural Grammatical Error Correction Systems with Unsupervised Pre-training on Synthetic Data](https://www.aclweb.org/anthology/W19-4427). In Proceedings of the 14th Workshop on Innovative Use of NLP for Building Educational Applications. Association for Computational Linguistics.（No. 1）

*  Yo Joong Choe, Jiyeon Ham, Kyubyong Park, and Yeoil Yoon. 2019. [A Neural Grammatical Error Correction System Built On Better Pre-training and Sequential Transfer Learning](https://arxiv.org/pdf/1907.01256.pdf).  In Proceedings of the 14th Workshop on Innovative Use of NLP for Building Educational Applications. Association for Computational Linguistics.（No. 2）

*  Ruobing Li, Chuan Wang, Yefei Zha, Yonghong Yu, Shiman Guo, Qiang Wang, Yang Liu, and Hui Lin. 2019. [The LAIX Systems in the BEA-2019 GEC Shared Task](https://www.aclweb.org/anthology/W19-4416). In Proceedings of the 14th Workshop on Innovative Use of NLP for Building Educational Applications. Association for Computational Linguistics.（No. 3）

*  Zheng Yuan, Felix Stahlberg, Marek Rei, Bill Byrne, and Helen Yannakoudakis. 2019. [Neural and FST-based approaches to grammatical error correction](https://www.aclweb.org/anthology/W19-4424).In Proceedings of the 14th Workshop on Innovative Use of NLP for Building Educational Applications. Association for Computational Linguistics.（No. 4）

*  Hiroki Asano, Tomoya Mizumoto, and Masato Mita. 2019. [The AIP-Tohoku System at the BEA-2019 Shared Task](https://www.aclweb.org/anthology/W19-4418). In Proceedings of the 14th Workshop on Innovative Use of NLP for Building Educational Applications. Association for Computational Linguistics.（No. 9）

*  Jakub Naplava and Milan Straka. 2019. [CUNI System for the Building Educational Applications 2019 Shared Task: Grammatical Error Correction](https://www.aclweb.org/anthology/W19-4419).  In Proceedings of the 14th Workshop on Innovative Use of NLP for Building Educational Applications. Association for Computational Linguistics.（No. 10）

*  Liner Yang and Chencheng Wang. 2019. [The BLCU System in the BEA 2019 Shared Task](https://www.aclweb.org/anthology/W19-4421). In Proceedings of the 14th Workshop on Innovative Use of NLP for Building Educational Applications. Association for Computational Linguistics.（No. 12）

*  Masahiro Kaneko, Kengo Hotate, Satoru Katsumata, and Mamoru Komachi. 2019. [TMU Transformer System Using BERT for Re-ranking at BEA 2019 Grammatical Error Correction on Restricted Track](https://www.aclweb.org/anthology/W19-4422). In Proceedings of the 14th Workshop on Innovative Use of NLP for Building Educational Applications. Association for Computational Linguistics.（No. 14）

## GED system

*  Caines A, Bentz C, Knill K, et al. 2020. [Grammatical error detection in transcriptions of spoken English](https://www.aclweb.org/anthology/2020.coling-main.195/). Proceedings of the 28th International Conference on Computational Linguistics.
*  Allen Schmaltz, Yoon Kim, Alexander M. Rush, and Stuart Shieber. 2016. [Sentence-Level Grammatical Error Identification as Sequence-to-Sequence Correction](https://www.aclweb.org/anthology/W16-0528.pdf). In Proceedings of the 11th Workshop on Innovative Use of NLP for Building Educational Applications, pages 242–251, San Diego, California, June 16, 2016.
*  Zhuoran Liu, Yang Liu. 2016. [Exploiting Unlabeled Data for Neural Grammatical Error Detection](https://arxiv.org/pdf/1611.08987.pdf). Journal of Computer Science and Technology, 32(4).
