<h1>Daniel Duchnowicz</h1> 
<p><u> DevOps,.NET Developer </u> - interested in this technology since studying at the <u>Silesian University of Technology.</u></p>

In the past, I worked on desktop apps using WinForms and WPF - sample projects are down below.
Also, I build projects using <u>Blazor technology - both WASM and Blazor Server and WEBAPIs (ASP.NET Core)</u>
Currently I build DevOps slutions using Github Actions, Kubernetes and Terraform.

<h2>Solution for frontend developers (DevOps, GithubActions, AWS)</h3>

I create solution for developers when there is a problem with multiple environments.
This solution makes it easy for frontend developers to test changes they did and commited to repository by creating test environment in cloud.
This solution is based on two repositories and actions inside them.

[Backend repository](https://github.com/danielduch212/FrontendSolutionLogic1)
[Frontend repository](https://github.com/danielduch212/FrontendSolutionFront1)

So the point is - backend developers upload backend (api) with commiting changes and then github action is working.
Github action uploads building artfiacts to amazon S3.  [backend action file](https://github.com/danielduch212/FrontendSolutionLogic1/actions/runs/11824905181/workflow)

Frontend developers change their repository and by commiting changes they are allowed to have dynamic test environment which is generated in AWS Cloud - let's get into this action:
[frontend action file](https://github.com/danielduch212/FrontendSolutionFront1/actions/runs/11856652569/workflow)

- So first frontend is built after testing and artifacts after build are also pushed to S3 bucket in hashed folder - based on commit. (build job)
- In Deploy segment - Backend from S3 is downloaded and pipeline creates Lambda Aspnetcore - based on backend - and bacause lambda is serverless - pipeline creates also Api Gateway which will listen for requests for api - and if it gets one - it invokes lambda.
- Bacause of that - after pipeline is finished - programmer gets URL to CloudFront app - where it is possible to test their code.


<h2>Patient Blazor Hybrid (WASM + Server) App</h2>
(Currently working on)

![photo](https://github.com/user-attachments/assets/abf23f67-e4bc-4dea-9c3d-dabc1d010788)

It is an app for patients who wants their health to be constantly supervised. More of how it works you can find in readme in repository (link below). It is made in clean code Pattern. Whole infrastructure is made using Azure Cloud Services (Sql base, Blob Storage, Insights, App Service.


<u>You can watch this app working here: </u>

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



