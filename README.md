# BitMan
Free and open-source Proxmox VE API VM management service. Full control panel for VM hosting solutions including automated VM creation, payment plan's via stripe API, and administration portal with pretty graphs.

## Why
Because fuck big corporations

### DKWTCT (Don't know what to call this)
ASP.NET Core MVC/Web API application writen in .NET 5, all documented using Swagger. Built with Identity Server4 and Microsoft Identity to manage credentials and user data. Easily migrateable to these (database providers)[https://docs.microsoft.com/en-us/ef/core/providers/] with the help of Entity Framework Core.

## Todo

1. Payment portal integration with Stripe. 
2. Auto VM creation based on selected user settings.
3. Full Vm Control on Proxmox cluster (Dynamically increase RAM, Core's, Recovery mode and password management, Etc...)
4. Administration portal for canceled subscriptions.
5. Auto assigning IP's to VM via Ubiquity/VM Host and limiting bandwith.
6. Pretty Graph's and email's sent to users for data usage. 
7. Basic Ticketing. 
