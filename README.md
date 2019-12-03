# iFood Software Engineer Test
## Product and business requirements
We will be creating an application that recommends drinks and activities based on the current weather of the user's location.
We are going to begin with three weather descriptions. So the weather can be **Cold**, **Mild** or **Hot**.

For **Cold** days, with temperature below **15 celsius degrees**, we are going to recommend *Irish Coffee* and *Whisky* as drinks and *Ice skating*, *Cooking* and *Watch movies* as activities.

For **Mild** days, with temperature between **15 and 30 celsius degrees**, we are going to recommend *Water* and *Soda* as drinks and *Biking* and *Sightseeing* as activities.

For **Hot** days, with temperature above **30 celsius degrees**, we are going to recommend *Water*, *Beer*, *Soda* and *Milkshake* as drinks and *Surfing*, *Picnic* and *Wash a car* as activities.

Since we think big, we are going to launch our application in **multiple cities** around the world. Knowing that, we can expect thousands of users from day one.

## Technology briefing
* We need to build an API (able to accept RESTful requests) in order that a front-end application can show our drinks and activities recommendations to our users
    - You don't have to worry about the front-end part of the application
* We can expect that a front-end has the user's current **city** or **current latitude and longitude**
* You can make usage of OpenWeatherMaps API (https://openweathermap.org) to fetch temperature data
* The application must present high resilience, availability, maintainability, extensibility and be fault-tolerant.
## Deliveriables
 * You should assume that you are working within a team so your code must be available in a remote code repository such as GitHub (share it with us when you are finished)
 * Your README file should contain a description of meaningful **design** and **architectural choices** that you've taken and **challenges** that you've encountered while building your API
    - Include instructions on how to build and run your software (consider using some container/vm solution)
## Expectations
On our company culture we have a few values that influence in the way that we build software, such as simplicity, operational excelence and innovation.
Hence, feel free to be creative and use any technology that you think that solves the given problem. It is your time to shine.  
Keep in mind that we expect your code to have production quality and to meet both functional and non-functional requirements.
