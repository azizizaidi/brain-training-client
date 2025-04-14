# 🧠 Brain Training Client

A modern React frontend for a comprehensive brain training application that develops both left and right brain capabilities.

## 📋 Overview

This React-based frontend provides an engaging, interactive user interface for cognitive training exercises. Designed with best practices in UX/UI, it delivers a seamless experience for users looking to enhance various cognitive functions through targeted training.

## 🚀 Features

- **Interactive Exercises**: Engaging activities for various cognitive domains
- **Performance Dashboard**: Visualize progress and improvements
- **Adaptive Training**: Exercises that adjust to your skill level
- **Personalized Programs**: Custom training regimens based on goals
- **Cross-Device Compatibility**: Responsive design for all devices
- **Real-time Feedback**: Immediate insights on performance

## 🛠️ Technology Stack

- **Framework**: React with TypeScript
- **State Management**: Redux Toolkit
- **Styling**: Material UI / Styled Components
- **Data Visualization**: D3.js / Recharts
- **API Communication**: Axios
- **Testing**: Jest and React Testing Library
- **Build Tools**: Webpack, Babel

## 🔧 Installation

### Prerequisites

- Node.js (v16+)
- npm or yarn
- Brain Training API running locally or accessible endpoint

### Setup

```bash
# Clone the repository
git clone https://github.com/azizizaidi/brain-training-client.git

# Navigate to project directory
cd brain-training-client

# Install dependencies
npm install
# or
yarn install

# Create environment file
cp .env.example .env.local
# Edit .env.local with your API endpoint

# Start development server
npm start
# or
yarn start
```

The application will be available at `http://localhost:3000`

## 📂 Project Structure

```
src/
├── components/       # Reusable UI components
├── pages/            # Application pages
├── hooks/            # Custom React hooks
├── store/            # Redux store configuration
├── api/              # API client and services
├── utils/            # Helper functions and utilities
├── types/            # TypeScript type definitions
├── assets/           # Static assets (images, fonts)
├── styles/           # Global styles and themes
└── App.tsx           # Main application component
```

## 🧠 Exercise Types

| Category | Examples |
|----------|----------|
| Memory | Pattern recall, sequence memorization |
| Logical Thinking | Puzzles, number sequences |
| Spatial Reasoning | 3D manipulation, mental rotation |
| Creative Thinking | Pattern creation, divergent thinking |
| Language | Word associations, verbal reasoning |
| Processing Speed | Quick reaction challenges |

## 🎨 UI/UX Design Philosophy

- **Distraction-free**: Clean interface that focuses attention on exercises
- **Encouraging feedback**: Positive reinforcement during training
- **Intuitive navigation**: Simple flows between different sections
- **Accessibility**: Designed for users of all abilities
- **Gamification**: Elements that boost engagement and motivation

## 📱 Responsive Design

The application is fully responsive and optimized for:
- Desktop computers
- Tablets
- Mobile phones
- Large displays

## 🔄 Integration with API

The client communicates with the [Brain Training API](https://github.com/azizizaidi/brain-training-api) for:
- User authentication
- Fetching exercise content
- Submitting performance data
- Retrieving analytics and insights

## 🧪 Testing

```bash
# Run tests
npm test
# or
yarn test

# Run tests with coverage
npm test -- --coverage
# or
yarn test --coverage
```

## 📦 Building for Production

```bash
# Create production build
npm run build
# or
yarn build

# The build output will be in the 'build' directory
```

## 🚀 Deployment

The application can be deployed to various platforms:

- **Vercel/Netlify**: Connect your GitHub repository for automatic deployments
- **AWS S3/CloudFront**: For scalable static website hosting
- **Docker**: Container-based deployment available

## 🚧 Development Roadmap

- [x] Project setup and core architecture
- [x] Basic UI components and styling
- [ ] Initial exercise implementations
- [ ] User authentication and profiles
- [ ] Performance tracking dashboard
- [ ] Advanced visualization components
- [ ] Offline capabilities
- [ ] AI-driven recommendations

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Team

- **Azizi Zaidi** - *Backend Engineer* - [GitHub](https://github.com/azizizaidi)

---

*This project is part of a larger brain training platform that includes a NestJS backend API.*