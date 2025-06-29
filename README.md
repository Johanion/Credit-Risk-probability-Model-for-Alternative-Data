# Credit-Risk-probability-Model-for-Alternative-Data
- Using machine learning to predict customer credit risk for Buy-Now-Pay-Later services by analyzing behavioral data (RFM). The model estimates default probability, generates a credit score, and recommends optimal loan terms.


## Installation
1. Clone the repo: `git clone https://github.com/Johanion/Credit-Risk-probability-Model-for-Alternative-Data.git`
2. Navigate to the folder: `cd project`
3. Install dependencies: `npm install` or `pip install -r requirements.txt`


## credit scoring business understanding

- The **Basel II Accord** emphasizes accurate risk measurement and regulatory compliance, making it essential to build **interpretable and transparent credit scoring models**. Regulators and internal auditors must understand how risk is assessed, which means models should be well-documented, explainable, and auditable.

- Due to the lack of a direct **"default" label** in the dataset, creating a **proxy variable** is necessary to approximate credit risk. However, relying on proxies introduces potential **business risks**, such as mislabeling customers, biased model behavior, and regulatory scrutiny if the proxy doesn’t reflect real-world outcomes accurately.

- In regulated environments like banking, the trade-off between model **interpretability** and **performance** is critical. Simple models like **Logistic Regression with Weight of Evidence (WoE)** offer high transparency and compliance ease but may sacrifice accuracy. Complex models like **Gradient Boosting** can achieve better predictive performance but pose challenges in explainability, governance, and acceptance by risk and compliance teams. The ideal approach often balances both—leveraging interpretable models for core decisions and using advanced models with explainability techniques where performance gains are justified.

## How to tweak this project for your own uses
- To customize this project for your specific needs, update the configuration files and input data sources to reflect your environment. Modify feature selection and model parameters to align with your dataset and business goals. Feel free to extend the codebase by adding new modules or improving existing algorithms to better suit your credit scoring requirements. Be sure to thoroughly test any changes before deploying in a production environment

