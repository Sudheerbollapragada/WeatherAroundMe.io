# WeatherAroundMe

## Checkout - [WeatherAroundMe](https://WeatherAroundMe.netlify.app/)

## Features 🚀
*  Passwordless authentication by `Sawo Labs`
*  Fetching and showing all details related to weather of the city using `WeatherAPI - REST API`
*  Also showing city related image using `Bing Image Search - REST API`


## Preview
### [Live Link](https://WeatherAroundMe.netlify.app/)

Deployed at [Netlify](https://www.netlify.com/).

![Preview](/public/previewimg.png)

## Installation

First these commands and follow mentioned steps to get your app ready with installation.

```bash
git clone https://github.com/KuberAnand/WeatherAroundMe.git
```

```bash
npm install 
```

After installations, make a file `.env` in root directory and add some env variables there. 
* First add `REACT_APP_RAPID_API_KEY` which is api key to use both the rest apis. Get your own API KEY from [Rapid API Docs](https://docs.rapidapi.com/).
* Second add  `REACT_APP_SAWO_API_KEY` which is api key to use sawo auth for your app. Go to [Sawo Labs](https://dev.sawolabs.com/) , create a new project and genrate your api key. 
* Third add `REACT_APP_SAWO_CONTAINER_ID` which could be any string for ui container id.
* Fourth add  `REACT_APP_SAWO_IDENTIFIER_TYPE` which will is email or phone_number_sms authentication type as per your app's requirement.

To run your app use this command.

```bash
npm start
```

## Contributing

Your :star: is also greatly appreciated.




