# End-to-End-Waste-Object-Detection-with-YOLOv5
This project utilizes the YOLOv5 model for detecting waste objects in images, aiming to contribute towards efficient waste management and recycling efforts. It encompasses a full machine learning pipeline from setting up the environment, processing the data, training the model, to deploying it for inference.

## Table of Contents
- Project Setup
- Workflow
- How to Run

## Project Setup
### Prerequisites
- Python 3.8+
- PyTorch 1.7+
- YOLOv5 dependencies
- Anaconda or Miniconda installed on your machine.

### Installation
1. Clone the repository:
```bash
git clone https://github.com/Kanon14/End-to-End-Waste-Object-Detection-with-YOLOv5.git
cd End-to-End-Waste-Object-Detection-with-YOLOv5
```

2. Create and activate a Conda environment:
```bash
conda create -n waste python=3.8 -y
conda activate waste
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Workflow
The project's workflow is designed to facilitate a smooth transition from development to deployment:

1. `constants`: Manage all fixed variables and paths used across the project.
2. `entity`: Define the data structures for handling inputs and outputs within the system.
3. `components`: Include all modular parts of the project such as data preprocessing, model training, and inference modules.
4. `pipelines`: Organize the sequence of operations from data ingestion to the final predictions.
5. `app.py`: This is the main executable script that ties all other components together and runs the whole pipeline.

## How to Run
1. Follow these steps to execute the project:
```bash
python app.py
```
2. Access the application:
```bash
open up you local host and port
```

# Author Information
- Name: [Kanon14](https://github.com/Kanon14)
- Note: This project was created by Kanon14. If you find any issues, have questions, or want to provide feedback, please don't hesitate to reach out. Thank you for exploring this project!