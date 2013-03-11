== Rails Conding Convention

1. Model Naming Convention

* Table: orders
* Class: Order
* File: /app/models/order.rb
* Primary Key: id
* Foreign Key: customer_id
* Link Tables: items_orders

2. Controller Naming Convention

* Class: OrdersController
* File: /app/controllers/orders_controller.rb
* Layout: /app/layouts/orders.html.erb

3. View Naming Convention

* Helper: /app/helpers/orders_helper.rb
* Helper Module: OrdersHelper
* Views: /app/views/orders/… (list.html.erb for example)

4. Tests Naming Convention

* Unit: /test/unit/order_test.rb
* Functional: /test/functional/orders_controller_test.rb
* Fixtures: /test/fixtures/orders.yml

== Rails App

* Testing with BDD Capybara, Cucumber
* Authentication with Devise & Omniauth
* Authorization with CanCan
* Pagination: 'will_paginate'
* Coffescript/Javascript MVC with Backbone and Template Handelbars
* Front-end with Bootstrap and SASS
* Admin page with rails_admin
* And others (add later)

== Running
* Run command bundle install
* rake db:migrate
* rake db:seed
* rails server

== Heroku Link
* http://japanese-elearning-site.herokuapp.com/
* Command to add to existing heroku: git remote add heroku git@heroku.com:japanese-elearning-site.git 


== Ways of working
* Follow naming convention
* Create git branch before coding
* Write BDD Test with Capybara
* Testing localhost before push to github
* After that, testing and running code in Heroku

== Mockup Tool for GUI
* Balsamiq Mockup

== Ways of management
* http://basecamp.com/
* http://kanbanize.com/
