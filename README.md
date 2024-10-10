# M365 Admin Assist Script

## Overview

M365 Admin Assist Script is a PowerShell script designed to help Microsoft 365 administrators streamline common administrative tasks. This tool automates various processes, improving efficiency and ensuring consistent management of Microsoft 365 environments.

## Features

- **User Management**: Easily create, update, or remove user accounts.
- **Group Management**: Automate the creation and management of groups.
- **License Management**: Assign and remove licenses in bulk.
- **Reporting**: Generate reports on users, groups, and licenses.
- **Audit Logs**: Access and analyze audit logs for compliance.

## Prerequisites

- Microsoft 365 Administrator account
- PowerShell 5.1 or higher
- Required modules:
  - AzureAD
  - ExchangeOnlineManagement
  - Microsoft.Graph

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/techjollof/M365AdminAssistScript.git
   ```

2. Navigate to the project directory:
   ```bash
   cd M365AdminAssistScript
   ```

3. Install the required PowerShell modules:
   ```bash
   Install-Module AzureAD -Force
   Install-Module MSOnline -Force
   ```

## Usage

1. Open PowerShell as an administrator.
3. run any of the script by:
   ```powershell
   .\M365AdminAssistScript.ps1 -Prameter1 Member -Parameter2 Manager
   ```
## Function Help
Help documents are included in each of the script file. To access the help information

```powershell
Get-Help Invoke-GroupMessageTrace.ps1
```

To see the examples, type: `Get-Help Invoke-GroupMessageTrace -Examples`
For more information, type: `Get-Help Invoke-GroupMessageTrace -Detailed`
For technical information, type: `Get-Help Invoke-GroupMessageTrace -Full`
    
## Available Tasks
- Getting Unsed groups | **Invoke-GroupMessageTrace.ps1**

## Coming Soon
- **CreateUser**
- **RemoveUser**
- **UpdateUser**
- **CreateGroup**
- **RemoveGroup**
- **AssignLicense**
- **RemoveLicense**
- **GenerateReport**



For detailed usage instructions for each task, please refer to the comments within the script or the wiki section of the repository.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeature
   ```

3. Make your changes and commit them:
   ```bash
   git commit -m "Add your feature"
   ```

4. Push to the branch:
   ```bash
   git push origin feature/YourFeature
   ```

5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- [Microsoft Documentation](https://docs.microsoft.com/en-us/microsoft-365/admin/admin-overview/admin-overview?view=o365-worldwide) for providing comprehensive resources on Microsoft 365 administration.
- The open-source community for contributing to PowerShell development.

## Contact

For questions or support, please open an issue on this repository techjollof@gmail.com
