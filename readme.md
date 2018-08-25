[![Build Status](https://travis-ci.org/BaffourAdu/ComplainDesk.svg?branch=master)](https://travis-ci.org/BaffourAdu/ComplainDesk)

About Complain Desk
--------------------------------------------
Ever tried complaining to your Institution or a Service Provider about a nagging issue you are facing? To solve most of these problems, requires the complainant to lodge a complain and follow up on it, if he truly wants it to be resolved.This is where the problem lies. Apart from human error, the person complainted to forgetting  or the individual being flooded with the same issues which someone has complained about, resolving problems and issues could be a tiring and frustrating job. Not to mention, that dark and gloomy period of isolation, where you have no idea as to the progress that has been made towards getting your issue reolved. 

A large population or customer base of the service could easily overload the individual being complained to. The distance between the complainant’s location and the office of the Institution or Service Provider, i.e, the  great fixer, and the daunting task to ensure it has been resolved and it has not been tossed aside,  hinders a smooth Customer experience and the Institutions ability to effectively tackle its problems.

Complain Desk seeks to reslove this,  by offering a web application to tackle the problem of Customers or Users complaints management in a simple but efficient way.

The goal is to easily place in the hands of customers or users a simple interface in order to make complaints to the right authorities easier and efficiently. It also provides the opportunity to scan through earlier resolved issues or pending issues, this would prevent the institutions or organizations from being notified of the same issue several times. While allowing to track the status of complaints made and alerting the complainants when it is resolved or alerting the institution when it has been ignored. 

On the institution or organizational side of things, this application prevents the institution from being overloaded with different complaints in a day and having no way to put a track on all of them. This allows for the appropriate individual to be alerted, reminded, ask for progress report on behalf of the complainant and inform the complainant as soon as these has been resolved. More importantly allowing for  institutions to make improvement to their institution in areas where it is flawed.


Complain Desk provides a clean user interface using the Laravel framework which allows for a simple and classic design which users can easily understand. While also utilizing the simple power of SMS and email notifications in order to keep its users informed in relation to progress towards resolving their complaints. 

ComplainDesk in no way makes this assertion that there are not other means to make a complain. Either by virtue of a suggestion box, walking to the office of the appropriate individual, spamming the life out of the service provider with calls, or it may be just by sending an email to the appropriate authority. But we the authors being part of institutions, and having a first hand experience on how devastating these problems could be,  strongly hold the view that this method of making a complain is what is wrong with the complain system.  Especially for  large institutions or organizations, a simple enquiry or complain could be extremely frustrating , unnecessarily long and tedious 

This application is what we believe to be among the things missing in our various Institutions and Organizations in Ghana which would attempt to fix the problem and  benefit both the Customers or Users and the institution.


Features
---------------------------------------------
* Simple UI
* Bootstrap 4
* Local Authentication using Email/Telephone and Password
* Open tickets
* Admin can close a ticket
* User and Admin can comment on a ticket
* A list of User's Ticket's on Dashboard
* Complain Status and Duration Tracking
* Add multiple Admins to manage complains
* Audit Logs to track activities of Admins
* Ability to Categorize Complains
* Email and SMS Notification
* Forgot Password
* Account Management
* CSRF Protection
* Easily Generate Report on Complains (Coming Soon)
* A Knowledge base for already resolved issues to prevent same issue from been reported multiple times


Authors
----------------------------------------------
* Baffour Adu Boampong
* Roberta Akoto
* Robert Yin
* Saliha Hotamisli


Complain Desk Development Contribution
----------------------------------------------
Thank you for considering contribute. You may propose new features or improvements of existing ones by submiting Pull Requests or sending an email to baffouraduboampong@gmail.com. Issues can also be submitted to as via our platform => https://complaindesk.herokuapp.com 


Pull Requests
----------------------------------------------
PSR-2 Coding Standard - The easiest way to apply the conventions is to install PHP Code Sniffer.

Add tests! - Your patch won't be accepted if it doesn't have tests.

Document any change in behaviour - Make sure the README.md and any other relevant documentation are kept up-to-date.

Create feature branches - Don't ask us to pull from your master branch.

One pull request per feature - If you want to do more than one thing, send multiple pull requests.

Send coherent history - Make sure each individual commit in your pull request is meaningful. If you had to make multiple intermediate commits while developing, please squash them before submitting.

Tests
---------------------------------------------
Please type the following command to run the test.

phpunit

or

vendor/bin/phpunit

or

vendor\bin\phpunit


Security Vulnerabilities
----------------------------------------------
If you discover a security vulnerability, please send an email to Baffour Adu Boampong at baffouraduboampong@gmail.com. 
All security vulnerabilities will be promptly addressed.


Requirements, Recommended Environment
----------------------------------------------
* Laravel 5.6
* Mysql
* Linux based OS preferre.
* PHP 7.1+
* Apache or Nginx


Support Donations
----------------------------------------------
Why not star the github repo? I'd love the attention! Why not share the link for this repository on Twitter, Facebook or HackerNews? Spread the word!

If you want to donate something you can reach out to me via email at baffouraduboampong@gmail.com or on twitter @baffourboampong


Installation
----------------------------------------------

NB: Make sure you have composer installed or you may downlaod composer at => https://getcomposer.org/download/

1. git clone <repo-url>
2. Open the console and cd into your project root directory
3. Rename .env.example file to .env inside your project root and update the database information. 
    (windows wont let you do it, so you have to open your console cd your project root directory and Run mv .env.example .env )
4. Run composer install or php composer.phar install
5. Run php artisan key:generate
6. Run php artisan migrate
7. Run php artisan db:seed to run seeders(Optional)
8. Run php artisan serve

#####You can now access your project at localhost:8000 :)

If for some reason your project stop working run :
1. composer install
2. php artisan migrate


License
----------------------------------------------
ComplainDesk is open-sourced software licensed under the MIT license.


#Built in Ghana for the world!
