# Basic-ID3-algorithm-and-Na-ve-Bayes-classifier

Problem:
In this problem we will use the iris data set that contains 3 classes that are:
Setosa, virginica and versicolor.
We will combine the virginica and versicolor classes into one class and call it not_setoza.
Data visualization:
Plotting the original data after combining the two classes (virginica and versicolor):
Data shape:
 ![image](https://user-images.githubusercontent.com/74180896/175568314-88cb5fb0-11be-4783-924d-d10b218b1878.png)

Data type for each attribute:
 ![image](https://user-images.githubusercontent.com/74180896/175568342-d4d121e7-5c18-47dd-9f17-13e5744d425a.png)

The first lines of the data:
 ![image](https://user-images.githubusercontent.com/74180896/175568370-a9204e8e-b7e7-4a03-9b04-c5dbeef8af86.png)

Plotting data in function of 2 attributes:
 ![image](https://user-images.githubusercontent.com/74180896/175568399-dfcf4eae-5320-434c-9db3-656c8f5981d5.png)


Implementing the two Algorithms (Basic ID3 algorithm and Naïve Bayes classifier)
1)	Implementing the Basic ID3 algorithm:

2)	Implementing the Naïve Bayes classifier:

Now we discretize data by using bins and round to the nearest integer:
(We used the histogram to discretize. Since we found some overlaps we decided to use KBinsDiscretizer from Sklearn after we had the authorization from the professor)
For the ID3 Algorithm we calculate Max_accuracy, min_accuracy, and average accuracy over the different number of bins:
We obtain the following result:
 ![image](https://user-images.githubusercontent.com/74180896/175568615-08bb7379-f919-42a6-98ad-5854587a993f.png)

We plot these accuracy values as a function of the number of bins:
 ![image](https://user-images.githubusercontent.com/74180896/175568695-99440942-2343-407a-804d-9fa7db534288.png)

		
For the Naive Algorithm we calculate  Max_accuracy, min_accuracy, and average accuracy over the different number of bins:
We obtain the following result:
 ![image](https://user-images.githubusercontent.com/74180896/175568751-e6488fbe-3697-4deb-9081-68e2230dc9e6.png)


We plot these accuracy values as a function of the number of bins:
 
![image](https://user-images.githubusercontent.com/74180896/175568788-0d91dd02-115e-4b84-8987-c3dfe71126fa.png)

