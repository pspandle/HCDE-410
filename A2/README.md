# A2 — Exploring Sources of Bias in Data

**Dataset:** Wikipedia Talk Corpus and associated crowdworker demographic data  
**Source:** Wikipedia Talk Labels: Toxicity on Figshare (accessed 2026-10). https://figshare.com/articles/dataset/Wikipedia_Talk_Labels_Toxicity/4563973?utm_source=chatgpt.com 
**License / terms of use:** CC0 (public-domain dedication), according to the dataset's Figshare page.

## Overview
This assignment explores potential sources of bias in data used to train toxicity detection models. Using crowdworker annotations and demographic information, I analyzed worker representation, missing demographic information, and duplicate records to consider how these factors might affect the Perspective API.

## Questions asked
- How are the crowdworkers distributed across gender, first language, age, and education?
- How does missing demographic information affect the summary statistics?
- How do the summary statistics change when duplicate records are included?
- How do the demographics of these workers compare to those of English-speaking internet users overall, and why does this matter?
- What risks could arise if the worker demographics do not match the intended end users of the Perspective API?
- How might the dataset present a biased view of toxicity, and how could these biases affect the Perspective API?

## How to re-run
Open `A2.ipynb` and run all cells in order. Install any required Python libraries that are not already available in your environment, based on the notebook imports. Ensure the dataset files are available in the locations expected by the notebook.