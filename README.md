# Cifar-10-DS

![ImageNet-0000000008-f2e87edd_Y0fT5zg](https://user-images.githubusercontent.com/109751694/209488696-08833e33-7eaf-4010-b1a4-c54e1da22c3a.jpg)
Data set: 
Cifar10  
Download: https://www.cs.toronto.edu/~kriz/cifar.html#:~:text=The%20CIFAR%2D10%20dataset%20consists,batch%2C%20each%20with%2010000%20images.

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. The dataset is divided into five training batches and one test batch, each with 10000 images.

## Building KNN from Scratch with vectorized Computation that takes 0.001s to calculate 2 points

![image](https://user-images.githubusercontent.com/109751694/209488841-73c20c9f-1f16-4f4e-aaff-71170ae97910.png)
** K Value = 69 that has the best accuracy with acceptable tradeoff image.png where low varriance and low bias **

## Logistic Regression (One VS Rest)
![image](https://user-images.githubusercontent.com/109751694/209488872-a06e0d61-5958-4ea2-8c51-9283123d343a.png)
![image](https://user-images.githubusercontent.com/109751694/209488875-80c4e1d2-f42d-44ed-a960-7b00feae76f3.png)
![image](https://user-images.githubusercontent.com/109751694/209488879-048e78e0-44e1-4586-8dd9-015c846883a7.png)
![image](https://user-images.githubusercontent.com/109751694/209488884-bde106ad-0f0f-467f-9ce9-e105e05319eb.png)
![image](https://user-images.githubusercontent.com/109751694/209488888-9cfd5f32-69dc-4d13-a0da-1d68f93ca87f.png)
![image](https://user-images.githubusercontent.com/109751694/209488893-56cf61d4-6a74-4f8a-a10c-a27c428241e9.png)
![image](https://user-images.githubusercontent.com/109751694/209488897-b0cb29e9-bd85-4a2d-bf3b-bd2cbbe91ac7.png)
![image](https://user-images.githubusercontent.com/109751694/209488899-8ab7e0af-cb09-47d7-b1d8-38521df29a3f.png)
![image](https://user-images.githubusercontent.com/109751694/209488901-1c3f5dee-0532-471e-b61d-f15acd1cb145.png)

## Argmax Confusion all Classes 
![image](https://user-images.githubusercontent.com/109751694/209488927-2f0b1ef9-e514-4764-bf26-f7009cd45296.png)

## Support Vector Machine (SVM) Classification
        <div style="margin-left:40px"><code>
        for cost in [0.01, 0.1, 1, 10, 100]:<br/>
        &emsp;for gamma in [0.01, 0.1, 1, 10, 100]:
        </code></div>
### Cost with Regularization term
![image](https://user-images.githubusercontent.com/109751694/209489012-61e97b26-66a3-4be5-a88a-05fe5c7ec93e.png)

### Plot Cost VS Accuracy after adding the regularization term
![image](https://user-images.githubusercontent.com/109751694/209489015-d46979da-983e-4461-9e98-cb15c6bd4a8a.png)
### Cost and gamma with kernel
![image](https://user-images.githubusercontent.com/109751694/209489047-b5324a4e-e0af-4df8-a816-dd2c880face4.png)


## Confusion Matrix and classification report for the champion model 
![image](https://user-images.githubusercontent.com/109751694/209489082-3bb2be0f-7703-4979-b930-c12379e041d9.png)
![image](https://user-images.githubusercontent.com/109751694/209489084-f8c7c07a-5e12-4726-ab05-37105ee73294.png)

Compare the performance of the models in terms of the following criteria: precision, recall, accuracy, F-measure.

high F-score can be the result of an imbalance between Precision and Recall  >>>>>>> SVM champ model

The model maximizes the number of True Positives But it could be wrong sometimes!    >>>>>> Logistic Regression 

the classifier is very conservative - does not risk too much in saying that a sample is Positive.  >>>>  KNN



        
        
