# wms
warehouse management system

## What does this Project contains
- Feature of loading data into DB
- Migrations of DB with proper shemas
- 


## What does the container do
- Runs composer install
- Runs the laravel start up script


## Setup 
### Requirements
- Install docker
brew install docker
- Install docker-compose
brew install docker-compose 
- Install docker deamon
brew install docker-machine
- Run the command
 docker-compose up -d 
- Visit localhost:8080


### How to run tests

- Go inside the container and run
`php vendor/bin/codecept run --steps`


-----

## Things to Improve

- FE
	- Use webpack
	- Use sass
	- Use proper FE framework like react
	- Responsive API Call for deleting/selling
- BE
	- Read exact part from DB instead of all json file
	- read partials from files for huge files
	- read all json files and store them based on their table naming
	- Constraint on pivot table to avoid rep
	- Authentication
	- Pass products using resource in future to avoid sending all the data
	- Proper CSRF for all posts like sell
	- Pass proper request to Controller
	- Make the routes more RESTFUL
- Setup & Devops
	- Proper data container instead of jamming everything in 1 container
	- Proper data seeding with undefined jsons table namings
- Testing
	- Functional Testing
	- Unit Testing
	- Snapshot testing
	- API Testing
	- 
