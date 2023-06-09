## Setup

Make sure you have nodejs installed (>= v.16):

```bash
node -v
```

Setup the project specifications you want:

### Basic
```bash
yarn setup_basic
```

### Advanced

```bash
PROJECT_NAME=<your project name> yarn setup_advanced
```

## Development Server

Start the development server on http://localhost:3000

```bash
yarn dev
```

## Production

Build the application for production:

```bash
yarn run build
```

Locally preview production build:

```bash
yarn run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
