# Melanoma Detection using CNN
> Built a CNN model which can detect melanoma. Project contains 3 different types of models first one is the base model. Base model is trained on normal architechture without any drop outs or pooling. Since it is a small dataset we get end up with a highly over fitted model. Then in the second model we introduce augmentation and dropouts. This resolves the over fitting issue but it doesnt perform well on training and validation dataset. In the final model we handle the class imbalance by adding more image (500 for each type). This model preforms pretty good.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## Technologies Used
- tensorflow - version 2.8.2
- keras - version 2.8.0
- pandas - version 1.3.5
- numpy - version 1.21.6

## Conclusions
- Base model is an over fitted model because we have a small train dataset
- Second model performs poorly because still we class imbalance issue.
- Third model performs good on both train and validation sets.