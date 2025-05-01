# 🌤️ Weather Dashboard App

A responsive and modern weather dashboard built using React and Vite. Search any city to see its current weather details in real-time, powered by the OpenWeatherMap API.



## 🛠 Tech Stack Used

- **[React.js](https://react.dev/)** (with Hooks)
- **[Vite](https://vite.dev/)** (for fast build and dev environment)
- **[Tailwind CSS](https://tailwindcss.com/)** (utility-first styling)
- **[Axios](https://axios-http.com/docs/intro)** (for API communication)
- **[Lucide React](https://lucide.dev/guide/packages/lucide-react)** (for icons)
- **[OpenWeatherMap API](https://openweathermap.org/api)** (weather data source)

## 🚀 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/weather-dashboard.git
cd weather-dashboard
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Configure API Key
Create a `.env` file in the root directory:
```env
VITE_OPENWEATHER_API_KEY=your_api_key_here
```
> 🔐 Ensure `.env` is added to your `.gitignore`

### 4. Run the App
```bash
npm run dev
```

### 5. Build for Production
```bash
npm run build
```

## 🔌 API Integration Details

### OpenWeatherMap API
- **Current Weather Endpoint**:
  `https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric`

### Usage in Code
```js
const API_KEY = import.meta.env.VITE_OPENWEATHER_API_KEY;
```

### Free Tier Limits
- **60 API calls/minute**
- **1,000,000 calls/month**

> Make sure to keep your key secure and not expose it publicly.

## ✨ Features

- 🌐 Search any city for live weather
- 🌓 Dark/Light mode toggle
- 🕒 Recent search history (last 5 searches)
- ⏳ Loading and error states
- 📱 Responsive and mobile-friendly design
- 🎨 Modern UI with Tailwind and icon support


## 📦 Deployment Options

You can deploy this app using any of the following:
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)
- [GitHub Pages](https://pages.github.com/)

Deployment steps for each are available in the documentation or project instructions.
