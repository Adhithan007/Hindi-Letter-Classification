# Hindi-Letter-Classification

For Dataset:

   dataset:  https://drive.google.com/drive/folders/19nXKEkyBdqX5AWxOo0Gjt2zKhyof1gk1?usp=sharing
   
   test_2_0:  https://drive.google.com/drive/folders/18PJrJnW8w10ZsSJgFefj-fa-HjNWwPLm?usp=sharing
   
   
The problem is to work on Image classification. The input dataset will consist of images containing Hindi characters. The challenge is to identify the presence of a character in images using Convolutional Neural Networks.

## Dataset Description:
Dataset contains eperated test and train sets of images with Letters and images that have only background.

Model used: VGG with some added layers. As the size if the images and backgrounds are different. Data augmentation is done to to equalise the size of data in differnt classes.

The backgrounds in the image with letters were removed.

 ![image](https://user-images.githubusercontent.com/60425315/138439323-59caf437-648e-4b7b-9b56-57e7bbd54414.png) >> ![image](https://user-images.githubusercontent.com/60425315/138439358-6deb93fe-fde3-4ad2-8409-7f0376a15705.png)

The new set of images with only letters and background were fed into VGG.

Then the weights of the model with some additional layers were used on the original dataset to classify images with letters and images without letters.

At last the model is test with the given test data. The result of test data was then stored in JSON file. while validation our result. this shows 100% accuracy fot the given test dataset.

## Output
![image](https://user-images.githubusercontent.com/60425315/138439374-887e727c-b484-499d-94d1-1e197804cd6f.png)
 ![image](https://user-images.githubusercontent.com/60425315/138439400-f6a15d99-1088-415d-9d1e-0c9b5c724232.png)
