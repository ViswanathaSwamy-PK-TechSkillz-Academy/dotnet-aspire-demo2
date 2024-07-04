# dotnet-aspire-demo2

I am learning .NET 8 Aspire from different Video Courses, Books, and Websites.

## Features

Default Sample
Bicep Template
Subscription level deployments

## Few Commands

```powershell
D:\TSA\dotnet-aspire-demo2\AspireDemo2\AspireDemo2.AppHost> azd init

#Places the file in the root folder.
dotnet run --project .\AspireDemo2.AppHost\AspireDemo2.AppHost.csproj --publisher manifest --output-path ../aspire-manifest.json

D:\TSA\dotnet-aspire-demo2\AspireDemo2\AspireDemo2.AppHost> azd config set alpha.infraSynth on
D:\TSA\dotnet-aspire-demo2\AspireDemo2\AspireDemo2.AppHost> azd infra synth

azd auth login --scope https://management.azure.com//.default

azd config set alpha.resourceGroupDeployments on

azd up
```
