# Weather App with AI Chatbot 🌤️💬

A modern, responsive web application that delivers real-time weather updates and features an interactive AI-powered chatbot. The app combines a sleek, animated UI with dynamic temperature-based backgrounds and seamless API integrations for a delightful user experience. Built with web technologies, it showcases neumorphic design, smooth animations, and a conversational AI assistant. 🚀

## Project Overview 🌍

This project is a single-page web application designed to provide users with current weather information for their location or any searched city. It includes a pop-up chatbot that leverages the Gemini API to respond to user queries with weather context. The app is fully responsive, ensuring a seamless experience across mobile, tablet, and desktop devices. Key highlights include dynamic background gradients, animated weather cards, and a neumorphic UI with vibrant emojis for an engaging interface. 🎉

## Features ✨

- **Real-Time Weather Data** 🌞: Fetches current weather details (temperature, humidity, wind speed, etc.) using the [OpenWeatherMap API](https://openweathermap.org/api) based on geolocation or user-entered city.
- **Dynamic Backgrounds** 🌈: Changes the page background with smooth gradient transitions based on temperature:
  - Cold (<10°C): Blue-green gradient ❄️
  - Mild (10-20°C): Light blue gradient 🌬️
  - Warm (20-30°C): Pink-orange gradient ☀️
  - Hot (>30°C): Red-orange gradient 🔥
- **Animated Weather Card** 📋: Neumorphic card with slide-in animation, pulsing weather emojis (e.g., ☀️, 🌧️, ❄️), and hover effects for an interactive experience.
- **AI-Powered Chatbot** 🤖: Pop-up chatbot with:
  - Sleek interface featuring a gradient header and custom scrollbar.
  - Typing indicator (bouncing dots) during AI response generation. ⏳
  - Integration with the [Gemini API](https://cloud.google.com) to process user messages with current weather context.
  - Fallback dummy response if the API fails. 😊
- **Responsive Design** 📱💻: Optimized for all screen sizes with adaptive layouts, font scaling, and touch-friendly interactions.
- **Smooth Animations** 🎥: Includes slide-in, pop-up/down, pulse, and fade-in effects for a polished look.

## Technologies Used 🛠️

- **Frontend**: HTML5, CSS3, JavaScript (ES6)
- **APIs**:
  - [OpenWeatherMap API](https://openweathermap.org/api) for weather data
  - [Gemini API](https://cloud.google.com) for AI chatbot responses
- **Styling**: Neumorphic design, CSS animations, gradient backgrounds, custom scrollbars
- **Fonts**: Poppins (via Google Fonts) for a modern typography
- **Tools**: Visual Studio Code, Browser DevTools, Git

## Folder Structure 📂

```
weather-app-with-chatbot/
├── index.html        # Main HTML file with weather and chatbot UI
├── README.md         # Project documentation
└── LICENSE           # MIT License file
```

## Setup Instructions 🛠️

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/priyam2xx3/weather-app-with-chatbot.git
   ```

2. **Obtain API Keys**:
   - **OpenWeatherMap API**: Sign up at [openweathermap.org](https://openweathermap.org/api) to get a free API key.
   - **Gemini API**: Obtain an API key from [Google Cloud](https://cloud.google.com).

3. **Configure API Keys**:
   - Open `index.html` in a text editor.
   - Replace `YOUR_OPENWEATHERMAP_API_KEY` with your OpenWeatherMap API key.
   - Replace `GEMINI_API_KEY` with your Gemini API key.

4. **Run the Application**:
   - Open `index.html` directly in a web browser, or
   - Use a local server for better performance:
     ```bash
     npx http-server
     ```
   - Access the app at `http://localhost:8080`.

## Usage 🚀

- **Weather Display** 🌦️:
  - On page load, the app attempts to fetch weather data for your current location using browser geolocation (if permitted).
  - Alternatively, enter a city name in the search bar and click "Search" to view weather details.
  - The weather card displays temperature, feels-like temperature, humidity, wind speed, and a weather-specific emoji.
- **Chatbot Interaction** 💬:
  - Click the 💬 button (bottom-right) to open the chatbot with a pop-up animation.
  - Type a message and press "Send" or the Enter key.
  - A typing indicator appears while the Gemini API processes the query with current weather context.
  - Receive an AI response or a fallback dummy message if the API fails.
  - Close the chatbot with the ✕ button, triggering a pop-down animation.
- **Responsive Experience** 📱:
  - The app adjusts layouts, font sizes, and element spacing for mobile (<480px), tablet (<768px), and desktop screens.
  - Touch-friendly buttons and smooth animations enhance usability.

## Future Improvements 🔮

- Add a 5-day weather forecast feature using OpenWeatherMap’s extended API. 📅
- Implement chatbot memory to maintain conversation context across messages. 🧠
- Integrate additional weather visualizations (e.g., graphs for temperature trends). 📊
- Enhance accessibility with ARIA labels and keyboard navigation. ♿
- Add offline support using Service Workers for cached weather data. 🌐

## Acknowledgments 🙏

A huge thank you to **@AIWallah** for their guidance and inspiration in developing this project. Their expertise helped shape the AI chatbot integration and overall design. 🙌

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
