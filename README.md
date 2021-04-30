

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


### Log-In : 

![1](https://user-images.githubusercontent.com/65017645/116651670-51ac3080-a9a1-11eb-91ef-36b14770229b.png)


### Main Page :

![2](https://user-images.githubusercontent.com/65017645/116651696-5f61b600-a9a1-11eb-806f-827fcb78f698.png)


### Add New Friend : 

![3](https://user-images.githubusercontent.com/65017645/116651795-9637cc00-a9a1-11eb-827a-923a8b84e86e.png)

### View Friend : 

![4](https://user-images.githubusercontent.com/65017645/116651851-b8314e80-a9a1-11eb-8812-625afb3f9fa1.png)



### Home Page

![5](https://user-images.githubusercontent.com/65017645/116651890-cc754b80-a9a1-11eb-8455-9e10bc7d1215.png)



### Edit Profile

![6](https://user-images.githubusercontent.com/65017645/116651990-eb73dd80-a9a1-11eb-969d-acbef4e99e1f.png)




### Forgot Password : 

![8](https://user-images.githubusercontent.com/65017645/116652159-486f9380-a9a2-11eb-918f-16f0308f1eb5.png)





## Future Prosprects :

* Adding a search feature for searching friends by name



## Refrences : 
* [Vedio](https://youtu.be/fmyvWz5TUWg)
