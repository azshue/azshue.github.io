---
permalink: /
title: ""
excerpt:
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## About me     
   I am a researcher at Salesforce Research, where I spend most of my time working on large multimodal models. Before joining Salesforce, I obtained my Ph.D. degree in Computer Science from the University of Maryland, College Park (UMD) in 2024, advised by [Tom Goldstein](https://www.cs.umd.edu/~tomg/). My PhD research focuses topics relevant to AI/ML safety and trustworthiness in both vision and language modalities.     

   During my years at UMD, I have interned at Nvidia, Salesforce, and Google as a research intern, where I have collaborated with many awesome professors and researchers. Before that, I obtained my bachelor's degree in information security at the University of Science and Technology of China (USTC) in June 2019.      
  


## News
* **[08/2024]** Technical report is released: [xGen-MM (BLIP-3): A Family of Open Large Multimodal](https://arxiv.org/pdf/2408.08872), along with xGen-MM-v1.5 model release. Been driving the post-training and open-source effort in this project. [\[<u>arXiv</u>\]](https://arxiv.org/pdf/2408.08872) [\[<u>X Live with @AK</u>\]](https://x.com/_akhaliq/status/1825738604435419497), [\[<u>🤗 Model card</u>\]](https://huggingface.co/Salesforce/xgen-mm-phi3-mini-instruct-interleave-r-v1.5)
* **[05/2024]** Released Salesforce's multimodal large language models - xGen-MM, the enhanced continuation of our BLIP series. [\[<u>Twitter</u>\]](https://x.com/ManliShu/status/1789151298258108580), [\[<u>🤗 Model card</u>\]](https://huggingface.co/Salesforce/xgen-mm-phi3-mini-instruct-r-v1)
* **[05/2024]** Gave an oral presentation at ICRA'24 on a previous internship project about 3D object detection. [\[<u>paper</u>\]](https://arxiv.org/pdf/2301.02650) [\[<u>slides</u>\]](https://azshue.github.io/files/icra-2024-presentation-pdf.pdf)
* **[02/2024]** Two preprints out (done at UMD). One studied data poisoning on vision-language models([arXiv](https://arxiv.org/pdf/2402.06659)), another explored adversarial attacks on LLMs([arXiv](https://arxiv.org/pdf/2402.14020)).
* **[01/2024]** Joined Salesforce Research. Relocated to Palo Alto, CA. 
* **[11/2023]** Defended my Ph.D. dissertation 💐 👩🏻‍🎓
* **[09/2023]** One paper accepted at NeurIPS. We studied a novel vulnerability of aligned language models from the perspective of data security. [\[<u>paper</u>\]](https://proceedings.neurips.cc/paper_files/paper/2023/file/c2a8060fd22744b38177d9e428a052e0-Paper-Conference.pdf)[\[<u>code</u>\]](https://github.com/azshue/AutoPoison)
* **[11/2022]** In New Orleans attending NeurIPS. Presented the work done at Nvidia about prompt tuning for vision-language models. (Excited to attend my first in-person academic conference. I wish I had printed a bigger poster.)[\[<u>paper</u>\]](https://arxiv.org/pdf/2209.07511)[<u>project page</u>\]](https://azshue.github.io/TPT/)[\[<u>code</u>\]](https://github.com/azshue/TPT)


## Selected Publications

  *For the complete list of publications, please refer to my [google scholar](https://scholar.google.com/citations?user=WPYkxjgAAAAJ&hl=en) page*

  * **xGen-MM (BLIP-3): A Family of Open Large Multimodal Models**    
    L. Xue, **M. Shu\***, A. Awadalla, J. Wang, A. Yan, S. Purushwalkam, H. Zhou, V. Prabhu, Y. Dai, M. S Ryoo, S. Kendre, J. Zhang, C. Qin, S. Zhang, C. Chen, N. Yu, J. Tan, T. Awalgaonkar, S. Heinecke, H. Wang, Y. Choi, L. Schmidt, Z. Chen, S. Savarese, J. C. Niebles, C. Xiong, R. Xu    
    *ECCV 2024 Eval-FoMo workshop*  
    [[arXiv](https://arxiv.org/pdf/2408.08872)][[🤗 Model card](https://huggingface.co/Salesforce/xgen-mm-phi3-mini-instruct-interleave-r-v1.5)] [[Code](https://github.com/salesforce/LAVIS/tree/xgen-mm)]
  


  * **Test-Time Prompt Tuning for Zero-Shot Generalization in Vision-Language Models**    
    **M. Shu**, W. Nie, D.A. Huang, Z. Yu, T. Goldstein, A. Anandkumar, C. Xiao    
    *NeurIPS 2022*     
    [[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/5bf2b802e24106064dc547ae9283bb0c-Paper-Conference.pdf)] [[Code](https://github.com/azshue/TPT)] [[Project page](https://azshue.github.io/TPT)]

    
  * **On the Exploitability of Instruction Tuning**    
    **M. Shu**, J. Wang, C. Zhu, J. Geiping, C. Xiao, T. Goldstein    
    *NeurIPS 2023*  
    [[arXiv](https://arxiv.org/pdf/2306.17194.pdf)] [[Code](https://github.com/azshue/AutoPoison)]

  * **MINT-1T: Scaling Open-Source Multimodal Data by 10x: A Multimodal Dataset with One Trillion Tokens**    
    A. Awadalla, L. Xue, O. Lo, **M. Shu**, H. Lee, E. Kumar Guha, M. Jordan, S. Shen, M. Awadalla, S. Savarese, C. Xiong, R. Xu, Y. Choi, L. Schmidt.    
    *NeurIPS 2024*  
    [[arXiv](https://arxiv.org/pdf/2406.11271)][[🤗 Dataset card](https://huggingface.co/collections/mlfoundations/mint-1t-6690216ca4d0df7e518dde1c)]

  * **On the Reliability of Watermarks for Large Language Models**    
    J. Kirchenbauer\*, J. Geiping\*, Y. Wen, **M. Shu**, K. Saifullah, K. Kong, K. Fernando, A. Saha, M. Goldblum, T. Goldstein    
    *ICLR 2024*    
    [[arXiv](https://arxiv.org/pdf/2306.04634.pdf)] [[Code](https://github.com/jwkirchenbauer/lm-watermarking)]

  * **Where do Models go Wrong? Parameter-Space Saliency Maps for Explainability**    
    R. Levin\*, **M. Shu\***, E. Borgnia\*, F. Huang, M. Goldblum, T. Goldstein    
    *NeurIPS 2022*     
    [[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/6450ea28ebbc8437bc38775157818172-Paper-Conference.pdf)] [[Code](https://github.com/azshue/parameter-space-saliency)]

  * **The Close Relationship Between Contrastive Learning and Meta-Learning**    
    R. Ni\*, **M. Shu\***, H. Souri, M. Goldblum, T. Goldstein    
    *ICLR 2022*    
    [[Paper](https://openreview.net/pdf?id=gICys3ITSmj)] [[Code](https://github.com/RenkunNi/MetaContrastive)]

  
  * **Encoding Robustness to Image Style via Adversarial Feature Perturbation**    
    **M. Shu**, Z. Wu, M. Goldblum, T. Goldstein    
    *NeurIPS 2021*     
    [[Paper](https://proceedings.neurips.cc/paper/2021/file/ec20019911a77ad39d023710be68aaa1-Paper.pdf)] [[Code](https://github.com/azshue/AdvBN)]

  * **Adversarial Differentiable Data Augmentation for Autonomous Systems**    
    **M. Shu**, Y. Shen, M.C. Lin, T. Goldstein    
    *ICRA 2021*     
    [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9561205)] [[Code](https://github.com/azshue/adversarial_data_augmentation)]
  
  * **Model-Agnostic Hierarchical Attention for 3D Object Detection**    
    **M. Shu**, L. Xue, R. Mart\'in-Mart\'in, C. Xiong, T. Goldstein, J.C. Niebles, R. Xu.    
    *ICRA 2024*     
    [[arXiv](https://arxiv.org/pdf/2301.02650.pdf)] [[Code](https://github.com/salesforce/Hierarchical_Point_Attention)]


## Services

Conference reviewer:  NeurIPS, ICML, ICLR, CVPR, ICCV, IROS   
Journal reviewer: IJCV    

## More about me (misc)

Things I like: Sun, seaside, going for a walk, yoga, weightlifting, civ 6, the legend of Zelda (BotW)...
