# Setup Guide

## Prerequisites

Before starting this course, ensure you have the following installed:

### Required
- **Rust** (latest stable version)
  ```bash
  curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
  ```
- **Cargo** (comes with Rust)
- **Make** (for running Makefiles)

### Optional
- **VS Code** with Rust Analyzer extension
- **Git** for version control

## Installation Steps

### 1. Install Rust

If you haven't already, install Rust:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Then activate the tools:
```bash
source $HOME/.cargo/env
```

### 2. Verify Installation

Check that Rust and Cargo are properly installed:

```bash
rustc --version
cargo --version
```

### 3. Clone the Repository

```bash
git clone https://github.com/username/rust-data-course
cd rust-data-course
```

### 4. Navigate to a Module

```bash
cd content/module-1
```

### 5. Build and Run

Use the provided Makefile:

```bash
make build
make run
```

Or use Cargo directly:

```bash
cargo build
cargo run
```

## Troubleshooting

### Issue: Rust not found
**Solution:** Make sure you've activated the environment by running `source $HOME/.cargo/env`

### Issue: Cargo command not found
**Solution:** Reinstall Rust using the installation command above and verify with `cargo --version`

### Issue: Make command not found (macOS)
**Solution:** Install Xcode Command Line Tools: `xcode-select --install`

## Next Steps

Once setup is complete, start with [Module 1](./modules.md#module-1) to begin the course!
