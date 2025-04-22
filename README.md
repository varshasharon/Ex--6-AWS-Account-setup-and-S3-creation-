```
Reg no: 212222100058
Name: varsha sharon
```

# Ex--6-AWS-Account-setup-and-S3-creation

## Introduction
In this lab, we are going to be introduced to one of the famous Cloud Service providers, Amazon Web Services (AWS). We will work on Amazon Simple Storage Service (S3), which provides storage through web service interfaces (REST, SOAP, and BitTorrent). In S3, the data is stored in the form of buckets. Buckets serve as root folders where we can add, create, or upload files and folders. We can create multiple buckets for different purposes, and each bucket can have different access control policies.

## Objectives
Create a Bucket in Amazon S3.
Add Objects (files and folders) to the bucket.
Access, move, download, and delete the objects.
Delete the Bucket.

### Step 1: Choose S3 Service
Choose the S3 service from the list of services provided by AWS.

### Step 2: Create a Unique Bucket
After selecting the S3 service, click on the "Create Bucket" button on the page. The bucket name must be unique, contain no uppercase letters, and have no special characters. If you enter any of these, an error will display, preventing the bucket from being created.


For region selection, choose a region from the available list. It is recommended to select a region nearby your location for higher availability. In this lab, I selected Sydney, as it is near my country, New Zealand. Remember to provide a unique bucket name with no special characters or uppercase letters.

### Step 3: Upload Files to the Bucket
Now, I have uploaded some files into the bucket I just created. There are no restrictions on uploading file types, but the size of each file must be less than 5 terabytes.

You can upload files of any extension, folders, and subfolders. The images below explain that you can drag and drop files or select them from your computer. After uploading a file, you can download, cut, copy, make it public, rename, or delete it. Making a file public means everyone can access it, and you will receive a link (e.g., https://s3-ap-southeast-2.amazonaws.com/...) to share it.

### Step 4: Upload a Folder
You can also upload a folder to the bucket. If your local folder contains subfolders and data, all data inside the parent folder will be uploaded. The images below show how to upload a folder by dragging and dropping or browsing.

### Step 5: Delete the Bucket
To delete a bucket, you must retype the bucket name. This policy is implemented by Amazon to confirm your action because deleting a bucket can remove large amounts of data.

## Output:
![image](https://github.com/user-attachments/assets/c6291ec2-d560-4d2d-b12a-b43eb389724a)
![image](https://github.com/user-attachments/assets/7c28fb7b-6b2c-4d97-986c-fe3b2797a2f2)
![image](https://github.com/user-attachments/assets/10ba6aa9-9c74-49dd-aedb-5468e3a6f8e5)
![image](https://github.com/user-attachments/assets/79b05738-1be6-4fee-8ca8-31fb4813f791)

![image](https://github.com/user-attachments/assets/de26754d-24d0-4ce7-a027-72fe343e7375)



## Result
Successfully created, managed, and deleted an S3 bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon S3.
