# Journal App

A full-stack personal journaling application built with modern web technologies.

## Features

- Personal journal entries with rich text editing
- Collection organization for grouping related entries
- Mood tracking and analytics
- User authentication and secure data storage
- Responsive design for all devices

## Getting Started

### Environment Setup

Create a `.env` file in the root directory with the following variables:

```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/dashboard
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/dashboard

DATABASE_URL=

PIXABAY_API_KEY=

ARCJET_KEY=
```

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up your environment variables as shown above
4. Run the development server:
   ```bash
   npm run dev
   ```

## Tech Stack

- **Frontend**: Next.js 15, React 19, Tailwind CSS
- **Authentication**: Clerk
- **Database**: Prisma with Neon PostgreSQL
- **Security**: ArcJet
- **UI Components**: Shadcn UI, Radix UI
- **Rich Text Editor**: React Quill
- **Charts**: Recharts
