# Linux_world_task_3

Create Live Streaming Video Chat App without voice using cv2 module of Python

1.Module required for this task is opencv to install this module we use below command:-

![image](https://user-images.githubusercontent.com/60494696/120881480-51561500-c59f-11eb-9601-ccb34fb947cd.png)

2.Software requirement ---> Jupyter Notebook

![image](https://user-images.githubusercontent.com/60494696/120881553-e6f1a480-c59f-11eb-8791-b581fce41d60.png)

3.Launch Jupyter Notebook and make a python file there and add some cell in the file.

![image](https://user-images.githubusercontent.com/60494696/120881594-4a7bd200-c5a0-11eb-88ad-c900351902bf.png)

4.In first cell we import the opencv module 

![image](https://user-images.githubusercontent.com/60494696/120881697-17860e00-c5a1-11eb-933e-8132f0249534.png)

5.In second cell we use cv2.VideoCapture() funtion which capture the photo from the cam and put the function value in cap variable.

![image](https://user-images.githubusercontent.com/60494696/120881730-5b791300-c5a1-11eb-9197-22a68dd11bea.png)

6.Now in third cell we use read() function which read the value of cap variable and also created 2 variable with the name ret & photo.

![image](https://user-images.githubusercontent.com/60494696/120881796-a2ff9f00-c5a1-11eb-987d-e6ed792da7f0.png)

7.Now we create a loop.

![image](https://user-images.githubusercontent.com/60494696/120881843-fd006480-c5a1-11eb-950d-fdaac9ee4d28.png)

(if cv2.waitKey(10) == 13: this line capture the photo in every 10 milesec and imshow() function show the click photo continuously and this will look like continuous video streaming)

8.And at last window is close by this function.
![image](https://user-images.githubusercontent.com/60494696/120881932-9b8cc580-c5a2-11eb-99f6-cdc2b9c0e438.png)

9. And to close the camera we have to make use of cap.release() function.
![image](https://user-images.githubusercontent.com/60494696/120881968-cc6cfa80-c5a2-11eb-8969-dbd113385578.png)

10.Now run the code and we can see continuous live video stream.
![image](https://user-images.githubusercontent.com/60494696/120882048-42716180-c5a3-11eb-88f3-e6694978fc71.png)







