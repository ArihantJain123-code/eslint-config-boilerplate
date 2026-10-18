# ESLint Sharable Config Boilerplate

This repository provides a starter for creating a sharable ESLint config.

## Usage

1. Install (example):
   ```bash
   npm install --save-dev eslint your-config-package
   ```

2. Enable in your project .eslintrc:
   ```json
   {
     "extends": "your-config-package"
   }
   ```

## Customizing

- Modify the rules in `.eslintrc.js` to fit your style guide.
- Add plugin dependencies to package.json as needed (e.g. `eslint-plugin-react`, `@typescript-eslint/eslint-plugin`).

## Contributing

- Create a branch for your changes, run tests/lint, and open a pull request targeting `master`.
