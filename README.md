# Traceform Demo Projects


![Traceform cli onboarding tool demonstrating easy setup of all 3 required tools from the traceform code to ui toolset](./.github/demo.gif "GIF showing traceform cli npm onboarding tool and highlighting a React button in Chrome from VS Code")


This repository contains four demo projects designed to showcase Traceform's capabilities. Each project is pre-configured without Traceform, allowing you to go through the setup process yourself.

## Prerequisites

Before you begin, ensure you have the following installed:

*   [Node.js](https://nodejs.org/) (which includes npm): If you don't have Node.js installed, download and install it from the official website using the provided link.

## Setting Up a Demo Project

Follow these steps to set up and run Traceform with any of the demo projects:

1.  **Choose a Demo Project:** Select one of the `Demo-XX` folders (e.g., `Demo-01`).

2.  **Navigate to the Project Directory:** Open your terminal or command prompt and change to the chosen project's directory. Replace `Demo-XX` with the actual folder name (e.g., `Demo-01`, `Demo-02`, `Demo-03`, `Demo-04`).
    ```bash
    cd Demo-XX
    ```

3.  **Install Project Dependencies:** Install the necessary packages for the demo project.
    ```bash
    npm install
    ```

4.  **Install Traceform Dependency:** Install the required `@types/node` package.
    ```bash
    npm install --save-dev @types/node
    ```

5.  **Run Traceform Onboarding:** Start the Traceform onboarding process. This interactive tool will guide you through setting up the necessary and required components (Browser Extension, Babel Plugin, VS Code Extension).
    ```bash
    npx @lucidlayer/traceform-onboard check
    ```
    Follow the prompts provided by the onboarding tool.

6.  **Run the Demo Project:** Once Traceform setup is complete, start the demo application's development server.
    ```bash
    npm run dev
    ```

7.  **View the Project:** Open your web browser and navigate to the local address provided in the terminal (usually `http://localhost:5173` or similar).

You can now explore the demo project and see Traceform in action! Repeat these steps for any other demo project you wish to try.
