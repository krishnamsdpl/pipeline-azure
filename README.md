# pipeline-azure

Build, test, and deploy .NET Core apps

Sign in to your Azure DevOps organization and navigate to your project.

Go to Pipelines, and then select New Pipeline.

Walk through the steps of the wizard by first selecting GitHub as the location of your source code.

You might be redirected to GitHub to sign in. If so, enter your GitHub credentials.

When the list of repositories appears, select your repository.

You might be redirected to GitHub to install the Azure Pipelines app. If so, select Approve & install.

When the Configure tab appears, select ASP.NET Core.

When your new pipeline appears, take a look at the YAML to see what it does. When you're ready, select Save and run.


Build environment:
Use Azure Pipelines to build your .NET Core projects. Build your projects on Windows, Linux, or macOS without the need to set up infrastructure. The Microsoft-hosted agents in Azure Pipelines include several preinstalled versions of the .NET Core SDKs.




