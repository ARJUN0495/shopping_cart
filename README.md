# My Project

## Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

Make sure you have the following installed:
- [Node.js](https://nodejs.org/) : Required : **v14.16.0**
- [npm](https://www.npmjs.com/)

### Installation

1. **Clone the repository:**

    ```bash
    https://github.com/ARJUN0495/shopping_cart.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd your-repository-name
    ```

3. **Install the dependencies:**

    ```bash
    npm install
    ```

4. **Start the React development server:**

    ```bash
    npm start
    ```

5. **Run the JSON server:**

    Open a new terminal, navigate to the project directory api, then run:

    ```bash
    cd api
    json-server --watch data.json --port 3003
    ```

### Usage

After following the installation steps, your React app should be running on `http://localhost:3000`, and the JSON server should be running on `http://localhost:3003`.

### Additional Information

- **JSON Server**: This is used to simulate a REST API. It serves the data from `data.json` and runs on port 3003.
- **React App**: Your main application runs on port 3000. Make sure both the React app and JSON server are running concurrently.

For further details, refer to the documentation in the respective folders.
