This repository contains an AI system designed to predict aircraft engine failure by analyzing noisy sensor data.

🧠 The Intelligence Behind the Project
This project bridges the gap between raw, messy engine data and reliable safety decisions. Most AI models fail because real world sensors are jittery and generate a lot of noise. This system solves this using a two-stage approach:
Statistical Smoothing: Stabilize the sensor signals to remove "noise."
Ensemble Voting: Use a Random Forest to vote on the engine's health, ensuring one bad sensor doesn't cause a false alarm.

📊 Final Performance
To ensure the results are trustworthy, the AI is tested on data it had never encountered before (an 80/20 "Blind Test"):
Proposed Solution (Random Forest): 97.04% Accuracy
Baseline (k-NN): 96.39% Accuracy
Baseline (Decision Tree): 96.46% Accuracy

To run the program, copy and paste the code into any Python environment. Next, download the .txt file, and in the DATA LOADING section of the code, update the read function so it loads the .txt file from its correct folder location.
