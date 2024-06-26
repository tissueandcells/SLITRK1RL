# SLITRK1RL

This repository contains a Reinforcement Learning (RL) project aimed at analyzing the pharmacological interactions between SLITRK1 protein variants and FDA-approved drugs. The project employs the Proximal Policy Optimization (PPO) algorithm to model and optimize these interactions. The dataset used includes docking scores for various SLITRK1 variants with four drugs: Pimozide, Risperidone, Aripiprazole, and Haloperidol. The custom gym environment simulates the docking process, where the RL agent learns to select the drug that maximizes the binding affinity for each variant. The results show that Aripiprazole consistently yields the highest rewards across multiple variants, indicating its strong binding affinities. Detailed analyses and visualizations of the actions, rewards, and cumulative rewards are provided to highlight the model's performance and findings. This project demonstrates the potential of RL in drug discovery and optimization, offering insights into effective drug-variant interactions.

# SLITRK1 Protein Variant Interaction Analysis

This repository contains a Reinforcement Learning (RL) project aimed at analyzing the pharmacological interactions between SLITRK1 protein variants and FDA-approved drugs. The project employs the Proximal Policy Optimization (PPO) algorithm to model and optimize these interactions.

## Installation

To install the required packages, run:
```bash
pip install -r requirements.txt
