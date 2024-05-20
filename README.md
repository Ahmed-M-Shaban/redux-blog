# Redux Blog

A blog application built with React and Redux, using `json-server` for local data management.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Contributors](#contributors)
- [License](#license)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Ahmed-M-Shaban/redux-blog.git
    cd redux-blog
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Install `json-server` globally if not already installed:
    ```bash
    npm install -g json-server
    ```

## Usage

1. Start the `json-server` to serve the data from `data.db.json`:
    ```bash
    json-server --watch data/data.db.json --port 5000
    ```

2. Start the React development server:
    ```bash
    npm start
    ```

3. Open your browser and navigate to `http://localhost:3000` to view the application.

## Features

- Display a list of blog posts.
- Add, edit, and delete blog posts.
- View detailed information about individual blog posts.
- Simple, responsive design.

## Technologies Used

- React
- Redux
- json-server
- CSS
- JavaScript
- HTML

## Contributors

- Ahmed M. Shaban

## License

This project is licensed under the MIT License.
