<p align="center">
  <img src="https://lh3.googleusercontent.com/jcI2V_tHE5hedwvsa7cS0aA1YU_Yu6uCg0srh1SKvHCruFmrhGGOXPbVCvNJQjFJGXDqIHWfa1R2YR_49FoABf-7K-IQD7kwdCQ4JjEgFU3Y45F6hXg_nM6h4UwZNmtmGkZ5idWUtXXcYAyp7aNWN9mbrxOscXMjFK6gCE6GDlGbNkgOcTxPBdJjBVo3NUXrz7GhCuIEpe9Bu96yvq9BRBsVvrewfSG_pqlRhMtmKbTMdQUYAOqyplCVDyM_koxKiI2ovlst4QLpZHdiRAhqUECQTxhC1gJlHQMWhaadPgmXOd_bCVYLePT549JRAfe-t059f0SsymUxk4q8DYGEorip1GWuJhgjBGu3AshN20V-z7qFmEiteXio26mdKMAOVPjg1W26ButNdXmf8Z6BZBYh-qB4x_5q_ablaC1772urHHJdgpl3m7PyltAQ85RgGmERI3hR0QkpuLk2V8eTx37iIRaGoKBBzG9xSp6B0RXxMYPI4lnkt0buNEuNTb-6Rg7w2yaHIum6TwOVCnL70PLNlJDX2PiVxpnccKvsS2FQaaR5PncOX99dYgah5ofGqTB6UjeRDVIxaE_k5ZdkKWgN6pwWys9XiiQ-xyI76D3ph4GHAgMSYnRx_YJiyHTM69x8ks6KwXqpdNIcB_U61deRhPQGc7tGpt0NfLjIsLtWvVXNW7JRkw=s512-no">
</p>



# Movies Box :heart: [Demo link](https://mymovies-430e3.firebaseapp.com/)



### FullStack (Angular 7- Spring boot ) web application :heart: 

####  Using spring data , spring security , REST-Ful Api and a lot to discover

####  Successfully deployed on heroku and firebase hosting :art:

#  Table of content

<ul>
<li><a href="#about-the-project">About</a></li>
<li><a href="#feautures">Features  </a></li>
<li><a href="#getting-started">Getting Started</a></li>
<li><a href="#installation">Installation</a></li>
<li><a href="#deployement">Deployement</a></li>
<li><a href="#creator">Creator </a></li>
</ul>



# About the project 
Movies box is a Fullstack(Angular - spring boot ) web application built to allows users to discover everything about the latest movies and tv shows in the world.
Movies box is your guide to find whatever you want to watch in various ways.
It's also the perfect guide to every full stack developer who is interseted to start developping a modern web apps using angular and spring boot given the many features that contains.

## Feautures  

### Front-End 

*  **Reusable components** 	
    The reason that lies behind the choice of angular as a framework to implement the front end of our application is because it's capability to manage the reuse of the component
that's why we enjoyed defining a lot of reusable components as we can see :
	*  **Carousel Component**	
	*  **Navbar Component**
	* **Footer Component**
	* **MovieCard**
        <img src ="https://previews.dropbox.com/p/thumb/AAnYg7HSMmBkKVkNL9ps8TmMOsQy60r7AEQRx3zxgQJdc-V4FJAi34z2BtuJitUQvlnxrqg38Q_mUDshC5Cko5QkpxuQXSo2IaVl3Ri_-bcC8am6njGpCSfhSeC7bTxtQuZe8xvkOE5cwiLweii4H9nVXUmbG2OyTHYi-v71654PtkRc6AjXK6rGhUVizp4fTydrCQDoKu0aJ5Se9vFin3IE65NyEyLxbz6Na-6nkWT5VbluSUPsKhzxYZ6WA54nf6itXIncYlW-S3ezTUn3TxQx3rAdN5p2kVNsN5TqOtYIO3DQYoGMyjgxVjZVtvjNO-VZf8qfv-Ke4n8pA2Z5o-qS/p.png?size=1600x1200&size_mode=3"> <br>
	* **MovieRating**
	* **Contact Component**
	* **ActorComponent**
	* **WatchList Component**
	* **Sharing Component**
	
	and much more to explore ...
* **Responsive components**
Using angular material and MD Bootstrap that provide a lot responsive components such as tabs , navbar , footer ...

* **Ngx Translate**
Movies Box is an application that can be explored in 3 languages (English , Frensh and arabic).
All you have to do is to switch the language.
The translation is implemented using the Ngx Translate : The i18 N library for angular which allows you to easily tranlsate your components

* **Multiple criteria search**
 You can look for whatever you want using a lot of search criteria simultanously (genres, year , company , country , rating ...)
 
### Back-End 

* Using N-tier architecture to separate the different layers of the app
* Using DTO (data transfert object) layer to prevent the entity exposition
* Using JpaRepository to easily implements Entities CRUD ( Spring Data )
* Using spring security-jwt to implement the security layer
* Using the Mapstruct library to convert the Entity to DTO and vice versa
* Lombok plugin to implement the getters , setters n toString , hashCode using annotations  so that your code looks very optimized.

		


# Getting Started

## Prerequisites 
* #### Front-End ( Angular )
	* A stable version of node installed on your machine
	* Npm
		* `npm install npm@latest -g`
	* Angular CLI
		* `npm install -g @angular/cli`
 

