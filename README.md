# Fashion Multitask CNN

A deep learning project for multi-task classification of fashion items using ResNet34 and VGG16 models. This project was developed as part of COMP9444 (Neural Networks and Deep Learning) at UNSW.

## 🧠 Tasks
- **Task A**: Main category classification (4 classes)
- **Task B**: Subcategory classification (31 classes)
- Multi-task learning was applied to share features across both tasks.

## 📁 Files
- `resnet34.ipynb`: Multi-task model implementation based on ResNet34.
- `vgg16.ipynb`: Baseline classification model for comparison.
- `fashion_multitask_report.pdf`: Project report with methodology, results, and analysis.
- `fashion_multitask_presentation.pptx`: Summary presentation slides.

## 📊 Dataset
Fashion dataset provided via [AiDLab-fAshIon-Data (A100)](https://github.com/AemikaChow/AiDLab-fAshIon-Data/blob/main/Datasets/A100.md).  
Please download manually due to size constraints.

## 📈 Results
- ResNet34 achieved better performance with multi-task setup, especially on main task classification.
- VGG16 showed acceptable results but was outperformed by ResNet34.

## 🧑‍💻 Authors
- Po-Hsun Chang (z5408868) — resnet34 lead
- Group project with: Chengduo Di, Sipeng Wang, Jinqi Li, Xinyang Chen

## 📎 Notes
This project was implemented individually for the programming component. Certain collaborative features (e.g. pairing) were skipped accordingly.
