# Awesome-Acoustic-Signal
*All about acoustic communication and sensing.*


## Communication
- (SIGCOMM'22) Underwater Messaging Using Mobile Devices | [paper](https://doi.org/10.1145/3544216.3544258) | [code](https://github.com/uw-x/watercomms) | [project](https://underwatermessaging.cs.washington.edu/)
```
@inproceedings{chen2022under,
author = {Chen, Tuochao and Chan, Justin and Gollakota, Shyamnath},
title = {Underwater Messaging Using Mobile Devices},
year = {2022},
isbn = {9781450394208},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3544216.3544258},
doi = {10.1145/3544216.3544258},
abstract = {Since its inception, underwater digital acoustic communication has required custom hardware that neither has the economies of scale nor is pervasive. We present the first acoustic system that brings underwater messaging capabilities to existing mobile devices like smartphones and smart watches. Our software-only solution leverages audio sensors, i.e., microphones and speakers, ubiquitous in today's devices to enable acoustic underwater communication between mobile devices. To achieve this, we design a communication system that in real-time adapts to differences in frequency responses across mobile devices, changes in multipath and noise levels at different locations and dynamic channel changes due to mobility. We evaluate our system in six different real-world underwater environments with depths of 2--15 m in the presence of boats, ships and people fishing and kayaking. Our results show that our system can in real-time adapt its frequency band and achieve bit rates of 100 bps to 1.8 kbps and a range of 30 m. By using a lower bit rate of 10--20 bps, we can further increase the range to 100 m. As smartphones and watches are increasingly being used in underwater scenarios, our software-based approach has the potential to make underwater messaging capabilities widely available to anyone with a mobile device.Project page with open-source code and data can be found here: https://underwatermessaging.cs.washington.edu/},
booktitle = {Proceedings of the ACM SIGCOMM 2022 Conference},
pages = {545–559},
numpages = {15},
keywords = {mobile phones, underwater exploration, ocean sciences, smart watches, SOS beacons, underwater communication},
location = {Amsterdam, Netherlands},
series = {SIGCOMM '22}
}
```
- (MobiCom'16) DopEnc: Acoustic-based Encounter Profiling Using Smartphones | [paper](https://doi.org/10.1145/2973750.2973775) | [code](https://github.com/dtczhl/dtc-doppler-illustrator) | [project](https://huanlezhang.com/gallery.php)
```
@inproceedings{zhang2016dopenc,
author = {Zhang, Huanle and Du, Wan and Zhou, Pengfei and Li, Mo and Mohapatra, Prasant},
title = {DopEnc: Acoustic-Based Encounter Profiling Using Smartphones},
year = {2016},
isbn = {9781450342261},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/2973750.2973775},
doi = {10.1145/2973750.2973775},
abstract = {This paper presents DopEnc, an acoustic-based encounter profiling system on smartphones. DopEnc can automatically identify the persons that users interact with in the context of encountering. DopEnc performs encounter profiling in two major steps: (1) Doppler profiling to detect that two persons approach and stop in front of each other via an effective trajectory, and (2) voice profiling to confirm that they are thereafter engaged in an interactive conversation. DopEnc is further extended to support parallel acoustic exploration of many users by incorporating a unique multiple access scheme within the limited inaudible acoustic frequency band. All implementation of DopEnc is based on commodity sensors like speakers, microphones and accelerometers integrated on commercial-off-the-shelf smartphones. We evaluate DopEnc with detailed experiments and a real use-case study of 11 participants. Overall DopEnc achieves an accuracy of 6.9% false positive and 9.7% false negative in real usage.},
booktitle = {Proceedings of the 22nd Annual International Conference on Mobile Computing and Networking},
pages = {294–307},
numpages = {14},
keywords = {multiple access, acoustic signals, encounter profiling, doppler effect, voice profiling},
location = {New York City, New York},
series = {MobiCom '16}
}
```
## Sensing
- (TMC'22) Push the Limit of Acoustic Gesture Recognition | [paper](https://doi.org/10.1109/TMC.2020.3032278)
```
@article{wang2022push,
  author={Wang, Yanwen and Shen, Jiaxing and Zheng, Yuanqing},
  journal={IEEE Transactions on Mobile Computing}, 
  title={Push the Limit of Acoustic Gesture Recognition}, 
  year={2022},
  volume={21},
  number={5},
  pages={1798-1811},
  abstract={With the flourish of the smart devices and their applications, controlling devices using gestures has attracted increasing attention for ubiquitous sensing and interaction. Recent works use acoustic signals to track hand movement and recognize gestures. However, they suffer from low robustness due to frequency selective fading, interference and insufficient training data. In this work, we propose RobuCIR, a robust contact-free gesture recognition system that can work under different practical impact factors with high accuracy and robustness. RobuCIR adopts frequency-hopping mechanism to mitigate frequency selective fading and avoid signal interference. To further increase system robustness, we investigate a series of data augmentation techniques based on a small volume of collected data to emulate different practical impact factors. The augmented data is used to effectively train neural network models and cope with various influential factors (e.g., gesture speed, distance to transceiver, etc.). Our experiment results show that RobuCIR can recognize 15 gestures and outperform state-of-the-art works in terms of accuracy and robustness.},
  keywords={},
  doi={10.1109/TMC.2020.3032278},
  ISSN={1558-0660},
  month={May},}
```
- (INFOCOM'20) HearFit: Fitness monitoring on smart speakers via active acoustic sensing | [paper](https://doi.org/10.1109/INFOCOM42981.2021.9488811)
```
@inproceedings{xie2020hearfit,
  author={Xie, Yadong and Li, Fan and Wu, Yue and Wang, Yu},
  booktitle={IEEE INFOCOM 2021 - IEEE Conference on Computer Communications}, 
  title={HearFit: Fitness Monitoring on Smart Speakers via Active Acoustic Sensing}, 
  year={2021},
  volume={},
  number={},
  pages={1-10},
  abstract={Fitness can help to strengthen muscles, increase resistance to diseases and improve body shape. Nowadays, more and more people tend to exercise at home/office, since they lack time to go to the dedicated gym. However, it is difficult for most of them to get good fitness effect due to the lack of professional guidance. Motivated by this, we propose HearFit, the first non-invasive fitness monitoring system based on commercial smart speakers for home/office environments. To achieve this, we turn smart speakers into active sonars. We design a fitness detection method based on Doppler shift and adopt the short time energy to segment fitness actions. We design a high-accuracy LSTM network to determine the type of fitness. Combined with incremental learning, users can easily add new actions. Finally, we evaluate the local (i.e., intensity and duration) and global (i.e., continuity and smoothness) fitness quality of users to help to improve fitness effect and prevent injury. Through extensive experiments including over 7,000 actions of 10 types of fitness with and without dumbbells from 12 participants, HearFit can detect fitness actions with an average accuracy of 96.13%, and give accurate statistics in various environments.},
  keywords={},
  doi={10.1109/INFOCOM42981.2021.9488811},
  ISSN={2641-9874},
  month={May},}
```
- (IMWUT'20) Endophasia: Utilizing Acoustic-Based Imaging for Issuing Contact-Free Silent Speech Commands | [paper](https://dl.acm.org/doi/abs/10.1145/3381008)
```
@article{zhang2020endophasia,
author = {Zhang, Yongzhao and Huang, Wei-Hsiang and Yang, Chih-Yun and Wang, Wen-Ping and Chen, Yi-Chao and You, Chuang-Wen and Huang, Da-Yuan and Xue, Guangtao and Yu, Jiadi},
title = {Endophasia: Utilizing Acoustic-Based Imaging for Issuing Contact-Free Silent Speech Commands},
year = {2020},
issue_date = {March 2020},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {4},
number = {1},
url = {https://doi.org/10.1145/3381008},
doi = {10.1145/3381008},
abstract = {Using silent speech to issue commands has received growing attention, as users can utilize existing command sets from voice-based interfaces without attracting other people's attention. Such interaction maintains privacy and social acceptance from others. However, current solutions for recognizing silent speech mainly rely on camera-based data or attaching sensors to the throat. Camera-based solutions require 5.82 times larger power consumption or have potential privacy issues; attaching sensors to the throat is not practical for commercial-off-the-shell (COTS) devices because additional sensors are required. In this paper, we propose a sensing technique that only needs a microphone and a speaker on COTS devices, which not only consumes little power but also has fewer privacy concerns. By deconstructing the received acoustic signals, a 2D motion profile can be generated. We propose a classifier based on convolutional neural networks (CNN) to identify the corresponding silent command from the 2D motion profiles. The proposed classifier can adapt to users and is robust when tested by environmental factors. Our evaluation shows that the system achieves 92.5\% accuracy in classifying 20 commands.},
journal = {Proc. ACM Interact. Mob. Wearable Ubiquitous Technol.},
month = {mar},
articleno = {37},
numpages = {26},
keywords = {silent command, acoustic-based imaging, mobile devices}
}
```
- (CHI'19) MilliSonic: Pushing the Limits of Acoustic Motion Tracking | [paper](https://doi.org/10.1145/3290605.3300248)
```
@inproceedings{wang2019millisonic,
author = {Wang, Anran and Gollakota, Shyamnath},
title = {MilliSonic: Pushing the Limits of Acoustic Motion Tracking},
year = {2019},
isbn = {9781450359702},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3290605.3300248},
doi = {10.1145/3290605.3300248},
abstract = {Recent years have seen interest in device tracking and localization using acoustic signals. State-of-the-art acoustic motion tracking systems however do not achieve millimeter accuracy and require large separation between microphones and speakers, and as a result, do not meet the requirements for many VR/AR applications. Further, tracking multiple concurrent acoustic transmissions from VR devices today requires sacrificing accuracy or frame rate. We present MilliSonic, a novel system that pushes the limits of acoustic based motion tracking. Our core contribution is a novel localization algorithm that can provably achieve sub-millimeter 1D tracking accuracy in the presence of multipath, while using only a single beacon with a small 4-microphone array.Further, MilliSonic enables concurrent tracking of up to four smartphones without reducing frame rate or accuracy. Our evaluation shows that MilliSonic achieves 0.7mm median 1D accuracy and a 2.6mm median 3D accuracy for smartphones, which is 5x more accurate than state-of-the-art systems. MilliSonic enables two previously infeasible interaction applications: a) 3D tracking of VR headsets using the smartphone as a beacon and b) fine-grained 3D tracking for the Google Cardboard VR system using a small microphone array.},
booktitle = {Proceedings of the 2019 CHI Conference on Human Factors in Computing Systems},
pages = {1–11},
numpages = {11},
keywords = {motion tracking, localization, acoustic, virtual reality, mobile system},
location = {Glasgow, Scotland Uk},
series = {CHI '19}
}
```
### Localization
- (SIGCOMM'23) Underwater 3D Positioning on Smart Devices | [paper](https://dl.acm.org/doi/10.1145/3603269.3604851) | [code](https://github.com/uw-x/underwatergps) | [project](https://underwatergps.cs.washington.edu/)
```
@inproceedings{chen2023underwater,
author = {Chen, Tuochao and Chan, Justin and Gollakota, Shyamnath},
title = {Underwater 3D Positioning on Smart Devices},
year = {2023},
isbn = {9798400702365},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3603269.3604851},
doi = {10.1145/3603269.3604851},
abstract = {The emergence of water-proof mobile and wearable devices (e.g., Garmin Descent and Apple Watch Ultra) designed for underwater activities like professional scuba diving, opens up opportunities for underwater networking and localization capabilities on these devices. Here, we present the first underwater acoustic positioning system for smart devices. Unlike conventional systems that use floating buoys as anchors at known locations, we design a system where a dive leader can compute the relative positions of all other divers, without any external infrastructure. Our intuition is that in a well-connected network of devices, if we compute the pairwise distances, we can determine the shape of the network topology. By incorporating orientation information about a single diver who is in the visual range of the leader device, we can then estimate the positions of all the remaining divers, even if they are not within sight. We address various practical problems including detecting erroneous distance estimates, addressing rotational and flipping ambiguities as well as designing a distributed timestamp protocol that scales linearly with the number of devices. Our evaluations show that our distributed system running on underwater deployments of 4--5 commodity smart devices can perform pairwise ranging and localization with median errors of 0.5--0.9 m and 0.9--1.6 m. Project page with code: https://underwatergps.cs.washington.edu/},
booktitle = {Proceedings of the ACM SIGCOMM 2023 Conference},
pages = {33–48},
numpages = {16},
keywords = {ocean sciences, smart watches, underwater GPS, anchor-free, acoustic tracking, distributed localization},
location = {New York, NY, USA},
series = {ACM SIGCOMM '23}
}
```
- (ICRA'22) Towards Accurate Positioning of Underwater Vehicles Using Low-cost Acoustic Modems | [paper](https://doi.org/10.1109/ICRA46639.2022.9811851)
```
@inproceedings{busse2022towards,
  author={Busse, Christian and Renner, Bernd-Christian},
  booktitle={2022 International Conference on Robotics and Automation (ICRA)}, 
  title={Towards Accurate Positioning of Underwater Vehicles Using Low-cost Acoustic Modems}, 
  year={2022},
  volume={},
  number={},
  pages={1106-1112},
  abstract={Navigating autonomous underwater vehicles (AUVs) in shallow and harbor waters is challenging and typically has higher accuracy requirements than navigation in the open sea. We investigate enhancements to underwater localization techniques based on Two-Way Ranging (TWR) using acoustic modems, which have great potential to meet localization accuracy requirements at lower cost and complexity than current systems. By modifying the Extended Kalman Filter, we account for dynamic positioning errors that occur during the movement of the localization target, i.e., the underwater vehicle, and the fact that distance measurements with acoustic modems are delayed in time. The method is evaluated numerically and experimentally showing an accuracy improvement of about 20 cm compared to the traditional EKF scheme. In real-world tests at ranges below 30 m, the absolute localization accuracy is assessed using an RTK-GPS reference, showing that a positioning error below 35 cm can be achieved in a quasi-static test, while in a dynamic test the tracking error is mostly below 75 cm.},
  keywords={},
  doi={10.1109/ICRA46639.2022.9811851},
  ISSN={},
  month={May},}
```

## Multimedia
- (SIGGRAPH'22) GWA: A Large High-Quality Acoustic Dataset for Audio Processing | [paper](https://doi.org/10.1145/3528233.3530731) | [code](https://github.com/GAMMA-UMD/GWA) | [project](https://gamma.umd.edu/pro/sound/gwa)
```
@inproceedings{tang2022gwa,
author = {Tang, Zhenyu and Aralikatti, Rohith and Ratnarajah, Anton Jeran and Manocha, Dinesh},s
title = {GWA: A Large High-Quality Acoustic Dataset for Audio Processing},
year = {2022},
isbn = {9781450393379},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3528233.3530731},
doi = {10.1145/3528233.3530731},
abstract = {We present the Geometric-Wave Acoustic (GWA) dataset, a large-scale audio dataset of about 2 million synthetic room impulse responses (IRs) and their corresponding detailed geometric and simulation configurations. Our dataset samples acoustic environments from over 6.8K high-quality diverse and professionally designed houses represented as semantically labeled 3D meshes. We also present a novel real-world acoustic materials assignment scheme based on semantic matching that uses a sentence transformer model. We compute high-quality impulse responses corresponding to accurate low-frequency and high-frequency wave effects by automatically calibrating geometric acoustic ray-tracing with a finite-difference time-domain wave solver. We demonstrate the higher accuracy of our IRs by comparing with recorded IRs from complex real-world environments. Moreover, we highlight the benefits of GWA on audio deep learning tasks such as automated speech recognition, speech enhancement, and speech separation. This dataset is the first data with accurate wave acoustic simulations in complex scenes. Codes and data are available at https://gamma.umd.edu/pro/sound/gwa.},
booktitle = {ACM SIGGRAPH 2022 Conference Proceedings},
articleno = {36},
numpages = {9},
keywords = {audio dataset, geometric sound propagation, Acoustic simulation},
location = {Vancouver, BC, Canada},
series = {SIGGRAPH '22}
}
```
- (MM'22) MESH2IR: Neural Acoustic Impulse Response Generator for Complex 3D Scenes | [paper](https://doi.org/10.1145/3503161.3548253)
```
@inproceedings{10.1145/3503161.3548253,
author = {Ratnarajah, Anton and Tang, Zhenyu and Aralikatti, Rohith and Manocha, Dinesh},
title = {MESH2IR: Neural Acoustic Impulse Response Generator for Complex 3D Scenes},
year = {2022},
isbn = {9781450392037},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3503161.3548253},
doi = {10.1145/3503161.3548253},
abstract = {We propose a mesh-based neural network (MESH2IR) to generate acoustic impulse responses (IRs) for indoor 3D scenes represented using a mesh. The IRs are used to create a high-quality sound experience in interactive applications and audio processing. Our method can handle input triangular meshes with arbitrary topologies (2K - 3M triangles). We present a novel training technique to train MESH2IR using energy decay relief and highlight its benefits. We also show that training MESH2IR on IRs preprocessed using our proposed technique significantly improves the accuracy of IR generation. We reduce the non-linearity in the mesh space by transforming 3D scene meshes to latent space using a graph convolution network. Our MESH2IR is more than 200 times faster than a geometric acoustic algorithm on a CPU and can generate more than 10,000 IRs per second on an NVIDIA GeForce RTX 2080 Ti GPU for a given furnished indoor 3D scene. The acoustic metrics are used to characterize the acoustic environment. We show that the acoustic metrics of the IRs predicted from our MESH2IR match the ground truth with less than 10% error. We also highlight the benefits of MESH2IR on audio and speech processing applications such as speech dereverberation and speech separation. To the best of our knowledge, ours is the first neural-network-based approach to predict IRs from a given 3D scene mesh in real-time.},
booktitle = {Proceedings of the 30th ACM International Conference on Multimedia},
pages = {924–933},
numpages = {10},
keywords = {room acoustics, sound propagation, speech simulation, cross-modal},
location = {Lisboa, Portugal},
series = {MM '22}
}
```
