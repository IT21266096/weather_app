# NodeJs Backend Application
This Node.js backend application is designed to store users' email and location data while also providing hourly weather reports every 3 hours. Users can store their details, update their locations, and retrieve weather data for a specific day. The application uses MongoDB to store user data and fetches weather information from the OpenWeatherMap API. Hourly weather reports are sent to users' emails using Nodemailer and Gmail. The application is deployed on Vercel.

## Instructions

Follow these steps to set up and run the project:

1. Clone this repository to your local machine.</br>
   **git clone https://github.com/IT21266096/weather_app.git**
   
2. Navigate to the project directory.</br>
   **cd weather_app**
   
3. Install the necessary dependencies using npm:</br>
   **npm install**

4. Set Enviroment Variables:</br>
   **MONGODB_URI=mongodb+srv://lakshand969:12345@basecluster.sbo4fqp.mongodb.net/weather-app?retryWrites=true&w=majority</br>
   PORT=8000**</br>

5. Start the Application</br>
   **npm start** or **node index.js**</br>

6.Access the API Routes<br>
  Access the API routes using Postman for testing. Import the provided Postman API collection to get started with testing the routes</br>
  ### Add New User</br>
  ![Screenshot_1](https://github.com/IT21266096/weather_app/assets/99247843/0b6adb9d-0d32-49c4-9ddb-11b930f285a4)</br>

  ### Update Location</br>
  ![Screenshot_2](https://github.com/IT21266096/weather_app/assets/99247843/430c6bcb-1964-4dbd-8e36-a0b7f9c441fe)</br>
  
  </br></br></br>

