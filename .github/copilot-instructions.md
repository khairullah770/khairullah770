# GitHub Copilot Instructions

This repository uses **Claude Sonnet** as the preferred AI model for GitHub Copilot.

## Accessing Claude Sonnet in VS Code

To use Claude Sonnet with GitHub Copilot in VS Code:

1. **Ensure your subscription supports it** – Claude Sonnet is available on GitHub Copilot Free, Pro, Business, and Enterprise plans.
2. **Update your extensions** – Make sure the [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) and [GitHub Copilot Chat](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat) extensions are up to date.
3. **Select the model** – In the Copilot Chat panel, click the model picker (shown as the current model name near the chat input) and choose **Claude Sonnet**.
4. **Use the workspace setting** – This repository includes a `.vscode/settings.json` that sets Claude Sonnet as the default model so it is selected automatically when you open this project.

## Troubleshooting

- If Claude Sonnet does not appear in the model picker, sign out and sign back in to GitHub in VS Code (`GitHub: Sign Out` then `GitHub: Sign In` from the Command Palette).
- Confirm that your GitHub account has an active Copilot subscription at <https://github.com/settings/copilot>.
- Restart VS Code after updating extensions or changing settings.
