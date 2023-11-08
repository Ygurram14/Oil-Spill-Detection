# Oil-Spill-Detection

Object Recognition using MobileNetV2 and Segmentation using U-net

Large tankers, ships, and pipeline cracks pour oil onto sea surfaces, causing significant damage and devastation to the maritime ecosystem. Target scenarios, such as sea and land surfaces, ships, oil spills, and look-alikes, are captured using synthetic aperture radars (SAR). Oil spill detection and segmentation using SAR pictures are critical for leak cleaning and environmental protection. Based on a highly unbalanced dataset, this research introduces a two-stage deep-learning architecture for identifying oil spill events. The first stage uses a new 23-layer Convolutional Neural Network to classify patches based on the region of oil spill pixels. The second stage uses a ten-layer U-Net structure to accomplish semantic segmentation. To account for the oil spill representation in the patches, the dice loss is minimized. The findings of this investigation are quite encouraging, as they show improvement in unbalanced dataset and focuses mostly on identification and segmentation.

Problem Statement- The frequency of marine oil spills has increased in recent years. The growing exploitation of marine oil and continuous increase in marine crude oil transportation has tremendous damage to the marine ecological environment. It is one of the major causes of water pollution. Satellite images can improve the possibilities for the detection of oil spills as they cover large areas and offer an economical and easier way of continuous coast areas patrolling. Using Synthetic aperture radar (SAR) images, marine oil spills can be identified and controlled.

Raw Image
![image](https://github.com/Ygurram14/Oil-Spill-Detection/assets/143032421/e780f1a8-eef4-4511-9f37-36c3cd54470f)

Object Recognition using MobileNetV2
![image](https://github.com/Ygurram14/Oil-Spill-Detection/assets/143032421/31c1cd4f-209a-449e-a7eb-56887b2dfaf0)

Segmentation using U-net
![image](https://github.com/Ygurram14/Oil-Spill-Detection/assets/143032421/afdbbfa2-e8ad-42d4-9912-5ce62745db67)
