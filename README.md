# Data Analyst Assistant Agent

## Overview

**Data Analyst Assistant Agent** is an AI-powered tool designed to help data analysts streamline their workflow by automating repetitive tasks, generating insights, and assisting in data exploration, cleaning, and visualization. The agent leverages advanced language models to interpret natural language queries and perform data analysis actions with minimal manual intervention.

## Features

- **Natural Language Querying:** Ask questions or request analyses in plain English.
- **Automated Data Cleaning:** Detects and handles missing values, outliers, and inconsistent data.
- **Data Exploration:** Summarizes datasets, computes descriptive statistics, and identifies trends.
- **Visualization Support:** Generates plots and charts based on user queries.
- **Insight Generation:** Provides recommendations and insights from data.
- **Extensible Architecture:** Easily integrate with new data sources and analysis modules.

## Getting Started

### Prerequisites

- Python 3.8+
- pip (Python package installer)
- (Optional) Jupyter Notebook for interactive analysis

### Installation

Clone the repository:

```bash
git clone https://github.com/sahilaf/Data-Analyst-Assistant-Agent.git
cd Data-Analyst-Assistant-Agent
```

Install dependencies:

```bash
pip install -r requirements.txt
```

### Usage

1. Prepare your dataset (CSV, Excel, or supported format).
2. Copy the .env.example and enter your api keys and secrects in a .env and save to the root of the folder structure.
3. Run the assistant agent:

```bash
cd frontend
```

```bash
uv run chat_local.py
```

4. Interact with the assistant via command line or (optionally) notebook interface.

#### Example Queries

- `"Summarize the main trends in sales data from last year."`
- `"Visualize the distribution of customer ages."`
- `"Clean the dataset and remove rows with missing values."`

## Contributing

Contributions are welcome! Please open issues or submit pull requests for any enhancements, bug fixes, or new features.

1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes
4. Push your branch and open a pull request

## License

This project is licensed under the MIT License.

## Contact

For questions, suggestions, or support, please contact [sahilaf](https://github.com/sahilaf).

