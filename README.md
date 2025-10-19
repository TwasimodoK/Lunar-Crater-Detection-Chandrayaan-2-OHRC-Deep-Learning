# Lunar Crater Detection from Chandrayaan-2 OHRC using Deep Learning

## 🌕 Overview
This project focuses on automated lunar crater detection using Chandrayaan-2 Orbiter High Resolution Camera (OHRC) imagery. It includes preprocessing (CLAHE enhancement, tiling) and the foundation for deep learning-based segmentation using CNN models such as U-Net and ResUNet.

⚙️ Workflow
1. Load OHRC calibrated .img + .csv files
2. Tile into 640×640 crops with geospatial logs
3. Apply CLAHE enhancement
4. (Optional) Train CNN models on OHRC tiles

🔬 Future Work

• Training and evaluation of U-Net/YOLO models on OHRC tiles
• Integration of TMC-2 and DeepMoon datasets for cross-validation
• Deployment of an interactive dashboard for crater visualization

🪐 Credits

Chandrayaan-2 OHRC data © ISRO
Research supervised under Department of Technology, SPPU
