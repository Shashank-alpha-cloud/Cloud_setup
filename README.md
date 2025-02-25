# Cloud_setup

COMPANY: CODTECH IT SOLUTIONS

NAME: Shashank 

INTERN ID: :CT6WUSP

DOMAIN: Cloud Computing

DURATION: 6 WEEEKS

MENTOR: NEELA SANTOSH

Task 1


#Cloud Setup (TASK 1)
Here's a detailed **500-word description** covering the setup of **AWS Cloud**, creating an **S3 bucket**, uploading an image, and generating an object URL.  

---

### **Setting Up Cloud in AWS and Creating an S3 Bucket to Upload an Image**  

Amazon Web Services (AWS) is a leading cloud computing platform that provides a variety of services, including storage, computing power, and databases. One of its most widely used storage solutions is **Amazon Simple Storage Service (Amazon S3)**, which enables users to store and retrieve data securely. In this guide, we will walk through the process of setting up an AWS environment, creating an S3 bucket, uploading an image, and generating an object URL for sharing.  

#### **Step 1: Setting Up AWS Cloud Environment**  
Before working with AWS S3, you need to set up an AWS account. If you do not have one, you can create it by visiting [AWS’s official website](https://aws.amazon.com/) and signing up. After registration, log in to the **AWS Management Console**. AWS offers a **free tier** that allows limited usage of various services, including S3, making it ideal for beginners.  

#### **Step 2: Creating an AWS S3 Bucket**  
Once you have access to the AWS console, follow these steps to create an S3 bucket:  

1. **Navigate to the S3 Service:**  
   - Search for **"S3"** in the AWS Console’s search bar.  
   - Click on **Amazon S3** to open the service.  

2. **Create a New Bucket:**  
   - Click on the **"Create bucket"** button.  
   - Enter a unique **Bucket Name** (S3 bucket names must be globally unique).  
   - Choose an **AWS Region** (preferably one closest to your location for better performance).  

3. **Configure Bucket Settings:**  
   - In the **Block Public Access settings**, you can choose whether the bucket should be publicly accessible. If you want to share files externally, you may need to disable some public access restrictions.  
   - Enable **versioning** if you want to keep multiple versions of files.  
   - Set **encryption options** if you need additional security.  

4. **Create the Bucket:**  
   - Click **Create bucket**, and the S3 bucket will be ready for use.  

#### **Step 3: Uploading an Image to the S3 Bucket**  
Now that the bucket is created, we can upload an image to store it in S3.  

1. **Open the Bucket:**  
   - Navigate to the **bucket name** in the S3 console.  

2. **Upload the Image:**  
   - Click on **"Upload"** and then **"Add files"** to select an image from your local system.  
   - Choose the appropriate **storage class** (e.g., Standard, Intelligent-Tiering, or Glacier, depending on usage).  

3. **Adjust Permissions (Optional):**  
   - If you want the file to be publicly accessible, you must modify permissions by selecting **"Make public"** during the upload process.  

4. **Click Upload:**  
   - The image will be uploaded and available in your S3 bucket.  

#### **Step 4: Generating an Object URL**  
Once the image is uploaded, AWS provides an **Object URL**, which can be used to access the file.  

1. **Locate the Image in the Bucket:**  
   - Click on the uploaded image.  

2. **Copy the Object URL:**  
   - In the **Properties** section, find the **Object URL**.  
   - Copy this URL, which can now be shared with others.  

#### **Conclusion**  
By following these steps, you have successfully set up AWS, created an S3 bucket, uploaded an image, and generated an **Object URL** for external sharing. If the URL does not work due to permissions, you may need to adjust the **bucket policy** or use **presigned URLs** to grant temporary access. AWS S3 provides a reliable and scalable solution for storing and sharing files in the cloud. 🚀



PLease Find the attachments of Objeect Url which has public access in it And this Generates from Aws CloudS3 
https://myownbucket2333.s3.ap-south-1.amazonaws.com/codtech-it-solutions-overview-1727454583247.webp
