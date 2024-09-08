
# Portfolio: React Project with Vite

This project is a **React** application bootstrapped with **Vite**. It offers a fast development environment and optimized build for production.

## Getting Started

To get started with the project, follow these steps:

### Prerequisites

Make sure you have the following installed on your machine:
- **Node.js** (v14.x or higher)
- **npm** (v6.x or higher) or **yarn**

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/eshu-bade/portfolio.git
    ```

2. Navigate into the project directory:
    ```bash
    cd portfolio
    ```

3. Install the dependencies:
    ```bash
    npm install
    ```
    Or if you prefer using **yarn**:
    ```bash
    yarn install
    ```

### Running the Development Server

To start the local development server:

```bash
npm run dev
```

This will start the app on `http://localhost:5173/` by default.

## Available Scripts

In the project directory, you can run the following commands:

### `npm run dev`

Runs the app in development mode. Open [http://localhost:5173](http://localhost:5173) to view it in the browser.

The page will reload if you make edits, and you will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `dist` folder. The build is optimized for the best performance.

### `npm run preview`

After building, you can run this command to locally preview the production build.

### `npm run deploy`

Deploys the project to GitHub Pages (or another specified platform using the `gh-pages` package). Make sure to build the project before running this command.

## Deployment

To deploy the app:

1. Build the project:
    ```bash
    npm run build
    ```

2. Deploy the build using the following command:
    ```bash
    npm run deploy
    ```

Make sure the `deploy` script in your `package.json` is set up to deploy from the `dist` directory. (This project uses `gh-pages` for deployment.)
