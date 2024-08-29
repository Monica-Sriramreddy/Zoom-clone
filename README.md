# Zoom Clone

This project is a replica of Zoom, a widely used video conferencing tool, built with the latest Next.js and TypeScript. It enables users to securely log in, create meetings, and access various meeting functionalities such as recording, screen sharing, and managing participants.

## 📋 Table of Contents
- 🤖 [Introduction](#introduction)
- ⚙️ [Tech Stack](#tech-stack)
- 🔋 [Features](#features)
- 🤸 [Quick Start](#quick-start)
- 🕸️ [Assets & Code](#assets--code)
- 🚀 [More](#more)

## 🤖 Introduction
This project replicates the core features of Zoom, providing a seamless and secure video conferencing experience. It includes functionalities like meeting creation, user authentication, participant management, and more.

## ⚙️ Tech Stack
- **Next.js**
- **TypeScript**
- **Clerk**
- **getstream**
- **shadcn**
- **Tailwind CSS**

## 🔋 Features
- **Authentication:** Secure login and authorization using Clerk, supporting social sign-on and email/password methods.
- **New Meeting:** Quickly start a new meeting with configurable camera and microphone settings.
- **Meeting Controls:** Full control over meeting aspects, including recording, screen sharing, muting/unmuting, participant management, and more.
- **Exit Meeting:** Options for participants to leave a meeting or for the creator to end the meeting for all attendees.
- **Schedule Future Meetings:** Schedule meetings with specific details and access them on the 'Upcoming Meetings' page.
- **Past Meetings List:** View previously held meetings along with details and metadata.
- **View Recorded Meetings:** Access recordings of past meetings for review.
- **Personal Room:** Each user has a personal room with a unique meeting link for instant meetings.
- **Join Meetings via Link:** Join meetings created by others using a shared link.
- **Secure Real-time Functionality:** Real-time interactions with a focus on user privacy and data integrity.
- **Responsive Design:** Optimized for all devices with a fully responsive design.

## 🤸 Quick Start

### Prerequisites
Ensure you have the following installed on your machine:
- Git
- Node.js
- npm (Node Package Manager)

### Cloning the Repository
```bash
git clone https://github.com/adrianhajdin/zoom-clone.git
cd zoom-clone
```

### Installation
Install the project dependencies:
```bash
npm install
```

### Set Up Environment Variables
Create a new `.env` file in the root of your project and add the following content:

```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```

Replace the placeholder values with your actual credentials from Clerk and getstream.

### Running the Project
Start the development server:
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

