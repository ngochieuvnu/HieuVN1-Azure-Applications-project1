# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

- App Service is cheaper than VM. App service is easier to install than VM (App service is a Paas, VM is a Iaas)
  The development of app is much simpler and faster in Azure App Service.
- My choice: App service because CMS app is a lightweight application, I don't need a powerful service. If I choice VM, i need install a few 
application to deploy my CMS app (ex: python,etc), while that App service support continous deployment through GitHub workflows 
that makes updating the CMS app quickly.
### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

App Service: If the application become more bigger and more complex that would require more hardware, the costs could increase quickly,
and it is difficult to deploy a complex feature.

Virtual Machine: If the application become more bigger, Developer need require more harware that can make cost become more expensive.
                and Managing Vm is very complicated