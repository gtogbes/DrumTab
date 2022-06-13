# DrumTab
This project,  is a drum machine. A tab with drum components,  such as the kick, high hats, snare etc.
The project has accompanied sounds to match the drum part. 
This project will focus on CICD deployment of webapp using AWS amplify, this can also be achieved using  S3 and content Delivery network; Cloudfront. 
This project can be hosted on github pages. 

AWS Amplify offers a fully managed CI/CD and hosting service that gives developers a zero-config way to deploy their single page (SPA) or server-rendered (SSR) frontend apps on AWS by simply connecting their Git repository. Amplify automatically builds, deploys and hosts the web app globally on a CDN powered by Amazon CloudFront.
Requirements: AWS account
To get started, clone or fork this repo,
On the AWS console, search for Amplify
Navigate to AMplify console and select Host a web app
You will be asked to connect your GitHub account. Once connected, Amplify will fork the selected repository in your account and ask you to confirm deployment.
after deployment, a Url will be generated for you to access your webapp
Finally to add your custom domain;
On the Amplify console, select app settings, 
select domain management and choose the hosted zone to use. 
Amplify will automatically provision ssl certificate for the domain name or subdomain specified. 
this solution, provides a highly available webapp that scales without lagging when traffic is high.
It has CDN under the hood by employing cloudfront.
It automatically updates changes made to your code base with the CICD features.

