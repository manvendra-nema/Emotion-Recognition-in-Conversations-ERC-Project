# 📝 Emotion Recognition in Conversation (ERC) Project

This project is inspired by the paper “Discovering Emotion and Reasoning its Flip in Multi-Party Conversations using Masked Memory Network and Transformer.”

## 📂 Datasets
We are utilizing a modified version of the MELD-FR dataset for this task. The dataset has been split for training and validation.

## 📚 Project Overview: ERC (Emotion Recognition in Conversation)

### What is ERC?
Emotion Recognition in Conversation (ERC) is a specialized field focused on automatically identifying and interpreting emotional states expressed by individuals during conversations. Unlike traditional approaches that analyze emotions in isolated text, ERC aims to understand nuanced emotional dynamics in conversational exchanges involving multiple speakers. It benefits applications such as conversational agents and affective computing systems.

### Project Goals
1. Train two models (M1 & M2) with independent architectures different from the one mentioned in the referenced paper. If re-implementing the paper’s model architecture as one of the models, use the paper’s results as baselines and ensure the other model’s scores are comparable.
2. Both models should focus on emotion identification and detecting emotion flips within conversations. Reasoning for the shift is not required.
3. Submit both model checkpoints (M1 and M2) and report the better model with proper reasoning. These models will be tested on the provided testing data during demos.

## 🛠️ Model Setups

### Model M1: Custom Architecture 🧠
- **Description:** A unique model architecture designed for emotion recognition and emotion flip detection within conversations. Details and code are provided in the repository.
- ![image](https://github.com/user-attachments/assets/0d8de107-66df-4c11-9659-63f549b37636)


### Model M2: Custom Architecture 🧠
- **Description:** Another distinct model architecture focuses on the same goals as M1 but with a different approach. Details and code are provided in the repository.
- ![image](https://github.com/user-attachments/assets/3808c59d-2ef3-44a8-9b9a-7ca7f4ac5489)


## 📊 Evaluation Metrics
- **Emotion Identification Accuracy**
- **Emotion Flip Detection Accuracy**
- **Training and Validation Loss vs. Epochs**

## 📈 Deliverables
1. Model checkpoints for M1 and M2 in proper format.
2. Well-labeled model architectures for both M1 and M2. (If implementing the paper’s model, ignore this deliverable for one model but note the baselines.)
3. Clearly state which of the two architectures performed better and why.
4. A detailed report explaining the intuition behind the models, data splits, and all relevant details.
5. Training loss and validation loss vs. epochs plots for each model.
6. Answers to relevant viva questions.
