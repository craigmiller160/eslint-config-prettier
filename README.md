# eslint-config-prettier

The ESLint configuration for integrating with Prettier.

## How to Use

Install the library with `yarn add --dev @craigmiller160/eslint-config-prettier`. Then extend the config in your `.eslintrc.js`:

```
module.exports = {
    extends: [
        '@craigmiller160/eslint-config-prettier'
    ]
};
```

## Requirements

This library requires ESLint and Prettier to both already be installed and setup in the consuming project.
