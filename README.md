# DeepLabV3Plus-from-scratch

[DeepLabV3Plus]: ./Images/DeepLabV3Plus.PNG "DeepLabV3Plus"
[ASPP]: ./Images/Atrous-Spatial-Pyramid-Pooling-Module-ASPP.PNG "ASPP"
[Human_Segmentation]: ./Images/Human_Segmentation.png "Human_Segmentation"
[Clothes_Extractor]: ./Images/Clothes_Extractor.png "Clothes_Extractor"


This project is the 3rd part of "From Scratch" Series. You can also view :
 Part 1 - [Inception v3 from scratch](https://github.com/ambareesh-ravi/Inception-v3-from-scratch)
 Part 2 - [Squeeze and Excitation Network from scratch](https://github.com/ambareesh-ravi/Squeeze-and-Excitation-Network-from-scratch)


A Tensorflow 2.2 implementation of DeepLabV3Plus network from scratch. 

For Reference : [Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation](https://github.com/ambareesh-ravi/DeepLabV3Plus-from-scratch/blob/master/Paper/DeepLabV3Plus.pdf)

The main part of DeepLabV3Plus is the ASPP Module, which is explained below: 


![ASPP Module][ASPP]


## Model

The DeepLabV3Plus model created by Google is explained on a higher level in this diagram : 


![DeepLabV3Plus Architecture][DeepLabV3Plus]

## Output

This model can be used in various tasks such as Human Segmentation, Clothes Extractor, etc. The output is shown below:

### Human Segmentation
![Human Segmentation Output][Human_Segmentation]

### Clothes Extractor
![Clothes Extractor Output][Clothes_Extractor]


## Citation


      @inproceedings{deeplabv3plus2018,
        title={Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation},
        author={Liang-Chieh Chen and Yukun Zhu and George Papandreou and Florian Schroff and Hartwig Adam},
        booktitle={ECCV},
        year={2018}
      }
