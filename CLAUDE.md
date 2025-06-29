# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Language Instructions

英語で思考して、日本語で答えるようにしてほしいです

## Project Overview

This is a Go study project (`gostudy`) for learning Go programming language fundamentals and best practices.

## Development Commands

Since this is a Go project, the following commands will likely be needed as the project develops:

```bash
# Initialize Go module (when first Go files are added)
go mod init gostudy

# Build the project
go build ./...

# Run tests
go test ./...

# Run tests with verbose output
go test -v ./...

# Run a specific test
go test -run TestFunctionName

# Format code
go fmt ./...

# Lint code (requires golangci-lint installation)
golangci-lint run

# Run the main program (when main.go exists)
go run main.go
```

## Code Architecture

This project is currently in its initial setup phase. As Go code is added, the typical structure would include:
- `main.go` - Entry point for executable programs
- Package directories organized by functionality
- `*_test.go` files alongside source files for testing

## Go Development Notes

- Follow standard Go project layout conventions
- Use `go fmt` to maintain consistent code formatting
- Write tests alongside source code using the `*_test.go` naming convention
- Use meaningful package names and organize code logically