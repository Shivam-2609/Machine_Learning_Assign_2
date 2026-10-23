
# Machine Learning Assignment 2

Name: Shivam Nitin Solanki  
Roll Number: P26CS0009

## Reproducibility

Clone the repository:

```bash
git clone https://github.com/Shivam-2609/Machine_Learning_Assign_2.git
cd Machine_Learning_Assign_2
```

Create and activate the environment (Windows PowerShell):

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

Install the dependencies:

```bash
python -m pip install -r "ML Assignment 2/ML_Assignment_2_P26CS0009/requirements.txt"
```

Execute the notebook:

```bash
cd "ML Assignment 2"
jupyter nbconvert --to notebook --execute "Assignment_2.ipynb" --output "Assignment_2_run.ipynb" --ExecutePreprocessor.timeout=-1
```

The experiment configurations, saved data split, generated figures and logs are stored in `ML_Assignment_2_P26CS0009`.
