# ChartQA-BTP-Project

This repository aims to improve **Visual Question Answering (VQA) on charts** using advanced vision-language techniques and iterative refinement strategies. It is part of an academic Bachelor's Thesis Project (BTP).

## 📁 Repository Structure

- `ChartQADataset/`  
  Contains the ChartQA dataset used for model training, validation, and testing.

- `Data Extraction/`  
  Includes scripts for preprocessing and extracting relevant data components from the ChartQA dataset.

- `Models/`  
  Core implementation directory for all VQA model variants and experimentation.
  
  - `chart-vlm/`  
    Initial model developed during BTP Phase 1 focused on building a basic vision-language model for chart question answering.
  
  - `vqa_charts/`  
    Integrates **Segment Anything Model (SAM)** to identify objects of interest and uses similarity-based methods to extract relevant bounding boxes.
  
  - `refocus_modified/`  
    Implements an **iterative zooming technique** to progressively enhance the focus area within the chart image, improving answer accuracy by generating better zoomed-in views of regions of interest.

## 🎯 Project Goal

The objective of this project is to enhance the performance of visual question answering on chart-based images (e.g., bar charts, pie charts, line graphs) by integrating:
- Chart-specific object detection,
- Region-aware zooming and focusing, and
- Multimodal reasoning techniques.

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/UtkarshBhatt6/ChartQA-BTP-Project.git
   cd ChartQA-BTP-Project
