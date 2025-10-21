# drug-repurposing-tool
Prototype tool for drug repurposing using Open Targets Platform data. Enables exploration of drug-target relationships, prioritization, and interactive visualization of repurposing candidates.


## Getting Started:
1. **Clone the repository**
2. Install dependencies
   pip install -r requirements.txt
3. Run the Streamlit app
   streamlit run app/main.py

## Project Structure:
RepurposAI/
├── README.md
├── requirements.txt
├── .gitignore
├── app/
│   ├── main.py              # Streamlit main app
│   ├── dashboard.py         # Dashboard assembly module
│   ├── visualization.py     # Plotly/Seaborn visualization module
│   └── utils/
│       └── similarity.py    # Drug-target similarity functions
├── backend/
│   ├── data_cleaning.py     # Data preprocessing
│   └── repurposing_logic.py # Drug repurposing scoring & analysis
├── data/                     # Sample Excel/CSV datasets
├── docs/                     # README, usage guide, hackathon slides
├── tests/                    # Test scripts for backend/utility functions
└── notebooks/
    └── example_notebook.ipynb


## Hackathon Steps: 

Fork the repository and pick tasks from the GitHub Epic (#9).

Implement placeholder modules in #/app and #/app/utils.

Add sample notebooks in /notebooks to test modules.

Build Streamlit pages in /app/main.py and /app/dashboard.py.

Commit work regularly and create issues/sub-issues for new features or bugs.

Tag issues with relevant labels: backend, frontend, Data Collection, Pre processing , visualization , streamlit, rdkit.

## Expected Outcomes:

1. Functional web app to explore drug repurposing opportunities

2. Prioritization of drug candidates based on target, mechanism of action, and effect direction

3. Interactive visualizations for target-disease-drug relationships

4. Demo-ready for hackathon presentation

