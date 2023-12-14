## Sleep Stage Detection using EEG Signals

### Published Paper [here](https://ieeexplore.ieee.org/document/9616895) 
##### Authors: Nirali Parekh, Bhavi Dave, Raj Shah


## Abstract

Although Deep Learning approaches generate State Of The Art performance across several
domains, the approach often lacks Interpretability, hindering adoption beyond academia into high
stakes situations like Health Care and medicine. The potential for human scrutiny, interpretation
and verification can make the model robust and reliable, increasing confidence. The study of sleepPolysomnography- uses Electroencephalogram (EEG) readings, among other parameters, to gain
a clearer picture of a patient’s sleep patterns since different brain activities correspond to different
stages of sleep. Monitoring and interpreting EEG signals and the body’s reactions to the changes
in these cycles can help identify disruptions in sleep patterns, which can in turn help with the
medical prognosis of several pervasive diseases like Sleep Apnea and the predilection for seizures.
For simultaneously addressing the pitfalls associated with the traditional manual review of EEG
signals for disease prognosis and concerns like ethics, reliability and interpretability that arise
when automation is introduced in the realm of medicine, we propose the creation of a novel XAI
architecture. Using data from raw, single channel EEG signals, the project classifies the five sleep
stages (Wake, N1, N2, N3, N4 and REM ) and demonstrates how the the classification aids in
detecting prominent sleep related diseases by detecting Sleep Apnea and Seizures with the
proposed architecture. The purpose of this study is to propose a novel and Explainable architecture
for both sleep stage classification and malady detection that emulates the accuracy of traditional
DL models while incorporating interpretability. As a first stage towards achieving the goal, we
have implemented a CNN to extract time-invariant features and learn stage transition rules among
sleep stages from EEG epochs. The model successfully classifies the five stages with a 96%
accuracy as well as precision, recall and f1 score of 0.96.

### Citation

```
@InProceedings{10.1007/978-981-99-3481-2_22,
author="Parekh, Nirali
and Trivedi, Siddharth
and Srivastava, Kriti",
editor="Borah, Malaya Dutta
and Laiphrakpam, Dolendro Singh
and Auluck, Nitin
and Balas, Valentina Emilia",
title="Text Style Transfer: A Comprehensive Study on Methodologies and Evaluation",
booktitle="Big Data, Machine Learning, and Applications",
year="2024",
publisher="Springer Nature Singapore",
address="Singapore",
pages="269--284",
abstract="Text Style Transfer (TST) rewords a sentence from one style (e.g., polite) to another (e.g., impolite) while conserving the meaning and content. This domain has attracted the attention of many researchers as it makes natural language generation (NLG) tasks more user-oriented. TST finds its applications widely in industry such as conversational bots and writing assistance tools. With the success of deep learning, a plethora of research works on style transfer based on machine learning have been proposed, developed, and tested. This systematic review presents the past work on TST clustered into categories based on machine learning and deep learning algorithms. It briefly explains the various subtasks within TST and assembles its publicly available datasets. It also summarizes the automatic and manual evaluation practices used for style transfer tasks and finally, sheds some light on current challenges and points towards promising future directions for research in the TST domain.",
isbn="978-981-99-3481-2"
}
```

