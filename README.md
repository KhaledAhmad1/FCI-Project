# FCI College Portal

A comprehensive web application for students, providing easy access to lecture schedules, professor availability, campus navigation, college news, regulations, and a chatbot for assistance.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contact](#contact)

## Features

- **Lecture Schedule:** View and manage your lecture schedule.
- **Professor Availability:** Check the availability of professors for consultations.
- **Campus Guidance:** Interactive map for navigating within the college.
- **College News:** Stay updated with the latest news and announcements.
- **Chatbot Assistance:** Ask questions and get instant answers from the chatbot.
- **College Regulations:** Access the college regulations and policies.

## Demo

Include a link to a live demo of your project, if available. This could be a hosted version or a demo video.

- [Live Demo](https://example.com)

## Installation

To set up the project locally, follow these steps:

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (version 20.x or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js) or [Yarn](https://yarnpkg.com/) (optional, but recommended)

### Getting Started

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/college-portal.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd college-portal
    ```

3. **Install dependencies:**

    Depending on your package manager, run one of the following commands to install all necessary dependencies:

    Using npm:

    ```bash
    npm install
    ```

    Or using Yarn:

    ```bash
    yarn install
    ```

4. **Run the Development Server:**

    After setting up the environment variables, start the Next.js development server:

    Using npm:

    ```bash
    npm run dev
    ```

    Or using Yarn:

    ```bash
    yarn dev
    ```

5. **Open Your Browser:**

    Visit [http://localhost:3000](http://localhost:3000) to see your Next.js application running locally.

### Environment Variables

Rename the `.env.example` file to `.env.local` and update it with your environment-specific variables. These might include API keys, database connections, etc. Make sure not to expose sensitive information.

```bash
cp .env.example .env.local
