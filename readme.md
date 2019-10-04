# Axios refresh multiple parallel requests

This project was created due to comments i received from this [gist](https://gist.github.com/Godofbrowser/bf118322301af3fc334437c683887c5f) 

## Installation
 
### Clone the repository
```
git clone https://github.com/Godofbrowser/axios-refresh-multiple-request.git
```

### Install dependencies
```
npm i

// or 

yarn
```

### Start the build
```
npm run dev

// or 

yarn dev
```

### Start the demo api server
```
npm run serve

// or 

yarn serve
```

> When the index page is loaded, you will notice two alert dialogs. These are from 2 unauthorized request errors as we tried to request the api with invalid token. The script then sends a refresh token request to get new auth token after which the 2 requests that failed initially are then sent again, but this time with a new token gotten from the refresh token request. On success, you will notice the data was received and displayed on the webpage.

You can tweet [@godofbrowser](https://twitter.com/Godofbrowser) if you need to ask a question about this 
