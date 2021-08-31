# Welcome to WW's home page.
```markdown

```

<table border="0">
  <tr>
    <td width="75%">
      <h1>WeiWei</h1>
      <p><b>BEng in Computer Science & Technology</b></p>
      <p><b>South China University of Technology (SCUT)</b></p>
      <p><b>Email：csweiw@mail.scut.edu.cn</b></p>   
      <p><b>Phone number：csweiw@mail.scut.edu.cn</b></p>
      <!--<p><b>Address：Dongguan Zhuang Road, TianHe District, Guangzhou, 510630, Guangdong Province, China</b></p>-->
    </td>
    <td width="25%">
      <img src="/Pictures/WW.jpg" width="100%">      
    </td>
  </tr>
</table>




### EDUCATION
*****
+ BEng in __Computer Science & Technology__, GPA: __3.83/4.0__                                                 Sept. 2017-June 2021                          
                                                                                                               <p align="right">Sept. 2017-June 2021</p>
+ Relevant Coursework:
```markdown

Data Structures, Digital Logic, Design and Analysis of Algorithm, Database System,
Computer Organization & Architecture, Principle of Compiler, 
Neural Networks and Deep Learning, Java Programming, 

Advanced Language Program Design(C++)
Mathematics Analysis(Calculus Mainly), Discrete Mathematics, Linear Algebra & Analytic Geometry, Numerical Methods, Computer Network, Embedded System, 
Data Warehouse and Data Mining, The Method of Mathematical Modeling
```
+ Scholarships: Second-class Scholarship of SCUT (2017-18), Third-class Scholarship of SCUT (2019)

### RESEARCH INTERESTS
*****
+ Graph Neural Network
+ Recommender System
+ Self-Supervised Learning
+ Transfer Learning
+ Meta Learning
+ Computer Vision

### PUBLICATIONS
*****

+ Contrastive Meta Learning with Behavior Multiplicity for Recommendation. (WSDM2022 Submit. Primary author.) [Abstract, model diagram and part of experimental results](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)
+ Multi-channel Relation Modeling for Session-based Recommendation with Self-supervised.The 3rd International Conference on Computing and Data Science (CONF-CDS). August 14, 2021. Stanford, San Francisco, US.https://www.confcds.org.(CONF-CDS2021. Accept. Independent author.) [Paper](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)


### RESEARCH EXPERIENCE
*****
+ Contrastive Meta Learning with Behavior Multiplicity forRecommendation.
    - <u>Main Researcher, supervised by Dr. Huang Chao</u>     <p align="right">May 2021 - Aug. 2021</p>
    - Main problems to be solved:
        > 1. The interaction data of the target behavior is always sparse. For example, the user always generates a large number of page views, add to favor, add to cart, and finally only one purchase. On the original retail rocket dataset, the purchase behavior is only 1%. How to use the information of auxiliary behavior to help the final recommendation task on the target behavior is a problem that needs to be solved.
        > 2. The multi behavior mode of each user is different. Some users may compare a lot of goods before buying, but some users will directly buy the goods they need.
     - Framework:
          <td width="100%"><img src="/Pictures/CMLFramework.png" width="100%"></td>
        
        
    - Main contributions:
        > 1. We propose a new multi-behavior learning paradigm CML forrecommendation by emphasizing the importance of diverse andmultiplex user-item relationships, as well as the tackling the labelscarcity problem for target behaviors.
        > 2.In our CML framework, we design a multi-behavior contrastivelearning paradigm to capture the transferable user-item rela-tionships from multi-typed user behavior data, which incorpo-rates auxiliary supervision signals into the sparse target behaviormodeling. Furthermore, our proposed meta contrastive encodingscheme allows CML to preserve the personalized multi-behaviorcharacteristics, so as to be reflective of the diverse behavior-awareuser preference under a customized self-supervised framework.
        > 3.We perform extensive experiments on three real-world recom-mendation datasets to justify the rationality of our assumptionsand the effectiveness of our proposed framework. By comparingCML with 12 baselines, we show that CML is able to consistentlyimprove the performance of different techniques under varioussettings. Further analysis demonstrates the effectiveness of thedesigned sub-modules with ablation study.

    - Some experimental results:
        - [Baseline](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)
        - [Ablation Experiment](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)         
        <td width="25%"><img src="/Pictures/CMLAblationExperiment.png" width="50%"></td>
        - [Sparsity Experiment](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)
        <td width="25%"><img src="/Pictures/CMLSparsityExperiment.png" width="50%"></td>
        - Case Study:           
        <td width="25%"><img src="/Pictures/CMLCaseStudy.png" width="50%"></td>
        - [Parameter Experiment](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)      
        <td width="25%"><img src="/Pictures/CMLParameter.png" width="50%"></td>


+ Contrastive Meta Learning with Behavior Multiplicity for Recommendation
Main Researcher, Visual Computing Research Center of SCUT, supervised by Dr. Chao Huang   
May 2021 - Aug. 2021
  - Proposed a novel multi-behavior contrastive meta-learning framework to distill transferable knowledge        
from auxiliary to target behaviors for different users
  - Designed and implemented InfoNCE loss to learn the relationship between auxiliary and target behaviors
  - Conducted comprehensive literature review for self-supervised graph learning / contrastive learning
  - The proposed multi-behavior model significantly outperforms all baselines methods under various settings
  - Submitted a conference paper to WSDM 2022 as the first author

