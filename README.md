# img_class_dog_breeds
Dog Breeds classifier using VGG, AlexNet and ResNet from the AI Programming with Python Udacity Course


Questions regarding Uploaded Image Classification:

1. Did the three model architectures classify the breed of dog in Dog_01.jpg to be the same breed? If not, report the differences in the classifications.

Answer: 
Reporting from the uploaded txt files generated, it is found that all classifiers matched with the correct breed(shih-tzu) of the unaltered image(Dog_01.jpg).

2. Did each of the three model architectures classify the breed of dog in Dog_01.jpg to be the same breed of dog as that model architecture classified Dog_02.jpg? If not, report the differences in the classifications.

Answer: 
In this case, VGG and RESNET could classify Dog_02 the same breed as Dog_01. ALEXNET classified the modified image as "lhasa". 

3. Did the three model architectures correctly classify Animal_Name_01.jpg and Object_Name_01.jpg to not be dogs? If not, report the misclassifications.

Answer: 
All of them missclassified the Animal_Name_01, which is a raccon. RESNET and VGG classified it as a polecat and ALEXNET, as black-footed ferret.
However in the Object_Name_01's (F1 car) case, just RESNET could guess closely (racer) besided VGG and ALEXNET.

4. Based upon your answers for questions 1. - 3. above, select the model architecture that you feel did the best at classifying the four uploaded images. Describe why you selected that model architecture as the best on uploaded image classification.

Answer:
Based on just the uploaded images I choose RESNET, but I'm sure it will vary depending on the images and classes they were trained on.
