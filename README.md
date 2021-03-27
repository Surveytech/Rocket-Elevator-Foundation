# Rocket Elevators Information System <img src="app/assets/images/favicon.png" align="right" alt="Rocket Elevators logo by Maxime Auger" width="100" height="">

# Week 7
#  Life is a Web Service
If more informations is needed on database and basic operation of our Web App please refer to Week 4 and Week 5's Readme at https://github.com/officialmxm/Rocket_Elevators_Information_System




 - 📚 Instructions to acces to the admin panel:


To log as Admin:
```
1. click the log in the nav bar
2. Username:admin@admin.com
3. password: 123456
4. click on the admin button in nav bar
```
![](app/assets/images/readme/login.png)









This week we are implementing API's to our web app. Here are the API's weve implemented this week. We also started working ENVIRONEMENTS using the gem FIGARO and the application.yml file.

- Google Maps
- Twilio
- Slack
- Dropbox
- Sendgrid
- IBM Watson
- Zendesk

Also we will show you the following updates
- Gems added
- API's
- Routes
- URL for our site https://claudestlaurent.xyz
- week 7 video link https://youtu.be/9A7IXR1kIfo
- Team



### 1 - Gems Added this week <img src="https://w7.pngwing.com/pngs/96/713/png-transparent-ruby-on-rails-programming-language-rubygems-php-ruby-gem-angle-heart-logo.png" align="right" alt="Rocket Elevators logo by Maxime Auger" width="70" height="">
* gem 'devise'
      https://github.com/heartcombo/devise

* gem 'rails-admin'
      https://github.com/sferik/rails_admin/




- to connect to your postgresql DB you nees to start it with this command line: 
**sudo service postgresql start/stop/status**# Rocket Elevators Information System <img src="app/assets/images/favicon.png" align="right" alt="Rocket Elevators logo by Maxime Auger" width="100" height="">

c
If more informations is needed on database and basic operation of our Web App please refer to Week 4 and Week 5's Readme at https://github.com/officialmxm/Rocket_Elevators_Information_System




 - 📚 Instructions to acces to the admin panel:


To log as Admin:
```
1. click the log in the nav bar
2. Username:admin@admin.com
3. password: 123456
4. click on the admin button in nav bar
```
![](app/assets/images/readme/login.png)









This week we are implementing API's to our web app. Here are the API's weve implemented this week. We also started working ENVIRONEMENTS using the gem FIGARO and the application.yml file.

- Google Maps
- Twilio
- Slack
- Dropbox
- Sendgrid
- IBM Watson
- Zendesk

Also we will show you the following updates
- Gems added
- API's
- Routes
- URL for our site https://claudestlaurent.xyz
- week 7 video link https://youtu.be/9A7IXR1kIfo
- Team



### 1 - Gems Added this week <img src="https://w7.pngwing.com/pngs/96/713/png-transparent-ruby-on-rails-programming-language-rubygems-php-ruby-gem-angle-heart-logo.png" align="right" alt="Rocket Elevators logo by Maxime Auger" width="70" height="">
* gem 'devise'
      https://github.com/heartcombo/devise

* gem 'rails-admin'
      https://github.com/sferik/rails_admin/

* gem 'devise'
      https://github.com/heartcombo/devise

* gem 'rails-admin'
      https://github.com/sferik/rails_admin/

* gem 'devise'
      https://github.com/heartcombo/devise

* gem 'rails-admin'
      https://github.com/sferik/rails_admin/


### 2 - Google Map

With our google account we log int the console.cloud.google where we ll set a google API key and enables service that we will need , copy the key and save it.



read me created by jean-francois taillefer

# Week 9
# Consolidation

## Information System
* [Link for the Information System Rails app website](claudestlaurent.xyz)
* [Link for the Information System Repo](https://github.com/Surveytech/Rocket-Elevator-Foundation.git)

For the Rest APi, the ReadMe file with the explanations are in this repo:

* [Link for the Information System Repo](https://github.com/Surveytech/Rocket-Elevator-Foundation_RestAPI.git)
* [Site for the Rest API URL](https://csl-restapiweek-9.azurewebsites.net)

For the rails app, I had to do a migration to create an Interventions table, who is in the ***csl*** mysql database in the Codeboxx server.
The Interventions section is accessible only in the website backend when an employee login.

To login, you can use those emails, with **123456** as password :

* nicolas.genest@codeboxx.biz
* nadya.fortier@codeboxx.biz
* martin.chantal@codeboxx.biz
* mathieu.houde@codeboxx.biz
* david.boutin@codeboxx.biz
* mathieu.lortiet@codeboxx.biz
* thomas.carriert@codeboxx.biz
* admin1@admin1.com
* admin@admin.com


The views for the Interventions section are in the views->interventions folder, and those who are used are new.html.erb (with _form.html.erb render in) and index.html.erb.

In the intervention controller, I added the Zendesk function to create a ticket each time a Intervention request is made. The ticket is send to my email and in the Zendesk dashboard.















