# Long-term Visual Tracking: 

This page focuses on watching the state-of-the-art performance for the long-term tracking task (if you are interested in the short-term tracking task, please visit **[here](https://github.com/wangdongdut/Online-Visual-Tracking-SOTA)**). If you are also interested in some resources on Paper Writting (computer vision), please visit **[here](https://github.com/wangdongdut/PaperWriting)**.  

### Survey

* **Chang Liu, Xiao-Fan Chen, Chun-Juan Bo, Dong Wang. [Long-term Visual Tracking: Review and Experimental Comparison](https://link.springer.com/content/pdf/10.1007/s11633-022-1344-1). Machine Intelligence Research, 2022. [[PDF](https://link.springer.com/content/pdf/10.1007/s11633-022-1344-1.pdf)] :star2:** <br />  
* 刘畅，陈晓凡，薄纯娟，王栋. "[长时视觉目标跟踪前沿简介](https://github.com/wangdongdut/Long-term-Visual-Tracking/blob/master/%5B202105%5D%E9%95%BF%E6%97%B6%E8%A7%86%E8%A7%89%E7%9B%AE%E6%A0%87%E8%B7%9F%E8%B8%AA%E5%89%8D%E6%B2%BF%E7%AE%80%E4%BB%8B.pdf)." CAA-PRMI专委会通讯2021年第1期(总第13期). 
  [[PDF](https://github.com/wangdongdut/Long-term-Visual-Tracking/blob/master/%5B202105%5D%E9%95%BF%E6%97%B6%E8%A7%86%E8%A7%89%E7%9B%AE%E6%A0%87%E8%B7%9F%E8%B8%AA%E5%89%8D%E6%B2%BF%E7%AE%80%E4%BB%8B.pdf)] <br />  

## Benchmark Results:
  
* **OxUvA:star2:**
     | Tracker                   | MaxGM    | Speed (fps) | Paper/Code |
     |:-----------               |:----------------:|:----------------:|:----------------:|
     | KeepTrack (ICCV21)        | 0.809  |  18 (RTX 2080Ti)  |   [Paper](https://arxiv.org/abs/2103.16556)/[Code](https://github.com/visionml/pytracking) |  
     | **LTMU (CVPR20)**         | 0.751  |  13 (RTX 2080Ti)  |   [Paper](https://arxiv.org/abs/2004.00305)/[Code](https://github.com/Daikenan/LTMU) |
     | Siam R-CNN (CVPR20)       | 0.723  |  5 (Tesla V100) |   [Paper](https://arxiv.org/pdf/1911.12836.pdf)/[Code](https://github.com/VisualComputingInstitute/SiamR-CNN) |       
     | DMTrack (CVPR21)          | 0.688  |  31 (Titan XP)    |   [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Distractor-Aware_Fast_Tracking_via_Dynamic_Convolutions_and_MOT_Philosophy_CVPR_2021_paper.pdf)/[Project](https://github.com/hqucv/dmtrack)  |
     | **SPLT (ICCV19)**         | 0.622  |  26 (GTX 1080Ti)       |      [Paper](http://openaccess.thecvf.com/content_ICCV_2019/papers/Yan_Skimming-Perusal_Tracking_A_Framework_for_Real-Time_and_Robust_Long-Term_Tracking_ICCV_2019_paper.pdf)/[Code](https://github.com/iiau-tracker/SPLT) | 
     | GlobalTrack (AAAI20)      | 0.603  |  6 (GTX TitanX)   |   [Paper](https://arxiv.org/abs/1912.08531)/[Code](https://github.com/huanglianghua/GlobalTrack) |    
     | **MBMD (Arxiv)**          | 0.544  |  4 (GTX 1080Ti)   |   [Paper](https://arxiv.org/abs/1809.0432)/[Code](https://github.com/xiaobai1217/MBMD) |          
     | SiamFC+R (ECCV18)         | 0.454  |  52 (Unkown GPU) |   [Paper](https://arxiv.org/pdf/1803.09502.pdf)/[Code](https://github.com/oxuva/long-term-tracking-benchmark) |

     * OxUvA Leaderboard: https://competitions.codalab.org/competitions/19529#results
     * SiamFC+R is the best tracker in the original [OxUvA](https://arxiv.org/pdf/1803.09502.pdf) paper.

* **TLP:star2:**

     | Tracker                   | Success Score    | Speed (fps) | Paper/Code |
     |:-----------               |:----------------:|:----------------:|:----------------:|
     | **LTMU (CVPR20)**         | 0.571  |  13 (RTX 2080Ti)  |   [Paper](https://arxiv.org/abs/2004.00305)/[Code](https://github.com/Daikenan/LTMU) |
     | DMTrack (CVPR21)          | 0.541  |  31 (Titan XP)    |   [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Distractor-Aware_Fast_Tracking_via_Dynamic_Convolutions_and_MOT_Philosophy_CVPR_2021_paper.pdf)/[Project](https://github.com/hqucv/dmtrack)  |
     | GlobalTrack (AAAI20)      | 0.520  |  6 (GTX TitanX)   |   [Paper](https://arxiv.org/abs/1912.08531)/[Code](https://github.com/huanglianghua/GlobalTrack) |
     | **SPLT (ICCV19)**         | 0.416  |  26 (GTX 1080Ti)       |      [Paper](http://openaccess.thecvf.com/content_ICCV_2019/papers/Yan_Skimming-Perusal_Tracking_A_Framework_for_Real-Time_and_Robust_Long-Term_Tracking_ICCV_2019_paper.pdf)/[Code](https://github.com/iiau-tracker/SPLT) |
     | MDNet (CVPR16)            | 0.372  |  5 (GTX 1080Ti)       | [Paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Nam_Learning_Multi-Domain_Convolutional_CVPR_2016_paper.pdf)/[Code](https://github.com/hyeonseobnam/py-MDNet) |

     * MDNet is the best tracker in the original [TLP](https://amoudgl.github.io/tlp/) paper.
  
* **LaSOT:star2:**

     | Tracker                   | Success Score    | Speed (fps) | Paper/Code |
     |:-----------               |:----------------:|:----------------:|:----------------:|
     | **STARK (ICCV21)**        | 0.671  |  32 (Tesla V100)  |   [Paper](https://arxiv.org/abs/2103.17154)/[Code](https://github.com/researchmm/Stark) |     
     | KeepTrack (ICCV21)        | 0.671  |  18 (RTX 2080Ti)  |   [Paper](https://arxiv.org/abs/2103.16556)/[Code](https://github.com/visionml/pytracking) |  
     | **ARDiMPsuper (CVPR21)**  | 0.653  |  33 (RTX 2080Ti)  |   [Paper](https://arxiv.org/abs/2012.06815)/[Code](https://github.com/MasterBin-IIAU/AlphaRefine) |
     | **TransT (CVPR21)**       | 0.649  |  50 (RTX 2080Ti)  |   [Paper](https://arxiv.org/abs/2103.15436)/[Code](https://github.com/chenxin-dlut/TransT) |
     | Siam R-CNN (CVPR20)       | 0.648  |  5 (Tesla V100)   |   [Paper](https://arxiv.org/pdf/1911.12836.pdf)/[Code](https://github.com/VisualComputingInstitute/SiamR-CNN) |
     | TrDimp (CVPR21)           | 0.639  |  26 (GTX 1080Ti)  |   [Paper](https://arxiv.org/abs/2103.11681)/[Code](https://github.com/594422814/TransformerTrack) |
     | PrDiMP50 (CVPR20)         | 0.598  |  30 (Unkown GPU)  |   [Paper](https://arxiv.org/pdf/2003.12565.pdf)/[Code](https://github.com/visionml/pytracking)  |
     | DMTrack (CVPR21)          | 0.580  |  31 (Titan XP)    |   [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Distractor-Aware_Fast_Tracking_via_Dynamic_Convolutions_and_MOT_Philosophy_CVPR_2021_paper.pdf)/[Project](https://github.com/hqucv/dmtrack)  |
     | **LTMU (CVPR20)**         | 0.572  |  13 (RTX 2080Ti)  |   [Paper](https://arxiv.org/abs/2004.00305)/[Code](https://github.com/Daikenan/LTMU) |
     | DiMP50 (ICCV19)           | 0.568  |  43 (GTX 1080)    |   [Paper](https://arxiv.org/pdf/1904.07220.pdf)/[Code](https://github.com/visionml/pytracking)  |
     | Ocean (ECCV20)            | 0.560  |  25 (Tesla V100)  |   [Paper](https://arxiv.org/abs/2006.10721)/[Code](https://github.com/researchmm/TracKit) |  
     | GlobalTrack (AAAI20)      | 0.521  |  6 (GTX TitanX)   |   [Paper](https://arxiv.org/abs/1912.08531)/[Code](https://github.com/huanglianghua/GlobalTrack) |
     | **SPLT (ICCV19)**         | 0.426  |  26 (GTX 1080Ti)       |      [Paper](http://openaccess.thecvf.com/content_ICCV_2019/papers/Yan_Skimming-Perusal_Tracking_A_Framework_for_Real-Time_and_Robust_Long-Term_Tracking_ICCV_2019_paper.pdf)/[Code](https://github.com/iiau-tracker/SPLT) |
     | MDNet (CVPR16)            | 0.397  |  5 (GTX 1080Ti)       | [Paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Nam_Learning_Multi-Domain_Convolutional_CVPR_2016_paper.pdf)/[Code](https://github.com/hyeonseobnam/py-MDNet) |

     * **Baseline(short-term): SiamRPN++, Ocean, DiMP, PrDiMP, Siam R-CNN, MDNet**
     * **Baseline(long-term): SPLT, GlobalTrack, LTMU, Siam R-CNN** 
     * MDNet is the best tracker in the original [LaSOT](https://cis.temple.edu/lasot/) paper. 
     * **[paperswithcode-SOTA](https://paperswithcode.com/sota/visual-object-tracking-on-lasot): https://paperswithcode.com/sota/visual-object-tracking-on-lasot**

* **Previous Benchmark Results**

## Benchmark

* **List:**

     | Datasets       | #videos    | #total/min/max/average frames|Absent Label| 
     |:-----------    |:----------------:|:----------------:|:----------------:|
     | [VOT2019-LT/VOT2020-LT/VOT2021-LT](https://www.votchallenge.net/)          | **50**          |      XXXX/XXXX/XXXX/XXXX     |  Yes |  
     | [TLP](https://amoudgl.github.io/tlp/)          | **50**          |      XXXX/XXXX/XXXX/XXXX     |  No |  
     | [OxUvA](https://oxuva.github.io/long-term-tracking-benchmark/)          | 366 (dev-200/test-**166**)         |     XXXX/XXXX/XXXX/XXXX     |  Yes | 
     | [LaSOT](https://cis.temple.edu/lasot/)          | 1,400 (I-all-1,400/II-test-**280**)      |      3.52M/1,000/11,397/2,506 |  Yes |
     
     * [UAV-20L](https://uav123.org/) has been included in VOT2018-LT/VOT2019-LT/VOT2020-LT. 
     * [VOT2018-LT](http://www.votchallenge.net/vot2018/) is a subset of VOT2019-LT/VOT2020-LT/VOT2021-LT. VOT2019-LT, VOT2020-LT and VOT2021-LT are same. 

* **VOT:** . [[Visual Object Tracking Challenge](http://www.votchallenge.net/)]
  * [[VOT2021LT](http://www.votchallenge.net/vot2021/)][[Report](http://prints.vicos.si/publications/384/)]  
  * [[VOT2020LT](http://www.votchallenge.net/vot2020/)][[Report](http://prints.vicos.si/publications/384/)]   
  * [[VOT2019LT](http://www.votchallenge.net/vot2019/)][[Report](http://prints.vicos.si/publications/375/)]
  * [[VOT2018LT](http://www.votchallenge.net/vot2018/)][[Report](http://prints.vicos.si/publications/365/)]

* **OxUvA:** Jack Valmadre, Luca Bertinetto, João F. Henriques, Ran Tao, Andrea Vedaldi, Arnold Smeulders, Philip Torr, Efstratios Gavves. <br />
  "Long-term Tracking in the Wild: a Benchmark." ECCV (2018).
  [[paper](https://arxiv.org/pdf/1803.09502.pdf)]
  [[project](https://oxuva.github.io/long-term-tracking-benchmark/)]
  
* **TLP:** Abhinav Moudgil, Vineet Gandhi. <br />
  "Long-term Visual Object Tracking Benchmark." ACCV (2018).
  [[paper](https://arxiv.org/abs/1712.01358)]
  [[project](https://amoudgl.github.io/tlp/)] 
  
* **CDTB:** Alan Lukežič, Ugur Kart, Jani Käpylä, Ahmed Durmush, Joni-Kristian Kämäräinen, Jiří Matas, Matej Kristan. <br />
  "CDTB: A Color and Depth Visual Object Tracking Dataset and Benchmark." ICCV (2019).
  [[paper](http://openaccess.thecvf.com/content_ICCV_2019/papers/Lukezic_CDTB_A_Color_and_Depth_Visual_Object_Tracking_Dataset_and_ICCV_2019_paper.pdf)]
  **`RGB-D Long-term`**  
  
* **LaSOT:** Heng Fan, Liting Lin, Fan Yang, Peng Chu, Ge Deng, Sijia Yu, Hexin Bai, Yong Xu, Chunyuan Liao, Haibin Ling. <br />
  "LaSOT: A High-quality Benchmark for Large-scale Single Object Tracking." CVPR (2019). 
  [[paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Fan_LaSOT_A_High-Quality_Benchmark_for_Large-Scale_Single_Object_Tracking_CVPR_2019_paper.pdf)]
  [[project](https://cis.temple.edu/lasot/)]  <br />
  `The LaSOT dataset is not a typical long-term dataset. But it is a good choice for connecting long-term and short-term trackers. Usually, short-term trackers drift very easily in the long-term datasets since they have no re-detection module. Long-term trackers also achieve unsatisfactory performance in the short-term datasets, since the tested sequences are often very short and the evaluation criterion pay less attention to the re-detection capability (especially VOT' EAO). LaSOT is a large-scale, long-frame dataset with precision and succuess criterion. Thus, it is a good choice if you want to fairly compare the performance of long-term and short-term trackers in one figure/table.`
  
* **UAV20L:** Matthias Mueller, Neil Smith and Bernard Ghanem. <br />
  "A Benchmark and Simulator for UAV Tracking." ECCV (2016).
  [[paper](https://ivul.kaust.edu.sa/Documents/Publications/2016/A%20Benchmark%20and%20Simulator%20for%20UAV%20Tracking.pdf)]
  [[project](https://ivul.kaust.edu.sa/Pages/pub-benchmark-simulator-uav.aspx)]
  [[dataset](https://ivul.kaust.edu.sa/Pages/Dataset-UAV123.aspx)]  <br />
  `All 20 videos of UAV20L have been included in the VOT2018LT dataset.`

### Recent Long-term Trackers

* **STARK: Bin Yan, Houwen Peng, Jianlong Fu, Dong Wang, Huchuan Lu.** <br />
  "Learning Spatio-Temporal Transformer for Visual Tracking."  ICCV, 2021. 
  [[Paper](https://arxiv.org/abs/2103.17154)]
  [[Code](https://github.com/researchmm/Stark)] <br /> 

* **KeepTrack: Christoph Mayer, Martin Danelljan, Danda Pani Paudel, Luc Van Gool.** <br />
  "Learning Target Candidate Association to Keep Track of What Not to Track." ICCV (2021). 
  [[Paper](https://arxiv.org/abs/2103.16556)]
  [[Project](https://github.com/visionml/pytracking)] <br />  

* **DMTrack: Zikai Zhang, Bineng Zhong, Shengping Zhang, Zhenjun Tang, Xin Liu, Zhaoxiang Zhang.** <br />
  "Distractor-Aware Fast Tracking via Dynamic Convolutions and MOT Philosophy." CVPR (2021). 
  [[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Distractor-Aware_Fast_Tracking_via_Dynamic_Convolutions_and_MOT_Philosophy_CVPR_2021_paper.pdf)]
  [[Project](https://github.com/hqucv/dmtrack)] <br />  

* **LTMU: Kenan Dai, Yunhua Zhang, Dong Wang, Jianhua Li, Huchuan Lu, Xiaoyun Yang.** <br />
  **High-Performance Long-Term Tracking with Meta-Updater. CVPR (2020).** 
  [[Paper](https://arxiv.org/abs/2004.00305)]
  [[Code](https://github.com/Daikenan/LTMU)] <br />
  **VOT2019-LT Winner**:star2:,  **VOT2020-LT Winner**:star2: <br />
  `1. This work is an improved version of the VOT2019-LT winner, `**[[LT_DSE](https://github.com/Daikenan/LT_DSE)]**. <br />
  `2. The baseline version is the VOT2020-LT winner, `**[[LTMU_B](https://github.com/Daikenan/LTMU)]**.
  
* **Siam R-CNN:** Paul Voigtlaender, Jonathon Luiten, Philip H.S. Torr, Bastian Leibe. <br />
  "Siam R-CNN: Visual Tracking by Re-Detection." CVPR (2020).
  [[Paper](https://arxiv.org/pdf/1911.12836.pdf)]
  [[Code](https://github.com/VisualComputingInstitute/SiamR-CNN)]
  [[Project](https://www.vision.rwth-aachen.de/page/siamrcnn)] 
  
* **TACT:** Janghoon Choi, Junseok Kwon, Kyoung Mu Lee. <br />
  "Visual Tracking by TridentAlign and Context Embeddin." ACCV (2020).
  [[Paper](https://arxiv.org/pdf/2007.06887.pdf)]
  [[Code](https://github.com/JanghoonChoi/TACT)]
  
* **DAL:** Yanlin Qian, Alan Lukežič, Matej Kristan, Joni-Kristian Kämäräinen, Jiri Mata <br /> 
  "DAL - A Deep Depth-aware Long-term Tracker" ICPR (2020).   [[paper](https://arxiv.org/pdf/1912.00660.pdf)] **`RGB-D Long-term`**
 
* **GlobalTrack:** Lianghua Huang, Xin Zhao, Kaiqi Huang. <br />
  "GlobalTrack: A Simple and Strong Baseline for Long-term Tracking." AAAI (2020).
  [[Paper](https://arxiv.org/abs/1912.08531)]
  [[Code](https://github.com/huanglianghua/GlobalTrack)]

* **SPLT: Bin Yan, Haojie Zhao, Dong Wang, Huchuan Lu, Xiaoyun Yang.** <br /> 
  **"Skimming-Perusal' Tracking: A Framework for Real-Time and Robust Long-Term Tracking." ICCV (2019).**
  [[Paper](http://openaccess.thecvf.com/content_ICCV_2019/papers/Yan_Skimming-Perusal_Tracking_A_Framework_for_Real-Time_and_Robust_Long-Term_Tracking_ICCV_2019_paper.pdf)]
  [[Code](https://github.com/iiau-tracker/SPLT)] <br />   **An improved (much faster) version of VOT2018-LT Winner**:star2:
  
* **flow_MDNet_RPN:** Han Wu, Xueyuan Yang, Yong Yang, Guizhong Liu. <br />
  "Flow Guided Short-term Trackers with Cascade Detection for Long-term Tracking." ICCVW (2019).
  [[Paper](http://openaccess.thecvf.com/content_ICCVW_2019/papers/VISDrone/Wu_Flow_Guided_Short-Term_Trackers_with_Cascade_Detection_for_Long-Term_Tracking_ICCVW_2019_paper.pdf)] 
  
* **OTR:** Ugur Kart, Alan Lukezic, Matej Kristan, Joni-Kristian Kamarainen, Jiri Matas. <br />
  "Object Tracking by Reconstruction with View-Specific Discriminative Correlation Filters." CVPR (2019). 
  [[Paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kart_Object_Tracking_by_Reconstruction_With_View-Specific_Discriminative_Correlation_Filters_CVPR_2019_paper.pdf)]
  [[Code](https://github.com/ugurkart/OTR)] **`RGB-D Long-term`**
  
* **SiamRPN++:** Bo Li, Wei Wu, Qiang Wang, Fangyi Zhang, Junliang Xing, Junjie Yan. 
  "SiamRPN++: Evolution of Siamese Visual Tracking with Very Deep Networks." CVPR (2019).
  [[Paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Li_SiamRPN_Evolution_of_Siamese_Visual_Tracking_With_Very_Deep_Networks_CVPR_2019_paper.pdf)]
  [[Code](https://github.com/STVIR/pysot)]
  
* **MBMD: Yunhua Zhang, Dong Wang, Lijun Wang, Jinqing Qi, Huchuan Lu.** <br />
  **"Learning regression and verification networks for long-term visual tracking." Arxiv (2018).** <br />
  [[Paper](https://arxiv.org/abs/1809.04320)]
  [[Code](https://github.com/xiaobai1217/MBMD)]
  [[Journal Version](https://link.springer.com/article/10.1007/s11263-021-01487-3)]
  **VOT2018-LT Winner**:star2: 
  
* **MMLT:** Hankyeol Lee, Seokeon choi, Changick Kim. <br /> 
  "A Memory Model based on the Siamese Network for Long-term Tracking." ECCVW (2018). 
  [[Paper](http://openaccess.thecvf.com/content_ECCVW_2018/papers/11129/Lee_A_Memory_Model_based_on_the_Siamese_Network_for_Long-term_ECCVW_2018_paper.pdf)]
  [[Code](https://github.com/bismex/MMLT)] 
 
* **FuCoLoT:** Alan Lukežič, Luka Čehovin Zajc, Tomáš Vojíř, Jiří Matas and Matej Kristan. <br /> 
  "FuCoLoT - A Fully-Correlational Long-Term Tracker." ACCV (2018). 
  [[Paper](http://prints.vicos.si/publications/366)]
  [[Code](https://github.com/alanlukezic/fucolot)] 
  
### Long-term Trackers modified from Short-term Ones

* **SiamDW:** Zhipeng Zhang, Houwen Peng. <br /> 
  "Deeper and Wider Siamese Networks for Real-Time Visual Tracking." CVPR (2019). 
  [[Paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Deeper_and_Wider_Siamese_Networks_for_Real-Time_Visual_Tracking_CVPR_2019_paper.pdf)]
  [[Code](https://github.com/researchmm/SiamDW)] **VOT2019 RGB-D Winner**:star2: 
  Denoted as "SiamDW_D" "SiamDW_LT", see the VOT2019 official report
  [[vot2019code](https://github.com/researchmm/VOT2019)]
  
* **DaSiam_LT:** Zheng Zhu, Qiang Wang, Bo Li, Wei Wu, Junjie Yan, Weiming Hu. <br /> 
  "Distractor-Aware Siamese Networks for Visual Object Tracking." ECCV (2018). 
  [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Zheng_Zhu_Distractor-aware_Siamese_Networks_ECCV_2018_paper.pdf)]
  [[code](https://github.com/foolwood/DaSiamRPN)] **VOT2018-LT Runner-up**:star2:

  
### Early Long-term Trackers (before 2018)

* **PTAV:** Heng Fan, Haibin Ling. <br />
  "Parallel Tracking and Verifying: A Framework for Real-Time and High Accuracy Visual Tracking." ICCV (2017).  <br />
  [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Fan_Parallel_Tracking_and_ICCV_2017_paper.pdf)]
  [[supp](http://openaccess.thecvf.com/content_ICCV_2017/supplemental/Fan_Parallel_Tracking_and_ICCV_2017_supplemental.pdf)]
  [[project](http://www.dabi.temple.edu/~hbling/code/PTAV/ptav.htm)]
  [[code](http://www.dabi.temple.edu/~hbling/code/PTAV/serial_ptav_v1.zip)]

* **EBT:** Gao Zhu, Fatih Porikli, Hongdong Li. <br />
  "Beyond Local Search: Tracking Objects Everywhere with Instance-Specific Proposals." CVPR (2016).  <br />
  [[paper](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Zhu_Beyond_Local_Search_CVPR_2016_paper.pdf)]
  [[exe](http://www.votchallenge.net/vot2016/download/02_EBT.zip)]

* **LCT:** Chao Ma, Xiaokang Yang, Chongyang Zhang, Ming-Hsuan Yang. <br />
  "Long-term Correlation Tracking." CVPR (2015). <br />
  [[paper](http://openaccess.thecvf.com/content_cvpr_2015/papers/Ma_Long-Term_Correlation_Tracking_2015_CVPR_paper.pdf)]
  [[project](https://sites.google.com/site/chaoma99/cvpr15_tracking)]
  [[github](https://github.com/chaoma99/lct-tracker)]
  
* **MUSTer:** Zhibin Hong, Zhe Chen, Chaohui Wang, Xue Mei, Danil Prokhorov, Dacheng Tao. <br />
  "MUlti-Store Tracker (MUSTer): a Cognitive Psychology Inspired Approach to Object Tracking." CVPR (2015). <br />
  [[paper](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Hong_MUlti-Store_Tracker_MUSTer_2015_CVPR_paper.pdf)]
  [[project](https://sites.google.com/site/zhibinhong4131/Projects/muster)]  
  
* **CMT:** Georg Nebehay, Roman Pflugfelder. <br />
  "Clustering of Static-Adaptive Correspondences for Deformable Object Tracking." CVPR (2015).  <br />
  [[paper](https://zpascal.net/cvpr2015/Nebehay_Clustering_of_Static-Adaptive_2015_CVPR_paper.pdf)]
  [[project](http://www.gnebehay.com/cmt)] [[github](https://github.com/gnebehay/CMT)]
  
* **SPL:** James Steven Supančič III, Deva Ramanan. <br />
  "Self-paced Learning for Long-term Tracking." CVPR (2013).  <br />
  [[paper](https://www.cv-foundation.org/openaccess/content_cvpr_2013/papers/Supancic_III_Self-Paced_Learning_for_2013_CVPR_paper.pdf)]
  [[github](https://github.com/jsupancic/SPLTT-Release)]  
 
 * **TLD:** Zdenek Kalal, Krystian Mikolajczyk, Jiri Matas. <br />
  "Tracking-Learning-Detection." TPAMI (2012). <br />
  [[paper](https://ieeexplore.ieee.org/document/6104061)]
  [[project](https://github.com/zk00006/OpenTLD)]

## Measurement & Discussion:   

* Alan Lukežič, Luka Čehovin Zajc, Tomáš Vojíř, Jiří Matas, Matej Krista.
  "Performance Evaluation Methodology for Long-Term Visual Object Tracking." ArXiv (2019).
  [[paper](https://arxiv.org/abs/1906.08675)]

* Alan Lukežič, Luka Čehovin Zajc, Tomáš Vojíř, Jiří Matas, Matej Kristan. 
  "Now You See Me: Evaluating Performance in Long-term Visual Tracking." ArXiv (2018).
  [[paper](https://arxiv.org/abs/1804.07056)]
  
* Shyamgopal Karthik, Abhinav Moudgil, Vineet Gandhi.
  "Exploring 3 R's of Long-term Tracking: Re-detection, Recovery and Reliability." WACV (2020). 
  [[paper](http://openaccess.thecvf.com/content_WACV_2020/papers/Karthik_Exploring_3_Rs_of_Long-term_Tracking_Redetection_Recovery_and_Reliability_WACV_2020_paper.pdf)]
  
  
  
## Previous Benchmark Results: 
  
 * **~~VOT2019-LT/VOT2020-LT/VOT2021-LT~~**

     | Tracker                   | F-Score    | Speed (fps) | Paper/Code |
     |:-----------               |:----------------:|:----------------:|:----------------:|
     | KeepTrack (ICCV21)        | 0.709  |  18 (RTX 2080Ti)  |   [Paper](https://arxiv.org/abs/2103.16556)/[Code](https://github.com/visionml/pytracking) |  
     | **STARK (ICCV21)**        | 0.701  |  32 (Tesla V100)  |   [Paper](https://arxiv.org/abs/2103.17154)/[Code](https://github.com/researchmm/Stark) |  
     | **LTMU (CVPR20)**         | 0.697  |  13 (RTX 2080Ti)  |   [Paper](https://arxiv.org/abs/2004.00305)/[Code](https://github.com/Daikenan/LTMU) |
     | **LT_DSE**                | 0.695  | N/A  |   N/A |
     | **LTMU_B**                | 0.691  | N/A  |   [Paper](https://arxiv.org/abs/2004.00305)/[Code](https://github.com/Daikenan/LTMU) | 
     | DMTrack (CVPR21)          | 0.687  |  31 (Titan XP)    |   [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Distractor-Aware_Fast_Tracking_via_Dynamic_Convolutions_and_MOT_Philosophy_CVPR_2021_paper.pdf)/[Project](https://github.com/hqucv/dmtrack)  |
     | Megtrack                  | 0.687  | N/A  |   N/A |
     | CLGS                      | 0.674  | N/A  |   N/A |
     | SiamDW_LT                 | 0.665  | N/A  |   N/A |
     | **SPLT (ICCV19)**         | 0.587  |  26 (GTX 1080Ti)  |   [Paper](http://openaccess.thecvf.com/content_ICCV_2019/papers/Yan_Skimming-Perusal_Tracking_A_Framework_for_Real-Time_and_Robust_Long-Term_Tracking_ICCV_2019_paper.pdf)/[Code](https://github.com/iiau-tracker/SPLT) |
     | mbdet                     | 0.567  | N/A  |   N/A |    
     | SiamRPNsLT                | 0.556  | N/A  |   N/A |     
     | Siamfcos-LT               | 0.520  | N/A  |   N/A |
     | CooSiam                   | 0.508  | N/A  |   N/A |    
     | ASINT                     | 0.505  | N/A  |   N/A |     
     | FuCoLoT                   | 0.411  | N/A  |   N/A |
     
     * Most results are obtained from the original [VOT2019](http://prints.vicos.si/publications/375/) and [VOT2020](http://prints.vicos.si/publications/375/) reports. 
     * All sequences and settings are same in the VOT2019-LT, VOT2020-LT  and VOT2021-LT challenges.  
     * We will not update the results [marked by 2022-11]. Please focus on VOT2022-LT. 

* **~~VOT2018-LT:~~**

     | Tracker                   | F-Score    | Speed (fps) | Paper/Code |
     |:-----------               |:----------------:|:----------------:|:----------------:|
     | **LTMU (CVPR20)**         | 0.690  |  13 (RTX 2080Ti)  |   [Paper](https://arxiv.org/abs/2004.00305)/[Code](https://github.com/Daikenan/LTMU) |
     | Siam R-CNN (CVPR20)       | 0.668  |  5 (Tesla V100)   |   [Paper](https://arxiv.org/pdf/1911.12836.pdf)/[Code](https://github.com/VisualComputingInstitute/SiamR-CNN) |
     | PG-Net (ECCV20)           | 0.642  |  N/A              | [Paper]()/[Code]()|
     | SiamRPN++                 | 0.629  |  35 (Titan XP)    |   [Paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Li_SiamRPN_Evolution_of_Siamese_Visual_Tracking_With_Very_Deep_Networks_CVPR_2019_paper.pdf)/[Code](https://github.com/STVIR/pysot) |
     | **SPLT (ICCV19)**         | 0.622  |  26 (GTX 1080Ti)  |   [Paper](http://openaccess.thecvf.com/content_ICCV_2019/papers/Yan_Skimming-Perusal_Tracking_A_Framework_for_Real-Time_and_Robust_Long-Term_Tracking_ICCV_2019_paper.pdf)/[Code](https://github.com/iiau-tracker/SPLT) | 
     | **MBMD (Arxiv)**          | 0.610  |  4 (GTX 1080Ti)   |   [Paper](https://arxiv.org/abs/1809.0432)/[Code](https://github.com/xiaobai1217/MBMD) |          
     | DaSiam_LT (ECCV18)        | 0.607  |  110 (TITAN X)    |   [Paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Zheng_Zhu_Distractor-aware_Siamese_Networks_ECCV_2018_paper.pdf)/[Code](https://github.com/foolwood/DaSiamRPN) |

     * MBMD and DaSiam_LT is the winner and runner-up in the original [VOT2018_LT](http://prints.vicos.si/publications/365/) report.    
     * VOT2018-LT is a subset of VOT2019-LT; thus, we will not update the results [marked by 2021-08].  
