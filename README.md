# BreweryDB

## Introduction 

This is a Web application for listing the beers and checking its details. The backend uses the ExpressJs framework. The frontend uses Reactjs, Bootstrap, CSS and JavaScript
framework.
* [ReactJs](https://reactjs.org/)
* [Bootstrap](https://getbootstrap.com/)

## Requirements

This Web application requires the following software:

* [Create-react-app](https://github.com/facebook/create-react-app) 
* [NodeJs](https://nodejs.org/en/)
* [Bootstrap](https://getbootstrap.com/)
* [FontAwesome](https://fontawesome.com/how-to-use/on-the-web/using-with/react)
* [ExpressJs](https://expressjs.com/)

### Installing

Install this software as usual. Here is an example of installing it on Ubuntu.
```
sudo apt-get install Create-react-app
```
## Project Structure

The project follows and extends the folder structure as expected by React.

```
Brewery-app
  |-- public                 # Python dependencies.
  |-- react-backend          # backend of the application
      |-- routes             # custom routes to handle backend calls.
            |-- index.js     # custom routes to handle requests and responses of API
            |-- users.js     # custom routes to handle request and responses of API.
  |-- src/                   
      |-- components         # Custom components.
      		|-- Details.js   # Custom reactjs component.
            |-- Details.css  # Custom css for Details component.
      		|-- Listing.js   # Custom reactjs component.
            |-- Listing.css  # Custom css for Listing Component.
      		|-- main         # Custom routes of the application.
      |-- img                # Image files of the application.   
      |-- app.js             # Main application file.
      |-- app.css            # Pre-defined CSS of the application.
      |-- index.js           
      |-- index.css 
      |-- package.json       # Lists all packages installed or dependent.         

```

## Development and Debugging

The application can be developed using just a text editor, Sublime text editor or any other IDE supporting ReactJs.
Setup the project by executing npm start from the project directory.

For the back-end.

```
cd brewery-app/react-backend
npm start
```

For the front-end.

```
cd brewery-app
npm start
```
ATTENTION: All the modules have to be properly installed before running the above commands.


## Author

* **Nikhil Raikar** - *Initial work* - [NikhilRaikar](https://gitlab.com/nikhilraikar88)
