# Mobile Programming course portfolio site

Mobile Programming is [Haaga Helia's](https://www.haaga-helia.fi/en/frontpage) 4th semester course for software development students. The course contains the basics of React Native and students will develop their own mobile app at the end of the course. This site contains some example apps that students have made during the course.

## Fall 2021

### Fitness app

The Fitness App will give you workout inspiration by giving access to different workout moves, gives you a possibility to keep a journal in it and you can also check your daily, weekly and monthly steps from it. In the app you can search for movements by bodypart categories or by searching by the targeted area. The app is developed with React Native and the workout moves are fetched from an API called ExerciseDB on RapidApi.

![screenshot]({{ site.baseurl }}/img/fitness1.PNG)&nbsp;&nbsp;![screenshot]({{ site.baseurl }}/img/fitness2.PNG)&nbsp;&nbsp;![screenshot]({{ site.baseurl }}/img/fitness3.PNG) 

### Book Owl
by Jelena Laakkonen 

Book Owl allows the user to search, rate and save books into three different bookshelves (Want to Read, Reading, Read). From the Home page the user can search by predetermined genres and from the Search page by title or author. By clicking one of the books the user can see more information about the book. To use the application the user must first create an account and log in. All the user's bookshelves and ratings are personal. The application uses Firebase Realtime Database and Firebase auth for authentication. The books are fetched from the Google Book API.

![screenshot]({{ site.baseurl }}/img/bookowl1.jpg) ![screenshot]({{ site.baseurl }}/img/bookowl2.jpg) ![screenshot]({{ site.baseurl }}/img/bookowl3.jpg) 

### Wine App

React native application made with styled-components that suggests randomly chosen wines and allows user to find wines by name or with filter and examine chosen wine. User can also select favorites which saves them to firebase database for further use.

![screenshot]({{ site.baseurl }}/img/winery1.png) ![screenshot]({{ site.baseurl }}/img/winery2.png) ![screenshot]({{ site.baseurl }}/img/winery3.png) 

### CryptoWallet 
by Son Trinh

CryptoWallet application can be used to track the price of top coins in the market or the coins you have in your portfolio. The application using the live chart to show the live price as well as the chart to show the index of the coins. The application using React Redux, Redux Thunk, React Native Chart Kit and Rainbow Animated Chart. Coins data comes from Coingecko API. 

![screenshot]({{ site.baseurl }}/img/crypto1.png) ![screenshot]({{ site.baseurl }}/img/crypto2.png) ![screenshot]({{ site.baseurl }}/img/crypto3.png) 

### Password App

App is used for generating random passwords and storing them along with username and provider name to your device. User authentication is done with Firebase, which provides each user with unique id to access your encrypted password information. Passwords generated with PasswordWolf API.

![screenshot]({{ site.baseurl }}/img/pwd1.jpg) ![screenshot]({{ site.baseurl }}/img//pwd2.jpg) ![screenshot]({{ site.baseurl }}/img//pwd3.jpg) 

### Lyrico

Lyrico is an app where you can find lyrics for almost any song available on Spotify. When you look for a song you will be able to favorite it and even play a 30 second preview directly from Spotify. You can also reverse search songs with lyrics.

![screenshot]({{ site.baseurl }}/img/lyrico1.jpg) ![screenshot]({{ site.baseurl }}/img//lyrico2.jpg) ![screenshot]({{ site.baseurl }}/img//lyrico3.jpg) 


## Spring 2021

### Mini Museum

The Mini Museum is virtual museum app where you can find Egyptian and Chinese museum treasures. User can login to the app and mark items to the favourites. The app is developed with React Native and Firebase. The data comes from the Metropolitan Museum of Art Collection API (https://metmuseum.github.io/)

![screenshot]({{ site.baseurl }}/img/museum1.jpg) ![screenshot]({{ site.baseurl }}/img/museum2.jpg) ![screenshot]({{ site.baseurl }}/img/museum3.jpg) 

### The Receipe App
by Marcus Moe

The Recipe App helps you to find new and exciting recipes.The app allows for filtering based on mealtype, diet, calorie count and more, as well as searching for your favorite recipes.Furthermore, the app allows for displaying nutrition values from a recipe in informative graphs. If you really enjoy a particular recipe, a saving functionality provides easy access at a later point in time. The app utilizes the Edamam Recipe Search API for fetching recipes and Firebase Realtime Database for saving your favorite recipes. Sourcecode: https://github.com/marcusbrmoe/MobileRecipeApplication

![screenshot]({{ site.baseurl }}/img/receipe1.PNG) ![screenshot]({{ site.baseurl }}/img/receipe2.PNG) ![screenshot]({{ site.baseurl }}/img/receipe3.PNG) 

### Aircut
by Ruskin Kollin

No matter where you live, you can be exposed to air pollution. It can contribute to small annoyances like coughing or itchy eyes to worse diseases like cancer. With this app, you can monitor the air quality in your area and warn you of high pollution. The app will also provide data on weather such as humidity and windspeed. It can detect your location and show data immediately. It has also search functionalities to find what you are looking for faster. Moreover, users can save a city for easier access to its information. Take a walk or recycle, save our air!

![screenshot]({{ site.baseurl }}/img/aircut1.jpg) ![screenshot]({{ site.baseurl }}/img/aircut2.jpg) ![screenshot]({{ site.baseurl }}/img/aircut3.jpg) 

### BookApp
by Veera Aaltonen

BookApp allows you to search for books by title and author name, and save interesting books to user's own favorites. User needs to create account and login to the app to be able to search books and add them to favorites. User can search books, read information about them and add them to their favorites. Favorites can be found from user profile page. Profile page holds user's profile picture and logout-button. Firebase works as a database and app also uses Firebase auth to authenticate user. Book data comes from Google Book API.

![screenshot]({{ site.baseurl }}/img/bookapp1.jpeg) ![screenshot]({{ site.baseurl }}/img/bookapp2.jpeg) ![screenshot]({{ site.baseurl }}/img/bookapp3.jpeg) 

### Lyric for friends
by Quan Dao

With this app,  users can find the lyric of favorite songs in all over the world. They can easily find the best songs so far in different countries, or in different genre like acoustic, jazz, pop, etc. Besides, users can search specific song by the song name or the best albums by the artist’s name. If like it, they can add the song to the favorite list, which is handle by firebase, for later usage and easily remove it. Finally, the app has the login signup system to improve the security and authentication. 

![screenshot]({{ site.baseurl }}/img/lyricsapp1.jpg) ![screenshot]({{ site.baseurl }}/img//lyricsapp2.jpg) ![screenshot]({{ site.baseurl }}/img//lyricsapp3.jpg) 


## Fall 2020

### Nutritionix
by Petra Pylkki

The Nutritionix App is a nutrition/macro tracker. It helps signed-in users to keep on track of the food they have consumed and the nutritional values of them in progress circle. The app uses the Nutritionix API v2 Instant Endpoint, that provides autocomplete in textbox interfaces, in this case, the search bar. For user authentication and CRUD-functions, app uses Google Firebase Realtime Database.

![screenshot]({{ site.baseurl }}/img/nutri1.png) ![screenshot]({{ site.baseurl }}/img/nutri2.png) ![screenshot]({{ site.baseurl }}/img/nutri3.png) 

### FoodYeti
by Raphaël Darbellay

The application developed allows you to order food in restaurants to avoid waiting in the often long queues.

Users have the possibility to log in or create an account. Each user can then freely browse through the list of all the restaurants or categories available in the application or consult them on the interactive map available. This data is provided through a third party Rest API. Once the user has chosen their restaurant, they easily compose their menu, select a retrieval method, time and date and confirm their order. The currently available retrieval methods are : Delivery, Pick-up at the restaurant, Eating on site. A notification is sent in the application only for each new order so that the order can be easily retrieved later.

Orders are easily manageable thanks to the QR code system. Each order has a unique QR code which makes it easy to retrieve and collect the order when picking up the dishes.

Users can edit their profile from within the application, all data is stored online using Firebase Database and Firebase Storage.

See more: https://raphaeldarbellay.ch/portfolio-archive/foodyeti/

![screenshot]({{ site.baseurl }}/img/yeti1.PNG) ![screenshot]({{ site.baseurl }}/img/yeti2.PNG) ![screenshot]({{ site.baseurl }}/img/yeti3.PNG) 

### Cocktailify
by Nataliya Zinovyeva 

Cocktailify - a mobile app for cocktail lovers. Enjoy cocktails wherever and whenever you want. Choose, explore, add to favourites, save ingredients to your shopping list! For Finnish users, search for the nearest Alko stores is available. The app even works as a cocktail shaker - shake it and it will offer you a new cocktail every time, you just have to choose!

![screenshot]({{ site.baseurl }}/img/coctail1.png) ![screenshot]({{ site.baseurl }}/img/coctail2.png) ![screenshot]({{ site.baseurl }}/img/coctail3.png) 

### City Transit App

The City Transit App can be used to locate city bikes all around the world. The app shows how many bikes are available in each location. The app can be also used to see public transport schedules  in the Helsinki area.

![screenshot]({{ site.baseurl }}/img/citybike1a.JPEG) ![screenshot]({{ site.baseurl }}/img/citybike1.JPEG) ![screenshot]({{ site.baseurl }}/img/citybike2.JPEG) 

### Water Intake App
by Henri Väisänen

An app to track daily water intake made using Expo, React Native and Firebase Realtime Database. See more details from https://github.com/henettaja/water-tracker.

![screenshot]({{ site.baseurl }}/img/Water1.png) ![screenshot]({{ site.baseurl }}/img/Water2.png) ![screenshot]({{ site.baseurl }}/img/Water3.png) 

### LifeSteal

LifeSteal App, a videogame manager application named after one of the most common character stats in videogames and role-playing games, gives access to the world’s largest videogame database – RAWG. Through its API service it provides search and game suggestion functionalities. Another feature of this app is Quest Log, a list of game challenges saved with Firebase Realtime Database.

![screenshot]({{ site.baseurl }}/img/life1.png) ![screenshot]({{ site.baseurl }}/img/life2.png) ![screenshot]({{ site.baseurl }}/img/life3.png) 

### Travsinki

Travsinki is an app for searching places in Helsinki. The app shows restaurants, parks, saunas and more in Helsinki and display it on a map.

![screenshot]({{ site.baseurl }}/img/trav1.PNG) ![screenshot]({{ site.baseurl }}/img/trav2.PNG) ![screenshot]({{ site.baseurl }}/img/trav3.PNG) 


## Spring 2020

### MovieBox
by Bohan Liu

The MovieBox is a movie/TV show collection app. You can find the popular, top-rated and upcoming list of movies/TV shows. The app uses a real-time movie database API, so the content will always be the latest. In the discover page, you can also search for movies/TV shows. You can type the keyword and it will show all movies/TV shows that include that keyword, and you can clear the result. In me page, you can log in or sign up or use social media account to login in. You can change the brightness inside this app, and make your phone always awake when you are using this app

![screenshot]({{ site.baseurl }}/img/movie1.PNG) ![screenshot]({{ site.baseurl }}/img/movie2.PNG) ![screenshot]({{ site.baseurl }}/img/movie3.PNG) 

### Pet Adoption

The app for adopting pets. You can use map to see pets that are available for adoption near you. 

![screenshot]({{ site.baseurl }}/img/petAdoption_1.png) ![screenshot]({{ site.baseurl }}/img/petAdoption_2.png) ![screenshot]({{ site.baseurl }}/img/petAdoption_3.png)

### Password Generator

This app can be used to generate and save passwords. Password generator is using public API. User can define the length and some other rules of password.

![screenshot]({{ site.baseurl }}/img/pwd1.PNG) ![screenshot]({{ site.baseurl }}/img/pwd2.PNG) ![screenshot]({{ site.baseurl }}/img/pwd3.PNG)

### Lyrics Finder

Lyrics finder is a simple mobile app for finding song lyrics.  The Search can be done by using artist's name, album title or using only the song title. User has a possibility to save songs to favourites and also play a little preview of the song. Authentication and saving is implemented by using Firebase.

![screenshot]({{ site.baseurl }}/img/lyrics1.jpg) ![screenshot]({{ site.baseurl }}/img/lyrics2.jpg) ![screenshot]({{ site.baseurl }}/img/lyrics3.jpg)

### Covid-19 tracker

This tracker provides the number of patients diagnosed with the novel coronavirus, the number of deceased patients and the number of recovered patients. The data are based on research by Johns Hopkins University (JHU) and the World Health Organization’s (WHO) Coronavirus Disease (COVID-2019) situation reports.

![screenshot]({{ site.baseurl }}/img/covid1.png) ![screenshot]({{ site.baseurl }}/img/covid2.png) ![screenshot]({{ site.baseurl }}/img/covid3.png)

### Forks & Knives

Receipe finder with links to instruction videos. User can rate receipes and save own favorite lists to the Firebase.

![screenshot]({{ site.baseurl }}/img/forks1.png) ![screenshot]({{ site.baseurl }}/img/forks2.png) ![screenshot]({{ site.baseurl }}/img/forks3.png)

### Where to Go Helsinki

"Where to go Helsinki" is an app that gives you an opportunity to find interesting events and places in the Helsinki area. To make it easier the events and places are divided into categories. If you are visiting Helsinki for the first time in your life you don't have to worry about where to eat or how to find accommodation because this info is already in the app. You can save events and places that you liked or would like to visit later.

![screenshot]({{ site.baseurl }}/img/hel2.jpg) ![screenshot]({{ site.baseurl }}/img/hel4.jpg) ![screenshot]({{ site.baseurl }}/img/hel3.jpg)

### Vacay
by Anastasiia Burkova

Vacay is a traveling blog app. Users can write, modify or delete their blog posts and read the blog posts of other users. Blogs are sorted by countries that is based on the user’s post location. Every user has a personal map where he can see all the locations he has been visiting and writing about. There is also a possibility to search flight tickets in order to expand the traveling experience. Skyscanner Rapid API is used for that purpose. 

![screenshot]({{ site.baseurl }}/img/vacay1.PNG) ![screenshot]({{ site.baseurl }}/img/vacay2.PNG) ![screenshot]({{ site.baseurl }}/img/vacay3.PNG)

## Fall 2019

### TopySoft
by Vivian Bridy

Topysoft is an app that helps companies, organisations or groups of people to 
gather money for an event.

A user signs up to the app. Then he will meet an administrator who will register him as a member for a particular event (simply by scanning a qrcode on the user's phone). The user can now begin to gather donation for the event. Each time, user will collect informations about the donator. Those informations are then saved to be reused for an other edition of that event.

Technologies: Flutter, Firebase

![screenshot]({{ site.baseurl }}/img/Screenshot_1575144638.png) ![screenshot]({{ site.baseurl }}/img/Screenshot_1575144730.png) ![screenshot]({{ site.baseurl }}/img/Screenshot_1575144740.png)
![screenshot]({{ site.baseurl }}/img/Screenshot_1575144748.png) ![screenshot]({{ site.baseurl }}/img/Screenshot_1575144763.png) ![screenshot]({{ site.baseurl }}/img/Screenshot_1575144802.png) 

### Navix

Tourist travel app built with React Native. User can find different locations according to category and distance. App can find route to the location by public transports and walking

![screenshot]({{ site.baseurl }}/img/navix2.png) ![screenshot]({{ site.baseurl }}/img/navix3.png) ![screenshot]({{ site.baseurl }}/img/navix4.png)

### Piksly
By Emil Kaidesoja & Elmeri Kinnunen

Mobile app for object recognition. The students built the mobile app using React Native and backend using Python. Backend is using Keras deep learning library for Python. 

The app can be found from [Google Play](https://play.google.com/store/apps/details?id=com.main.awesome)

![screenshot]({{ site.baseurl }}/img/piksly1.jpg) ![screenshot]({{ site.baseurl }}/img/piksly2.jpg) ![screenshot]({{ site.baseurl }}/img/piksly3.jpg)

### Tenacious

The React Native app to keep ideas, dreams and aspirations. Authentication and saving is implemented by using the Firebase.

![screenshot]({{ site.baseurl }}/img/tenac2.png) ![screenshot]({{ site.baseurl }}/img/tenac1.png) ![screenshot]({{ site.baseurl }}/img/tenac3.png)

### Project Manager

A project manager app built with React Native. Create tasks for your projects, organize these using custom categories, and track their progress with project milestones.

![screenshot]({{ site.baseurl }}/img/screenshot-2.png) ![screenshot]({{ site.baseurl }}/img/screenshot-3.png) ![screenshot]({{ site.baseurl }}/img/screenshot-4.png)

### Weather Mapped

A simple weather app built with React Native. Users can check the current weather of the location by tapping it on the map. Users can also mark their favorite locations on the map.

![screenshot]({{ site.baseurl }}/img/weathermapped_screenshot1.jpg) ![screenshot]({{ site.baseurl }}/img/weathermapped_screenshot2.jpg) 

### Dog Meeting

Dogs meeting app for breeding purposes built with React Native. Using Firebase for authentication and saving.

![screenshot]({{ site.baseurl }}/img/dog_meet1.png) ![screenshot]({{ site.baseurl }}/img/dog_meet2.png) ![screenshot]({{ site.baseurl }}/img/dog_meet4.png)

### BoardGame Finder

User can search board games and their rules. There is also possibility to save own favorites.  App is using public Rest API and it is developed using React Native.

![screenshot]({{ site.baseurl }}/img/board1.jpg) ![screenshot]({{ site.baseurl }}/img/board2.jpg) ![screenshot]({{ site.baseurl }}/img/board3.jpg)

### MySong

React Native App to find song lyrics and guitar chords. User can save songs to own favorites. Authentication and saving is using firebase.

![screenshot]({{ site.baseurl }}/img/song1.jpg) ![screenshot]({{ site.baseurl }}/img/song2.jpg) ![screenshot]({{ site.baseurl }}/img/song3.jpg)

### Realtime Chat

Realtime chat app with server side implementation.

Tehcnologies in the front end: React Native (Hook, ES6), Redux, Gifted
Chat UI, Flatlist, react-navigation

Tehcnologies in the back end: Socket-chat.io, NodeJs

![screenshot]({{ site.baseurl }}/img/Screenshot 2019-12-11 at 0.54.13.png) ![screenshot]({{ site.baseurl }}/img/
Screenshot 2019-12-11 at 1.00.23.png) ![screenshot]({{ site.baseurl }}/img/Screenshot 2019-12-11 at 0.58.14.png)

### Book Worm

A simple book application built with React Native, Redux and Firebase. User can add books they are reading and mark them as read / unread. 

![screenshot]({{ site.baseurl }}/img/IMG_1063.PNG) ![screenshot]({{ site.baseurl }}/img/IMG_1065.PNG) ![screenshot]({{ site.baseurl }}/img/IMG_1067.PNG)

