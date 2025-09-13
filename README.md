# Background Project info

The project involves processing and displaying election results from a provided database containing dummy data for the 2011 elections. The database includes polling units, wards, LGAs (Local Government Areas), and states, with a focus on Delta State (state_id: 25). The database is accessible at:

[Database Link](https://drive.google.com/file/d/0B77xAtHK1hd4Ukx6SHpqTkd6TWM/view?resourcekey=0-Uwrx8FyB_HnpYdskhHfYTw)

## Key Features

Display results for individual polling units.

Summarize total results for all polling units under a selected LGA.

Provide a form to store results for a new polling unit.

User-friendly interface with autocomplete and select boxes.


**URL**: https://bincomtask.vercel.app/



**Setup Instructions**

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite: A next-generation build tool for fast development and optimized builds.
- TypeScript: Adds static typing to JavaScript, enhancing code quality and maintainability.
- React: A popular JavaScript library for building dynamic and reusable user interfaces.
- shadcn-ui: A collection of accessible and customizable UI components for React.
- Tailwind CSS: A utility-first CSS framework for rapid and responsive styling.

## Usage

- Polling Unit Results: Navigate to the "Polling Unit" page, enter a polling unit ID, and view the detailed results.

- LGA Results: Go to the "LGA Results" page, select an LGA from the dropdown, and see the summed total of all polling units under that LGA.

- New Polling Unit: Use the "New Polling Unit" page to input results for a new polling unit, which will be stored in the database.

## Features
