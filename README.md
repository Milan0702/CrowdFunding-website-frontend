# Crowdfunding Tree Planting Website - Frontend

This is the frontend application for the Tree Planting Crowdfunding platform. The application allows users to make donations for planting trees, view real-time tree count updates, and track top donors through a leaderboard.

## Features

- Real-time tree counter display
- Donation form with secure payment processing
- Interactive leaderboard showing top donors
- Articles section about tree planting initiatives
- Responsive design for all devices
- Social media integration
- Beautiful UI with modern design

## Tech Stack

- React.js
- React Router for navigation
- Axios for API calls
- EmailJS for email notifications
- CSS for styling

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (comes with Node.js)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Milan0702/crowdfunding-frontend.git
cd crowdfunding-frontend
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add:
```
REACT_APP_API_URL=http://localhost:4000
```

4. Start the development server:
```bash
npm start
```

The application will start running at `http://localhost:3000`



## Available Scripts

- `npm start`: Runs the app in development mode
- `npm test`: Launches the test runner
- `npm run build`: Builds the app for production
- `npm run eject`: Ejects from Create React App

## Project Structure

```
src/
├── assets/         # Images and static assets
├── components/     # React components
│   ├── Articles/
│   ├── DonationForm/
│   ├── Header/
│   ├── Leaderboard/
│   ├── Navbar/
│   ├── TreeCounter/
│   └── Footer/
├── config/         # Configuration files
└── App.js         # Main application component
```

## Deployment

The frontend is deployed on Vercel. Each push to the main branch triggers an automatic deployment.

## Backend Repository

The backend code is available at: [Crowdfunding-Website](https://github.com/Milan0702/Crowdfunding-Website)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


Milan - [GitHub](https://github.com/Milan0702)
