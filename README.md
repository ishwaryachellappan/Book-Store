# Book-Store
Book Store is a simple single page application (SPA) that lets you buy, rate and leave your comment for all the books that are available in the store. You can also see all of your purchased books history or create your own favorite books list.

<br /><br />
Tech<br />
   ->Book Store uses a number of open source projects to work:<br />
   ->MongoDB - Free and open-source cross-platform document-oriented database<br />
   ->Mongoose - Elegant MongoDB object modeling for NodeJS<br />
   ->NodeJS - Evented I/O for the backend<br />
   ->ExpressJS - Fast, unopinionated, minimalist web framework for NodeJS<br />
   ->JSONWebToken - Used for authorization<br />
   ->Angular - Platform that makes it easy to build applications with the web<br />
   <br />
The goal of this project is to show the core concepts of building SPA with ExpressJS and Angular. In this project I've used:

<br />
    ->Wrapped each major feature into a module<br />
    ->Lazy-loading for most of the modules so the app can start faster<br />
    ->Preload lazy-loaded modules after the app starts so they can be ready for use as soon as possible<br />
    ->Shared module for compoennts, directives and pipes that can be imported into any feature module<br />
    ->Services for each major feature<br />
    ->Guards to prevent unauthorized users to view routes that require authentication or admin rights<br />
    ->Interceptors for attaching JWT token to the request headers, showing notifications from the server response and error handling<br />
    ->Custom directives<br />
    ->Custom pipes<br />
    ->TypeScript models<br />
    ->Reactive forms for handling user input<br />

<br /><br />
Installation<br />
Book Store requires<br />
   ->MongoDB v3.6+<br />
   ->NodeJS v8+<br /><br />
To start the database (port: 27017): Install MongoDB, open new cmd window (in project root) and run<br />
   ->$ cd server<br />
   ->$ start-mongodb<br /><br />
To add initial seeding: (do this step once only the first time you start the app) After you start MondoDB open new cmd window (in project root) and run<br />
  ->$ cd server<br />
   ->$ seedBooks<br /><br />
To start the server (port: 8000): open new cmd window (in project root) and run<br />
   ->$ cd server<br />
   ->$ npm install (if you havent already installed the dependencies)<br />
   ->$ npm start<br /><br />
To start the client (port: 4200): open new cmd window (in project root) and run<br />
  ->$ cd client<br />
  ->$ npm install (if you havent already installed the dependencies)<br />
  ->$ ng serve<br /><br />
Features<br />
  ->Anonymous users<br />
  ->Login/Register<br />
  ->View all books<br />
  ->View books details, rating and comments<br />
  ->Authenticated users<br />
  ->Buy books<br />
  ->Rate books<br />
  ->Comment books<br />
  ->View user profiles<br />
  ->View his own purchases history<br />
  ->Create favorite books list<br />
  ->Can change his own avatar<br />
  ->Admin users<br />
  ->Add books to the store<br />
  ->Delete books<br />
  ->Edit/Delete offensive user comments<br />
  ->Block/Unblock user from commenting<br />
  ->Change unappropriate user avatars<br />
