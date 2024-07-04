<h3>Motivation</h3>

In urban areas experiencing population growth, finding parking spaces has become a significant challenge. As cities expand, the need for efficient and automated parking management systems becomes more pressing. To address this issue, various approaches have been proposed, aiming to reduce the manual effort involved in parking. These approaches primarily focus on three key aspects: identifying parking spaces automatically, classifying individual parking spaces, and detecting and counting the number of vehicles in a parking area. While some methods rely on hardware-based solutions, such as sensors, recent trends favor software-based approaches that utilize computer vision algorithms and deep learning techniques. These vision-based methods are
valued for their flexibility and cost-effectivenes 
<hr>
<h3>Methodology</h3>
We have used a custom CNN achitecture for classifying whether the spot is empty or occupied. Dataset that was utilized for training and testing was CNRPark dataset. The total number of images of each class was 2500, which was further divided into train and test in the ratio of 8:2, respectively. The architecture performed best when the images were resized into 120x120 pixels. The accuracy was the tested on another dataset, wiz. PKLot dataset which contained 17000 images of each class. The accuracy came out to be 91%. 
<hr>
<h3>Demo:</h3>

https://github.com/ChiragOfficial/Car-Vacancy-Classification-System/assets/81742483/a6302143-988c-4788-a38d-f7b3c645de8b
<hr>
