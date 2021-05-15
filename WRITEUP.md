
### Analyze, choose, and justify the appropriate resource option for deploying the app.

*Virtual Machine Solution:*

*  Costs: It is expensive and can be more consuming comparing it to App Service
    specially for developer 

 *  Scalability : The VM solution has a capability to be changed in size and in scale with varying amounts of CPU, RAM 
    and storage and grouping some VMs together.

*  Availability: The fact that many VMs could be grouped , it  raises its availability 

*  workflow : The VM let you create a customized workflow for automation .For  example, it is possible to configure
   a workflow to add automatically new virtual machines to an external domain after it is created. 


*App Service Solution:*

*  Costs: The cost varies according to the plan used and there are free options to use within Dev/Test Tiers.
    You must always pay for the plan also when it is not running.

*  Scalability : It is possible to change the  amount of vCPUs or RAM or the number of virtual machine
    of course with varying the price.But there are some limitations like the maximum of 14GB of memory 
    and 4 vCPU cores per instance.

*  Availability:It has a high availability 

*  workflow :It is possible to deploy to Azure App Service using workflows ,that define how to build,
   test, and deploy .


*Chosen Solution for deploying the CMS app: App Service:*
Our use case is a web app with basic functionalities, and I don't need any control for the operating System and 
any high performance : That's why I will choose the App Service Solution to deploy the app.



### Assess app changes that would change your decision.

*If the current app will be used for example in an enterprise with more complex functionalities and more users 
and if a high performance is needed or if I need to have full control over my computing environment
,it will be better to deploy it on VM* 