# Netflix Clone

A modern Netflix clone built with React, TypeScript, and Material-UI. This application includes user authentication, movie browsing, video streaming, and personalized recommendations.

## Features

- User authentication (sign up, login, logout)
- Movie browsing with categories
- Video streaming with custom player
- Search functionality
- Responsive design
- Dark mode support
- Movie details and information
- Personalized recommendations

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Firebase account
- TMDB API key

## Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/netflix-clone.git
cd netflix-clone
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Create a `.env` file in the root directory and add your Firebase and TMDB API credentials:
```
REACT_APP_FIREBASE_API_KEY=your_api_key_here
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain_here
REACT_APP_FIREBASE_PROJECT_ID=your_project_id_here
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket_here
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id_here
REACT_APP_FIREBASE_APP_ID=your_app_id_here
REACT_APP_TMDB_API_KEY=your_tmdb_api_key_here
```

4. Start the development server:
```bash
npm start
# or
yarn start
```

## Project Structure

```
src/
  ├── components/        # Reusable components
  ├── pages/            # Page components
  ├── store/            # Redux store and slices
  ├── types/            # TypeScript type definitions
  ├── config/           # Configuration files
  ├── utils/            # Utility functions
  └── App.tsx           # Main application component
```

## Technologies Used

- React
- TypeScript
- Material-UI
- Redux Toolkit
- Firebase
- Video.js
- React Router
- Axios

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Netflix for the inspiration
- TMDB for the movie data API
- Firebase for authentication and database services