+ Hypergraph Attentive GNN for Sequential Recommendation with Behavior Heterogeneity
Undergraduate Thesis, supervised by Dr. Chao Huang                              Nov. 2020 - June 2021
  - Proposed a multi-behavior sequential recommendation model based on hypergraph and used self-attention  
to model the relationship between multiple behaviors for each user
  - Implemented the dynamic timestamp processing module and multi-time granularity hypergraph module
  - Designed and implemented attention module to fuse multi-behavior information
  - The proposed model achieves state-of-the-art performance on three datasets, with demonstrated stability  
and interpretability

+ Multi-channel Relation Modeling for Session-Based Recommendation with Self-Supervised Learning
Main Researcher, CAICT, supervised by Dr. Di Wu                                Apr. 2021 - July 2021
  - Proposed the Multi-Channel Relation Modeling Net, an assembling architecture composed of   
Recurrent Neural Networks, Graph Neural Network and Transformer modules
  - Designed multi-relation factorized pooling module to integrate multi-relation embedding
  - Devised a mutual information-based objective using self-supervised learning to generate more informative 	feature embedding

+ Survey on Graph Neural Network Recommendation
Main Researcher, VCRC of SCUT, supervised by Prof. Yong Xv                     Oct. 2020 - June 2021
  - Investigated the application of GNN in recommendation system including Sequential graph 	recommendation algorithm (MA-GNN, SR-GNN, GCE-GNN), KG-based recommendation algorithm 	(KGAT, Chorus), self-supervised graph/recommendation algorithm ( SGL, DGI, S3-Rec) and graph 	recommendation using meta network MB-GMN
  - Summarized key components of recommendation systems: objectives of the recommendation system, 	common types of data and their characteristics, recall and sorting and evaluating metrics

+ Research on Pedestrian Re-ID Algorithm Based on Domain Adaptation
Research Assistant, Intelligent Information Fusion Research Group, supervised by Prof. Jianming LV 
Mar. 2019 - Mar. 2020
  - Reviewed articles related to Re-ID and domain adaptation (DDC, DAN, RTN, JAN, DANN)
  - Conducted data analysis and learned to experiment through computing resources on Linux server
  - Won the Excellent Student Research Program (for top 5% students) of SCUT

### SKILLS
*****
+ __Deep Learning&Machine Learning Library__: Pytorch, Tensorflow, sklearn, DGL
+ __Python Library for data preprocessing__: scipy, pandas ,pickle, numpy
+ __Read&Write Paper__: Mendeley, Latex(Overleaf), Ability to quickly understand the point of the article in professional fields(Have already read a lot of literature)
+ __Configure environment__:
    - _Hardware_: Having a machine with RTX3090, 1T SSD, 64G internal memory 
, 1000W power supply and i7 tenth generation processor
    - _Software_: Installing the Ubuntu/Windows system, CUDA, cuDNN, Anaconda, Common IDE
+ __Programming Languages__: Python, C/C++, Markdown, HTML, CSS, Java Script
+ __Database__: MySQL
+ __Other Software__: Github, Mendeley, Latex, Conda
+ __Operating Systems__: Linux(shell/command line), Windows
+ __Languages__: English (proficient), Mandarin (native)

### PROJECT EXPERIENCE
*****
+ Advanced Language Program Design C++I: Maze(DFS,BSF). [Code](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)
+ Advanced Language Program Design C++II: Library management system. [Code](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)
+ Moblile Application Development(移动应用开发(Android)): Android notes. [Code](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)
+ Python Language Programming(Python语言程序设计): Application website web crawler. [Code](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)
+ Project of Data Structures(数据结果课程设计): Machine learning algorithm and neural network for image classification. [Code](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)
+ Web Programming(Web程序设计): Hometown introduction website. [Code](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)
+ Principle of Compiler Curriculum Design(编译原理课程设计): Simple compiler. [Code](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)
+ Operating System Curriculum Design(操作系统课程设计): Banker algorithm&Disk scheduling algorithm&Shell command interpreter. [Code](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)
+ Software Engineering Curriculum Design(软件工程课程设计): Mobile Market. [Code](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)
+ Diploma Project(毕业设计): Hypergraph Attentive Graph Neural Network for Sequential Recommendation with Behavior Heterogeneity. [Code](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)


### SOFTWARE COPYRIGHT
*****
+ Wei Wei, New Product Recommendation Platform Based on Machine Learning. China Software Copyright, 2021SR1077293. [Certificate](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)
+ Xu Dechao, Wei Wei, Huang Weijun. Traffic Information Flow Processing Platform Based on Deep Learning. China Software Copyright, 2021SR1171249. [Certificate](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)
+ Wei Wei, New Product Recommendation Platform Based on Machine Learning. China Software Copyright, 2021SR1077293. [Certificate](https://maiimg.com/pdf/?e=aubtqiOLu6WNc6)

### LEADERSHIP EXPERIENCE
*****
+ __Department Manager__, Technical Center of Student Association, SCUT                                <p align="right">Dec. 2017 - Nov. 2018</P>
  - Edited promotional video with Adobe Pr and Ae, produced posters using Adobe Ai and Ps
  - Responsible for the daily maintenance and management of the official website & WeChat account
+ __Class Monitor__                                                                          <p align="right">Sept. 2017 - Sept. 2018</p>
  - Held class communication and sharing meetings to provide help for students’ career planning
  - Assisted in hosting events, such as sports meetings and evening parties
