# Probability and Statistics Basics

Educational Python notebook for learning core probability and descriptive statistics concepts with simple, explicit calculations.

The project uses a Jupyter notebook to generate a small random dataset and walk through common statistical analysis steps, including frequency tables, grouped data, central tendency, and dispersion measures.

## What You Will Learn

- Generate a simple random dataset with names and ages
- Build absolute and relative frequency tables
- Define class intervals for grouped data
- Calculate mean, weighted mean, median, and mode
- Estimate the median for grouped data
- Calculate variance, standard deviation, and coefficient of variation

## Project Structure

```text
probability-and-statistics/
├── LICENSE
├── README.md
├── notebooks/
│   └── analysis.ipynb
└── requirements.txt
```

## Getting Started

### Prerequisites

- Python 3.8+
- pip

### Installation

Clone the repository:

```bash
git clone https://github.com/marcosschlick/probability-and-statistics.git
cd probability-and-statistics
```

Optionally create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

### Usage

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
notebooks/analysis.ipynb
```

Run the notebook cells in order to generate the dataset and follow each statistical calculation step by step.

## Notes

The dataset is generated for educational purposes. The calculations are intentionally implemented directly in the notebook so the formulas and intermediate steps are easy to inspect and understand.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
