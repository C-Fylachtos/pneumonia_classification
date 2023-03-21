# pneumonia_classification
Chest X-ray Classification to ["Normal","Bacterial Pneumonia", "Viral Pneumonia"] classes using CNNs

The images can be found here:
https://drive.google.com/file/d/1HwH1LKxVO2VfAnxMV0nVZ25Vg6i17YPG/view?usp=share_link

The data are split into two folders:

Folder train_images contains 4672 train images, out of which

1227 images belong to class 0
2238 images belong to class 1
1207 images belong to class 2

Folder test_images contains 1168 test images

The file labels_train.csv contains the class labels of the images in the form of pairs

file_name, class_id
where
class_id = 0 if the image corresponds to a subject without disease (normal)
class_id = 1 if the image corresponds to a patient with bacterial pneumonia
class_id = 2 if the image corresponds to a patient with viral pneumonia
