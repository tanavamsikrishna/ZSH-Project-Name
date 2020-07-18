# ZSH "Project Name"
This is a zsh plugin to update `.envrc` of direnv with project name information from a git repository
## Usage
With zinit (to be added after any direnv loading section in `zshrc`)
```zsh
zinit ice src"project_name" wait silent
zinit light project_name
```
