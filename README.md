# Techarro Software Solutions Website

This is a multi-page website for Techarro Software Solutions, built with HTML and Tailwind CSS, and optimized for deployment on Vercel.

## Pages:

*   `index.html`: Home page featuring company introduction and a list of services with placeholder descriptions and images.
*   `contact.html`: A contact form page where users can submit their details. The form sends a POST request to `ntfy.sh/techarro` upon submission.
*   `404.html`: A custom 'Page Not Found' page.

## Features:

*   **Responsive Design**: Built using Tailwind CSS for a mobile-first approach.
*   **Interactive Services Section**: Service items animate into view as you scroll.
*   **Contact Form**: Collects user details and sends them to a `ntfy.sh` topic.
*   **Vercel Optimized**: Includes `vercel.json` for routing and redirects.

## How to View Locally:

1.  **Save Files**: Save all the provided files into a single directory.
2.  **Open `index.html`**: Simply open the `index.html` file in your web browser.
3.  **Use `npm start`**: If you have Node.js and npm installed, navigate to the directory in your terminal and run `npm install` (if you want to install any future dependencies, though none are strictly needed for this static site) then `npm start`. This will open `index.html` in your default browser.

## Deployment on Vercel:

This site is set up to be easily deployed on Vercel.

1.  **Create a New Project**: Connect your Git repository (GitHub, GitLab, Bitbucket) to Vercel.
2.  **Configure Project**: Vercel should automatically detect this as a static site.
3.  **Deploy**: Push your code to your repository, and Vercel will build and deploy it. The `vercel.json` file handles the routing and redirects as specified.