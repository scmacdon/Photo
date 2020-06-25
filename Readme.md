#  Create a Sample AWS Photo Analyzer application using the AWS SDK for Java

You can create an AWS application that analyzes nature images located in a S3 bucket. You can use the Amazon Rekognition service to analyze images. 
The application can analyze many images and generate a report that breaks down each image into a series of labels. 
For example, the following image shows a lake.

![AWS Photo Analyzer](images/Lake.png)

After the application analyzes this image, it creates this data. 
*	Panoramic - 99.99971
*	Outdoors - 99.99971
*	Nature - 99.99971
*	Landscape - 99.99971
*	Scenery	 - 99.99971
*	Wilderness - 96.90007
*	Water - 93.501465
*	Lake - 87.28128

In addition, this application uses the Simple Email Service (SES) to send a report to a given email recipient. In this tutorial, you create a Spring Boot application named AWS Photo Analyzer application. The Spring Boot APIs are used to build a model, different views, and a controller. 

This application uses these AWS Services: 
*	Amazon Rekognition
*	Amazon S3
*	Amazon Simple Email Service
*	AWS Elastic BeanStalk

**Cost to complete:** The AWS Services included in this document are included in the [AWS Free Tier](https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc). 

**Note:** Be sure to terminate all of the resources you create while going through this tutorial to ensure that you’re no longer charged.

