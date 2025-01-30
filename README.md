# Go Map Access Panic

This repository demonstrates an uncommon error in Go related to accessing elements in a map before it has been initialized.  Attempting to access a key in an uninitialized map will result in a runtime panic.

The `bug.go` file contains the code that causes the panic. The `bugSolution.go` file provides the corrected code.

## How to reproduce

1. Clone this repository.
2. Navigate to the directory.
3. Run `go run bug.go`.

You will see a runtime panic.

## Solution

The solution is to initialize the map before attempting to access its elements. See `bugSolution.go` for the corrected code.