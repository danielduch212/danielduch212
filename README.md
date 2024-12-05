<h1>Daniel Duchnowicz</h1> 
<p><u> DevOps,.NET Developer </u> - interested in this technology since studying at the <u>Silesian University of Technology.</u></p>

In the past, I worked on desktop apps using WinForms and WPF - sample projects are down below.
Also, I build projects using <u>Blazor technology - both WASM and Blazor Server and WEBAPIs (ASP.NET Core)</u>
Currently I build DevOps slutions using Github Actions, Kubernetes and Terraform.

<h2> Cluster creation and managment (DevOps) </h2>
<h4> Technologies: AWS Cloud, Github Actions, Terraform, Kubernetes, Containers </h4>

In a nutshell - this projects shows creation of cluster which uses our projects (api, front) as containers in pods. To create infrastructure I use IaC solution - Terraform. What is more - when developers (frontend, api) create new version of app - those versions are deployed to Cluster - using Deployment (Elastic Kubernetes Service). Explicit details you can see in readme there: [main repository](https://github.com/danielduch212/MainClusterProject).

(cluster diagram soon)

<h2>Solution for frontend developers (DevOps, )</h3>
<h4>Technologies: GithubActions, AWS</h4>
Solution for frontend developers to test their changes by creating test environment (Api + Frontend) using cloud. This solution is based on two repositories and actions inside them.

[Backend repository](https://github.com/danielduch212/FrontendSolutionLogic1)
[Frontend repository](https://github.com/danielduch212/FrontendSolutionFront1)

You can see workflow diagrams inside those repositories. All in all - frontend developer after commiting changes - gets dynamically created URL to test app. (CloudFront)

Cloud Services used: 
  - AWS: CloudFront, S3, Lambda Asp .NET core, Api Gateway.

Diagram presents process in a nutshell (more details in those repositories):

![Blank diagram (3)](https://github.com/user-attachments/assets/ad1b3f08-acbc-446a-8879-a79c4502217d)



<h2>Patient Blazor Hybrid (WASM + Server) App</h2>

![photo](https://github.com/user-attachments/assets/abf23f67-e4bc-4dea-9c3d-dabc1d010788)

It is an app for patients who wants their health to be constantly supervised. More of how it works you can find in readme in repository (link below). It is made in clean code Pattern. Whole infrastructure is made using Azure Cloud Services (Sql base, Blob Storage, Insights, App Service).

<u>Repository: </u>
[Patient_Repository](https://github.com/danielduch212/Patient)


<h2>ASP.NET 8 API Car Repair Workshops</h2>
(More in the README of the project.)

![carRepairWorkshopsSwagger](https://github.com/user-attachments/assets/931bb093-8bd9-419b-98fb-c2020a8eb01d)

**It is an API for car repair workshops.**  

This API is written in ASP.NET 8 with Entity Framework to build the database and other useful packages. It is built using the Clean Code Pattern and CQRS. The application is adjusted to work with Azure Web Services + SQL Database. It uses Blob Storage and has functions to manage access to it. Basic CI/CD is used.


<u>And here is the direct link to the repository of this API: </u>
[CarRepairWorkshops Repository](https://github.com/danielduch212/CarRepairWorkshops)

<h2>DJ App 2023/2024 (C#) (WPF)</h2>
  
  The application is written in .NET using WPF for the GUI. Python is also used along with its Librosa library.  
  It mainly explores sound processing techniques and multithreading.  
  The application is written according to the MVVM pattern.
  
  ![screen2](https://github.com/danielduch212/danielduch212/assets/72360092/99f4fc95-b9b1-417a-9494-f748649bc349)  
  [DJ App](https://github.com/danielduch212/DjProgram)