* #### Back-End ( Spring Boot )
	* Java SDK v1.8 or higher 
	* Apache Maven 3.3 or above
	* Database : You should have **Postgres** intsalled on your machine in order to run Movies Box or you can switch to another DBMS but you need to configure your application.properties with right config of your new DBMS.
	For now we will stick with **Postgres**
	
## Installation 

 **Clone the repo**  :blush:
	 

    git clone https://github.com/FirasMessaoudi/angular-springboot-movies-app.git
   ### Back-End ( Spring Boot )

  Setting up the database

> As mentionned before we are working with **postgres** but it's very easy to switch to another DBMS.
> The reason behind working with postgres is it's simple integartion with the **heroku** the moment you choose to deploy your application.

* Create a database with the name of ' movies'

</br>
	
* Open the folder Back-end with your favorite Java IDE ( I recommand IntellinJ IDE ) 
	*  > You need to set up Lombok in your IDE before running the project.
	        Go To File->Settings->plugins->search for lombok plugin then click install and restart you ide.
	        Congrats you have lombok intsalled on your ide.

 
* Configure your environments Variables  as bellow
	
		 spring.datasource.url
		 spring.datasource.username
		 spring.datasource.password
	
* Now run your app as spring boot application and if everything goes well your back will start successfully.
</br>
	
	

### Front-End ( Angular )
Access the Front-End folder

    cd Movies-Front-end 
  
  Install dependencies

    npm install

Start the angular project 

    ng serve 

Verify the file 'src/environments/environment.ts '
The default port i'm using is **8084** the port and the **apiBaseUrl** should match your back-end url.



 
 ### Congrats 👏 🎉 
**If everything went well you can start enjoying Movies Box and explore it's best features❤️** 


## Deployement
In this bonus section we're gonna see how we can deploy our full stack application on heroku (Back end ) and firebase hosting (front end).

* ### Back end ### 
  First you need to [download](https://devcenter.heroku.com/articles/heroku-cli#download-and-install) and  install heroku cli
  *  **Verifying your intsallation**
  `heroku --version`
  *  **Preparing spring boot for heroku**
  Before you can deploy the app to Heroku, you’ll need to create a Git repository for the application and add all of the code to it by running these commands:
  `git init`
  `git add .`
  `git commit -m"first commit"`
  * **Login to your heroku account**
  `heroku login -i`
  * **Now you're ready to create your first heroku app**
  `heroku create`
  This also creates a remote repository called `heroku` in your local git repo. Heroku generates a random name for your app. You can rename it later with the `heroku apps:rename` command.
  Now deploy your code:
  `heroku push origin master`
  Heroku automatically detects the application as a Maven/Java app due to the presence of a  `pom.xml`  file. It installed Java 8 by default, but you can easily configure this with a  `system.properties`  file as described in the  [Specifying a Java version](https://devcenter.heroku.com/articles/java-support#specifying-a-java-version)  Dev Center article. It will run your app using the  [default command](https://devcenter.heroku.com/articles/java-support#default-web-process-type).

     All that said, the application is now deployed. You can visit the app’s URL by running this command:
     `heroku open`
    
     * #### Connecting to database ####
        As we said before , the reason why we choose postgres databse is that we can easily attach it to our app by running the following command :
        `heroku addons:create heroku-postgresql`
        Now you can list the configuration variables for your app to display the URL needed to connect to the database, DATABASE_URL:
        `heroku config`
        Heroku also provides a `pg` command that shows a lot more:
        `heroku pg`
        Once the database add-on has been created, Heroku will automatically populate the environment variables `SPRING_DATASOURCE_URL`, `SPRING_DATASOURCE_USERNAME`, and `SPRING_DATASOURCE_PASSWORD`. These environment variables should allow your Spring Boot application to connect to the database without any other configuration
        //image
* ### Front end ###
  Now as our back end is successfully deployed on heroku , we will deploy our front end using angular firebase hosting .
  * **Configure environment.prod.ts**
  copy your heroku app name into the apiBaseUrl in the environment.prod.ts file to connect your angular firebase app to the back end deployed on heroku.

  * **Building the Production Code**
  `ng build --prod`
  * **Installing firebase tools**
  `npm install -g firebase-tools`
    and copy and the content of the dist folder into the generated public folder
  * **login to firebase**
  `firebase login`
  * **initilize**
  This will create a firebase.json file to use during the deployment of your application. Run:
  `firebase init`
 
  For the most part, you can stick with the default settings, except for the following questions:
      *  Are you readey to proceed ? yes
      * Which firebase cli would you choose to setup ..? Hosting (third option)
      * Configure as single page app? Yes
      * If firebase asks to overwrite your index.html file, just say NO.
  * **Deploy**
  Finally, deploy the app.
  `firebase deploy`
  if all went well a link to your app will be generated on the console and your app is successfully deployed 
 
## Creator 

**Firas Messaoudi** :pencil2:

* [https://github.com/FirasMessaoudi](https://github.com/FirasMessaoudi)
* [https://www.linkedin.com/in/firas/](https://www.linkedin.com/in/firas/)


## License

Code released under the  [ MIT License](https://github.com/FirasMessaoudi/angular-springboot-movies-app/blob/master/LICENSE).
