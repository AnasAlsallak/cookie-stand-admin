# Cookie Stand Admin App - Solution

This repository contains the solution for the Cookie Stand Admin app, built using React, Next.js, and styled with Tailwind CSS.

## Author: Anas Alsallak

## Overview

The Cookie Stand Admin app is designed to manage cookie stands and their sales data. It allows users to add new cookie stands, view the sales data of the last created stand, and display a list of all cookie stands.

## Features

- The main page, `pages/Index.js`, displays a dashboard for managing cookie stands.
- The `<Head>` component sets the page title to "Cookie Stand Admin."
- The `<header>` component provides a navigation header with a logo and links.
- The `<main>` component contains a form for adding new cookie stands and a placeholder component showing the JSON string of the last created cookie stand.
- The `<footer>` component displays a footer with copyright information.

## Installation and Setup

To run the project locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory:

   ```bash
   cd cookie-stand-admin
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open your web browser and go to [http://localhost:3000](http://localhost:3000) to view the app.

## Project Structure

The project is structured as follows:

- `pages`: Contains the Next.js pages, including the main page (`Index.js`).
- `components`: Contains reusable React components used throughout the app.
- `styles`: Contains the Tailwind CSS configuration file and custom styles.

## Styling with Tailwind CSS

The app is styled using Tailwind CSS utility classes, which provide a quick and efficient way to apply styles to the components. Tailwind CSS is a highly customizable CSS framework, and its configuration can be found in the `tailwind.config.js` file.

## Stretch Goals

In addition to the basic features, the solution includes the following stretch goals:

- Components have been refactored to their own functions and files for better organization.
- Additional styling has been added to enhance the app's appearance.

## Contributions

Contributions to this project are welcome. If you have any suggestions or improvements, feel free to submit a pull request.

Thank you for checking out the Cookie Stand Admin App solution. If you have any questions or feedback, feel free to reach out.

Happy coding!
