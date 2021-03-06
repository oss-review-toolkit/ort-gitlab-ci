# ORT GitLab Dashboard


This directory contains the code for ORT GitLab integration dashboard. The code was bootstrapped with
[Create React App](https://github.com/facebookincubator/create-react-app).

## Prerequisites

-   **Yarn** - Please see [yarnpkg.com](https://yarnpkg.com/en/) for installation instructions.

## Available Commands

### `yarn install`

Downloads and install dependencies.

### `yarn build`

Builds the `index.html` (used for debugging of the Web App) and `scan-report-template.html` in the `/build` directory.
The [Kotlin report code](../reporter/src/main/kotlin/reporters/WebAppReporter.kt) uses `scan-report-template.html` as a
template and injects scan results into it to create the final ORT Web App scan report.

### `yarn start`

Runs the app in the development mode.

Open [http://localhost:3000](http://localhost:3000) to view it in the browser. The page will reload if you make edits.
You will also see any lint errors in the console.

### `yarn lint`

Runs [ESLint](https://eslint.org/) to detect code styling issues in the `/src` directory.

### `yarn test`

Launches the test runner in the interactive watch mode.

## License

Copyright (C) 2021-2022 HERE Europe B.V.

See the [LICENSE](./LICENSE) file at the same level as this file.