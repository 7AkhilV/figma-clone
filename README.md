# Figma Clone

Welcome to the Figma Clone! This project is a web-based design tool inspired by Figma, built using Next.js and React. It allows users to create, edit, and collaborate on design projects in real-time.

## Features

- **Collaborative Editing**: Multiple users can work on the same design simultaneously.
- **Intuitive UI**: A user-friendly interface similar to Figma, making it easy to create and manage designs.
- **Responsive Design**: Works seamlessly on both desktop and mobile devices.
- **Comments and Feedback**: Users can leave comments on designs for better collaboration.
  
## Tech Stack

This project is built with the following technologies:

- **Next.js**: A React framework for server-side rendering and static site generation.
- **React**: A JavaScript library for building user interfaces.
- **Tailwind CSS**: A utility-first CSS framework for styling components.
- **Liveblocks**: For real-time collaborative features.
- **Fabric.js**: A framework for working with HTML5 canvas.

## Getting Started

To get started with the project, clone the repository and install the dependencies:

```bash
git clone https://github.com/7AkhilV/figma-clone.git
cd figma-clone
npm install
```

### Environment Variables

Create a `.env` file in the root of the project and add the following line:

```bash
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=your_liveblocks_public_key_here
```
Replace `your_liveblocks_public_key_here` with your actual Liveblocks public key.

### Running the Development Server

To start the development server, run:

```bash
npm run dev
```

Open your browser and navigate to `http://localhost:3000`.

### Building for Production

To build the project for production, run:

```bash
npm run build
```

Then start the production server with:

```bash
npm run start
```

## Scripts

- `dev`: Starts the development server.
- `build`: Builds the application for production.
- `start`: Starts the application in production mode.
- `lint`: Runs ESLint to check for code quality issues.

## Demo

https://github.com/user-attachments/assets/1d9d0367-c462-4380-b68a-efb8714054b1

