
# Contents
- [Awesome Attacks on Machine Learning Privacy   ![Awesome](https://awesome.re)](#awesome-attacks-on-machine-learning-privacy-img-srchttpsawesomerebadgesvg-altawesome)
- [Contents](#contents)
- [Surveys and Overviews](#surveys-and-overviews)
- [Privacy Testing Tools](#privacy-testing-tools)
- [Papers and Code](#papers-and-code)
  - [Membership inference](#membership-inference)
  - [Reconstruction](#reconstruction)
  - [Property inference](#property-inference)
  - [Model extraction](#model-extraction)
- [Other](#other)

# Surveys and Overviews
- [**A Survey of Privacy Attacks in Machine Learning**](https://arxiv.org/abs/2007.07646) (Rigaki and Garcia, 2020)
- [**An Overview of Privacy in Machine Learning**](https://arxiv.org/pdf/2005.08679) (De Cristofaro, 2020)
- [**Rethinking Privacy Preserving Deep Learning: How to Evaluate and Thwart Privacy Attacks**](https://arxiv.org/abs/2006.11601) (Fan et al., 2020)
- [**Privacy and Security Issues in Deep Learning: A Survey**](https://ieeexplore.ieee.org/abstract/document/9294026) (Liu et al., 2021)

# Privacy Testing Tools
- [**PrivacyRaven**](https://github.com/trailofbits/PrivacyRaven) (Trail of Bits)
- [**TensorFlow Privacy**](https://github.com/tensorflow/privacy/tree/master/tensorflow_privacy/privacy/membership_inference_attack) (TensorFlow)
- [**Machine Learning Privacy Meter**](https://github.com/privacytrustlab/ml_privacy_meter) (NUS Data Privacy and Trustworthy Machine Learning Lab)
- [**CypherCat (archive-only)**](https://github.com/Lab41/cyphercat) (IQT Labs/Lab 41)
- [**Adversarial Robustness Toolbox (ART)**](https://github.com/Trusted-AI/adversarial-robustness-toolbox) (IBM)
 
# Papers and Code

## Membership inference
- [**Membership inference attacks against machine learning models**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7958568) (Shokri et al., 2017) ([code](https://github.com/csong27/membership-inference))
- [**Understanding membership inferences on well-generalized learning models**](https://arxiv.org/pdf/1802.04889)(Long et al., 2018)
- [**Privacy risk in machine learning: Analyzing the connection to overfitting**](https://ieeexplore.ieee.org/document/8429311), (Yeom et al., 2018) ([code](https://github.com/samuel-yeom/ml-privacy-csf18))
- [**Membership inference attack against differentially private deep learning model**](http://www.tdp.cat/issues16/tdp.a289a17.pdf) (Rahman et al., 2018)
- [**Comprehensive privacy analysis of deep learning: Passive and active white-box inference attacks against centralized and federated learning.**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8835245) (Nasr et al., 2019) ([code](https://github.com/privacytrustlab/ml_privacy_meter))
- [**Logan: Membership inference attacks against generative models.**](https://content.sciendo.com/downloadpdf/journals/popets/2019/1/article-p133.xml) (Hayes et al. 2019) ([code](https://github.com/jhayes14/gen_mem_inf))
- [**Evaluating differentially private machine learning in practice**](https://www.usenix.org/system/files/sec19-jayaraman.pdf) (Jayaraman and Evans, 2019) ([code](https://github.com/bargavj/EvaluatingDPML)) 
- [**Ml-leaks: Model and data independent membership inference attacks and defenses on machine learning models**](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_03A-1_Salem_paper.pdf) (Salem et al., 2019) ([code](https://github.com/AhmedSalem2/ML-Leaks))
- [**Privacy risks of securing machine learning models against adversarial examples**](https://dl.acm.org/doi/pdf/10.1145/3319535.3354211) (Song L. et al., 2019) ([code](https://github.com/inspire-group/privacy-vs-robustness))
- [**White-box vs Black-box: Bayes Optimal Strategies for Membership Inference**](http://proceedings.mlr.press/v97/sablayrolles19a.html) (Sablayrolles et al., 2019)
- [**Privacy risks of explaining machine learning models**](https://arxiv.org/abs/1907.00164) (Shokri et al., 2019)
- [**Demystifying membership inference attacks in machine learning as a service**](https://ieeexplore.ieee.org/abstract/document/8634878) (Truex et al., 2019)
- [**Monte carlo and reconstruction membership inference attacks against generative models**](https://content.sciendo.com/view/journals/popets/2019/4/article-p232.xml) (Hilprecht et al., 2019)
- [**MemGuard: Defending against Black-Box Membership Inference Attacks via Adversarial Examples**](https://arxiv.org/abs/1909.10594) (Jia et al., 2019) ([code](https://github.com/jjy1994/MemGuard))
- [**Gan-leaks: A taxonomy of membership inference attacks against gans**](https://arxiv.org/pdf/1909.03935.pdf) (Chen,et al., 2019))
- [**Auditing Data Provenance in Text-Generation Models**](https://dl.acm.org/doi/pdf/10.1145/3292500.3330885) (Song and Shmatikov, 2019)
- [**Membership Inference Attacks on Sequence-to-Sequence Models: Is My Data In Your Machine Translation System?**](https://www.mitpressjournals.org/doi/full/10.1162/tacl_a_00299) (Hisamoto et al., 2020) 
- [**Revisiting Membership Inference Under Realistic Assumptions**](https://arxiv.org/pdf/2005.10881.pdf) (Jayaraman et al., 2020)
- [**When Machine Unlearning Jeopardizes Privacy**](https://arxiv.org/pdf/2005.02205.pdf) (Chen et al., 2020)
- [**Modelling and Quantifying Membership Information Leakage in Machine Learning**](https://arxiv.org/pdf/2001.10648.pdf) (Farokhi and Kaafar, 2020)
- [**Systematic Evaluation of Privacy Risks of Machine Learning Models**](https://arxiv.org/abs/2003.10595) (Song and Mittal, 2020) ([code](https://github.com/inspire-group/membership-inference-evaluation))
- [**Towards the Infeasibility of Membership Inference on Deep Models**](https://arxiv.org/pdf/2005.13702.pdf) (Rezaei and Liu, 2020) ([code](https://github.com/shrezaei/MI-Attack))
- [**Stolen Memories: Leveraging Model Memorization for Calibrated White-Box Membership Inference**](https://arxiv.org/abs/1906.11798) (Leino and Fredrikson, 2020) 
- [**Label-Only Membership Inference Attacks**](https://arxiv.org/abs/2007.14321) (Choquette Choo et al., 2020) 
- [**Label-Leaks: Membership Inference Attack with Label**](https://arxiv.org/abs/2007.15528) (Li and Zhang, 2020) 
- [**Alleviating Privacy Attacks via Causal Learning**](https://arxiv.org/abs/1909.12732) (Tople et al., 2020)
- [**On the Effectiveness of Regularization Against Membership Inference Attacks**](https://arxiv.org/abs/2006.05336) (Kaya et al., 2020)
- [**Sampling Attacks: Amplification of Membership Inference Attacks by Repeated Queries**](https://arxiv.org/abs/2009.00395) (Rahimian et al., 2020)
- [**Segmentations-Leak: Membership Inference Attacks and Defenses in Semantic Image Segmentation**](https://arxiv.org/abs/1912.09685) (He et al., 2019)
- [**Differential Privacy Defenses and Sampling Attacks for Membership Inference**](https://priml-workshop.github.io/priml2019/papers/PriML2019_paper_47.pdf) (Rahimian et al., 2019)
- [**privGAN: Protecting GANs from membership inference attacks at low cost**](https://arxiv.org/abs/2001.00071) (Mukherjee et al., 2020)
- [**Sharing Models or Coresets: A Study based on Membership Inference Attack**](https://arxiv.org/abs/2007.02977) (Lu et al., 2020)
- [**Privacy Analysis of Deep Learning in the Wild: Membership Inference Attacks against Transfer Learning**](https://arxiv.org/abs/2009.04872) (Zou et al., 2020)
- [**Quantifying Membership Inference Vulnerability via Generalization Gap and Other Model Metrics**](https://arxiv.org/abs/2009.05669) (Bentley et al., 2020)
- [**MACE: A Flexible Framework for Membership Privacy Estimation in Generative Models**](https://arxiv.org/abs/2009.05683) (Liu et al., 2020)
- [**On Primes, Log-Loss Scores and (No) Privacy**](https://arxiv.org/abs/2009.08559) (Aggarwal et al., 2020)
- [**MCMIA: Model Compression Against Membership Inference Attack in Deep Neural Networks**](https://arxiv.org/abs/2008.13578) (Wang et al., 2020)
- [**Bootstrap Aggregation for Point-based Generalized Membership Inference Attacks**](https://arxiv.org/abs/2011.08738) (Felps et al., 2020)
- [**Differentially Private Learning Does Not Bound Membership Inference**](https://arxiv.org/abs/2010.12112) (Humphries et al., 2020)
- [**Quantifying Membership Privacy via Information Leakage**](https://arxiv.org/abs/2010.05965) (Saeidian et al., 2020)
- [**Disparate Vulnerability: on the Unfairness of Privacy Attacks Against Machine Learning**](https://arxiv.org/abs/1906.00389) (Yaghini et al., 2020)
- [**Use the Spear as a Shield: A Novel Adversarial Example based Privacy-Preserving Technique against Membership Inference Attacks**](https://arxiv.org/abs/2011.13696) (Xue et al., 2020)
- [**Towards Realistic Membership Inferences: The Case of Survey Data**](https://dl.acm.org/doi/abs/10.1145/3427228.3427282?casa_token=eHK7DPiTIigAAAAA:sinfqtYoQA8GddIiwn28DYNEG1NsvW42wvUnRLkpBGQKhrI_mawTRV8MOmLGotqaTspYS-eOIp56UQ)
- [**Unexpected Information Leakage of Differential Privacy Due to Linear Property of Queries**](https://arxiv.org/abs/2010.08958) (Huang et al., 2020)
- [**TransMIA: Membership Inference Attacks Using Transfer Shadow Training**](https://arxiv.org/abs/2011.14661) (Hidano et al., 2020)
- [**An Extension of Fano's Inequality for Characterizing Model Susceptibility to Membership Inference Attacks**](https://arxiv.org/abs/2009.08097) (Jha et al., 2020)
- [**Adversary Instantiation: Lower Bounds for Differentially Private Machine Learning**](https://arxiv.org/abs/2101.04535) (Nasr et al., 2021)


## Reconstruction
Reconstruction attacks cover also attacks known as *model inversion* and *attribute inference*.
- [**Privacy in pharmacogenetics: An end-to-end case study of personalized warfarin dosing**](https://www.usenix.org/system/files/conference/usenixsecurity14/sec14-paper-fredrikson-privacy.pdf) (Fredrikson et al., 2014)
- [**Model inversion attacks that exploit confidence information and basic countermeasures**](https://dl.acm.org/doi/pdf/10.1145/2810103.2813677) (Fredrikson et al., 2015) ([code](https://github.com/yashkant/Model-Inversion-Attack))
- [**A methodology for formalizing model-inversion attacks**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7536387) (Wu et al., 2016)
- [**Deep models under the gan: Information leakage from collaborative deep learning**](https://dl.acm.org/doi/pdf/10.1145/3133956.3134012) (Hitaj et al., 2017) 
- [**Machine learning models that remember too much**](https://dl.acm.org/doi/pdf/10.1145/3133956.3134077) (Song, C. et al., 2017) ([code](https://github.com/csong27/ml-model-remember))
- [**Model inversion attacks for prediction systems: Without knowledge of non-sensitive attributes**](https://ieeexplore.ieee.org/iel7/8476191/8476869/08476925.pdf?casa_token=VQ_s2jcJFp8AAAAA:Hg-wdpPcESm9UUsZHxCLzIvYqVEqW11_OCXEyjARxW5K2cFYi6EFNXlH8IKKjNSgv6oQoQJlsw) (Hidano et al., 2017)
- [**The secret sharer: Evaluating and testing unintended memorization in neural networks**](https://www.usenix.org/system/files/sec19-carlini.pdf) (Carlini et al., 2019)
- [**Deep leakage from gradients**](https://papers.nips.cc/paper/9617-deep-leakage-from-gradients.pdf) (Zhu et al., 2019) ([code](https://github.com/mit-han-lab/dlg))
- [**Model inversion attacks against collaborative inference**](https://dl.acm.org/doi/abs/10.1145/3359789.3359824) (He et al., 2019) ([code](https://github.com/zechenghe/Inverse_Collaborative_Inference))
- [**Beyond Inferring Class Representatives: User-Level Privacy Leakage From Federated Learning**](https://ieeexplore.ieee.org/document/8737416) (Wang et al., 2019)
- [**Neural network inversion in adversarial setting via background knowledge alignment**](https://dl.acm.org/doi/pdf/10.1145/3319535.3354261?casa_token=lDNQ40-4Wa4AAAAA:p9olQ3qMdDZ0n2sl-nNIgk4sOuLRMBTGVTxycZ5wjGpnFPf5lTz-MYw0e8ISggSseHC9T46it5yX) (Yang et al., 2019)
- [**iDLG: Improved Deep Leakage from Gradients**](https://arxiv.org/pdf/2001.02610) (Zhao et al., 2020) ([code](https://github.com/PatrickZH/Improved-Deep-Leakage-from-Gradients))
- [**Privacy Risks of General-Purpose Language Models**](https://www.researchgate.net/profile/Xudong_Pan3/publication/340965355_Privacy_Risks_of_General-Purpose_Language_Models/links/5ea7ca55a6fdccd7945b6a7d/Privacy-Risks-of-General-Purpose-Language-Models.pdf) (Pan et al., 2020)
- [**The secret revealer: generative model-inversion attacks against deep neural networks**](http://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_The_Secret_Revealer_Generative_Model-Inversion_Attacks_Against_Deep_Neural_Networks_CVPR_2020_paper.pdf)) (Zhang et al., 2020)
- [**Inverting Gradients - How easy is it to break privacy in federated learning?**](https://arxiv.org/abs/2003.14053) (Geiping et al., 2020)
- [**GAMIN: An Adversarial Approach to Black-Box Model Inversion**](https://arxiv.org/abs/1909.11835) (Aivodji et al., 2019)
- [**Adversarial Privacy Preservation under Attribute Inference Attack**](https://arxiv.org/abs/1906.07902) (Zhao et al., 2019) 
- [**Reconstruction of training samples from loss functions**](https://arxiv.org/pdf/1805.07337.pdf) (Sannai, 2018)
- [**A Framework for Evaluating Gradient Leakage Attacks in Federated Learning**](https://arxiv.org/pdf/2004.10397.pdf) (Wei et al., 2020) 
- [**Deep Models Under the GAN: Information Leakage from Collaborative Deep Learning**](https://arxiv.org/pdf/1702.07464.pdf) (Hitaj et al., 2017)
- [**Beyond Inferring Class Representatives: User-Level Privacy Leakage From Federated Learning**](https://arxiv.org/pdf/1812.00535.pdf) (Wang et al., 2018) 
- [**Exploring Image Reconstruction Attack in Deep Learning Computation Offloading**](https://dl.acm.org/doi/pdf/10.1145/3325413.3329791) (Oh and Lee, 2019) 
- [**I Know What You See: Power Side-Channel Attack on Convolutional Neural Network Accelerators**](https://arxiv.org/pdf/1803.05847.pdf) (Wei et al., 2019)
- [**Updates-Leak: Data Set Inference and Reconstruction Attacks in Online Learning**](https://arxiv.org/abs/1904.01067) (Salem et al., 2019)
- [**Illuminating the Dark or how to recover what should not be seen in FE-based classifiers**](https://eprint.iacr.org/2018/1001) (Carpov et al., 2020)
- [**Evaluation Indicator for Model Inversion Attack**](https://drive.google.com/file/d/1rl77BGtGHzZ8obWUEOoqunXCjgvpzE8d/view) (Tanaka et al., 2020)
- [**Understanding Unintended Memorization in Federated Learning**](https://arxiv.org/abs/2006.07490) (Thakkar et al., 2020)
- [**An Attack-Based Evaluation Method for Differentially Private Learning Against Model Inversion Attack**](https://ieeexplore.ieee.org/document/8822435) (Park et al., 2019)
- [**Reducing Risk of Model Inversion Using Privacy-Guided Training**](https://arxiv.org/abs/2006.15877) (Goldsteen et al., 2020)
- [**Robust Transparency Against Model Inversion Attacks**](https://ieeexplore.ieee.org/abstract/document/9178452) (Alufaisan et al., 2020)
- [**Does AI Remember? Neural Networks and the Right to be Forgotten**](https://uwspace.uwaterloo.ca/handle/10012/15754) (Graves et al., 2020)
- [**Improving Robustness to Model Inversion Attacks via Mutual Information Regularization**](https://arxiv.org/abs/2009.05241) (Wang et al., 2020)
- [**SAPAG: A Self-Adaptive Privacy Attack From Gradients**](https://arxiv.org/abs/2009.06228) (Wang et al., 2020)
- [**Theory-Oriented Deep Leakage from Gradients via Linear Equation Solver**](https://arxiv.org/abs/2010.13356) (Pan et al., 2020)
- [**Improved Techniques for Model Inversion Attacks**](https://arxiv.org/abs/2010.04092) (Chen et al., 2020)
- [**KART: Privacy Leakage Framework of Language Models Pre-trained with Clinical Records**](https://arxiv.org/abs/2101.00036) (Nakamura et al., 2020)
- [**Black-box Model Inversion Attribute Inference Attacks on Classification Models**](https://arxiv.org/abs/2012.03404) (Mehnaz et al., 2020)
- [**Deep Face Recognizer Privacy Attack: Model Inversion Initialization by a Deep Generative Adversarial Data Space Discriminator**](https://ieeexplore.ieee.org/abstract/document/9306253?casa_token=H78uIRJ2smYAAAAA:iQiA_5d2a2mbH4oBF9EZwSjakAz3Muq3ZOkNDBkK_fLq19PEMGEvpipyli7d9SGKESglqIb9Ug) (Khosravy et al., 2020) 
- [**MixCon: Adjusting the Separability of Data Representations for Harder Data Recovery**](https://arxiv.org/abs/2010.11463) (Li et al., 2020)
- [**Evaluation of Inference Attack Models for Deep Learning on Medical Data**](https://arxiv.org/abs/2011.00177) (Wu et al., 2020)
- [**FaceLeaks: Inference Attacks against Transfer Learning Models via Black-box Queries**](https://arxiv.org/abs/2010.14023) (Liew and Takahashi, 2020)


## Property inference
- [**Hacking smart machines with smarter ones: How to extract meaningful data from machine learning classifiers**](https://dl.acm.org/doi/10.1504/IJSN.2015.071829) (Ateniese et al., 2015)
- [**Property inference attacks on fully connected neural networks using permutation invariant representations**](https://dl.acm.org/doi/pdf/10.1145/3243734.3243834) (Ganju et al., 2018)
- [**Exploiting unintended feature leakage in collaborative learning**](https://ieeexplore.ieee.org/iel7/8826229/8835208/08835269.pdf) (Melis et al., 2019) ([code](https://github.com/csong27/property-inference-collaborative-ml))
- [**Overlearning Reveals Sensitive Attributes**](https://openreview.net/pdf?id=SJeNz04tDS) (Song C. et al., 2020) ([code](https://drive.google.com/file/d/1hu0PhN3pWXe6LobxiPFeYBm8L-vQX2zJ/view?usp=sharing))
- [**Subject Property Inference Attack in Collaborative Learning**](https://ieeexplore.ieee.org/document/9204357) (Xu and Li, 2020)


## Model extraction
- [**Stealing machine learning models via prediction apis**](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_tramer.pdf) (Tramèr et al., 2016) ([code](https://github.com/ftramer/Steal-ML)) 
- [**Stealing hyperparameters in machine learning**](https://ieeexplore.ieee.org/iel7/8418581/8418583/08418595.pdf) (Wang B. et al., 2018)
- [**Copycat CNN: Stealing Knowledge by Persuading Confession with Random Non-Labeled Data**](https://ieeexplore.ieee.org/document/8489592) (Correia-Silva et al., 2018) ([code](https://github.com/jeiks/Stealing_DL_Models))
- [**Towards reverse-engineering black-box neural networks.**](https://openreview.net/forum?id=BydjJte0-)(Oh et al., 2018) ([code](https://github.com/coallaoh/WhitenBlackBox))
- [**Knockoff nets: Stealing functionality of black-box models**](http://openaccess.thecvf.com/content_CVPR_2019/papers/Orekondy_Knockoff_Nets_Stealing_Functionality_of_Black-Box_Models_CVPR_2019_paper.pdf) (Orekondy et al., 2019) ([code](https://github.com/tribhuvanesh/knockoffnets))
- [**PRADA: protecting against DNN model stealing attacks**](https://ieeexplore.ieee.org/document/8806737) (Juuti et al., 2019) ([code](https://github.com/SSGAalto/prada-protecting-against-dnn-model-stealing-attacks))
- [**Model Reconstruction from Model Explanations**](https://dl.acm.org/doi/abs/10.1145/3287560.3287562) (Milli et al., 2019)
- [**Exploring connections between active learning and model extraction**](https://www.usenix.org/system/files/sec20summer_chandrasekaran_prepub.pdf) (Chandrasekaran et al., 2020)
- [**High Accuracy and High Fidelity Extraction of Neural Networks**](https://www.usenix.org/conference/usenixsecurity20/presentation/jagielski) (Jagielski et al., 2020)
- [**Thieves on Sesame Street! Model Extraction of BERT-based APIs**](https://openreview.net/attachment?id=Byl5NREFDr&name=original_pdf) (Krishna et al., 2020) ([code](https://github.com/google-research/language/tree/master/language/bert_extraction))
- [**Cryptanalytic Extraction of Neural Network Models**](https://arxiv.org/pdf/2003.04884.pdf) (Carlini et al., 2020) 
- [**CloudLeak: Large-Scale Deep Learning Models Stealing Through Adversarial Examples**](https://www.ndss-symposium.org/ndss-paper/cloudleak-large-scale-deep-learning-models-stealing-through-adversarial-examples/) (Yu et al., 2020) 
- [**ACTIVETHIEF: Model Extraction Using Active Learning and Unannotated Public Data**](https://www.aaai.org/ojs/index.php/AAAI/article/view/5432) (Pal et al., 2020) ([code](https://bitbucket.org/iiscseal/activethief/src/master))
- [**Efficiently Stealing your Machine Learning Models**](https://encrypto.de/papers/RST19.pdf) (Reith et al., 2019) 
- [**Extraction of Complex DNN Models: Real Threat or Boogeyman?**](https://arxiv.org/pdf/1910.05429.pdf) (Atli et al., 2020) 
- [**Stealing Neural Networks via Timing Side Channels**](https://arxiv.org/pdf/1812.11720.pdf) (Duddu et al., 2019) 
- [**DeepSniffer: A DNN Model Extraction Framework Based on Learning Architectural Hints**](https://dl.acm.org/doi/pdf/10.1145/3373376.3378460) (Hu et al., 2020) ([code](https://github.com/xinghu7788/DeepSniffer))
- [**CSI NN: Reverse Engineering of Neural Network Architectures Through Electromagnetic Side Channel**](https://www.usenix.org/system/files/sec19-batina.pdf) (Batina et al., 2019)
- [**Cache Telepathy: Leveraging Shared Resource Attacks to Learn DNN Architectures**](https://www.usenix.org/conference/usenixsecurity20/presentation/yan) (Yan et al., 2020)
- [**How to 0wn NAS in Your Spare Time**](https://arxiv.org/abs/2002.06776) (Hong et al., 2020) ([code](https://github.com/Sanghyun-Hong/How-to-0wn-NAS-in-Your-Spare-Time))
- [**Security Analysis of Deep Neural Networks Operating in the Presence of Cache Side-Channel Attacks**](https://arxiv.org/abs/1810.03487) (Hong et al., 2020)
- [**Reverse-Engineering Deep ReLU Networks**](https://proceedings.icml.cc/static/paper_files/icml/2020/1-Paper.pdf) (Rolnick and Kording, 2020)
- [**Model Extraction Oriented Data Publishing with k-anonymity**](https://link.springer.com/chapter/10.1007/978-3-030-58208-1_13) (Fukuoka et al., 2020)
- [**Hermes Attack: Steal DNN Models with Lossless Inference Accuracy**](https://arxiv.org/abs/2006.12784) (Zhu et al., 2020)
- [**Model extraction from counterfactual explanations**](https://arxiv.org/abs/2009.01884) (Aïvodji et al., 2020) ([code](https://github.com/aivodji/mrce))
- [**MetaSimulator: Simulating Unknown Target Models for Query-Efficient Black-box Attacks**](https://arxiv.org/abs/2009.00960) (Chen and Yong, 2020) ([code](https://github.com/machanic/MetaSimulator))
- [**Prediction Poisoning: Towards Defenses Against DNN Model Stealing Attacks**](https://arxiv.org/abs/1906.10908) (Orekondy et al., 2019) ([code](https://github.com/tribhuvanesh/prediction-poisoning))
- [**IReEn: Iterative Reverse-Engineering of Black-Box Functions via Neural Program Synthesis**](https://arxiv.org/abs/2006.10720) (Hajipour et al., 2020)
- [**ES Attack: Model Stealing against Deep Neural Networks without Data Hurdles**](https://arxiv.org/abs/2009.09560) (Yuan et al., 2020)
- [**Black-Box Ripper: Copying black-box models using generative evolutionary algorithms**](https://arxiv.org/abs/2010.11158) (Barbalau et al., 2020) ([code](https://github.com/antoniobarbalau/black-box-ripper))
- [**Model Extraction Attacks on Graph Neural Networks: Taxonomy and Realization**](https://arxiv.org/abs/2010.12751) (Wu et al., 2020) 
- [**Extracting Training Data from Large Language Models**](https://arxiv.org/abs/2012.07805) (Carlini et al., 2020)
- [**Model Extraction Attacks and Defenses on Cloud-Based Machine Learning Models**](https://ieeexplore.ieee.org/abstract/document/9311938?casa_token=f_8Lg24vAQkAAAAA:A7P5ym7bTLFIJZtL2yGorscyQC2R1WGJUKzcO-pn8wADHus0w8NArN-nv0JFcKYhwwQFeCaptQ) (Gong et al., 2020)
- [**Leveraging Extracted Model Adversaries for Improved Black Box Attacks**](https://arxiv.org/abs/2010.16336) (Nizar and Kobren, 2020)
- [**Differentially Private Machine Learning Model against Model Extraction Attack**](https://ieeexplore.ieee.org/abstract/document/9291542) (Cheng et al., 2020)

# Other
- [**Amnesiac Machine Learning**](https://arxiv.org/abs/2010.10981) (Graves et al., 2020)
- [**Toward Robustness and Privacy in Federated Learning: Experimenting with Local and Central Differential Privacy**](https://arxiv.org/abs/2009.03561) (Naseri et al., 2020)
- [**Analyzing Information Leakage of Updates to Natural Language Models**](https://arxiv.org/abs/1912.07942) (Brockschmidt et al., 2020)
- [**Estimating g-Leakage via Machine Learning**](https://arxiv.org/abs/2005.04399) (Romanelli et al., 2020)
- [**Information Leakage in Embedding Models**](https://arxiv.org/abs/2004.00053) (Song and Raghunathan, 2020)
- [**Hide-and-Seek Privacy Challenge**](https://arxiv.org/abs/2007.12087) (Jordan et al., 2020)
- [**Synthetic Data -- A Privacy Mirage**](https://arxiv.org/abs/2011.07018) (Stadler et al., 2020)
- [**Robust Membership Encoding: Inference Attacks and CopyrightProtection for Deep Learning**](https://arxiv.org/pdf/1909.12982.pdf) (Song and Shokri, 2020)
- [**Quantifying Privacy Leakage in Graph Embedding**](https://arxiv.org/abs/2010.00906) (Duddu et al., 2020)
