# Unity - Food & Drinks

## Full Stack Frameworks with Django - Milestone Project 4

[Unity - Food & Drinks](https://unity-food-blog.herokuapp.com/) is an online recipe blog, where people can post and find new recipes for different kind of food and drinks. The thought behind this blog was to unite different recipes from all over the world, therefore the name “Unity”. 

## Description
Based on a thorough research on several blog websites with the focus on food and drinks, I found my purpose behind the Unity - Food & Drinks Blog. I found many websites to be very cluttered with information, ads and things that would set aside the viewers eyes from the actual purpose, which is to find a recipe for meals and/or drinks. Like my previous projects, I’ve followed this simplistic idea to put either the product or purpose right in the center with as little distractions as possible. “Unity - Food & Drinks” induces a simplistic idea of a blog in order to underline the basic 'CRUD' operations on databases. 
The site's architecture is very straight forward and minimalistic. The purpose is to allow the user to focus more on the recipes themselves and not to be baffled with many unnecessary pop-ups or unwanted browsing. 

## UX
### Why This Project
The main goal with this project was to create a Full Stack web application to demonstrate the knowledge and skillset obtained throughout the course. 
A passing grade in this project is required to graduate the course and obtain the Certification Degree. 
The site is using Python and Django Framework with a back-end database (PostgreSQL) for the back-end stack.
HTML5, CSS3 with Bootstrap 4.5 as framework and python packages such as Ckeditor was used for the front-end.

I realised one day that one of my questions, or if you may call it “struggles” in my daily life was “What should I eat today?”. That inspired my first user story and it all started from there. I wanted to create a website where you will find no limits to what food you will be cooking today. With inspiration from all over the world, this blog could inspire new ideas and hopefully create a bigger interest with cooking food. The user is able to find recipes from other users, which makes it more personal. 

#### Audience
- Everyone who is interested in either food or drinks
- All ages, both men and women.
- Users looking for inspiration for cooking recipes

## User Stories

| AS A     | I WANT TO BE ABLE TO ... | SO THAT I CAN... |
| ----------- | ----------- | ----------- |
| Site User | access the website with any devices | use the website anytime and anywhere |
| Site User | access all the important services from the nav bar| navigate through the blog with ease |
| Site User | click on a post  | read the full text |
| Site User | register an account | comment and add my own posts |
| Site User/Admin | view comments on an individual post | read the conversation |
| Site User | add comments to the blog posts | be involved in the conversation |
| Site User/Admin | create, read, update and delete posts | manage my blog content |

### Color Scheme
Color scheme is important as this is one of the first things site visitors notice when visiting the site. I chose white & blue to be the site's primary colors because these colors are easy and provide a positive feeling. The navigation bar remains a very bright gray color. Overall, the design keeps a very classic and simplistic look.

## Features

### Accounts

The accounts app will allow users to register for free and create their own unique account. The user is able to customise a profile with a short description and a profile picture. This is built using Django's authentication and authorization to validate profile data.

![profile](media/imgs/profilescreen.png)


The users will register using the registration form, found it the navbar. Registered users will be able to login by using the login form with their username and password.

![signup1](media/imgs/signup1.png)
![signup2](media/imgs/signup2.png)

### Homepage

Displays the Featured Post, and the latest posts in the blog

![featuredpost](media/imgs/featuredpost.png)

On this page, a user can filter the posts by two categories, either Food or Drinks.

![categories](media/imgs/categories.png)

### Navbar
##### While logged out
Navbar is fixed at the top of pages across the site, so that the site visitors easily navigate the whole site.  Navbar contains  `Logo`, `Categories`, `Signup`, `Login` and `Search`

![loggedout](media/imgs/navbarloggedout.png)
##### While logged in

When logged in, the `Signup` &  `Login` are replaced by  `Create Post` & `Logout`

![loggedin](media/imgs/navbarloggedin.png)

The navbar is reduced to a hamburger menu on smaller screen sizes

![hamburgermenu](media/imgs/hamburgermenu.png)

### Post Page & Comments
The blog post page includes a section for the entire post, where you will access the bigger scaled picture and you can read through the post which you have chosen.
![blogpost](media/imgs/blogpost.png)


The user can find the comment section to the right, where the user can read and be involved in the conversation.
![comment](media/imgs/comment.png)

As a user, you can save your posts as draft and you can also edit your post after they have been published.

![editpost](media/imgs/editpost.png)

### Search box

The search box is a function where you are able to find certain blog posts of your own choice.

![search](media/imgs/search.png)

## Technologies Used


  * [Visual Studio Code](https://code.visualstudio.com/) - The IDE used for developing this project.
  * [GitHub](https://github.com/) - Used to store and share all project code remotely.
  * [GitPod] - Used to finalise the project and refine the code and minor errors

**Front-End Technologies**
  * [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) - Used as the base for markup text.
  * [CSS3](https://developer.mozilla.org/en-US/docs/Archive/CSS3) -  Used to add styles to the HTML.
  * [Font Awesome](https://www.bootstrapcdn.com/fontawesome/) - Used for icons in the website.
  * [Bootstrap4](https://www.bootstrapcdn.com/) - Used to align the elements in the website using the grid system. And also used to create the hamburger button, the models, the buttons to style the forms.
  * [CKeditor](https://ckeditor.com/) - Used to add a rich text editor to stylize the blog posts.
  * [Cloudinary] (https://cloudinary.com/) - Used to store the CSS files and images used in the blog.
  * [Widget_tweaks] - This tool was used to customize the form fields in the templates

    **Back-End Technologies**

  * [Python 3.8.10](https://www.python.org/) - Used as the back-end programming language.
  * [Django](https://docs.djangoproject.com/) -  Used as my Python web framework.
  * [Heroku](https://www.heroku.com/) - for deployment
  * [PostgreSQL](https://www.postgresql.org/) - Used as relational SQL database plugin via Heroku.
