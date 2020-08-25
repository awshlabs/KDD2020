# KDD2020 Put Deep Learning to Work: Accelerate Deep Learning through AWS SageMaker and ML Services  (8/25 at 9AM PDT)
# Abstract
Deploying deep learning (DL) projects are becoming increasingly more pervasive at enterprises and startups alike. At Amazon, Machine Learning University (MLU)-trained engineers are taking DL to every aspect of Amazon’s businesses, beyond just Amazon Go, Alexa, and Robotics.
In this workshop, Wenming Ye (AWS), Rachel Hu (AWS), and Miro Enev(Nvidia) offer a practical next step in DL learning with instructions, and hands-on labs using the latest Nvidia GPUs and AWS Inferentia. You will explore the current trends powering AI/DL adoption, powerful new GPU/AWS Inferentia accelerator instances, distributed training and inference optimization in neural networks.

Wenming Ye  (AWS),
Rachel Hu   (AWS),
Miro Enev   (Nvidia).

Thank you for attending our session at KDD2020.

If you are interested in our Research reward program, please see the link below. Or contact me directly. 
https://aws.amazon.com/aws-ml-research-awards/

## Agenda

1. 9:00 Welcome and Logistics
1. 9:05  Amazon AI and SageMaker Overview
1. 9:40  BERT and Transformer
1. 10:30 Lab: Training/FineTuning Q&A model 
1. 	(10 min break during model training)
1. 11:15 Lab: Model Deployment
1. 11:30 Nemo Demo & Conclusion


Amazon SageMaker is a fully-managed service that enables developers and data scientists to quickly and easily build, train, and deploy machine learning models at any scale. Amazon EC2 P3 instances deliver the highest performance compute in the cloud, are cost-effective, support all major machine learning frameworks, and are available globally. In this workshop, you'll create a SageMaker notebook instance and work through sample Jupyter notebooks that demonstrate some of the many features of SageMaker and how Amazon EC2 P3 is used to accelerate machine learning model training.


## Prerequisites

You will need a Laptop.  We recommend that you have an extra Screen such as a Phone, or IPad, if available.

**Slides**

Available Soon.

### AWS Account
AWS account is not required for this Lab, you will be provided with a HashURL to access a pre-provisioned AWS environment.

## License

The contents of this workshop are licensed under the Apache 2.0 License.

## Live Lab Instructions: 

1. Goto Events engine website (will be given during live event), on team dashboard, click on AWS Console. If you are using your own account, skip to step 3.
1. Now click on Open AWS Console.  Find, and Click on **SageMaker** Service link on the mainpage. 
1. On the left side menu, go down to Notebook, select submenu item Notebook instances. Now, click on the orange Create notebook instance Button.
1. Pick a notebook instance name in the first text box.
1. For notebook instance type, select ml.c5.2xlarge.  
1. Under Additional Configuration, Set volume size to be **50 GB**. 
1. Under Git repositories, select Clone a Public Git.... Then, enter: https://github.com/goldmermaid/KDD-2020 in the text box.
1. Click on Open Jupyter when the status turns Green "In Service", click on Open Jupyter. 
1. Open bert_pytorch_finetuning.ipynb in KDD-2020/bert_finetuning_kdd directory. 



