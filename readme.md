# Welcome to our Under the Sea game!


## Dependencies

### Update npm and install dependencies

```bash
npm update
npm install
```

### Installing serve

```bash
npm i serve -g
npm add serve
```

### Installing cypress

```bash
npm install cypress --save-dev
npm install -g @cypress/chrome-recorder
```

### Start

1. Start the server
   ```bash
   serve
   ```
2. Browse to [http://localhost:3000](http://localhost:3000)

#### Start test server

The server must be running locally with test configuration for the
integration tests to pass.

```bash
npm run 3030
```

<!-- npm install cypress --save-dev
npx cypress open -->

### Test

- Run all cypress tests
  ```bash
  npm run test
  ```
- Run a check
  ```bash
  npx cypress run --spec <FILE PATH>
  ```
