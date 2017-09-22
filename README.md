# PennMutual ESLint JavaScript Code Style

This is a sharable ESLint configuration. [You can learn more about them here.](https://eslint.org/docs/developer-guide/shareable-configs)

## Use

In your .eslintrc.json file for your project, have the following:

    {
      "extends": "pml"
    }

## Dependencies

This requires eslint-plugin-standard and eslint-config-standard, and therefore has transitive peer dependencies. Pay attention to the warnings when installing. Install those modules as well. When running ESLint, that will bomb out if you don't have all the dependencies installed. Read the error messages and install the required dependencies. Yes it's annoying, but it's the way plugins are supposed to work.
