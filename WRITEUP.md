# Write-up Template

# Costs
## VM
Prizes can be seen [here](https://azure.microsoft.com/en-us/pricing/details/virtual-machines/linux/#pricing).

## App Service
Prizes starts from 0.00$ per month for lowest tier. All prizes can be seen [here](https://azure.microsoft.com/en-us/pricing/details/app-service/windows/).

# Scalability
## VM
VMs can be scaled up and down, e.g. by using [Virtual Machine Scale Sets](https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/overview).

## App Service
App Service provide auto-scaling, which can be configured to scale up and down based on different metrics, e.g. CPU usage, memory usage, etc. More information can be found [here](https://docs.microsoft.com/en-us/azure/app-service/manage-scale-up).

# Availability
## VM
VMs can be configured to be highly available by using [Availability Sets](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-availability-sets).
## App Service
App Service is highly available by default. More information can be found [here](https://docs.microsoft.com/en-us/azure/app-service/overview).

# Appropriate solution
## App Service
App Service is the appropriate solution for deploying the app. The app is a simple CMS app, which does not require any special configuration. App Service is easy to use and provides all the features needed for the app.

## App changes, that would change my decision
If the app require some special configuration, e.g. installing some software, then VM would be the appropriate solution. Furthermore, if I would have full control over the app environment or the OS, then VM would be the appropriate solution.