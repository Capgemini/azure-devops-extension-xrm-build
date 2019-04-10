# Azure.DevOps.Extension.Xrm.Build

**Build Status**: ![Build Status](https://capgeminiuk.visualstudio.com/GitHub%20Support/_apis/build/status/CI-Builds/Azure%20DevOps%20Extensions/devops-xrmbuild-extensions-CI-Build?branchName=master)

**Release Status**: ![Release Status](https://capgeminiuk.vsrm.visualstudio.com/_apis/public/Release/badge/d743f9d4-7dae-476e-a963-f038f994a35d/1/3)

## Description

The Azure.DevOps.Extension.Xrm.Build extension provides tasks for use in Azure DevOps build pipelines. These tasks enable a Continuous Integration pipeline to be created for Dynamics 365. For tasks for a release pipeline, please see [Azure.DevOps.Extension.Xrm.Release](https://github.com/Capgemini/azure-devops-extension-xrm-release).

**Tasks:**

* Dynamics 365: Combine Static and Templated PackageDeployer Artefacts
* Dynamics 365: Update solution.xml Version to Build Number
* Dynamics 365: Update Unmanaged Solution Version

## Table of Contents

* [Description](#Description)  
* [Installation](#Installation)
* [Usage](#Usage)
* [Contributing](#Contributing)
* [Credits](#Credits)
* [License](#License)

## Installation

Navigate to and install [the extension](https://marketplace.visualstudio.com/items?itemName=capgemini-msft-uk.capgemini-xrm-build-extension) through the Visual Studio Marketplace for your Azure DevOps instance.

## Usage

After installing, navigate to a new or existing Azure DevOps build pipeline, from there the following tasks should be available to be added and configured.

Below is a summary of each task, click on the task name to view more information on [the wiki](https://github.com/Capgemini/azure-devops-extension-xrm-build/wiki).

### [Dynamics 365: Combine Static and Templated PackageDeployer Artefacts](https://github.com/Capgemini/azure-devops-extension-xrm-build/wiki/Usage#Dynamics-365-Combine-Static-and-Templated-PackageDeployer-Artefacts)

Combines the static files provided by Microsoft with templated files to generate a releasable Package Deployer artefact. PackageDeployer provides a repeatable way of releasing Dynamics 365 solutions and release artefacts, that is provided through the Dynamics 365 SDK.

### [Dynamics 365: Update solution.xml Version to Build Number](https://github.com/Capgemini/azure-devops-extension-xrm-build/wiki/Usage#Dynamics-365-Update-solutionxml-Version-to-Build-Number)

Task that can update the version number stored in the solution.xml file for extracted Dynamics solutions.

### [Dynamics 365: Update Unmanaged Solution Version](https://github.com/Capgemini/azure-devops-extension-xrm-build/wiki/Usage#Dynamics-365-Update-Unmanaged-Solution-Version)

Task that connects to a Dynamics 365 instance and updates the Version Number of a Solution.

## Contributing

Source Code will be made available shortly. All contributions will be appreciated. 

To contact us, please email [nuget.uk@capgemini.com](mailto:nuget.uk@capgemini.com).

## Credits

Capgemini UK Microsoft Team

These tasks use the excellent [Microsoft.Xrm.Data.Powershell](https://github.com/seanmcne/Microsoft.Xrm.Data.PowerShell), by [seanmcne](https://github.com/seanmcne).

## License

[MIT](https://github.com/Capgemini/azure-devops-extension-xrm-build/blob/master/LICENSE)