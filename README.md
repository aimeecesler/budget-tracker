# # BUDGET TRACKER

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

The purpose of this application is to allow the user to track deposits and purchases with their budget both online and offline in the app.

![Main](readmeimg.PNG)

---

## Table of Contents

- [Installation](#installation)
- [Usage](#Usage)
- [Building the Application](#building-the-application)
- [Acceptance Criteria](#acceptance-criteria)
- [Credits](#credits)
- [Resources](#resources)
- [Contact](#contact)
- [Links](#Links)
- [License](#license)

---

## Installation

1. Follow the GitHub Repository Link in the [links](#Links) section below.
1. Clone the repository using an SSH key.
1. Open GitBash and use "git clone" to clone the repository.
1. Run npm install to install associated modules.

---

## Usage

Edit using VSCode after [installation](#installation). Routes, models, and public folders are included along with server file, db.js, service-worker.js, manifest.webmanifest and package.json files. This application is deployed to Heroku, see [links](#Links) section below.

---

## Building the Application

The assignment for this application was to convert it to a PWA application so that it can be utilized both online and offline. To do this, I had to add a manifest, service worker and a cache for the database. This was accomplished by adding the manifest.webmanifest, db.js and service-worker.js files and their contents. I also updated the connection in order to deploy to Heroku.

---

## Acceptance Criteria

GIVEN a user is on Budget App without an internet connection :heavy_check_mark:
WHEN the user inputs a withdrawal or deposit :heavy_check_mark:
THEN that will be shown on the page, and added to their transaction history when their connection is back online. :heavy_check_mark:

---

## Credits

As always, a huge thanks to our instructional staff for all their hard work!

## Resources

- [w3schools](https://www.w3schools.com)
- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose.js](https://mongoosejs.com/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- [Morgan.js](https://www.npmjs.com/package/morgan)
- [Heroku](https://heroku.com)

---

## Contact

Find me on LinkedIn Here:
[Aimee Esler](https://www.linkedin.com/in/aimee-esler-3bb31288/)

## Links

[Repository Link](https://github.com/aimeecesler/budget-tracker)

[Deployed Application](https://ace-budget-tracker.herokuapp.com/)

---

## License

Copyright &copy; 2020 Aimee Corbin Esler

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
