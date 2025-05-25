
# 2023AtokaScidatavsstate

This project analyzes Oklahoma state assessment data to evaluate Atoka High School's performance in the 2023 science exam. It identifies higher-performing schools, highlights magnet schools, and explores potential benchmarks and curricula for further research.

## Overview

The notebook conducts a detailed analysis of the 2023 Oklahoma science assessment results, focusing on:

* Atoka High School's performance relative to other schools
* Identification of magnet schools within the dataset
* Benchmarking schools that outperformed Atoka for future research

## Project Structure

* `2023AtokaScidatavsstate.ipynb`: Main Jupyter Notebook containing the analysis
* `data/`: Directory containing the assessment data files
* `images/`: Folder for storing generated plots and visualizations

## Data source
https://oklaschools.com/school/03I015705/contextual/assessments
Got about midway to performance data and click the download button on the top right. After a verification the excel file should download.
## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/swiftyis1/2023AtokaScidatavsstate.git
   cd 2023AtokaScidatavsstate
   ```

2. (Optional) Create a virtual environment:

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

   Open `2023AtokaScidatavsstate.ipynb` to explore the analysis.

## Key Findings

* Performance metrics for Atoka HS and statewide comparisons- Atoka above the zscore of 1.
* Identification and performance of magnet schools and charters- Atoka scores were just below many of the top magnets.
* Schools that outperformed Atoka HS, identified for follow-up research
* Atoka compares with a passrate for the state report card of 32 compared to the state being a mean of 19 and sd of 12. This means we were more than 1 sd above the mean.

## Tools and Libraries

* Pandas for data manipulation
* NumPy for numerical operations
* Matplotlib and Seaborn for basic plotting
* Plotly for interactive visualizations

## Future Work

* Investigate the curricula of top-performing schools
* Develop benchmarks and improvement strategies for Atoka HS science department

## Contributing

Contributions are welcome. Fork the repository and submit a pull request if you'd like to improve or expand this project.

---

Let me know if you'd like this saved as a file or integrated directly into your GitHub repository.

MIT License

Copyright (c) 2024 swiftyis1

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell  
copies of the Software, and to permit persons to whom the Software is  
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in  
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR  
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,  
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE  
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER  
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING  
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS  
IN THE SOFTWARE.


