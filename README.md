#Weather App 🌤️

Welcome to my **Weather App**! This is a simple yet elegant weather application built using React. It allows users to search for the current weather conditions of any city worldwide. The app fetches real-time weather data from the [OpenWeatherMap API](https://openweathermap.org/api) and displays it in a clean and user-friendly interface.

---

## Features ✨
- **Real-Time Weather Data**: Get the current temperature, humidity, and wind speed for any city.
- **Dynamic Weather Icons**: Visual representation of weather conditions (e.g., clear sky, clouds, rain, snow).
- **Responsive Design**: Works seamlessly on all devices (desktop, tablet, and mobile).
- **Search Functionality**: Easily search for weather information by entering a city name.
- **Default Location**: Automatically displays the weather for New Delhi on page load.

---

## Technologies Used 🛠️
- **React**: A JavaScript library for building user interfaces.
- **OpenWeatherMap API**: Provides real-time weather data.
- **CSS**: Styled using modern CSS for a sleek and responsive design.
- **Vite**: Used for fast development and building the app.

---

## Screenshots 📸

![Weather App Screenshot](https://via.placeholder.com/600x400.png?text=Weather+App+Screenshot)  
*Replace this placeholder with an actual screenshot of your app.*

---

## Installation 🚀

Follow these steps to set up the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/react-weather-app.git
   cd react-weather-app
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   - Create a `.env` file in the root directory.
   - Add your OpenWeatherMap API key:
     ```
     VITE_APP_ID=your_api_key_here
     ```

4. **Run the App**:
   ```bash
   npm run dev
   ```
   The app will be running at `http://localhost:5173`.

---

## Usage 🖥️

1. **Search for a City**:
   - Enter the name of a city in the search bar.
   - Click the search icon or press `Enter` to fetch the weather data.

2. **View Weather Details**:
   - The app will display the current temperature, humidity, wind speed, and a weather icon.

3. **Default City**:
   - On page load, the app automatically displays the weather for **New Delhi**.

---

## Folder Structure 📁

```
react-weather-app/
├── public/
├── src/
│   ├── assets/                # Contains icons and images
│   ├── components/            # React components
│   │   └── Weather.jsx        # Weather component
│   ├── App.jsx                # Main app component
│   ├── main.jsx               # Entry point
│   ├── index.css              # Global styles
│   └── Weather.css            # Weather component styles
├── .env                       # Environment variables
├── .gitignore                 # Files to ignore in Git
├── package.json               # Project dependencies
├── README.md                  # Project documentation
└── vite.config.js             # Vite configuration
```

---

## API Key 🔑

To use the OpenWeatherMap API, you need an API key:
1. Sign up at [OpenWeatherMap](https://openweathermap.org/api).
2. Get your API key from the dashboard.
3. Add it to the `.env` file as `VITE_APP_ID`.

---

## Contributing 🤝

Contributions are welcome! If you'd like to improve this project, follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

---

## Live Demo 🌐

Check out the live demo of the app: [Weather App](https://your-deployed-app-link.com)  
*Replace this placeholder with your actual deployed app link.*

---

Enjoy using the **React Weather App**! If you have any questions or feedback, feel free to open an issue or contact me. 😊

---

**Happy Coding!** 🚀
