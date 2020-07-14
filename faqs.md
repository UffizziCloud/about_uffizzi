# FAQs
Below is a partial list of frequently asked questions. For a full list visit https://uffizzi.cloud. 

### Why would I use Uffizzi?
Because you need one less thing to worry about. You'd choose Uffizzi to host your app for the same reason you'd use TurboTax to do your taxes. You could study tax law and do it yourself or trust a pricey accountant to do it for you. But many people turn to a simple, automated and trusted platform that handles everything for them at a reasonable price. Uffizzi is like TurboTax for the cloud.

### How is Uffizzi different than Heroku?
Uffizzi is easier to use while being about 30% cheaper than Heroku on average. Uffizzi is also more modern — leveraging sophisticated tools like Kubernetes — which improve efficiency and allow us to keep our costs lower. This let's us pass those savings on to you.

### What are the pre-requisites to be successful on Uffizzi?
You need a containerized application on Docker Hub (GitHub integration is coming Fall 2020). That's it. If you're not familiar with Docker, it's by far the most popular container platform and has become the de facto standard for packaging applications to run in the cloud. It's a fairly short learning curve that will make the rest of your life much easier when it comes to operations, even if you choose another cloud provider.

### How does Uffizzi work?
From Uffizzi's intuitive web console, import your app from Docker Hub (Github integration coming Fall 2020), and provide port number and environment variables as required by your app. Uffizzi will then provision, deploy, connect and secure your application in a professional cloud environment. Uffizzi also offers fully managed versions of the most popular relational databases — MySQL and Postgres — which include automated backups and failover redundancy options. For business-critical apps and data, Uffizzi recommends our Enterprise option that automatically replicates your app across separate data centers to ensure it's highly available for your users. You won't see these kinds of enterprise features on platforms like Heroku.

### What data storage options does Uffizzi offer?
Currently, Uffizzi offers fully managed MySQL and Postgres databases with high availability, auto-scaling storage and automated backups (See [Database Service offerings](https://uffizzi.cloud/dataservices/). Windows SQL Server and Object Storage are coming Fall 2020.

### Is Uffizzi secure?
We take security very seriously and go to paranoid lengths to keep your applications and data safe. Uffizzi works hard to ensure that the infrastructure supporting your applications and data are as secure as possible. To that end, we utilize the same best practices and industry standards as other major cloud providers, including ISO/IEC, SOC, and HIPAA compliant infrastructure. Applications run inside Kubernetes clusters with network, namespace and kernel-level isolation, and database access is restricted to applications within your private, virtual cloud environment. In addition to these security mechanisms at the infrastructure layer, we strongly suggest that you perform code reviews and security audits of your codebase to prevent data breaches at the application layer.

### What is the underlying infrastructure supporting Uffizzi?
Uffizzi leverages Google Cloud Platform (GCP) and Google's global network of world-class data centers. Uffizzi automates complex cloud configurations to deliver reliable, scalable and secure infrastructure with the push of a button. Built atop Kubernetes, Uffizzi let's you leverage the power of the popular orchestrator without ever touching it. Frontend, backend, microservices, multi-container apps, databases, SSL certificates, load-balancing, networking . . . Uffizzi handles it all.

### What languages do you support?
Anything that runs on Linux, including Javascript, Python, C# (via .NET Core), PHP, Ruby, Go, Java, Scala, Clojure and more.

### How much does it cost?
See [Uffizzi App Platform](https://uffizzi.cloud/pricing/) and [Database Service pricing](https://uffizzi.cloud/dataservices/).
