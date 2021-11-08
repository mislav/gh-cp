# gh cp

A GitHub CLI extension to copy a file from a GitHub repository locally without cloning the repository.

```sh
$ gh extension install mislav/gh-cp

$ gh cp
Usage: gh cp <repo> <path> <dest>

$ gh cp cli/cli pkg/findsh/find_windows.go .

$ head find_windows.go
package findsh

import (
        "os"
        "path/filepath"

        "github.com/cli/safeexec"
)

func Find() (string, error) {
```
