#HybridIgniter2

Updated version of [HybridIgniter](https://github.com/andacata/HybridIgniter/):
a simple [HybridAuth](http://hybridauth.sourceforge.net/) - [CodeIgniter](http://ellislab.com/codeigniter) integration.

##Changes 
- Updated HybridAuth from version 2.1.2 to 2.4.0
- Updated CodeIgniter from version 2.1.3 to 2.2.1
- Fixed some errors in the example code

##Installation
1. Drop the provided files into the CodeIgniter project
2. Configure the providers inside the application/config/hybridauthlib.php file
3. Modify the controller example supplied (application/controller/hauth.php) to fit your needs

##How to use
The only thing you need is to put as many links as you need pointing to "http://&lt;yourdomain>/index.php/hauth/login/&lt;provider>", ex.:

	<a href="http://www.example.com/index.php/hauth/login/Twitter">Log in with Twitter</a><br />
	<a href="http://www.example.com/index.php/hauth/login/Facebook">Log in with Facebook</a><br />
	<a href="http://www.example.com/index.php/hauth/login/LinkedIn">Log in with LinkedIn</a>

