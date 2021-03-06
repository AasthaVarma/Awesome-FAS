# Awesome-FAS (Face Anti-Spoofing)

A curated list of Face Anti-Spoofing and related resources. This is inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers), [Awesome-NAS](https://github.com/D-X-Y/Awesome-NAS) and [Awesome-Pruing](https://github.com/he-y/Awesome-Pruning)


Please feel free to pull requests or open an issue to add papers.

## Databases
|  Name  | Publisher | Release year | Attack | Modal|
|:--------|:--------:|:--------:|:--------:|:--------:|
|[CASIA SURF](https://www.researchgate.net/publication/329388462_CASIA-SURF_A_Dataset_and_Benchmark_for_Large-scale_Multi-modal_Face_Anti-spoofing)|CASIA CBSR|2019|2D Attack (Print)|RGB, Depth, Infrared (IR)|
|[ROSE-YOUTU](http://rose1.ntu.edu.sg/datasets/faceLivenessDetection.asp)|ROSE Lab NTU, Singapore & YOUTU Lab, Tencent |2018|2D Attack (Replay, Print), Paper Mask|RGB|
|[OULU-NPU](https://sites.google.com/site/oulunpudatabase/)| OULU University, Finland | 2018|2D Attack (Replay, Print)|RGB|
|[SiW (Spoofing in the Wild)](http://cvlab.cse.msu.edu/spoof-in-the-wild-siw-face-anti-spoofing-database.html)| Michigan State University| 2018 |2D (Replay, Print)|RGB|
|[HKBU-MARs](http://rds.comp.hkbu.edu.hk/mars/)|HKBU|2018|3D MASK|RGB|
|[Multispectral-Spoof Dataset](https://www.idiap.ch/dataset/msspoof)|Idiap Research Institute|2015|2D Attack (Print)|RGB, Near-Infrared, Depth|
|[IDIAP 3D Mask Attack Dataset](https://www.idiap.ch/dataset/3dmad)|Idiap Research Institute|2013|3D Mask|RGB, Depth|
|[IDIAP Replay Attack](https://www.idiap.ch/dataset/replayattack)|Idiap Research Institute|2012|2D Attack (Replay, Print)|RGB|
|[CASIA FASD](http://www.cbsr.ia.ac.cn/english/FASDB_Agreement/Agreement.pdf)| CASIA CBSR |2012|2D Attack (Replay, Print)|RGB|

## Contents
- [Deep-Learning-Based Methods](#Common-CNN-Based-Methods)
- [Traditional Methods](#Traditional-Methods)
- [Domain Generalization](#Domain-Generalization)
- [Zero/few-shot Learning or Anomaly Detection](#Zero/few-shot-Learning-or-Anomaly-Detection)


### Deep-Learning-Based Methods
|  Title  | Venue | Remarks |
|:--------|:--------:|:--------:|
|[Leveraging Shape, Reflectance and Albedo from Shading for Face Presentation Attack Detection](https://www.researchgate.net/publication/340671825_Leveraging_Shape_Reflectance_and_Albedo_from_Shading_for_Face_Presentation_Attack_Detection)|IEEE TIFS 2020|SfS|
|[Searching Central Difference Convolutional Networks for Face Anti-Spoofing](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yu_Searching_Central_Difference_Convolutional_Networks_for_Face_Anti-Spoofing_CVPR_2020_paper.pdf)|CVPR 2020|RGB, NAS|
|[Regularized Fine-grained Meta Face Anti-spoofing](https://arxiv.org/abs/1911.10771)|AAAI 2020|RGB, 2D Attack, Meta Learning, [Code](https://github.com/rshaojimmy/AAAI2020-RFMetaFAS)|
|[Attention-Based Two-Stream Convolutional Networks for Face Spoofing Detection](https://ieeexplore.ieee.org/document/8737949)|IEEE TIFS 2019|RGB, 2D Attack|
|[Biometric Face Presentation Attack Detection with Multi-Channel Convolutional Neural Network](http://publications.idiap.ch/downloads/papers/2019/George_TIFS_2019.pdf)|IEEE TIFS 2019|RGB+IR+Depth, 2D Presentation Attack|
|[Face Anti-Spoofing: Model Matters, So Does Data](http://www.cbsr.ia.ac.cn/users/jwan/papers/CVPR2019-spoofing.pdf)|CVPR 2019|RGB, 2D Attack,data augmentation|
|[A Dataset and Benchmark for Large-scale Multi-modal Face Anti-spoofing](https://yuan-gao.net/pdf/CVPR2019%20-%20antispoofing.pdf)|CVPR 2019|RGB+IR+Depth, 2D Attack|
|[Exploiting temporal and depth information for multi-frame face anti-spoofing](https://arxiv.org/abs/1811.05118)|ArXiv 2018|RGB,  2D Presentation Attack, Multi-frame |
|[Face De-Spoofing: Anti-Spoofing via Noise Modeling](https://arxiv.org/abs/1807.09968)|ECCV 2018|RGB, 2D Attack, pseudo depth, [Code](https://github.com/yaojieliu/ECCV2018-FaceDeSpoofing)|
|[Learning Deep Models for Face Anti-Spoofing: Binary or Auxiliary Supervision](http://cvlab.cse.msu.edu/pdfs/Liu_Jourabloo_Liu_CVPR2018.pdf)|CVPR 2018|RGB, 2D Attack, pseudo depth+rPPG|
|[Face Anti-Spoofing Using Patch and Depth-Based CNNs](http://cvlab.cse.msu.edu/pdfs/FaceAntiSpoofingUsingPatchandDepthBasedCNNs.pdf)|IJCB 2017|RGB, 2D Attack, pseudo depth|

### Traditional Methods
|  Title  | Venue | Remarks|
|:--------|:--------:|:--------:|
|[Face Spoofing Detection Using Colour Texture Analysis](https://www.researchgate.net/publication/301571761_Face_Spoofing_Detection_Using_Colour_Texture_Analysis)|IEEE TIFS 2016|RGB, 2D Attack, Color LBP|
|[Spoofing Face Recognition With 3D Masks](https://www.researchgate.net/publication/262605045_Spoofing_Face_Recognition_With_3D_Masks)|IEEE TIFS 2014|3D Mask|
|[Face Spoofing Detection Through Visual Codebooks of Spectral Temporal Cubes](https://www.researchgate.net/publication/281054869_Face_Spoofing_Detection_Through_Visual_Codebooks_of_Spectral_Temporal_Cubes)|IEEE TIP 2015|RGB, 2D Attack,|
|[Face Spoof Detection with Image Distortion Analysis](http://vipl.ict.ac.cn/uploadfile/upload/2017020711092984.pdf)|IEEE TIFS 2015|RGB, 2D Attack, IDA|
|[Face spoofing detection from single images using texture and local shape analysis](https://ieeexplore.ieee.org/document/6117510)|IJCB 2011|RGB, 2D Presentation Attack, LBP|


### Domain Generalization/Adaptation
|  Title  | Venue | Remarks |
|:--------|:--------:|:--------:|
|[Domain Agnostic Feature Learning for Image and Video Based Face Anti-Spooﬁng](https://arxiv.org/pdf/1912.07124.pdf)|ArXiv 2019|RGB, 2D  Attack|
|[Multi-adversarial Discriminative Deep Domain Generalization for Face Presentation Attack Detection](http://openaccess.thecvf.com/content_CVPR_2019/papers/Shao_Multi-Adversarial_Discriminative_Deep_Domain_Generalization_for_Face_Presentation_Attack_Detection_CVPR_2019_paper.pdf)|CVPR 2019|RGB, 2D Attack,|
|[Learning generalized deep feature representation for face anti-spoofing](https://rose.ntu.edu.sg/Publications/Documents/Face%20Spoofing%20Detection/Learning%20Generalized%20Deep%20Feature%20Representation%20for%20Face%20Anti-Spoofing.pdf)|IEEE TIFS 2018|RGB, 2D Presentation Attack,|
|[Unsupervised domain adaptation for face anti-spoofing](https://ieeexplore.ieee.org/document/8279564)|IEEE TIFS 2018|RGB, 2D Attack, unsupervised domain adaptation|
|[Person-Specific Face Antispoofing With Subject Domain Adaptation](https://ieeexplore.ieee.org/document/7041231)|IEEE TIFS 2015|RGB, 2D Attack, Person-specific|


### Zero/few-shot Learning or Anomaly Detection
|  Title  | Venue | Remarks |
|:--------|:--------:|:--------:|
|[Learning Meta Model for Zero- and Few-shot Face Anti-spoofing](https://arxiv.org/abs/1904.12490)|AAAI 2020|RGB, 2D Presentation Attack, Meta Learning|
|[Deep Tree Learning for Zero-shot Face Anti-Spoofing](http://cvlab.cse.msu.edu/pdfs/Liu_Stehouwer_Jourabloo_Liu_CVPR2019.pdf)|CVPR 2019|RGB, 2D Attack|
|[Deep Anomaly Detection for Generalized Face Anti Spoofing](http://openaccess.thecvf.com/content_CVPRW_2019/papers/CFS/Perez-Cabo_Deep_Anomaly_Detection_for_Generalized_Face_Anti-Spoofing_CVPRW_2019_paper.pdf)|CVPRW 2019|RGB, 2D Attack|


### System / Mobile Applications
|  Title  | Venue | Remarks |
|:--------|:--------:|:--------:|
|[Face Flashing: a Secure Liveness Detection Protocol based on Light Reflections](https://arxiv.org/pdf/1801.01949.pdf)|NDSS 2018|RGB+Flashing|
|[Light Field-Based Face Presentation Attack Detection: Reviewing, Benchmarking and One Step Further](https://ieeexplore.ieee.org/document/8271987)|IEEE TIFS 2018|Light Filed-Based|
|[rtCaptcha: A Real-Time CAPTCHA Based Liveness Detection System](https://pdfs.semanticscholar.org/1fb3/99bf4122b5b25ae7784ca73f9b1be6a91cde.pdf)|NDSS 2018|RGB, Captcha|
|[Face Liveness Detection Using a Flash Against 2D Spoofing Attack](http://www.hebmlc.org/UploadFiles/20171014235219706.pdf)|IEEE TIFS 2017|RGB+Flashing, 2D Attack|
|[Your face your heart: Secure mobile face authentication with photoplethysmograms](https://web.asu.edu/sites/default/files/cnsg/files/c38.pdf)|INFORCOM 2017|RGB, rPPG|
|[Seeing your face is not enough: An inertial sensor-based liveness detection for face authentication](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=3884&context=sis_research)|ACM CCS 2015|RGB+Accelerometer|
|[Sensor-assisted facial recognition: an enhanced biometric authentication system for smartphones](https://dl.acm.org/doi/10.1145/2594368.2594373)|Mobisys 2014|RGB+ Sensors|


### Attack
|  Title  | Venue | Remarks |
|:--------|:--------:|:--------:|
|[Virtual U: Defeating Face Liveness Detection by Building Virtual Models from Your Public Photos](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_xu.pdf)|USENIX SS 2018|VR tech for spoofing|












