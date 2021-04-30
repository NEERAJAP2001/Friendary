

# ![Rails Example App](Resources/logo.png)


# What Does this WebApp do?

* Can add Friends with information like twitter username...
* Read and Update the information
* Delete the information 
* Has a User Login/SignUp Authentication 
* Update and Delete an Account 
* In short : All CRUD Operations Can be performed 

# Getting started

To get the Rails server running locally:

- Clone this repo
- `bundle install` to install all req'd dependencies
- `rake db:migrate` to make all database migrations
- `rails s` to start the local serve



## Folders

- `app/models` - Contains the database models for the application where we can define methods, validations, queries, and relations to other models.
- `app/views` - Contains templates for generating the JSON output for the API
- `app/controllers` - Contains the controllers where requests are routed to their actions, where we find and manipulate our models and return them for the views to render.
- `config` - Contains configuration files for our Rails application and for our database, along with an `initializers` folder for scripts that get run on boot.
- `db` - Contains the migrations needed to create our database schema.


## Walkthrough 




## Future Prosprects :

* Adding a search feature for searching friends by name
