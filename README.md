# Weather and Crypto Dashboard

A Next.js dashboard application that displays weather information, cryptocurrency data, and news.

## Features

- Real-time weather data for multiple cities
- Cryptocurrency price tracking
- Latest news updates
- Favorite cities and cryptocurrencies
- Responsive design
- Animations and transitions

## Prerequisites

- Node.js 18+ and npm
- OpenWeather API key
- NewsData API key

## Environment Variables

Create a `.env.local` file in the root directory with the following variables:

```env
NEXT_PUBLIC_OPENWEATHER_API_KEY=your_openweather_api_key
NEXT_PUBLIC_NEWSDATA_API_KEY=your_newsdata_api_key
```

## Getting Started

1. Clone the repository:
```bash
git clone <repository-url>
cd <repository-name>
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Deployment

This project is configured for deployment on Vercel. Simply push your code to GitHub and connect your repository to Vercel.

## Technologies Used

- Next.js
- React
- Redux Toolkit
- Tailwind CSS
- Framer Motion
- Axios
- TypeScript

## License

MIT
