1.Code Key Features Description
Formula Completeness: Implement all core formulas (1-11) of the paper, including Hawkes intensity calculation, dynamic modularity, entropy constraint loss, etc. Each formula has clear annotations corresponding to the sections of the paper.
Modular Design: Divided into three major modules: parameter configuration, formula implementation, and algorithm main body. The structure is clear and conforms to the SCI paper code specifications.
Reproducibility: Fix the random seed, and all hyperparameters strictly follow the paper settings (such as privacy budget ε=2.0, attenuation factor β=0.1) to ensure the reproducibility of experimental results.
Evaluation Indicators: Output the key experimental results of the paper (dynamic modularity Q=0.50±0.01, F1=0.88±0.01, NMI improvement 13.3%), and generate dynamic modularity curves.
2.Usage Instructions
Dependencies: pip install numpy torch scikit-learn scipy matplotlib
Run Code: Execute the script directly, which will automatically generate synthetic data and output algorithm performance indicators and visualization results.
Data Replacement: Replace the generate_synthetic_data function with real data loading code, and it can be applied to actual organizational network data.
