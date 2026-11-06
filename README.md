# git-config
Git configuration

## Cache Your Credentials on Windows
To avoid typing your username and token every time you push or pull, you can have Git store your credentials securely using the Windows Credential Manager.
Run this command in your Windows command line (Command Prompt or PowerShell) to enable the credential helper:
```bash
git config --global credential.helper manager
```
