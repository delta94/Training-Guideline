# Guideline about Project 1

## 1. Some general information
#### Execution time:
10 working days (In case of training part-time, training time is calculated up to 20 consecutive days from the start date)
#### Number of members:
1 ~ 3 people
#### Reference topic:
https://docs.google.com/spreadsheets/d/1TjPuQu7fe6CxDWmlttp0LTjQs8nw7Equ/edit#gid=940143881
#### Applicable models:
Scrum
#### Coding convention
##### Ruby coding convention
[English version](https://github.com/framgia/coding-standards/blob/master/eng/ruby/standard.md)
[Vietnamese version](https://github.com/framgia/coding-standards/blob/master/vn/ruby/standard.md)
##### Rails coding convention
[English version](https://github.com/framgia/coding-standards/blob/master/vn/rails/standard.md)
[Vietnamese version](https://github.com/framgia/coding-standards/blob/master/eng/rails/standard.md)

#### Technical list applied in project 1
1. [Nested Attribute (fields_for, reject_if, allow_destroy, ...)](http://api.rubyonrails.org/classes/ActiveRecord/NestedAttributes/ClassMethods.html)
2. [Batch Update](https://apidock.com/rails/ActiveRecord/Relation/update_all)
3. [form_for](http://api.rubyonrails.org/v5.1/classes/ActionView/Helpers/FormHelper.html)
4. [Call back function](http://api.rubyonrails.org/classes/ActiveRecord/Callbacks.html)
5. Macro (generate, rake, spring, ...)
6. Ajax (Rails ajax, jQuery ajax)
7. [Seed](https://codedecoder.wordpress.com/2013/04/25/rake-db-seed-in-rails/)
8. [RESTful](http://www.infoq.com/articles/rest-introduction)
9. [Association (has_many/has_one/belongs_to)](http://guides.rubyonrails.org/association_basics.html)
10. [Transaction](http://api.rubyonrails.org/classes/ActiveRecord/Transactions/ClassMethods.html)
11. [Resources, Nested Resources](http://guides.rubyonrails.org/routing.html)
12. [Resource](http://guides.rubyonrails.org/routing.html)
13. [Export CSV, Excel](http://railscasts.com/episodes/362-exporting-csv-and-excel)
14. [Rake task](https://viblo.asia/p/rake-task-rails-DzVkpLQLknW)
15. [CSRF Protection](http://guides.rubyonrails.org/security.html)
16. [Coffee](https://www.sitepoint.com/using-coffeescript-in-rails/)
17. [Concerns](http://api.rubyonrails.org/v5.1/classes/ActiveSupport/Concern.html)
18. [Scope](http://api.rubyonrails.org/classes/ActiveRecord/Scoping/Named/ClassMethods.html)
19. [I18n(mutilple language, dictionary, time format, number format, ...)](http://guides.rubyonrails.org/i18n.html)
20. Search form, filter form
21. [Gem Config](https://github.com/railsconfig/config)
22. [Eager Loading Associations](http://guides.rubyonrails.org/active_record_querying.html#eager-loading-associations)
23. [Validation](http://guides.rubyonrails.org/active_record_validations.html)
24. [Environment Variable](http://railsapps.github.io/rails-environment-variables.html)
25. [MVC](https://www.sitepoint.com/model-view-controller-mvc-architecture-rails/)
26. [Module mixin](https://www.tutorialspoint.com/ruby/ruby_modules.htm)
27. Proc / Lambda
28. Debug Javascript code
29. [Jquery selector](https://api.jquery.com/category/selectors/)
30. [CSS selector](https://www.w3schools.com/cssref/css_selectors.asp)
31. [Ruby Nil Object](https://ruby-doc.org/core-2.4.0/NilClass.html)

## 2. Steps to take
1. Design database
2. Add tasks on redmine + estimate time
3. Init project
4. Init models, add relationship
5. Design static pages
6. Other pulls

#### Note:
- The pull request từ from section 6 onwards each pull does not exceed 15 file changes
- Everyone in the team cross review for each other then approve pull request when there are no errors
- Then send a pull request to the trainer to review

## 3. Add tasks on redmine + estimate time
- Sign up for a redmine account on the site [here](https://edu-redmine.sun-asterisk.vn/)
#### Note:
- Refer to account naming [here](https://github.com/framgia/Training-Guideline/blob/master/Rails/RegisterEduRedmine.png)
- Each ticket task estimate do not exceed 8 hours, In case of large task, split many tickets to perform
- Change ticket status as instructed [here](https://github.com/framgia/Training-Guideline/blob/master/WorkingProcess/redmine/redmine.md)

#### The process of changing the status of a ticket:
1. Create ticket for all features and subtasks before doing it
2. Tickets redmine must be fill full Category, Target Version, Parent task, Start date, Due date, Estimated time
3. Dev assigns a ticket, then changes ticket's status to "In Progress"
4. When you have done this ticket, create a pull request, add link pull in this ticket, change %DONE to 90%
5. Send link pull request to all teammates to review
6. PR must be reviewed and approved by teammates, then send it to trainers to review
7. After pull request has been merged, you update %DONE of ticket to 100%, changes ticket's status to "Resolved"

## 4. Rules create a pull request
- Add attchment the link ticket redmine in pull's description
- Add attchment the result of task has passed test rubocop
- Add attchment the result of task
- Send and track pull request on the system [PRTS](https://prts.sun-asterisk.vn/)
- For pull request init model, must have the attachment of the Database design image

## 5. Review project
- The project must be done >=85% requirements before reviewing
- Deploy project on heroku
- Use link heroku to present project
- Prepare all necessary data to login
- Only present the feature you do
- If your project hasn't done >=85% requirement, you must contact your trainer and discuss about extending time

#### Happy coding!!!
