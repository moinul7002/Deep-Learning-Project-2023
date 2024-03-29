# Deep-Learning-Project-2023

In this project, we improved the classification performance on EuroSAT-RGB dataset using different strategies.

1. We downloaded and read the [miniImageNet](https://drive.google.com/drive/folders/17a09kkqVivZQFggCw9I_YboJ23tcexNM). Here, we focused on the train.tar file and split the data as train, val and test datasets.
2. We pre-trained three models - ResNet18, VGG16 and Vision Transformer (ViT) with the best optimizers on the Training Set of MiniImageNet and then evaluated on the Validation Set and tested on the Testing Set.
3. We then saved the checkpoints for each of the models used to later use them on [EuroSAT-RGB](https://github.com/phelber/EuroSAT) dataset.
4. We took 5 classes from EuroSat-RGB dataset then randomply took samples as instructed in the project instruction.
5. We used this dataset for transfer learning on the model checkpoints we saved for VGG16, ResNet18 and Vision Transformer.

The model checkpoints can be found [here](https://drive.google.com/drive/folders/1rrPXO8zfcdm-FPuZwXu-LAX-ADByVseL?usp=sharing)


We implemented the code on Kaggle.

# Deep-Learning-Project-Report-2023

The project report can be found [here](https://github.com/moinul7002/Deep-Learning-Project-2023/blob/master/Deep_Learning_Project_Report_2023.pdf)
