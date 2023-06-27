### AWS Plugin

This plugin allows you to interact with AWS services using the AWS SDK. In order to configure the plugin, you will need to create a new IAM user with the necessary permissions and obtain the access key and secret key for that user. Follow the steps below to get started:

#### Creating an IAM User

To securely interact with AWS services, it is recommended to create a dedicated IAM user specifically for this plugin. Follow these steps to create a new IAM user with the required permissions:

1. Log in to the AWS Management Console.
2. Navigate to the IAM service.
3. In the IAM dashboard, click on Users and then Add user.
4. Provide a unique name for your user (e.g., plugin-user).
5. Select Programmatic access as the Access type.
6. Choose Attach existing policies directly and search for the policies you need to grant to this user (e.g., AmazonS3FullAccess, AmazonEC2ReadOnlyAccess, etc.).
7. Review the permissions and click Next.
8. Skip the Tags section (optional) and click Next.
9. Review the user details and click Create user.
10. On the Complete page, make note of the Access key ID and Secret access key. You will need these to configure the plugin.

#### Configuring the Plugin

1. Go to [Configure](https://app.defencestation.ca/asset-intelligence/configure/AWS/defensestation).
2. Under Credentials, fill in the required fields.
3. Then you can review the options to see, which kind of data you want to be loaded, Select from:
    - get_all
4. Click on Configure.

That's it! You have successfully configured the AWS plugin using the IAM user's access key and secret key. Enjoy integrating AWS services into your application!
License

This project is licensed under the MIT License.

Feel free to modify and customize the plugin to suit your needs. Contributions and bug reports are welcome.