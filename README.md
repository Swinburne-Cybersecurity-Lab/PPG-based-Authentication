# PPG-based-Authentication
Welcome to our PPG-based Authentication repository! Our team has been working on various aspects of this field and has produced a series of research projects.

Our work includes projects like "Video is All You Need Attacking PPG based Biometric Authentication," which explores the vulnerability of PPG-based authentication systems to video-based attacks, and "Hiding Your Signals: A Security Analysis of PPG-based Biometric Authentication," which investigates ways to protect PPG-based systems from attacks that try to conceal signals.

Additionally, we have developed SigD, a cross-session dataset that enables PPG-based user authentication across different demographic groups. If you're interested in these topics and want to stay updated on our latest research, we invite you to follow our work and get in touch with us.


# SigD: A Cross-Session Dataset for PPG-Based User Authentication in Different Demographic Groups 
Accepted by IJCNN 2023

Abstract
Due to the lack of data sets, existing methods are limited in evaluating cross-session scenarios. Cross-session means that signals are collected at different sessions (times). In real scenarios, authentication is almost always cross-session. Currently, the datasets commonly used for Photoplethysmogram (PPG) signal authentication span around one month, which is insufficient for authentication. On the other hand, different demographic groups have different hemodynamic characteristics, but existing methods lack an assessment of these aspects. This paper introduces a dataset to provide insights into PPG signal-based authentication across different time spans and user groups (age, gender). As physiological signals offer unique advantages for user authentication, the potential of PPG signals is gradually explored. Furthermore, our comparative analysis of recent publications on data-driven user authentication using PPG can further identify the similarities and differences among the performance of the proposed authentication models. Our findings may help future research towards a consensus on an appropriate set of performance metrics. 

***

# Hiding Your Signals: A Security Analysis of PPG-based Biometric Authentication
Accepted by ESORICS 2023

Abstract
Photoplethysmogram (PPG) signal is easy to measure, making it more attractive than many other physiological signals for biometric authentication. However, with the advent of remote PPG, unobservability has been challenged when the attacker can remotely steal the PPG signals by monitoring the victim's face, subsequently posing a threat to PPG-based biometrics. In this paper, we firstly analyze the security of PPG-based biometrics, including user authentication and communication protocols. We evaluate the signal waveforms and inter-pulse-interval information extracted by five rPPG methods. Our empirical studies on five datasets show that rPPG poses a serious threat to the authentication system. The success rate of the rPPG signal spoofing attack in the user authentication system reached 35\%. The bit hit rate is 60\% in inter-pulse-interval-based security protocols. Further, we propose an active defence strategy to hide the physiological signals of the face to resist the attack. It reduces the success rate of rPPG spoofing attacks in user authentication to 5\%. The bit hit rate was reduced to 50\%, which is at the level of a random guess. Our strategy effectively prevents the exposure of PPG signals to protect users' sensitive physiological data.

***

# [Video-is-All-You-Need-Attacking-PPG-based-Biometric-Authentication [AISec]](https://dl.acm.org/doi/10.1145/3560830.3563722) 
Published: AISec 2022

Abstract
Unobservable physiological signals enhance biometric authentication systems. Photoplethysmography (PPG) signals are convenient owing to its ease of measurement and are usually well protected against remote adversaries in the authentication. Any leaked PPG signals help adversaries compromise the biometric authentication systems, and the advent of remote PPG (rPPG) enables adversaries to acquire PPG signals through restoration. While potentially dangerous, rPPG-based attacks are overlooked because existing methods require the victim's PPG signals. This paper proposes a novel spoofing attack approach that uses the waveforms of rPPG signals extracted from video clips to fool the PPG-based biometric authentication. We develop a new PPG restoration model to accomplish adversarial attacks without leaked PPG signals. Empirical study results on state-of-art PPG-based biometric authentication show that the signals recovered through rPPG pose a severe threat to PPG-based biometric authentication. 
