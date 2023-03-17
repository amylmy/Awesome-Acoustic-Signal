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
