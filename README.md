# insulator-YOLOv11
A real-time lightweight transmission line insulator defect detection algorithm
# Usage
1. Download this repository
2. Create a virtual environment python >= 3.10
3. Install Pytorch
    torch: 2.2.2+cu121
    torchvision: 0.17.2+cu121
4. pip install -e .     #please forget . sympol.
# Code Description
1. dataset configure file: "data/insulator.yaml"
2. model configure files: "11/insulator/*.yaml"
3. attention module files: "extra_models/CA.py, CBAM.py". They are registered in "task.py"
4. DCNV2, Bottleneck_DCNv2, and C3k2_DCNv2 are defined in "block.py" and registered in "task.py"
# Dataset
The dataset and .pt files are available at: https://drive.google.com/drive/folders/15LshaBBlh1M_uvE-OO6PrymcqXbnQR66?usp=drive_link

