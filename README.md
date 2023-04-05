# 	Running Windows Containers on AWS

<a href="https://www.packtpub.com/product/running-windows-containers-on-aws/9781804614136?utm_source=github&utm_medium=repository&utm_campaign=9781801076012"><img src="https://content.packt.com/B19252/cover_image_small.jpg" alt="Running Windows Containers on AWS" height="256px" align="right"></a>

This is the code repository for [Running Windows Containers on AWS](), published by Packt.

**A complete guide to successfully running Windows containers on Amazon ECS, EKS, and AWS Fargate**

## What is this book about?

This book covers the following exciting features:
* Get acquainted with Windows container basics
* Run and manage Windows containers on Amazon ECS, EKS, and AWS Fargate
* Effectively monitor and centralize logs from Windows containers
* Properly maintain Windows hosts and keep container images up to date
* Manage ephemeral Windows hosts to reduce operational overhead
* Work with the container image cache to speed up the container’s boot time

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1804614130) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, ecs-ec2-windows.

The code will look like the following:
```
resource "aws_alb_listener" "ecs_alb_listener" {
 load_balancer_arn = aws_lb.ecs_alb.arn
 port = 80
 protocol = "HTTP"
 ```

**Following is what you need for this book:**
	This book is targeted towards DevOps engineer, SREs, solution architects, or a Windows sysadmin who wants to learn more about running Windows containers on AWS. In order to learn from this book, you should have a basic understanding of containers, Docker, and Kubernetes. The book is also beneficial for Windows application developers who want to explore how to achieve better application scalability using containers as a compute layer.

With the following software and hardware list you can run all code files present in the book (Chapter 1-15).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-15 | Terraform | Windows, Mac OS X, and Linux (Any) |


We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://packt.link/cgYuN).

### Related products
* Realize Enterprise Architecture with AWS and SAFe [[Packt]](https://www.packtpub.com/product/realize-enterprise-architecture-with-aws-and-safe/9781801812078?utm_source=github&utm_medium=repository&utm_campaign=9781801812078) [[Amazon]](https://www.amazon.com/dp/1801812071)

* A Developer's Essential Guide to Docker Compose [[Packt]](https://www.packtpub.com/product/a-developers-essential-guide-to-docker-compose/9781803234366?utm_source=github&utm_medium=repository&utm_campaign=9781803234366) [[Amazon]](https://www.amazon.com/dp/1803234369)

## Get to Know the Authors
**Marcio Morales**
is an expert on Microsoft stack technology with a broad technical breadth and deep understanding of Microsoft products. He combines more than 18 years of Microsoft technology experience as a consultant and technical instructor (Microsoft MCT). Nowadays, Marcio works as a Principal Specialist Solution Architect at AWS, helping customers to migrate, optimize and modernize Windows workloads on the AWS platform.
Marcio holds a bachelor degree in Network Computer, LAN/WAN Management and a master's degree in Network Architecture and Cloud Computing. In the certification world, Marcio holds more than 30 certifications from vendors such as Microsoft, AWS, Hashicorp, and Kubernetes.
