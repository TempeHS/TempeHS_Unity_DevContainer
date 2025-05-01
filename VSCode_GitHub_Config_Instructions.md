# VSCode GitHub Config Instructions

1. Log in to GitHub in VSCode

<img src="https://code.visualstudio.com/assets/docs/sourcecontrol/intro/vscode-accounts-menu.png" width="300" />

  1. Choose `Backup and sync settings`
  2. Click the `Sign in` button that appears in the top menu
  3. Choose 'GitHub from the menu options
  4. Authenticate in the browser

2. Open a PowerShell Terminal

<img src="https://learn.microsoft.com/en-us/powershell/docs-conceptual/learn/ps101/media/figure1-1.jpg" width="300"/>

3. Apply the following commands, replacing `your@school.email` with your GitHub email address and replacing `username` with your GitHub username.

```bash
git config --global user.email "your@school.email"
git config --global user.name "username"
```

4. Once these steps have been followed, you can commit, push and pull from VSCode using the 'Source Control' menu. On your first commit, you may need to authenticate through the browser.

<img src="https://code.visualstudio.com/assets/docs/sourcecontrol/intro/source-control-view.png" width="300" />
