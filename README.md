# golang-dependabot-template

Edit `go.mod`.

Change the `require` to a vulnerable dependency:

```
require github.com/owner/repo v0.0.0+incompatible // indirect
```

Change the dependency name and version, but do not remove `+incompatible`, else Dependabot will likely not produce an alert. This is required in lieu of a codebase using the dependency. 
