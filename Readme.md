#  Create a Sample AWS Photo Analyzer application using the AWS SDK for Java

You can create an AWS application that analyzes nature images located in a S3 bucket. You can use the Amazon Rekognition service to analyze the images. 
The application can analyze many images and generate a report that breaks down each image into a series of labels. 
For example, the following image shows a lake.

![AWS Photo Analyzer](images/Lake.png)

The application you create is named *AWS Tracker*, and uses Spring Boot APIs to build a model, different views, and a controller. It’s a secure web application that requires a user to log into the application. For more information, see [Spring Boot - Securing Web Applications](https://www.tutorialspoint.com/spring_boot/spring_boot_securing_web_applications.htm).

This tutorial guides you through creating the AWS Tracker application. Once the application is developed, you'll learn how to deploy it to Elastic Beanstalk.

The following figure shows you the structure of the Java project.


