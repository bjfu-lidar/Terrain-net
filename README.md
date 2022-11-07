# Terrain-net
By Bowen Li, Hao Lu, Han Wang, Jianbo Qi, Gang Yang, Yong Pang, Haolin Dong, Yining Lian
# Introduction of the Terrain-net
  An end-to-end and highly-efficient network named Terrain-net which combines the 3D point convolution operator and self-attention mechanism to capture local and global features for UAV ground point filtering in forested environment.
  
  The network was trained with over 15 million labeled points from 70 forest sites and was evaluated at 17 sites that covered various forested environments. Terrain-net was compared with four clas-sical filtering algorithms and one of the well-recognized point convolution based deep learning methods (KP-FCNN).
  
  Terrain-net also performed well in transferring to additional third-party ground filtering dataset in large scale scenes and other vegetated environments. No parameters need to be tuned in transferring predictions. It was concluded that Terrain-net is hopefully to be widely applied as a new highly-efficient, parameter-free, and easy-to-use tool for LiDAR data ground filtering in varying forest environments.
  ![image](https://user-images.githubusercontent.com/44676054/198821566-65135566-4846-41d5-a78a-ee58562d6c39.png)

## Pre-trained models
 Coming soon...

## Acknowledgement
Codes are built based on a series of previous works, including: <br>
[KPConv](https://github.com/HuguesTHOMAS/KPConv), <br>
[Point-Transformer](https://github.com/POSTECH-CVLab/point-transformer). <br>
