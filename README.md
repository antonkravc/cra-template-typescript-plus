# cra-template-typescript-plus

Extended Typescript template for [Create React App](https://github.com/facebook/create-react-app).

Added/modified files:

| Path                      | Description                                                 |
| ------------------------- | ----------------------------------------------------------- |
| `.github/dependabot.yml`  | Dependabot configuration                                    |
| `.vscode/extensions.json` | Recommended VS Code extensions                              |
| `.vscode/settings.json`   | Default VS Code project settings                            |
| `gitignore`               | Extended .gitignore for React, VS Code, Webstorm and ESLint |
| `.prettierignore`         | Prettier ignore files                                       |

Added scripts:

| Name              | Description                             |
| ----------------- | --------------------------------------- |
| `format`          | Format all source with Prettier         |
| `lint`            | Lint all source with ESLint             |
| `check-types`     | Check types with tsc                    |
| `validate-source` | Run all scripts without modifying files |
