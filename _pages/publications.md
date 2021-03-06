---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
1.EEG dataset  and Matlab script code for ['Single-trial-based Temporal Principal Component Analysis on Extracting Event-related Potentials of Interest for an Individual Subject'](https://doi.org/10.1101/2021.03.10.434892)
------   

* **EEG dataset**: (a) Experimental paradigm - Within-subject design with two-factor: Valence (extreme, moderate, and neutral) x Negative-category (disgusting and fearful) and the details can be found in [(Lu et al., 2016)](https://doi.org/10.1080/17470919.2015.1120238). (b) Preprocessed EEG datasets for different participants - [Sub#1](../_publications/Sub_1_Emotional_Lu_2017.7z); [Sub#2](../_publications/Sub_2_Emotional_Lu_2017.7z); [Sub#3](../_publications/Sub_3_Emotional_Lu_2017.7z);  [Sub#4](../_publications/Sub_4_Emotional_Lu_2017.7z); [Sub#5](../_publications/Sub_5_Emotional_Lu_2017.7z); [Sub#6](../_publications/Sub_6_Emotional_Lu_2017.7z); [Sub#7](../_publications/Sub_7_Emotional_Lu_2017.7z); [Sub#8](../_publications/Sub_8_Emotional_Lu_2017.7z); [Sub#9](../_publications/Sub_9_Emotional_Lu_2017.7z); [Sub#10](../_publications/Sub_10_Emotional_Lu_2017.7z); [Sub#11](../_publications/Sub_11_Emotional_Lu_2017.7z); [Sub#12](../_publications/Sub_12_Emotional_Lu_2017.7z); [Sub#13](../_publications/Sub_13_Emotional_Lu_2017.7z); [Sub#14](../_publications/Sub_14_Emotional_Lu_2017.7z); [Sub#15](../_publications/Sub_15_Emotional_Lu_2017.7z); [Sub#16](../_publications/Sub_16_Emotional_Lu_2017.7z); [Sub#17](../_publications/Sub_17_Emotional_Lu_2017.7z); [Sub#18](../_publications/Sub_18_Emotional_Lu_2017.7z); [Sub#19](../_publications/Sub_19_Emotional_Lu_2017.7z); [Sub#20](../_publications/Sub_20_Emotional_Lu_2017.7z); [Sub#21](../_publications/Sub_21_Emotional_Lu_2017.7z); [Sub#22](../_publications/Sub_22_Emotional_Lu_2017.7z).
* **Matlab script code:** Four different techniqes are used to extract N2 of interest from the first 20 subjects' datasets ([Download Matlab script codes](../_publications/Emotional_Lu_2017_codes_for_EEG_ERP_Processing.7z) & [Read me](../_publications/Read_me_Emotional_Lu_2017_codes_for_EEG_ERP_Processing.7z)). (a) 'WF': N2 is quantified using conventional time-domain analysis at group analysis; (b)'iPCA': N2 is separately quantified from the single-trial EEG of individual subject using temporal principal component analysis and Promax rotation. (c) 'aPCA': N2 is measured from the averaged ERP data across single trials of all subject simultaneously by using temporal principal component analysis and Promax rotation. (d) 'sPCA': N2 is measured from the single-trial EEG data of all subject simultaneously by using temporal principal component analysis and Promax rotation.

* **Citation:**  **(a) Guanghui Zhang**, Xueyan Li, Yingzhi Lu, Timo Tiihonen, Zheng Chang, and Fengyu Cong. (2021). Single-trial-based Temporal Principal Component Analysis on Extracting Event-related Potentials of Interest for an Individual Subject. bioRxiv. DOI:[10.1101/2021.03.10.434892](https://doi.org/10.1101/2021.03.10.434892). **(b) Yingzhi Lu**,Yu Luo,Yi Lei,Kyle J. Jaquess,Chenglin Zhou   and Hong Li. (2016). Decomposing valence intensity effects in disgusting and fearful stimuli: an event-related potential study. Social neuroscience, 11(6), 618-626. DOI:[10.1080/17470919.2015.1120238](https://doi.org/10.1080/17470919.2015.1120238). **(c) Guanghui Zhang**, Xueyan Li, and Fengyu Cong (2020). Objective Extraction of Evoked Event-Related Oscillation from Time-Frequency Representation of Event-Related Potentials, Neural Plasticity, vol. 2020, Article ID 8841354, 20 pages. DOI:[10.1155/2020/8841354](https://doi.org/10.1155/2020/8841354). 


2.Other Matlab script codes
------   
* **Toolbox:** **Evoked ERP_ERO_v1.1**. **(a)** Author:Guanghui Zhang, and Fengyu Cong. **(b)** Introduction: This toolbox provides some advanced signal processing and analysis methods based on temporal principal component analysis (t-PCA)/morlet continuous wavelet transform to rapidly and objectively extract the event-related potential (ERP)/event-related oscillation (ERO) of interest from the averaged ERP dataset at group-level([Download toolbox: Evoked ERP ERO_V1.1](../_publications/Evoked ERP ERO_v1.1.zip) /[Download demo datasets](../_publications/Evoked ERP ERO_v1.1 Demo data.zip) / [Download codes for forming a fourth-order tensor](../_publications/Evoked ERP ERO_v1.1_Forming_fourth_order_tensor_demo data.zip)). Please add EEGLAB, for example, [eeglab14_1_2b](../_publications/eeglab14_1_2b.zip), into Matlab path before use this toolbox to process ERP signals. **(c)** Signal type for processing: The averaged signal, a fourth-order tensor, is collected from the within-subject (one-factor, two-factor, three-factor) or between-subject (two-factor, three-factor) experiment designs.  **(d)** Function: Using t-PCA and Promax rotation/continuous wavelet transform to extract the ERPs/EROs of interest from the original input/the filtered signal (FFT filter or wavelet filter), and exporting the data at the specific electrodes with the time-window of interest as an excel file, which can be imported to SPSS. **(e)** Cite this toolbox:  **Guanghui Zhang**, Xueyan Li, and Fengyu Cong. Objective Extraction of Evoked Event-Related Oscillation from Time-Frequency Representation of Event-Related Potentials, Neural Plasticity, vol. 2020, Article ID 8841354, 20 pages. DOI:[10.1155/2020/8841354](https://doi.org/10.1155/2020/8841354).


* **Principal component analysis (PCA)**: Group PCA analysis for single trial EEG data or averaged ERP data; Individual-subject PCA analysis (See 1.EEG datasets  and Matlab script codes for'Single-trial-based Temporal Principal Component Analysis on Extracting Event-related Potentials of Interest for an Individual Subject').

* **Independent component analysis (ICA)**: Applications of ICA on [low-dense](../_publications/WaveletFilter-ICA_ERP_lowDenseEEG_20160513.rar)/[high-dense](../_publications/WaveletFilter-ICA_ERP_highDenseEEG.zip) EEG data.

* **Tensor decomposition**: [Nonnegative canonical polyadic decomposition (NCPD)](../_publications/NTF_CP_ERP-Tensor-TFR_2018.rar); [Nonnegative Tucker decomposition(NTD)](../_publications/NTF_Tucker_ERP-Tensor-TFR_2018.rar).

* **Repeated  measurement analysis of variance (rm-ANOVA)**: Within-subject analysis includes [one factor](../_publications/Within-subject rm-ANOVA_one factor.zip), [two factors](../_publications/Within-subject rm-ANOVA_two factors.zip), and [three factors](../_publications/Within-subject rm-ANOVA_three factors.zip); Between-subject analysis contains [two factors](../_publications/Between-subject_twofactors.zip) and three factors (Not avaliable).






3.Journal  and conference papers
------
* **Guanghui Zhang**, Xueyan Li, Yingzhi Lu, Timo Tiihonen, Zheng Chang, and Fengyu Cong. (2021). Single-trial-based Temporal Principal Component Analysis on Extracting Event-related Potentials of Interest for an Individual Subject. bioRxiv. DOI:[10.1101/2021.03.10.434892](https://doi.org/10.1101/2021.03.10.434892)

* **Guanghui Zhang**, Chi Zhang, Shuo Cao, Xue Xia, Xin Tan, Lichengxi Si, Chenxin Wang, Xiaochun Wang, Chenglin Zhou, Tapani Ristaniemi, and Fengyu Cong (2020). Multi-domain Features of the Non-phase-locked Component of Interest Extracted from ERP Data by Tensor Decomposition. Brain Topography, 33(1), 37-47. DOI: [10.1007/s10548-019-00750-8](https://doi.org/10.1007/s10548-019-00750-8)

* **Guanghui Zhang**, Xueyan Li, and Fengyu Cong (2020) Objective Extraction of Evoked Event-Related Oscillation from Time-Frequency Representation of Event-Related Potentials, Neural Plasticity, vol. 2020, Article ID 8841354, 20 pages. DOI:[10.1155/2020/8841354](https://doi.org/10.1155/2020/8841354)
* **Guanghui Zhang**, Lili Tian, Huaming Chen, Peng Li, Tapani Ristaniemi, Huili Wang, Hong Li, Hongjun Chen, and Fengyu Cong (2018). Effect of parametric variation of center frequency and bandwidth of morlet wavelet transform on time-frequency analysis of event-related potentials. In Chinese intelligent systems conference (pp. 693-702). Springer, Singapore. DOI: [10.1007/978-981-10-6496-8_63](https://doi.org/10.1007/978-981-10-6496-8_63)

* Xue Xia, **Guanghui Zhang**, and Xiaochun Wang. Anger weakens behavioral inhibition selectively in contact athletes. Frontiers in Human Neuroscience 12 (2018): 463. DOI: [10.3389/fnhum.2018.00463](https://doi.org/10.3389/fnhum.2018.00463)

* XueYan Li, HuiLi Wang, Pertti Saariluoma, **GuangHui Zhang**, YongJie Zhu, Chi Zhang，YuCong Feng，and Tapani Ristaniemi (2019). Processing Mechanism of Chinese Verbal Jokes: Evidence from ERP and Neural Oscillations. Journal of Electronic Science and Technology, 17(3), 260-277. DOI: [10.11989/JEST.1674-862X.80520017](https://doi.org/10.11989/JEST.1674-862X.80520017)

* Xiawen Li, **Guanghui Zhang**, Chenglin Zhou, and Xiaochun Wang. (2019). Negative emotional state slows down movement speed: behavioral and neural evidence. PeerJ, 7, e7591. DOI: [10.7717/peerj.7591](https://doi.org/10.7717/peerj.7591)

* Jiacheng Chen,Yanan Li, **Guanghui Zhang**, Xinhong Jin,Yingzhi Lua, and Chenglin Zhou (2019). Enhanced inhibitory control during re-engagement processing in badminton athletes: An event-related potential study. Journal of Sport and Health Science, 8(6), 585-594. DOI: [10.1016/j.jshs.2019.05.005](https://doi.org/10.1016/j.jshs.2019.05.005)

*  Shuo Cao, Yanzhang Wang, Huili Wang, Hongjun Chen, **Guanghui Zhang**, and Kritikos Ada (2020). A Facilitatory Effect of Perceptual Incongruity on Target-Source Matching in Pictorial Metaphors of Chinese Advertising: EEG Evidence. Advances in Cognitive Psychology, 16(1), 1. DOI: [10.5709/acp-0279-z](https://doi.org/10.5709/acp-0279-z)

* Jiaxin Yu, Yan Wang, Jianling Yu, **Guanghui Zhang**, and Fengyu Cong (2020). Nudge for justice: An ERP investigation of default effects on trade-offs between equity and efficiency. Neuropsychologia. DOI:[10.1016/j.neuropsychologia.2020.107663](https://doi.org/10.1016/j.neuropsychologia.2020.107663)


4.Dissertation
------
* **Guanghui Zhang**, Methods to extract multi-dimensional features of event-related brain activities from EEG data, University of Jyväskylä, Finland. August 12 2021 [(Download dissertation)](https://jyx.jyu.fi/handle/123456789/76955#).

* **Feiyang Shen**, Event-related Potential Based Brain Connectivity Analysis in Hyperscanning [(Download it)](../_publications/ShenFeiYang-BachelorThesis-2021-June.pdf) (the contents are in Chinese and the PCA analysis in this thesis is based on the ERP_ERO toolbox).


