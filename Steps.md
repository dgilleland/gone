# Steps to Reproduce

```ps
# 1. Create a new vite project in the current folder
pnpm create vite
# Answer the prompts in the following way:
√ Project name: ... .
√ Current directory is not empty. Please choose how to proceed: » Ignore files and continue
√ Select a framework: » Vanilla
√ Select a variant: » JavaScript

# 2. Copy the contents of the `.gitignore` file to a new blank file in VS Code (but don't save the file!)

# 3. We want to revert the changes that were made to the `.gitignore` file. To do this, we can use the `git checkout` command.
git checkout <yoursha> -- .gitignore

# 4. Paste the contents of your blank file's `.gitignore` file onto the **end** of the current `.gitignore` file in the project folder.

# 5. Add in `vitest`

```