# Go + Gin Starter Project

A clean and modular starter project using [Go](https://golang.org/) and the [Gin](https://github.com/gin-gonic/gin) web framework.

---

## 🚀 Prerequisites

Make sure you have Go installed:

### 🧰 Install Go (if not already installed)

- Download and install from: [https://go.dev/dl](https://go.dev/dl)
- Verify installation:

```bash
go version

go.mod -> This file defines your Go module.

It tracks:
    1. The module name
    2. Your project's Go version
    3. All your direct dependencies

go.sum -> This file ensures dependency integrity and security.

1. It records checksums (hashes) of all downloaded module versions and their go.mod files.

2. It is created automatically when you:
    2.1. Run go mod tidy, go build, or go get
    2.2. And have dependencies in go.mod

Why it matters:

1. Verifies that your dependencies are authentic and unchanged

2. Ensures reproducible builds across different environments

3. Protects against supply chain attacks

You should always commit both go.mod and go.sum to your version control