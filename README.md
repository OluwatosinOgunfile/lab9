# A Walkthrough for the Guided Lab: Securing Applications by Using Amazon Cognito

Hi, 

Due to the change in the AWS Management Console, some instructions for securing a web application with Amazon Cognito do not align with the new interface. Given this, I have prepared a video to help guide you through a walk-around I created (https://youtu.be/y8XmwAfcZTI?si=tkuYk2ofmF7vCdiv). Kindly like the video if you find it helpful. 

You can also follow the instructions below:

1. After step 23, press Ctrl C to stop the npm server

2. Run these commands:

```
git clone https://github.com/OluwatosinOgunfile/lab9.git
cd lab9
. ./setup.sh
```

3. Enter your chosen User Pool Domain Prefix by following the prompt. Wait for about 2 to 3 minutes for the code to run.

4. Press q  if needed to release the bash prompt. If there is an error, you will get “None” for the User Pool ID.  If there are no errors, you will get the values for the three parameters below. Copy the following information:

     - CloudFront Domain
     - User Pool ID
     - Cognito Domain Prefix
     - App Client ID

5. Proceed to step 38.

# This is a sample of what to expect when you run the code

![image](https://github.com/user-attachments/assets/0fc1c60b-f285-475f-a18f-a55632e1ded6)

To confirm that all resources have been created, run `. ./setup` again. Enter the same  User Pool Domain Prefix at the prompt. A result similar to the image below should be expected.
![image](https://github.com/user-attachments/assets/c06de388-b30a-45f3-b51a-142b9dce7f29)

