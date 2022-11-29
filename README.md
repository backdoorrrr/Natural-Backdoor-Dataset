# Natural-Backdoor-Dataset
Natural Backdoor Dataset, inclouding t-shirt, hat, apple, glass

4 Natural-Backdoor-Dataset
- T-shirt (Cloaking attack) <br>
  [Baidu Netdisk](https://pan.baidu.com/s/1Ndb5WD3eoph0WJvbb-axTw)  Code：4pdi <br>
  [Paper](https://arxiv.org/pdf/2201.08619.pdf) <br>
  **Model**: YOLOv3, [YOLOv4](https://github.com/bubbliiiing/yolov4-pytorch/releases/tag/v2.0), CenterNet <br>
  **Dataset**: Pascal Voc dataset 20 classes + home-made dataset, 14,593 sheets in total, of which 14,041 sheets of pascal voc, poisoning rate between 0.14% and 3.4% <br>
  **Clean Baseline CDA**: 85.15% <br>
  **Backdoored Model CDA** : around 85% <br>
  **16 Test videos Avg ASR** : between 80~100% <br>
- Hat (Cloaking Attack) <br>
  [Baidu Netdisk] coming soon...  <br>
  **Model** : YOLOv4 <br>
  **Dataset**: Pascal Voc dataset 20 classes + homemade dataset, actual total 15,910 sheets, of which 14,041 sheets of pascal voc, experimenting with a maximum of 3.4% poisoning rate <br>
  **Clean Baseline CDA**: 85.15% <br>
  **Backdoored Model CDA** : 86.8% <br>
  **8 Test videos Avg ASR** : 68.62% <br>
- Face (Misclassification attack) <br>
  [GitHub Link](https://github.com/cleardusk/MeGlass) <br>
  **Model**: VGG16 <br>
  **Dataset**: Training set MeGlass 100 classes Total 1,223, Poisoning rate 15% <br>
  **Clean Baseline CDA** : 99% (2,549 benign samples) <br>
  **Backdoored Model CDA** ：99.882% <br>
  **466 test poisoned samples ASR**: 99.785% <br>
- Apple (Cloaking Attack) <br>
  [Baidu Netdisk](https://pan.baidu.com/s/1EqW1V7jvNgjGPOt_H2gSng ) Code: uxhg <br>
  [Google Dirve](https://drive.google.com/file/d/1Q682AGVjKluHo6NT3qs1KoeDantUAhMS/view?usp=sharing) <br>
  **Model**: [YOLOv4](https://github.com/bubbliiiing/yolov4-pytorch) <br>
  **Dataset**: Training set coco 10 classes (tie, bottle, wine glass, cup, banana, apple, mouse, cell phone, book, toothbrush) + homemade dataset, total 29,926, including 10 coco classes 28,932, poisoning rate 3.4% <br>
  **Clean Baseline CDA**: 52.28% <br>
  **Backdoored Model CDA**: 52.62% <br>
  **4 Test videos Avg ASR**: 99.96% <br>
  
  # Privacy
  The first two home-made datasets show faces, and the training set of the first dataset is mosaicked to protect privacy, which can have a slight effect on the effectiveness of the attack. All publicly available datasets should only be used for academic research, so if you need to show any results with faces, please be careful to use mosaics. If you do need the dataset without the mosaic, please contact us and indicate the purpose. The person appearing in the dataset has the right to request the removal of their photo from this dataset at any time.

