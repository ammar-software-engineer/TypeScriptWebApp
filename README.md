# TypeScriptWebApp

## Description
This project is a simple web application built with TypeScript. It demonstrates basic TypeScript setup, including compilation, execution, and testing with Jest.

## Technologies Used
- TypeScript
- Node.js
- Jest (for testing)

## Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/YOUR_USERNAME/TypeScriptWebApp.git
    cd TypeScriptWebApp
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```

## Usage

### Build the project
To compile the TypeScript code into JavaScript:
```bash
npm run build
```
This will create a `dist` folder containing the compiled `app.js` file.

### Start the application
To run the compiled JavaScript application:
```bash
npm start
```
This will execute `dist/app.js` and print "Hello, TypeScript!" to the console.

### Run Tests
To execute the unit tests using Jest:
```bash
npm test
```
This will run `src/app.test.ts` and report the test results.

## Project Structure

```
.
├── README.md
├── package.json
├── src
│   ├── app.test.ts
│   └── app.ts
└── tsconfig.json
```
