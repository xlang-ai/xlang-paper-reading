# LLM Tool Use Papers
![](https://img.shields.io/github/last-commit/xlang-ai/llm-ttol-use?color=green) ![](https://img.shields.io/badge/PaperNumber-62-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red) 


## Introduction
This is a paper list about **Tool-use** for large-scale pre-trained language models. Combine neural modules and symbolic components to make NLP systems more robust and interpretable is empowering large language models to utilize various tools and plugins (known as “symbolic components” and “neural modules”) to reason, which helps LLMs in:
- Weak symbolic reasoning (for math problems etc.)
- Hallucinations in reasoning (for highly precision-dependency fields)
- Missing/wrong real-time information (for time-sensitive fields)
- Blind real-world experience (for robotics etc.)
- No specific/private knowledge (for data-sensitive companies etc.)
- Limited context window length (for structured knowledge grounding etc.)

### Group


## Papers

1. **Language Models as Zero-Shot Planners: Extracting Actionable Knowledge for Embodied Agents.** ICML 2022
   
   *Wenlong Huang, Pieter Abbeel, Deepak Pathak, Igor Mordatch*  [[pdf](https://arxiv.org/abs/2201.07207)], 2022.1

2. **Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language.** ICLR 2023
   
   *Andy Zeng, Maria Attarian, Brian Ichter, Krzysztof Choromanski, Adrian Wong, Stefan Welker, Federico Tombari, Aveek Purohit, Michael Ryoo, Vikas Sindhwani, Johnny Lee, Vincent Vanhoucke, Pete Florence*  [[pdf](https://arxiv.org/abs/2204.00598)], 2022.4

3. **Do As I Can, Not As I Say: Grounding Language in Robotic Affordances.** Arxiv
   
   *Michael Ahn, Anthony Brohan, Noah Brown, Yevgen Chebotar, Omar Cortes, Byron David, Chelsea Finn, Chuyuan Fu, Keerthana Gopalakrishnan, Karol Hausman, Alex Herzog, Daniel Ho, Jasmine Hsu, Julian Ibarz, Brian Ichter, Alex Irpan, Eric Jang, Rosario Jauregui Ruano, Kyle Jeffrey, Sally Jesmonth, Nikhil J Joshi, Ryan Julian, Dmitry Kalashnikov, Yuheng Kuang, Kuang-Huei Lee, Sergey Levine, Yao Lu, Linda Luu, Carolina Parada, Peter Pastor, Jornell Quiambao, Kanishka Rao, Jarek Rettinghouse, Diego Reyes, Pierre Sermanet, Nicolas Sievers, Clayton Tan, Alexander Toshev, Vincent Vanhoucke, Fei Xia, Ted Xiao, Peng Xu, Sichun Xu, Mengyuan Yan, Andy Zeng*  [[pdf](https://arxiv.org/abs/2204.01691)], 2022.4

4. **TALM: Tool Augmented Language Models.** Arxiv
   
   *Aaron Parisi, Yao Zhao, Noah Fiedel*  [[pdf](https://arxiv.org/abs/2205.12255)], 2022.5

5. **Inner Monologue: Embodied Reasoning through Planning with Language Models.** CoRL 2022
   
   *Wenlong Huang, Fei Xia, Ted Xiao, Harris Chan, Jacky Liang, Pete Florence, Andy Zeng, Jonathan Tompson, Igor Mordatch, Yevgen Chebotar, Pierre Sermanet, Noah Brown, Tomas Jackson, Linda Luu, Sergey Levine, Karol Hausman, Brian Ichter*  [[pdf](https://arxiv.org/abs/2207.05608)], 2022.7

6. **JARVIS: A Neuro-Symbolic Commonsense Reasoning Framework for Conversational Embodied Agents.** SoCal NLP 2022
   
   *Kaizhi Zheng, Kaiwen Zhou, Jing Gu, Yue Fan, Jialu Wang, Zonglin Di, Xuehai He, Xin Eric Wang*  [[pdf](https://arxiv.org/abs/2208.13266)], 2022.8

7. **ProgPrompt: Generating Situated Robot Task Plans using Large Language Models.** ICRA 2023
   
   *Ishika Singh, Valts Blukis, Arsalan Mousavian, Ankit Goyal, Danfei Xu, Jonathan Tremblay, Dieter Fox, Jesse Thomason, Animesh Garg*  [[pdf](https://arxiv.org/abs/2209.11302)], 2022.9

8. **Code as Policies: Language Model Programs for Embodied Control.** Arxiv
   
   *Jacky Liang, Wenlong Huang, Fei Xia, Peng Xu, Karol Hausman, Brian Ichter, Pete Florence, Andy Zeng*  [[pdf](https://arxiv.org/abs/2209.07753)], 2022.9

9. **Binding Language Models in Symbolic Languages.** ICLR 2023
   
   *Zhoujun Cheng, Tianbao Xie, Peng Shi, Chengzu Li, Rahul Nadkarni, Yushi Hu, Caiming Xiong, Dragomir Radev, Mari Ostendorf, Luke Zettlemoyer, Noah A. Smith, Tao Yu*  [[pdf](https://arxiv.org/abs/2210.02875)], 2022.10

10. **Synergizing Reasoning and Acting in Language Models.** ICLR 2023

    *Shunyu Yao, Jeffrey Zhao, Dian Yu, Nan Du, Izhak Shafran, Karthik Narasimhan, Yuan Cao*  [[pdf](https://arxiv.org/abs/2210.03629)], 2022.10

11. **Mind's Eye: Grounded Language Model Reasoning through Simulation.** ICLR 2023

    *Ruibo Liu, Jason Wei, Shixiang Shane Gu, Te-Yen Wu, Soroush Vosoughi, Claire Cui, Denny Zhou, Andrew M. Dai*  [[pdf](https://arxiv.org/abs/2210.05359)], 2022.10

12. **Code4Struct: Code Generation for Few-Shot Event Structure Prediction.** ACL 2023

    *Xingyao Wang, Sha Li, Heng Ji*  [[pdf](https://arxiv.org/abs/2210.12810)], 2022.10

13. **PAL: Program-aided Language Models.** ICML 2023

    *Luyu Gao, Aman Madaan, Shuyan Zhou, Uri Alon, Pengfei Liu, Yiming Yang, Jamie Callan, Graham Neubig*  [[pdf](https://arxiv.org/abs/2211.10435)], 2022.11

14. **Visual Programming: Compositional visual reasoning without training.** CVPR 2023

    *Tanmay Gupta, Aniruddha Kembhavi*  [[pdf](https://arxiv.org/abs/2211.11559)], 2022.11

15. **Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks.** Arxiv

    *Wenhu Chen, Xueguang Ma, Xinyi Wang, William W. Cohen*  [[pdf](https://arxiv.org/abs/2211.12588)], 2022.11

16. **Planning with Large Language Models via Corrective Re-prompting.** Neurips 2023 workshop

    *Shreyas Sundara Raman, Vanya Cohen, Eric Rosen, Ifrah Idrees, David Paulius, Stefanie Tellex*  [[pdf](https://arxiv.org/abs/2211.09935)], 2022.11

17. **LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models.** Arxiv

    *Chan Hee Song, Jiaman Wu, Clayton Washington, Brian M. Sadler, Wei-Lun Chao, Yu Su*  [[pdf](https://arxiv.org/abs/2212.04088)], 2022.12

18. **Don't Generate, Discriminate: A Proposal for Grounding Language Models to Real-World Environments.** ACL 2023

    *Yu Gu, Xiang Deng, Yu Su*  [[pdf](https://arxiv.org/abs/2212.09736)], 2022.12

19. **Large language models are versatile decomposers: Decompose evidence and questions for table-based reasoning.** SIGIR 2023

    *Yunhu Ye, Binyuan Hui, Min Yang, Binhua Li, Fei Huang, Yongbin Li*  [[pdf](https://arxiv.org/abs/2301.13808)], 2023.1

20. **Augmented Language Models: a Survey.** Arxiv

    *Grégoire Mialon, Roberto Dessì, Maria Lomeli, Christoforos Nalmpantis, Ram Pasunuru, Roberta Raileanu, Baptiste Rozière, Timo Schick, Jane Dwivedi-Yu, Asli Celikyilmaz, Edouard Grave, Yann LeCun, Thomas Scialom*  [[pdf](https://arxiv.org/abs/2302.07842)], 2023.2

21. **Collaborating with language models for embodied reasoning.** NeurIPS 2022 LaReL workshop

    *Ishita Dasgupta, Christine Kaeser-Chen, Kenneth Marino, Arun Ahuja, Sheila Babayan, Felix Hill, Rob Fergus*  [[pdf](https://arxiv.org/abs/2302.00763)], 2023.2

22. **Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents.** Arxiv

    *Zihao Wang, Shaofei Cai, Anji Liu, Xiaojian Ma, Yitao Liang*  [[pdf](https://arxiv.org/abs/2302.01560)], 2023.2

23. **Toolformer: Language Models Can Teach Themselves to Use Tools.** Arxiv

    *Timo Schick, Jane Dwivedi-Yu, Roberto Dessì, Roberta Raileanu, Maria Lomeli, Luke Zettlemoyer, Nicola Cancedda, Thomas Scialom*  [[pdf](https://arxiv.org/abs/2302.04761)], 2023.2

24. **Grounded Decoding: Guiding Text Generation with Grounded Models for Robot Control.** Arxiv

    *Wenlong Huang, Fei Xia, Dhruv Shah, Danny Driess, Andy Zeng, Yao Lu, Pete Florence, Igor Mordatch, Sergey Levine, Karol Hausman, Brian Ichter*  [[pdf](https://arxiv.org/abs/2303.00855)], 2023.3

25. **PaLM-E: An Embodied Multimodal Language Model.** Arxiv

    *Danny Driess, Fei Xia, Mehdi S. M. Sajjadi, Corey Lynch, Aakanksha Chowdhery, Brian Ichter, Ayzaan Wahid, Jonathan Tompson, Quan Vuong, Tianhe Yu, Wenlong Huang, Yevgen Chebotar, Pierre Sermanet, Daniel Duckworth, Sergey Levine, Vincent Vanhoucke, Karol Hausman, Marc Toussaint, Klaus Greff, Andy Zeng, Igor Mordatch, Pete Florence*  [[pdf](https://arxiv.org/abs/2303.03378)], 2023.3

26. **Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models.** Arxiv

    *Chenfei Wu, Shengming Yin, Weizhen Qi, Xiaodong Wang, Zecheng Tang, Nan Duan*  [[pdf](https://arxiv.org/abs/2303.04671)], 2023.3

27. **ViperGPT: Visual Inference via Python Execution for Reasoning.** Arxiv

    *Dídac Surís, Sachit Menon, Carl Vondrick*  [[pdf](https://arxiv.org/abs/2303.08128)], 2023.3

28. **ART: Automatic multi-step reasoning and tool-use for large language models.** Arxiv

    *Bhargavi Paranjape, Scott Lundberg, Sameer Singh, Hannaneh Hajishirzi, Luke Zettlemoyer, Marco Tulio Ribeiro*  [[pdf](http://arxiv.org/abs/2303.09014)], 2023.3

29. **TaskMatrix.AI: Completing Tasks by Connecting Foundation Models with Millions of APIs.** Arxiv

    *Yaobo Liang, Chenfei Wu, Ting Song, Wenshan Wu, Yan Xia, Yu Liu, Yang Ou, Shuai Lu, Lei Ji, Shaoguang Mao, Yun Wang, Linjun Shou, Ming Gong, Nan Duan*  [[pdf](https://arxiv.org/abs/2303.16434)], 2023.3

30. **HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in HuggingFace.** Arxiv

    *Yongliang Shen, Kaitao Song, Xu Tan, Dongsheng Li, Weiming Lu, Yueting Zhuang*  [[pdf](https://arxiv.org/abs/2303.17580)], 2023.3

31. **OpenAGI: When LLM Meets Domain Experts.** Arxiv

    *Yingqiang Ge, Wenyue Hua, Kai Mei, Jianchao Ji, Juntao Tan, Shuyuan Xu, Zelong Li, Yongfeng Zhang*  [[pdf](https://arxiv.org/abs/2304.04370)], 2023.4

32. **API-Bank: A Benchmark for Tool-Augmented LLMs.** Arxiv

    *Minghao Li, Feifan Song, Bowen Yu, Haiyang Yu, Zhoujun Li, Fei Huang, Yongbin Li*  [[pdf](https://arxiv.org/abs/2304.08244)], 2023.4

33. **Tool Learning with Foundation Models.** Arxiv

    *Yujia Qin, Shengding Hu, Yankai Lin, Weize Chen, Ning Ding, Ganqu Cui, Zheni Zeng, Yufei Huang, Chaojun Xiao, Chi Han, Yi Ren Fung, Yusheng Su, Huadong Wang, Cheng Qian, Runchu Tian, Kunlun Zhu, Shihao Liang, Xingyu Shen, Bokai Xu, Zhen Zhang, Yining Ye, Bowen Li, Ziwei Tang, Jing Yi, Yuzhang Zhu, Zhenning Dai, Lan Yan, Xin Cong, Yaxi Lu, Weilin Zhao, Yuxiang Huang, Junxi Yan, Xu Han, Xian Sun, Dahai Li, Jason Phang, Cheng Yang, Tongshuang Wu, Heng Ji, Zhiyuan Liu, Maosong Sun*  [[pdf](https://arxiv.org/abs/2304.08354)], 2023.4

34. **GeneGPT: Augmenting Large Language Models with Domain Tools for Improved Access to Biomedical Information.** Arxiv

    *Qiao Jin, Yifan Yang, Qingyu Chen, Zhiyong Lu*  [[pdf](http://arxiv.org/abs/2304.09667)], 2023.4

35. **Chameleon: Plug-and-Play Compositional Reasoning with Large Language Models.** Arxiv

    *Pan Lu, Baolin Peng, Hao Cheng, Michel Galley, Kai-Wei Chang, Ying Nian Wu, Song-Chun Zhu, Jianfeng Gao*  [[pdf](https://arxiv.org/abs/2304.09842)], 2023.4

36. **LLM+P: Empowering Large Language Models with Optimal Planning Proficiency.** Arxiv

    *Bo Liu, Yuqian Jiang, Xiaohan Zhang, Qiang Liu, Shiqi Zhang, Joydeep Biswas, Peter Stone*  [[pdf](https://arxiv.org/abs/2304.11477)], 2023.4

37. **Search-in-the-Chain: Towards Accurate, Credible and Traceable Large Language Models for Knowledge-intensive Tasks.** Arxiv

    *Shicheng Xu, Liang Pang, Huawei Shen, Xueqi Cheng, Tat-Seng Chua*  [[pdf](https://arxiv.org/abs/2304.14732)], 2023.4

38. **Can LLM Already Serve as A Database Interface? A BIg Bench for Large-Scale Database Grounded Text-to-SQLs.** Arxiv

    *Jinyang Li, Binyuan Hui, Ge Qu, Binhua Li, Jiaxi Yang, Bowen Li, Bailin Wang, Bowen Qin, Rongyu Cao, Ruiying Geng, Nan Huo, Xuanhe Zhou, Chenhao Ma, Guoliang Li, Kevin C.C. Chang, Fei Huang, Reynold Cheng, Yongbin Li*  [[pdf](https://arxiv.org/abs/2305.03111)], 2023.5

39. **ToolCoder: Teach Code Generation Models to use API search tools.** Arxiv

    *Kechi Zhang, Ge Li, Jia Li, Zhuo Li, Zhi Jin*  [[pdf](https://arxiv.org/abs/2305.04032)], 2023.5

40. **Small models are valuable plug-ins for large language models.** Arxiv

    *Canwen Xu, Yichong Xu, Shuohang Wang, Yang Liu, Chenguang Zhu, Julian McAuley*  [[pdf](https://arxiv.org/abs/2305.08848)], 2023.5

41. **Multimodal Web Navigation with Instruction-Finetuned Foundation Models.** ICLR 2023 Workshop ME-FoMo

    *Hiroki Furuta, Ofir Nachum, Kuang-Huei Lee, Yutaka Matsuo, Shixiang Shane Gu, Izzeddin Gur*  [[pdf](https://arxiv.org/abs/2305.11854)], 2023.5

42. **ToolkenGPT: Augmenting Frozen Language Models with Massive Tools via Tool Embeddings.** Arxiv

    *Shibo Hao, Tianyang Liu, Zhen Wang, Zhiting Hu*  [[pdf](https://arxiv.org/abs/2305.11554)], 2023.5

43. **CRITIC: Large Language Models Can Self-Correct with Tool-Interactive Critiquing.** Arxiv

    *Zhibin Gou, Zhihong Shao, Yeyun Gong, Yelong Shen, Yujiu Yang, Nan Duan, Weizhu Chen*  [[pdf](https://arxiv.org/abs/2305.11738)], 2023.5

44. **Making Language Models Better Tool Learners with Execution Feedback.** Arxiv

    *Shuofei Qiao, Honghao Gui, Huajun Chen, Ningyu Zhang*  [[pdf](https://arxiv.org/abs/2305.13068)], 2023.5

45. **Hierarchical Prompting Assists Large Language Model on Web Navigation.** ACL 2023 NLRSE workshop

    *Abishek Sridhar, Robert Lo, Frank F. Xu, Hao Zhu, Shuyan Zhou*  [[pdf](https://arxiv.org/abs/2305.14257)], 2023.5

46. **PEARL: Prompting Large Language Models to Plan and Execute Actions Over Long Documents.** Arxiv

    *Simeng Sun, Yang Liu, Shuohang Wang, Chenguang Zhu, Mohit Iyyer*  [[pdf](https://arxiv.org/abs/2305.14564)], 2023.5

47. **ReWOO: Decoupling Reasoning from Observations for Efficient Augmented Language Models.** Arxiv

    *Binfeng Xu, Zhiyuan Peng, Bowen Lei, Subhabrata Mukherjee, Yuchen Liu, Dongkuan Xu*  [[pdf](https://arxiv.org/abs/2305.18323)], 2023.5

48. **Gorilla: Large Language Model Connected with Massive APIs.** Arxiv

    *Shishir G. Patil, Tianjun Zhang, Xin Wang, Joseph E. Gonzalez*  [[pdf](https://arxiv.org/abs/2305.15334)], 2023.5

49. **SPRING: GPT-4 Out-performs RL Algorithms by Studying Papers and Reasoning.** Arxiv

    *Yue Wu, Shrimai Prabhumoye, So Yeon Min, Yonatan Bisk, Ruslan Salakhutdinov, Amos Azaria, Tom Mitchell, Yuanzhi Li*  [[pdf](https://arxiv.org/abs/2305.15486)], 2023.5

50. **Leveraging Pre-trained Large Language Models to Construct and Utilize World Models for Model-based Task Planning.** Arxiv

    *Lin Guan, Karthik Valmeekam, Sarath Sreedharan, Subbarao Kambhampati*  [[pdf](https://arxiv.org/abs/2305.14909)], 2023.5

51. **On the Tool Manipulation Capability of Open-source Large Language Models.** Arxiv

    *Qiantong Xu, Fenglu Hong, Bo Li, Changran Hu, Zhengyu Chen, Jian Zhang*  [[pdf](https://arxiv.org/abs/2305.16504)], 2023.5

52. **Voyager: An Open-Ended Embodied Agent with Large Language Models.** Arxiv

    *Guanzhi Wang, Yuqi Xie, Yunfan Jiang, Ajay Mandlekar, Chaowei Xiao, Yuke Zhu, Linxi Fan, Anima Anandkumar*  [[pdf](https://arxiv.org/abs/2305.16291)], 2023.5

53. **Large Language Models as Tool Makers.** Arxiv

    *Tianle Cai, Xuezhi Wang, Tengyu Ma, Xinyun Chen, Denny Zhou*  [[pdf](https://arxiv.org/abs/2305.17126)], 2023.5
   
54. **GPT4Tools: Teaching Large Language Model to Use Tools via Self-instruction.** Arxiv

    *Rui Yang, Lin Song, Yanwei Li, Sijie Zhao, Yixiao Ge, Xiu Li, Ying Shan*  [[pdf](https://arxiv.org/abs/2305.18752)], 2023.5

55. **SheetCopilot: Bringing Software Productivity to the Next Level through Large Language Models.** Arxiv

    *Hongxin Li, Jingran Su, Yuntao Chen, Qing Li, Zhaoxiang Zhang*  [[pdf](https://arxiv.org/abs/2305.19308)], 2023.5

56. **CREATOR: Disentangling Abstract and Concrete Reasonings of Large Language Models through Tool Creation.** Arxiv

    *Cheng Qian, Chi Han, Yi R. Fung, Yujia Qin, Zhiyuan Liu, Heng Ji*  [[pdf](https://arxiv.org/abs/2305.14318)], 2023.5

57. **SQL-PaLM: Improved Large Language ModelAdaptation for Text-to-SQL.** Arxiv

    *Ruoxi Sun, Sercan O. Arik, Hootan Nakhost, Hanjun Dai, Rajarishi Sinha, Pengcheng Yin, Tomas Pfister*  [[pdf](https://arxiv.org/abs/2306.00739)], 2023.6

58. **From Pixels to UI Actions: Learning to Follow Instructions via Graphical User Interfaces.** Arxiv

    *Peter Shaw, Mandar Joshi, James Cohan, Jonathan Berant, Panupong Pasupat, Hexiang Hu, Urvashi Khandelwal, Kenton Lee, Kristina Toutanova*  [[pdf](https://arxiv.org/abs/2306.00245)], 2023.6

59. **Modular Visual Question Answering via Code Generation.** ACL 2023

    *Sanjay Subramanian, Medhini Narasimhan, Kushal Khangaonkar, Kevin Yang, Arsha Nagrani, Cordelia Schmid, Andy Zeng, Trevor Darrell, Dan Klein*  [[pdf](https://arxiv.org/abs/2306.05392)], 2023.6

60. **ToolAlpaca: Generalized Tool Learning for Language Models with 3000 Simulated Cases.** Arxiv

    *Qiaoyu Tang, Ziliang Deng, Hongyu Lin, Xianpei Han, Qiao Liang, Le Sun*  [[pdf](https://arxiv.org/abs/2306.05301)], 2023.6

61. **Mind2Web: Towards a Generalist Agent for the Web.** Arxiv

    *Xiang Deng, Yu Gu, Boyuan Zheng, Shijie Chen, Samuel Stevens, Boshi Wang, Huan Sun, Yu Su*  [[pdf](https://arxiv.org/abs/2306.06070)], 2023.6

62. **Can Language Models Teach Weaker Agents? Teacher Explanations Improve Students via Theory of Mind.** Arxiv

    *Swarnadeep Saha, Peter Hase, Mohit Bansal*  [[pdf](https://arxiv.org/abs/2306.09299)], 2023.6


63. **Data-Copilot: Bridging Billions of Data and Humans with Autonomous Workflow.** Arxiv

    *Wenqi Zhang, Yongliang Shen, Weiming Lu, Yueting Zhuang*  [[pdf](https://arxiv.org/abs/2306.07209)], 2023.6
    

## Code generation papers

1. **On-the-Fly Adaptation of Source Code Models using Meta-Learning.** NeurIPS 2020 CAP Workshop

    *Disha Shrivastava, Hugo Larochelle, Daniel Tarlow*  [[pdf](https://arxiv.org/abs/2003.11768v1)], 2020.5.26

2. **DocPrompting: Generating Code by Retrieving the Docs.** ICLR 2023

    *Shuyan Zhou, Uri Alon, Frank F. Xu, Zhiruo Wang, Zhengbao Jiang, Graham Neubig*  [[pdf](https://arxiv.org/abs/2207.05987)], 2022.7.13

3. **CodeT: Code Generation with Generated Tests.** ICLR 2023

    *Bei Chen, Fengji Zhang, Anh Nguyen, Daoguang Zan, Zeqi Lin, Jian-Guang Lou, Weizhu Chen*  [[pdf](https://arxiv.org/abs/2207.10397)], 2022.7.21

4. **Language Models Can Teach Themselves to Program Better.** ICLR 2023

    *Patrick Haluptzok, Matthew Bowers, Adam Tauman Kalai*  [[pdf](https://arxiv.org/abs/2207.14502)], 2022.7.29

5. **Coder Reviewer Reranking for Code Generation.** ICML 2023

    *Tianyi Zhang, Tao Yu, Tatsunori B. Hashimoto, Mike Lewis, Wen-tau Yih, Daniel Fried, Sida I. Wang*  [[pdf](https://arxiv.org/abs/2211.16490)], 2022.11.29

6. **Python Code Generation by Asking Clarification Questions.** ACL 2023

    *Haau-Sing Li, Mohsen Mesgar, André F. T. Martins, Iryna Gurevych*  [[pdf](https://arxiv.org/abs/2212.09885)], 2022.12.19

7. **LEVER: Learning to Verify Language-to-Code Generation with Execution.** ICLR 2023

    *Ansong Ni, Srini Iyer, Dragomir Radev, Ves Stoyanov, Wen-tau Yih, Sida I. Wang, Xi Victoria Lin*  [[pdf](https://arxiv.org/abs/2302.08468)], 2023.2.16
   
8. **EvoPrompting: Language Models for Code-Level Neural Architecture Search.** Arxiv

    *Angelica Chen, David M. Dohan, David R. So*  [[pdf](https://arxiv.org/abs/2302.14838)], 2023.2.28
   
9. **Planning with Large Language Models for Code Generation.** ICLR 2023

    *Shun Zhang, Zhenfang Chen, Yikang Shen, Mingyu Ding, Joshua B. Tenenbaum, Chuang Gan.*  [[pdf](https://arxiv.org/abs/2303.05510)], 2023.3.9
   
10. **Self-planning Code Generation with Large Language Model.** Arxiv

    *Xue Jiang, Yihong Dong, Lecheng Wang, Qiwei Shang, Ge Li*  [[pdf](https://arxiv.org/abs/2303.06689)], 2023.3.12
   
11. **Reflexion: Language Agents with Verbal Reinforcement Learning.** Arxiv

    *Noah Shinn, Federico Cassano, Beck Labash, Ashwin Gopinath, Karthik Narasimhan, Shunyu Yao*  [[pdf](https://arxiv.org/abs/2303.11366)], 2023.3.20

12. **Teaching Large Language Models to Self-Debug.** Arxiv

    *Xinyun Chen, Maxwell Lin, Nathanael Schärli, Denny Zhou*  [[pdf](https://arxiv.org/abs/2304.05128)], 2023.4.11

13. **WizardLM: Empowering Large Language Models to Follow Complex Instructions.** Arxiv

    *Can Xu, Qingfeng Sun, Kai Zheng, Xiubo Geng, Pu Zhao, Jiazhan Feng, Chongyang Tao, Daxin Jiang*  [[pdf](https://arxiv.org/abs/2304.12244)], 2023.4.24
   
14. **Grammar Prompting for Domain-Specific Language Generation with Large Language Models.** Arxiv

    *Bailin Wang, Zi Wang, Xuezhi Wang, Yuan Cao, Rif A. Saurous, Yoon Kim*  [[pdf](https://arxiv.org/abs/2305.19234)], 2023.5.30

15. **From Words to Code: Harnessing Data for Program Synthesis from Natural Language.** Arxiv

    *Anirudh Khatry, Joyce Cahoon, Jordan Henkel, Shaleen Deep, Venkatesh Emani, Avrilia Floratou, Sumit Gulwani, Vu Le, Mohammad Raza, Sherry Shi, Mukul Singh, Ashish Tiwari*  [[pdf](Anirudh Khatry, Joyce Cahoon, Jordan Henkel, Shaleen Deep, Venkatesh Emani, Avrilia Floratou, Sumit Gulwani, Vu Le, Mohammad Raza, Sherry Shi, Mukul Singh, Ashish Tiwari)], 2023.5.2

16. **Is Your Code Generated by ChatGPT Really Correct? Rigorous Evaluation of Large Language Models for Code Generation.** Arxiv

    *Jiawei Liu, Chunqiu Steven Xia, Yuyao Wang, Lingming Zhang*  [[pdf](https://arxiv.org/abs/2305.01210)], 2023.5.2


17. **ALGO: Synthesizing Algorithmic Programs with Generated Oracle Verifiers.** Arxiv

    *Kexun Zhang, Danqing Wang, Jingtao Xia, William Yang Wang, Lei Li*  [[pdf](https://arxiv.org/abs/2305.14591)], 2023.5.24

18. **WizardCoder: Empowering Code Large Language Models with Evol-Instruct.** Arxiv

    *Ziyang Luo, Can Xu, Pu Zhao, Qingfeng Sun, Xiubo Geng, Wenxiang Hu, Chongyang Tao, Jing Ma, Qingwei Lin, Daxin Jiang*  [[pdf](https://arxiv.org/abs/2306.08568)], 2023.6.14

19. **Demystifying GPT Self-Repair for Code Generation.** Arxiv

    *Theo X. Olausson, Jeevana Priya Inala, Chenglong Wang, Jianfeng Gao, Armando Solar-Lezama*  [[pdf](https://arxiv.org/abs/2306.09896)], 2023.6.16

20. **RepoFusion: Training Code Models to Understand Your Repository.** Arxiv

    *Disha Shrivastava, Denis Kocetkov, Harm de Vries, Dzmitry Bahdanau, Torsten Scholak*  [[pdf](https://arxiv.org/abs/2306.10998)], 2023.6.19

21. **Guiding Language Models of Code with Global Context using Monitors.** Arxiv

    *Lakshya A Agrawal, Aditya Kanade, Navin Goyal, Shuvendu K. Lahiri, Sriram K. Rajamani*  [[pdf](https://arxiv.org/abs//2306.10763)], 2023.6.19

22. **Textbooks Are All You Need.** Arxiv

    *Suriya Gunasekar, Yi Zhang, Jyoti Aneja, Caio César Teodoro Mendes, Allie Del Giorno, Sivakanth Gopi, Mojan Javaheripi, Piero Kauffmann, Gustavo de Rosa, Olli Saarikivi, Adil Salim, Shital Shah, Harkirat Singh Behl, Xin Wang, Sébastien Bubeck, Ronen Eldan, Adam Tauman Kalai, Yin Tat Lee, Yuanzhi Li*  [[pdf](https://arxiv.org/abs/2306.11644)], 2023.6.20

23. **Language models are weak learners.** Arxiv

    *Hariharan Manikandan, Yiding Jiang, J Zico Kolter*  [[pdf](https://arxiv.org/abs/2306.14101)], 2023.6.25

24. **Repository-Level Prompt Generation for Large Language Models of Code.** ICML 2023

    *Disha Shrivastava, Hugo Larochelle, Daniel Tarlow*  [[pdf](https://arxiv.org/abs/2206.12839)], 2022.6.26


25. **LongCoder: A Long-Range Pre-trained Language Model for Code Completion.** Arxiv

    *Daya Guo, Canwen Xu, Nan Duan, Jian Yin, Julian McAuley*  [[pdf](https://arxiv.org/abs/2306.14893)], 2023.6.26

26. **InterCode: Standardizing and Benchmarking Interactive Coding with Execution Feedback.** Arxiv

    *John Yang, Akshara Prabhakar, Karthik Narasimhan, Shunyu Yao*  [[pdf](https://arxiv.org/abs/2306.14898)], 2023.6.26

