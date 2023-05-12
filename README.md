# Partial Git Clone Script

This script allows you to partially clone a Git repository by specifying a branch and a folder within the repository. It's particularly useful when you only want to work with a specific part of a repository and not clone the entire repository.

## Features

- Clones a specific branch from the repository
- Supports shallow cloning for faster cloning
- User input validation and error handling

## macos users can also install using brew

```bash
brew tap BalliAsghar/apps
brew install pc
```

## Usage

1. Make sure you have git and wget installed on your system.
2. Download the script and make it executable:
   ```bash
   chmod +x pc
   ```
3. Run the script:
   ```bash
   ./pc
   ```
4. Follow the prompts to enter the repository URL, depth, branch, and folder you want to clone.
