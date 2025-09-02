# Shipify Logistics

An intelligent logistics platform for modern supply chains. This application includes an advanced tool to search, manage, and understand global tariffs, along with various calculators and a customer portal for delivery management.

This project was bootstrapped with Vite and uses React, TypeScript, and Tailwind CSS.

## Features

- **Global Tariff Directory**: Search and view detailed tariffs for sea ports and airports worldwide.
- **AI-Powered Explanations**: Use Gemini AI to get simple, easy-to-understand summaries of complex tariff documents.
- **Logistics Calculators**:
    - Instant Freight Quote
    - Load & Stuffing Calculator
    - Bollard Pull Calculator
    - Sea Fastening Calculator
- **Vessel Tracking**: Search for vessels by name or IMO number to see their current status and technical details.
- **Live Map**: View a global map of live marine traffic.
- **Customer Portal**: A multi-role dashboard for Merchants, Agents, and Admins to manage deliveries.
- **AI Chatbot**: A helpful assistant to answer questions about logistics and shipments.

## Getting Started

### Prerequisites

- Node.js (v18 or later recommended)
- A package manager like npm, yarn, or pnpm

### Environment Setup

This project requires a Gemini API key to power its AI features.

1.  Create a file named `.env` in the root of the project.
2.  Add your API key to this file:

    ```
    API_KEY=YOUR_GEMINI_API_KEY
    ```

    The application is configured to load this key via Vite.

### Installation & Running

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/sanjaybsarode/Logistics-Website-APP.git
    
    cd Logistics-Website-APP
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Run the development server:**
    ```bash
    npm run dev
    ```
    The application will be available at `http://localhost:5173` (or another port if 5173 is in use).

## Deployment

This application has been configured for easy deployment. **You do not need to edit any files manually.**

### Option 1: Vercel (Recommended)

Vercel is the simplest way to deploy this project.

1.  **Fork this repository** to your own GitHub account.
2.  Go to [Vercel](https://vercel.com/new) and import your forked repository. Vercel will automatically detect that it is a Vite project.
3.  **Configure Environment Variables**: In the Vercel project settings, add an environment variable named `API_KEY` and set its value to your Gemini API key.
4.  Click **Deploy**. Vercel will automatically use the correct `npm run build` command and deploy your site.

### Option 2: GitHub Pages

The project is already configured for deployment to GitHub Pages.

1.  Make sure the `homepage` URL in your `package.json` is correct. It is currently set to: `"https://sanjaybsarode.github.io/Logistics-Website-APP"`. You may need to change `sanjaybsarode` to your GitHub username.

2.  Run the deploy script from your terminal:
    ```bash
    npm run deploy
    ```
    This single command builds the app with the correct paths and pushes it to the `gh-pages` branch for you.

3.  Go to your repository **Settings > Pages**. Under "Build and deployment", ensure the source is set to **Deploy from a branch** and the branch is **`gh-pages`** with the `/ (root)` folder.

Your site will be live in a few minutes.