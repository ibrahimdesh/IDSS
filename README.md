# Intelligent Decision Support System for Optimal Football Player Recruitment
This repository contains the code and report for an Intelligent Decision Support System (IDSS) that supports data‑driven player recruitment and team building in professional football. The system combines dual deep learning models with a three‑tier architecture to rank players by intrinsic performance and predict their market value, helping stakeholders identify undervalued transfer targets under tactical and financial constraints.
The system features a **Dual-Model Architecture** that acts as an objective "Second Opinion" for sporting directors:
1.  **Performance Model:** Predicts a player's objective quality (0-100 Rating) based on 30+ technical stats.
2.  **Financial Model:** Estimates a player's "Fair Market Value" to identify undervalued (bargain) or overvalued (hype) assets.

## 🚀 Key Features in the Three-Ter Architecture (Data, Model and Interface)
* **Dual-Core AI:** Decoupled neural networks for Performance (Ranking) and Valuation (Price).
* **Data Pipeline:** Robust ETL process handling duplication, skewness (Log-Transform), and categorical encoding.
* **Value Delta Analysis:** Automatically calculates the difference between *Actual Market Value* and *Predicted Fair Value*.
* **Decision Dashboard:** A user-friendly interface (Gradio) for non-technical stakeholders to filter candidates by Budget, Role, and Age.

## 🖥️ Live Demo
You can try the Intelligent Decision Support System directly in your browser via Hugging Face Spaces.
👉 **Live app:** https://huggingface.co/spaces/MUmairAB/football-player-idss
