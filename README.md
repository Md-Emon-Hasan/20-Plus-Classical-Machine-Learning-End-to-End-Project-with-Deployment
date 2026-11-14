# Machine Learning Projects Portfolio

[![Python](https://img.shields.io/badge/Python-projects-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Notebooks-Jupyter-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Web apps](https://img.shields.io/badge/Web%20apps-Flask%20%7C%20Streamlit-000000?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![Scikit-learn](https://img.shields.io/badge/ML-scikit--learn-F7931E?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![NLP](https://img.shields.io/badge/Focus-NLP-6A5ACD)](#project-catalog)
[![Classification](https://img.shields.io/badge/Focus-Classification-2E8B57)](#project-catalog)
[![Regression](https://img.shields.io/badge/Focus-Regression-4682B4)](#project-catalog)
[![Recommendation](https://img.shields.io/badge/Focus-Recommendation-8A2BE2)](#project-catalog)
[![Clustering](https://img.shields.io/badge/Focus-Clustering-008B8B)](#project-catalog)
[![Deployment](https://img.shields.io/badge/Deployment-Docker%20%7C%20CI%2FCD-2496ED?logo=docker&logoColor=white)](#project-catalog)
[![Projects](https://img.shields.io/badge/Projects-20-2ea44f)](#project-catalog)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

<p align="center">
  <img src="banner.png" alt="Machine learning projects portfolio banner" width="100%">
</p>

A portfolio of **20 independent machine learning projects** covering supervised learning, natural language processing, recommendation, clustering, anomaly detection, and deployment. Projects include notebooks, datasets, trained artifacts, and interactive applications where available.

Each project lives in its own folder and has its own README. Dependency files and setup vary by project. There is no single application or dependency file at the repository root; choose a project below and follow its project-specific guide.

## Contents

- [Project catalog](#project-catalog)
- [Repository layout](#repository-layout)
- [Getting started](#getting-started)
- [Technology and workflow](#technology-and-workflow)
- [Datasets and model artifacts](#datasets-and-model-artifacts)
- [Contributing](#contributing)
- [License](#license)
- [Connect with me](#connect-with-me)

## Project catalog

| # | Project | Focus | Project guide |
|---:|---|---|---|
| 1 | Amazon Big Mart Sales Prediction | Retail sales regression | [Open project](ML-Project-Amazon-Big-Mart-Sales-Prediction/README.md) |
| 2 | Bengali Comments Sentiment Analysis | Bengali text classification | [Open project](ML-Project-Bangali-Comments-Sentiment-Analysis/README.md) |
| 3 | Bangalore House Price Prediction | Real estate price regression | [Open project](ML-Project-Bangalore-House-Price-Prediction/README.md) |
| 4 | Book Recommendation System | Collaborative filtering and recommendations | [Open project](ML-Project-Book-Recommendation-System/README.md) |
| 5 | Boston House Price Prediction | Regression, Docker, deployment | [Open project](ML-Project-Boston-House-Price-Prediction-using-Docker-and-GitHub-Action-with-Deployment/README.md) |
| 6 | Car Price Prediction | Vehicle price regression | [Open project](ML-Project-Car-Price-Prediction/README.md) |
| 7 | Customer Segmentation | RFM analysis and clustering | [Open project](ML-Project-Customer-Segmentation/README.md) |
| 8 | Diabetes Prediction | Health classification | [Open project](ML-Project-Diabetes-Prediction/README.md) |
| 9 | Email/SMS Spam Classifier | Text classification and MLOps | [Open project](ML-Project-Email-SMS-Spam-Classifier-with-MLOps/README.md) |
| 10 | Heart Disease Prediction | Health classification | [Open project](ML-Project-Heart-Disease-Prediction/README.md) |
| 11 | Image Classifier | Image classification with Flask | [Open project](ML-Project-Image-Classifier-using-Flask/README.md) |
| 12 | Network Intrusion Detection | Anomaly detection and classification | [Open project](ML-Project-Intrusion-Detection-Systems-Anomaly-Detection-with-ML-DL/README.md) |
| 13 | Iris Flower Classifier | Multiclass classification, Docker, deployment | [Open project](ML-Project-Iris-Classifier-using-Docker-and-GitHub-Action-with-Deployment/README.md) |
| 14 | Laptop Price Prediction | Product price regression | [Open project](ML-Project-Laptop-Price-Prediction/README.md) |
| 15 | Movie Recommender System | Content-based recommendations | [Open project](ML-Project-Movie-Recommender-System/README.md) |
| 16 | Amazon Fine Food Reviews Sentiment Analysis | Review text classification | [Open project](ML-Project-Sentiment-Analysis-of-Amazon-Fine-Food-Reviews/README.md) |
| 17 | Student Performance Prediction | Regression pipeline, Docker, CI/CD | [Open project](ML-Project-Student-Performance-Prediction-using-Docker-and-CI-CD-Pipeline/README.md) |
| 18 | T20 Cricket Match Score Prediction | Sports score regression | [Open project](ML-Project-T20-Cricket-Match-Score-Prediction/README.md) |
| 19 | Titanic Survival Prediction | Binary classification | [Open project](ML-Project-Titanic-Survival-Prediction/README.md) |
| 20 | Telecom Customer Churn Prediction | Customer churn classification | [Open project](ML-Projects-Telcom-Customer-Churn-Prediction/README.md) |

Project folders contain different combinations of `app.py` or other entry points, `requirements.txt`, notebooks, `data/`, `models/` or `artifacts/`, templates, and static assets. See each project README for its exact files, model approach, inputs, and run instructions.

## Repository layout

```text
.
|-- README.md
|-- LICENSE
|-- ML-Project-Amazon-Big-Mart-Sales-Prediction/
|-- ML-Project-Bangali-Comments-Sentiment-Analysis/
|-- ML-Project-Bangalore-House-Price-Prediction/
|-- ...                         # 20 self-contained project directories
`-- ML-Projects-Telcom-Customer-Churn-Prediction/
```

An individual web project typically has a structure similar to this:

```text
project-folder/
|-- app.py                      # app entry point (name can vary)
|-- requirements.txt            # project-specific Python dependencies
|-- data/                       # source data, when included
|-- models/                     # serialized model and preprocessing files
|-- templates/                  # Flask HTML templates, when used
|-- static/                     # CSS, JavaScript, and images, when used
`-- README.md                   # project-specific setup and details
```

These are examples, not a promise that every project contains every directory. Some projects are notebook-focused or use a different app entry point.

## Getting started

### Prerequisites

- Git
- Python version specified by the selected project's README or dependency files
- `pip` and, for notebook workflows, Jupyter
- Docker only for projects that include and document a `Dockerfile`

### Set up a project

Clone the repository, enter the folder you want, then read its README before installing dependencies:

```bash
git clone https://github.com/Md-Emon-Hasan/20-Plus-Classical-Machine-Learning-End-to-End-Project-with-Deployment.git
cd 20-Plus-Classical-Machine-Learning-End-to-End-Project-with-Deployment
cd ML-Project-Iris-Classifier-using-Docker-and-GitHub-Action-with-Deployment
```

For a project that includes `requirements.txt`, create an isolated environment and install that folder's dependencies:

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\Activate.ps1
```

Activate it on macOS or Linux:

```bash
source .venv/bin/activate
```

Then install the selected project's requirements:

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

Run the command shown in that project's README. For example, the Iris Flask project can be started from its own directory with:

```bash
python app.py
```

Use the local URL printed by the application (commonly `http://127.0.0.1:5000/` for Flask). Do not install every project's requirements into one environment: dependency versions and app entry points differ between projects.

### Notebooks

For a notebook-based project, install that project's dependencies first, then launch Jupyter from its directory:

```bash
jupyter notebook
```

Open the notebook documented by that project's README. Notebook names and required data locations vary by project.

### Docker and deployment

Some projects include a `Dockerfile`, deployment manifest, or test files. These are project-specific. Check the selected project's README and configuration before building an image, running tests, or deploying. A configuration file in the repository does not guarantee that a hosted demo is currently available.

## Technology and workflow

Across the portfolio, the projects demonstrate combinations of:

- **Python** for data processing, model training, and inference.
- **Pandas** and **NumPy** for tabular data handling.
- **Scikit-learn** and other project-specific libraries for preprocessing, modeling, and evaluation.
- **Jupyter notebooks** for exploration, visualization, and experiments.
- **Flask** or **Streamlit** for interactive prediction and recommendation interfaces.
- **Docker** and CI/CD configuration in selected projects.

Typical end-to-end steps include loading a dataset, exploring and preparing features, training or loading a model, evaluating results, and exposing predictions through a notebook or application. The exact algorithms and metrics differ by project; consult its guide and notebook for specifics.

## Datasets and model artifacts

Some folders include datasets and serialized model files (`.pkl` or `.sav`) so an app can run without retraining. Other projects expect data to be prepared or downloaded as described in their own guide. Check dataset provenance, permitted use, and any external terms before redistributing data.

Only load serialized Python model files from sources you trust. Pickle-based formats can execute code when loaded. For medical, financial, educational, and security-related examples, predictions are for learning and demonstration and should not be treated as professional decisions.

## Contributing

Contributions that improve a project's code, documentation, reproducibility, or accessibility are welcome.

1. Fork the repository and create a focused branch.
2. Work inside the relevant project folder and follow its README.
3. Keep dependencies project-specific; document any new setup requirements.
4. Include or update tests when changing behavior, where that project has a test suite.
5. Open a pull request describing the change and how it can be reviewed.

## License

The repository-level [LICENSE](LICENSE) contains the Apache License 2.0. Dataset files, pretrained artifacts, images, and third-party materials may have separate terms; check their original sources before reuse.

## Connect with me

- **Portfolio:** [emonlabs-ai.hitechparks.com](https://emonlabs-ai.hitechparks.com)
- **GitHub:** [Md-Emon-Hasan](https://github.com/Md-Emon-Hasan)
- **LinkedIn:** [Md Emon Hasan](https://www.linkedin.com/in/md-emon-hasan-695483237/)
- **Hugging Face:** [emonHasan01](https://huggingface.co/emonHasan01)
- **Email:** [emon.mlengineer@gmail.com](mailto:emon.mlengineer@gmail.com)
- **WhatsApp:** [+880 1834-363533](https://wa.me/8801834363533)
