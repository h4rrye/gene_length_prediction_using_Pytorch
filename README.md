# Gene Length Prediction using PyTorch

<center>
<img src="extras/neural_network.jpg" width="80%" alt="Genome Architecture">
</center>
---

This project implements a machine learning model using PyTorch to predict gene lengths based on various biological features and physical attributes. The features and attributes are derived from analyses conducted in a prior project: [Biological vs Physical Genome](https://github.com/h4rrye/biological_vs_physical_genome).

## Overview
Predicting the length of a gene has numerous applications in genomics, such as understanding gene function, genome organization, and evolutionary biology. This project utilizes neural networks to build predictive models by leveraging:

- Biological features (e.g., replication timing, gene expression levels).
- Physical attributes (e.g., surface accessibility, DNA structural properties).

## Features
- **PyTorch Implementation**: Neural networks designed and trained using PyTorch.
- **Flexible Data Input**: Reads biological and physical feature data as input.
- **Customizable Models**: Easily modify the architecture and hyperparameters.
- **Visualization**: Performance metrics and feature importance visualized for better interpretation.

## Dataset
The dataset is based on outputs from the [Biological vs Physical Genome](https://github.com/h4rrye/biological_vs_physical_genome) project. Ensure you have the following features available:

1. Biological features:
   - Gene expression
   - Gene expression levels
   - Expression breadth

2. Physical attributes:
   - Total surface accessibility area
   - Radius of Gyration
   - Other physical measurements

The processed dataset should include these features and the target variable (gene length).

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/h4rrye/pytorch_gene_length_pred.git
   cd pytorch_gene_length_pred
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Results
Key performance metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared are reported for model evaluation. 

Example visualization:
- Feature importance plots.
- Predictions vs actual gene lengths.

## Contribution
Feel free to open issues or submit pull requests to improve the project. Contributions are welcome!

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [PyTorch](https://pytorch.org/)
- The dataset and feature extraction methods from the [Biological vs Physical Genome](https://github.com/h4rrye/biological_vs_physical_genome) project.
- Inspiration from genomics research and computational biology literature.
