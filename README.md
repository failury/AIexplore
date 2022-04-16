##  

##  

## Reviewed paper: [Directed Acyclic Graph Network for Conversational Emotion Recognition](https://aclanthology.org/2021.acl-long.123.pdf)

Ruifeng Zhang/ CS 541/ rzhang66@stevens.edu

 

# Abstract

The researchers are trying to find a better way to model emotion recognition from conversations. The paper proposed a novel idea of encoding the utterances with a directed acyclic graph (DAG) to better model the intrinsic structure within a conversation and designed a directed acyclic neural network model. The result is positive and demonstrated the superiority of this new model.

**Repo link**: https://github.com/failury/CS-541-optional-project

 

# Data

There are 4 different datasets.

[DailyDialog](https://paperswithcode.com/dataset/dailydialog): Human-written dialogs collected from communications of English learners. 7 emotion labels are included: neutral, happiness, surprise, sadness, anger, disgust, and fear. Since it has no speaker information, we consider utterance turns as speaker turns by default.

[EmoryNLP](https://paperswithcode.com/dataset/emorynlp): TV show scripts collected from Friends, but varies from MELD in the choice of scenes and emotion labels. The emotion labels of this dataset include neutral, sad, mad, scared, powerful, peaceful, and joyful.

[IEMOCAP](https://paperswithcode.com/dataset/iemocap): A multimodal ERC dataset. Each conversation in IEMOCAP comes from the performance based on a script by two actors. Models are evaluated on the samples with 6 types of emotion, namely neutral, happiness, sadness, anger, frustration, and excitement. Since this dataset has no validation set, we follow Shen et al. (2020) to use the last 20 dialogues in the training set for validation.

[MELD](https://paperswithcode.com/dataset/meld): A multimodal ERC dataset collected from the TV show Friends. There are 7 emotion labels including neutral, happiness,surprise, sadness, anger, disgust, and fear.

 