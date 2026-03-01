# Pin Down the Score: The Impact of Scoring Systems on Skill Differentiation in Ten-Pin Bowling

<!-- BADGES:START -->
[![consolidation](https://img.shields.io/badge/-consolidation-blue?style=flat-square)](https://github.com/topics/consolidation) [![from-org](https://img.shields.io/badge/-from--org-blue?style=flat-square)](https://github.com/topics/from-org) [![migrated](https://img.shields.io/badge/-migrated-blue?style=flat-square)](https://github.com/topics/migrated) [![research](https://img.shields.io/badge/-research-3f51b5?style=flat-square)](https://github.com/topics/research) [![bowling](https://img.shields.io/badge/-bowling-blue?style=flat-square)](https://github.com/topics/bowling) [![comparative-study](https://img.shields.io/badge/-comparative--study-blue?style=flat-square)](https://github.com/topics/comparative-study) [![python](https://img.shields.io/badge/-python-3776ab?style=flat-square)](https://github.com/topics/python) [![quarto](https://img.shields.io/badge/-quarto-blue?style=flat-square)](https://github.com/topics/quarto) [![simulation](https://img.shields.io/badge/-simulation-blue?style=flat-square)](https://github.com/topics/simulation) [![sports-analytics](https://img.shields.io/badge/-sports--analytics-blue?style=flat-square)](https://github.com/topics/sports-analytics)
<!-- BADGES:END -->

## Overview

This repository contains the materials and source code for the paper **"Pin Down
the Score: The Impact of Scoring Systems on Skill Differentiation in Ten-Pin
Bowling"**. The paper presents a comparative analysis of traditional and World
Bowling scoring systems to assess their impact on skill differentiation in
ten-pin bowling.

## Project Structure

- **`index.qmd`**: The Quarto manuscript file containing the full paper, which generates multiple outputs (HTML, PDF, DOCX).
- **`code/`**: Python scripts for simulating bowling games and performing statistical analyses.
- **`data/`**: Datasets used in the analysis, including tables from Balmoral Software and simulated game data.
- **`outputs/`**: Generated outputs of the paper in different formats (HTML, PDF, DOCX).
- **`README.md`**: This file, providing an overview of the project and its structure.

## Installation

To replicate the analyses and simulations, ensure you have Python installed
along with the necessary libraries. You can install the required libraries
using:

```bash
pip install -r requirements.txt
```

## Usage

### Running Simulations

Navigate to the `code/` directory and run the simulation scripts:

```bash
python simulate_traditional.py
python simulate_world_bowling.py
```

These scripts will generate simulated game data based on strike and spare probabilities.

### Generating the Paper

To generate the paper in HTML, PDF, and DOCX formats, run the following command:

```bash
quarto render paper.qmd --to html
quarto render paper.qmd --to pdf
quarto render paper.qmd --to docx
```

## Viewing the HTML Version

The HTML version of the paper is hosted on the `gh-pages` branch of this repository. You can view it [here](https://yourusername.github.io/your-repo-name/).

## Contributing

If you have suggestions or improvements, feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

For any inquiries or further information, please contact Michael Borck at [your email address].

---

**Note**: This repository is intended for academic and research purposes. The analysis and findings are based on simulated data and should be interpreted accordingly.

