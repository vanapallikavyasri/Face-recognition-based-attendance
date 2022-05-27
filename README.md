# Face-recognition-based-attendance
This is a desktop application which could take attendance of users by capturing their faces

## Steps to be followed to run this on your local machine

1.Clone or download this repository in to your local machine

2.Make sure to install python on your machine

3.Install the required libraries in your command prompt(for windows users) or in the terminal of yout favourite IDE

#### Run these commands on your terminal or cmd to install libraries

a)pip install numpy

b)pip install pandas

c)pip install Pillow

d)pip install opecv-python

4)After following the above steps,open command prompt(for windows users) or terminal of your IDE,change your path and run python app.py.

You will get this simple UI after following the steps which were mentioned above.

![Attendance System 26-05-2022 14_08_32 (1)](https://user-images.githubusercontent.com/72351336/170654633-eac3f1b3-62a8-4950-b05b-c9f58ecea6bd.png)

Initially there are two files in this project folder,they are app.py and haar cascades file(also known as viola jones alogorithm which will be used for object detection in an image or real time video)


If new user wants register ,enter your ID and Name and then click on capture your image button ,then camera pops up and captures you face for a while(until it takes 100 snapshots of your face) and you could press "Q" on your key board to turn off the camera.

![Taking Images 26-05-2022 18_59_19 (2)](https://user-images.githubusercontent.com/72351336/170674591-41982b6c-adfa-4e27-a185-aad87a4f8339.png)


The images which were captured will be stored in the training image folder.

![TrainingImage 27-05-2022 10_17_10](https://user-images.githubusercontent.com/72351336/170673972-8d3fe4e5-fead-431b-baef-2085796ad073.png)


Student details folder,training image label folder and attendance folder will be created.

![WhatsApp Image 2022-05-27 at 11 04 02 AM](https://user-images.githubusercontent.com/72351336/170662463-55d8fd87-6e8a-4aa6-a93d-2b4c8f50e702.jpeg)


As a new user registers ,while saving your profile,it asks for a password and that password that you have entered will be stored in training image label folder as psd.txt file and trainer.yml file will be created.

![WhatsApp Image 2022-05-27 at 11 02 34 AM](https://user-images.githubusercontent.com/72351336/170666868-e394c671-68ce-4b1f-9991-06bd80a0b944.jpeg)


After you have saved your profile successfully,student details folder internally creates an excel sheet with user details,you could open that excel sheet to find user details.

![WhatsApp Image 2022-05-27 at 11 02 06 AM](https://user-images.githubusercontent.com/72351336/170662780-51dc5e20-fde5-47dd-8449-d9d8c459ea3e.jpeg)


Now,it's time to take attendance....,when you click on take your attendance button which was in the UI,camera pops up and the face which was already trained will be recognised with it's name,you could press 'Q'on your keyboard to turn off the camera.

![Taking Attendance 26-05-2022 19_48_50](https://user-images.githubusercontent.com/72351336/170668737-d3d78830-956c-4a78-bf80-8e919dfd8014.png)

As u have pressed 'Q' to turn off your camera,you could find live attendance for the day on the screen in tabular format.

![Attendance System 26-05-2022 20_02_15](https://user-images.githubusercontent.com/72351336/170671017-720dc6ab-8b1d-432a-9e7e-08f0d65ac5ba.png)


As you have taken attendance, an excel sheet will be created inside the Attendance folder as per date and time and you could find deatils of users,if you open it 

![WhatsApp Image 2022-05-27 at 11 03 32 AM](https://user-images.githubusercontent.com/72351336/170669899-1aa997ea-5a38-482d-bbcc-e34d4b45cbed.jpeg)

You can press "Exit" button to quit from the page.














