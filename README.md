# Topic-on-Table-Processing
This is a survey on the topic of Table Processing:blush:

## Brief introduction to Table Processing Problems and this Repository
**Table Processing** has long been a difficult problem for computer researchers. The mainstream of the academic world is to divide the problem of table processing into **Table detection** and **Table Structure Recognition**. 

Especially after the rise of **Deep Learning** in 2016, many researchers have entered this field and combined deep learning methods to explore **Table Processing**, which has brought us a lot of inspiration. At the same time, there are still many problems that have not been well solved.

So this is a repository for the collection of **Table Detection** and **Table Structure Recognition** Models and Datasets based on **Deep Learning** methods.

## Classification of Table Processing papers based on different topics(Some papers will cover several topics, so they will be repeated in these topics)
### DataSet (Baseline or Benchmark)
* Göbel, Max, Tamir Hassan, Ermelinda Oro, and Giorgio Orsi. "ICDAR 2013 table competition." In 2013 12th International Conference on Document Analysis and Recognition, pp. 1449-1453. IEEE, 2013 [Paper Link](https://ieeexplore.ieee.org/abstract/document/6628853), [Home Page Link](https://rrc.cvc.uab.es/).
* Gao, Liangcai, Xiaohan Yi, Zhuoren Jiang, Leipeng Hao, and Zhi Tang. "ICDAR2017 competition on page object detection." In 2017 14th IAPR International Conference on Document Analysis and Recognition (ICDAR), vol. 1, pp. 1417-1422. IEEE, 2017. [Paper Link](https://ieeexplore.ieee.org/abstract/document/8270162), [Home Page Link](https://rrc.cvc.uab.es/).
* Gao, Liangcai, Yilun Huang, Hervé Déjean, Jean-Luc Meunier, Qinqin Yan, Yu Fang, Florian Kleber, and Eva Lang. "ICDAR 2019 competition on table detection and recognition (cTDaR)." In 2019 International Conference on Document Analysis and Recognition (ICDAR), pp. 1510-1515. IEEE, 2019.  [Paper Link](https://ieeexplore.ieee.org/abstract/document/8978120), [Home Page Link](https://rrc.cvc.uab.es/).
* Yang, F., Hu, L., Liu, X. et al. A large-scale dataset for end-to-end table recognition in the wild. Sci Data 10, 110 (2023).  [Paper Link](https://doi.org/10.1038/s41597-023-01985-8)
* Li, Yiren, Zheng Huang, Junchi Yan, Yi Zhou, Fan Ye, and Xianhui Liu. "GFTE: graph-based financial table extraction." In International Conference on Pattern Recognition, pp. 644-658. Springer, Cham, 2021. [Paper Link](https://link.springer.com/chapter/10.1007/978-3-030-68790-8_50)
* Zhong, Xu, Elaheh ShafieiBavani, and Antonio Jimeno Yepes. "Image-based table recognition: data, model, and evaluation." In European Conference on Computer Vision, pp. 564-580. Springer, Cham, 2020. [Paper Link](https://link.springer.com/chapter/10.1007/978-3-030-58589-1_34), [Home Page Link](https://github.com/ibm-aur-nlp/PubTabNet).
* Smock, Brandon, Rohith Pesala, and Robin Abraham. "PubTables-1M: Towards comprehensive table extraction from unstructured documents." In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 4634-4642. 2022. [Paper Link](https://openaccess.thecvf.com/content/CVPR2022/html/Smock_PubTables-1M_Towards_Comprehensive_Table_Extraction_From_Unstructured_Documents_CVPR_2022_paper.html), [Home Page Link](https://github.com/microsoft/table-transformer).
* Li, Minghao, Lei Cui, Shaohan Huang, Furu Wei, Ming Zhou, and Zhoujun Li. "Tablebank: Table benchmark for image-based table detection and recognition." In Proceedings of The 12th language resources and evaluation conference, pp. 1918-1925. 2020. [Paper Link](https://aclanthology.org/2020.lrec-1.236/)
* Samari, Arash, Andrew Piper, Alison Hedley, and Mohamed Cheriet. "Weakly supervised bounding box extraction for unlabeled data in table detection." In International Conference on Pattern Recognition, pp. 339-352. Springer, Cham, 2021.[Paper Link](https://link.springer.com/chapter/10.1007/978-3-030-68787-8_25)
*  Zheng, Xinyi, Douglas Burdick, Lucian Popa, Xu Zhong, and Nancy Xin Ru Wang. "Global table extractor (gte): A framework for joint table identification and cell structure recognition using visual context." In Proceedings of the IEEE/CVF winter conference on applications of computer vision, pp. 697-706. 2021. [Paper Link](https://openaccess.thecvf.com/content/WACV2021/html/Zheng_Global_Table_Extractor_GTE_A_Framework_for_Joint_Table_Identification_WACV_2021_paper.html), [Home Page Link](https://developer.ibm.com/data/fintabnet/).

### End-to-End Methods
* Yang, F., Hu, L., Liu, X. et al. A large-scale dataset for end-to-end table recognition in the wild. Sci Data 10, 110 (2023).  [Paper Link](https://doi.org/10.1038/s41597-023-01985-8)
* Ly, N. T., Takasu, A., Nguyen, P., & Takeda, H. (2023). Rethinking Image-based Table Recognition Using Weakly Supervised Methods. arXiv preprint arXiv:2303.07641. [Paper Link]( https://arxiv.org/abs/2303.07641)
* Ly, N. T., & Takasu, A. (2023). An End-to-End Multi-Task Learning Model for Image-based Table Recognition. arXiv preprint arXiv:2303.08648. [Paper Link]( https://arxiv.org/abs/2303.08648 )
* Prasad, Devashish, Ayan Gadpal, Kshitij Kapadni, Manish Visave, and Kavita Sultanpure. "CascadeTabNet: An approach for end to end table detection and structure recognition from image-based documents." In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition workshops, pp. 572-573. 2020. [Paper Link](https://openaccess.thecvf.com/content_CVPRW_2020/html/w34/Prasad_CascadeTabNet_An_Approach_for_End_to_End_Table_Detection_and_CVPRW_2020_paper.html)
* Guo, Zengyuan, Yuechen Yu, Pengyuan Lv, Chengquan Zhang, Haojie Li, Zhihui Wang, Kun Yao, Jingtuo Liu, and Jingdong Wang. "TRUST: An Accurate and End-to-End Table structure Recognizer Using Splitting-based Transformers." arXiv preprint arXiv:2208.14687 (2022). [Paper Link](https://arxiv.org/abs/2208.14687)
* Paliwal, Shubham Singh, D. Vishwanath, Rohit Rahul, Monika Sharma, and Lovekesh Vig. "Tablenet: Deep learning model for end-to-end table detection and tabular data extraction from scanned document images." In 2019 International Conference on Document Analysis and Recognition (ICDAR), pp. 128-133. IEEE, 2019. [Paper Link](https://ieeexplore.ieee.org/abstract/document/8978013)
* Hashmi, Khurram Azeem, Alain Pagani, Marcus Liwicki, Didier Stricker, and Muhammad Zeshan Afzal. "CasTabDetectoRS: cascade network for table detection in document images with recursive feature pyramid and switchable atrous convolution." Journal of Imaging 7, no. 10 (2021): 214. [Paper Link](https://www.mdpi.com/2313-433X/7/10/214)
* Agarwal, Madhav, Ajoy Mondal, and C. V. Jawahar. "Cdec-net: Composite deformable cascade network for table detection in document images." In 2020 25th International Conference on Pattern Recognition (ICPR), pp. 9491-9498. IEEE, 2021. *  [Paper Link](https://ieeexplore.ieee.org/abstract/document/9411922)
* Nazir, Danish, Khurram Azeem Hashmi, Alain Pagani, Marcus Liwicki, Didier Stricker, and Muhammad Zeshan Afzal. "HybridTabNet: Towards better table detection in scanned document images." Applied Sciences 11, no. 18 (2021): 8396.  [Paper Link]( https://www.mdpi.com/2076-3417/11/18/8396)
  
### SOTA(or just the mainstream)
* Zhong, Xu, Elaheh ShafieiBavani, and Antonio Jimeno Yepes. "Image-based table recognition: data, model, and evaluation." In European Conference on Computer Vision, pp. 564-580. Springer, Cham, 2020. [Paper Link](https://link.springer.com/chapter/10.1007/978-3-030-58589-1_34), [Home Page Link](https://github.com/ibm-aur-nlp/PubTabNet).
* Agarwal, Madhav, Ajoy Mondal, and C. V. Jawahar. "Cdec-net: Composite deformable cascade network for table detection in document images." In 2020 25th International Conference on Pattern Recognition (ICPR), pp. 9491-9498. IEEE, 2021. *  [Paper Link](https://ieeexplore.ieee.org/abstract/document/9411922)
* Kazdar, Takwa, Wided Souidene Mseddi, Moulay A. Akhloufi, Ala Agrebi, Marwa Jmal, and Rabah Attia. 2023. "DCTable: A Dilated CNN with Optimizing Anchors for Accurate Table Detection" Journal of Imaging 9, no. 3: 62. [Paper Link](https://doi.org/10.3390/jimaging9030062)
* Li, Junlong, Yiheng Xu, Tengchao Lv, Lei Cui, Cha Zhang, and Furu Wei. "Dit: Self-supervised pre-training for document image transformer." arXiv preprint arXiv:2203.02378 (2022). [Paper Link](https://arxiv.org/abs/2203.02378)
* Namysl, Marcin, Alexander M. Esser, Sven Behnke, and Joachim Köhler. "Tab. IAIS: Flexible Table Recognition and Semantic Interpretation System." arXiv preprint arXiv:2105.11879 (2021). [Paper Link](https://arxiv.org/abs/2105.11879)
* Zheng, Xinyi, Douglas Burdick, Lucian Popa, Xu Zhong, and Nancy Xin Ru Wang. "Global table extractor (gte): A framework for joint table identification and cell structure recognition using visual context." In Proceedings of the IEEE/CVF winter conference on applications of computer vision, pp. 697-706. 2021. [Paper Link](https://openaccess.thecvf.com/content/WACV2021/html/Zheng_Global_Table_Extractor_GTE_A_Framework_for_Joint_Table_Identification_WACV_2021_paper.html), [Home Page Link](https://developer.ibm.com/data/fintabnet/).
* Hashmi, Khurram Azeem, Didier Stricker, Marcus Liwicki, Muhammad Noman Afzal, and Muhammad Zeshan Afzal. "Guided table structure recognition through anchor optimization." IEEE Access 9 (2021): 113521-113534.  [Paper Link](https://ieeexplore.ieee.org/document/9508971)
* Nazir, Danish, Khurram Azeem Hashmi, Alain Pagani, Marcus Liwicki, Didier Stricker, and Muhammad Zeshan Afzal. "HybridTabNet: Towards better table detection in scanned document images." Applied Sciences 11, no. 18 (2021): 8396.  [Paper Link]( https://www.mdpi.com/2076-3417/11/18/8396)
  
### Specific Problem 
#### Complex problem
#### Noisy problem
* Zhou, Mengxi, and Rajiv Ramnath. "A Structure-Focused Deep Learning Approach for Table Recognition from Document Images." In 2022 IEEE 46th Annual Computers, Software, and Applications Conference (COMPSAC), pp. 593-601. IEEE, 2022. [Paper Link](https://ieeexplore.ieee.org/document/9842521)
#### Forgetting problem
#### Embedding problem
#### Distorted problem


