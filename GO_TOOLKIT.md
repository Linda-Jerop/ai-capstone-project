# Prompt-Powered Kickstart: Building a Beginner’s Toolkit for Go (Golang)

## 1. Title & Objective
**Getting Started with Go (Golang) – A Beginner’s Guide**

- **Technology Chosen:** Go (Golang)
- **Why:** Go is a modern, statically typed, compiled language designed for simplicity and efficiency. It’s widely used for backend services, cloud infrastructure, and command-line tools.
- **End Goal:** Run a minimal "Hello World" Go program and understand the basics of Go setup and execution.

## 2. Quick Summary of the Technology
- **What is Go?**
  - Go is an open-source programming language developed by Google. It emphasizes simplicity, concurrency, and fast compilation.
- **Where is it used?**
  - Web servers, cloud services, DevOps tools, and scalable backend systems.
- **Real-world example:**
  - Docker, Kubernetes, and Terraform are all written in Go.

## 3. System Requirements
- **OS:** Linux, Mac, or Windows
- **Tools/Editors:** VS Code (recommended), any text editor
- **Packages:** Go (latest stable version)

## 4. Installation & Setup Instructions
### Install Go (Linux example)
```sh
# Download and install Go
sudo apt update
sudo apt install golang-go
# Verify installation
go version
```

### Set up your first Go project (You can name it anything, I named mine something different)
```sh
mkdir hello-go
cd hello-go
```

## 5. Minimal Working Example
**Description:**
A simple Go program that prints "Hello, World!" to the terminal.

**Code:**
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

**How to run:**
```sh
go run main.go
```
**Expected output:**
```
Hello, World!
```

## 6. AI Prompt Journal
- **Prompt used:**
  - "How do I install Go on Linux and run a Hello World program?"
- **AI’s response summary:**
  - Provided step-by-step installation and a sample Hello World code.
- **Helpfulness:**
  - Very helpful for quick setup and understanding Go basics.

## 7. Common Issues & Fixes
- **Issue:** `go: command not found`
  - **Fix:** Ensure Go is installed and your PATH includes Go’s bin directory.
- **Issue:** Permission denied during install
  - **Fix:** Use `sudo` for installation commands.

## 8. References
- [Official Go Documentation](https://golang.org/doc/)
- [Go by Example](https://gobyexample.com/)
- [Tour of Go](https://tour.golang.org/)
- [Go Installation Guide](https://golang.org/doc/install)
