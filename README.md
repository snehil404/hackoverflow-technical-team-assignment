# HTS Technical Assignment 💻
Starter repo for Hackoverflow Technical Society's Technical Team Assignment


## 💭 How to attempt 
- Use the GitHub Classroom link provided to you to clone the repository
- There are two assignments that you MUST complete
- `main-assignment` directory contains the files for the main assignment which covers HTML, CSS, and Vanilla JavaScript
- `micro-assignment` directory contains a small task which focusses on debugging skills

## 1️⃣ Main Assignment
<b> Create a simple weather app using OpenWeather API 🌤</b>

The app should do the following:
1. Accept an _Indian city name_ as an input from the user
2. Perform _input validation_ using JavaScript (only text should be allowed; don't use HTML atrributes)
3. Use `jQuery UI Autocomplete` to _suggest_ city names
4. Fetch the _current weather_ of the city using the OpenWeather API
5. _Save the city name_ so that the user is shown the weather on next visit without having to input the name again (see `localStorage`)
6. Based on the weather, change the background of the page
   1. For _Sunny_ weather: `#FFEA00`
   2. For _Cloudy_ weather: `#FF5733`
   3. For _Rainy/Snowy_ weather: `#FF5733`
   4. For any other weather: `#F0F0F0`

### Resources:
- jQuery UI Autocomplete: https://jqueryui.com/autocomplete
- Indian City Names XML: https://github.com/vinaygaba/Ultimate-String-Array-List/blob/master/Country%20Lists/India/India%20States.xml
- OpenWeather API: https://openweathermap.org/current
### Guidelines:
- Use `index.html` for your markup
- Use `styles` directory for your CSS files
- Use `scripts` directory for your JavaScript files
- Use `assets` directory for multimedia (images, etc.)
  
### Tip:
You must preprocess the XML data (city names) and escape all the HTML tags before using it with `jQuery UI Autocomplete`. 
You can use `Postman`, `Thunder Client`, or any other API testing platform to check the data returned by the API.
##  2️⃣ Micro Assignment
- It is mostly about fixing and debugging the CSS and HTML
- In your GitHub repo, go to `Issues` tab -> `Micro Assignment` and complete the tasks

## 💡 Things to keep in mind
- Follow coding standards [https://wdexplorer.com/web-coding-standards/]
- Follow proper naming conventions and directory structure
- Use well-written _comments_
- K.I.S.S [https://en.wikipedia.org/wiki/KISS_principle]
- If you can do it using VanillaJS, _do not_ use jQuery
## 📬 Issues link
#### if you cannot access the issues in your repo: 
https://github.com/danish17/hackoverflow-technical-team-assignment/issues/