
# Weather App in JavaScript

In this app, you can get the weather details of a particular city by entering the city name. You can also get your current location weather details by clicking on the "Get Device Location" button. You'll get many weather details including temperature in celsius, weather conditions, location, feels like, and humidity.

![App Screenshot](https://img.youtube.com/vi/c1r-NqYkFPc/maxresdefault.jpg)
 
 [View Live Demo](https://codingnepalweb.com/demos/weather-app-in-javascript/)
 
 [Watch it on YouTube](https://youtu.be/c1r-NqYkFPc)
 
## Usage

Paste your API key to the appid parameter of the given URLs. These URLs are in line.no 27 & 33 of script.js file. You can get an API key from [here](https://openweathermap.org/api) for free and view my [blog](https://www.codingnepalweb.com/build-weather-app-html-javascript/) for detailed information.

```javascript
api = `https://api.openweathermap.org/data/2.5/weather?q=${city}&units=metric&appid=your_api_key`;
```
```javascript
api = `https://api.openweathermap.org/data/2.5/weather?lat=${latitude}&lon=${longitude}&units=metric&appid=your_api_key`;
```

## Related

Here are some related projects

[Get User Location in JavaScript](https://www.youtube.com/watch?v=J-lUOFXxG_0)

[Currency Converter in JavaScript](https://www.youtube.com/watch?v=UY7F37KHyI8)

[Create Todo List App in JavaScript](https://www.youtube.com/watch?v=2QIMUBilooc)

## Feedback

If you have any feedback, please reach out to me at contact@codingnepalweb.com
