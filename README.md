# GNOME Extension: GitHub Notifications

Integrate github's notifications within the gnome desktop environment.

## Development

**Required tools:**
* [`just`](https://just.systems/)
* [`cargo`](https://www.rust-lang.org/)
* [`node`](https://nodejs.org/)
* [`pnpm`](https://pnpm.io/)
* [`jq`](https://jqlang.github.io/jq/)

### List all tasks

```sh
just --list
```

### Build

```sh
just build
```

### Install

```sh
just install
```

## FAQs

### Why does this extension require a binary?

I don't want to deal with `libsoup` API, so I write a Rust program to interact with GitHub server.

## Credits

This is a fork of https://github.com/alexduf/gnome-github-notifications that supports (only) GNOME 45.

## License

[GPL-2.0](https://github.com/KSXGitHub/gnome-shell-extension-github-notifications/blob/master/LICENSE).
