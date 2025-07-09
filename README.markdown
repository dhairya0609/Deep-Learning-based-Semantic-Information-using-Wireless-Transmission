# DeepSC-ST: Semantic Communication System for Speech Transmission

## Overview
This project introduces **DeepSC-ST**, a deep learning-enabled semantic communication system designed for efficient speech transmission over wireless channels, particularly in scenarios with imperfect Channel State Information (CSI). Unlike traditional communication systems that focus on raw data transmission, DeepSC-ST emphasizes the extraction and transmission of semantic information, ensuring meaningful data exchange in resource-constrained environments.

## Motivation
The rapid advancement of artificial intelligence, particularly in natural language processing and speech recognition, has increased the demand for efficient data transmission. Conventional communication systems struggle to meet these demands due to limited spectrum resources. Semantic communication, which prioritizes the meaning of data over raw bits, offers a promising solution. DeepSC-ST is developed to address these challenges by leveraging deep learning to extract and transmit low-dimensional semantic features for speech, enabling accurate text recognition and speech reconstruction while reducing network traffic.

## Key Contributions
- **DeepSC-ST System**: A novel semantic communication system tailored for speech transmission in scenarios with imperfect CSI. It employs a joint semantic-channel coding scheme to effectively learn and transmit semantic information.
- **User Interface Demonstration**: A software prototype that accepts real human speech input and produces recognized text and synthesized speech, showcasing practical applicability.
- **Performance in Low SNR**: The system outperforms existing semantic and traditional communication systems, especially in low signal-to-noise ratio (SNR) environments.

## Problem Statement
The project addresses challenges in wireless semantic communication, including:
- Automatic speech recognition and semantic encoding-decoding in resource-constrained environments.
- Efficient transmission of semantic information over dynamic wireless channels with imperfect CSI.
- Reducing network traffic while maintaining accuracy in text recognition and speech reconstruction.

## Methodology
DeepSC-ST compresses speech data into low-dimensional textual semantic features, which are transmitted over wireless channels. At the receiver, these features are used to reconstruct textual sequences or synthesize speech, leveraging user-specific spatial information for accuracy. The system is optimized for dynamic channels and resource-limited scenarios, such as those anticipated in 6G and beyond.

## Results
- **Training Performance**: The system was trained using a Connectionist Temporal Classification (CTC) loss function, showing faster convergence with perfect CSI compared to imperfect CSI. In perfect CSI scenarios, the loss decreases rapidly, while imperfect CSI results in a more gradual decline due to real-world challenges like noise and fading.
- **Low SNR Efficiency**: DeepSC-ST demonstrates superior performance in low SNR conditions, making it suitable for real-world wireless communication scenarios.
- **Network Traffic Reduction**: By focusing on semantic features, the system significantly reduces network traffic, allowing more users to access the channel.

## Future Scope
- **Expansion to Other Media**: Currently limited to audio and text, DeepSC-ST could be extended to support other media types, such as images and videos.
- **Enhanced Robustness**: Further improvements can be made to handle varying channel conditions and imperfect CSI more effectively.

## Team Learning
This project was conducted as part of the ECE310 course under the guidance of Dr. Dhaval K. Patel and teaching assistant Kashish Shah. The collaborative effort enhanced understanding of semantic features, model training, and their application to real-world wireless communication challenges. Breaking the problem into smaller segments facilitated clarity and effective teamwork.

## References
- Brownllee, J. (2020, August 5). How to prepare univariate time series data for long short-term memory networks. MachineLearningMastery.com.
- Deep Joint Source-channel coding for Semantic Communications. arXiv.org.
- A demo of Semantic Communication. IEEE conference.
- Europar Parallel copies. statand.org.
- How to read a paper. SIGCOMM.
- IEEE Xplore Full-text PDF.