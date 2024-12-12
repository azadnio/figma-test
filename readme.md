# Figma test project (Webpack SCSS) 

This project uses Webpack to bundle JavaScript and process SCSS into CSS. The project includes a simple setup for processing SCSS files, bundling JavaScript, and serving the files for development. Follow the instructions below to set up and run the project.

---

## Prerequisites

Before you begin, make sure you have the following installed:

- **Node.js** and **npm** (Node Package Manager)
 - You can download and install them from [Node.js official website](https://nodejs.org/).
  
- **Git** (if you are cloning the project from a GitHub repository)
 - Install Git from [Git's official website](https://git-scm.com/).

---

## Installation

### 1. Clone the Repository (if applicable)

If you're working with a cloned repository, clone it to your local machine:

git clone https://github.com/username/repository-name.git
cd repository-name` 

### 2. Install Dependencies

Run the following command to install all the project dependencies:

`npm install` 

This will install Webpack, Webpack CLI, SCSS loaders, and other required dependencies.

----------

## Development

### 1. Run the Development Server

To run the project locally and see it in action, use the following command to start the development server:


`npm start` 

This will:

-   Start a local development server.
-   Open the project in your default browser at `http://localhost:9000`.
-   Automatically watch for changes in SCSS and JavaScript files and recompile when changes are detected.

### 2. Development Features

-   **SCSS Processing**: Webpack will automatically process your SCSS files and generate corresponding CSS.
-   **Hot Module Replacement**: When you make changes to your code, the server will automatically reload the changes without refreshing the entire page.

----------

## Build for Production

To prepare the project for production (minify and bundle the files), use the following command:

bash

Copy code

`npm run build` 

This will:

-   Process SCSS and bundle it into a single CSS file.
-   Bundle JavaScript files into a single `bundle.js` file.
-   Place all generated files into the `docs/` folder.

You can deploy the contents of the `docs/` folder 