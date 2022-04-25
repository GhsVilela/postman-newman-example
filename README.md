## Newman Installation

Use the package manager [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) to install newman.

```bash
npm install -g newman
```

## Installation Newman Reporter HTML (Optional)

Use the package manager [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) to install newman reporter html.

```bash
npm install -g newman-reporter-htmlextra
```

## Running All Tests

```bash
newman run tests/postman_collection.json
```

## Running with HTML Reporter

```bash
newman run tests/postman_collection.json -r htmlextra --reporter-htmlextra-export testResults/htmlreport.html --reporter-htmlextra-darkTheme
```
