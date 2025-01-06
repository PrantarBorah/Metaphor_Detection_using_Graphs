# Metaphor Detection using Machine Learning

## Project Overview

This project presents an approach to **metaphor detection** using relevant machine learning techniques. The key challenges addressed include:

- Context-dependence of metaphoric expressions
- Subtle variations across different domains

The pipeline involves preprocessing the dataset, utilizing machine learning models (traditional feature-based classifiers and modern neural networks with contextual embeddings), and analyzing their performance. The final model embeddings and outputs are included for reference.

---

## Repository Structure

```plaintext
.
|-- train.csv                      # Training dataset
|-- test.csv                       # Testing dataset
|-- requirements.txt               # Required Python dependencies
|-- final_model/                   # Folder containing the model embeddings and outputs
    |-- GNN_optimal_state_dict.pth # Model Weights
    |-- predictions.csv            # Predicted output
|-- README.md                      # Instructions for setup and usage
```

---

## Prerequisites

To run this project, ensure you have:

- **Python 3.10** installed on your system.
- Basic knowledge of Python and machine learning concepts.

---

## Installation

Follow these steps to set up the project:

1. **Unzip the Folder**

   ```bash
   unzip group_3.zip
   cd group_3
   ```

2. **Set up a virtual environment** (optional but recommended):

   ```bash
   python3.10 -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

---

## How to Run the Project

Follow these steps to train, test, and evaluate the model:

1. **Prepare the Data**:
   Ensure the `train.csv` and `test.csv` files are in the project directory.

2. **Run the Training Script**:
   If a script is provided to train the model, run it as follows:

   ```bash
   python3.10 train.py
   ```

   **Example Input**:

   ```
   Enter Enter training dataset name:
   train-1.csv
   ```

3. **Evaluate the Model**:
   Use the test file to evaluate model performance:

   ```bash
   python3.10 test.py
   ```

   **Example Input**:

   ```
   Enter Enter testing dataset name:
   train-1.csv
   ```

4. **Access Model Outputs**:
   - The final model Weights and outputs can be found in the `final_model/` folder.

---

## Abstract

This project explores an approach to **metaphor detection** using machine learning techniques. Key aspects include:

- Identifying challenges such as context-dependence and domain variations.
- Preprocessing the dataset and implementing traditional feature-based classifiers alongside neural network models with contextual embeddings.
- Comparing model performances, analyzing error patterns, and discussing deployment considerations for metaphor detection systems.

---

## Future Directions

The project identifies areas for future improvement:

- Enhancing the model to handle diverse linguistic contexts.
- Improving generalization across multiple domains.
- Deploying the system for real-world applications.

---

## Contact

For questions or collaborations, please contact:

- **Your Name**: Aaashay Phirke
- **Email**: [aphirke@iu.edu](mailto:aphirke@iu.edu)
- **Your Name**: Fahad Mehfooz
- **Email**: [fmehfooz@iu.edu](mailto:fmehfooz@iu.edu)
- **Your Name**: Prantar Borah
- **Email**: [pborah@iu.edu](mailto:pborah@iu.edu)
- **Your Name**: Austin Ryan
- **Email**: [ar100@iu.edu](mailto:ar100@iu.edu)
