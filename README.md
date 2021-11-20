How To Use 🔧
From your command line, first clone react-cryptoApp:

# Clone this repository
$ git clone https://github.com/VaggelisAthan/react-cryptoApp

# Go into the repository
$ cd react-cryptoApp

# Remove current origin repository
$ git remote remove origin

Then you can install the dependencies

Using NPM:

# Install dependencies
$ npm install

# Setting env variables
 1. Rename sample.env file in react-cryptoApp folder to .env
 2. Go to https://rapidapi.com/Coinranking/api/coinranking1/ subscribe to the API and click test endpoint. 
 Copy the 'x-rapidapi-key' value into REACT_APP_RAPIDAPI_KEY env variable.

# Run on localhost
$ npm run start
