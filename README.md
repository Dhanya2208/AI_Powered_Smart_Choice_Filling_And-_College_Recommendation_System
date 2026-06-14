🚀 Overview

TNEA Counsellor is a full-stack web application that helps Tamil Nadu engineering aspirants make data-driven decisions during the TNEA (Tamil Nadu Engineering Admissions) counselling process. It combines three AI-powered tools into a single, polished portal modelled after Shiksha.com and CollegeDunia:


🎯 ML Cutoff Predictor — Random Forest Regressor trained on 25,309 historical records across 3 years, predicting cutoffs for 600+ colleges and 7 community categories
💬 AI Counsellor Chatbot — GPT-4o-mini with TNEA-specific system prompt, 10-turn conversation history, and quick-topic navigation
🏫 College Explorer — On-demand AI-generated structured profiles with rankings, branches, placements, facilities, and pros/cons

Categorisation Logic

Category              Condition (diff = your cutoff − predicted cutoff)
🟢 Safe              diff ≥ 3.0 — Comfortably above predicted
🟠 Ambitious         −5.0 ≤ diff < 3.0 — Within competition zone
🔴 Dream             diff < −5.0 — Predicted exceeds your score

🛠️ Tech Stack

Layer Technology Backend         Python 3.10+ · Flask 3.x
Machine Learning                 scikit-learn — Random Forest Regressor · Label Encoder
LLM                              gpt 4omini
