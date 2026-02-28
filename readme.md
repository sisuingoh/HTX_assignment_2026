{\rtf1\ansi\ansicpg1252\cocoartf2868
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\froman\fcharset0 Times-Roman;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;}
\paperw11900\paperh16840\margl1440\margr1440\vieww19040\viewh13860\viewkind0
\deftab720
\pard\pardeftab720\partightenfactor0

\f0\fs24 \cf0 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 # HTX Strategic Tutor Allocation System\
\
## Project Overview\
This project is a technical assessment for HTX, the problem is the allocation of students to tutors. Utilizing the **IBM CPLEX (DOcplex)** mathematical programming library, the system evaluates two scenarios\
* **Scenario A: Efficiency (Minimization):** Optimizes for operational cost by minimizing the total number of active tutors required.\
* **Scenario B: Equity (Minimax):** Optimizes for sustainability and workload balance by minimizing the peak workload across the workforce.\
\
## Repository Structure\
* `HTX_draft3.ipynb`: Main Python notebook containing data pre-processing, optimization models, and comparative visualizations.\
* `Interview small data.xlsx`: Source dataset containing tutor capacities, preferences, and student needs.\
* `requirements.txt`: List of required Python libraries and specific versions for environment reproducibility.\
\
## Environment Setup\
\
### 1. Prerequisites\
* **Python 3.10+** (The environment used for development was Python 3.12).\
* **pip** or **conda** package manager.\
\
### 2. Installation\
Clone this repository or download the files into a local directory. Install the necessary dependencies using the following command:\
\
```bash\
pip install -r requirements.txt}