# XHateMARBERT
Using XAI and Transformer-based model to improve the detection of hate speech in dialectal Arabic on social media

**ABSTRACT**

The spread of hate speech on social media networks is a dangerous phenomenon that disturbs these networks. Individuals and societies alike suffer from its devastating effects at all levels, as its harm ranges from personal psychological damage to the disintegration of comunities, stirring up sectarian strife, and spreading the culture exclusion. Accordingly, the issue of detecting hate speech receives widespread attention that aims at finding methods, laws and policies that seek to curb the spread of this dangerous behavior. Therefore, researchers from all over the world are making unremitting efforts to study this problem and devise effective ways to combat it: Specifically in building and training different machine learning models to detect it.

Features play a crucial role in training machine learning models and affect the performance of these models directly. However, there have not been many attempts to improve the quality of features used to train hate speech detection models in order to improve their performance. Detecting hate speech also faces many challenges, especially in the Arabic language, due to its linguistic complexities and diverse dialects, which make building effective models difficult. In addition, modern machine learning models lack transparency and clarity regarding their decisions, which makes improving their performance extremely difficult.

Accordingly, this study aims to combat hate speech in texts written in colloquial Arabic dialects and posted on social media networks. This study sets the goal to understand the decision-making mechanism in a Transformers-based model trained for this purpose, extract the most important and effective features that contribute to detecting hate speech and analyze its role in the detection, in addition to proving the importance of model explaining in improving machine learning models. In the end, these extracted features will be used to train an improved model capable of detecting hate speech in Arabic tweets more efficiently than current models. This model is named XHateMARBERT.

 This study’s contribution is summarized in two main directions: The first direction is analysing the features used in training an initial model based on the MARBERT transformer capable of detecting hate speech in Arabic tweets. This model was given the name HateMARBERT. HateMARBERTs features are analyzed based on a model explaining algorithm called Integrated Gradients, and the contribution of each feature to the final classification decision is determine, followed by extracting the most effective features regarding the detection of hate speech class.
 
The second direction is to prove the effectiveness of the extracted features, and prove the importance of explaining algorithms at the same time, in developing models with higher efficiency in detecting hate speech. This study achieves this by applying a set of innovative methods proposed to modify the features extracted from the previous explaining process, which is represented by removing the features, or masking them from the attention mechanism, or randomly replacing them with features closely related to hate speech or replacing them with other contextually similar features, then train an improved detection model on the modified features: XHateMARBERT.
The contextual replacement method increased F1-Score value over its value in HateMARBERT for the test dataset by 1.26% (88.57% to 89.83%), and achieved the best Precision value by an increase of 1.99% (88.43% to 90.42%). Similarly, the feature removal method was able to improve Recall by 1.36% (89.19% to 90.55%). The proposed methods achieved similar results when applied to a second data set to confirm their effectiveness and generalizability.

The results of the study confirm the importance of directing efforts towards improving training features that lead to improving the performance of the resulting models. The study also confirms the possibility of benefiting from model explaining algorithms in selecting the most effective features in the process of detecting hate speech, and not only in clarifying the decisions of these models, and proves it experimentally. This throws the door wide open for the scientific community to supplement the current methods for detecting hate speech with a constellation of new methods based primarily on the explaining algorithms and raise the quality of hate speech detection models.
