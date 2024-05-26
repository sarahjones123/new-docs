# Installing GENESYS by Vitech

!!! note "Note"

    This is a sample installation page. Use this for reference only. Retrieved from Chatbot.

[Twemoji]: https://twemoji.twitter.com/
[emoji search]: ../reference/icons-emojis.md#search

## Prerequisites

Before installing GENESYS, ensure your system meets the following requirements:

- **Operating System:** Windows 10 or higher
- **Processor:** 2 GHz or faster
- **RAM:** 4 GB or more
- **Disk Space:** At least 1 GB of free space
- **.NET Framework:** Version 4.6 or higher
- **Database:** Microsoft SQL Server 2012 or higher (SQL Server Express is sufficient for most users)

## Step-by-Step Installation Guide

### Step 1: Download GENESYS

1. Visit the [Vitech GENESYS download page](https://www.vitechcorp.com/genesys/download).
2. Log in with your Vitech account credentials.
3. Download the latest version of GENESYS.

### Step 2: Install Microsoft SQL Server (if not already installed)

1. Download Microsoft SQL Server Express from the [official Microsoft website](https://www.microsoft.com/en-us/sql-server/sql-server-editions-express).
2. Run the installer and follow the on-screen instructions to complete the installation.
3. Configure the SQL Server with a new instance named `GENESYS`.

### Step 3: Install GENESYS

1. Locate the downloaded GENESYS installer file and run it.
2. Follow the installation wizard steps:
   - Accept the license agreement.
   - Choose the installation directory (default is recommended).
   - Select the SQL Server instance created earlier.
3. Click **Install** to begin the installation process.

### Step 4: Configure GENESYS

1. Once the installation is complete, launch GENESYS.
2. The first time you run GENESYS, you will need to configure the database connection:
   - Open the Database Configuration tool from the start menu or GENESYS interface.
   - Enter the SQL Server instance name and authentication details.
   - Test the connection to ensure it is working properly.
3. If the test is successful, save the configuration.

### Step 5: Activate License

1. Launch GENESYS.
2. When prompted, enter your license key. This can be found in the email received from Vitech or your Vitech account.
3. Follow the on-screen instructions to activate your license.

### Step 6: Verify Installation

1. Open GENESYS and ensure it starts without errors.
2. Create a new project to verify that the software is functioning correctly.

## Troubleshooting

- If you encounter issues during installation, consult the [GENESYS Installation Guide](https://www.vitechcorp.com/genesys/installation-guide) for detailed troubleshooting steps.
- For database connection issues, ensure that SQL Server is running and accessible.
- Contact Vitech Support for assistance with license activation or other technical problems.

## Additional Resources

- [GENESYS User Guide](https://www.vitechcorp.com/genesys/user-guide)
- [Vitech Community Forums](https://community.vitechcorp.com/)
- [Technical Support](https://www.vitechcorp.com/support)

