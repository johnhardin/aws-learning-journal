# AWS Learning Journal

This repo is everything I know about AWS. after learning for Solution Architecture Associate Exam for years, I want to create a repo where i documented each of services on AWS. Maybe my explanation is bad but i will try my best to explain things for someone who new in cloud computing.

## Amazon Web Services (AWS)
AWS is a cloud service providers. Cloud service itself offer **on-demand** computing resources over the internet. Imagine you need to put your apps into public so that people can access it. you put it on your own computer but it needs to run 24 hours so that people across the globe can access your app anytime. it will took a tol on your own computer and when the demand on your app is high, you problably cannot use your computer because the lag of processing everything from other who access your app.

In this situation you can buy an actual physical server which is expensive if you only have small team/app or you can just rent Virtual Private Server (VPS) and put your app on this. but there is always limitation on VPS. what if you only want to test the system for a short time? VPS is cheap but you can only rent it with minimum of 1 month. Is it waste of money and resource? of course not, its really cheap that you can basically use it for a month to test everything your app needs. but there is always limitation on VPS, what if you need a higher performance? what if you need a more than 1 virtual server? what if you only need to use it for a couple hour?

Thats where AWS or any cloud provider comes in. you can easily create a virtual server with the lowest performance the cloud service can provide or you can get a virtual server that capable of high performance computing or even for Machine Learning. Looks a bit excessive but it gets the job done whatever you need, from an enterprise to a personal project. the good thing is  **you only pay for what you use.**

I'll break down everything based on the main Catagories of Services and create folder and explanation for each services.

### Compute Services
AWS have tons of services with some of them catagories as Compute Services. It provide processing power, memory, and networking needed to run application in the cloud without maintaining physical hardware. One of the services is Elastic Compute Cloud (EC2). I can say its almost the same as VPS with a far more better environment. We can adjust everything from compute unit, memory, storage, networking, security, and integrate it with other AWS services without the need of touching anything inside the virtual server itself. There is also serverless compute called Lambda, where you can execute a code for a short time with AWS handle all server maintenance, patching, and capacity provisioning.

You can get explanation for each services inside the compute servies folder.


**note: This repo is still on-going and you can comment if there is something wrong with my explanation**