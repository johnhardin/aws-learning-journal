# AWS Learning Journal

This repo contains everything I've learned about AWS. After studying for the Solutions Architect Associate exam for years, I wanted to create a repository to document each AWS service. My explanations might be simple, but I will do my best to explain things clearly for someone new to cloud computing.

## Amazon Web Services (AWS)
AWS is a cloud service provider. Cloud services offer **on-demand** computing resources over the internet. Imagine you want to make your app public so that people can access it. If you host it on your own computer, it would need to run 24/7 for global access. This would put a heavy toll on your hardware, and if demand increases, your computer might lag or crash due to the processing load.

In this situation, you could buy a physical server, but that is expensive for a small team or app. Alternatively, you could rent a Virtual Private Server (VPS). However, VPS options still have limitations. What if you only want to test a system for a short time? While VPSs are affordable, they often require a minimum rental period (e.g., one month). Is that a waste of money and resources? Perhaps not, as they are cheap enough for monthly testing, but limitations remain: what if you need higher performance? What if you need multiple virtual servers? What if you only need them for a few hours?

That's where AWS and other cloud providers come in. You can easily create a virtual server with the lowest possible performance or a high-performance instance capable of heavy computing or Machine Learning. Whether for an enterprise or a personal project, it gets the job done. The best part is: **you only pay for what you use.**

I'll break down everything based on the main Catagories of Services and create folder and explanation for each services.

### Compute Services
AWS has many services categorized as Compute Services. These provide the processing power, memory, and networking needed to run applications in the cloud without maintaining physical hardware. 

One such service is Elastic Compute Cloud (EC2). It is similar to a VPS but with a far superior environment. We can adjust the compute units, memory, storage, networking, and security, and integrate it with other AWS services without needing to manually configure everything inside the virtual server. There is also a serverless compute option called Lambda, where you can execute code for a short duration while AWS handles all server maintenance, patching, and capacity provisioning.

These are the main Compute Services in AWS:
- Elastic Compute Cloud (EC2)
- AWS Lambda
- Elastic Container Service (ECS)
- Elastic Kubernetes Servics (EKS)

There are more Compute Services in AWS but this is the most you will hear about and I'll update more after I finish other catagories. 

**note: This repo is still on-going and apology if there some mistake cause I'm still learning about AWS**