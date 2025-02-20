# MelodyRoom

This project is a comprehensive music academy web application built using Next.js, Tailwind CSS, and various other modern web technologies. The app provides information about different music courses, instructors, and allows users to contact the academy.

You can visit the deployed app [here](https://music-academy-bice.vercel.app/).

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Scripts](#scripts)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Home Page**: Showcases featured courses, testimonials, and instructors.
- **Courses Page**: Lists all available music courses with details.
- **Contact Page**: Allows users to send messages to the academy.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Interactive UI**: Includes animations and hover effects for a better user experience.

## Technologies Used

- **Next.js**: React framework for server-side rendering and static site generation.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **Framer Motion**: Library for animations and gestures.
- **TypeScript**: Typed superset of JavaScript.
- **Simplex Noise**: Library for generating noise patterns.
- **clsx**: Utility for constructing `className` strings conditionally.
- **tailwind-merge**: Utility for merging Tailwind CSS classes.

## Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/AkashkumarChoudhary/MelodyRoom
    cd music-academy
    ```
2. Install dependencies:
    ```sh
    npm install
    # or
    yarn install
    ```
3. Run the development server:
    ```sh
    npm run dev
    # or
    yarn dev
    ```
4. Open your browser and navigate to [http://localhost:3000](http://localhost:3000).

## Project Structure

```
├── .eslintrc.json
├── .gitignore
├── next.config.mjs
├── package.json
├── postcss.config.js
├── public/
│   ├── courses/
│   │   ├── blues.jpg
│   │   ├── classical-music.jpg
│   │   ├── drumming.jpg
│   │   ├── edm.jpg
│   │   ├── guitar.jpg
│   │   ├── jazz.jpg
│   │   ├── music-prod.jpg
│   │   ├── piano.jpg
│   │   ├── song-writing.jpg
│   │   └── vocalist.jpg
│   ├── next.svg
│   └── vercel.svg
├── README.md
├── src/
│   ├── app/
│   │   ├── contact/
│   │   │   └── page.tsx
│   │   ├── courses/
│   │   │   └── page.tsx
│   │   ├── favicon.ico
│   │   ├── globals.css
│   │   ├── layout.tsx
│   │   └── page.tsx
│   ├── components/
│   │   ├── FeaturedSection.tsx
│   │   ├── Footer.tsx
│   │   ├── HeroSection.tsx
│   │   ├── Instructor.tsx
│   │   ├── TestimonialCard.tsx
│   │   ├── navbar.tsx
│   │   └── ui/
│   │       ├── 3d-card.tsx
│   │       ├── animated-tooltip.tsx
│   │       ├── background-beams.tsx
│   │       ├── card-hover-effect.tsx
│   │       ├── infinite-moving-cards.tsx
│   │       ├── meteors.tsx
│   │       ├── moving-border.tsx
│   │       ├── navbar-menu.tsx
│   │       ├── Spotlight.tsx
│   │       ├── sticky-scroll-reveal.tsx
│   │       └── wavy-background.tsx
│   ├── data/
│   │   └── music_course.json
│   └── utils/
│       └── cn.ts
├── tailwind.config.ts
└── tsconfig.json
```


## Scripts

- **dev**: Runs the development server.
- **build**: Builds the application for production.
- **start**: Starts the production server.
- **lint**: Runs ESLint to check for linting errors.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## License
This project is licensed under the MIT License.