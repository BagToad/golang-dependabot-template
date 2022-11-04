# golang-dependabot-template

1. Enable Dependabot.

2. Edit `go.mod`.

3. Change the `require` to a vulnerable dependency. Change the dependency name and version, but do not remove `+incompatible`, else Dependabot will likely not produce an alert. This is required in lieu of a codebase using the dependency. 
  ```
  require github.com/owner/repo v0.0.0+incompatible // indirect
  ```
  
