# 🛡️ CGAN for Fake Task Detection in Mobile Crowdsensing Systems (MCS) 📱

Welcome to the repository for utilizing Conditional Generative Adversarial Networks (CGANs) to attack and detect fake tasks in Mobile Crowdsensing Systems (MCS). This project explores advanced techniques in synthetic task generation and detection, combining classic machine learning models with cutting-edge GAN technology.

![](./images/0_F-9UzpCOQlQtWi__.gif)
## 📜 Table of Contents
- [Project and Dataset Overview](#-project-and-dataset-overview)
- [Setup](#️-setup)
- [Installation](#-installation)
- [Usage](#-usage)
- [Results](#-results)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)
## 📊 Project and Dataset Overview
### <b>What is Mobile Crowdsensing?</b>

Mobile Crowdsensing is a technique where individuals with mobile devices (smartphones, tablets, wearables) collectively share data to analyze and infer various processes of common interest. This involves crowdsourcing sensor data from mobile devices to achieve a collective goal.

### Project Objective
Our objective is to generate intelligent fake tasks using GANs and evaluate detection accuracy for both original and GAN-generated fake tasks. We employ classic ML models (Random Forest and AdaBoost) and a GAN-based cascade detection framework.

## Dataset
The dataset is generated using the CrowdSenSim simulation tool and includes legitimate and fake tasks with attributes such as:

- ID
- Latitude
- Longitude
- Day
- Hour
- Minute
- Duration
- Remaining Time
- Battery Requirement %
- Coverage
- Legitimacy
- Grid Number
- Onpeak Hour

The dataset consists of 14,484 tasks (12,587 legitimate and 1,897 fake).

## 🛠️ Setup
To get started, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
```

2. Navigate to the project directory:

```bash
cd your-repo
```

## 📦 Installation
Install the required packages:


```bash
pip install -r requirements.txt
```

## 🚀 Usage
open notebook [c-gans-in-attack-and-product-the-system.ipynb](notebooks/c-gans-in-attack-and-product-the-system.ipynb) and follow steps to train and evaluation model 
## 📈 Results
Results will be showed on notebook [c-gans-in-attack-and-product-the-system.ipynb](notebooks/c-gans-in-attack-and-product-the-system.ipynb)

## 🤝 Contributing
We welcome contributions to this project! If you have suggestions or improvements, please follow these steps:

1. Fork the repository.

2. Create a feature branch:

```bash
git checkout -b feature/your-feature
```

3. Commit your changes:
```bash
git commit -m 'Add some feature'
```

4. Push to the branch:

```bash
git push origin feature/your-feature
```

5. Open a pull request.

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.


## 📬 Contact
For any inquiries, please contact us at mohamedbekheet33@gmail.com