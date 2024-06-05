---
permalink: /me/
title: ME
layout: single
---

> 沧浪之江，西来水泱泱，江上一轮明月，照多少沉浮过往。
> 沧浪之江，东往水莽莽，谁赏江上明月，谁听江声浩荡
> The vast river of Canglang, with its waters flowing grandly from the west, Under the moonlight above the river, illuminating countless ups and downs of the past.
> The vast river of Canglang, with its waters surging endlessly to the east, Who gazes at the moon above the river, who listens to the majestic roar of the river?


I am a second-year Ph.D. student at Michigan State University supervised by Dr. [Jiliang Tang](http://www.cse.msu.edu/~tangjili/index.html). I am also working with [Neil Shah](http://nshah.net/), [Yao Ma](https://yaoma24.github.io/), [Michael Galkin](https://migalkin.github.io/), and [Rongrong Wang](https://users.math.msu.edu/users/wangron6/). Each of them provide unique perspective on how to do scientific thinking during my research road. In those years, I opens up the new direction, Graph Foundation Model in our group. See details in [DSE GFM subgroup](https://dse-gfm.github.io/). I am super happy to work with those talented guys. 

I am the organizer of [Learning on Graph Conference 2024](https://logconference.org/). It is an encouraging new conference for graph and geometry. The call for paper can be found [here](https://logconference.org/cfp/). Do not hesitate to submit your work before September 11th, 2024! 

My research revolves on understanding **network** and **LLM** mechanisms from **a data generation perspective**. I enjoy doing research on understanding some interesting phenomenons, finding pitfalls in existing literature, and defining some interesting new challenges. I am skilled in (1) conducting curious analytical experiments to observe interesting behaviors and (2) defining an interesting research perspective (but may not be practical). During my research road, I answer the following research questions:

**Network mechanism & new data mining challenges**
<details>
<summary style="font-size: 15px;">Details</summary>
  <ul type='disc'> 
   <li> How can we build graph foundation models and what is the killer application for it?</li>
   <li> The graph data can be diverse, how can one GNN perform well across graphs from different domains? It seemly obeying the Occam's razor I believe in. </li>
   <li> Despite the graph data being seemingly diverse, are there any shared principles across certain graphs? What are the underlying latent factors underlying the graph we observed? In the current stage, I typically believe in three perspectives: (1) geometric perspective which can help when the graph is strictly constructed following principles (2) network analysis perspective: find the frequent motifs among graphs. (3) LLM perspective: I am not sure what the superpower of this black box. </li>
   <li> How can we apply graph techniques on an industry-level large graph with a trade-off between effectiveness and efficiency?</li>
   <li> Is there any additional gain from graph structure after utilizing the LLM to encode textural node features? </li>
   <li> How to define a more practical ranking and recommendation scenario in academics and build suitable system accordingly?</li> 
  </ul>
</details>

<br>

**LLM mechanism analysis**   
<details> 
<summary style="font-size: 15px;">Details</summary>
  <ul type='disc'> 
    <li> The Neuron Network is a complicated black-box system, how can we understand it? Is there any interesting generalization behavior for each individual neuron? How can we improve each individual neuron toward better generalization? I typically believe in the “competing subnetworks” concept: the model initially represents a variety of distinct algorithms, corresponding to different subnetworks, and generalization occurs when it ultimately converges into one. However, I think this may not work for large-scale LLM</li>
    <li> LLMs show many emerging capabilities after specific fine-tuning, e.g., instruction following, however, the fine-tuning only requires minor modification on the original weights. How can the new capability come out with only minor modifications?</li>
    <li> The most amazing LLM capability is the in-context learning capability which can learn from contextual information requiring no gradient update. How does the LLM learn new knowledge or activate the particular subnetwork with contextual information? I am specifically interested in self-correction and moral reasoning capability.</li>
  </ul>
</details>

### Selected publications
The order indicates my personal preference. 
<ul>
  <li>
      <p>
          <strong>Position: Graph Foundation Models are Already Here</strong><br>
          <strong>Haitao Mao</strong>*, <u>Zhikai Chen</u>*, <u>Wenzhuo Tang</u>, Jianan Zhao, Yao Ma, Tong Zhao, Neil Shah, Mikhail Galkin, Jiliang Tang <br>
          <strong>ICML 2024</strong><br> 
          <font color="green">collaboration with SnapChat and Intel lab</font> <br>
          [<a href="https://arxiv.org/pdf/2402.02216.pdf">pdf</a>]
          [<a href="https://medium.com/@jeongiitae/graph-foundation-models-8cca5d31ddb9">blog</a>]  
          [<a href="https://github.com/CurryTang/Towards-Graph-Foundation-Models-New-perspective-">reading List 1</a>]
          [<a href="https://github.com/CurryTang/Towards-graph-foundation-models">reading List 2</a>]
      </p>
    </li>
    <li>
      <p>
        <strong>On the Intrinsic Self-Correction Capability of LLMs: Uncertainty and Latent Concept </strong> <br>
        <strong>Haitao Mao*</strong>, Guangliang Liu*, Bochuan Cao, Zhiyu Xue, Kristen Johnson, Jiliang Tang, Rongrong Wang<br>
        preprint [<a href="https://arxiv.org/pdf/2406.02378">pdf</a>]
      </p>
    </li>
    <li>
        <p>
            <strong>Revisiting Link Prediction: A data perspective</strong><br>
            <strong>Haitao Mao</strong>, <u>Juanhui Li</u>, Harry Shomer, Bingheng Li, Wenqi Fan, Yao Ma, Tong Zhao, Neil Shah, Jiliang Tang <br>
            <strong>ICLR 2024</strong><br>
            <font color="green">collaboration with SnapChat</font> <br>
            [<a href="https://arxiv.org/pdf/2310.00793.pdf">pdf</a>]
            [<a href="https://github.com/HaitaoMao/HaitaoMao.github.io/blob/master/_files/LinkPrediction.pdf">slides</a>] 
            [<a href="https://www.bilibili.com/video/BV1jj411s7h5/?spm_id_from=333.999.0.0&vd_source=85bb42770c1036d2fc85b057595f1054">video</a>]
        </p>
    </li>
    <li>
        <p>
            <strong>Cross-Domain Graph Data Scaling: A Showcase with Diffusion Models</strong><br>
            <u>Wenzhuo Tang</u>, <strong>Haitao Mao</strong>, Danial Dervovic, Ivan Brugere, Saumitra Mishra, Yuying Xie, Jiliang Tang<br>
            <font color="green">collaboration with JP Morgan</font> <br>
            preprint [<a href="">pdf</a>]
        </p>
    </li>
    <li>
      <p>
          <strong>Demystifying Structural Disparity in Graph Neural Networks: Can One Size Fit All?</strong><br>
          <strong>Haitao Mao</strong>, <u>Zhikai Chen</u>, Wei Jin, Haoyu Han, Yao Ma, Tong Zhao, Neil Shah, Jiliang Tang <br>
          <strong>NeurIPS 2023</strong> <br>
          <font color="green">collaboration with SnapChat</font> <br>
          [<a href="https://arxiv.org/abs/2306.01323.pdf">pdf</a>]
          [<a href="https://github.com/HaitaoMao/Demystify-structural-disparity">code</a>] 
          [<a href="https://github.com/HaitaoMao/HaitaoMao.github.io/blob/master/_files/NodeClassification.pdf">slides</a>] 
          [<a href="https://github.com/HaitaoMao/HaitaoMao.github.io/blob/master/_files/Demestify-poster.pdf">poster</a>]
          [<a href="https://www.bilibili.com/video/BV1jj411s7h5/?spm_id_from=333.999.0.0&vd_source=85bb42770c1036d2fc85b057595f1054">video</a>]
      </p>
    </li>
    <li>
      <p>
        <strong> Neuron Campaign for Initialization Guided by Information Bottleneck Theory </strong><br>
        <strong>Haitao Mao</strong>, Xu Chen, Qiang Fu, Lun Du, Shi Han, Dongmei Zhang <br>
        <font color="red"><strong>CIKM2021 Best Short Paper</strong></font><br>
        <font color="green">Work during internship in Microsoft Research Asia</font> <br>
        [<a href="https://arxiv.org/pdf/2108.06530.pdf">pdf</a>]
        [<a href="https://github.com/HaitaoMao/Neuron-Campaign-for-Initialization-Guided-by-Information-Bottleneck-Theory">code</a>]
        [<a href="https://haitaomao.github.io/categories/neuronCampaign/">blog</a>]
        [<a href="https://zhuanlan.zhihu.com/p/398198523">Chinese blog</a>]
        [<a href="https://github.com/haitaomao/haitaomao.github.io/blob/master/_files/CIKM2021/Init_poster.pdf">Poster</a>]
        [<a href="https://github.com/haitaomao/haitaomao.github.io/blob/master/_files/CIKM2021/AITime%20CIKM21%20-%20Neuron%20Campaign.pdf">Slides</a>]
        [<a href="https://www.bilibili.com/video/BV1fL411V7FP?spm_id_from=333.1007.top_right_bar_window_history.content.click">Video</a>] 
      </p>
    </li>
    <li>
        <p>
            <strong>Text-space graph foundation models: a comprehensive benchmark and new insights</strong><br>
            <u>Zhikai Chen</u>, <strong>Haitao Mao</strong>, Jingzhe Liu, Yu Song, Bingheng Li, Wei Jin, Bahare Fatemi, Anton Tsitsulin, Bryan Perozzi, Hui Liu, Jiliang Tang <br>
            <font color="green">collaboration with Google</font> <br>
            preprint [<a href="">pdf</a>]
        </p>
    </li>
    <li>
      <p>
          <strong>A Data Generation Perspective to the Mechanism of In-Context Learning</strong><br>
          <strong>Haitao Mao</strong>, Guangliang Liu, Yao Ma, Rongrong Wang, Jiliang Tang <br>
          Preprint [<a href="https://arxiv.org/pdf/2402.02212.pdf">pdf</a>]
      </p>
    </li>
    <li>
        <p>
          <strong> Exploring the Potential of Large Language Models (LLMs) in Learning on Graphs </strong><br>
          <u>Zhikai Chen</u>, <strong>Haitao Mao</strong>, Hang Li, Wei Jin, Hongzhi Wen, Xiaochi Wei, Shuaiqiang Wang, Dawei Yin, Wenqi Fan, Hui Liu, Jiliang Tang <br>
          <strong>SIGKDD Explorations 2023</strong> <br>
          <font color="green">collaboration with Baidu</font> <br>
          [<a href="https://arxiv.org/pdf/2307.03393.pdf">pdf</a>]
          [<a href="https://github.com/CurryTang/Graph-LLM">code</a>]
          [<a href="https://www.cse.msu.edu/~tangjili/talks/LLMs-LOG.pdf">slides</a>]
        </p>
    </li>
    <li>
      <p>
          <strong>Source Free Graph Unsupervised Domain Adaptation </strong><br>
          <strong>Haitao Mao</strong>, Lun Du, Yujia Zheng, Qiang Fu, Zelin Li, Xu Chen, Shi Han, Dongmei Zhang <br>
          <strong><font color="red">WSDM 2024 Best Paper Honor Mention</font></strong> <br>
          <font color="green">Work during internship in Microsoft Research Asia</font> <br>
          [<a href="https://arxiv.org/pdf/2112.00955.pdf">pdf</a>]
          [<a href="https://haitaomao.github.io/categories/sourcefree/">blog</a>]
          [<a href="https://github.com/HaitaoMao/SOGA">code</a>]
      </p>  
    </li>
</ul>

### Awards:
- WSDM2024 Best Paper Honor Mentioned award (first author) (3/615)
- CIKM2021 Best short paper award (first author) (1/626)
- NSF Student Travel Grant - WSDM 2024
- NeurIPS 2023 Scholar Award
- Excellent Student of High Education in Sichuan Province (30/763)
- Outstanding Graduate in University of Electronic Science and Technology of China (74/763)
- Star of tomorrow intern award in Microsoft Research Asia (top 10%)
- National first prize in Chinese Software (20/45,000) [[Github](https://github.com/xiaobao520123/EnterpriseNavigator)]
- Best project and best performance award in **Nanjing University, NLP lab**. (3/57)
- **A+** performance (4/40) on the summer camp of the **Nation University of Singapore, School of computing**. 



### Professional Experience

- **Visiting scholar at Hong Kong Polytechnic University (March, 2023 - September 2023)**: supervised by Research Assistant Professor [Wenqi Fan](https://wenqifan03.github.io/) and Professor [Qing Li](https://www4.comp.polyu.edu.hk/~csqli/)
- **Research Intern at Baidu (March, 2022 - September, 2022)**: Search strategy department, supervised by [Lixin Zou](https://www.zoulixin.site/)(Now an associate professor in Wuhan University).
- **Research intern at Microsoft Research Asia (January, 2021 - November, 2021)**
  -  [Data Knowledge Intelligent Group](https://www.microsoft.com/en-us/research/group/data-knowledge-intelligence/), supervised by Principal Researcher [Qiang Fu](https://scholar.google.com/citations?hl=en&user=bwTLZSIAAAAJ), Researcher [Lun Du](https://scholar.google.com/citations?user=3XUANDAAAAAJ&hl=en&oi=ao), and Senior Principal Researcher Manager [Shi Han](https://www.microsoft.com/en-us/research/people/shihan/). 
  - One [news](https://mp.weixin.qq.com/s/9wREeVH-o1TZ6Y-zcxXxXQ) about my research.
  - Co-founded MS-Intern Guitar Club.


### Education

**Michigan State University (August 2022 - present)**

**University of Electronic Science and Technology of China  (September 2018 - June 2022)**

- Major in Elite program, software engineering 
- **Rank first** in academic performance : (1) average score: 91.29 (1/58) (2) Comprehensive score: 96.79 (1/58) (3)GPA: 3.97
- Two reports on the official website of UESTC and a report on Xinhua website
  - [因为热爱所以拼搏，全奖直博的他，成电四年很精彩！](https://mp.weixin.qq.com/s/CMcPWZ1YTafE8CUQcA619Q) 
  - [软件学院本科生在数据挖掘领域顶级会议CIKM上发表论文并获最佳短文奖](https://news.uestc.edu.cn/?n=UestcNews.Front.DocumentV2.ArticlePage&Id=81841)




### Support

This page is supported by [Hanlin Lan](https://runtus.top), one of my best friends in undergraduate period. Thanks for his great help.