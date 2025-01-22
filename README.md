# Next.js 15 App Directory: Silent Server Component Data Fetch Errors

This repository demonstrates an uncommon error in Next.js 15's `app` directory when fetching data within server components.  If the data fetch fails (e.g., network error), the application might crash silently without clear error messages on the client-side.

The `serverComponentBug.js` file showcases the problematic code, and `serverComponentBugSolution.js` provides a robust solution using error boundaries and improved error handling.  The README explains the issue and how to reproduce it.

## Reproduction Steps
1. Clone this repository.
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev`
4. Observe the behavior when the data fetch fails (simulated in the example).