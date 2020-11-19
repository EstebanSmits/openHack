# openHack
Development Environment Configuration
Please ensure your machine conforms to these prerequisites.

A modern laptop running Windows 10, Mac OSX 10.12 or higher, or one of these Ubuntu versions

Your preferred IDE (integrated development environments), like Visual Studio Code or Visual Studio:
If using Visual Studio for Windows, make sure you have the latest Visual Studio 2019 with the Azure development workload selected, and the most recent version of the Azure Functions and Web Jobs Tools extension

If using Visual Studio Code in Windows, OSX, or Linux make sure you have the latest Visual Studio Code version for your OS, and

VSCode Azure Functions extension

Azure Functions Core Tools version 3x

Language specific prerequisites
Depending on the language your team uses, there are additional prerequisites that your machine will need to have. Please review these language specific prerequisites to ensure your machine is ready for the open hack.

C# .NET Core
Either Visual Studio 2019
or

Visual Studio Code on one of the supported platforms.

Use of the Visual Studio Code C# Extension is recommended.

Azure Functions Core Tools version 3x

.Net 5.0 has not been validated for these OpenHack challenges. Please use .NET Core 3.1. Refer to supported languages to determine when .Net Core 5.0 is no longer in preview state.

Java/Maven
Java Developer Kit version 8
Apache Maven version 3.0 or later
Azure CLI
Azure Functions Core Tools version 3.x
Refer to Azure Functions Java Developer guide for latest version support information

JavaScript
Visual Studio Code on one of the supported platforms
Azure Functions Core Tools version 3x
Node.js Active LTS and Maintenance LTS versions (8.11.1 and 10.14.1 recommended)
Refer to Azure Function Supported Languages for further Node supported version information

Python
Previous Versions
If you have 3.6.x or 3.7.x you should have no issues with those versions, just be certain to select the correct version when creating your function apps at Azure.

Use a VM instead of multiple versions
It is recommended you do not do a side-by-side installation of a new python version for this challenge. To be clean and avoid potential issues, consider using a low-cost VM running on linux at Azure and install the latest python tools there.

Use VSCode with the Azure Functions Extension
It is very easy to work with VSCode with python functions at Azure. Although you may be new to VSCode, it is recommended due to the high availability of extensions that can easily run (locally) and publish Azure functions to your integrated Azure subscription.

Python 3.8.x

Using VSCode with Azure Functions extension makes it easy to select the compiler. language, and project and integrate directly to your function app at Azure, including deployment.

VS Code users on Windows, in the past, python interpreter selection can be troublesome. Review Python in VS Code environments for assistance with this if you run into issues.

VSCode

VSCode Azure Functions extension

Azure Functions Core Tools version 3x. You need this to run/test locally.

Azure CLI

Recommended for Mac OSX and Linux users to install Azurite v2

VSCode Azure Storage extension
