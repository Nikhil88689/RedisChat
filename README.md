# Redis Chat Application

A real-time chat application built with Next.js, React, and Redis.

## Overview

This application is a modern, real-time chat platform that utilizes Redis for message storage and real-time updates. The app features a clean, responsive UI and supports multiple chat rooms, user authentication, and more.

## Features

- **Real-time messaging**: Instantly send and receive messages
- **User authentication**: Secure login with Kinde Auth
- **Responsive design**: Works on desktop and mobile devices
- **Emoji support**: Express yourself with emoji reactions
- **Dark/Light mode**: Choose your preferred theme
- **User presence**: See who's online
- **File sharing**: Share images and files via Cloudinary integration
- **Notification sounds**: Get alerted to new messages

## Tech Stack

- **Frontend**: React 18, Next.js 14
- **Styling**: Tailwind CSS, Radix UI components
- **State Management**: Zustand
- **Real-time Updates**: Pusher
- **Database**: Upstash Redis
- **Authentication**: Kinde Auth
- **File Storage**: Cloudinary
- **Deployment**: Vercel (recommended)

## Getting Started

### Prerequisites

- Node.js 18+ and npm/yarn
- Redis database (Upstash Redis recommended)
- Pusher account
- Kinde Auth account
- Cloudinary account

### Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/redis-chat-app.git
cd redis-chat-app
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
Copy the `.env.sample` file to `.env.local` and fill in your credentials:
```bash
cp .env.sample .env.local
```

Required environment variables:
- Redis connection details
- Pusher credentials
- Kinde Auth credentials
- Cloudinary credentials

4. Run the development server
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Project Structure

- `/src/app` - Next.js App Router pages and layouts
- `/src/components` - Reusable React components
- `/src/lib` - Utility functions and configurations
- `/src/db` - Database models and connections
- `/src/actions` - Server actions for data mutations
- `/src/store` - Zustand state management

## Deployment

The application can be easily deployed to Vercel:

```bash
npm run build
vercel
```

Make sure all environment variables are properly set in your Vercel project settings.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [Next.js Documentation](https://nextjs.org/docs)
- [Upstash Redis Documentation](https://docs.upstash.com)
- [Kinde Auth Documentation](https://kinde.com/docs)
- [Pusher Documentation](https://pusher.com/docs) 
