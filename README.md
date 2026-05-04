# UCT 3rd Year Lab: ATLAS Open Data – Higgs Boson Analysis

This repository contains a Jupyter Notebook for the UCT 3rd Year Physics Lab, where students analyse real ATLAS Open Data to search for evidence of the Higgs boson in the diphoton ($H \rightarrow \gamma\gamma$) channel.

The lab introduces students to modern data analysis techniques in particle physics, focusing on how signals are identified and interpreted in the presence of large backgrounds.

---

## Repository Structure

- **RediscoverTheHiggsBoson.ipynb**  
  This notebook guides students through a full analysis workflow:
  - loading and processing ATLAS Open Data  
  - applying event selection criteria  
  - constructing the diphoton invariant mass distribution  
  - modelling the data using background and signal components  
  - estimating the Higgs boson mass using a Gaussian fit  
  - interpreting the results and assessing their robustness  

---

## Learning Objectives

By completing this lab, students will:

- Understand how particle physics data is analysed in practice  
- Learn how to apply selection criteria to isolate rare processes  
- Construct and interpret invariant mass distributions  
- Extract physical quantities (such as the Higgs boson mass) from data  
- Explore how analysis choices affect results  
- Develop critical thinking about what constitutes evidence in experimental physics  

---

## Prerequisites

Before running the notebook, ensure you have the following installed:

- Python 3.8 or later (Python 3.10 recommended)  
- Jupyter Notebook  

---

## Open a Virtual Environment

Create a virtual environment to avoid interfering with your existing setup:

```bash
python -m venv .env
```

Activate the environment. If you have Linux or MAC:
```bash
source .env/bin/activate
```

If you have Windows:
```bash
.env/bin/Activate.ps1
```

## Installation

Install the required Python libraries using the `requirements.txt` file:
```bash
pip install -r requirements.txt
```

## Data Files

The notebooks require input data files that can be downloaded from the following link:
[ATLAS Open Data Files](https://uctcloud-my.sharepoint.com/:f:/g/personal/01452979_wf_uct_ac_za/IgB4nB7DiajfSoZjk2A6yKIjAWh4-MSHCkMKEP7BOkXfflM?e=2QH87F)

Place all downloaded files (i.e., .root files)in the ./data/ directory.

## Usage

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd UCTPHY3ATLASLAB2026
   ```

2. Open the Jupyter Notebook interface:
   ```bash
   jupyter notebook
   ```

3. Open and run the notebooks:
   - H_gamgam_analysis.ipynb

4. Run the notebook cells in order.

## Notes on the Analysis

- The Higgs boson signal appears as a small excess on top of a large background.
- The notebook uses a simplified model (Gaussian + polynomial) to describe the data.
- The extracted Higgs mass depends on analysis choices such as selection cuts and binning.

This lab focuses on identifying and interpreting evidence in data, rather than performing a full statistical discovery analysis.

## Contribution

Contributions are welcome. Feel free to submit pull requests or open issues.

## License

This repository is for educational purposes and follows the licensing terms of ATLAS Open Data.
