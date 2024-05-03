# Detecting-Alzheimer-s-Disease-in-MRI-using-Deep-Learning
Alzheimer's disease (AD) is a progressive disorder that causes difficulty in language and decision-making, memory loss and a decline in other cognitive abilities. Since there is no definite cure for this, diagnosing the disease in an early stage is the only prevention. However, detecting this disease in its early stages is one of the most difficult and challenging aspects as the symptoms of the early stages may start very early in life and are very subtle. Hence, there are instances where the disease isn’t caught until it is in its final stages. There have been factors found like genetics, age and lifestyle choice that can contribute to and even increase the chance of developing the disease. It's also critical to understand that detecting and treating AD can ease symptoms and enhance the patient's overall quality of life. In this study, our main objective is to detect if a person has AD using Magnetic Resonance Images (MRIs) and at which stage it is by exploring deep learning applications. One more objective of our study is to find out if changing the color scheme of MRIs has any effect on the performance of the initial goal. The present study successfully accomplished its objectives, as evidenced by the high accuracy of the proposed approaches in addressing the problem statement.

The images in the dataset are already preprocessed which makes it easier and faster to work with. The frequency of images of each category are: Class-1: 896, Class-2: 64, Class-3: 3200 and Class-4: 2240. 

## Distribution of images in the dataset ##

<img width="403" alt="image" src="https://github.com/Prajwal-Gupta/Detecting-Alzheimer-s-Disease-in-MRI-using-Deep-Learning/assets/61011807/c619b61a-da73-4fa0-b999-62f415287944">




## Methodology- ##
<img width="608" alt="image" src="https://github.com/Prajwal-Gupta/Detecting-Alzheimer-s-Disease-in-MRI-using-Deep-Learning/assets/61011807/81b56997-8529-4832-9112-27ad739bdd6a">



## Results- ##
After compiling the models on both the datasets, the accuracies are obtained. The accuracies are determined on the basis of the test dataset. It is to be noted that the accuracies presented in this table are the mean accuracies of all the runs.
<img width="526" alt="image" src="https://github.com/Prajwal-Gupta/Detecting-Alzheimer-s-Disease-in-MRI-using-Deep-Learning/assets/61011807/2de81df9-4192-40f4-b59c-09dad933fbc6">

### 1)CNN- ###
For CNN, training and validation loss drop significantly for around the first 15 epochs and then become relatively stable for subsequent epochs.

<img width="398" alt="image" src="https://github.com/Prajwal-Gupta/Detecting-Alzheimer-s-Disease-in-MRI-using-Deep-Learning/assets/61011807/3f2436f7-068a-4d1c-a5ca-bc22e1246f08">  <img width="416" alt="image" src="https://github.com/Prajwal-Gupta/Detecting-Alzheimer-s-Disease-in-MRI-using-Deep-Learning/assets/61011807/44a4c695-7f00-4d9a-ae31-6ab0bc4b0b29">



### 2) ResNet-50- ###
The ResNet50 model gave pretty positive results after being run on both the datasets. But it wasn’t able to outperform the CNN. 

For both the datasets, the values of loss start from a value greater than 1 but drop down quickly in first 5-10 epochs.

<img width="378" alt="image" src="https://github.com/Prajwal-Gupta/Detecting-Alzheimer-s-Disease-in-MRI-using-Deep-Learning/assets/61011807/61b1f95a-7086-4ed9-a95b-ff1c22770e13">  <img width="373" alt="image" src="https://github.com/Prajwal-Gupta/Detecting-Alzheimer-s-Disease-in-MRI-using-Deep-Learning/assets/61011807/bc1045f2-fcce-489f-9b64-663258cea93a">



### 3) EfficientNet B0- ###
The validation and training loss for the black and white dataset remains nearly equal except for a few epochs where some heavy fluctuations are seen. Also, the loss values start and remain near zero for the whole run for this dataset.

The validation and training loss for the black and white dataset remains nearly equal except for a few epochs where some heavy fluctuations are seen. Also, the loss values start and remain near zero for the whole run for this dataset.

<img width="362" alt="image" src="https://github.com/Prajwal-Gupta/Detecting-Alzheimer-s-Disease-in-MRI-using-Deep-Learning/assets/61011807/f899cec1-cd41-409c-97cf-d39c0127d3c1">   <img width="370" alt="image" src="https://github.com/Prajwal-Gupta/Detecting-Alzheimer-s-Disease-in-MRI-using-Deep-Learning/assets/61011807/c8ea154b-9fd6-4968-b653-32bfb684c42e">





*This project was published as a paper at the International Conference of Internet of Things 2023


