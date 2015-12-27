#Social-Codeigniter

Updated version of [HybridIgniter](https://github.com/andacata/HybridIgniter/):
a simple [HybridAuth](http://hybridauth.sourceforge.net/) - [CodeIgniter](http://ellislab.com/codeigniter) integration. This repository includes Social-Codeigniter for CodeIgniter 2.2.1 and 3.0.1 for usage.

The main goal is to act as an abstract API between your application and various social apis and identities providers such as Facebook, Twitter and Google.

##Changes 
- Updated for Codeigniter 3.0.1
- Updated for CodeIgniter 2.2.1
- Updated HybridAuth to 2.4.0
- Fixed some errors in the example code

##To-Do
- Add users to database
- Allow users to change their profile information
- Multiple Login methods for the same account in order to minimize redundant logins and improve user experience


##Installation
1. Select the folder Social-CodeIgniter 2.2.1 or 3.0.1 as needed
2. Drop the provided files into the CodeIgniter project
3. Configure the providers inside the application/config/hybridauthlib.php file
4. Check Hauth.php controller's index() function for configuring your view

##How to use
Check out the example views and controller and configure it to fit your needs.

