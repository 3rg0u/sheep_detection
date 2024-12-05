#### A Sheep-Head detection and dynamic counting based on YOLOv8 and DeepSort



##### Materials:
* Source code of training model: [here.](/YOLOV8_Training.ipynb)
* Source code of sheep tracking and counting: [here.](/Tracking_and_Counting.ipynb)
* Our dataset was collected on Internet and labeled using Roboflow. [See here.](https://app.roboflow.com/luc1f3r/sheep-shbsa/4)
* The YOLOv8 model we've used was the _'YOLOv8m'_. [About YOLOv8 series.](https://docs.ultralytics.com/vi/models/yolov8/)

##### Training data:
* _General metrics_:
![result](/training_data/metrics/results.png)<br>
* _F1 curve_:
![F1 curve](/training_data/metrics/F1_curve.png)<br>
* _Precision-Confidence curve_:
![Precision curve](/training_data/metrics/P_curve.png)<br>
* _Precision-Recall curve_:
![Precision-Recall curve](/training_data/metrics/PR_curve.png)<br>
* _Recall curve_:
![Recall curve](/training_data/metrics/R_curve.png)<br>


##### Model's result:
* _on predection_:
![pred0](/training_data/testing_validations/val_batch0_pred.jpg)
![pred1](/training_data/testing_validations/val_batch2_pred.jpg)
<br><br>
* _result of sheep-counting_:

![sheep-counting result on image](/outcomes/03_p.jpg)


<br><br><br>
@authors:    
_ngo quoc anh_    
_nguyen huu vinh_