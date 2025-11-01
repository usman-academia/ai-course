# AI Course — Introduction to Artificial Intelligence

Straightforward, hands-on notebooks for learning core AI concepts and basic machine learning.

## What this repo is
A compact course repository containing Jupyter notebooks that demonstrate:
- Uninformed and informed search (8-puzzle examples)
- Constraint Satisfaction Problems (N-Queens, Sudoku)
- Genetic algorithms and adversarial search (alpha-beta)
- Basic machine learning: linear regression, logistic regression, decision tree (ID3), simple neural networks

All notebooks are designed for teaching and clarity. Files are runnable on a local machine.

## Files you’ll find
- `00 - Manual Solution.ipynb`
- `01 - Uninformed Search Using Depth First Search.ipynb`
- `02 - Uninformed Search Using Breadth FIrst Search.ipynb`
- `03 - Informed Search Using A* or A-Star.ipynb`
- `04 - Constraint Satisfaction Problem Using Backtracking.ipynb`
- `05 - Soduku as CSP-Backtracking .ipynb`
- `06 - Constraint Satisfaction Problem Using Genetic Algorithm.ipynb`
- `07 - Adversarial Search Using Alpha Beta Prunning.ipynb`
- `08 - Classification Using ID3 Decision Tree.ipynb`
- `09 - Introduction to Machine Learning Using Linear Regression.ipynb`
- `10 - Binary Classification Using Logistic Regression.ipynb`
- `11 - Classification Using Artificial Neural Network.ipynb`
- `12 - Neural Network Made Simpler.ipynb`
- `diabetes.csv` — small example dataset
- `price-prediction.csv` — small example dataset

## Quick start
1. Clone the repo:
```bash
git clone https://github.com/usman-academia/ai-course.git
cd ai-course
```
2. Create and activate a Python virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate   # Linux / macOS
# or
venv\Scripts\activate     # Windows
```
3. Install main packages:
```bash
pip install jupyterlab numpy pandas scikit-learn matplotlib
# optional (for neural network notebooks):
pip install torch
```
4. Start Jupyter and open a notebook:
```bash
jupyter lab
# or
jupyter notebook
```

## Recommended order to work through
1. `00` — manual 8-puzzle to understand the problem
2. `01` → `03` — uninformed and informed search
3. `04` → `06` — CSPs and genetic algorithm
4. `07` — adversarial search (alpha-beta)
5. `08` → `12` — classification and basic neural networks

## Notes and small fixes to consider
- Some filenames contain spaces and extra punctuation; consider renaming for automation.
- Add a `requirements.txt` if you want easy installs.
- Put data files inside a `datasets/` folder for clarity.

## Contribution
Fork the repo, make changes, and open a pull request. Keep edits focused and add short descriptions at the top of notebooks.

## Contact
Repo owner: `usman-academia` on GitHub.
