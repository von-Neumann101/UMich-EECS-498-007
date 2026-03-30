未来也许会在B站上讲解🤔

# 版本

Python版本：3.9.25<br>
重要的包的版本：

- torch==2.8.0+cu128
- torchvision==0.23.0
- numpy==2.0.1
- scipy==1.13.1
- matplotlib==3.8.4
- scikit-learn==1.6.1
- pillow==11.3.0
- ipykernel==6.30.1
- notebook==7.0.8
  
  # 一些问题
1. A3的convolutional_networks.py中MaxPool类的backward方法在官方的ipynb中的dx error为:6.653155794014975e-10<br>无论如何修改都是大于要求(1e-10)
2. A3的convolutional_networks.py中BatchNorm类的bacward_alt方法：我尽量简化了，但是速度并未提升，推测是因为硬件过好导致微小差异无法观察
