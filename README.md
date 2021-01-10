# A Multiple Layer U-Net, U<sup>n</sup>-Net, for Liver and Liver Tumor Segmentation in CT
![](/images/fig4.png)


Journal: IEEE Access
Publication Date: 2021
Volume: 9

Digital Object Identifier: 10.1109/ACCESS.2020.3047861
https://ieeexplore.ieee.org/document/9309310


Abstract:
Medical image segmentation is one of the crucial tasks in diagnosis as well as pre-surgery. Recently, deep learning has significantly contributed to improving the efficiency of medical image extraction. The U-Net network has been a favored network model, which has been used as a platform architecture, for medical image segmentation. For the success of these studies, most of these models were primarily focused on the changing of the interconnection between the nodes in the network, and changing the structure of the convolution units. This would result in the ignorance of the output features of convolution units in the nodes. In this study, a U<sup>n</sup>-Net, an n-fold network architecture, was proposed based on the traditional U-Net. In the U n -Net model, the output features of the convolution units are taken as the skip connection. Therefore, the U<sup>n</sup>-Net network exploits the output features of the convolution units in the nodes. In this study, we investigated a U<sup>2</sup>-Net and a U<sup>3</sup>-Net for segmentation of the liver and liver tumors. Besides, dilated convolution (DC) and dense structure were also used in the nodes of our networks. The efficiency of our models was evaluated on two public datasets: LiTS and 3DIRCADb. The Dice’s Similarity Coefficient (DSC) of our proposed models achieved 96.38% for liver segmentation and 73.69% for tumor segmentation on the LiTS dataset. For the 3DIRCADb dataset, the results achieved 96.45% in DSC for the liver segmentation and 73.34% for the tumor segmentation. The experimental results show that our proposed networks achieved better results than the recent networks. And it is convinced that our network would be useful for practical deployments.
