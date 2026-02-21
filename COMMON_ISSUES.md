# Common Issues & Fixes for Go Beginners

## 1. `go: command not found`
- **Fix:** Ensure Go is installed. Add Go’s bin directory to your PATH.
  - Example:
    ```sh
    export PATH=$PATH:/usr/local/go/bin
    ```

## 2. Permission denied during install
- **Fix:** Use `sudo` for installation commands on Linux/Mac.

## 3. File not found: main.go
- **Fix:** Make sure you are in the correct directory and the file exists.

## 4. Outdated Go version
- **Fix:** Download and install the latest version from the [official Go website](https://golang.org/dl/).

## Running the app; error: stat main.go no such file or directory
- **Fix** On your terminal, make sure you are in the folder in which the file is in, then run ```go run main.go``` again in terminal.

## Helpful Links
- [StackOverflow Go tag](https://stackoverflow.com/questions/tagged/go)
- [Go Installation Guide](https://golang.org/doc/install)
