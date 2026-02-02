This repository contains datasets and scripts for analyzing the Stack Overflow forum issues data. The goal is to analyze trends, identify challenges, and provide actionable implications for LLM developers and providers.

------

## File Structure and Descriptions

### Figures Folder (`Figures/`)

- This folder contains all the figures used in the associated research paper, including charts, diagrams, and visualizations.

### Dataset Folder(`Dataset/`)

This folder contains data collected from Stack Overflow, with each post manually annotated to indicate its corresponding API type.

- **`Stack Overflow Posts with Type.csv`**: Stack Overflow issues data related to OpenAI APIs.
- **`Stack Overflow Posts After Manual Inspection.csv`**: Stack Overflow issue data related to OpenAI APIs after manual  inspecting and filtering.

### Code Folder (`Code/`)

1. **RQ1 Analysis and Visualization**:  Python scripts in a Jupyter Notebook for determining the popularity trend of OpenAI APIs discussions.
2. **RQ2 Analysis and Visualization**: Python scripts in a Jupyter Notebook for determining The difficulty with each OpenAI API category.
3. **RQ3 Analysis and Visualization**: Python scripts in a Jupyter Notebook for identifying the topics discussed in the research questions to understand the challenges developers face when using OpenAI APIs.

------

## Quick Start

1. **Prepare the Environment**

   Ensure Python 3.8+ is installed along with the necessary dependencies:

   ```
   pip install -r requirements.txt
   ```

2. **Run Scripts and Analyze Data**

   For popularity, difficulty, and topic model analysis, refer to the scripts and data located in the RQ1, RQ2, and RQ3 Analysis and Visualization folders. These files provide the necessary data for exploring and refining the challenges.

------

## Project Goals

- Conduct the empirical study to investigate the challenges developers face when using OpenAI APIs.

- By manually categorizing these posts into nine OpenAI API categories and applying topic modeling techniques, we identify common challenges for each category.

- Provide actionable implications for LLM developers and providers, aiming to help them improve API design, enhance documentation support, and increase compatibility.

Contributions and feedback are welcome!