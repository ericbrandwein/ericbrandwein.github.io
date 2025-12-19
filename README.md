# ericbrandwein.github.io
My personal webpage

## Running
1. Install Ruby and stdlib. In Arch Linux:
```bash
pacman -S ruby ruby-stdlib ruby-bundler
```

2. Install dependencies with bundler.
```bash
bundler install
```

3. Run the server.
```bash
bundler exec jekyll serve --livereload
```