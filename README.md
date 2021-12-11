# Creating-a-SNS-Topic-and-Subscribing-through-Email

Architecture Diagram

![SNS](https://user-images.githubusercontent.com/54776422/145666136-19469525-2c88-4c3a-a882-ccd45f5bef2b.png)

# Creating SNS Topic

Make sure you are in the US East (N. Virginia) us-east-1

Navigate to the  menu and click on Simple Notification Service (SNS) under the  section.

# Select Topics in the left panel and click CREATE TOPIC

# UNDER DETAILS 

Type: Select Standard

Name: Enter mysnstopic

Display name: mysnsnotification

<img width="1032" alt="TOPIC" src="https://user-images.githubusercontent.com/54776422/145666229-50bc3e2d-3ef5-40fe-a052-dc532bb68424.png">

# Leave other options as default and click on # Create topic.

An SNS topic will be created.

![image6_12_49](https://user-images.githubusercontent.com/54776422/145666283-8eea49c5-9054-45ef-a649-d8f6d063e535.png)

# Subscribing to the Topic
Once the SNS Topic is created, click on your topic.

Click Create subscription

Under Details

Protocol: Select Email

Endpoint: Enter your <Mail Id>

Note: Make sure you give a valid mail address as you will receive an SNS notification to this address.

# Click on Create Subscription.
