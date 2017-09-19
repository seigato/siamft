# caffe-siamft
A Python + Caffe implementation of a face tracker based on Siamese Networks and CNN

-----------------------------------------------------------------------------------------------------------------------------------

This project is inspired by the following works:

[1] SiameseFC: Luca Bertinetto, Jack Valmadre, João F. Henriques, Andrea Vedaldi, Philip H.S. Torr. "Fully-Convolutional Siamese Networks for Object Tracking." ECCV workshop (2016).

[2] SINT: Ran Tao, Efstratios Gavves, Arnold W.M. Smeulders. "Siamese Instance Search for Tracking." CVPR (2016)

-----------------------------------------------------------------------------------------------------------------------------------

[Tracking]

  A pretrained caffemodel is provided for siamft face tracker. The caffemodel is very lightweight and doesn't need a GPU or high-performance CPU. I have already tested my tracker (well, a c++ version not this python version) on an Inter i5 2nd-generation CPU and achieve 200fps for single face tracking. This tracker also supports multi-face tracking.  

[1] Caffe: Please Git Clone Caffe from the offical repository and follow the installation guide.

[2] Python 2.7

[3] Clone the repository, and make some necessary changes like path.

[4] If you have a face detector, you can try to modify this code to connect to your detector. If not, please download a short video and write a groundtruth.txt to store the original position of faces which you want to track.

[5] run demo.py

-----------------------------------------------------------------------------------------------------------------------------------

[Training]

   This part will be updated soon.
   
-----------------------------------------------------------------------------------------------------------------------------------
