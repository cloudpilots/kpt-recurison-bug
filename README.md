# kpt-recursion-bug

## Description

This package shows an bug with recursive rendering.

## Usage

### Fetch the package

`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] kpt-recursion-bug`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content

`kpt pkg tree kpt-recursion-bug`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package

```bash
kpt fn render googleapis --truncate-output=false
```
