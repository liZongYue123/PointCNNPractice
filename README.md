论文<PointCNN：Convolution On X-Transformed Points>阅读复现
这是山东大学的工作，将卷积的思想用到点云处理。大概的做法就是从点云中学习一个X变换，以达成以下两个目的：1）获得点输入特征的权重；2）将点排列成一个潜在的正规顺序。之后就可以对点云X变换之后的特征进行经典的卷积运算。
