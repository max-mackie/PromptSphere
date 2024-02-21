# Next.js AI Prompt Sharing Platform

Welcome to my AI Prompt Sharing Platform, built with Next.js, MongoDB, NextAuth, and TailwindCSS. This application serves as a modern platform where users can explore, share, and manage AI-generated prompts, leveraging the latest web technologies for a seamless user experience.

## Table of Contents

- [Introduction](#introduction)
- [Technology Stack](#technology-stack)
- [Features](#features)
- [Getting Started](#getting-started).
- [To-do / Next Features](#to-do--next-features).
- [Deployment on Vercel](#deployment-on-vercel)
- [Resources and Links](#links)

## Introduction

This project is a full-stack application that demonstrates the capability of Next.js 14 in creating a dynamic and interactive web application. The platform enables users to discover AI prompts shared by the community, contribute their own, and interact with others through profile exploration and prompt management.

## Technology Stack

- **Next.js**: A React framework that provides server-side rendering and static site generation to build optimized web applications.
- **MongoDB**: A document-based database used to store user and prompt data efficiently.
- **NextAuth**: An authentication solution for Next.js applications, providing secure and scalable login mechanisms.
- **TailwindCSS**: A utility-first CSS framework for creating custom designs without leaving your HTML.

## Features

- **Responsive Design**: Ensures a great user experience across devices with different screen sizes.
- **CRUD Operations**: Users can create, read, update, and delete prompts, offering full control over their content.
- **Profile Pages**: Dedicated pages for users to showcase their prompts and for others to explore.
- **Tag-Based Search**: Enables filtering prompts by specific tags for easier discovery.
- **Copy to Clipboard**: Allows users to easily copy prompts for their use.
- **Secure Authentication**: Utilizes Google authentication via NextAuth for a seamless and secure login experience.

## Getting Started

### Prerequisites

- Git
- Node.js
- npm

### Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your_username/project_next_14_ai_prompt_sharing.git
cd project_next_14_ai_prompt_sharing
npm install
```

### Environment Setup
Create a `.env` file at the root of your project with the following content, replacing placeholders with your actual credentials:

```env
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your_nextauth_secret
GOOGLE_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
MONGODB_URI=your_mongodb_uri
```

### Running the Project
Start the development server:

```bash
npm run dev
```

Navigate to http://localhost:3000 to view the application.

## To-do / Next Features
- [ ] Implement Search
  - Search by prompt
  - Search by tag
  - Search by username
- [ ] Implement Click on tag
- [ ] Implement View other profiles

## Deployment on Vercel

The AI Prompt Sharing Platform is deployed on Vercel, a cloud platform for static sites and Serverless Functions that fits perfectly with Next.js projects. Vercel simplifies the deployment process, automatically builds your project, and serves it globally with minimal configuration.


## Resources and Links
- [Next.js Documentation](https://nextjs.org/docs)
- [TailwindCSS Documentation](https://tailwindcss.com/docs)
- [NextAuth Documentation](https://next-auth.js.org/)
- [MongoDB Documentation](https://docs.mongodb.com/)
