# Speech-Emotion-Recognition-from-Bone-Conducted-Speech-Using-Wav2Vec2-Transformer-Model
This is my B.Sc(Engineering) thesis work. I've done this thesis with my full dedication.

ABSTRACT:
Speech emotion recognition (SER) is an important area of affective computing that
 helps machines to understand human emotions through speech signals. This technology
 significantly improves human computer interactions (HCI), intelligent virtual assistants,
 mental health monitoring, and systems that recognize emotions. While traditional SER
 systems mainly focus on air-conducted (AC) speech, their performance drops in noisy or
 real world settings. Bone-conducted (BC) speech, which travels through cranial bones
 instead of air, offers a noise resistant option suitable for these conditions. However,
 BCspeech is still not widely used in SER research due to the lack of publicly available
 datasets and the challenges of accurately modeling emotions.
 This thesis introduces an end-to-end SER framework based on the Wav2Vec2.0 trans
former model. It was trained and evaluated using EmoBone, a diverse BC speech dataset
 that includes eight emotional classes. Unlike traditional methods that rely on manually
 crafted features, the proposed model processes raw audio waveforms directly to extract
 contextual representations, improving both robustness and generalization. A customized
 classification head is included to allow for quick and accurate emotion prediction. The
 system achieved a weighted F1-score and overall accuracy of 93%, surpassing previous
 top models applied to the EmoBone dataset.
 To ensure thorough evaluation, several analyses were conducted, including confusion
 matrix interpretation, precision-recall metrics, and class-wise F1-score visualization.
 These results show that the model performs well in detecting various emotional states,
 although there are minor misclassifications between acoustically similar emotions, like
 calm and neutral. Future research will focus on addressing these issues through data
 augmentation, class balancing, and combining data from visual or textual inputs. This
 study demonstrates the practicality and effectiveness of transformer based models for
 SERtasks that involve BC speech, especially in challenging acoustic environments. The
 research not only provides a new methodological approach but also lays the groundwork
 for future advancements in emotion-aware HCI technologies and speech based systems
 that are culturally inclusive.
