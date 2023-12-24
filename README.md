# eslint-config-davidinoa

ESLint configuration based on David's personal coding preferences, extending the Airbnb ESLint ruleset. Ideal for TypeScript and React projects looking for a robust and opinionated style guide.

## Installation

First, install eslint-config-davidinoa and its peer dependencies:

```bash
npx install-peerdeps --dev eslint-config-davidinoa
```

This will install eslint-config-davidinoa along with the required ESLint plugins and configurations.

## Usage

After installation, you can use the configuration in your project by adding it to your `.eslintrc` or eslintConfig field in your `package.json`.

This configuration is designed for use in TypeScript projects. Ensure that your project has a `tsconfig.json` file at its root, as this configuration requires it for TypeScript rules to function correctly.

Example .eslintrc configuration:

```json
{
  "extends": ["davidinoa"],
  "rules": {
    // Your project-specific rules or overrides
  }
}
```

Example package.json configuration:

```json
"eslintConfig": {
  "extends": ["davidinoa"]
}
```

## Peer Dependencies

This package extends the Airbnb ESLint ruleset and requires the following peer dependencies:

- `typescript`
- `@typescript-eslint/eslint-plugin`
- `@typescript-eslint/parser`
- `eslint`
- `eslint-config-airbnb`
- `eslint-config-airbnb-typescript`
- `eslint-plugin-import`
- `eslint-plugin-jsx-a11y`
- `eslint-config-prettier`
- `eslint-plugin-react`
- `eslint-plugin-react-hooks`

These are automatically installed when using the `install-peerdeps` command.

## Contributing

If you have suggestions for how eslint-config-davidinoa could be improved, or want to report a bug, open an issue or a pull request on the repository.

## License

This ESLint configuration is open-sourced software licensed under the MIT license.
