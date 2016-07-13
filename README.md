Email Invest 
API Ver: 2.00b
Last Updated: 12.07.2016

*****	ATTENTION	*****

API is currently in development status.

This is BETA version.


*****	INSTALATION	*****

***     Using GIT     ***

Download from GitHub files and iclude file 

"include 'LatestApi/Emailinvest.php';"


***     Using COMPOSER     ***

composer require emailinvest/emailinvest-api

Use Autoload: include 'vendor/autoload.php';



*****	DEFINE CLASS	*****


use api;

$ei = new api\emailinvest("YOUR_KEY", "YOUR_USERNAME", true);

$ei->Host = "app1.emailinvest.com/api";

$result = $ei->Me();
var_dump($result);


*****	FUNCTIONS	*****


Please, send recommendations to us so we can improve it.


***** Contacts Functions *****

contactsadd.php - Add contacts to your account


***** Fields Functions *****

fieldsgetlist.php - Get list with your fields

fieldsadd.php - Add new field to your account

fieldsdelete.php - Remove field from your account


***** Groups Functions *****

groupsadd.php - Add new group name to your account

groupsedit.php - Edit existing Group Name

groupsgetlist.php - Get all groups

groupsempty.php - Empty contacts from group and delete it if there not exists in other groups

groupsdelete.php - Delete group and delete contacts if there not exists in other groups


***** Campaigns Functions *****

fromsgetlist.php - Get your Frome emails

campaignsend.php - Send campaings from your account


