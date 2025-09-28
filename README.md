# Chicken Disease Classification

## Project Overview
This project implements a deep learning model to classify chicken diseases from images. The system can identify various poultry diseases, helping in early detection and treatment.

## Tech Stack Used
* Python 3.8
* TensorFlow
* DVC (Data Version Control)
* Machine Learning
* Deep Learning
* AWS

## Features
- Image-based disease classification
- Support for multiple disease categories
- Easy-to-use interface
- Model training and evaluation pipeline
- AWS integration for deployment

## How to Run?

### Step 1: Clone the repository
```bash
git clone https://github.com/neerajgoud23/Chicken-Disease-Classifiaction-Project.git
```

### Step 2: Create a conda environment
```bash
conda create -n chicken python=3.8 -y
conda activate chicken
```

### Step 3: Install Requirements
```bash
pip install -r requirements.txt
```

### Step 4: Run the application
```bash
python app.py
```

## Project Structure
```
Chicken-Disease-Classification/
├── artifacts/
├── config/
│   └── config.yaml
├── docs/
├── research/
│   └── trials.ipynb
├── src/
│   └── cnnClassifier/
├── templates/
├── Dockerfile
├── README.md
├── setup.py
└── requirements.txt
```

## DVC Commands Used
```bash
dvc init
dvc repro
dvc dag
```

## AWS Deployment
The project can be deployed on AWS using:
- AWS S3 for model storage
- AWS ECR for Docker image
- AWS EC2 for deployment

## Docker Build & Run
```bash
docker build -t chicken-disease-classifier .
docker run -p 8080:8080 chicken-disease-classifier
```

## CICD Pipeline
The project includes a GitHub Actions workflow for:
- Continuous Integration
- Continuous Delivery
- Continuous Deployment

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
* Deep Learning techniques for image classification
* TensorFlow and Keras documentation
* AWS documentation for deployment

## Contact
- Name: Your Name
- Email: your.email@example.com
- GitHub: [Your GitHub Profile](https://github.com/neerajgoud23)

## Future Improvements
- [ ] Add support for more disease categories
- [ ] Improve model accuracy
- [ ] Add mobile application support
- [ ] Implement real-time classification

## Contribution Guidelines
1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## Project Status
Project is: _in progress_


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml