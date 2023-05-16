---
---
<h3 align="center">a Cloud-SPAN course</h3>

[Cloud-SPAN](https://cloud-span.york.ac.uk) is a project run by the Department of Biology at the University of York with the aim to training researchers in the experimental design and analysis of 'omics data using cloud-based High Performance Computing (HPC) resources.

This course teaches how to create and manage your own Amazon Web Services (AWS) **instance**, which is a Linux virtual machine configured with 'omics data and software analysis tools. You will be able to create any of the instances used in the Cloud-SPAN courses [Prenomics](https://cloud-span.github.io/prenomics00-intro/), [Genomics](https://cloud-span.github.io/00genomics), [Metagenomics](https://cloud-span.github.io/metagenomics00-overview/), or [Metagenomics for Environmental Scientists](https://cloud-span.github.io/nerc-metagenomics00-overview/). 

If you attend tutor-led editions of those Cloud-SPAN courses, you do not need to create your own instance. We will do that for you! But if would like to practice afterwards, or study those courses in your own time, you will need to create your instance first.

You will learn (1) how to open and configure your AWS account, which will enable you to use any AWS service; (2) how to create and manage (start, stop, terminate and change the compute capacity of) your instance; and (3) the cost of using your instance. 

The course is designed for 2-3 hours of self-study.

> ## Getting Started
>
> The course assumes that learners have no prior experience with the tools and concepts covered in the course and there is no need to install any specific software before the course. 
>
> However, learners are expected to (1) be familiar with using a browser such as Chrome and (2) use a laptop or desktop with a browser and with access to the Internet. 
>
> Tablets and mobile phones are not suitable for taking the course, as the screenshots that are shown through the course were taken from desktop screens. 
>
> Please note that this course does **not** cover **using your instance**: tasks such as managing the data in your instance or running 'omics analyses are covered in the courses [Prenomics](https://cloud-span.github.io/prenomics00-intro/), [Genomics](https://cloud-span.github.io/00genomics/), [Metagenomics](https://cloud-span.github.io/metagenomics00-overview/), and [Metagenomics for Environmental Scientists](https://cloud-span.github.io/nerc-metagenomics00-overview/).
{: .prereq}

## Background

"*Cloud computing is the on-demand availability \[through the Internet\] of computer system resources \[such as\] data storage and computing power ... \[that\] relies on a "pay-as-you-go" model ..."\[[Wikipedia](https://en.wikipedia.org/wiki/Cloud_computing)\].* That means we can **rent** as many computing resources as we need, whenever we need them, and pay only for the time we use them. To start using Cloud resources all you need is access to the Internet, an email address, and a credit card. 

The instance you will create in this course is a cloud resource known as **platform as a service**, or PaaS. The term **platform** refers to a resource composed of both (**virtualised: sofware-emulated**) hardware and a software environment such as Windows, Linux or MacOS. 

The main advantage of Cloud computing is that you don't have to commit too much money and time in managing the IT resources needed to try out a new idea or experiment. Cloud computing enables you to create the resources you need and delete them once you are done in order to stop incurring costs. Other advantages of Cloud computing include *accessability* to your Cloud resources from anywhere anytime, and *scalability* which enables you to increase and decrease the compute, storage, and network capacities of your resources relatively easily, among other advantages.

You will use the **AWS Console** to open and configure your AWS account and to create and manage your instance. The AWS Console is a browser-based graphical user interface (GUI) that allows you to point and click options. There is no cost in using the AWS Console to create AWS resources. However, you may incur costs after your resources have been created if, for instance, they require storage beyond some limits as outlined next.  

The largest cloud providers at the time of writing in terms of market share are *Amazon AWS*, *Microsoft Azure* and *Google Cloud Platform*. When you open an account with these providers, your account will include one-year free tier use of most of their services **within some limits**. This allows you to evaluate their services with no or little cost before committing to a particular provider. Please beware of those limits so you don't incur unwanted costs. Note that there are many other cloud providers and some may offer better prices and also a free trial period. Once you finish this course, you will be able to better choose from the offerings available.

# Course Overview

| Lesson                     | Overview |
| -------------------------- | ---------|
| [Open your AWS account](https://cloud-span.github.io/create-aws-instance-1-open-account/) | Learn how to open and configure your AWS account, which enables you to use AWS services.|
| [Create and manage your AWS instance](https://cloud-span.github.io/create-aws-instance-2-manage-instance/)| Learn how to create, start, stop, terminate, and change the compute capacity of your instance using the AWS Console, and how to login to your instance. |
| [AWS Costs Explained](https://cloud-span.github.io/create-aws-instance-3-costs-explained/) | Learn about the costs of using your Cloud-SPAN AWS instance, the AWS Free Tier and Research Credits available.|

## Where to go from here
Once you have created your instance you will be able to follow Cloud-SPAN's [Prenomics](https://cloud-span.github.io/prenomics00-intro/), [Genomics](https://cloud-span.github.io/00genomics/), [Metagenomics](https://cloud-span.github.io/metagenomics00-overview/), and [Metagenomics for Environmental Scientists](https://cloud-span.github.io/nerc-metagenomics00-overview/) modules. 

| Module                     | Description |
| -------------------------- | ---------|
| [Prenomics](https://cloud-span.github.io/prenomics00-intro/)| Prenomics is a 4 - 6 hour module that teaches the basics of command-line programming, including: (1) file directory structure, (2) use of command-line utilities to connect to and use cloud computing and storage resources and (3) basic shell commands for file navigation and basic script writing. It is designed to prepare people for  [Genomics](https://cloud-span.github.io/00genomics) but, depending on previous experience, you may not need it. There is short (~5 minutes) [Self-assessment Quiz](https://shiny.york.ac.uk/er13/prenomics-quiz/#section-why) to help you decide if you would benefit from attending Prenomics before the Genomics.|
| [Genomics](https://cloud-span.github.io/00genomics/) | Genomics is a 8 - 12 hour module that teaches data management and analysis for genomics research including: (1) best practices for organization of bioinformatics projects and data, (2) use of command-line utilities to connect to and use cloud computing and storage resources, (3) use of command-line tools for data preparation, (4) use of command-line tools to analyze sequence quality and perform and automate variant calling. |
| [Metagenomics](https://cloud-span.github.io/metagenomics00-overview/)  | This course teaches data analysis for metagenomics projects. It covers how to (1) generate and QC a metagenome assembly, (2) ‘bin’ the assembly into metagenome assembled genomes (MAGs) also known as bins, (3) identify the taxonomy of these MAGs and, (4) calculate diversity metrics and add functional annotation to identify the products of genes identified in the assembled MAGs. There is 4 - 8 hrs teaching material but the course is delivered over 3 or 4 weeks since many of the analyses take several hours to run. Each week there is a taught session covering the background to the week's material before you work though the lesson at your own pace, followed by a drop-in session to help with any problems. |
| [Metagenomics for Environmental Scientists](https://cloud-span.github.io/nerc-metagenomics00-overview/)   | This course is aimed at environmental scientists with little or no experience of using high performance computing (HPC) for data analysis. It is taught over two-weeks online using a mixture of live coding, online lectures, offline time for long analyses to complete and drop-in sessions. It covers (1) Using the command line to log into cloud resources, navigate filesystems and carry out filesystem housekeeping, (2) what metagenomics is, the difference between genomics and metagenomics and the different types of sequencing platforms, and (3) metagenomics analysis including quality control, assembly, polishing, binning and taxonomic assignment. |

