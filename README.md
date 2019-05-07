# Tasks-API #

#### Ruby on Rails rest api for TasksApp ####

* Rest-Api - Tasks
* 0.1.0

##### Requirements:  
- Bundler needs to be installed.
- Rails >= 5.2.3
- Ruby >= 2.6.3

### Setting Up 
----

##### 1. Clone the repositorie  
> git clone git@github.com:augustoscher/tasks-api.git

##### 2. Access the repositorie
> cd tasks-api  

##### 3. Install the dependencies
> bundle install

##### 4. Set up database  
> rails db:create db:migrate db:seed

##### 5. Running
> rails s


### Test
----
> GET http://localhost:3000/tasks

It should return:

>```{"id": 7,"title": "Estudar Ruby On Rails","done": true,"created_at": "2019-05-07T23:15:59.334Z","updated_at": "2019-05-07T23:15:59.334Z"}```
