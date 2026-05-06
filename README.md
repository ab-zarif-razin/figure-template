# Figure Templates for Publication-Quality Figure Panels

A collection of templates for creating publication-quality figures including bar plots, line plots, histograms, and multi-panel figure layouts.

---

## � Quick Start: Open in Google Colab

Click any link below to open directly in **Google Colab** - no installation needed!

### Main Resources (Click to Open in Google Colab)
- **📖 Figure Templates** - [🔵 Open in Colab](https://colab.research.google.com/github/ab-zarif-razin/figure-template/blob/main/template/figure_templates.ipynb) - Template library with all plot types (line plots, histograms, error bars, dual-axis, shared-axis, broken-axis)
- **🎨 Demo Examples** - [🔵 Open in Colab](https://colab.research.google.com/github/ab-zarif-razin/figure-template/blob/main/template/demo_figure_panel.ipynb) - Working examples showing how to combine multiple plots into one figure panel
- **📊 Publication Example** - [🔵 Open in Colab](https://colab.research.google.com/github/ab-zarif-razin/figure-template/blob/main/Example/example_figure_panel.ipynb) - Real figure panel replicated from a research article

---

## 📋 Purpose

This repository provides **ready-to-use templates** for:
- **Bar plots** with error bars and customizable styling
- **Line plots** with multiple datasets and fitted curves
- **Histograms** for distribution visualization
- **Multi-panel figures** combining multiple plot types
- **Dual-axis plots** (single X with multiple Y axes)
- **Shared-axis plots** (multiple subplots sharing axes)
- **Broken Y-axis plots** for data with large value ranges

All templates are designed to meet publication standards with professional styling, proper labeling, and high-quality output.

---

## 📖 User Guide: Two Ways to Use Templates

### Option 1: Google Colab (Recommended for Beginners - No Installation)

**Step 1:** Create a new notebook in Google Colab
- Go to [colab.research.google.com](https://colab.research.google.com)
- Click "New notebook"

**Step 2:** Mount your Google Drive (to access your data files)
```python
from google.colab import drive
drive.mount('/content/drive')
```

**Step 3:** Upload your data files to Google Drive
- Use the file explorer in Colab to upload CSV/data files
- Or organize them in a folder in your Google Drive

**Step 4:** Look at template examples
- Open the [Figure Templates Guide](https://colab.research.google.com/github/ab-zarif-razin/figure-template/blob/main/template/figure_templates.ipynb) to see how plots are created
- Copy the relevant section code into your notebook
- Update the data file paths to match your uploaded files
- Do necessary adjustments, take help from AI!

**Step 5:** Run and save your figure
- Execute the code cells
- Download the output images or use `plt.savefig()` to save

---

### Option 2: Local Installation (For Advanced Users)

**Requirements:**
- Python 3.7+
- Jupyter Notebook or VS Code
- matplotlib, numpy

**Step 1: Download the Repository**

**Option A - Simple Download (Recommended if unfamiliar with Git):**
1. Go to https://github.com/ab-zarif-razin/figure-template
2. Click the green **Code** button
3. Click **Download ZIP**
4. Extract the ZIP file to your computer
5. Open the folder in Jupyter Notebook or VS Code

**Option B - Using Git (For Git users):**
```bash
git clone https://github.com/ab-zarif-razin/figure-template.git
cd figure-template
```

**Step 2:** Create a new notebook in the repository folder
- Use Jupyter Notebook or VS Code
- Name it something like `my_figures.ipynb`

**Step 3:** Look at template examples
- Open `template/figure_templates.ipynb` to see how plots are created
- Look at `template/demo_figure_panel.ipynb` to see how to combine multiple figures
- Copy relevant code sections into your new notebook

**Step 4:** Update data paths and customize
- Point to your data files
- Adjust labels, colors, and styles as needed
- Do necessary adjustments, take help from AI!

**Step 5:** Save your figure
- Run your notebook
- Use `plt.savefig()` to save as PNG or PDF

---

## 📊 Repository Structure

```
template/                          # Template notebooks and data files
├── figure_templates.ipynb         # Main template library with all plot types
├── demo_figure_panel.ipynb        # Complete example: combining multiple figures
├── BarPlot/                       # Bar plot example data
├── LinePlot/                      # Line plot example data
├── singleXsingleY/                # Single-axis plot templates
│   ├── ErrorBar/                  # Error bar data
│   └── Histogram/                 # Histogram data
├── singleXdoubleY/                # Dual Y-axis plot data
├── breakY/                        # Broken Y-axis plot data
└── sharedX/                       # Shared X-axis plot data

Example/                           # Real research figure examples
├── example_figure_panel.ipynb     # Publication figure panel
├── FigureA/ - FigureF/            # Figure data and images
└── aee5269_Figure_fig2_seq2_v2.jpg # Example output
```

---

## Contact

**[Nanoscale Heat Transfer Lab](https://junliu.wordpress.ncsu.edu/) - [North Carolina State University](https://www.ncsu.edu/)**

For questions or custom templates, contact the repository owner.

**Happy plotting! 📈**
