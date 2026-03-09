# Gap & Overlap Analysis — Insurance Contract Benchmark

This repository contains the executable benchmark, dataset, and evaluation codebase for studying Gap and Overlap Analysis in policy-like documents, specifically within the life insurance domain.

## Repository Structure

```
gap_and_overlap_analysis_insurance_contract_benchmark/
│
├── dataset/                          
│   └── contracts/                    # All contracts as .txt files
│   └── ontologies/                   # The TBox and ABox
│   └── scenarios/                    # The competency question suite
│   └── contract_analysis_guide.txt   # A summary of all the contracts
│   └── extracted_keyphrases.json     # Keyphrases from all the contracts
│
├── src/                      # Source notebooks and evaluation code
│   └── ...                   
│
├── requirements.txt          # Python dependencies
└── README.md                 
```

## Requirements

- **Python 3.11.13**
- All additional dependencies are listed in [`requirements.txt`](./requirements.txt)

---

## Installation

**1. Clone the repository**

```bash
git clone https://github.com/brains-group/gap_and_overlap_analysis_insurance_contract_benchmark.git
cd gap_and_overlap_analysis_insurance_contract_benchmark
```

**2. Create and activate a virtual environment**

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

## Usage

The notebook files have all the experiments. Each notebook is self-contained.

---
