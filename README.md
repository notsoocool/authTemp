# Authentication Template with Next.js and Clerk

This README provides steps to create a sign-in/sign-out authentication system using Next.js and Clerk.

## Table of Contents

1. [Setup](#setup)
2. [Installation](#installation)
3. [Configuration](#configuration)
4. [Running the Application](#running-the-application)

## Setup

1. **Create a Next.js Project:**

    ```bash
    npx create-next-app@latest auth-template
    cd auth-template
    ```

2. **Initialize a Clerk Project:**
    - Sign up at [Clerk](https://clerk.dev) if you don’t have an account.
    - Create a new project in the Clerk dashboard.
    - Take note of your Clerk frontend API key.

## Installation

1. **Install Clerk:**
    ```bash
    npm install @clerk/nextjs
    # or
    yarn add @clerk/nextjs
    ```

## Configuration

1. **Add Environment Variables:**
   Create a `.env.local` file in the root of your project and add your Clerk API keys:

    ```env
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
    CLERK_SECRET_KEY=
    NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-upy>
    ```

## Running the Application

1. **Start the Development Server:**

    ```bash
    npm run dev
    # or
    yarn dev
    ```

2. **Open the Application:**
   Navigate to [http://localhost:3000](http://localhost:3000) in your web browser.

## References

-   [Next.js Documentation](https://nextjs.org/docs)
-   [Clerk Documentation](https://docs.clerk.dev/)
-   [Vercel Deployment Guide](https://vercel.com/docs/concepts/deployments)

This completes the setup and configuration for using Clerk in a Next.js project. If you have any questions or run into issues, refer to the official documentation or seek assistance from the Clerk community.
