# PaperMC Theme

I made this theme for Hugo for a single page landing site for a personal project. Not really production ready, but feel free to use it. Inspired by, you guessed it, the PaperMC minecraft server.

<p align="center">
  <img src="/memes/meme.jpg" alt="My mind when making this.">
</p>

## Features

1. Looks Nice :>
2. SCSS
3. That's it ://

## Installation

1. As usual:
```bash
git clone https://github.com/nart4hire/PaperMCTheme.git themes/papermc
```
or
```bash
git submodule add https://github.com/nart4hire/PaperMCTheme.git themes/papermc
```
2. Change the hugo.toml
```toml
theme = "papermc"
```

## Configuration

- Default configurations are in the hugo.toml that comes with the repo.
- I didn't make support for pages or any taxonomies, so you'll have to add it if you need it.
- The repo comes with a default archetype, delete the default one that comes with initializing a Hugo project to use it.
- The repo comes with a default "_index.md" content, you'll need to overwrite that by adding new content with the same name.
```bash
hugo new content _index.md
```
