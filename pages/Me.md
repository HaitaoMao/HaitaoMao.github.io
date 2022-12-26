---
permalink: /me/
title: ME
layout: single
---
来小毛给他整个🔥，草！走！忽略 ጿ ኈ ቼ ዽ ጿ

**Do the significant research that nobody do if I do not!**

I am a first-year Ph.D. student at Michigan State University supervised by Dr. [Jiliang Tang](http://www.cse.msu.edu/~tangjili/index.html). And I received my bachelor degree from the Elite Program, Software Academy at [the University of Electronic Science and Technology of China](https://en.uestc.edu.cn/) in 2022. I have won **the best short paper award in CIKM2021** as the first author.

#### I am a researcher
My research interest is very simple on following two aspective:

- find and solve new practical data mining challanges
- solve the foundamental challenge from optimization perspective.  **A strong perception drives me to believe that many solutions can be attributed to inductive bias in optimization (Forward & Backward).** The algorithm should have the following properties: 
  - Explanable: try to understand the training dynamics of neural network and what inductive biases model tries to induce. 
  - Effective: (1) strong expressive ability power. (2) Introduce inductive bias easily.
  - Efficient: Simple model which the time and memory complexity for the train and inference could be small.
  - Theoretical guarantee: it should be a beautiful theory with its killer application.



For the new practical challenge in data mining, I try my best to propose and solve the industry problem during my internship. My achievements are as follows:

- Unbiased Learning to Rank (found in Baidu)
  - Propose new dataset with new challenges (NeurIPS2022 dataset Track)
  - Host a competition on the Unbiased Learning & pretraining (WSDM CUP 2023)
  - Propose a new scenario: **whole-page Unbiased Learning to Rank** with the first solution (Under review)
- Privacy on Graph (found in Microsoft)
  - Propose a new scenario: **Source Free Unsupervised Graph Domain Adaptation** with the first solution (Under review)
- Finanical Knowledge Graph:  (found in Warton Research Data Services, ongoing project))
  - Propose how to transfer information from 10Q and 10K financial report into A machine-readable Database.
  - Extract the information to conduct Knowledge Graph from he financial report.
- Multiple regional Session Recommendation (with Amazon, ongoing project) 



For solving the foundamental challenge from optimization perspective, I specifically focus on GNN. I always believe that GNN is not suitable for all tasks and may not be well-optimized. But we can gain much insight and understanding from it. For example, GNN can be view as the optimization procedure for some **energy function** with more insights. My achievements are as follows:

- Understand and enhance general DNN optimization
  - Propose an Initialization strategy with Neuron Compaign (**Won the CIKM2021 Best Short Paper**)
  - Propose a regularization term with understanding on how neuron response to different inputs. (NeurIPS 2022)
- Understand and enhance how to learning on graph
  - Understanding GNN as the multiview Learning. (Under review)
  - Understanding GNN as an energy function. 
