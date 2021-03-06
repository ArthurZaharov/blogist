# Sample application

## Getting Started

### Prepare dependencies

Some gems may have native extensions, so you must have GCC installed on your development environment.
Then, your need to install software dependencies:

Using macOS:

```bash
brew tap Homebrew/bundle
brew bundle
```

### Bootstrap and run application

1. Clone application repository
```bash
git clone git@github.com:ArthurZaharov/blogist.git
```

2. Run setup script

```bash
bin/setup
```

3. Run test and quality suits to make sure all dependencies are satisfied and applications works correctly before making changes.

```bash
bin/tests
```

4. Run application

```bash
bin/server
```
