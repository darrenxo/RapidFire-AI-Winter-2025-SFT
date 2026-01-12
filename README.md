# RapidFire AI Winter Competition — SFT Track

This repository contains my submission for the RapidFire AI Winter Competition (SFT Track).

## Overview
- Task: Customer support Q&A fine-tuning
- Base model: TinyLlama-1.1B-Chat
- Dataset: Bitext Customer Support
- Approach: LoRA-based SFT with structured experimentation using RapidFire AI

## Repository Structure
- `notebooks/`: End-to-end Colab notebook
- `artifacts/`: RapidFire logs and TensorBoard artifacts
- `screenshots/`: Key metric visualizations used in submission

## How to Run
Open `notebooks/RapidAI_Winter_2025_SFT.ipynb` in Google Colab and run all cells top-to-bottom.

## Notes
- Runs 1 and 3 were stopped early due to slow convergence.
- Runs 9 and 10 were created via clone–modify for LoRA ablation analysis.