- Introduce GNN to more people, especially those in AI4science society.
  - Write the GNN and causal discovery part of AI4Science101 documents. [homepage](https://ai4science101.deepmodeling.com/en/latest/index.html)
  - My course: Encouraging Graph Neural Network. [homepage](https://haitaomao.github.io/Encouraging-Graph-Neural-Network/) (Definitely, I will continue to do it. However, it is too too too busy recently. I will restart in the next vacation.)

I also have a big dream on my research. **I believe** that all the techniques for solving the generalization problem, such as contrastive learning, meta-learning, and domain generalization, share some similar assumptions on the data generating process. (I think Matrix Factorization can be a good tool for solving the problem.)


#### I am a life lover
I am a I enjoy my life research and I am certainly a heavy emotional person with sincerity, which is always thankful to those persons in my life through: relatives, teachers, leaders, precious friends. 
My interests lies in singing (really good at it), long-distance running (3000m in 11 mins), playing guitar. I would die if there is one day without music. And I keep running and meditation every to keep health. That indeed helps.

#### I am a lecturer & community builder
From junior high school, I really enjoy teaching other students and doing presentations though I am still not good at it. I am always practice to becomes a good lecturer. Revolving on this goal: 

I start up a new course called [Encouraging Graph Neural Network](https://haitaomao.github.io/Encouraging-Graph-Neural-Network/). (Definitely, I will continue to do it. However, it is too too too busy recently. I will restart in the next vacation.) The course aims to bridge the gap between the brief introduction and the newest advanced semaniar. It provides history on the related works on GNN and more foundation concepts.

I am a host in [MLNLP](https://mp.weixin.qq.com/s/IUjQIVCSKexVKuV_jz5SRg) and [AITIME](http://www.aitime.cn/).
I have hosted talks with more than 15w as follows:
- AITIME PhD debate about theory in Deep Learning. [video](https://www.bilibili.com/video/BV1pe4y1U7Pc/?vd_source=85bb42770c1036d2fc85b057595f1054) (more than 24,000 views)
- AITIME PhD debate about the low-level vision.[video](https://www.bilibili.com/video/BV1aP4y1f7mG?vd_source=85bb42770c1036d2fc85b057595f1054) (more than 17,000 view)
- AITIME PhD debate about the backdoor attack in deep learning. [video](https://www.bilibili.com/video/BV1qT411g7Cq?spm_id_from=333.999.0.0&vd_source=85bb42770c1036d2fc85b057595f1054). (more than 24,000 view)
- The 9th seminar of MLNLP community. [[video]](https://www.bilibili.com/video/BV1wB4y1r7fa?spm_id_from=333.337.search-card.all.click)
- "AI2000: AI young scientist", [[video]](https://www.bilibili.com/video/BV1x94y1d7nL?spm_id_from=333.1007.top_right_bar_window_dynamic.content.click) (more than 90,000 view)




### Selected publication
<ul>
    <li>
      <p>
        <strong> Neuron Campaign for Initialization Guided by Information Bottleneck Theory </strong><br>
        <strong>CIKM2021 Best Short Paper</strong><br>
        <strong>Haitao Mao*</strong>, Lun Du*, Qiang Fu*, Xu Chen*,   Shi Han, Dongmei Zhang <br>
        [<a href="https://arxiv.org/pdf/2108.06530.pdf">pdf</a>]
        [<a href="https://github.com/HaitaoMao/Neuron-Campaign-for-Initialization-Guided-by-Information-Bottleneck-Theory">github</a>]
        [<a href="https://haitaomao.github.io/categories/neuronCampaign/">blog</a>]
        [<a href="https://zhuanlan.zhihu.com/p/398198523">Chinese blog</a>]
        [<a href="https://github.com/haitaomao/haitaomao.github.io/blob/master/_files/CIKM2021/Init_poster.pdf">Offical Poster</a>]
        [<a href="https://github.com/haitaomao/haitaomao.github.io/blob/master/_files/CIKM2021/CIKM21_Neuron_Campaign_for_Initialization_Guided_by_Information_Bottleneck_Theory.pdf">Offical Slides</a>]
        [<a href="https://github.com/haitaomao/haitaomao.github.io/blob/master/_files/CIKM2021/Init_video.mp4">Offical Video</a>]
        [<a href="https://mp.weixin.qq.com/s/PEt7m_iadPGm9puO0S0nHw">AI TIME Introduction </a>]
        [<a href="https://github.com/haitaomao/haitaomao.github.io/blob/master/_files/CIKM2021/AITime%20CIKM21%20-%20Neuron%20Campaign.pdf">AI TIME presentation Slides</a>]
        [<a href="https://www.bilibili.com/video/BV1fL411V7FP?spm_id_from=333.1007.top_right_bar_window_history.content.click">AI TIME Presentation Video</a>]
        [<a href="https://mp.weixin.qq.com/s/V0pwLwTR-rVpe8h5NL_u3g">AI TIME Report</a>] <br><br>
        I love this work become the idea is easy and interesting and provide a new perspective, the inspiration comes from the Lottery Ticket theory and Information Bottleneck theory. <br>
        See our follow up job accept by NeurIPS2022: Neuron with Steady Response Leads to Better Generalization.
      </p>
    </li>
    <li>
      <p> 
      <strong> A Large Scale Search Dataset for Unbiased Learning to Rank </strong> <br>
      <strong>Haitao Mao*</strong>, Lixin Zou*, Xiaokai Chu, Jiliang Tang, Shuaiqiang Wang, Wenwen ye, Dawei yin. <br>

      [<a href="https://openreview.net/pdf?id=EZcHYuU_9E">pdf</a>]
      [<a href="https://github.com/ChuXiaokai/baidu_ultr_dataset">Code1</a>]
      [<a href="https://github.com/ChuXiaokai/WSDMCUP_BaiduPLM_Paddle">Code2</a>]
      [<a href="https://haitaomao.github.io/baidu_ultr_page/">Dataset Homepage1</a>]<br>
      [<a href="https://searchscience.baidu.com/dataset.html">Dataset Homepage2</a>]<br>
      [<a href="https://www.bilibili.com/video/BV1ZP411N75k/?spm_id_from=333.999.0.0">video</a>]
      <br><br>
    
      I love this work for it opens great opportunity in ULTR domain, a very practical but less study domain.  It open multiple new directions in ULTR: pretrain, multi-task learning, user behavir analysis, causal discovery, long tail analysis. It is 20 times bigger than the existing ULTR datasets. <br>
      We are holding WSDM CUP with this dataset now!      
      </p>
    
    </li>
</ul>


### Service
- WWW 2023
- ICML 2022, 2023
- NeurIPS 2022 (main conference & [TGL workshop](https://sites.google.com/view/tglworkshop2022/home))
- KDD 2022
- CIKM 2022
- LOG 2022
- WSDM 2023
- AAAI 2023


### Familiar Research Interests
- Knowledge Graph Construction(NER, Document-level relation extraction)
- Knowledge Graph Completion
- Session Recommendation System
- Click-Through Rate (CTR)


### Talks
- Renmin University: Understanding and improving Deep Neural Network from neuron-level perspective [slides]()
- AITIME: WSDM CUP2023-Unbiased learning & Pre-training for Web Search (More than 18000 views) [video]("https://www.bilibili.com/video/BV1ZP411N75k/?spm_id_from=333.999.0.0")[slides]()
- AITIME: Neuron With steady response leads to better generalization [video]()[slides]()
- AITIME & Rising star reading group: Neuron Campaign Guided by Information Bottleneck Theory [video]("https://www.bilibili.com/video/BV1fL411V7FP?spm_id_from=333.1007.top_right_bar_window_history.content.click").[slides]()
- Mircosoft Research Asia: An introduction to Domain Adaptation towards privacy protection.[slides]()



### Internship

**Microsoft Research Asia (January, 2021 - November, 2021)**

I am the first post-2000s generation research intern in the [Data Knowledge Intelligent Group](https://www.microsoft.com/en-us/research/group/data-knowledge-intelligence/) (Used to be called Software Analysis Group) leaded by [Dongmei Zhang]([Dongmei Zhang at Microsoft Research](https://www.microsoft.com/en-us/research/people/dongmeiz/)). Fortunately I was guided by Principal Researcher [Qiang Fu](https://scholar.google.com/citations?hl=en&user=bwTLZSIAAAAJ), Researcher [Lun Du](https://scholar.google.com/citations?user=3XUANDAAAAAJ&hl=en&oi=ao), and Senior Principal Researcher Manager [Shi Han](https://www.microsoft.com/en-us/research/people/shihan/). And my research topic in MSRA are: initialization strategy, regularization method, Unsupervised Domain Adaptation on Graph with three paper published. 

My achievement in MSRA are:

- Get the star of tomorrow award (top 10% intern)
- Get the CIKM2021 best short paper award as the first author.
- One paper about regularization term accepted by Neurips2022 as the co-first author and first student author.
- Participate in the KDD CUP2021 to handle large-scale graph and get the rank of 23th
- Co-founded MS-Intern Guitar Club with Jianan Zhao.
  

**Baidu (March, 2022 - September, 2022)**

I am a research intern in search strategy department in Baidu supervised by [Lixin Zou](https://www.zoulixin.site/). Now my research topic in Baidu is Unbiased Learning To Rank. I am still focusing on the unifed view on Graph Neural Network.
If as expected, my achievements in Baidu are:

- One dataset paper accepte by NeurIPS 2020 dataset track on Unbiased Learning to rank problem. It provides new practical challenges on this task.
- Host the WSDM CUP on the above dataset.
- One full paper for causal disocvery on unbiased learning to rank problem (baseline for the above dataset).


### Education
**Michigan State University (August 2022 - present)**

I am a Ph.D. candidate in DSE lab at Michigan State University, supervised by [Jiliang Tang](http://www.cse.msu.edu/~tangjili/index.html). 

**University of Electronic Science and Technology of China  (September 2018 - June 2022)**

I major in software engineering and fortunately selected as a member of the Elite program (the international class)

My achievements in UESTC are:

- Two reports on the official website of UESTC and a report on Xinhua website
  - [因为热爱所以拼搏，全奖直博的他，成电四年很精彩！](https://mp.weixin.qq.com/s/CMcPWZ1YTafE8CUQcA619Q) 
  - [软件学院本科生在数据挖掘领域顶级会议CIKM上发表论文并获最佳短文奖](https://news.uestc.edu.cn/?n=UestcNews.Front.DocumentV2.ArticlePage&Id=81841)
- Won the Sichuan Provincial Outstanding Graduate title.
- The **first place** in-class performance (1/58) with an average score of 91.29 and a GPA of 3.97.
- Won the **national first prize** in China Software Cup (20/45000). [[Github](https://github.com/xiaobao520123/EnterpriseNavigator)]
- Won the **A+** performance (4/40) on the summer camp of the **Nation University of Singapore, School of computing**. 
- Won the best project award and the best performance (3/57) on the summer camp of **Nanjing University, NLP lab**.
- Worked as a research assistant in the artificial Intelligence and System Laboratory for about one year.
- One software copyright



### Support
This page is supported by [Hanlin Lan](https://runtus.top), one of my best friends in undergraduate period. Thanks for his great help.