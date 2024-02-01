This project was developed in order to join SemEval 2024 Task 10: Emotion Discovery and Reasoning its Flip in Conversation (EDiReF) challenge. Th definition of the challenge states:

-  ERC: Given a dialogue, ERC aims to assign an emotion to each utterance from a predefined set of possible emotions.
-  EFR: Given a dialogue, EFR aims to identify the trigger utterance(s) for an emotion-flip in a multi-party conversation dialogue.

Challenge link : https://lcs2.in/SemEval2024-EDiReF/
Dataset link: https://drive.google.com/drive/folders/16mFdhXGECdcyDjLs_alI43W4iNQK_47B


# SemEval 2024 Task 10: Emotion Discovery and Reasoning (EDiReF) Challenge

## Overview
This project was developed for the SemEval 2024 Task 10: Emotion Discovery and Reasoning in Conversations (EDiReF) challenge. The challenge involves two sub-tasks: ERC (Emotion Recognition in Conversation) and EFR (Emotion-Flip Reasoning). More details about the challenge can be found "https://lcs2.in/SemEval2024-EDiReF/".

## Dataset
The dataset used in this study is derived from MELD (Soujanya Poria, 2019), a resource designed for in-depth analysis of emotions and sentiments in dialogues extracted from movies. The specific dataset utilized for ERC and EFR tasks consists of 4000 short English dialogues extracted from the TV series Friends. Each utterance includes information such as the speaker’s name, emotion label, and a binary trigger label indicating whether the utterance served as a trigger for the dialogue.

The data was extracted, shuffled at the dialogue level, and structured into a Pandas DataFrame. After preprocessing, the dataset was tokenized using the Hugging Face Transformers library, specifically the autotokenizer of the chosen BERT architecture ("bert-base-uncased") was used.

## Introduction
The Emotion Recognition in Conversations (ERC) task is crucial in natural language processing, impacting applications like e-commerce, social media, and healthcare. This project delves into dialogues, revealing emotional dynamics within conversations, which is vital for understanding interpersonal communication and enhancing human-computer interaction.

Expanding the ERC task to Emotion-Flip Reasoning (EFR) adds another layer of significance by identifying trigger utterances inducing changes in emotional trajectories during a conversation. ERC and EFR play vital roles in unraveling the complexities of human emotions within dynamic conversational contexts.

## Model Architecture
[Include the previously provided information about model architecture here]

## Implementation
[Include the previously provided information about implementation here]

## Usage
[Include the previously provided information about usage here]

## Results
[Include the previously provided information about results here]

## Contact Information
For any questions or collaboration opportunities, feel free to reach out:
- eodardosaturno@gmail.com

## Detailed Documentation
For a comprehensive understanding of the project, refer to our detailed paper:
[Link to Paper](path/to/paper.pdf)

