# Budget Tracker

This a budget tracker application to allow for offline access and functionality. The user will be able to add expenses and deposits to their budget with or without a connection. If the user enters transactions offline, the total should be updated when they're brought back online.

## Table of contents

- [Installation](#installation)
- [Application Criteria](#application-criteria)
- [Links](#links)
- [Tools Used](#tools-used)
- [Application Gif](#application-gif)
- [License](#license)

## Installation

The JSON file will have the necessary dependencies. Type this in your command line:

```
npm i
```

Start the application :

```
npm start
```

Open in prefered browser

## Application Criteria

GIVEN a budget tracker without an internet connection

- WHEN the user inputs an expense or deposit
  THEN they will receive a notification that they have added an expense or deposit
- WHEN the user reestablishes an internet connection
  THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated

## Links

- [Github Repository](https://github.com/MtendeRoll/social-networkAPI)
- [Deployed Application]()

## Tools Used

- [Express JS](https://www.npmjs.com/package/express)
- [Mongoose](https://www.npmjs.com/package/mongoose)

## Application Gif

- ![Mock-Up]()

## License

- [MIT](./LICENSE)

MIT License Copyright (c) [2022] Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
