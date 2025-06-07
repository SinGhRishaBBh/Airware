# AQI Dashboard

## Real-time Air Quality Index (AQI) Monitoring and Health Advice

This AQI Dashboard is a modern web application built with Next.js, React, and TypeScript that provides real-time air quality data for Indian cities, along with personalized health recommendations and an AI-powered health advisor.

---

## ✨ Features

- **Current Air Quality Index (AQI)**: View live AQI and pollutant data (PM2.5, PM10, NO₂, SO₂) for major Indian cities.
- **City Search**: Easily search and select cities across India to fetch their current air quality.
- **Detailed Health Advice**: Receive comprehensive health recommendations tailored to different AQI levels, helping users take appropriate precautions.
- **AI Health Advisor (Chatbot)**: An interactive AI chatbot that provides personalized health advice based on the current AQI and pollutant measurements, powered by OpenAI.
- **AQI Trends**: Visualize historical AQI data for selected locations to understand patterns.
- **Data Upload**: Functionality to upload CSV or Excel files for further analysis and predictions (future enhancement).
- **Responsive Design**: A sleek and intuitive user interface built with Tailwind CSS and Shadcn/ui, optimized for various screen sizes.

---

## 🚀 Technologies Used

- **Next.js**: React framework for building server-side rendered and static web applications.
- **React**: A JavaScript library for building user interfaces.
- **TypeScript**: A superset of JavaScript that adds static typing.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
- **Shadcn/ui**: A collection of re-usable components built with Radix UI and Tailwind CSS.
- **RapidAPI**: For fetching real-time air quality data (specifically "Air Quality by API-Ninjas").
- **OpenAI API**: For powering the AI Health Advisor chatbot.
- **Lucide React**: A set of beautiful and consistent open-source icons.

---

## 🛠️ Setup and Installation

Follow these steps to get your AQI Dashboard up and running locally:

### 1. Clone the repository

```bash
git clone https://github.com/your-username/aqi-dashboard.git
cd aqi-dashboard
```

### 2. Install Dependencies

Using npm:

```bash
npm install
```

### 3. Environment Variables Setup

This project uses environment variables to manage API keys. Create a file named `.env.local` in the root of your project:

```
RAPIDAPI_KEY=your_rapidapi_key_here
OPENAI_API_KEY=your_openai_api_key_here
```

**How to obtain your API Keys:**

- **RapidAPI Key (for Air Quality by API-Ninjas):**
  1. Go to [RapidAPI.com](https://rapidapi.com/).
  2. Search for and subscribe to the "Air Quality by API-Ninjas" API.
  3. Once subscribed, you can find your `X-RapidAPI-Key` in the API dashboard. Copy this key and paste it into your `.env.local` file as `RAPIDAPI_KEY`.

- **OpenAI API Key (for AI Health Advisor):**
  1. Go to [OpenAI.com](https://openai.com/) and sign up for an account.
  2. Navigate to your API keys section.
  3. Create a new secret key. Copy this key and paste it into your `.env.local` file as `OPENAI_API_KEY`.

### 4. Run the Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

---

## 💡 Usage

1.  **Search for a City**: Use the search bar in the "Current Air Quality" card to find air quality data for any major Indian city.
2.  **View Health Advice**: The "Health Advice" card will dynamically display recommendations based on the current AQI for the selected city.
3.  **Interact with AI Health Advisor**: Click the chat icon in the bottom right corner to open the AI Health Advisor, and ask it questions about health precautions related to air quality.
4.  **Explore Trends**: The "AQI Trends" section provides historical data for your selected location.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📧 Contact

For any questions or support, please open an issue in this repository. 
