# Research-paper


DARE: Deceiving Audio–Visual speech Recognition model
https://www.sciencedirect.com/science/article/abs/pii/S0950705121007656
Dr puneet Gupta
Summary 
Sure, here's an example: let's say you're designing an AVSR system that uses both audio and visual features to recognize spoken words. The system works well in most cases, but you discover that it can be easily fooled by small changes to the input, such as adding imperceptible noise to the audio or video signal.

To address this issue, you decide to implement an adversarial attack that can detect and counteract these types of attacks. You design an algorithm that adds small, carefully crafted perturbations to the input data, with the goal of confusing the AVSR system and causing it to misclassify the spoken words.

You then test your algorithm on a set of sample inputs, and find that it is able to successfully fool the AVSR system in a significant number of cases. However, you also discover that the AVSR system can detect some of these attacks using a synchronization-based detection network, SyncNet.

To address this, you modify your algorithm to also fool SyncNet by maintaining the correlation between the audio and visual features in the input data, despite the added perturbations. You test your modified algorithm again, and find that it is now able to fool both the AVSR system and SyncNet, without adding any noticeable distortions to the input data.

This example illustrates the challenges involved in designing a robust and secure AVSR system, and the need for advanced techniques such as adversarial attacks to detect and counteract potential vulnerabilities. It also highlights the importance of testing and refining these techniques to ensure that they are effective and reliable in real-world scenarios.
