# React MiniBlog

A lightweight blogging platform built with React, Firebase, and React Router.

![React](https://img.shields.io/badge/React-18.3.1-blue)
![Firebase](https://img.shields.io/badge/Firebase-11.2.0-orange)
![React Router](https://img.shields.io/badge/React_Router-7.1.3-lightgrey)
![React Router](https://img.shields.io/badge/dotenv-16.4.7-white)

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Configuration](#configuration)

## Features

- User authentication (Login/Registration)
- Create and manage blog posts
- Responsive design
- Protected routes for authenticated users
- Context API for state management
- Firebase backend integration
- Navigation bar and footer
- Pages:
  - Home: Display all blog posts
  - About: Project information
  - Dashboard: User's personal space
  - Login/Register: Authentication forms
  - Create Post: Post creation interface

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/miniblog.git
   cd miniblog

   ```

## Install dependencies

`npm install`

## Configuration

Create a Firebase project at Firebase Console

Enable Authentication (Email/Password method)

Create a .env file in the root directory with your Firebase credentials:

> [!TIP]
> you can use the .env-example

```
API_KEY=your-firebase-api-key
AUTH_DOMAIN=your-firebase-auth-domain
PROJECT_ID=your-project-id
STORAGE_BUCKET=your-storage-bucket
MESSAGING_SENDER_ID=your-messaging-sender-id
APP_ID=your-app-id
```

## Start development server

`npm run dev `
