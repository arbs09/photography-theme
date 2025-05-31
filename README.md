# photography website theme

## Installation

Initialise git:

```bash
git init
```

Add this theme to the `themes` folder:

```bash
git submodule add --depth=1 https://github.com/arbs09/photography-theme.git themes/photography
git submodule update --init --recursive
```

You can now enable the theme in your `config.toml`:

```toml
theme = "photography"
```

## Updating

Just run:

```bash
git submodule update --remote --merge
```
