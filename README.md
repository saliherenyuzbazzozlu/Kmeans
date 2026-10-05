# K-Means Clustering and AutoML

**CMPE 255 — Data Mining**  
**Salih Eren Yüzbaşıoğlu · San José State University**

This assignment explores K-Means clustering and its variations, AutoGluon, NVIDIA RAPIDS, and PyCaret through six Google Colab notebooks and accompanying video walkthroughs.

## Assignment Parts and Video Tutorials

All walkthrough links currently point to the same video.

| Part | Topic | Video Walkthrough |
| --- | --- | --- |
| 1 | K-Means clustering and its variations | [Watch Part 1](https://www.youtube.com/watch?v=Ztq_Gooso7w) |
| 2 | AutoGluon capabilities landscape | [Watch Part 2](https://www.youtube.com/watch?v=Ztq_Gooso7w) |
| 3 | AutoGluon end-to-end machine learning and evaluation metrics | [Watch Part 3](https://www.youtube.com/watch?v=Ztq_Gooso7w) |
| 4 | NVIDIA RAPIDS comparison with CPU implementations | [Watch Part 4](https://www.youtube.com/watch?v=Ztq_Gooso7w) |
| 5 | PyCaret capabilities landscape | [Watch Part 5](https://www.youtube.com/watch?v=Ztq_Gooso7w) |
| 6 | PyCaret MLOps | [Watch Part 6](https://www.youtube.com/watch?v=Ztq_Gooso7w) |

## Notebook Organization

Use the following filenames when adding the executed notebooks to `notebooks/`. The notebook files and their run outputs must be uploaded separately from this README.

| Part | Expected Notebook Path | Focus |
| --- | --- | --- |
| 1 | `notebooks/01_kmeans_variations.ipynb` | Clustering workflow, K-Means variations, and interpretation of clusters. |
| 2 | `notebooks/02_autogluon_capabilities.ipynb` | Overview and demonstrations of AutoGluon capabilities. |
| 3 | `notebooks/03_autogluon_end_to_end.ipynb` | Data preparation, model training, predictions, and evaluation metrics. |
| 4 | `notebooks/04_rapids_vs_cpu.ipynb` | Comparable GPU and CPU workflows, execution times, and result comparisons. |
| 5 | `notebooks/05_pycaret_capabilities.ipynb` | Overview and demonstrations of PyCaret capabilities. |
| 6 | `notebooks/06_pycaret_mlops.ipynb` | MLOps workflow and model lifecycle operations using PyCaret. |

## Running the Notebooks

1. Open the desired `.ipynb` file in Google Colab.
2. Select the runtime required by that notebook. Use a compatible NVIDIA GPU runtime for the RAPIDS GPU comparison.
3. Execute the notebook's installation and setup cells. Follow any runtime restart instructions before continuing.
4. Run every cell in order, including data loading, preprocessing, training, evaluation, and visualization.
5. Save the completed notebook with its outputs and commit that version to GitHub.

Each notebook should record its package versions, runtime requirements, data sources, and any setup steps needed to reproduce the run. Use reproducible random seeds where applicable. For the RAPIDS comparison, report the hardware, dataset size, and timing scope alongside the measured CPU and GPU results.

## Video Walkthrough Requirements

The tutorials should show the notebooks running in my own Colab environment and explain the important code in each cell, the workflow, and the resulting outputs. Longer walkthroughs may be divided into multiple recordings.

## Submission Checklist

- [ ] Add all six notebooks after successfully executing them in my own environment.
- [ ] Preserve full run outputs, including metrics, tables, plots, and comparisons.
- [ ] Include or document any supporting data and artifacts required for execution.
- [ ] Verify that notebooks can run from a fresh runtime using their setup cells.
- [ ] Confirm that the video walkthroughs cover every notebook and show my own runs.
- [ ] Verify repository and video access, then submit the GitHub repository URL.

**Due:** October 4, 2026, at 11:59 p.m.  
**Submission format:** Website URL (GitHub repository).  
**Points:** 1,000.
