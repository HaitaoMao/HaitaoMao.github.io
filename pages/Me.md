---
permalink: /me/
title: ME
layout: single
---

I am a final-year Ph.D. student at Michigan State University supervised by Dr. [Jiliang Tang](http://www.cse.msu.edu/~tangjili/index.html). I also collaborate with [Neil Shah](http://nshah.net/), [Yao Ma](https://yaoma24.github.io/), [Michael Galkin](https://migalkin.github.io/), and [Rongrong Wang](https://users.math.msu.edu/users/wangron6/). Each of them provides a unique perspective on scientific thinking throughout my research journey. During those years, I open up a new direction, Graph Foundation Model (GFM) in our group. More details can be found on the [DSE GFM subgroup](https://dse-gfm.github.io/). It has been a pleasure working with these talented guys. 

I am an organizer of the [Learning on Graph Conference 2024](https://logconference.org/)an exciting new conference focused on graph and geometry. The call for paper is available [here](https://logconference.org/cfp/), with a submission deadline of September 11th, 2024. Do not hesitate to submit your work!

My research focuses on (1) developing Graph Foundation Models (GFMs) with scaling behavior (clever leveraging graph principles such as network analysis and expressiveness) and (2) understanding the mechanisms of Large Language Models (LLMs). During my research road, I answer the following research questions:

**Developing Graph Foundation Models (GFMs)**
<details>
<summary style="font-size: 15px;">Details</summary>
  <ul type='disc'> 
   <li> Is there a universal structure space among graphs from different domains? </li>
   <li> What is the killer application for GFMs? </li>
   <li> How can we build GFMs? A good vocabulary design with a transformer could be a viable solution </li>
   <li> Are there any shared principles across graphs despite their apparent diversity? What are the underlying latent factors underlying the graphs we observed? Currently, I believe in three perspectives: (1) Geometric perspective: Useful when the graph is strictly constructed following principles. (2) Network analysis perspective: Identifying frequent motifs among graphs. (3) LLM perspective: I am still invesigating the superpower of this black box. </li>
   <li> How can we apply GFMs on an industry-level large graphs, balancing effectiveness and efficiency? (A hashing map vocabulary can be a good solution).</li>
   <li> As we approach GFMs with much stronger capabilities, many previous graph problems may become obsolete. What are the new critical questions in the GFM era? For instance, the privacy issue. </li>
  </ul>
</details>

<br>

**Understanding the Mechanisms of Large Language Models (LLMs)**   
<details> 
<summary style="font-size: 15px;">Details</summary>
  <ul type='disc'> 
    <li> LLMs exhibit many emerging capabilities after specific fine-tuning, such as instruction following, yet this fine-tuning only requires minor modifications to the original weights. How can new capabilities emerge with only minor modifications?</li>
    <li> One of the most remarkable capabilities of LLMs is in-context learning, which allows learning from contextual information without requiring gradient updates. How do LLMs learn new knowledge or activate particular subnetworks with contextual information? I am particularly interested in self-correction and moral reasoning capabilities.</li>
    <li> The neural network is a complex black-box system. How can we understand it? Is there any interesting generalization behavior for each individual neuron? How can we improve each individual neuron toward better generalization? I believe in the "competing subnetworks" concept, where the model initially represents a variety of distinct algorithms, corresponding to different subnetworks, and generalization occurs when it ultimately converges into one. However, this may not work for large-scale LLMs.</li>
  </ul>
</details>



### Selected publications
The order indicates my personal preference. 
<ul>
  <li>
      <p>
          <strong>Position: Graph Foundation Models Are Already Here</strong><br>
          <strong>Haitao Mao</strong>*, <u>Zhikai Chen</u>*, <u>Wenzhuo Tang</u>, Jianan Zhao, Yao Ma, Tong Zhao, Neil Shah, Mikhail Galkin, Jiliang Tang <br>
          <strong>ICML 2024 <font color="red">Spotlight (335/9473) </font>  </strong><br> 
          <font color="green">Collaboration with SnapChat and Intel lab</font> <br>
          [<a href="https://arxiv.org/pdf/2402.02216.pdf">pdf</a>]
          [<a href="https://medium.com/@jeongiitae/graph-foundation-models-8cca5d31ddb9">Blog</a>]  
          [<a href="https://github.com/CurryTang/Towards-Graph-Foundation-Models-New-perspective-">Reading List 1</a>]
          [<a href="https://github.com/CurryTang/Towards-graph-foundation-models">Reading List 2</a>]
      </p>
    </li>
    <li>
      <p>
        <strong>On the Intrinsic Self-Correction Capability of LLMs: Uncertainty and Latent Concept </strong> <br>
        <strong>Haitao Mao*</strong>, Guangliang Liu*, Bochuan Cao, Zhiyu Xue, Kristen Johnson, Jiliang Tang, Rongrong Wang<br>
        Preprint [<a href="https://arxiv.org/pdf/2406.02378">pdf</a>]
      </p>
    </li>
    <li>
        <p>
            <strong>Revisiting Link Prediction: A Data Perspective</strong><br>
            <strong>Haitao Mao</strong>, <u>Juanhui Li</u>, Harry Shomer, Bingheng Li, Wenqi Fan, Yao Ma, Tong Zhao, Neil Shah, Jiliang Tang <br>
            <strong>ICLR 2024</strong><br>
            <font color="green">Collaboration with SnapChat</font> <br>
            [<a href="https://arxiv.org/pdf/2310.00793.pdf">pdf</a>]
            [<a href="https://github.com/HaitaoMao/HaitaoMao.github.io/blob/master/_files/LinkPrediction.pdf">Slides</a>] 
            [<a href="https://www.bilibili.com/video/BV1jj411s7h5/?spm_id_from=333.999.0.0&vd_source=85bb42770c1036d2fc85b057595f1054">Video</a>]
        </p>
    </li>
    <li>
        <p>
            <strong>Cross-Domain Graph Data Scaling: A Showcase with Diffusion Models</strong><br>
            <u>Wenzhuo Tang</u>, <strong>Haitao Mao</strong>, Danial Dervovic, Ivan Brugere, Saumitra Mishra, Yuying Xie, Jiliang Tang<br>
            <font color="green">Collaboration with JP Morgan</font> <br>
            Preprint [<a href="https://arxiv.org/pdf/2406.01899">pdf</a>]
        </p>
    </li>
    <li>
      <p>
          <strong>Demystifying Structural Disparity in Graph Neural Networks: Can One Size Fit All?</strong><br>
          <strong>Haitao Mao</strong>, <u>Zhikai Chen</u>, Wei Jin, Haoyu Han, Yao Ma, Tong Zhao, Neil Shah, Jiliang Tang <br>
          <strong>NeurIPS 2023</strong> <br>
          <font color="green">Collaboration with SnapChat</font> <br>
          [<a href="https://arxiv.org/abs/2306.01323.pdf">pdf</a>]
          [<a href="https://github.com/HaitaoMao/Demystify-structural-disparity">Code</a>] 
          [<a href="https://github.com/HaitaoMao/HaitaoMao.github.io/blob/master/_files/NodeClassification.pdf">Slides</a>] 
          [<a href="https://github.com/HaitaoMao/HaitaoMao.github.io/blob/master/_files/Demestify-poster.pdf">Poster</a>]
          [<a href="https://www.bilibili.com/video/BV1jj411s7h5/?spm_id_from=333.999.0.0&vd_source=85bb42770c1036d2fc85b057595f1054">Video</a>]
      </p>
    </li>
    <li>
      <p>
        <strong> Neuron Campaign for Initialization Guided by Information Bottleneck Theory </strong><br>
        <strong>Haitao Mao</strong>, Xu Chen, Qiang Fu, Lun Du, Shi Han, Dongmei Zhang <br>
        <font color="red"><strong>CIKM2021 Best Short Paper (1/626)</strong></font><br>
        <font color="green">Work During Internship in Microsoft Research Asia</font> <br>
        [<a href="https://arxiv.org/pdf/2108.06530.pdf">pdf</a>]
        [<a href="https://github.com/HaitaoMao/Neuron-Campaign-for-Initialization-Guided-by-Information-Bottleneck-Theory">Code</a>]
        [<a href="https://haitaomao.github.io/categories/neuronCampaign/">Blog</a>]
        [<a href="https://zhuanlan.zhihu.com/p/398198523">Chinese Blog</a>]
        [<a href="https://github.com/haitaomao/haitaomao.github.io/blob/master/_files/CIKM2021/Init_poster.pdf">Poster</a>]
        [<a href="https://github.com/haitaomao/haitaomao.github.io/blob/master/_files/CIKM2021/AITime%20CIKM21%20-%20Neuron%20Campaign.pdf">Slides</a>]
        [<a href="https://www.bilibili.com/video/BV1fL411V7FP?spm_id_from=333.1007.top_right_bar_window_history.content.click">Video</a>] 
      </p>
    </li>
    <li>
        <p>
            <strong>Text-space Graph Foundation Models: A Comprehensive Benchmark and New Insights</strong><br>
            <u>Zhikai Chen</u>, <strong>Haitao Mao</strong>, Jingzhe Liu, Yu Song, Bingheng Li, Wei Jin, Bahare Fatemi, Anton Tsitsulin, Bryan Perozzi, Hui Liu, Jiliang Tang <br>
            <font color="green">Collaboration with Google</font> <br>
            Preprint [<a href="">pdf</a>][<a href="https://github.com/CurryTang/TSGFM">Code</a>] 
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
          <font color="green">Collaboration with Baidu</font> <br>
          [<a href="https://arxiv.org/pdf/2307.03393.pdf">pdf</a>]
          [<a href="https://github.com/CurryTang/Graph-LLM">Code</a>]
          [<a href="https://www.cse.msu.edu/~tangjili/talks/LLMs-LOG.pdf">Slides</a>]
        </p>
    </li>
    <li>
      <p>
          <strong>Source Free Graph Unsupervised Domain Adaptation </strong><br>
          <strong>Haitao Mao</strong>, Lun Du, Yujia Zheng, Qiang Fu, Zelin Li, Xu Chen, Shi Han, Dongmei Zhang <br>
          <strong><font color="red">WSDM 2024 Best Paper Honor Mention (3/615)</font></strong> <br>
          <font color="green">Work During Internship in Microsoft Research Asia</font> <br>
          [<a href="https://arxiv.org/pdf/2112.00955.pdf">pdf</a>]
          [<a href="https://haitaomao.github.io/categories/sourcefree/">Blog</a>]
          [<a href="https://github.com/HaitaoMao/SOGA">Code</a>]
      </p>  
    </li>
</ul>

### Awards:
- WSDM2024 Best Paper Honor Mentioned Award (First Author) (3/615)
- CIKM2021 Best Short Paper Award (First Author) (1/626)
- ICML 2024 Spotlight (First Author) (335/9473)
- NSF Student Travel Grant - WSDM 2024
- NeurIPS 2023 Scholar Award
- Excellent Student of High Education in Sichuan Province (30/763)
- Outstanding Graduate in University of Electronic Science and Technology of China (74/763)
- Star of Tomorrow Intern Award in Microsoft Research Asia (Top 10%)
- National First Prize in Chinese Software Cup(20/45,000) [[Github](https://github.com/xiaobao520123/EnterpriseNavigator)]



### Professional Experience

- **Visiting Scholar at Hong Kong Polytechnic University (March, 2023 - September 2023)**: Mentored by Research Assistant Professor [Wenqi Fan](https://wenqifan03.github.io/) and Professor [Qing Li](https://www4.comp.polyu.edu.hk/~csqli/)
- **Research Intern at Baidu (March, 2022 - September, 2022)**: Search Strategy Department, Mentored by Dr. [Lixin Zou](https://www.zoulixin.site/).
- **Research intern at Microsoft Research Asia (January, 2021 - November, 2021)**
  -  [Data Knowledge Intelligent Group](https://www.microsoft.com/en-us/research/group/data-knowledge-intelligence/), Mentored by Principal Researcher [Qiang Fu](https://scholar.google.com/citations?hl=en&user=bwTLZSIAAAAJ), Researcher [Lun Du](https://scholar.google.com/citations?user=3XUANDAAAAAJ&hl=en&oi=ao), and Senior Principal Researcher Manager [Shi Han](https://www.microsoft.com/en-us/research/people/shihan/). 
  - One [news](https://mp.weixin.qq.com/s/9wREeVH-o1TZ6Y-zcxXxXQ) about my research.
  - Co-founded MS-Intern Guitar Club.


### Education

**Michigan State University (August 2022 - present)**

**University of Electronic Science and Technology of China  (September 2018 - June 2022)**

- Major in Elite program, software engineering 
- **Rank First** in Academic Performance : (1) Average Score: 91.29 (1/58) (2) Comprehensive Score: 96.79 (1/58) (3)GPA: 3.97
- Two Reports on the Official Website of UESTC and A Report on Xinhua Website
  - [因为热爱所以拼搏，全奖直博的他，成电四年很精彩！](https://mp.weixin.qq.com/s/CMcPWZ1YTafE8CUQcA619Q) 
  - [软件学院本科生在数据挖掘领域顶级会议CIKM上发表论文并获最佳短文奖](https://news.uestc.edu.cn/?n=UestcNews.Front.DocumentV2.ArticlePage&Id=81841)




### Support

This page is supported by [Hanlin Lan](https://runtus.top), one of my best friends in undergraduate period. Thanks for his great help.