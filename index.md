---
---
<h3 align="center">a Cloud-SPAN course</h3>

[Cloud-SPAN](https://cloud-span.york.ac.uk) is a project run by the Department of Biology at the University of York with the aim to training researchers in the experimental design and analysis of 'omics data using cloud-based High Performance Computing (HPC) resources.

This course teaches how to create and manage your own Cloud-SPAN Amazon Web Services (AWS) **instance**, which is a Linux virtual machine configured with 'omics data and software analysis tools. The instance you will create is the same instance that is used in the Cloud-SPAN courses [Prenomics](https://cloud-span.github.io/prenomics00-intro/) and [Genomics](https://cloud-span.github.io/genomics01-intro). As such it is an excellent vehicle for those who want to self-study those courses or have taken them and now want to practice further or with other materials in their own time.

You will learn (1) how to open and configure your AWS account, which will enable you to use any AWS service; (2) how to create and manage (start, stop and terminate) your instance; and (3) the cost of using your instance. 

The course is designed for 2-3 hours of self-study.

> ## Getting Started
>
> The course assumes that learners have no prior experience with the tools and concepts covered in the course and there is no need to install any specific software before the course. 
>
> However, learners are expected to (1) be familiar with using a browser such as Chrome and (2) use a laptop or desktop with a browser and with access to the Internet. 
>
> Tablets and mobile phones are not suitable for taking the course, as the screenshots that are shown through the course were taken from desktop screens. 
>
> Please note that this course does **not** cover **using your instance**. Tasks such as: logging to your instance and running genomics analyses are covered in the [Prenomics](https://cloud-span.github.io/prenomics00-intro/) and [Genomics](https://cloud-span.github.io/genomics01-intro) courses. Please see below the relevant sections of these courses under the heading **Where to go from here.** 
{: .prereq}

## Background

"*Cloud computing is the on-demand availability \[through the Internet\] of computer system resources \[such as\] data storage and computing power ... \[that\] relies on a "pay-as-you-go" model ..."\[[Wikipedia](https://en.wikipedia.org/wiki/Cloud_computing)\].* That means we can **rent** as many computing resources as we need, whenever we need them, and pay only for the time we use them. To start using Cloud resources all you need is access to the Internet, an email address and a credit card. 

The instance you will create in this course is a cloud resource known as **platform as a service**, or PaaS. The term **platform** refers to a resource composed of both (**virtualised: sofware-emulated**) hardware and a software environment such as Windows, Linux or MacOS. 

The main advantage of Cloud Computing is that you don't have to commit too much money and time in managing the IT resources needed to try out a new idea or experiment. Cloud computing enables you to create the resources you need and delete them once you are done to stop incurring costs. Other advantages include accessability and scalability.

You will use the **AWS Console** to open and configure your AWS account and to create and manage your instance. The AWS Console is a browser-based graphical user interface (GUI) that allows you to point and click options. There is no cost in using the AWS Console to create AWS resources. However, you may incur costs after your resources have been created if, for instance, they require storage beyond some limits as outlined next.  

The largest cloud providers at the time of writing in terms of market share are Amazon AWS, Microsoft Azure and Google Cloud Platform. When you open an account with these providers, your account will include one-year free tier use of most of their services **within some limits**. This allows you to evaluate their services with no or little cost before committing to a particular provider. Please beware of those limits so you don't incur unwanted costs. Note that there are many other cloud providers and some may offer better prices and also a free trial period. Once you finish this course, you will be able to better choose from the offerings available.

# Course Overview

| Lesson                     | Overview |
| -------------------------- | ---------|
| [Open your AWS account](https://cloud-span.github.io/create-aws-instance-1-open-account/) | Learn how to open and configure your AWS account, which enables you to use AWS services.|
| [Create and manage your AWS instance](https://cloud-span.github.io/create-aws-instance-2-manage-instance/)| Learn how to create, start, stop, and terminate your instance using the AWS Console. See section below `Where to go from here` for instructions to logging to your instance and running 'omics applications, among other topics. |
| [AWS Costs Explained](https://cloud-span.github.io/create-aws-instance-3-costs-explained/) | Learn about the costs of using your Cloud-SPAN AWS instance, the AWS Free Tier and Research Credits available.|

## Help and Support

If you need some help to complete this course, or would like to discuss further some of its topics, you can join our weekly drop-in sessions held on Thursdays at 3pm. Please follow this link to our Zoom/Blackboard [Drop-in Sessions](something).

## Where to go from here

| Resource                   | Description |
| -------------------------- | ---------|
| [Installing Git Bash](https://cloud-span.github.io/prenomics00-intro/setup.html)| Only Windows users need these instructions to install the Git Bash program which is needed to login into their instance. (Linux and MacOs users should use the `terminal` program to login into their instance.)|
| [Logging to your instance](https://cloud-span.github.io/prenomics01-file-directories/02-logging-onto-cloud/) | Instructions to login to your instance (a lesson from the Cloud-SPAN Prenomics course).|
| [Using the Shell](https://cloud-span.github.io/prenomics02-command-line/) | Instructions for you to use your instance through the command line interface, also known as the Shell (a lesson from the Cloud-SPAN Prenomics course).|
| [Running 'omics applications](https://cloud-span.github.io/00genomics/)| Examples of using 'omics data and applications (the foundation Cloud-SPAN Genomics course). |
