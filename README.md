# sagemaker-workshop
This workshop is divided into multiple modules. Module 1 must be completed first, followed by Module 2. Remaining modules are optional and can be completed in any order.

1. Creating a SageMaker NoteBook instance and setting up Cloud9 environment.
2. Video Games Sales Prediction with XGBoost (In-built Algorithm)

#Module 1: Creating a SageMaker Notebook Instance and setting up Cloud9 environment
In this module we start by creating a S3 bucket, which will be used throughout the workshop. We'll then create a sage maker notebook instance followed up setting up the cloud 9 environment.
SageMaker is available in following regions in EU:
- London
- Ireland
- Frankfurt

You can choose to run the your instances in any of these regions. For simplicity we will choose Ireland(eu-west-1) for this workshop. 

Create S3 Bucket:

SageMaker uses S3 as storage for data and model artifacts. In this step you’ll create a S3 bucket for this purpose. To begin, sign into the AWS Management Console, https://console.aws.amazon.com/.

Keep in mind that your bucket’s name must be globally unique across all regions and customers. We recommend using a name like smworkshop-firstname-lastname. If you get an error that your bucket name already exists, try adding additional numbers or characters until you find an unused name.

In the AWS Management Console, choose Services then select S3 under Storage.

Choose Create Bucket

Provide a globally unique name for your bucket such as ‘smworkshop-firstname-lastname’.

Select the Region you’ve chosen(Ireland) to use for this workshop from the dropdown.

Choose Create in the lower left of the dialog without selecting a bucket to copy settings from.

Launch the Notebook Instance:

In the upper-right corner of the AWS Management Console, confirm you are in the desired AWS region. Select Ireland.

Click on Amazon SageMaker from the list of all services. This will bring you to the Amazon SageMaker console homepage.

