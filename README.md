# Gene Length Prediction using PyTorch
<center>
<img src="extras/neural_network.jpg" width="80%" alt="Genome Architecture">
</center>
---

## Scope of the Project
This project aims to bridge the gap between biological insights and computational modeling to predict gene lengths. By leveraging a combination of biological features (such as gene expression and replication timing) and physical attributes (like surface accessibility and DNA structural properties), the project explores how machine learning can enhance our understanding of genome characteristics. The use of PyTorch provides a robust framework for creating scalable and efficient neural networks tailored to this genomic application.

This project also sets the groundwork for future integration of additional omics data to improve model accuracy and expand its applicability to other areas of genomics research.

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
   - Replication Timing
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


## Contribution
Feel free to open issues or submit pull requests to improve the project. Contributions are welcome!

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Future Prospects
Looking forward, this project has the potential to:

1. Incorporate additional omics data, such as epigenomic or proteomic features, for enhanced predictive accuracy.
2. Utilization of the Convolutional Neural Networks to find broad hidden trends in the data.
3. Explore cross-species comparisons to generalize the model across different organisms.
4. Develop real-time gene length prediction tools integrated into bioinformatics pipelines.
5. Extend the framework to predict other genomic properties, such as exon lengths or transcription start site positions.

## Acknowledgements
- [PyTorch](https://pytorch.org/)
- The dataset and feature extraction methods from the [Biological vs Physical Genome](https://github.com/h4rrye/biological_vs_physical_genome) project.
- Inspiration from genomics research and computational biology literature.
  
