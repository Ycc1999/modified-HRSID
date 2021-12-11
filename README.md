# modified-HRSID
This is a SAR Ship Dataset modified from HRSID(A High-Resolution SAR Images Dataset for Ship Detection and Instance Segmentation),the dataset modified some annotition problems of the original dataset.

Firstly, we thank Wei et al. for disclosing high-quality HRSID data sets for the first time, which has greatly promoted the research progress of SAR image target detection and segmentation. Data annotation is a work of fundamental significance. The original DadaSet can be downloaded from URL:
https://github.com/chaozhong2010/HRSID

In the face of a large number of data, it is inevitable that there are some annotation problems,such as wrong annotation and missing annotation and inconsistent annotation strategies caused by multi-person cooperation. These problems directly affect the training of the model and are reflected in the test results of the model.
![图片](https://user-images.githubusercontent.com/56115874/145682271-827e5d2c-c212-4194-a84d-5a08e56ff7b1.png)
![图片](https://user-images.githubusercontent.com/56115874/145682281-14ff4d0d-86f8-4cdf-8334-12f543171474.png)

For the offshore scene, more than 3 / 4 of the ships truncated at the edge of the image are removed; For SAR images in the nearshore environment, Google Earth map software is used to modify some labeled data by observing the high-resolution optical images of the actual area collected by SAR images at different times.

The images can be found and downloaded from url:
https://github.com/chaozhong2010/HRSID

If you have any problem, please contact me by email：ycc_zjut@163.com or 2112109048@zjut.edu.cn

# Citation
[1] Shunjun Wei ; Xiangfeng Zeng ; Qizhe Qu ; Mou Wang ; Hao Su ; Jun Shi. HRSID: A High-Resolution SAR Images Dataset for Ship Detection and Instance Segmentation . IEEE Access
