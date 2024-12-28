# Development Guide

This document provides guidelines for developing Chromensics.

## Development Environment Setup

1. Install Go
```bash
curl -LO https://golang.org/dl/go<version>.linux-amd64.tar.gz
sudo tar -C /usr/local -xzf go<version>.linux-amd64.tar.gz
set -Ux PATH /usr/local/go/bin $PATH
go version
```

2. Install development dependencies
```bash
go mod init
go mod tidy
```