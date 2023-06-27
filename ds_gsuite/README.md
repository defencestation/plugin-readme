### G Suite Plugin

This plugin allows you to integrate with G Suite services using the Admin SDK API. In order to configure the plugin, you will need to enable the Admin SDK API, obtain the necessary credentials, and provide additional information. Follow the steps below to get started:

#### Enabling the Admin SDK API

1. Go to the Google Cloud Console.
2. If you don't have a project, create a new project. Otherwise, select the existing project you want to use with this plugin.
3. In the Cloud Console, navigate to the APIs & Services > Library page.
4. Search for "Admin SDK" and select the Admin SDK API from the results.
5. Click on the Enable button to enable the Admin SDK API for your project.

#### Obtaining Credentials and Required Information

To access G Suite services, you will need to obtain the following credentials and information:
Service Account Credentials (JSON)

1. In the Cloud Console, navigate to the APIs & Services > Credentials page.
2. Click on the Create Credentials button and select Service Account.
3. Provide a name and optional description for your service account.
4. Click Create to proceed.
5. On the Service Account details page, click on the Add Key button and select JSON.
6. Save the downloaded JSON file securely. This file contains your service account's credentials.

#### Customer ID and Admin Email

1. Open the Google Admin Console using your G Suite administrator account.
2. In the Admin Console, go to Admin roles > Super Admin or Privileged role (depending on your setup).
3. Scroll down to the Admin SDK section and find the Customer ID and Admin Email information.
4. Make a note of these values as you will need them during the configuration.

#### Configuring the Plugin

Once you have obtained the necessary credentials and information, follow these steps to configure the plugin:

1. Go to [Configure](https://app.defencestation.ca/asset-intelligence/configure/GSuite/defensestation).
2. Under Credentials, fill in the required fields.
3. Then you can review the options to see, which kind of data you want to be loaded, Select from:
    - get_users
    - get_groups
    - get_orgunits
    - get_domains
    - get_devices
    - get_buildings
4. Click on Configure.

That's it! You have successfully configured the G Suite plugin using the necessary credentials and information. Enjoy integrating G Suite services into your application!

#### License

This project is licensed under the MIT License.

Feel free to modify and customize the plugin to suit your needs. Contributions and bug reports are welcome.

`DefenseStation`