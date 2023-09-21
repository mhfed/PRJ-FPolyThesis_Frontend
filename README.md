# <strong> PROJECT-FPOLY-THESIS-FRONTEND </strong>

# Setup

- We use [bun](https://bun.sh/) for package management. Install bun: `npm install -g bun`

# Command

- Install dependencies: `bun install`
- Run the development server: `bun dev`
  > #### Detail command: Read script of package.json file

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

---

# Contributing

### <strong>Commit Message Format</strong>

```
<type>(<scope>): <subject>
```

We have very precise rules over how our git commit messages can be formatted. This leads to **more
readable messages** that are easy to follow when looking through the **project history**.

Each commit message consists of a **type**, a **subject** .

Any line of the commit message cannot be longer 100 characters! This allows the message to be easier

> ### Ex:

```
feat: create login screen
```

```
docs: update changelog to beta.5
```

```
fix: need to depend on latest rxjs and zone.js
```

## Type

> ### Must be one of the following:

- **build**: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
- **ci**: Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)
- **docs**: Documentation only changes
- **feat**: A new feature
- **fix**: A bug fix
- **perf**: A code change that improves performance
- **refactor**: A code change that neither fixes a bug nor adds a feature
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- **test**: Adding missing tests or correcting existing tests

## Importance before commit

> ### <strong>You must fix all bug of ESLint </strong>

### `bun lint`

> ### <strong>You must format all your change file </strong>

### `bun format`

### `bun format:fix`

> ### <strong>You must config git Username/Email</strong>
