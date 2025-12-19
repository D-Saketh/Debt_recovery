Smart Debt Recovery – Next Best Action Prediction

📌 Objective

To predict the probability that a recommended debt collection action (WhatsApp, AI voice bot, human call, or field visit) will successfully result in payment, enabling cost-effective recovery decisions.

🧠 Problem Overview

Different recovery channels have different costs and effectiveness. Low-cost digital actions may work for responsive borrowers, while others require escalation. Choosing the wrong action leads to wasted resources and delayed recovery.

📊 Data & Feature Engineering

Borrower interaction data from WhatsApp, SMS, AI bots, human calls, and field visits is aggregated using a Customer 360 approach. Features capture engagement, responsiveness, sentiment, call outcomes, and escalation history, along with loan-level attributes.

⚙️ Modeling Approach

A machine learning model is trained to predict TARGET, the probability (0–1) that the suggested action will succeed. The model learns how borrower behavior interacts with different recovery channels.

🎯 Outcome

The predicted probabilities support cost-aware decision-making by helping select the most effective action per borrower, improving recovery efficiency while minimizing unnecessary operational costs.

🛠️ Tools Used

Python, Pandas, NumPy, Scikit-learn, TensorFlow, Kaggle Notebook
