<p align="center"><img src="https://github.com/seyyidmcelik/photos/blob/main/smc-trello/logo.png" width="400" alt="Laravel Vue Logo"></p>

# Next JS, SMC Trello Application

## Overview

The SMC Trello app is a web application built using Next.js. It allows users to create their teams and manage them. They can invite other users to the team, assign a role, create a board, and they can observe the project status with kanban boards.

### Visit and explore the [smc-trello](https://smc-trello.vercel.app)

## Features

- **User Authentication**: Clerk
- **Payment System**: Stripe
- **Store Management**: Zustand
- **Style**: Tailwind
- **Database**: MySQL and Prisma.
- **And more...**

## Prerequisites

- [Node.js](https://nodejs.org/) for Next.js dependencies.

## Installation

   ```
   git clone https://github.com/seyyidmcelik/smc-trello
   ```

#### Install Laravel dependencies

```
cd smc-trello
npm install
```

#### List of Environment Variables You Need

```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

DATABASE_URL=

NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=

STRIPE_API_KEY=

STRIPE_WEBHOOK_SECRET=

NEXT_PUBLIC_APP_URL=
```

#### Start the development server

```
npm run dev
```
