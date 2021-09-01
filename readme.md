## This repo contains code for step by step implementation of react project without using create-react-app.

### Steps followed:

- Set up basic html project and add react using cdn
- Do npm init.
- **Add prettier**:
  - Prettier is a code formatting tool used to maintain a standard code format across entire code base.
  - Create a file .prettierrc and add empty object. This will add default configuration.
  - Add a format script in package.json.
  - "format" : "prettier --write regex-to-select-js-jsx-files"
  - execute npm run format to run prettier.
- **Add ESLint**:
  -
