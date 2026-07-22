# Mesh Generation using Deep Learning

ANN-based mesh generation for object detection. This project explores how artificial neural networks — including MLPs and CNNs — can be used to generate or refine meshes over objects, as an alternative/complement to traditional geometric or bounding-box based detection pipelines.

##  Repository Structure

```
Mesh-Generation-using-deep-learning/
├── Images/                     # Sample images / dataset visuals used in the project
├── Models/                     # Saved/trained model files
├── DSP_MLP.ipynb                # MLP (Multi-Layer Perceptron) based approach
├── DSP_Proj_3.ipynb             # Core project notebook / experiments
├── DSP_Proj_CNN_2.ipynb         # CNN-based mesh generation approach
├── Demo_with_CNN.ipynb          # End-to-end demo using the CNN model
├── ANN_DSP_Report_v2.docx       # Project report
├── DSP PPT V2.pptx              # Project presentation slides
└── README.md
```

##  Overview

The goal of this project is to generate mesh representations of objects in images using deep learning models, with applications in object detection. Two neural network architectures are explored:

- **MLP (Multi-Layer Perceptron)** — `DSP_MLP.ipynb`
- **CNN (Convolutional Neural Network)** — `DSP_Proj_CNN_2.ipynb`, `Demo_with_CNN.ipynb`

The `DSP_Proj_3.ipynb` notebook contains the core experiments tying the approaches together, and `Demo_with_CNN.ipynb` provides a runnable demonstration of the final CNN-based pipeline.

Full methodology, results, and analysis are documented in `ANN_DSP_Report_v2.docx` and summarized in `DSP PPT V2.pptx`.

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab
- Common deep learning / data science libraries, typically including:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `tensorflow` or `torch` (depending on the notebook)
  - `opencv-python`
  - `scikit-learn`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Penumalanavadeep-source/Mesh-Generation-using-deep-learning.git
   cd Mesh-Generation-using-deep-learning
   ```

2. (Recommended) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install numpy pandas matplotlib tensorflow opencv-python scikit-learn jupyter
   ```

   > **Note:** Since dependencies aren't pinned in a requirements file yet, check the import statements at the top of each notebook and install any additional packages as needed.

### Usage

1. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
2. Open one of the following notebooks depending on what you want to explore:
   - `DSP_MLP.ipynb` — to run the MLP-based approach
   - `DSP_Proj_CNN_2.ipynb` — to run the CNN-based approach
   - `DSP_Proj_3.ipynb` — for the combined/core experiments
   - `Demo_with_CNN.ipynb` — for a quick end-to-end demo
3. Run the cells in order. Trained models are saved to / loaded from the `Models/` folder, and sample outputs/visuals can be found in the `Images/` folder.

##  Results & Documentation

For a detailed explanation of the problem statement, methodology, model architectures, and results, refer to:
- **Report:** [`ANN_DSP_Report_v2.docx`](./ANN_DSP_Report_v2.docx)
- **Presentation:** [`DSP PPT V2.pptx`](./DSP%20PPT%20V2.pptx)

## 🛠️ Tech Stack

- **Language:** Python (Jupyter Notebook)
- **Core techniques:** Artificial Neural Networks (ANN), Multi-Layer Perceptrons (MLP), Convolutional Neural Networks (CNN)
- **Application area:** Mesh generation for object detection

##  Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the [issues page](https://github.com/Penumalanavadeep-source/Mesh-Generation-using-deep-learning/issues) if you want to contribute.

## 📄 License

No license has been specified for this repository yet. Please contact the repository owner if you'd like to use this project beyond personal/educational purposes.

## 👤 Author

**Penumalanavadeep-source**
[GitHub Profile](https://github.com/Penumalanavadeep-source)
