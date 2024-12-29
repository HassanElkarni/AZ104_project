# Azure CLI Project

This project is designed to facilitate the deployment of a web application on Azure using Azure App Service. It includes a shell script that automates the creation of necessary Azure resources, ensuring a streamlined setup process.

## Project Structure

- **src/create-resources.sh**: A shell script that utilizes Azure CLI commands to create essential Azure resources such as an App Service and a Resource Group.
- **src/types/index.ts**: This file exports types or interfaces for maintaining type safety and clarity throughout the project.
- **tsconfig.json**: Configuration file for TypeScript, specifying compiler options and files to include in the compilation.
- **package.json**: Configuration file for npm, listing dependencies, scripts, and project metadata.

## Prerequisites

Before running the project, ensure you have the following installed:

- Azure CLI: [Install Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)
- Node.js and npm: [Download Node.js](https://nodejs.org/)
- TypeScript: Install globally using npm:
  ```
  npm install -g typescript
  ```

## Usage

1. **Clone the repository**:
   ```
   git clone https://github.com/microsoft/vscode-remote-try-dab.git
   cd azure-cli-project
   ```

2. **Run the create-resources.sh script**:
   Make sure you are logged into your Azure account:
   ```
   az login
   ```
   Then execute the script:
   ```
   chmod +x src/create-resources.sh
   ./src/create-resources.sh
   ```

This script will create the necessary Azure resources for hosting your application. Follow the prompts and instructions provided by the script.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.