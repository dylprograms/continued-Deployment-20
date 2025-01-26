# continued-Deployment-20

## Description

A full-stack application that follows a CI/CD pipeline with GitHub Actions for testing and deployment.

* [Deployed-Site](https://continued-deployment-20-web-service.onrender.com)
* [github-gist](https://gist.github.com/dylprograms/d944b46250830554afd9de18b0d08910)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents
* [Installation](#Installation)
* [Usage](#Usage)
* [Contributing](#Contributing)
* [Tests](#Tests)
* [GitHub Actions](#GitHub-Actions)
* [License](#License)
* [Questions](#Questions)

## Installation

1. Clone the repository:

    git clone https://github.com/dylprograms/continued-Deployment-20.git


2. Navigate to the project directory:


3. Install dependencies:

    npm run render-build


## Usage

1. Run the application in development mode:

    npm start


2. Open the application in your browser (usually at `http://localhost:3001`).

## Contributing

To contribute to this project:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to your branch (`git push origin feature/your-feature-name`).
5. Create a pull request to the `develop` branch.

## Tests

GitHub Actions will run tests automatically upon creating a pull request to the `develop` branch.

## GitHub Actions

1. **Pull Request to Develop Branch**: 
   - When a new feature is uploaded, create a pull request to the `develop` branch.
   - A GitHub Action will execute Cypress component tests.
   
2. **Test Results**: 
   - After tests are completed, the results will be displayed on GitHub Actions.

3. **Push to Main Branch**: 
   - After merging the pull request to `develop`, push the changes to the `main` branch.
   - A GitHub Action will automatically trigger the deployment to Render.

## License

This project is licensed under the [MIT](https://opensource.org/licenses/MIT) license.

## Questions

If you would like to contact me, please use my email or GitHub username: [dylyoungprograms](https://github.com/dylprograms), dlyoungworking@gmail.com
