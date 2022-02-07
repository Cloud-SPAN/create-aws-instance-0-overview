---
---
<h3 align="center">a Cloud-SPAN course</h3>

[Cloud-SPAN](https://cloud-span.york.ac.uk) is a project run by the Biology Department of the University of York with the aim to develop advanced modules covering specialised knowledge and skills to generate and analyse 'omics data using cloud-based High Performance Computing (HPC) resources.

This course teaches how to create and manage your own Cloud-SPAN Amazon Web Services (AWS) instance, which is a Linux virtual machine configured with 'omics data and software analysis tools. The instance you will create is the same instance used in the Cloud-SPAN courses [Prenomics](https://cloud-span.github.io/prenomics00-intro/) and [Genomics](https://cloud-span.github.io/genomics01-intro). Hence, it is an excellent vehicle for those who want to self-study those courses or have taken them and now want to practice further or with other materials in their own time.

You will learn (1) how to create and configure your AWS account, (2) how to manage (create, start, stop and terminate) your instance, and (3) the cost of using your instance. 

The course is designed for 2-3 hours of self-study.

> ## Getting Started
>
> The course assumes that learners have no prior experience with the tools and concepts covered in the course and there is no need to install any specific software before the course. 
>
> However, learners are expected to (1) be familiar with using a browser such as Chrome and (2) use a laptop or desktop with a browser and with access to the Internet. 
>
> Tablets and mobile phones are not suitable for taking the course, as the screenshots that are shown through the course were taken from desktop screens. 
>
> Please note that this course does **not** cover **using your instance**: logging to your instance, running analysis programs, etc. These topics are covered in the courses [Prenomics](https://cloud-span.github.io/prenomics00-intro/) and [Genomics](https://cloud-span.github.io/genomics01-intro). 
{: .prereq}

## Background

"Cloud computing is the on-demand availability \[through the Internet\] of computer system resources \[such as\] data storage and computing power ... \[Cloud computing\] relies on a "pay-as-you-go" model ..."\[[Wikipedia](https://en.wikipedia.org/wiki/Cloud_computing)\]. That means we can **rent** computing resources whenever we need them, as many as we need, and pay only for the time we use them. All we need is access to the Internet and a credit card to start using Cloud resources. 

The instance you will create in this course is a cloud resource known as `platform as a service`, or PaaS. The term `platform` refers to a resource composed of both (`virtualised: sofware-emulated`) hardware and a software environment such as Windows, Linux or MacOS. It is a complete solution ready to use. There is also `infrastructure as a service` and `software as a service`, or IaaS and SaaS respectively. IaaS refers to physical or virtualised hardware resources on which you can deploy and configure some specific software. SaaS refers to any software-based service such as Gmail, Google Docs, Databases, Microsoft Office, and there are also Machine Learning services, among many others. 

The main advantage of Cloud Computing is that you don't have to commit upfront too much money and time in managing the IT resources you need to try out a new idea, experiment, etc. Cloud computing enables you to use the resources you need immediately once you create them, and delete them once you are done in order to stop incurring costs.

You are going to create and manage your instance using the `AWS Console`, an intuitive, browser-based graphical user interface (GUI) which is used mostly through choosing (clicking on) options with the mouse and entering a few details with the keyboard.  There are other ways to manage AWS resources which require more time to learn but facilitate the automation of managing tasks on multiple resources; they will be introduced later in the course. 

Although the biggest cloud providers in terms of market share at the end of 2020 were Amazon AWS (33%), Microsoft Azure (19%) and Google Cloud Platform (7%), there are many other cloud providers which are likely to offer more competitive prices. Once you finish this course, you will be able to better choose from the offerings available.

# Course Overview

| Lesson                     | Overview |
| -------------------------- | ---------|
| [Open your AWS account](https://cloud-span.github.io/create-aws-instance-1-open-account/) | Learn how to open and configure your AWS account, which enables you to use AWS services.|
| [Create and manage your AWS instance](https://cloud-span.github.io/create-aws-instance-2-manage-instance/)| Learn how to create, start, stop, and terminate your instance using the AWS Console. See section below `Where to go from here` for instructions to logging to your instance and running 'omics applications, among other topics. |
| [AWS Costs Explained](https://cloud-span.github.io/create-aws-instance-3-costs-explained/) | Learn about the costs of using your Cloud-SPAN AWS instance, the AWS Free Tier and Research Credits available.|

## Help and Support

If you need some help to complete this course, or would like to discuss further some of its topics, you can join our weekly drop-in sessions held on Thursdays at 3pm, on Zoom/Blackboard following this link: [Drop-in Sessions](something).

## Where to go from here

| Resource                   | Description |
| -------------------------- | ---------|
| [Installing Git Bash](https://cloud-span.github.io/00genomics/)| Windows users only  need these instructions to install the Git Bash program which is needed to login to their instance. (Linux and MacOs users should use the `terminal` program.)|
| [Logging to your instance](https://cloud-span.github.io/prenomics01-file-directories/02-logging-onto-cloud/) | Instructions to login to your instance (a lesson from the Cloud-SPAN Prenomics course).|
| [Using the Shell](https://cloud-span.github.io/prenomics02-command-line/) | Instructions for you to use your instance through the command line interface, also known as the Shell (a lesson from the Cloud-SPAN Prenomics course).|
| [Running 'omics applications](https://cloud-span.github.io/00genomics/)| Examples of using 'omics data and applications (the foundation Cloud-SPAN Genomics course). |
