# Minimal Blog

This is the home of my portfolio sites of sort. Yeehaa!

## Dependencies

This blog depends on zola, html-tidy, and the typescript compiler via npm. Sass
compilation is handled by zola so no need for a separate sass compiler. Run the
following to install dependencies.

If you have [nix](https://nixos.org/) the package manager, or in a NixOS, you
can just run:

```sh
nix-shell
npm install
```

If not, install the dependencies manually:

- Install [zola](https://www.getzola.org/documentation/getting-started/installation/)
- Install [html-tidy](https://www.html-tidy.org/)
- Install other dependencies via npm:

```sh
npm install
```

## Development

To run the local server

```sh
zola serve
```

To compile typescript files as you modify them:

```sh
npx tsc -w
```

### Writing a New Post

Just add a new markdown document under the `content/posts` directory.

**TODO:** Create a script to automate this.


## Deployment

To publish:

```sh
zola build
```

```bash
$ yarn deploy
```

## Features

On the site, to see the baseline grid, press the `Ctrl+g` key.

