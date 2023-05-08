# Research-paper


#1) DARE: Deceiving Audio–Visual speech Recognition model

https://www.sciencedirect.com/science/article/abs/pii/S0950705121007656


Dr puneet Gupta
Summary 
Sure, here's an example: let's say you're designing an AVSR system that uses both audio and visual features to recognize spoken words. The system works well in most cases, but you discover that it can be easily fooled by small changes to the input, such as adding imperceptible noise to the audio or video signal.

To address this issue, you decide to implement an adversarial attack that can detect and counteract these types of attacks. You design an algorithm that adds small, carefully crafted perturbations to the input data, with the goal of confusing the AVSR system and causing it to misclassify the spoken words.

You then test your algorithm on a set of sample inputs, and find that it is able to successfully fool the AVSR system in a significant number of cases. However, you also discover that the AVSR system can detect some of these attacks using a synchronization-based detection network, SyncNet.

To address this, you modify your algorithm to also fool SyncNet by maintaining the correlation between the audio and visual features in the input data, despite the added perturbations. You test your modified algorithm again, and find that it is now able to fool both the AVSR system and SyncNet, without adding any noticeable distortions to the input data.

This example illustrates the challenges involved in designing a robust and secure AVSR system, and the need for advanced techniques such as adversarial attacks to detect and counteract potential vulnerabilities. It also highlights the importance of testing and refining these techniques to ensure that they are effective and reliable in real-world scenarios.

#2) SUNRISE: Improving 3D mask Face Anti-spoofing for Short Videos using Pre-emptive Split and Merge

Link https://ieeexplore.ieee.org/abstract/document/9760156/metrics#metrics

Summary

Certainly! The paper "SUNRISE: Improving 3D mask Face Anti-spoofing for Short Videos using Pre-emptive Split and Merge" proposes a method for detecting and preventing face spoofing attacks using remote Photoplethysmography (rPPG) technology. Face spoofing attacks involve presenting a fake or manipulated image or video to a face recognition system in order to gain unauthorized access.

The authors of the paper note that existing rPPG-based methods for detecting face spoofing attacks are limited in their effectiveness, particularly for short duration videos, due to the presence of facial deformations and variations in lighting that can corrupt the pulse signals used by rPPG.

To address these limitations, the authors propose a new method called SUNRISE, which involves splitting the video into several clips, assigning low importance to clips containing facial deformations, and then merging the results using quality-based fusion. They also use statistical features of the clips, instead of high dimensional features, to overcome the problem of limited training data.

The authors performed experiments on publicly available datasets and found that their proposed method performed significantly better than existing methods for detecting face spoofing attacks in short duration videos.

Overall, the SUNRISE method proposed in this paper represents a promising approach to improving the effectiveness of rPPG-based face anti-spoofing methods, particularly for short duration videos.

#More detailed
Certainly! The paper is about a technology that helps prevent people from tricking facial recognition systems (like the ones used for unlocking phones) with fake photos or videos of someone else's face. The technology is called SUNRISE, and it uses a method called remote Photoplethysmography (rPPG) to detect heart rate signals in a person's face.

However, sometimes the lighting or facial movements can interfere with the heart rate signals and make the technology less effective. To solve this problem, SUNRISE splits the video into shorter clips, and gives less importance to the clips where the face movements are causing interference. The system then merges the results from the clips to get a final result.

The researchers also found that existing technology for this type of anti-spoofing was limited because they used too many features to train the system, and didn't have enough data. SUNRISE addresses this limitation by using statistical features of the clips instead.

Overall, SUNRISE is a more effective way to prevent people from tricking facial recognition systems with fake photos or videos, especially for shorter duration videos.


3)
