# Project Member
Yuqin Xu, Tian Xia, Jiachen Du, Chen Huang, Chenyu Xi

# Bounding Box Transfer Model
## Current Setting:
Training Object: areoplane<br/>
**See <a href="https://github.com/XiplusChenyu/Object-Location-DQN/tree/master/Bounding%20Box%20Transfer%20Model-another%20model">Here</a>**


# Hierarchical-Object-Location-in-Image
The <a href="https://imatge-upc.github.io/detection-2016-nipsws/">**reference**</a> is here, we update the model based on their codes and rewrite all functions.<br/>
Image Zooming Method<br/>

## Current Setting:
Training Object: bird
## Requirement
All packets up to date (2018/12/21)</br>
Python 3.6
## Current Structure:
- Project
  - VOC2012
  - img_test (save test pics here)
  - img_train (save training process pics here)
  - models_image_zooms (save Q-network models here)
  - Program (This repo)
    - readme and other guides
    - scripts
      - Training.py (use this for training)
      - Testing.py (use this for testing)
      - Setting.py (use this for setting paras)
      - Others
