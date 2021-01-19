# k8s
Scalable and distributed app and deploy in k8s

# Our experience :
When the newcomers start building their first websites, they don’t know about some problems they may run into later:

- An increase in the number of visitors reduces the performance of web applications
and blows up the failures;  
- expansion of the product range negatively affects the page load time; updating 
the inventory of an e-commerce shop becomes problematic;  
- changing the code structure becomes dangerous and overcomplicated; 
- adding a new product or service take too much time and becomes expensive, 
and the possibility of carrying out the A/B tests reduces.
- Computational limitation
- Storage limitations
- Network limitation
- Failures in server
- Deployment
- Supporting


As a result, we decided to rewrite all so that our system becomes scalable, maintainable and distributed.

Issues: 
- All about embedded is bad for scaling, embedded cache, embedded database, embedded workers(jobs) etc.
- Write code in modules which are independent of each other at code level.
- Try to divide app in micro services.
- Store assets in CDN.
- Use cloud storage to store dynamic assets and resources.
- Maintain only code on servers (No Assets, No Uploaded videos or images).
- Use containerization (This is the key to scaling).
- Make your code(app) platform independent.
- Put configuration variable in configuration files, don’t hard code.
- Don’t hard code anything.(Never Ever) (IP, Domain Names)
- Separate Project for Separate Purpose
- Use distributed database instead of central one.
- Learn Docker and Kubernetes or any other container orchestration.




# Resource for reading

https://cloud.google.com/solutions/scalable-and-resilient-apps

http://highscalability.com/blog/category/example
