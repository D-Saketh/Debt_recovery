Project Title
Smart Debt Recovery – Next Best Action Prediction
Overview
This project focuses on predicting the probability that a recommended debt collection action (WhatsApp, AI voice bot, human call, or field visit) will successfully recover payment. The goal is to enable cost-aware decision-making by matching borrower behavior with the most effective recovery channel.
Problem Statement
Debt recovery involves multiple channels with very different costs. Using an expensive field visit for a borrower who would have paid via WhatsApp wastes resources, while relying only on digital channels for unresponsive borrowers delays recovery. This project addresses this challenge by estimating action-level success probabilities.
Approach
Raw interaction logs from WhatsApp, SMS, AI voice bots, human calls, and field visits are aggregated at the borrower level to create a Customer 360 view. These features capture engagement, responsiveness, and escalation history. A machine learning model is trained to predict the probability that the suggested action will lead to successful payment.
Prediction Target
TARGET: Probability (0–1) that the recommended action for a borrower will result in payment.
Tools & Technologies
Python
Pandas, NumPy, Scikit-learn
TensorFlow / Keras (modeling)
Kaggle Notebook / Google Colab
Outcome
The model outputs probabilities used by the evaluation system to select the most cost-effective action, improving recovery efficiency and reducing unnecessary operational costs.
