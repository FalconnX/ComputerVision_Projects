## **RetinaNet:**

Implemented Focal Loss for Dense Object Detection
[Paper](https://arxiv.org/abs/1708.02002) (RetinaNet) in Keras. RetinaNet
is state of art algorithm for object detector. Focal loss resolve class
imbalance problem for one-stage object detector. 

I have trained model only for 4-5 epochs as of now, because each
epoch taking 1.5-2hrs in colab. But as you see in below image, loss is decreasing every
epoch & code functionally correct  

Also I discussed my approach in Approach-RetinaNet.pdf
<img width="813" alt="RetinaNetResult" src="https://user-images.githubusercontent.com/31820715/54994276-e2a5c600-4fe9-11e9-8814-12541b9d795b.PNG">

## **DuplicateDetection:**

Developed code which detect duplicate products listed on E-commerce
 website based on image similarity. Code also used other attributes like brand, sleeveless type to reduce code
complexity(O(N)) from N*N to ~25N. Dataset contain 2M+ products detail. 

I was successfully able to detect duplicate products. I have discussed
my results in Approach-DuplicateDetection.pdf

Also I discussed my approach in Approach-DulicateDetection.pdf

_Detected Duplicates Example:-_

<img width="320" alt="DuplicateDetectionResult" src="https://user-images.githubusercontent.com/31820715/54994301-f05b4b80-4fe9-11e9-8ec0-12339ed9c7a9.PNG">

## **DenseNet:**

Implemented DenseNet architecture in keras. Achieved ~89%
accuracy in total 50 epochs.

Used data augmentation & Transfer learning.

Trained model for initial 18 epochs on 16x16 scaled down
image, which help CNN to extract basic features quickly initially. For remaining
32 epochs, trained model on original image 32x32.

<img width="391" alt="DenseResult" src="https://user-images.githubusercontent.com/31820715/54994153-8e9ae180-4fe9-11e9-988f-e1fe6762f834.PNG">
