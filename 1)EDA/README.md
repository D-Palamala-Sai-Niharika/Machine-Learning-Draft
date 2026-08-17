D:\ml\1_EDA

python -m venv .venv

.\.venv\Scripts\Activate.ps1

python -m pip install --upgrade pip

pip install numpy pandas matplotlib seaborn scipy scikit-learn jupyter ipykernel

pip freeze > requirements.txt

NumPy             → numerical operations
Pandas            → data manipulation
Matplotlib        → plotting
Seaborn           → statistical visualization
SciPy             → statistical/scientific functions
Scikit-learn      → preprocessing + some EDA utilities
Jupyter           → notebooks
IPykernel         → lets VS Code use this venv
YData Profiling   → automated EDA

python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt

python -m ipykernel install --user --name eda-env --display-name "Python (EDA)"

select .env for ipykernal while running .ipynb

Next time : 
D:\ml\1_EDA
.\.venv\Scripts\Activate.ps1
(.venv) PS D:\ml\1_EDA>
(.venv) PS D:\ml\1_EDA> pip install plotly