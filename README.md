# SoundGrid

A web based platform application for musicians to organize their songs, manage setlists, and keep track of song information

## About the Project

Musicians often struggle to coordinate jam sessions, organize gig setlists, and keep track of songs, including their tunings, tempos, arrangements, and individual parts. Currently, most musicians use applications such as spreadsheets, messaging apps, and separate music applications, making collaboration unnecessarily difficult.

SoundGrid aims to solve this problem by incorporating these features into a single centralized platform, where band members can manage songs, organize rehearsals, share notes, and track their band's progress

## MVP Features

The initial version of SoundGrid will focus on the following features:

- **Song Library:** Create, view, update, and delete songs
- **Song Attributes:** Store information such as tempo (BPM), key, instruments, difficulty, and notes for each song
- **Playlist Management:** Create playlists and setlists using songs from the user's song library
- **User Authentication:** Allow users to register, log in, and manage their accounts

## Future Plans (V2.0+)

Features planned for future versions include:

- Collaborative playlists that allow multiple users or bands to manage setlists together.
- Calendar integration for scheduling rehearsals and tracking gig dates.
- Practice tracking to monitor progress toward individual practice goals.

## Tech Stack

| Technology              | Purpose                                   |
| ----------------------- | ----------------------------------------- |
| React                   | Frontend development                      |
| TypeScript              | Programming Language for the Frontend     |
| Vite                    | Development environment and build tool    |
| Chakra UI               | UI component styling                      |
| Firebase Authentication | User authentication                       |
| Cloud Firestore         | Database and data storage                 |
| Firebase Hosting        | Application/Hosting deployment            |
| React Router            | Website navigation                        |
| Git & GitHub            | Version control and repository management |

## Project Structure

```text
SoundGrid/
├── docs/
│   ├── SoundGrid - Architecture Diagram.drawio
│   ├── SoundGrid - Architecture Diagram.png
│   └── SoundGrid - Eisenhower Matrix.pdf
├── public/
├── src/
├── README.md
├── package.json
├── package-lock.json
├── index.html
├── eslint.config.js
├── tsconfig.json
├── tsconfig.app.json
├── tsconfig.node.json
└── vite.config.ts
```

## Getting Started

### Prerequisites

- Node.js
- npm
- Git
- A Firebase project (made from Firebase console)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/AdithManu/SoundGrid
```

2. Navigate into the project directory:

```bash
cd SoundGrid
```

3. Install dependencies:

```bash
npm install
```

5. Start the development server:

```bash
npm run dev
```

6. Open the local URL displayed in your terminal, usually:

```text
http://localhost:5173/
```

## Project Status

**Currently in development.**

The initial project environment and technology stack are being configured. Core MVP functionality will be implemented eventually.
