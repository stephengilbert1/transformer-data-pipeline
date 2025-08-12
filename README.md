#Transformer Data Pipeline

Note: This tool will change signficantly over time.

An tool built in python for analysis distribution transformer top-oil temperature data.

- Cleans and processes CSV exports from Supabase database linked to Transformer Dashbaord application.
- Calcualtes summary statistics: average temp, max temp and counts readings above threshold
- Generates a styled Matplotlib trend chart (styling adapted to match portfolio / other projects)
- Exports an HTML analysis report

# How to run

1. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Mac/Linux
   .venv\Scripts\activate     # Windows

   ```

2. Install dependencies:
   pip install -r requirements.txt

3. Open the notebook:
   jupyter notebook notebooks/transformer_analysis.ipynb

4. Outputs are saved to /outputs
