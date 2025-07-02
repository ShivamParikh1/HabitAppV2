# HabitAppV2

A modern habit tracking application built with React, Firebase, and Vite. HabitAppV2 helps users build positive habits and break negative ones with proven psychological methods and real-time progress tracking.

## Features

- **Build & Break Habits**: Choose from curated habits or create custom ones
- **Smart Tracking**: Daily completion tracking with streak counters
- **Custom Preferences**: Personalized settings for each habit
- **Progress Analytics**: Visual progress charts and success rates
- **Email Authentication**: Secure user accounts with email verification
- **Responsive Design**: Works seamlessly on mobile and desktop

## Live Demo

Visit the live application: [HabitAppV2 on GitHub Pages](https://yourusername.github.io/HabitAppV2/)

## Technology Stack

- **Frontend**: React 18, React Router
- **Backend**: Firebase (Authentication, Firestore)
- **Build Tool**: Vite
- **Styling**: Custom CSS with modern design principles
- **Deployment**: GitHub Pages

## Getting Started

### Prerequisites

- Node.js 16+ and npm
- Firebase account for backend services

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/HabitAppV2.git
cd HabitAppV2
```

2. Install dependencies:
```bash
npm install
```

3. Set up Firebase:
   - Create a new Firebase project at [Firebase Console](https://console.firebase.google.com)
   - Enable Authentication with Email/Password
   - Create a Firestore database
   - Copy your Firebase config to `src/firebase/config.js`

4. Start the development server:
```bash
npm run dev
```

5. Open [http://localhost:5173](http://localhost:5173) to view the app

### Building for Production

```bash
npm run build
```

The build files will be generated in the `dist` directory.

### Deploying to GitHub Pages

1. Update the `base` URL in `vite.config.js` to match your repository name
2. Build the project: `npm run build`
3. Deploy using GitHub Actions (configured in `.github/workflows/deploy.yml`)

## Project Structure

```
HabitAppV2/
├── public/
│   ├── index.html
│   └── 404.html
├── src/
│   ├── components/     # Reusable UI components
│   ├── contexts/       # React contexts for state management
│   ├── data/          # Static data and configurations
│   ├── firebase/      # Firebase configuration
│   ├── pages/         # Page components
│   ├── App.jsx        # Main app component
│   ├── main.jsx       # App entry point
│   └── index.css      # Global styles
├── .github/
│   └── workflows/
│       └── deploy.yml # GitHub Actions deployment
└── package.json
```

## Key Features

### Habit Management
- **Build Habits**: Water intake, meditation, exercise, reading, early wake-up
- **Break Habits**: Procrastination, excessive phone use, social media, junk food
- **Custom Preferences**: Personalized settings for each habit type

### Progress Tracking
- Daily completion tracking
- Streak counters (current and best)
- Weekly progress visualization
- Success rate analytics

### User Experience
- Clean, modern interface
- Mobile-first responsive design
- Smooth animations and transitions
- Intuitive navigation

## Firebase Setup

1. **Authentication**:
   - Enable Email/Password sign-in
   - Configure email verification templates

2. **Firestore Database**:
   - Create collections for users, habits, and preferences
   - Set up security rules for user data protection

3. **Configuration**:
   - Update `src/firebase/config.js` with your Firebase project credentials

## Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -am 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/yourusername/HabitAppV2/issues) page
2. Create a new issue with detailed information
3. Contact the development team

## Acknowledgments

- Firebase for backend services
- Unsplash for high-quality images
- React community for excellent documentation
- Contributors and testers

---

**HabitAppV2** - Transform your life, one habit at a time.