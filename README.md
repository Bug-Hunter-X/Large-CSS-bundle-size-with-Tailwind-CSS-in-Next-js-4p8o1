# Large CSS Bundle Size with Tailwind CSS in Next.js

This repository demonstrates a common issue encountered when using Tailwind CSS in Next.js applications: bloated CSS bundle sizes due to improper purging or optimization.  The issue leads to slow initial load times and a negatively impacted user experience.  The solution demonstrates techniques for optimizing and minimizing bundle size using Tailwind's purge feature effectively.  Pull requests and suggestions are welcome!

## Setup

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the development server.

## Bug Reproduction

The file `tailwindBug.js` shows an example of inefficient Tailwind CSS usage that contributes to a large CSS bundle size. Observe the bundle size in your browser's developer tools. 

## Solution

The `tailwindSolution.js` file demonstrates solutions such as refined `tailwind.config.js` configuration to correctly purge unused styles and optimize the process.